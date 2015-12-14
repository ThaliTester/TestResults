#### Test 50650278e3ff7c2_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/AlertReceiver( 5991): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
--------- beginning of system
I/ActivityManager(  837): Killing 5783:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/InitNotificationRingtoneService( 5991): Start InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 5991): onHandleIntent
D/HolidayDataLoader( 5991): readJsonAsset : holiday.json
I/AlertUtils( 5991): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
W/libprocessgroup(  837): failed to open /acct/uid_10069/pid_5783/cgroup.procs: No such file or directory
I/AlertUtils( 5991): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
E/AgendaWidgetManager( 5991): [updateWidgets] 
D/MonthWidgetProvider( 5991): [onReceive]
D/CalendarWidgetProvider( 5991): [onReceive]
D/CalendarWidgetProvider( 5991): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5991): [onCreate] mContext.getPackageName() = com.android.calendar
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
D/WeekWidgetProvider( 5991): [onReceive]
D/CalendarWidgetProvider( 5991): [onReceive]
D/CalendarWidgetProvider( 5991): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/AlertService( 5991): 0 Action = android.intent.action.PROVIDER_CHANGED
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AudioManager( 5122): getMode name:com.lge.qremote
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
D/CalendarTypeController( 5991): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5122): getMode name:com.lge.qremote
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
E/HolidayIntentService( 5991): onHandleIntent:holiday data empty
I/art     (  837): Explicit concurrent mark sweep GC freed 28508(1472KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.105ms total 171.082ms
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5991): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5991): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/ActivityManager(  837): Killing 5321:com.google.android.talk/u0a61 (adj 15): empty #11
I/AlertUtils( 5991): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 5991): End InitializeAlertRingtoneService.onHandleIntent
W/libprocessgroup(  837): failed to open /acct/uid_10061/pid_5321/cgroup.procs: No such file or directory
D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/AndroidRuntime( 6021): 
D/AndroidRuntime( 6021): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6021): CheckJNI is OFF
I/ActivityManager(  837): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6035 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ResourcesManager( 6035): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5685): Internal timer expired: 1
D/AndroidRuntime( 6021): Calling main entry com.android.commands.am.Am
I/ActivityManager(  837): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  837): setTaskToReturnTo : TaskRecord{367005ca #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  837): setTaskToReturnTo : TaskRecord{367005ca #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  837): AppWindowTokenEx init.. 
D/ContextHelper(  837): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  837): Focus left window: Window{334c454 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6021): Shutting down VM
D/SplitWindow(  837): check instance of lgWin Window{3ea46404 u0 Starting com.test.thalitest}
I/ActivityManager(  837): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6069 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     ( 6035): CheckpointMarkThreadRoots callback created = 0xb042d3c0
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 323us total 22.257ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.660ms
I/art     ( 6035): CheckpointMarkThreadRoots callback created = 0xb042d390
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.867ms
W/art     ( 6035): Suspending all threads took: 7.465ms
I/HotwordDetector( 1932): Closing mic
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
I/MicrophoneInputStream( 1932): mic_close com.google.android.apps.gsa.speech.audio.u@c1bad8e
V/AudioRecord( 1932): stop()
D/AudioRecord( 1932): AudioRecord->stop()
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
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb4297000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/WindowStateAnimator(  837): Starting window displayed
I/SystemUI[Framework](  837): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  837): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  837): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  837): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@233bea84,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1370): draw background and invalidate : color = 11000000
D/BarTransitions( 1370): draw background and invalidate : color = f0e0e0e
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  282): disable_audio_route: exit
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
,I/Babel_SMS( 6035): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6035): MmsConfig.loadMmsSettings
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb4297000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioRecord( 1932): stop()
V/AudioRecord( 1932): stop()
V/AudioRecord( 1932): stop()
V/AudioFlinger(  282): releasing 16 from 1932 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioSystem( 1997): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread 0xb4297000 exiting
V/AudioSystem(  837): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2084): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1747): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3130): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1932): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
I/Babel_SMS( 6035): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6035): MmsConfig.loadFromDatabase
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 1932, calling pid 282
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/HotwordRecognitionRnr( 1932): Stopping hotword detection.
E/Babel_SMS( 6035): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6035): MmsConfig.loadFromResources
E/Babel_SMS( 6035): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6035): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/HotwordRecognitionRnr( 1932): Hotword detection finished
D/SensorManager( 6035): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6035): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6035): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6035): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6035): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6035): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6035): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6035): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6035): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6035): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6035): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6035): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6035): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6035): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6035): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6035): found sensor: Motion Accel, handle=46
W/Settings( 6035): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6035): startup - clean
D/ContextHelper( 6069): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/Babel   ( 6035): deleted: false for 0
I/WebViewFactory( 6069): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  837): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6101 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/AudioCapabilities( 6035): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6035): Unsupported mime audio/adpcm
W/AudioCapabilities( 6035): Unsupported mime audio/g726
W/AudioCapabilities( 6035): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6035): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6035): Unsupported mime video/mjpg
I/LibraryLoader( 6069): Time to load native libraries: 3 ms (timestamps 3008-3011)
I/LibraryLoader( 6069): Expected native library version number "",actual native library version number ""
W/VideoCapabilities( 6035): Unsupported mime video/theora
V/WebViewChromiumFactoryProvider( 6069): Binding Chromium to main looper Looper (main, tid 1) {c323836}
I/LibraryLoader( 6069): Expected native library version number "",actual native library version number ""
I/chromium( 6069): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/AppUp4:AppBoxCP( 6101): onCreate
W/AppUp4:DB( 6101):  [AppBoxDatabaseHelper] construct
I/BrowserStartupController( 6069): Initializing chromium process, singleProcess=true
W/AudioCapabilities( 6035): Unsupported mime audio/evrc
W/art     ( 6069): Attempt to remove local handle scope entry from IRT, ignoring
W/AudioCapabilities( 6035): Unsupported mime audio/qcelp
I/AppUp4:DB( 6101):  setFingerPrint start
I/AppUp4:DB( 6101):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/VideoCapabilities( 6035): Unrecognized profile 2130706433 for video/avc
E/SysUtils( 6069): ApplicationContext is null in ApplicationStatus
I/AppUp4:DB( 6101):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6101):  SDK version = 0
I/AppUp4:DB( 6101):  beforefinger == newfinger no write in DB
W/AudioCapabilities( 6035): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6035): Unsupported mime audio/qcelp
W/AudioCapabilities( 6035): Unsupported mime audio/evrc
D/AppUp4:AppBoxApplication( 6101): AppBoxApplication onCreate()
W/VideoCapabilities( 6035): Unsupported mime video/mp4v-esdp
I/AppUp4:CustModeStarterReceiver( 6101): onReceive
I/AppUp4:CustModeStarterReceiver( 6101): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6101): Context : android.app.ReceiverRestrictedContext@3c42acf8
D/AppUp4:CustFacade( 6101): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6101): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6101): begin check event
I/AppUp4:CustModeStarterReceiver( 6101): Event For Nothing, skip.
I/ActivityManager(  837): Killing 5531:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/VideoCapabilities( 6035): Unsupported profile 4 for video/mp4v-es
W/chromium( 6069): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6069): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6069): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6069): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6069): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6069): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6069): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6069): Remote Branch: 
I/Adreno-EGL( 6069): Local Patches: 
I/Adreno-EGL( 6069): Reconstruct Branch: 
W/libprocessgroup(  837): failed to open /acct/uid_10086/pid_5531/cgroup.procs: No such file or directory
W/VideoCapabilities( 6035): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6035): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6035): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6035): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  837): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6127 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,V/AudioPolicyService(  282): registerClient() client 0xb40c6a80, uid 10316
,D/BluetoothManagerService(  837): Message: 20
D/BluetoothManagerService(  837): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31c9a15:true
D/BluetoothAdapterService(350331330)( 1997): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36374428
,I/GAV2    ( 5809): Thread[GAThread,5,main]: No campaign data found.
,W/ResourcesManager( 6127): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6127): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6127): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/NotificationManager( 6035): com.google.android.talk: cancel(8) by com.google.android.talk
,I/vclib   ( 6035): onServiceConnected
W/Babel   ( 6035): Attempted to change video mute state without an active call.
W/ResourcesManager( 6035): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6035): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6035): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppConfig( 6127): Total System Memory = 906309632
,W/art     ( 6069): Attempt to remove local handle scope entry from IRT, ignoring
I/GalleryUtils( 6127): Application Heap = 96 MB
I/AppConfig( 6127): App Tier : NOT_DEF
,D/SystemHelper( 6127): region [EU], country [EU], operator [OPEN], sub-operator []
W/AwContents( 6069): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6069): CordovaWebView is running on device made by: LGE
,W/System  ( 6035): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6035): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  837): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6166 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/art     ( 6069): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6069): Attempt to remove local handle scope entry from IRT, ignoring
I/NotificationManager( 6035): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/Activity( 6069): Activity.onPostResume() called 
,W/ResourcesManager( 6166): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/OpenGLRenderer( 6069): Render dirty regions requested: true
I/OpenGLRenderer( 6069): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6069): Enabling debug mode 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/Atlas   ( 6069): Validating map...
,D/SplitWindow(  837): check instance of lgWin Window{26f5683 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6069): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager(  837): Killing 5598:com.android.vending/u0a36 (adj 15): empty #11
,I/SystemConfig( 6166): BUILD Country: EU
I/SystemConfig( 6166): BUILD Operator: OPEN
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 93758358719; DSPS: 3170358; Offset : -2994886337
,W/libprocessgroup(  837): failed to open /acct/uid_10036/pid_5598/cgroup.procs: No such file or directory
,D/InputDispatcher(  837): Focus entered window: Window{26f5683 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  837): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6192 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  837): Killing 5853:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  837): failed to open /acct/uid_10009/pid_5853/cgroup.procs: No such file or directory
,I/SystemConfig( 6166): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6166): existFile = false
I/SystemConfig( 6166): canReadFile = false
I/SystemConfig( 6166): systemFeature RCS result false
D/SystemConfig( 6166): refreshRcsSupport() :false
W/InputMethodManagerService(  837): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  837): Displayed com.test.thalitest/.MainActivity: +1s514ms
,I/Timeline(  837): Timeline: Activity_windows_visible id: ActivityRecord{13b2333b u0 com.test.thalitest/.MainActivity t220} time:93939
I/Timeline( 6069): Timeline: Activity_idle id: android.os.BinderProxy@1929147d time:93950
I/LockScreenSettings( 6192): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6192): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6192): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6192): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6192): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6192): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,W/BindingManager( 6069): Cannot call determinedVisibility() - never saw a connection for the pid: 6069
,I/ActivityManager(  837): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6213 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  837): Killing 5893:com.google.android.configupdater/u0a3 (adj 15): empty #11
I/ActivityManager(  837): Process com.google.android.gm (pid 5809) has died
,W/ActivityManager(  837): Unbind failed: could not find connection for android.os.BinderProxy@227e2d8c
W/libprocessgroup(  837): failed to open /acct/uid_10003/pid_5893/cgroup.procs: No such file or directory
W/ResourcesManager( 6213): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/JsMessageQueue( 6069): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  837): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=6237 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  837): RTC_WAKEUP set : Alarm{3e01bf18 type 0 when 1450100288898 com.android.vending} when 1450100288898
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/UpdateIcingCorporaServi( 1932): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/art     ( 3939): Explicit concurrent mark sweep GC freed 3089(122KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 485us total 32.685ms
,I/UpdateIcingCorporaServi( 1932): UpdateCorporaTask done [took 79 ms] updated apps [took 79 ms] 
,D/jxcore_app_log( 6069): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618643456
D/JX-Cordova( 6069): jxcore cordova android initializing
,I/ActivityManager(  837): Process com.lge.qremote (pid 5122) has died
,D/UEI.SmartControl( 5685): Service.onUnbind: IControl
D/UEI.SmartControl( 5685): Service.onDestroy
D/UEI.SmartControl( 5685): Shutdown IRRCPlayer... 
W/irrc_jni( 5685): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5685): ~IrrcClient ++ 
D/irrcClient( 5685): ~IrrcClient -- 
W/irrc_jni( 5685): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5685): Blaster closed
D/UEI.SmartControl( 5685): Blaster closed
D/UEI.SmartControl( 5685): Shut down QS...
D/UEI.SmartControl( 5685): Stopped file observer...
I/UEI.SmartControl( 5685): QS lib stop result = true
,D/UEI.SmartControl( 5685): QS shutdown complete
I/art     ( 6069): CheckpointMarkThreadRoots callback created = 0x9adba480
,D/Finsky  ( 6237): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/art     ( 6069): CheckpointMarkThreadRoots callback created = 0x9adba450
,D/Finsky  ( 6237): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6237): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6237): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6237): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3207): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@3e87f688 on behalf of 6237
D/Finsky  ( 6237): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/Finsky  ( 6237): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6237): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6237): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 6237): Skipping gmscore version check
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageBroadcastService( 4205): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6237): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  837): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6284 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 4205): Null package name or gms related package.  Ignoreing.
I/NotificationManager(  837): android: cancelAsUser(2) by android
,I/Icing   ( 4205): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6284): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/libc-netbsd( 6237): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6237): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6237): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6237): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6237): propertyValue:false
D/libc-netbsd( 6237): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6237): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     (  837): Explicit concurrent mark sweep GC freed 24290(1221KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.855ms total 188.086ms
,D/BluetoothManagerService(  837): Message: 20
D/BluetoothManagerService(  837): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@149c88af:true
,D/BluetoothAdapterService(350331330)( 1997): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36374428
D/BluetoothAdapterService(350331330)( 1997): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36374428
D/libc-netbsd( 6237): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6237): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AudioManager( 6284): getMode name:com.lge.qremote
,I/AudioManager( 6284): getMode name:com.lge.qremote
,I/ActivityManager(  837): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6307 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6307): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6307): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2eba8955
,D/CalendarProvider2( 6307): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6307): Created com.android.providers.calendar.CalendarAlarmManager@c323836(com.android.providers.calendar.CalendarProvider2@2eba8955)
D/CalendarProviderBroadcastReceiver( 6307): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6307): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6307): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6307): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6307): [getOrCreateCalendarAlarmManager]
,I/ActivityManager(  837): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6326 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/CalendarProvider2( 6307): [IntentService] Release Lock
,D/CalendarProvider2( 6307): CalendarProviderIntentService.onDestroy()
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  837): android: cancelAsUser(2) by android
,I/qtaguid ( 6237): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6237): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6237): untagSocket(41) failed with errno -22
D/Finsky  ( 6237): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  837): Process com.uei.lg.quicksetsdk.lite (pid 5685) has died
,I/ActivityManager(  837): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6346 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ActivityManager(  837): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  837): android: cancelAsUser(2) by android
,W/ResourcesManager( 6346): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6346): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AlertService( 5991): Beginning updateAlertNotification
,D/AlertService( 5991): No fired or scheduled alerts
,I/NotificationManager( 5991): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(2) by com.android.calendar
I/Gmail   ( 6326): getAccountsCursor
I/NotificationManager( 5991): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(6) by com.android.calendar
,I/NotificationManager( 5991): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(8) by com.android.calendar
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 5991): com.android.calendar: cancel(9) by com.android.calendar
,I/NotificationManager( 5991): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(16) by com.android.calendar
,I/NotificationManager( 5991): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5991): com.android.calendar: cancel(20) by com.android.calendar
W/GAV2    ( 6326): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/MultiDex( 6346): VM with version 2.1.0 has multidex support
I/MultiDex( 6346): install
I/MultiDex( 6346): VM has multidex support, MultiDex support library is disabled.
D/AlertService( 5991): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,V/JNIHelp ( 6346): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityManager(  837): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/AlarmScheduler( 5991): No events found starting within 1 week.
E/Gmail   ( 6326): Error finding the version of the Email provider.....
E/Gmail   ( 6326): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6326): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6326): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6326): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6326): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6326): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6326): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6326): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6326): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6326): getAccountsCursor
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 6237): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6237): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6237): untagSocket(41) failed with errno -22
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 4205): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/ActivityThread( 6346): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6346): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e87f688: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6346): Installed default security provider GmsCore_OpenSSL
W/jxcore-log( 6069): Initializing JXcore engine
,W/jxcore-log( 6069): JXcore engine is ready
I/ActivityManager(  837): Process com.android.calendar (pid 5991) has died
W/ActivityManager(  837): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/NotificationManager( 6346): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6346): com.google.android.gms: cancel(39789) by com.google.android.gms
,W/jxcore-log( 6069): Starting JXcore engine
I/Gmail   ( 6326): Observing account changes for notifications
,D/Icing   ( 4205): Loaded CLD2 Version V2.0 - 20141016
I/ActivityManager(  837): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6385 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  837): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/art     (  307): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 23.013ms
I/art     (  307): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.106ms
,I/Icing   ( 4205): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 24.201ms
I/ActivityManager(  837): Process com.lge.appbox.client (pid 6101) has died
,V/LGMDMManager( 6284): Create singleton instance
I/Gmail   ( 6326): notifyAccountChanged
,W/.test.thalitest( 6069): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7686]" dev="sockfs" ino=7686 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6069): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6069): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6423]" dev="sockfs" ino=6423 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6069): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6069): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6069): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29020]" dev="sockfs" ino=29020 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/Gmail   ( 6326): getAccountsCursor
,I/Gmail   ( 6326): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  837): Process com.google.android.setupwizard (pid 5966) has died
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6326): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/AudioManager( 6284): getMode name:com.lge.qremote
,I/art     ( 6237): CheckpointMarkThreadRoots callback created = 0x9dc13e40
,I/Gmail   ( 6326): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6326): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ChimeraCfgMgr( 6346): Reading stored module config
,I/art     ( 6237): CheckpointMarkThreadRoots callback created = 0x9dc13e00
D/UEI.SmartControl( 6385): Quickset Services start...
,I/UEI.SmartControl( 6385): Manufacture = LGE
D/UEI.SmartControl( 6385): File observer start...
E/UEI.SmartControl( 6385): IR Port is disabled: false
D/UEI.SmartControl( 6385): Starting file observer...
D/UEI.SmartControl( 6385): Extracting JNI libs...
D/UEI.SmartControl( 6385): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6385): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,I/ActivityManager(  837): Process com.android.gallery3d (pid 6127) has died
W/jxcore-log( 6069): Platform android
W/jxcore-log( 6069): 
W/jxcore-log( 6069): Process ARCH arm
W/jxcore-log( 6069): 
D/UEI.SmartControl( 6385): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6385): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/ChimeraCfgMgr( 6346): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/WearableService( 1729): callingUid 10006, callindPid: 1729
,E/MDM     ( 1729): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4205): Restart initialization of location
D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,I/UEI.SmartControl( 6385): --- Selecting new region: 2
I/UEI.SmartControl( 6385): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6385): Platform has CIR...
D/UEI.SmartControl( 6385): NO CIR support, need to check package...
,D/NativeLibraryUtils( 6346): Install completed successfully. count=14 extracted=0
I/UEI.SmartControl( 6385): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6385): QS Service created
W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
,V/AlarmManager(  837): RTC_WAKEUP set : Alarm{d050014 type 0 when 1450100291982 com.google.android.googlequicksearchbox} when 1450100291982
,E/UEI.SmartControl( 6385): QS start get config
I/Gmail   ( 6326): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 6385): Loading JNI Libs...
,D/UEI.SmartControl( 6385):  configuring local db...
D/CAR.SERVICE( 6346): Connecting to CarCallService...
,I/art     ( 6346): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6346): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6346): com.google.android.projection.gearhead isn't installed.
,D/UEI.SmartControl( 6385):  ---- Has DB8: true
,D/UEI.SmartControl( 6385): QS start statue = true Error code = 0
D/UEI.SmartControl( 6385): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6385): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/CAR.TEL.Service( 6346): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6346): Creating a new PhoneAdapter instance
W/ActivityManager(  837): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6346): setListener: com.google.android.gms.car.dn@13ddcef7
W/ActivityManager(  837): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6346): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6346): Starting CarCallService with initial phone null
D/UEI.SmartControl( 6385): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6385): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6385): IrrcClient ++ 
D/irrcClient( 6385): getIrrcService ++ 
,D/irrcClient( 6385): getIrrcService -- 
D/irrcClient( 6385): IrrcClient -- 
W/irrc_jni( 6385): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6385): Services init done
I/UEI.SmartControl( 6385): Device manager: loading config....
,D/CAR.SERVICE( 6346): Package validated; name: com.android.vending
D/UEI.SmartControl( 6385): QS Service init finished
,D/UEI.SmartControl( 6385): QS Service version name: 0.1.73
D/UEI.SmartControl( 6385): QS Service version code: 1073
D/UEI.SmartControl( 6385): Config is loaded...
D/UEI.SmartControl( 6385): Service requested: Control
D/UEI.SmartControl( 6385): Internal service binding...
D/UEI.SmartControl( 6385): -----IControl: 11
,D/UEI.SmartControl( 6385): Caller: com.lge.qremote
D/UEI.SmartControl( 6385): ------------ IControl registerCallback...
I/UEI.SmartControl( 6385): Registering callback...
D/UEI.SmartControl( 6385): -----IControl: 19
D/UEI.SmartControl( 6385):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6385): Notify AllClients services are ready: 0
I/NotificationManager( 6346): com.google.android.gms: cancel(10436) by com.google.android.gms
D/UEI.SmartControl( 6385): Caller: com.lge.qremote
I/UEI.SmartControl( 6385): Registering Services Ready callback...
I/UEI.SmartControl( 6385): Notify client services are ready...
D/UEI.SmartControl( 6385): -----IControl: 8
D/UEI.SmartControl( 6385): Caller: com.lge.qremote
,I/NotificationManager( 6237): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 6237): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/AudioManager( 6284): getMode name:com.lge.qremote
,I/AudioManager( 6284): getMode name:com.lge.qremote
,I/AudioManager( 6284): getMode name:com.lge.qremote
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  837): android: cancelAsUser(2) by android
,I/qtaguid ( 6237): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6237): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6237): untagSocket(41) failed with errno -22
,I/jxcore-log( 6069): JXcore Cordova bridge is ready!
I/jxcore-log( 6069): 
,W/jxcore-log( 6069): JXcore engine is started
,I/chromium( 6069): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 6069): Skipped 224 frames!  The application may be doing too much work on its main thread.
W/PackageSettings(  837): Skipping PackageSetting{1189c2bb com.example.hello/10030} due to missing metadata
,W/ResourcesManager( 6237): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6237): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6237): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6237): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 6237): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  837): RTC_WAKEUP set : Alarm{137c69dc type 0 when 1450100293281 com.android.vending} when 1450100293281
,I/art     (  837): Explicit concurrent mark sweep GC freed 19601(1157KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.131ms total 153.083ms
,D/DeviceConnectionService( 1729): client connected with version: 8296000
D/Finsky  ( 6237): [774] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  837): android: cancelAsUser(2) by android
,D/libc-netbsd( 6237): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6237): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6237): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6237): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6237): propertyValue:false
,I/ActivityManager(  837): Killing 6035:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_10061/pid_6035/cgroup.procs: No such file or directory
,I/jxcore-log( 6069): Toggling radios to true
I/jxcore-log( 6069): 
,D/BluetoothAdapter( 6069): enable(): BT is already enabled..!
D/WifiServiceImplEx(  837): setWifiEnabled: true pid=6069, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  837): setWifiEnabled: true pid=6069, uid=10316
,D/WifiServiceImplEx(  837): disconnect pid=6069, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  837): reconnect pid=6069, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6069): Radios toggled
I/jxcore-log( 6069): 
D/BluetoothManagerService(  837): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6069): Got Device Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 6069): 
I/jxcore-log( 6069): Perf Test app loaded loaded
I/jxcore-log( 6069): 
,I/jxcore-log( 6069): check test folder
I/jxcore-log( 6069): 
I/jxcore-log( 6069): found test : ./testFindPeers.js
I/jxcore-log( 6069): 
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2770): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2770): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  837): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  837): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/jxcore-log( 6069): found test : ./testSendData.js
I/jxcore-log( 6069): 
,D/WfdsMonitor( 1801): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/LGWifiP2pService(  837): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  837): P2pEnabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  837): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  278): Clearing all IP addresses on wlan0
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1729): Read error: ssl=0xaaee1000: I/O error during system call, Connection timed out
D/ConnectivityService(  837): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/WifiHS20(  837): hidePasspointNotification off =false
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  837): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 1729): SSL shutdown failed: ssl=0xaaee1000: I/O error during system call, Broken pipe
,D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:15.094 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  837): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,I/ActivityManager(  837): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6464 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): ValidatedState{ when=-5ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): DefaultState{ when=-19ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  837): Start Disconnecting Watchdog 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): Forcing reevaluation
D/WifiHS20(  837): hidePasspointNotification off =false
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  837): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  837): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2770): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:15.184 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/DhcpStateMachine(  837): StoppedState
,D/CommandListener(  278): Clearing all IP addresses on wlan0
D/ConnectivityService(  837): Default network via Wi-Fi disconnect. stop DSQN
D/DhcpStateMachine(  837): StoppedState{ when=-89ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/DSQN    (  837): disableDataServiceNotify
D/WifiHS20(  837): hidePasspointNotification off =false
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    (  837): stop dsqn bin
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:15.256 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/WifiNetworkAgent(  837): NetworkAgent: NetworkAgent channel lost
I/chromium( 6069): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/ConnectivityService(  837): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  837):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  837):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/WifiHS20(  837): hidePasspointNotification off =false
D/ConnectivityService(  837): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/Nat464Xlat(  837): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:15.281 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524292
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/CSLegacyTypeTracker(  837): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  837): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:15.288 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/ConnectivityService(  837): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  837): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  837): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  837): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  837): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1837): |CORE| No family connected
V/NetworkPolicy(  837): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1837): |CORE| No family connected
I/QCNEJ   ( 1837): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1837): |CORE| sendDefaultNwMsg: default = -1
D/ConnectivityService(  837): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  837): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  837): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  837):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt(  837): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  837): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  837): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  837): setSupplicantStateSCANNING
D/Tethering(  837): MasterInitialState.processMessage what=3
D/Tethering(  837): MasterInitialState.processMessage what=3
D/NetworkManagementService(  837): Removing idletimer
D/TelephonyNetworkFactory-1( 1747): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1747):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,W/Settings(  837): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  837): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6464): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6464): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6464): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6464): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6464): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/IndexDatabaseHelper( 6464): Using schema version: 115
,I/IndexDatabaseHelper( 6464): Index is fine
V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
,I/ActivityManager(  837): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6493 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  837): Killing 6166:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  837): failed to open /acct/uid_10018/pid_6166/cgroup.procs: No such file or directory
,I/PCSuite ( 6493): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6493): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6493): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/GAV2    ( 6326): Thread[GAThread,5,main]: No campaign data found.
,V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
I/PCSuite ( 6493): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6493): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6493): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  837): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6517 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  837): Killing 6192:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_10069/pid_6192/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2770): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,W/ResourcesManager( 6517): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LocSvc_java(  837): onReceive
,W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:16.333 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:16.337 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2770): wlan0: Associated with c0:ff:d4:d3:aa:48
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  837): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  837): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  837): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  837): setSupplicantStateASSOCIATED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:16.374 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  837): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  837): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:16.381 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/wpa_supplicant( 2770): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2770): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/WifiServiceExtension(  837): setVHTCapabilityType  : false
I/WifiServerServiceExt(  837): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  837): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  837): setSecurityType  : 2
,I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:16.438 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:16.45 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,D/ConnectivityService(  837): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  837): Got NetworkAgent Messenger
D/ConnectivityService(  837): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  837): NetworkAgent connected
,D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiConfigStore(  837): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  837): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Setting iface cfg
E/WifiStateMachine(  837): Start Dhcp Watchdog 2
D/DhcpStateMachine(  837): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  837): WaitBeforeStartState
D/WifiServerServiceExt(  837): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  837): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  837): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/Babel_SMS( 6517): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6517): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6517): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6517): MmsConfig.loadFromDatabase
,E/WifiStateMachine(  837): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  837): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  837): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15f5a222 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  837): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15f5a222 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  837): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
E/Babel_SMS( 6517): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6517): MmsConfig.loadFromResources
V/LgDhcpStateMachineHelper(  837): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
E/Babel_SMS( 6517): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6517): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/DhcpStateMachine(  837): DHCP Start wake lock is acquired.
D/CommandListener(  278): Setting iface cfg
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  837): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiServerServiceExt(  837): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  837): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  837): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  837): setSupplicantStateCOMPLETED
D/ConnectivityService(  837): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  837): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  837): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  837): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  837): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  837): ignoring duplicate network state non-change
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-52 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:16.616 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  837): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  837): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
E/WifiStateMachine(  837): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService(  837): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  837): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  837): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  278): netlink response contains error (File exists)
D/ConnectivityService(  837): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  837): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  837): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  837): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-52 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:16.666 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/WifiHS20(  837): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 3
D/WifiHS20(  837): [PASSPOINT] passpointNotification: hs20AP list is checked
D/Nat464Xlat(  837): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  837): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  837): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  837): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  837):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  837):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  837):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  837):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  837):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  837): currentScore = 0, newScore = 20
D/ConnectivityService(  837):    accepting network in place of null
D/ConnectivityService(  837): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WIFI    (  837): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  837):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1747): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/TelephonyNetworkFactory-1( 1747):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:16.701 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 3
E/ConnectivityService(  837): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  837): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:16.713 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  837): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  837): MasterInitialState.processMessage what=3
D/ConnectivityService(  837): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  837): [e] list.add(nai) empty : false size: 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): [LWD] Start DNSResolver start to wait
W/QCNEJ   ( 1837): |CORE| No family connected
I/QCNEJ   ( 1837): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  837): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/QCNEJ   ( 1837): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  837): validation of new default Network = false
D/ConnectivityService(  837): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  837): enableDataServiceNotify 
D/DSQN    (  837): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): [LWD] wait 500ms before dns check
V/NetworkPolicy(  837): [LG_RESTRICTED] checkMobilePolicy_type()
,D/ConnectivityService(  837): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  837):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  837):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  837): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/DhcpStateMachine(  837): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  837): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  837): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/DSQN    ( 6560): DSQN samuel.seo ver 141203
E/DSQN    ( 6560): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6560): created command queue thread
I/DSQN    ( 6560): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6560): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/dhcpcd  ( 6561): version 5.5.6 starting
E/dhcpcd  ( 6561): get_duid: Read-only file system
W/art     ( 6517): Suspending all threads took: 74.689ms
I/art     ( 6517): CheckpointMarkThreadRoots callback created = 0xb042d800
,D/SensorManager( 6517): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6517): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 6517): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6517): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6517): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6517): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6517): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6517): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6517): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6517): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6517): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6517): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6517): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6517): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6517): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6517): found sensor: Motion Accel, handle=46
I/art     ( 6517): CheckpointMarkThreadRoots callback created = 0xb042d7f0
,I/ActivityManager(  837): Process com.google.android.apps.plus (pid 6213) has died
,I/dhcpcd  ( 6561): wlan0: rebinding lease of 192.168.1.134
,I/ActivityManager(  837): Process com.android.providers.calendar (pid 6307) has died
W/Settings( 6517): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6517): startup - clean
I/Babel   ( 6517): deleted: false for 0
,V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
W/AudioCapabilities( 6517): Unsupported mime audio/x-lg-flac
I/PCSuite ( 6493): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6493): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6493): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6517): Unsupported mime audio/adpcm
W/AudioCapabilities( 6517): Unsupported mime audio/g726
,W/AudioCapabilities( 6517): Unsupported mime audio/x-ms-wma
V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6517): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6517): Unsupported mime video/mjpg
D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
W/VideoCapabilities( 6517): Unsupported mime video/theora
I/PCSuite ( 6493): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6493): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6493): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6464): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
W/AudioCapabilities( 6517): Unsupported mime audio/evrc
,V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
W/AudioCapabilities( 6517): Unsupported mime audio/qcelp
W/VideoCapabilities( 6517): Unrecognized profile 2130706433 for video/avc
,V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
W/AudioCapabilities( 6517): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6517): Unsupported mime audio/qcelp
W/AudioCapabilities( 6517): Unsupported mime audio/evrc
V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): [LWD] DNSResolver start dns
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
W/VideoCapabilities( 6517): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6517): Unsupported profile 4 for video/mp4v-es
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  837): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): Checking http://clients3.google.com/generate_204 on "NG700"
W/VideoCapabilities( 6517): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6517): Unrecognized profile 2130706433 for video/avc
,D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/VideoCapabilities( 6517): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6517): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  837): Process com.google.android.gm (pid 6326) has died
I/DSQN    ( 6560): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6560): restart monitoring
,D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6560): dsqn report finish
D/DSQN    (  837): DSQM DsqnNotification wlan0  1
D/DSQN    (  837): start to monitor internet connection
D/UEI.SmartControl( 6385): Service.onTrimMemory: 10
E/UEI.SmartControl( 6385): Setup service releasing memory...
I/PhoneApp( 1747): onTrimMemory: 10
I/PhoneApp( 1747): trim memory
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 13:38:17 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450100297313], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450100297294]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  837): Validated
D/ConnectivityService(  837): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  837): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  837):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  837):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  837):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  837): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  837): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  837):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  837):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  837): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  837): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  837): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  837):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1747): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1747):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
D/ConnectivityService(  837): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiDataContinuityService(  837): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  837): set CMD_CAPTIVE_CHECK_COMPLETED
,I/vclib   ( 6517): onServiceConnected
W/Babel   ( 6517): Attempted to change video mute state without an active call.
D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
,I/art     ( 6385): Explicit concurrent mark sweep GC freed 134(16KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 333us total 31.298ms
I/NotificationManager( 6517): com.google.android.talk: cancel(10436) by com.google.android.talk
V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
,D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
I/PCSuite ( 6493): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6493): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6464): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/UEI.SmartControl( 6385): Internal timer expired: 1
D/WiFiOffLoadBroadcast( 6464): MCCMNC not supported: null
I/PCSuite ( 6493): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6493): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/CAR.SERVICE( 6346): mConnectedToCar = false, abort
,E/ActivityThread( 6346): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@35dcfeff that was originally bound here
E/ActivityThread( 6346): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@35dcfeff that was originally bound here
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
,E/ActivityThread( 6346): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@22760af6 that was originally bound here
E/ActivityThread( 6346): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@22760af6 that was originally bound here
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
W/ActivityManager(  837): Unbind failed: could not find connection for android.os.BinderProxy@2c3d6be
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/dhcpcd  ( 6561): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6561): wlan0: leased 192.168.1.134 for 86400 seconds
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  837): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  837): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  837): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  837): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  837): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  837): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  837): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  837): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  837): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  837): RunningState
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  837): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:18.075 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/ConnectivityService(  837): identical MTU - not setting
D/Nat464Xlat(  837): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  837): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  837):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  837):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  837): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  837): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  837): enableDataServiceNotify 
D/DSQN    (  837): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524295
,D/DSQN    (  837): dsqn is running restart
,I/DSQN    ( 6604): DSQN samuel.seo ver 141203
E/DSQN    ( 6604): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6604): created command queue thread
,I/DSQN    ( 6604): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6604): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityService(  837): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  837): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  837): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  837): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  837): onReceive
D/LocSvc_java(  837): got connectivity action
,D/LocSvc_java(  837): broadcast - no network connections
D/LocSvc_java(  837): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  837): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  837): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  837): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  837): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  837): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6614 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider(  837): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  837): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  837): onReceive
D/LocSvc_java(  837): got connectivity action
D/LocSvc_java(  837): broadcast - no network connections
D/LocSvc_java(  837): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  837): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  837): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  837): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  837): ignore wifi update if we are not in OPENING or CLOSING
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/MusicStore( 6614): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6614): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6614): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6614): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6614): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6614): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6614): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6614): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6614): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26f5783: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6614): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6614): GMSCore installation verified
I/ConfigStore( 6614): Config Database version: 1
,I/MediaRouter( 6614): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6614): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6614): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6614): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  837): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6646 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6614): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6614): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6614): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6646): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6646): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6646): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  837): Process com.android.vending (pid 6237) has died
,I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-51 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 14:38:19.514 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/LGEmail ( 6646): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6646): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,V/WifiInternetCheck(  837): Single check msg out of sync, ignoring.
,D/ConnectivityService(  837): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  837): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  837): onReceive
D/LocSvc_java(  837): got connectivity action
D/LocSvc_java(  837): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  837): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  837): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  837): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  837): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6614): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  837): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/eas_req ( 6646): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  837): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6676 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6646): JNI_OnLoad()
,I/HubEmail( 6646): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6646): registerNatives()
I/HubEmail( 6646): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6646): registerNativeMethods()
I/HubEmail( 6646): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6646): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6646): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6676): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/BluetoothAdapterService(350331330)( 1997): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36374428
,D/LGDMClient( 6676): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/jxcore-log( 6069): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6069): 
W/ContextImpl( 6676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6676): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6676): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  837): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6698 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 6676): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6676): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6676): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6676): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6676): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6676): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6676): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  837): Killing 6346:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6698): onCreate
,W/AppUp4:DB( 6698):  [AppBoxDatabaseHelper] construct
W/libprocessgroup(  837): failed to open /acct/uid_10006/pid_6346/cgroup.procs: No such file or directory
I/AppUp4:DB( 6698):  setFingerPrint start
I/AppUp4:DB( 6698):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6698):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6698):  SDK version = 0
I/AppUp4:DB( 6698):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6698): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6698): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6698): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6698): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6698): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6698): onReceive
I/AppUp4:CustModeStarterReceiver( 6698): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6698): Context : android.app.ReceiverRestrictedContext@2e469337
D/AppUp4:CustFacade( 6698): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6698): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6698): begin check event
I/AppUp4:CustModeStarterReceiver( 6698): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6698): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6698): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6698): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6698): handleAsyncCustNotification do not startCustService
I/ActivityManager(  837): Killing 6517:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  837): failed to open /acct/uid_10061/pid_6517/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3130): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3130): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3130): networkInfo.isConnected() = false
I/ActivityManager(  837): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6719 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6719): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6719): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6719): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  837): Killing 6464:com.android.settings/1000 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_1000/pid_6464/cgroup.procs: No such file or directory
,I/CheckinService( 4205): Checkin interval check for package: unspecified last checkin: 1450100274697 min interval config: 0 actual interval: 25652
,V/DownloadManager( 3207): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3207): DownloadService onCreate
D/PhoneMonitor( 6719): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6719): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6719): [parse] Load xml
I/DownloadManager( 3207): in removeSpuriousFiles
I/NotificationManager( 3207): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/TelephonyAutoProfiling( 6719): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6719): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3207): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@2319821 on behalf of 3207
,I/ActivityManager(  837): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6746 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/DownloadManager( 3207): in trimDatabase
V/DownloadManager( 3207): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@27e9f334 on behalf of 3207
V/DownloadManager( 3207): DownloadService onStartCommand
I/CheckinService( 4205): Checking schedule, now: 1450100300414 next: 1450100304635
I/CheckinService( 4205): active receiver: disabled
,V/DownloadManager( 3207): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@14ee955d on behalf of 3207
D/PhoneMonitor( 6719): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3207): DownloadService onDestroy
,I/ActivityManager(  837): Killing 6385:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6284): android.os.DeadObjectException
,W/System.err( 6284): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6284): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6284): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6284): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6284): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6284): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6284): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6284): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6284): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6284): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6284): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6284): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6284): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6284): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6284): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6284): android.os.DeadObjectException
W/System.err( 6284): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6284): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6284): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6284): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6284): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6284): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6284): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6284): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6284): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6284): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6284): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6284): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6284): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6284): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6284): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  837): failed to open /acct/uid_10089/pid_6385/cgroup.procs: No such file or directory
,W/ActivityManager(  837): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/WeatherAncestor( 2738): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:38:20
I/ActivityManager(  837): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6775 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UpdateThreadPoolManager( 2738): 2 : This is isUpdating : false
D/WeatherAncestor( 2738): connectivity changed - connection : true
D/Weather_cast( 2738): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2738): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:38:20
D/WeatherService( 2738): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  837): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6792 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 472us total 30.034ms
,W/ActivityManager(  837): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2738): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2738): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2738): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.448ms
,D/UEI.SmartControl( 6775): Quickset Services start...
I/UEI.SmartControl( 6775): Manufacture = LGE
,D/UEI.SmartControl( 6775): File observer start...
E/UEI.SmartControl( 6775): IR Port is disabled: false
D/UEI.SmartControl( 6775): Starting file observer...
D/UEI.SmartControl( 6775): Extracting JNI libs...
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 21.368ms
D/UEI.SmartControl( 6775): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6792): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/UEI.SmartControl( 6775): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6775): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6775): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  837): propertyValue:false
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  837): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  837): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
I/Babel_SMS( 6792): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6792): MmsConfig.loadMmsSettings
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  837): propertyValue:false
I/Babel_SMS( 6792): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6792): MmsConfig.loadFromDatabase
,I/DSQN    ( 6604): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6604): restart monitoring
,I/DSQN    ( 6604): dsqn report finish
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  837): DSQM DsqnNotification wlan0  1
D/DSQN    (  837): start to monitor internet connection
,I/UEI.SmartControl( 6775): --- Selecting new region: 2
I/UEI.SmartControl( 6775): -- Running on KitKat(19) and above! JNI will be used.
E/Babel_SMS( 6792): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6792): MmsConfig.loadFromResources
E/Babel_SMS( 6792): canonicalizeMccMnc: invalid mccmnc nullnull
D/UEI.SmartControl( 6775): Platform has CIR...
I/Babel_SMS( 6792): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/UEI.SmartControl( 6775): NO CIR support, need to check package...
V/WifiInternetCheck(  837): isHttpConnectionAvailable - We got a valid response : 204
,I/UEI.SmartControl( 6775): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6775): QS Service created
D/SensorManager( 6792): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6792): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6792): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6792): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6792): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6792): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6792): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6792): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6792): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6792): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6792): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6792): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6792): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6792): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6792): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6792): found sensor: Motion Accel, handle=46
,E/UEI.SmartControl( 6775): QS start get config
,W/Settings( 6792): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6792): startup - clean
D/UEI.SmartControl( 6775): Loading JNI Libs...
,D/UEI.SmartControl( 6775):  configuring local db...
I/Babel   ( 6792): deleted: false for 0
I/art     ( 6792): CheckpointMarkThreadRoots callback created = 0xb042d840
,I/art     ( 6792): CheckpointMarkThreadRoots callback created = 0xb042d820
,I/art     (  837): Explicit concurrent mark sweep GC freed 79933(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.268ms total 158.877ms
,D/UEI.SmartControl( 6775):  ---- Has DB8: true
I/ActivityManager(  837): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6834 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6775): QS start statue = true Error code = 0
D/UEI.SmartControl( 6775): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6775): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6775): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6775): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6775): IrrcClient ++ 
D/irrcClient( 6775): getIrrcService ++ 
,D/irrcClient( 6775): getIrrcService -- 
D/irrcClient( 6775): IrrcClient -- 
W/irrc_jni( 6775): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6775): Services init done
I/UEI.SmartControl( 6775): Device manager: loading config....
D/UEI.SmartControl( 6775): QS Service init finished
,D/UEI.SmartControl( 6775): QS Service version name: 0.1.73
D/UEI.SmartControl( 6775): QS Service version code: 1073
D/UEI.SmartControl( 6775): Service requested: Control
W/AudioCapabilities( 6792): Unsupported mime audio/x-lg-flac
D/UEI.SmartControl( 6775): Config is loaded...
W/AudioCapabilities( 6792): Unsupported mime audio/adpcm
W/AudioCapabilities( 6792): Unsupported mime audio/g726
W/AudioCapabilities( 6792): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6792): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6792): Unsupported mime video/mjpg
W/VideoCapabilities( 6792): Unsupported mime video/theora
D/UEI.SmartControl( 6775):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6775): Notify AllClients services are ready: 0
,W/AudioCapabilities( 6792): Unsupported mime audio/evrc
,W/AudioCapabilities( 6792): Unsupported mime audio/qcelp
W/VideoCapabilities( 6792): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 6775): Request IControl service: devices are loaded...
W/AudioCapabilities( 6792): Unsupported mime audio/amr-wb-plus
D/UEI.SmartControl( 6775): -----IControl: 11
I/ActivityManager(  837): Killing 6493:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6775): Caller: com.lge.qremote
W/AudioCapabilities( 6792): Unsupported mime audio/qcelp
,D/UEI.SmartControl( 6775): ------------ IControl registerCallback...
W/AudioCapabilities( 6792): Unsupported mime audio/evrc
I/UEI.SmartControl( 6775): Registering callback...
D/UEI.SmartControl( 6775): -----IControl: 19
D/UEI.SmartControl( 6775): Caller: com.lge.qremote
I/UEI.SmartControl( 6775): Registering Services Ready callback...
I/UEI.SmartControl( 6775): Notify client services are ready...
D/UEI.SmartControl( 6775): -----IControl: 8
D/UEI.SmartControl( 6775): Caller: com.lge.qremote
W/VideoCapabilities( 6792): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6792): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6792): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6792): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6792): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6792): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  837): failed to open /acct/uid_1000/pid_6493/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6775): Internal service binding...
I/vclib   ( 6792): onServiceConnected
,W/Babel   ( 6792): Attempted to change video mute state without an active call.
I/NotificationManager( 6792): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6792): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6792): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6792): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6792): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6792): propertyValue:false
,I/Babel   ( 6792): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  837): Killing 6284:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  837): failed to open /acct/uid_10106/pid_6284/cgroup.procs: No such file or directory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6834): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6834): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6834): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6834): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6834): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6834):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6834):   adb logcat -s GAv4
W/GAv4    ( 6834): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6834): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6834): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6834): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6834): Time to load native libraries: 2 ms (timestamps 7797-7799)
,I/LibraryLoader( 6834): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6834): Binding Chromium to main looper Looper (main, tid 1) {3e6a11b8}
I/LibraryLoader( 6834): Expected native library version number "",actual native library version number ""
I/chromium( 6834): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6834): Initializing chromium process, singleProcess=true
,W/art     ( 6834): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6834): ApplicationContext is null in ApplicationStatus
W/chromium( 6834): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6834): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6834): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6834): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6834): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6834): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6834): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6834): Remote Branch: 
I/Adreno-EGL( 6834): Local Patches: 
I/Adreno-EGL( 6834): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb551c900, uid 10079
,W/AudioManagerAndroid( 6834): Requires BLUETOOTH permission
I/NSApplication( 6834): Starting up...
,I/ActivityManager(  837): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6901 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  837): Killing 6614:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  837): failed to open /acct/uid_10081/pid_6614/cgroup.procs: No such file or directory
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  837): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6924 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  837): Killing 6646:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  837): failed to open /acct/uid_10021/pid_6646/cgroup.procs: No such file or directory
,W/ResourcesManager( 6924): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  837): Killing 6676:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_1000/pid_6676/cgroup.procs: No such file or directory
,I/ActivityManager(  837): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6948 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6948): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6948): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6948): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6948): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6948): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6948): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6948): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6948): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6948): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26f5783: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6948): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6948): GMSCore installation verified
,I/ConfigStore( 6948): Config Database version: 1
,I/MediaRouter( 6948): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6948): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6948): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/NetworkMonitor( 6948): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  837): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6976 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{2f884e4e type 2 when 109455 com.google.android.gms} when 109455
I/GHttpClientFactory( 6948): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6948): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6976): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6976): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6976): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  837): Killing 6698:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_10011/pid_6698/cgroup.procs: No such file or directory
,I/NotificationManager( 6948): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6976): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6976): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6976): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  837): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7006 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6976): JNI_OnLoad()
I/HubEmail( 6976): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6976): registerNatives()
I/HubEmail( 6976): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6976): registerNativeMethods()
I/HubEmail( 6976): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6976): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  837): Killing 6719:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/Settings( 6976): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup(  837): failed to open /acct/uid_10038/pid_6719/cgroup.procs: No such file or directory
D/LGDMClient( 7006): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7006): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7006): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7006): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7006): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7006): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  837): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7030 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7006): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7006): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7006): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7006): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7006): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  837): Killing 6746:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  837): failed to open /acct/uid_10051/pid_6746/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7030): onCreate
W/AppUp4:DB( 7030):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7030):  setFingerPrint start
I/AppUp4:DB( 7030):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7030):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7030):  SDK version = 0
I/AppUp4:DB( 7030):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7030): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7030): onReceive
I/AppUp4:CustModeStarterReceiver( 7030): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7030): Context : android.app.ReceiverRestrictedContext@2e469337
D/AppUp4:CustFacade( 7030): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7030): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7030): begin check event
I/AppUp4:CustModeStarterReceiver( 7030): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7030): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7030): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7030): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7030): handleAsyncCustNotification do not startCustService
I/ActivityManager(  837): Killing 6775:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_10089/pid_6775/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3130): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3130): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3130): networkInfo.isConnected() = false
,I/ActivityManager(  837): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7049 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7049): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7049): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7049): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  837): Killing 6792:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7049): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7049): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7049): [parse] Load xml
V/TelephonyAutoProfiling( 7049): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7049): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7049): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  837): failed to open /acct/uid_10061/pid_6792/cgroup.procs: No such file or directory
V/DownloadManager( 3207): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/AlarmManager(  837): RTC_WAKEUP set : Alarm{cad4f6b type 0 when 1450100304635 com.google.android.gms} when 1450100304635
V/DownloadManager( 3207): DownloadService onCreate
I/NotificationManager( 3207): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/AlarmManager(  837): RTC_WAKEUP set : Alarm{206e0761 type 0 when 1450100304735 com.google.android.googlequicksearchbox} when 1450100304735
I/DownloadManager( 3207): in removeSpuriousFiles
,V/DownloadManager( 3207): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@17cd0ea0 on behalf of 3207
I/DownloadManager( 3207): in trimDatabase
V/DownloadManager( 3207): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@c842a59 on behalf of 3207
,I/ActivityManager(  837): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7079 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3207): DownloadService onStartCommand
V/DownloadManager( 3207): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@35dcfeff on behalf of 3207
I/CheckinService( 4205): Checkin interval check for package: unspecified last checkin: 1450100274697 min interval config: 0 actual interval: 30110
,I/CheckinService( 4205): Checking schedule, now: 1450100304822 next: 1450100304635
I/CheckinService( 4205): active receiver: enabled
,I/CheckinService( 4205): Preparing to send checkin request
I/EventLogService( 4205): Accumulating logs since 1450100266122
,V/DownloadManager( 3207): DownloadService onDestroy
,D/WeatherAncestor( 2738): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:38:24
D/UpdateThreadPoolManager( 2738): 2 : This is isUpdating : false
D/WeatherAncestor( 2738): connectivity changed - connection : true
D/Weather_cast( 2738): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2738): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:38:24
D/WeatherService( 2738): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  837): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7103 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  837): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2738): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2738): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2738): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/CheckinRequestBuilder( 4205): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4205): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 7103): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  837): Explicit concurrent mark sweep GC freed 16771(877KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.458ms total 164.938ms
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  837): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7126 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.334ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.295ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.091ms
,I/art     ( 7103): CheckpointMarkThreadRoots callback created = 0xb042d460
,W/ResourcesManager( 7126): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7126): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 7103): CheckpointMarkThreadRoots callback created = 0xb042d440
,I/Babel_SMS( 7103): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7103): MmsConfig.loadMmsSettings
I/Babel_SMS( 7103): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7103): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7103): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7103): MmsConfig.loadFromResources
E/Babel_SMS( 7103): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7103): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7103): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7103): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7103): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7103): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7103): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7103): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7103): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7103): found sensor: LGE Step Detector Sensor, handle=43
,D/SensorManager( 7103): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7103): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7103): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7103): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7103): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7103): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7103): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7103): found sensor: Motion Accel, handle=46
I/MultiDex( 7126): VM with version 2.1.0 has multidex support
I/MultiDex( 7126): install
I/MultiDex( 7126): VM has multidex support, MultiDex support library is disabled.
W/Settings( 7103): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7103): startup - clean
V/JNIHelp ( 7126): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel   ( 7103): deleted: false for 0
,W/ActivityThread( 7126): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7126): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e87f688: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7126): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7126): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7126): com.google.android.gms: cancel(39789) by com.google.android.gms
W/AudioCapabilities( 7103): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7103): Unsupported mime audio/adpcm
W/AudioCapabilities( 7103): Unsupported mime audio/g726
V/MusicLeanback( 6948): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/AudioCapabilities( 7103): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7103): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7103): Unsupported mime video/mjpg
D/LGDMClient( 7006): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7006): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,I/art     ( 6924): CheckpointMarkThreadRoots callback created = 0xb042dd90
W/ContextImpl( 7006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/VideoCapabilities( 7103): Unsupported mime video/theora
W/Settings( 6976): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7030): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7030): onReceive
I/AppUp4:CustModeStarterReceiver( 7030): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7030): Context : android.app.ReceiverRestrictedContext@2e469337
D/AppUp4:CustFacade( 7030): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7030): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7030): begin check event
I/AppUp4:CustModeStarterReceiver( 7030): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3130): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3130): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3130): networkInfo.isConnected() = true
D/PhoneState( 3130): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 7049): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7049): onReceive CONNECTIVITY_CHANGE networkType=1
D/LGDMClient( 7006): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
V/DownloadManager( 3207): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 7006): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3207): DownloadService onCreate
,I/DownloadManager( 3207): in removeSpuriousFiles
V/DownloadManager( 3207): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@38441315 on behalf of 3207
D/LGDMClient( 7006): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/WeatherAncestor( 2738): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:38:25
W/ContextImpl( 7006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LGDMClient( 7006): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/NotificationManager( 3207): com.android.providers.downloads: cancelAll by com.android.providers.downloads
E/LGDMClient( 7006): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/UpdateThreadPoolManager( 2738): 2 : This is isUpdating : false
D/WeatherAncestor( 2738): connectivity changed - connection : true
D/Weather_cast( 2738): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2738): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:38:25
D/WeatherService( 2738): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7006): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7006): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/DownloadManager( 3207): in trimDatabase
V/DownloadManager( 3207): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/art     ( 6924): CheckpointMarkThreadRoots callback created = 0xb042dd60
D/LGDMClient( 7006): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
V/DownloadManager( 3207): DownloadService onStartCommand
W/ActivityManager(  837): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2738): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3207): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/WeatherService( 2738): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2738): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@3e6a11b8 on behalf of 3207
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@10dfcb91 on behalf of 3207
D/LGDMClient( 7006): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
W/AudioCapabilities( 7103): Unsupported mime audio/evrc
,W/AudioCapabilities( 7103): Unsupported mime audio/qcelp
W/VideoCapabilities( 7103): Unrecognized profile 2130706433 for video/avc
,I/art     ( 7126): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7126): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/AudioCapabilities( 7103): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7103): Unsupported mime audio/qcelp
W/AudioCapabilities( 7103): Unsupported mime audio/evrc
V/DownloadManager( 3207): DownloadService onDestroy
,W/VideoCapabilities( 7103): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7103): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7103): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7103): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7103): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7103): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7103): onServiceConnected
,W/Babel   ( 7103): Attempted to change video mute state without an active call.
D/libc-netbsd( 7103): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7103): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7103): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7103): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7103): propertyValue:false
,I/NotificationManager( 7103): com.google.android.talk: cancel(10436) by com.google.android.talk
D/NativeLibraryUtils( 7126): Install completed successfully. count=14 extracted=0
,I/Babel   ( 7103): connection state changed from UNKNOWN to CONNECTED
,D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): CdmEngine::OpenSession
I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
I/ActivityManager(  837): Process com.google.android.music:main (pid 6948) has died
,W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  837): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7172 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  282): PrepareKeyRequest: nonce=3083978981
,W/ResourcesManager( 7172): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  837): Message: 20
D/BluetoothManagerService(  837): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@68dc5b1:true
,D/BluetoothAdapterService(350331330)( 1997): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36374428
,D/BluetoothAdapterService(350331330)( 1997): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36374428
I/ActivityManager(  837): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7190 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7172): Create singleton instance
,D/UEI.SmartControl( 7190): Quickset Services start...
,I/UEI.SmartControl( 7190): Manufacture = LGE
D/UEI.SmartControl( 7190): File observer start...
E/UEI.SmartControl( 7190): IR Port is disabled: false
D/UEI.SmartControl( 7190): Starting file observer...
D/UEI.SmartControl( 7190): Extracting JNI libs...
,D/UEI.SmartControl( 7190): --- this system supports 32-bit or 64-bit only
I/art     ( 7126): CheckpointMarkThreadRoots callback created = 0xb04cbe80
I/AudioManager( 7172): getMode name:com.lge.qremote
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
I/CheckinService( 4205): Checkin interval check for package: unspecified last checkin: 1450100274697 min interval config: 0 actual interval: 31859
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/UEI.SmartControl( 7190): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7190): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7190): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
,I/UEI.SmartControl( 7190): --- Selecting new region: 2
I/UEI.SmartControl( 7190): -- Running on KitKat(19) and above! JNI will be used.
I/art     ( 7126): CheckpointMarkThreadRoots callback created = 0xb04cbe70
,D/UEI.SmartControl( 7190): Platform has CIR...
D/UEI.SmartControl( 7190): NO CIR support, need to check package...
I/UEI.SmartControl( 7190): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7190): QS Service created
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dex2oat ( 7212): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/ActivityManager(  837): Process com.lge.email (pid 6976) has died
,D/WearableService( 1729): callingUid 10006, callindPid: 1729
D/LocationInitializer( 4205): Restart initialization of location
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/UEI.SmartControl( 7190): QS start get config
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
E/MDM     ( 1729): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/AudioManager( 7172): getMode name:com.lge.qremote
I/dex2oat ( 7212): dex2oat took 134.033ms (threads: 4)
I/Adreno-EGL( 7126): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7126): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7126): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7126): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7126): Remote Branch: 
I/Adreno-EGL( 7126): Local Patches: 
I/Adreno-EGL( 7126): Reconstruct Branch: 
,D/UEI.SmartControl( 7190): Loading JNI Libs...
D/UEI.SmartControl( 7190):  configuring local db...
,I/GCM     ( 4205): Message from null null
E/GCM     ( 4205): Dropping message from null
,I/WVCdm   (  282): CdmEngine::OpenSession
,D/UEI.SmartControl( 7190):  ---- Has DB8: true
,D/UEI.SmartControl( 7190): QS start statue = true Error code = 0
D/UEI.SmartControl( 7190): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7190): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7190): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7190): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7190): IrrcClient ++ 
D/irrcClient( 7190): getIrrcService ++ 
D/irrcClient( 7190): getIrrcService -- 
D/irrcClient( 7190): IrrcClient -- 
W/irrc_jni( 7190): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7190): Services init done
,I/UEI.SmartControl( 7190): Device manager: loading config....
D/UEI.SmartControl( 7190): QS Service init finished
D/UEI.SmartControl( 7190): QS Service version name: 0.1.73
D/UEI.SmartControl( 7190): QS Service version code: 1073
D/UEI.SmartControl( 7190): Config is loaded...
D/UEI.SmartControl( 7190): Service requested: Control
D/UEI.SmartControl( 7190): -----IControl: 11
D/UEI.SmartControl( 7190): Internal service binding...
D/UEI.SmartControl( 7190): Caller: com.lge.qremote
D/UEI.SmartControl( 7190): ------------ IControl registerCallback...
I/UEI.SmartControl( 7190): Registering callback...
D/UEI.SmartControl( 7190): -----IControl: 19
,D/UEI.SmartControl( 7190): Caller: com.lge.qremote
I/UEI.SmartControl( 7190): Registering Services Ready callback...
D/UEI.SmartControl( 7190):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7190): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7190): -----IControl: 8
D/UEI.SmartControl( 7190): Caller: com.lge.qremote
I/AudioManager( 7172): getMode name:com.lge.qremote
I/ActivityManager(  837): Killing 7030:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_10011/pid_7030/cgroup.procs: No such file or directory
,I/AudioManager( 7172): getMode name:com.lge.qremote
I/AudioManager( 7172): getMode name:com.lge.qremote
,I/ActivityManager(  837): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7237 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  837): RTC_WAKEUP set : Alarm{2290ca5d type 0 when 1450100307535 com.android.vending} when 1450100307535
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/Finsky  ( 7237): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 7237): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7237): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7237): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7237): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Ads     ( 7237): Skipping gmscore version check
D/Finsky  ( 7237): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7237): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3207): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@13ddcef7 on behalf of 7237
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  837): tsOffsetIs: Apps: 113759226940; DSPS: 3825747; Offset : -2994903360
,D/Finsky  ( 7237): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7237): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 7237): [915] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7237): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  837): Killing 7079:com.lge.drmservice/u0a51 (adj 15): empty #11
I/WVCdm   (  282): CdmEngine::CloseSession
W/libprocessgroup(  837): failed to open /acct/uid_10051/pid_7079/cgroup.procs: No such file or directory
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=933949371
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/WVCdm   (  282): CdmEngine::CloseSession
,I/WVCdm   (  282): L3 Terminate.
I/Adreno-EGL( 7126): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7126): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7126): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7126): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7126): Remote Branch: 
I/Adreno-EGL( 7126): Local Patches: 
I/Adreno-EGL( 7126): Reconstruct Branch: 
,I/Adreno-EGL( 7126): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7126): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7126): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7126): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7126): Remote Branch: 
I/Adreno-EGL( 7126): Local Patches: 
I/Adreno-EGL( 7126): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/CheckinRequestBuilder( 4205): Classify the device as Phone.
,D/libc-netbsd( 4205): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4205): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4205): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4205): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 4205): propertyValue:false
,D/libc-netbsd( 4205): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4205): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4205): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4205): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4205): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4205): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4205): Sending checkin request (9799 bytes)
,I/MusicWidget( 2654): mDelayedStopHandler : unbind
,I/MusicBrowser( 2084): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2084): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2084): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2084): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2084): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2084): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2084): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2084): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  837):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1069ff72com.lge.music.MediaPlaybackService$6@d22afc3
,D/MusicBrowser( 2084): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2084): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2084): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2084): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2084): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1672bd3
I/MusicBrowser( 2084): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2084): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2084): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2084): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2084): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2084): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2084): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2084): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2084): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2084): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2084): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2084): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2084): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2084): reset
V/MediaPlayer[Native]( 2084): setListener
V/MediaPlayer[Native]( 2084): disconnect
V/MediaPlayer[Native]( 2084): destructor
,V/AudioFlinger(  282): releasing 19 from 2084 for -1
,V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2084): disconnect
D/MusicBrowser( 2084): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2084): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2084): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2084): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2084): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2084): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2084): [SmartShareManagerClient] unregisterListener: 488927296
W/SmartShareClient( 2084): [SmartShareManagerClient] unregisterListener invalid listener: 488927296
I/SmartShareClient( 2084): [SmartShareManagerClient] terminate service: 2084/MediaPlaybackService/954688977
E/HomeCloudIF( 2084): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2084): [SmartShareManagerClient] unbindService context:android.app.Application@14377b79
V/CloudHub( 2084): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2084): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2084): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2084): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2084): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  837): Killing 7006:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/CloudHub( 2084): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
W/libprocessgroup(  837): failed to open /acct/uid_1000/pid_7006/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 4205): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4205): Failed to find provider info for com.google.android.wearable.settings
I/art     ( 3939): Explicit concurrent mark sweep GC freed 1843(69KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 865us total 96.289ms
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 4205): Classify the device as Phone.
,I/CheckinTask( 4205): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4205): Checking schedule, now: 1450100311877 next: 1450627560873
I/CheckinService( 4205): active receiver: disabled
,I/CheckinService( 4205): Checking schedule, now: 1450100311920 next: 1450627560873
I/CheckinService( 4205): active receiver: disabled
,D/CheckinService( 4205): Recording last checkin time for package unspecified as 1450100311930
,I/ActivityManager(  837): Killing 6834:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_10079/pid_6834/cgroup.procs: No such file or directory
,V/SetupWizard( 7049): Connected to Gservices successfully
,I/ActivityManager(  837): Killing 6901:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  837): failed to open /acct/uid_10048/pid_6901/cgroup.procs: No such file or directory
,D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7190): Internal timer expired: 1
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{13696093 type 2 when 119640 com.google.android.gms} when 119640
,I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  837): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/administrator(  837): Handling package changes for user 0
,I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/ActivityManager(  837): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7360 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationManager( 7103): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7103): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7103): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7103): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7103): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7103): Installed default security provider GmsCore_OpenSSL
,I/NotificationService(  837): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  837): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  837): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  837): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/art     (  837): Explicit concurrent mark sweep GC freed 30148(1423KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.713ms total 206.078ms
,V/BackupManagerService(  837): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  837): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@26303a45
I/AppUp4:AppBoxCP( 7360): onCreate
W/AppUp4:DB( 7360):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7360):  setFingerPrint start
,I/AppUp4:DB( 7360):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7360):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7360):  SDK version = 0
I/AppUp4:DB( 7360):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7360): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7360): onReceive
I/AppUp4:CustModeStarterReceiver( 7360): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7360): Context : android.app.ReceiverRestrictedContext@3c42acf8
D/AppUp4:CustFacade( 7360): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7360): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7360): begin check event
I/AppUp4:CustModeStarterReceiver( 7360): Event For Nothing, skip.
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
W/ResourcesManager(  837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  837): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7382 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7382): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7382): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7382): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  837): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 },
,I/GCoreNlp( 1729): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 7382): Total System Memory = 906309632
,I/GalleryUtils( 7382): Application Heap = 96 MB
D/LocationProviderProxy(  837): applying state to connected service
I/AppConfig( 7382): App Tier : NOT_DEF
D/SystemHelper( 7382): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  837): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7406 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  837): Killing 6924:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/ActivityManager(  837): Process com.android.vending (pid 7237) has died
,W/libprocessgroup(  837): failed to open /acct/uid_10086/pid_6924/cgroup.procs: No such file or directory
W/ResourcesManager( 7406): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7406): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7406): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7406): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 7406): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7406): BUILD Country: EU
I/SystemConfig( 7406): BUILD Operator: OPEN
,I/ActivityManager(  837): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7433 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7406): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7406): existFile = false
I/SystemConfig( 7406): canReadFile = false
I/SystemConfig( 7406): systemFeature RCS result false
D/SystemConfig( 7406): refreshRcsSupport() :false
,I/LockScreenSettings( 7433): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7433): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7433): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7433): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7433): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7433): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  837): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7453 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  837): Killing 7190:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7172): android.os.DeadObjectException
,W/System.err( 7172): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7172): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7172): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7172): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7172): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7172): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7172): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7172): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7172): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7172): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7172): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7172): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7172): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7172): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7172): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7172): android.os.DeadObjectException
W/System.err( 7172): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7172): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7172): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7172): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7172): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7172): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7172): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7172): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7172): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7172): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7172): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7172): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7172): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7172): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7172): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  837): failed to open /acct/uid_10089/pid_7190/cgroup.procs: No such file or directory
W/ActivityManager(  837): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  837): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7471 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7453): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 7471): Quickset Services start...
,I/UEI.SmartControl( 7471): Manufacture = LGE
D/UEI.SmartControl( 7471): File observer start...
E/UEI.SmartControl( 7471): IR Port is disabled: false
D/UEI.SmartControl( 7471): Starting file observer...
D/UEI.SmartControl( 7471): Extracting JNI libs...
D/UEI.SmartControl( 7471): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7471): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7471): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7471): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7471): --- Selecting new region: 2
,I/UEI.SmartControl( 7471): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7471): Platform has CIR...
D/UEI.SmartControl( 7471): NO CIR support, need to check package...
I/UEI.SmartControl( 7471): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7471): QS Service created
E/UEI.SmartControl( 7471): QS start get config
,D/UEI.SmartControl( 7471): Loading JNI Libs...
,D/UEI.SmartControl( 7471):  configuring local db...
I/UpdateIcingCorporaServi( 1932): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  837): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7502 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  837): Killing 2084:com.lge.music/u0a28 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1932): UpdateCorporaTask done [took 112 ms] updated apps [took 112 ms] 
,V/AudioFlinger(  282): 2084 died, releasing its sessions
V/AudioFlinger(  282):  pid 1747 @ 0
V/AudioFlinger(  282):  pid 3130 @ 1
V/AudioFlinger(  282):  pid 3130 @ 2
D/UEI.SmartControl( 7471):  ---- Has DB8: true
D/UEI.SmartControl( 7471): QS start statue = true Error code = 0
D/UEI.SmartControl( 7471): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 7471): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7471): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7471): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7471): IrrcClient ++ 
D/irrcClient( 7471): getIrrcService ++ 
D/irrcClient( 7471): getIrrcService -- 
D/irrcClient( 7471): IrrcClient -- 
W/irrc_jni( 7471): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7471): Services init done
I/UEI.SmartControl( 7471): Device manager: loading config....
D/UEI.SmartControl( 7471): Config is loaded...
,W/libprocessgroup(  837): failed to open /acct/uid_10028/pid_2084/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7471): QS Service init finished
D/UEI.SmartControl( 7471): QS Service version name: 0.1.73
D/UEI.SmartControl( 7471): QS Service version code: 1073
D/UEI.SmartControl( 7471): Service requested: Control
,I/ActivityManager(  837): Killing 7172:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 7471):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7471): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7471): Internal service binding...
W/libprocessgroup(  837): failed to open /acct/uid_10106/pid_7172/cgroup.procs: No such file or directory
,D/Finsky  ( 7502): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7502): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7502): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7502): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7502): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3207): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3207): created cursor android.database.sqlite.SQLiteCursor@148a9164 on behalf of 7502
,D/Finsky  ( 7502): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7502): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 7502): Skipping gmscore version check
D/Finsky  ( 7502): [1] Libraries$2.run: Finished loading 1 libraries.
D/PackageBroadcastService( 4205): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4205): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7502): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4205): updateResources: need to parse f{com.google.android.gms}
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Icing   ( 4205): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4205): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  837): Killing 7049:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_10038/pid_7049/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  837): Killing 7126:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  837): failed to open /acct/uid_10006/pid_7126/cgroup.procs: No such file or directory
,D/charger_monitor(  481): init target 500000
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/charger_monitor(  481): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1801): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,D/WifiController(  837): battery changed pluggedType: 2
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,D/UEI.SmartControl( 7471): Internal timer expired: 1
,D/UEI.SmartControl( 7471): Service.onUnbind: IControl
D/UEI.SmartControl( 7471): Service.onDestroy
W/System.err( 7471): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@14e1a1c2
W/System.err( 7471): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7471): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7471): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7471): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7471): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7471): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7471): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7471): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7471): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7471): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7471): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7471): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7471): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7471): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7471): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7471): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@14e1a1c2
D/UEI.SmartControl( 7471): Shutdown IRRCPlayer... 
,W/irrc_jni( 7471): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7471): ~IrrcClient ++ 
D/irrcClient( 7471): ~IrrcClient -- 
W/irrc_jni( 7471): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7471): Blaster closed
D/UEI.SmartControl( 7471): Blaster closed
D/UEI.SmartControl( 7471): Shut down QS...
,D/UEI.SmartControl( 7471): Stopped file observer...
I/UEI.SmartControl( 7471): QS lib stop result = true
D/UEI.SmartControl( 7471): QS shutdown complete
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 133760146101; DSPS: 4481137; Offset : -2994898920
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{322c9a6f type 2 when 140307 com.google.android.gms} when 140307
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1729): Vacuum at: now=1450100334839 tag=VacuumService
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 41475(2MB) AllocSpace objects, 31(496KB) LOS objects, 39% free, 14MB/23MB, paused 1.619ms total 105.741ms
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  837): acquireWakeLockInternal: lock=802069523, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=837
,D/WeatherService( 2738): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:39:0
,D/WeatherService( 2738): 2 : TimeTick Intent And Screen On
D/WeatherService( 2738): 2 : SDK version : 21
W/ActivityManager(  837): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2738): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2738): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2738): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2738): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2738): 2 : This is isUpdating : false
D/WeatherService( 2738): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2738): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2738): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2738): 2 : Fixed theme : optimus
D/WeatherReflect( 2738): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,D/lim     ( 2738): 2 : time = 14:39
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/WeatherReflect( 2738): Model Name : LG-D722
D/WeatherTheme( 2738): 2 : Different view - status_min_formatted : 38 != 39
D/WeatherTheme( 2738): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2738): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
,D/Theme   ( 2738): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2738): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2738): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2738): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2738): forecast size is 0
,D/Theme   ( 2738): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2738): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2738): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2738): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2738): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2738): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2738): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2738): url is : null
D/Theme   ( 2738): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2738): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2738): 2 : update view, appWidgetId: 2
D/WeatherService( 2738): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:39:0
D/PowerManagerServiceEx(  837): releaseWakeLockInternal: lock=802069523 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  837): ALS enabled for SRE
D/PowerManagerServiceEx(  837): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28331 ms ago)
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/qdlights(  837): set_light_backlight: 254
,D/qdlights(  837): set_light_backlight: 251
D/qdlights(  837): set_light_backlight: 248
,D/qdlights(  837): set_light_backlight: 244
,D/qdlights(  837): set_light_backlight: 241
,D/qdlights(  837): set_light_backlight: 238
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/qdlights(  837): set_light_backlight: 234
D/qdlights(  837): set_light_backlight: 231
,D/qdlights(  837): set_light_backlight: 228
,D/qdlights(  837): set_light_backlight: 224
,D/qdlights(  837): set_light_backlight: 221
,D/qdlights(  837): set_light_backlight: 218
,D/qdlights(  837): set_light_backlight: 214
,D/qdlights(  837): set_light_backlight: 211
,D/qdlights(  837): set_light_backlight: 208
,D/qdlights(  837): set_light_backlight: 204
,D/qdlights(  837): set_light_backlight: 201
,D/qdlights(  837): set_light_backlight: 198
,D/qdlights(  837): set_light_backlight: 194
,D/qdlights(  837): set_light_backlight: 191
,D/qdlights(  837): set_light_backlight: 188
,D/qdlights(  837): set_light_backlight: 184
,D/qdlights(  837): set_light_backlight: 181
,D/qdlights(  837): set_light_backlight: 178
,D/qdlights(  837): set_light_backlight: 174
,D/qdlights(  837): set_light_backlight: 171
,D/qdlights(  837): set_light_backlight: 168
,D/qdlights(  837): set_light_backlight: 164
,D/qdlights(  837): set_light_backlight: 161
,D/qdlights(  837): set_light_backlight: 158
,D/qdlights(  837): set_light_backlight: 154
,D/qdlights(  837): set_light_backlight: 151
,D/qdlights(  837): set_light_backlight: 148
,D/qdlights(  837): set_light_backlight: 144
,D/qdlights(  837): set_light_backlight: 141
,D/qdlights(  837): set_light_backlight: 138
,D/qdlights(  837): set_light_backlight: 134
,D/qdlights(  837): set_light_backlight: 131
,D/qdlights(  837): set_light_backlight: 128
,D/qdlights(  837): set_light_backlight: 124
,D/qdlights(  837): set_light_backlight: 121
,D/qdlights(  837): set_light_backlight: 118
,D/qdlights(  837): set_light_backlight: 114
,D/qdlights(  837): set_light_backlight: 111
,D/qdlights(  837): set_light_backlight: 108
,D/qdlights(  837): set_light_backlight: 104
,D/qdlights(  837): set_light_backlight: 101
,D/qdlights(  837): set_light_backlight: 98
,D/qdlights(  837): set_light_backlight: 94
,D/qdlights(  837): set_light_backlight: 91
,D/qdlights(  837): set_light_backlight: 88
,D/qdlights(  837): set_light_backlight: 84
,D/qdlights(  837): set_light_backlight: 81
,D/qdlights(  837): set_light_backlight: 78
,D/qdlights(  837): set_light_backlight: 74
,D/qdlights(  837): set_light_backlight: 71
,D/qdlights(  837): set_light_backlight: 68
,D/qdlights(  837): set_light_backlight: 64
,D/qdlights(  837): set_light_backlight: 61
,D/qdlights(  837): set_light_backlight: 58
,D/qdlights(  837): set_light_backlight: 54
,D/qdlights(  837): set_light_backlight: 51
,D/qdlights(  837): set_light_backlight: 48
,D/qdlights(  837): set_light_backlight: 44
,D/qdlights(  837): set_light_backlight: 41
,D/qdlights(  837): set_light_backlight: 38
,D/qdlights(  837): set_light_backlight: 34
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  837): set_light_backlight: 31
,D/qdlights(  837): set_light_backlight: 28
,D/qdlights(  837): set_light_backlight: 24
,D/qdlights(  837): set_light_backlight: 21
,D/qdlights(  837): set_light_backlight: 18
,D/qdlights(  837): set_light_backlight: 14
,D/qdlights(  837): set_light_backlight: 11
,D/qdlights(  837): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 153760906145; DSPS: 5136522; Offset : -2994901841
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  837): ALS enabled for SRE
D/PowerManagerServiceEx(  837): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35331 ms ago)
,I/PowerManagerService(  837): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  837): ALS enabled for SRE
D/PowerManagerServiceEx(  837): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35345 ms ago)
,W/ContextImpl(  837): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  837): Sleeping (uid 1000)...
D/LPWGController(  837): [updateScreenState] screen on = false
D/LPWGController(  837): disable proximity sensor
,D/LPWGController(  837): enable proximity sensor
I/SensorManager(  837): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2a110614] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  837): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  837): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  837): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  837): activate: handle is 48, enable
V/sensors_hal_Ctx(  837): activate sensors is 1400000000000
D/sensors_hal_Thresh(  837): enable: handle=48
I/sensors_hal_SAM(  837): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  837): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  837): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  837): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  837): enable: Received response: 0
D/PowerManagerServiceEx(  837): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35387 ms ago)
I/Adreno-EGL(  837): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  837): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  837): Build Date: 03/02/15 Mon
I/Adreno-EGL(  837): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  837): Remote Branch: 
I/Adreno-EGL(  837): Local Patches: 
I/Adreno-EGL(  837): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1100 us)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Sensors (  427): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  837): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  837): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  837): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  837): processInd: handle 48, count=1
V/sensors_hal_Thresh(  837): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  837): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  837): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  837): poll: count: 256
I/sensors_hal_Ctx(  837): poll: released wakelock sensor_ind
D/sensors_hal_Util(  837): waitForResponse: timeout=0
D/LPWGController(  837): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  837): current mode = 1  value = 1 1
I/LPWGController(  837): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  837): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  837): set_light_backlight: 0
,I/SensorManager(  837): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  837): activate: handle is 46, disable
V/sensors_hal_Ctx(  837): activate sensors is 1000000000000
D/sensors_hal_LP2(  837): enable: handle=46
D/sensors_hal_LP2(  837): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  837): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  837): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  837): Display changed displayId=0
,V/sensors_hal_SAM(  837): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  837): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1747): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  837): Excessive delay in setPowerMode(): 189ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  837): Got set_interactive hint
D/KeyguardViewMediator( 1370): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1370): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1370): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1370): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1370): unregisterProximitySensor
,D/WifiServerServiceExt(  837): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1370): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 837
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  282): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
I/WifiServerServiceExt(  837): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
,I/Sensors (  427): sns_pwr.c(301):releasing wakelock
,D/GpsLocationProvider(  837): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1837): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1801): stopPatternFlashing()
,D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1801): updateLightsLocked : turn off led
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1801): RESTART MSG
D/SplitWindow(  837): check instance of lgWin Window{1d482403 u0 SearchPanel}
,I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1801): lockStatus = 0
D/LNfcService( 1784): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1784): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1784): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
,D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 3
D/NfcService( 1784): Discovery configuration equal, not updating.
D/InputDispatcher(  837): Window went away: Window{b43240c u0 SearchPanel}
I/[SystemUI]Clock( 1370): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
,D/Ulp_jni (  837): JNI:system_update. Event-0
,V/PhoneApp( 1747): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2738): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:39:11
,D/WeatherService( 2738): 2 : ACTION screen on
D/WeatherService( 2738): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2738): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2738): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:39:11
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): ACTION_SCREEN_ON
D/AppCleanupService( 4065): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 837
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
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
D/WifiController(  837): CMD_SCREEN_OFF 
D/WifiController(  837): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  837): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1837): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn on led
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1801): Can't handle this request of patternId:0
D/LEDHandler( 1801): RESTART MSG
,I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1784): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1784): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1874): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1747): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2738): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:39:11
D/WeatherService( 2738): 2 : ACTION screen off
,D/WeatherService( 2738): 2 : TimeTick Receiver Unregister
D/WeatherService( 2738): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:39:11
,W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  837): ACTION_SCREEN_OFF
D/AppCleanupService( 4065): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4065): AppUsageStatsSaveTask
,E/NxpNfcJni( 1784): getReconnectState = 0x0
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: 0
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 1
E/NxpNfcJni( 1784): getReconnectState = 0x0
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1370): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{10026f80 type 2 when 161222 com.android.systemui} when 161222
,D/PhoneUtils( 1747): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1747): getCallState : 0
,D/PhoneUtils( 1747): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1370): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1370): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 173761626345; DSPS: 5791905; Offset : -2994885993
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  837): battery changed pluggedType: 2
V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{c02a9b9 type 2 when 187455 com.google.android.gms} when 187455
,I/PhenotypeConfigurator( 1729): Scheduling Phenotype for one-off execution 9327 seconds from now (1450100382139)
,D/GetConfigurationSnapshotOperation( 1729): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1729): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  837): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 1729): propertyValue:false
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/LocationManagerService(  837): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  837): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  837): android: cancelAsUser(2) by android
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     (  837): Explicit concurrent mark sweep GC freed 59012(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.264ms total 166.529ms
,D/LocationManagerService(  837): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  837): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  837): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{1ac47329 type 2 when 189916 android} when 189916
,D/LocationManagerService(  837): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  837): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 193762404463; DSPS: 6447291; Offset : -2994899562
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 213763240965; DSPS: 7102678; Offset : -2994886748
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  837): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 233763997520; DSPS: 7758063; Offset : -2994893628
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  481): init target 500000
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 253764829596; DSPS: 8413450; Offset : -2994884952
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 273765569848; DSPS: 9068834; Offset : -2994877278
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 293766238487; DSPS: 9724216; Offset : -2994879870
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  481): init target 500000
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  837): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1729): disconnect managed GoogleApiClient
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 313766907021; DSPS: 10379598; Offset : -2994882750
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 333767654669; DSPS: 11034983; Offset : -2994898223
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  837): remove 35581813
,D/LocationManagerService(  837): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  837): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  837): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  837): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  837): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  837): acquireWakeLockInternal: lock=802069523, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=837
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
D/PowerManagerServiceEx(  837): releaseWakeLockInternal: lock=802069523 [*alarm*], flags=0x0
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 353769534713; DSPS: 11690404; Offset : -2994879412
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  481): init target 500000
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 373770486737; DSPS: 12345796; Offset : -2994903899
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 393771252460; DSPS: 13001181; Offset : -2994900933
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  837): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 413771928388; DSPS: 13656563; Offset : -2994896678
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 433772598746; DSPS: 14311945; Offset : -2994897993
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6069): Connected to the server!
I/jxcore-log( 6069): 
,I/chromium( 6069): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 453773349206; DSPS: 14967329; Offset : -2994879617
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 473774128626; DSPS: 15622715; Offset : -2994893941
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  837): acquireWakeLockInternal: lock=802069523, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=837
,V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{2da7fc4f type 2 when 492676 android} when 492676
D/PowerManagerServiceEx(  837): releaseWakeLockInternal: lock=802069523 [*alarm*], flags=0x0
,I/NotificationManager(  837): android: cancelAsUser(-1874035846) by android
,I/NotificationManager(  837): android: cancelAsUser(2145784878) by android
,I/NotificationManager(  837): android: cancelAsUser(-1548111331) by android
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 493774987473; DSPS: 16278103; Offset : -2994889612
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 513775763403; DSPS: 16933488; Offset : -2994876698
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  837): acquireWakeLockInternal: lock=802069523, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=837
,V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{5bdc80c type 2 when 522948 android} when 522948
I/ActivityManager(  837): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7793 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 423us total 51.978ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 399us total 38.048ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 403us total 32.271ms
,I/DigitalAppWidgetProvider( 7793): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7793): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3c42acf8
D/PowerManagerServiceEx(  837): releaseWakeLockInternal: lock=802069523 [*alarm*], flags=0x0
,I/ActivityManager(  837): Killing 7103:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  837): failed to open /acct/uid_10061/pid_7103/cgroup.procs: No such file or directory
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 533776398968; DSPS: 17588869; Offset : -2994881664
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 553777061824; DSPS: 18244251; Offset : -2994890299
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 573777832286; DSPS: 18899636; Offset : -2994882595
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 593778520403; DSPS: 19555019; Offset : -2994896252
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 613779196021; DSPS: 20210401; Offset : -2994891969
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 633779935856; DSPS: 20865785; Offset : -2994884555
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 653781013349; DSPS: 21521180; Offset : -2994876168
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 673781783603; DSPS: 22176566; Offset : -2994898641
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 693782457293; DSPS: 22831948; Offset : -2994896493
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 713783311139; DSPS: 23487336; Offset : -2994896932
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  837): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 733784071496; DSPS: 24142721; Offset : -2994899592
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 753784738988; DSPS: 24798103; Offset : -2994903565
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 773785492470; DSPS: 25453487; Offset : -2994882140
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 793786158140; DSPS: 26108869; Offset : -2994888117
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 813786911934; DSPS: 26764254; Offset : -2994897029
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 833787584218; DSPS: 27419636; Offset : -2994896419
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 853788345252; DSPS: 28075021; Offset : -2994898428
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 873789013421; DSPS: 28730403; Offset : -2994901411
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 893789773831; DSPS: 29385788; Offset : -2994903758
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  837): battery changed pluggedType: 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 913790706896; DSPS: 30041178; Offset : -2994886403
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 933791381420; DSPS: 30696560; Offset : -2994883160
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  837): acquireWakeLockInternal: lock=802069523, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=837
,V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{a0a0555 type 2 when 952500 com.android.bluetooth} when 952500
D/PowerManagerServiceEx(  837): releaseWakeLockInternal: lock=802069523 [*alarm*], flags=0x0
,W/bt-smp  ( 1997): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1997): Plain text(LSB ~ MSB) = b0 0b 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1997): Encrypted text(LSB ~ MSB) = bc 3b 47 8f cf 74 9a bf 54 ea 86 3b c5 e3 ad c3 
W/bt-btm  ( 1997): Stopping oneshot timer
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 953792133599; DSPS: 31351945; Offset : -2994894625
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 973792807915; DSPS: 32007327; Offset : -2994891565
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 993793471084; DSPS: 32662709; Offset : -2994899158
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  837): acquireWakeLockInternal: lock=802069523, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=837
,V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{8a25b6a type 2 when 1012595 com.google.android.gms} when 1012595
,D/PowerManagerServiceEx(  837): releaseWakeLockInternal: lock=802069523 [*alarm*], flags=0x0
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1013794230295; DSPS: 33318094; Offset : -2994903278
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,W/ProcessCpuTracker(  837): Skipping unknown process pid 7888
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  837): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1033795082527; DSPS: 33973481; Offset : -2994874837
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1053795747155; DSPS: 34628863; Offset : -2994881206
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1073796592928; DSPS: 35284251; Offset : -2994890289
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  837): battery changed pluggedType: 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1093797415941; DSPS: 35939638; Offset : -2994891173
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1113798082028; DSPS: 36595020; Offset : -2994896577
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1133798853530; DSPS: 37250405; Offset : -2994887624
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1153799515138; DSPS: 37905787; Offset : -2994897689
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1173802856276; DSPS: 38561256; Offset : -2994884868
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1193803518716; DSPS: 39216638; Offset : -2994891730
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1213804273813; DSPS: 39872023; Offset : -2994900693
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  837): User[0] Flushing usage stats to disk
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1233805011357; DSPS: 40527407; Offset : -2994894713
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1253805773485; DSPS: 41182792; Offset : -2994897346
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1273806434727; DSPS: 41838173; Offset : -2994875177
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1293807193157; DSPS: 42493558; Offset : -2994879400
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1313807951690; DSPS: 43148943; Offset : -2994883832
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1333808692361; DSPS: 43804327; Offset : -2994876234
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1353809542769; DSPS: 44459715; Offset : -2994879927
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1373810603388; DSPS: 45115110; Offset : -2994887214
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1393811272390; DSPS: 45770492; Offset : -2994890668
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1413812066080; DSPS: 46425878; Offset : -2994889289
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1433812615551; DSPS: 47081256; Offset : -2994889421
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  837): battery changed pluggedType: 2
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1453813294867; DSPS: 47736638; Offset : -2994881517
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1473814154442; DSPS: 48392026; Offset : -2994876305
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1493814829539; DSPS: 49047408; Offset : -2994872750
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1513815596979; DSPS: 49702794; Offset : -2994898689
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1533816454004; DSPS: 50358182; Offset : -2994896052
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1553817166548; DSPS: 51013565; Offset : -2994885413
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1573817995602; DSPS: 51668952; Offset : -2994880541
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1593818857834; DSPS: 52324341; Offset : -2994903163
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1613819531837; DSPS: 52979723; Offset : -2994900469
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1633820486986; DSPS: 53635114; Offset : -2994891938
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1653821254218; DSPS: 54290499; Offset : -2994887124
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1673822122387; DSPS: 54945887; Offset : -2994873316
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1693822865192; DSPS: 55601272; Offset : -2994894572
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1713823535601; DSPS: 56256654; Offset : -2994894300
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1733824298145; DSPS: 56912039; Offset : -2994894799
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1753825049232; DSPS: 57567423; Offset : -2994876941
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1773825719120; DSPS: 58222805; Offset : -2994877763
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1793826492549; DSPS: 58878191; Offset : -2994897973
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1813827164573; DSPS: 59533573; Offset : -2994897934
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1833827934930; DSPS: 60188958; Offset : -2994889866
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  837): acquireWakeLockInternal: lock=802069523, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=837
,V/AlarmManager(  837): ELAPSED_WAKEUP set : Alarm{368558f8 type 2 when 1852647 com.android.bluetooth} when 1852647
,W/bt-smp  ( 1997): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1997): Plain text(LSB ~ MSB) = 38 f7 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1997): Encrypted text(LSB ~ MSB) = 3b 83 f9 5e 21 98 79 a5 d0 3c 51 b1 da d4 1d 02 
W/bt-btm  ( 1997): Stopping oneshot timer
I/ProcessStatsService(  837): Prepared write state in 18ms
,I/ProcessStatsService(  837): Prepared write state in 16ms
,I/DigitalAppWidgetProvider( 7793): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7793): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3c42acf8
,D/PowerManagerServiceEx(  837): releaseWakeLockInternal: lock=802069523 [*alarm*], flags=0x0
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1853828650444; DSPS: 60844341; Offset : -2994876204
,I/ProcessStatsService(  837): Pruning old procstats: /data/system/procstats/state-2015-12-13-11-41-30.bin
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  837): battery changed pluggedType: 2
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,V/AlarmManager(  837): RTC_WAKEUP set : Alarm{1fb2a1d1 type 0 when 1450101606441 com.google.android.gms} when 1450101606441
,D/LocationManagerService(  837): getAllProviders()=[passive, gps, network]
,I/EventLogService( 4205): Aggregate from 1450100304872 (log), 1450099806297 (data)
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  837): android: cancelAsUser(2) by android
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1729): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/PhenotypeConfigurator( 1729): Server returned 404
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1873829346998; DSPS: 61499724; Offset : -2994882335
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  837): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1997): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  837): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  837): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  837): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  837): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  837): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  837): tsOffsetIs: Apps: 1893830310845; DSPS: 62155116; Offset : -2994894114
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8080): 
D/AndroidRuntime( 8080): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8080): CheckJNI is OFF
D/AndroidRuntime( 8080): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  837): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  837): Killing 6069:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  837): WIN DEATH: Window{26f5683 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  837): Skipping PackageSetting{1189c2bb com.example.hello/10030} due to missing metadata
D/InputDispatcher(  837): Focus left window: Window{26f5683 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  837): Window went away: Window{26f5683 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ThermalEngine(  295): Sensor:pa_therm0:28000 mC
I/ActivityManager(  837):   Force finishing activity ActivityRecord{13b2333b u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  837): Display changed displayId=0
D/DSDPConnection( 1747): Display #0 changed.
W/ActivityManager(  837): Spurious death for ProcessRecord{282bd6ca 6069:com.test.thalitest/u0a316}, curProc for 6069: null
I/ActivityManager(  837): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  837):   Force finishing activity ActivityRecord{13b2333b u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  837): Duplicate finish request for ActivityRecord{13b2333b u0 com.test.thalitest/.MainActivity t220 f}
I/[LGHome]EVENT( 1874): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/art     ( 1932): Explicit concurrent mark sweep GC freed 9889(571KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 1.256ms total 90.791ms
I/art     ( 4205): Explicit concurrent mark sweep GC freed 1100(42KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/19MB, paused 11.010ms total 92.510ms
I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1729): Ignoring removeGeofence because network location is disabled.
I/InputReader(  837): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3602): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3602): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3602): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3602): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3602): 	at android.os.Handler.handleCallback(Handler.java:739)
I/[LGHome]EVENT( 1874): [Launcher.java:776:onResume()]onResume
W/System.err( 3602): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3602): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3602): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3602): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3602): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3602): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3602): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  837): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8113 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1874): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1874): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1874): [Launcher.java:929:onResume()]onResume end
I/Activity( 1874): Activity.onPostResume() called 
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
W/[LGHome]LGWallpaperInfo( 1874): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1874): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/art     (  837): Explicit concurrent mark sweep GC freed 58225(3MB) AllocSpace objects, 14(374KB) LOS objects, 33% free, 23MB/35MB, paused 2.602ms total 271.343ms
I/art     (  837): WaitForGcToComplete blocked for 242.326ms for cause Explicit
W/ResourcesManager( 8113): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8113): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8113): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
I/SystemUI[Framework](  837): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/InputDispatcher(  837): Focus entered window: Window{334c454 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
W/PhoneWindowManagerEx(  837): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  837): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  837): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@233bea84,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  837): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  837): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  837): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  837): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@233bea84,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  837): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): handleShortcutListChanged...
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/PhoneWindow( 1874): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
D/administrator(  837): Handling package changes for user 0
D/KeyguardModel( 1370): handleShortcutListChanged...
I/LGEmail ( 8113): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8113): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/NotificationService(  837): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  837): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  837): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  837): Explicit concurrent mark sweep GC freed 6980(425KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 6.695ms total 311.430ms
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister(  837): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
I/PackageChangeReceiver( 8113): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/AppUp4:PreloadHelper( 7360): added Exclude : com.test.thalitest
W/InputMethodManagerService(  837): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  837): Got RemoteException sending setActive(false) notification to pid 6069 uid 10316
D/AndroidRuntime( 8080): Shutting down VM
I/ActivityManager(  837): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8137 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  837): Killing 7382:com.android.gallery3d/u0a23 (adj 15): empty #11
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  837): failed to open /acct/uid_10023/pid_7382/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  837): Timeline: Activity_windows_visible id: ActivityRecord{1ee447e1 u0 com.lge.launcher2/.Launcher t219} time:1905873
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
W/IInputConnectionWrapper( 1874): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1621): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1874): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/ResourcesManager(  837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
W/ResourcesManager( 8137): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8137): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8137): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8137): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8137): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created

```
