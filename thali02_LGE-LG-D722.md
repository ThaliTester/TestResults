#### Test 50650278d6c551a_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/GAV2    ( 5856): Thread[GAThread,5,main]: No campaign data found.
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/AndroidRuntime( 6077): 
D/AndroidRuntime( 6077): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6077): CheckJNI is OFF
D/AlertService( 5901): Beginning updateAlertNotification
D/AlertService( 5901): No fired or scheduled alerts
I/NotificationManager( 5901): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5901): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5901): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5901): No events found starting within 1 week.
D/AndroidRuntime( 6077): Calling main entry com.android.commands.am.Am
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
--------- beginning of system
I/ActivityManager(  954): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  954): setTaskToReturnTo : TaskRecord{51f9e64 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  954): setTaskToReturnTo : TaskRecord{51f9e64 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  954): AppWindowTokenEx init.. 
D/ContextHelper(  954): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  954): Focus left window: Window{1d9115e9 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6077): Shutting down VM
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
I/ActivityManager(  954): Killing 5901:com.android.calendar/u0a13 (adj 15): empty #11
D/SplitWindow(  954): check instance of lgWin Window{6a427ce u0 Starting com.test.thalitest}
W/libprocessgroup(  954): failed to open /acct/uid_10013/pid_5901/cgroup.procs: No such file or directory
I/ActivityManager(  954): Killing 5669:com.google.android.talk/u0a61 (adj 15): empty #11
I/ActivityManager(  954): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6097 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  954): failed to open /acct/uid_10061/pid_5669/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1935): Closing mic
I/WindowStateAnimator(  954): Starting window displayed
I/MicrophoneInputStream( 1935): mic_close com.google.android.apps.gsa.speech.audio.u@2ae5236b
V/AudioRecord( 1935): stop()
D/AudioRecord( 1935): AudioRecord->stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioFlinger(  283): Record stopped OK
V/AudioPolicyManager(  283): stopInput() input 16
,V/AudioPolicyService(  283): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  283): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  283): ThreadBase::setParameters() routing=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb39e9000
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/SystemUI[Framework](  954): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
,D/PhoneStatusBar( 1364): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  954): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  954): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  954): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  954): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d2c973d,  pkg=WindowManager.LayoutParams
,I/SystemUI[Framework](  954): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1364): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1364):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1364): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/BarTransitions( 1364): draw background and invalidate : color = 13000000
D/BarTransitions( 1364): draw background and invalidate : color = 14131313
V/audio_hw_primary(  283): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  283): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  283): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  283): disable_audio_route: exit
E/audio_hw_primary(  283): disable_snd_device: enter 144
D/hardware_info(  283): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  283): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  283): stop_input_stream: exit: status(0)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  283): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  283): setParameters(): io 16, keyvalue hotword_active=0, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb39e9000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioRecord( 1935): stop()
,V/AudioRecord( 1935): stop()
V/AudioRecord( 1935): stop()
V/AudioFlinger(  283): releasing 15 from 1935 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioPolicyManager(  283): releaseInput() 16
V/AudioPolicyManager(  283): closeInput(16)
V/AudioFlinger(  283): closeInput() 16
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  283): ThreadBase::exit
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): RecordThread 0xb39e9000 exiting
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/AudioSystem( 1364): ioConfigChanged() event 4, ioHandle 16
,V/AudioSystem( 1748): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1935): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  954): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1987): ioConfigChanged() event 4, ioHandle 16
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioSystem( 2665): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 3216): ioConfigChanged() event 4, ioHandle 16
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  283): removeClient_l() pid 1935, calling pid 283
I/HotwordRecognitionRnr( 1935): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1935): Hotword detection finished
D/ContextHelper( 6097): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6097): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/ActivityManager(  954): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  954): RTC_WAKEUP set : Alarm{58d5e8 type 0 when 1449495526535 com.android.providers.contacts} when 1449495526535
V/AlarmManager(  954): ELAPSED_WAKEUP set : Alarm{106ff401 type 2 when 60067 com.google.android.talk} when 60067
I/ActivityManager(  954): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6129 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/LibraryLoader( 6097): Time to load native libraries: 2 ms (timestamps 4329-4331)
I/LibraryLoader( 6097): Expected native library version number "",actual native library version number ""
V/AlarmManager(  954): RTC_WAKEUP set : Alarm{1531c4e7 type 0 when 1449754783673 com.android.vending} when 1449754783673
,D/Finsky  ( 5592): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/WebViewChromiumFactoryProvider( 6097): Binding Chromium to main looper Looper (main, tid 1) {253dff5c}
,I/LibraryLoader( 6097): Expected native library version number "",actual native library version number ""
I/chromium( 6097): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6129): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/BrowserStartupController( 6097): Initializing chromium process, singleProcess=true
W/art     ( 6097): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6097): ApplicationContext is null in ApplicationStatus
,I/NotificationManager(  954): android: cancelAsUser(2) by android
,W/chromium( 6097): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6097): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6097): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6097): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6097): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6097): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6097): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6097): Remote Branch: 
I/Adreno-EGL( 6097): Local Patches: 
I/Adreno-EGL( 6097): Reconstruct Branch: 
I/ActivityManager(  954): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6154 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/AudioPolicyService(  283): registerClient() client 0xb4027980, uid 10316
,D/BluetoothManagerService(  954): Message: 20
D/BluetoothManagerService(  954): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1103a52e:true
D/BluetoothAdapterService(358200648)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@a4ceade
,I/GservicesProvider( 6154): Gservices pushing to system: true; secure/global: true
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 94711417989; DSPS: 3201688; Offset : -3002048831
W/art     ( 6097): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6097): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6097): CordovaWebView is running on device made by: LGE
,I/GoogleHttpClient( 6154): GMS http client unavailable, use old client
W/art     ( 6097): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6097): Attempt to remove local handle scope entry from IRT, ignoring
I/GoogleHttpClient( 6154): GMS http client unavailable, use old client
,I/art     ( 6129): CheckpointMarkThreadRoots callback created = 0xb042d370
I/Activity( 6097): Activity.onPostResume() called 
,D/OpenGLRenderer( 6097): Render dirty regions requested: true
I/OpenGLRenderer( 6097): Initialized EGL, version 1.4
D/OpenGLRenderer( 6097): Enabling debug mode 0
,I/art     ( 6129): CheckpointMarkThreadRoots callback created = 0xb042d340
,I/Babel_SMS( 6129): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6129): MmsConfig.loadMmsSettings
I/Babel_SMS( 6129): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6129): MmsConfig.loadFromDatabase
D/Atlas   ( 6097): Validating map...
D/SplitWindow(  954): check instance of lgWin Window{3b577378 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/chromium( 6097): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/libc-netbsd( 5592): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5592): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5592): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5592): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 5592): propertyValue:false
D/libc-netbsd( 5592): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5592): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/Babel_SMS( 6129): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6129): MmsConfig.loadFromResources
E/Babel_SMS( 6129): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6129): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/InputDispatcher(  954): Focus entered window: Window{3b577378 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/SensorManager( 6129): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6129): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6129): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6129): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6129): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6129): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6129): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6129): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6129): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6129): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6129): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6129): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6129): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6129): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6129): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6129): found sensor: Motion Accel, handle=46
,W/InputMethodManagerService(  954): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  954): Displayed com.test.thalitest/.MainActivity: +1s217ms
I/Timeline(  954): Timeline: Activity_windows_visible id: ActivityRecord{361118cd u0 com.test.thalitest/.MainActivity t220} time:95071
,W/Settings( 6129): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Timeline( 6097): Timeline: Activity_idle id: android.os.BinderProxy@23aafddb time:95081
I/Babel_Crash( 6129): startup - clean
,D/libc-netbsd( 5592): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,I/Babel   ( 6129): deleted: false for 0
D/libc-netbsd( 5592): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:44.564 DNS addrs= 192.168.1.1, 0.0.0.0, 
,W/AudioCapabilities( 6129): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6129): Unsupported mime audio/adpcm
W/AudioCapabilities( 6129): Unsupported mime audio/g726
W/AudioCapabilities( 6129): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6129): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6129): Unsupported mime video/mjpg
W/VideoCapabilities( 6129): Unsupported mime video/theora
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/AudioCapabilities( 6129): Unsupported mime audio/evrc
,W/BindingManager( 6097): Cannot call determinedVisibility() - never saw a connection for the pid: 6097
W/AudioCapabilities( 6129): Unsupported mime audio/qcelp
W/VideoCapabilities( 6129): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6129): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6129): Unsupported mime audio/qcelp
W/AudioCapabilities( 6129): Unsupported mime audio/evrc
,W/VideoCapabilities( 6129): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6129): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6129): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6129): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6129): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6129): Unrecognized profile 2130706433 for video/avc
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  954): android: cancelAsUser(2) by android
,W/art     ( 6129): Suspending all threads took: 35.963ms
,I/qtaguid ( 5592): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5592): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5592): untagSocket(41) failed with errno -22
,D/Finsky  ( 5592): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/vclib   ( 6129): onServiceConnected
,W/Babel   ( 6129): Attempted to change video mute state without an active call.
W/ResourcesManager( 6129): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6129): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  954): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6218 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 6129): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/NotificationManager(  954): android: cancelAsUser(2) by android
,W/System  ( 6129): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6129): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  954): Process com.android.contacts (pid 5777) has died
,W/ResourcesManager( 6218): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6218): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 4204): Explicit concurrent mark sweep GC freed 80065(5MB) AllocSpace objects, 32(512KB) LOS objects, 24% free, 14MB/18MB, paused 1.095ms total 150.464ms
,I/art     ( 4204): WaitForGcToComplete blocked for 110.040ms for cause HomogeneousSpaceCompact
I/NotificationManager( 6129): com.google.android.talk: cancel(10436) by com.google.android.talk
I/MultiDex( 6218): VM with version 2.1.0 has multidex support
I/MultiDex( 6218): install
I/MultiDex( 6218): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6218): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/JsMessageQueue( 6097): Set native->JS mode to OnlineEventsBridgeMode
W/SQLiteConnectionPool( 4204): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/ActivityThread( 6218): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6218): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@152b303e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6218): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6218): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6218): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,D/LocationInitializer( 4204): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1731): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5592): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5592): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5592): untagSocket(41) failed with errno -22
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 6218): Reading stored module config
W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
D/ChimeraCfgMgr( 6218): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/jxcore_app_log( 6097): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622792704
,D/JX-Cordova( 6097): jxcore cordova android initializing
D/UEI.SmartControl( 6014): Internal timer expired: 1
,D/CAR.SERVICE( 6218): Connecting to CarCallService...
,D/NativeLibraryUtils( 6218): Install completed successfully. count=14 extracted=0
,I/art     ( 6218): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6218): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6097): CheckpointMarkThreadRoots callback created = 0x9a95f470
,D/CAR.SERVICE( 6218): com.google.android.projection.gearhead isn't installed.
,I/art     ( 6097): CheckpointMarkThreadRoots callback created = 0x9a95f440
D/CAR.TEL.Service( 6218): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6218): Creating a new PhoneAdapter instance
W/ActivityManager(  954): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6218): setListener: com.google.android.gms.car.dn@39fd0c25
W/ActivityManager(  954): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6218): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6218): Starting CarCallService with initial phone null
,I/art     ( 5592): CheckpointMarkThreadRoots callback created = 0xb0566860
,I/art     ( 5592): CheckpointMarkThreadRoots callback created = 0xb0566830
,I/NotificationManager( 6218): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6218): Package validated; name: com.android.vending
,I/NotificationManager( 5592): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5592): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     (  954): Explicit concurrent mark sweep GC freed 32898(1599KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.264ms total 161.780ms
,I/ActivityManager(  954): Process com.android.gallery3d (pid 5970) has died
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  954): android: cancelAsUser(2) by android
,I/qtaguid ( 5592): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5592): Untagging socket 41 failed errno=-22
,W/NetworkManagementSocketTagger( 5592): untagSocket(41) failed with errno -22
W/ResourcesManager( 5592): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5592): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5592): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5592): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 5592): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  954): RTC_WAKEUP set : Alarm{c3f3d4e type 0 when 1449754787322 com.android.vending} when 1449754787322
,D/DeviceConnectionService( 1731): client connected with version: 8296000
D/Finsky  ( 5592): [689] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  954): android: cancelAsUser(2) by android
,D/libc-netbsd( 5592): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5592): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5592): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5592): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 5592): propertyValue:false
W/jxcore-log( 6097): Initializing JXcore engine
,W/jxcore-log( 6097): JXcore engine is ready
W/jxcore-log( 6097): Starting JXcore engine
,W/.test.thalitest( 6097): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6600]" dev="sockfs" ino=6600 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6097): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6097): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5062]" dev="sockfs" ino=5062 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6097): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6097): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6097): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28774]" dev="sockfs" ino=28774 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,W/jxcore-log( 6097): Platform android
W/jxcore-log( 6097): 
W/jxcore-log( 6097): Process ARCH arm
W/jxcore-log( 6097): 
D/libc-netbsd( 5592): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5592): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5592): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5592): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 5592): propertyValue:false
V/AlarmManager(  954): RTC_WAKEUP set : Alarm{3601a826 type 0 when 1449754788475 com.google.android.googlequicksearchbox} when 1449754788475
,E/PlayEventLogger( 5592): Status 503 without retry-after header
,I/jxcore-log( 6097): JXcore Cordova bridge is ready!
I/jxcore-log( 6097): 
W/jxcore-log( 6097): JXcore engine is started
,I/Choreographer( 6097): Skipped 196 frames!  The application may be doing too much work on its main thread.
I/chromium( 6097): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:50.591 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  954): Killing 5800:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_10069/pid_5800/cgroup.procs: No such file or directory
,I/jxcore-log( 6097): Toggling radios to true
I/jxcore-log( 6097): 
,D/BluetoothAdapter( 6097): enable(): BT is already enabled..!
D/WifiServiceImplEx(  954): setWifiEnabled: true pid=6097, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  954): setWifiEnabled: true pid=6097, uid=10316
,D/WifiServiceImplEx(  954): disconnect pid=6097, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  954): reconnect pid=6097, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6097): Radios toggled
I/jxcore-log( 6097): 
D/BluetoothManagerService(  954): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6097): Got Device Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 6097): 
I/jxcore-log( 6097): Perf Test app loaded loaded
I/jxcore-log( 6097): 
,I/Choreographer( 6097): Skipped 113 frames!  The application may be doing too much work on its main thread.
I/wpa_supplicant( 2802): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/jxcore-log( 6097): check test folder
I/jxcore-log( 6097): 
,I/jxcore-log( 6097): found test : ./testFindPeers.js
I/jxcore-log( 6097): 
I/wpa_supplicant( 2802): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,E/WifiStateMachine(  954): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  954): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
D/WfdsMonitor( 1802): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/jxcore-log( 6097): found test : ./testSendData.js
I/jxcore-log( 6097): 
,D/LGWifiP2pService(  954): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  954): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  954): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  279): Clearing all IP addresses on wlan0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 10
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/NativeCrypto( 1731): Read error: ssl=0xaaede000: I/O error during system call, Connection timed out
D/ConnectivityService(  954): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  954): ignoring duplicate network state non-change
D/WifiHS20(  954): hidePasspointNotification off =false
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:51.119 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  954): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/NativeCrypto( 1731): SSL shutdown failed: ssl=0xaaede000: I/O error during system call, Broken pipe
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  954): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): ValidatedState{ when=-4ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): DefaultState{ when=-9ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): Forcing reevaluation
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/ActivityManager(  954): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6301 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/WifiStateMachine(  954): Start Disconnecting Watchdog 1
,D/WifiHS20(  954): hidePasspointNotification off =false
I/wpa_supplicant( 2802): wlan0: CTRL-EVENT-SCAN-STARTED 
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  954): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  954): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/ConnectivityService(  954): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  954): disableDataServiceNotify
D/DSQN    (  954): stop dsqn bin
D/WifiHS20(  954): hidePasspointNotification off =false
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  954): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  954):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  954):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  954): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/Nat464Xlat(  954): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): Disconnected - quitting
D/CSLegacyTypeTracker(  954): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  954): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  954): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  954): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  954): MasterInitialState.processMessage what=3
D/ConnectivityService(  954): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  954): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  954): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  954): MasterInitialState.processMessage what=3
V/NetworkPolicy(  954): [LG_RESTRICTED] !!!isConnected  type  :1
,D/ConnectivityService(  954): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  954): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:51.256 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityManager.CallbackHandler( 1364): CM callback handler got msg 524292
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:51.26 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/QCNEJ   ( 1838): |CORE| No family connected
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  954): Removing idletimer
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/TelephonyNetworkFactory-1( 1748): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
W/Settings(  954): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
,D/WifiNetworkAgent(  954): NetworkAgent: NetworkAgent channel lost
D/WifiHS20(  954): hidePasspointNotification off =false
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:51.281 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WIFI    (  954): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  954):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:51.286 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  954): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  954): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  954): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  954): setSupplicantStateSCANNING
D/TelephonyIcons( 1364): null signal icon name: drawable/stat_sys_signal_null
I/chromium( 6097): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/[SystemUI]LGNetworkController( 1364): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/DhcpStateMachine(  954): StoppedState
D/DhcpStateMachine(  954): StoppedState{ when=-99ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/TelephonyIcons( 1364): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1364): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
W/ResourcesManager( 6301): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6301): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6301): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6301): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6301): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager(  954): Process com.google.android.gm (pid 5856) has died
,D/CAR.SERVICE( 6218): mConnectedToCar = false, abort
E/ActivityThread( 6218): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@212bbc6d that was originally bound here
E/ActivityThread( 6218): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@212bbc6d that was originally bound here
E/ActivityThread( 6218): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6218): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6218): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6218): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6218): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6218): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6218): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6218): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6218): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6218): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6218): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6218): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6218): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6218): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6218): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6218): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6218): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6218): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6218): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6218): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6218): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6218): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6218): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6218): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1430681c that was originally bound here
E/ActivityThread( 6218): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1430681c that was originally bound here
E/ActivityThread( 6218): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6218): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6218): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6218): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6218): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6218): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6218): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6218): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6218): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6218): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6218): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6218): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6218): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6218): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6218): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6218): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6218): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6218): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6218): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6218): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6218): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6218): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  954): Unbind failed: could not find connection for android.os.BinderProxy@33545c67
I/IndexDatabaseHelper( 6301): Using schema version: 115
,I/IndexDatabaseHelper( 6301): Index is fine
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
I/ActivityManager(  954): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6328 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6328): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6328): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6328): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6328): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
I/ActivityManager(  954): Killing 5516:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_10086/pid_5516/cgroup.procs: No such file or directory
,V/AlarmManager(  954): ELAPSED_WAKEUP set : Alarm{2dbcea14 type 2 when 102859 com.google.android.gms} when 102859
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  954): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2802): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LocSvc_java(  954): onReceive
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:52.376 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2802): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:52.389 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
,D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  954): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  954): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  954): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  954): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
D/WiFiOffLoadBroadcast( 6301): Not supported operator for automatic switch
,I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:52.416 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/wpa_supplicant( 2802): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2802): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:52.425 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  954): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  954): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServiceExtension(  954): setVHTCapabilityType  : false
D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt(  954): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  954): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  954): setSecurityType  : 2
D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:52.479 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:52.484 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService(  954): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  954): Got NetworkAgent Messenger
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  954): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  954): NetworkAgent connected
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
E/WifiConfigStore(  954): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
,D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
E/WifiConfigStore(  954): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Setting iface cfg
E/WifiStateMachine(  954): Start Dhcp Watchdog 2
D/DhcpStateMachine(  954): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  954): WaitBeforeStartState
D/WifiServerServiceExt(  954): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  954): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  954): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
E/WifiStateMachine(  954): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  954): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  954): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@113e1102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  954): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@113e1102 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  954): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  954): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  954): DHCP Start wake lock is acquired.
D/CommandListener(  279): Setting iface cfg
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  954): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  954): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  954): setSupplicantStateCOMPLETED
D/ConnectivityService(  954): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  954): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  954): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  954): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  954): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  954): ignoring duplicate network state non-change
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
,W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:52.64 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:52.647 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  954): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  954): Adding iface wlan0 to network 101
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
D/WifiHS20(  954): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:52.663 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
E/WifiStateMachine(  954): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  954): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:52.672 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
E/ConnectivityService(  954): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  954): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  954): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  279): netlink response contains error (File exists)
D/ConnectivityService(  954): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  954): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  954): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  954): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  954): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  954): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  954): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  954): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  954):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  954):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  954):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  954):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  954):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  954): currentScore = 0, newScore = 20
D/ConnectivityService(  954):    accepting network in place of null
D/ConnectivityService(  954): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WIFI    (  954): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  954):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1748): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1364): mWifiConnected = true, mWifiLevel = 2
E/ConnectivityService(  954): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  954): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  954): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  954): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  954): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  954): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  954): validation of new default Network = false
D/ConnectivityService(  954): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  954): enableDataServiceNotify 
D/DSQN    (  954): start dsqn bin
D/Tethering(  954): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): [LWD] Start DNSResolver start to wait
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1364): Remote
D/ConnectivityService(  954): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  954):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  954):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  954): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1364): CM callback handler got msg 524290
D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
I/DSQN    ( 6368): DSQN samuel.seo ver 141203
E/DSQN    ( 6368): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 6368): created command queue thread
I/DSQN    ( 6368): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6368): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): [LWD] wait 500ms before dns check
V/NetworkPolicy(  954): [LG_RESTRICTED] checkMobilePolicy_type()
,V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
,D/TelephonyIcons( 1364): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1364): updateLGTelephonySignalStrength : !hasService()
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/DhcpStateMachine(  954): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  954): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  954): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/dhcpcd  ( 6372): version 5.5.6 starting
E/dhcpcd  ( 6372): get_duid: Read-only file system
V/WiFiOffLoadBroadcast( 6301): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6301): MCCMNC not supported: null
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/dhcpcd  ( 6372): wlan0: rebinding lease of 192.168.1.134
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/dhcpcd  ( 6372): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6372): wlan0: leased 192.168.1.134 for 86400 seconds
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): [LWD] DNSResolver start dns
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out(  954): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6368): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6368): restart monitoring
,I/DSQN    ( 6368): dsqn report finish
D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  954): DSQM DsqnNotification wlan0  1
D/DSQN    (  954): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 13:39:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449754793328], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449754793309]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  954): Validated
D/ConnectivityService(  954): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  954): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  954):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  954):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  954):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  954): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  954): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  954):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  954):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  954): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  954): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  954): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  954): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/WifiServerServiceExt(  954): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  954): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1364): CM callback handler got msg 524290
D/WIFI    (  954):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyIcons( 1364): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1364): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  954): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  954): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  954): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  954): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  954): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  954): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  954): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  954): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  954): RunningState
I/NotificationManager( 1935): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  954): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  954): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  954): identical MTU - not setting
D/Nat464Xlat(  954): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  954): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  954):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  954):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:53.984 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  954): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  954): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  954): enableDataServiceNotify 
D/DSQN    (  954): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1364): CM callback handler got msg 524295
D/DSQN    (  954): dsqn is running restart
,I/DSQN    ( 6428): DSQN samuel.seo ver 141203
,E/DSQN    ( 6428): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6428): created command queue thread
I/DSQN    ( 6428): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6428): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityService(  954): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  954): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  954): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  954): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6435 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LocSvc_java(  954): onReceive
D/LocSvc_java(  954): got connectivity action
I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  954): broadcast - no network connections
D/LocSvc_java(  954): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  954): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  954): onReceive
D/LocSvc_java(  954): got connectivity action
D/LocSvc_java(  954): broadcast - no network connections
D/LocSvc_java(  954): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  954): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  954): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  954): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  954): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  954): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  954): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  954): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  954): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  954): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  954): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  954): ELAPSED_WAKEUP set : Alarm{20d6c729 type 2 when 105045 com.google.android.gms} when 105045
,I/MusicStore( 6435): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6435): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6435): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6435): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6435): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6435): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6435): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6435): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6435): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@304bd911: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6435): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6435): GMSCore installation verified
I/ConfigStore( 6435): Config Database version: 1
,I/MediaRouter( 6435): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6435): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6435): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6435): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  954): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6486 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/GHttpClientFactory( 6435): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6435): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6486): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6486): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6486): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  954): Killing 6036:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  954): failed to open /acct/uid_10014/pid_6036/cgroup.procs: No such file or directory
I/NotificationManager( 6435): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 6486): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6486): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 14:39:55.541 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/WifiInternetCheck(  954): Single check msg out of sync, ignoring.
D/eas_req ( 6486): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/ConnectivityService(  954): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  954): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6526 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/LocSvc_java(  954): onReceive
D/LocSvc_java(  954): got connectivity action
D/LocSvc_java(  954): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  954): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  954): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  954): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  954): ignore wifi update if we are not in OPENING or CLOSING
,I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 25.417ms
D/GpsLocationProvider(  954): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  954): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/[SystemUI]QuickSettingsHandler( 1364): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 25.914ms
I/NetworkMonitor( 6435): type=WIFI subType= reason=null isConnected=true
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.575ms
,I/ActivityManager(  954): Process com.google.android.talk (pid 6129) has died
,I/HubEmail( 6486): JNI_OnLoad()
I/HubEmail( 6486): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6486): registerNatives()
I/HubEmail( 6486): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6486): registerNativeMethods()
I/HubEmail( 6486): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6486): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6486): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6526): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6526): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6526): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6526): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/BluetoothAdapterService(358200648)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@a4ceade
I/jxcore-log( 6097): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6097): 
,D/LGDMClient( 6526): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6526): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6526): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6526): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  954): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6561 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6526): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6526): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6526): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6526): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6526): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6526): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  954): Killing 6218:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  954): failed to open /acct/uid_10006/pid_6218/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6561): onCreate
,W/AppUp4:DB( 6561):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6561):  setFingerPrint start
,I/AppUp4:DB( 6561):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6561):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6561):  SDK version = 0
I/AppUp4:DB( 6561):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6561): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6561): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6561): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6561): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6561): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6561): onReceive
I/AppUp4:CustModeStarterReceiver( 6561): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6561): Context : android.app.ReceiverRestrictedContext@1c5bf265
D/AppUp4:CustFacade( 6561): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6561): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6561): begin check event
I/AppUp4:CustModeStarterReceiver( 6561): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6561): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6561): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6561): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6561): handleAsyncCustNotification do not startCustService
I/ActivityManager(  954): Killing 5592:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_10036/pid_5592/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3216): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3216): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3216): networkInfo.isConnected() = false
I/ActivityManager(  954): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6584 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6584): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6584): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6584): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  954): Killing 6301:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  954): failed to open /acct/uid_1000/pid_6301/cgroup.procs: No such file or directory
,V/DownloadManager( 3242): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3242): DownloadService onCreate
D/PhoneMonitor( 6584): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6584): [loadFeatureFromXml] *** start feature loading from xml
I/CheckinService( 4204): Checkin interval check for package: unspecified last checkin: 1449754767527 min interval config: 0 actual interval: 28909
I/DownloadManager( 3242): in removeSpuriousFiles
D/TelephonyAutoProfiling( 6584): [parse] Load xml
I/NotificationManager( 3242): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/TelephonyAutoProfiling( 6584): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6584): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/PhoneMonitor( 6584): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@30993c0 on behalf of 3242
I/DownloadManager( 3242): in trimDatabase
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@152b303e on behalf of 3242
I/ActivityManager(  954): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6608 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3242): DownloadService onStartCommand
,V/DownloadManager( 3242): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 4204): Checking schedule, now: 1449754796480 next: 1449754797472
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@d42bec on behalf of 3242
I/CheckinService( 4204): active receiver: disabled
,V/DownloadManager( 3242): DownloadService onDestroy
,I/ActivityManager(  954): Killing 6014:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5035): android.os.DeadObjectException
W/System.err( 5035): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5035): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 5035): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5035): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5035): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5035): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5035): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5035): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5035): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5035): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5035): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5035): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5035): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5035): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5035): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5035): android.os.DeadObjectException
W/System.err( 5035): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5035): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5035): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5035): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5035): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5035): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5035): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5035): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5035): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5035): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5035): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5035): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5035): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5035): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5035): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  954): failed to open /acct/uid_10089/pid_6014/cgroup.procs: No such file or directory
,W/ActivityManager(  954): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/WeatherAncestor( 2644): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:39:56
I/ActivityManager(  954): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6625 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UpdateThreadPoolManager( 2644): 2 : This is isUpdating : false
D/WeatherAncestor( 2644): connectivity changed - connection : true
D/Weather_cast( 2644): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2644): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:39:56
D/WeatherService( 2644): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  954): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6642 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  954): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2644): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2644): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2644): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6625): Quickset Services start...
,I/UEI.SmartControl( 6625): Manufacture = LGE
D/UEI.SmartControl( 6625): File observer start...
E/UEI.SmartControl( 6625): IR Port is disabled: false
D/UEI.SmartControl( 6625): Starting file observer...
D/UEI.SmartControl( 6625): Extracting JNI libs...
,D/UEI.SmartControl( 6625): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6642): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  954): propertyValue:false
,D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  954): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  954): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  954): propertyValue:false
I/DSQN    ( 6428): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6428): restart monitoring
,I/DSQN    ( 6428): dsqn report finish
D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  954): DSQM DsqnNotification wlan0  1
D/DSQN    (  954): start to monitor internet connection
D/UEI.SmartControl( 6625): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6625): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6625): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/WifiInternetCheck(  954): isHttpConnectionAvailable - We got a valid response : 204
I/UEI.SmartControl( 6625): --- Selecting new region: 2
,I/UEI.SmartControl( 6625): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6625): Platform has CIR...
D/UEI.SmartControl( 6625): NO CIR support, need to check package...
I/UEI.SmartControl( 6625): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6625): QS Service created
I/Babel_SMS( 6642): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6642): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6642): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6642): MmsConfig.loadFromDatabase
E/UEI.SmartControl( 6625): QS start get config
,E/Babel_SMS( 6642): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6642): MmsConfig.loadFromResources
E/Babel_SMS( 6642): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6642): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/UEI.SmartControl( 6625): Loading JNI Libs...
,D/UEI.SmartControl( 6625):  configuring local db...
,D/SensorManager( 6642): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6642): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6642): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6642): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6642): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6642): found sensor: LGE Linear Acceleration Sensor, handle=30
,D/SensorManager( 6642): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6642): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6642): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6642): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6642): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6642): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6642): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6642): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6642): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6642): found sensor: Motion Accel, handle=46
I/art     ( 6642): CheckpointMarkThreadRoots callback created = 0xb042d880
,W/Settings( 6642): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6642): startup - clean
I/art     ( 6642): CheckpointMarkThreadRoots callback created = 0xb042d860
,I/Babel   ( 6642): deleted: false for 0
,I/ActivityManager(  954): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6680 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6625):  ---- Has DB8: true
W/AudioCapabilities( 6642): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6642): Unsupported mime audio/adpcm
W/AudioCapabilities( 6642): Unsupported mime audio/g726
W/AudioCapabilities( 6642): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6642): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6642): Unsupported mime video/mjpg
D/UEI.SmartControl( 6625): QS start statue = true Error code = 0
D/UEI.SmartControl( 6625): QS version = v2.7.11.1_RC1
W/VideoCapabilities( 6642): Unsupported mime video/theora
D/UEI.SmartControl( 6625): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6625): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6625): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6625): IrrcClient ++ 
D/irrcClient( 6625): getIrrcService ++ 
,D/irrcClient( 6625): getIrrcService -- 
D/irrcClient( 6625): IrrcClient -- 
W/irrc_jni( 6625): IRRCPlayer_nativeInit -- 
W/AudioCapabilities( 6642): Unsupported mime audio/evrc
W/AudioCapabilities( 6642): Unsupported mime audio/qcelp
W/VideoCapabilities( 6642): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 6625): Services init done
,I/UEI.SmartControl( 6625): Device manager: loading config....
W/AudioCapabilities( 6642): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6642): Unsupported mime audio/qcelp
W/AudioCapabilities( 6642): Unsupported mime audio/evrc
,D/UEI.SmartControl( 6625): Config is loaded...
W/VideoCapabilities( 6642): Unsupported mime video/mp4v-esdp
,D/UEI.SmartControl( 6625):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6625): Notify AllClients services are ready: 0
I/VideoCapabilities( 6642): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6642): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6642): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6642): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6642): Unrecognized profile 2130706433 for video/avc
,I/art     (  954): Explicit concurrent mark sweep GC freed 82499(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.515ms total 201.202ms
,D/UEI.SmartControl( 6625): QS Service init finished
D/UEI.SmartControl( 6625): QS Service version name: 0.1.73
D/UEI.SmartControl( 6625): QS Service version code: 1073
D/UEI.SmartControl( 6625): Service requested: Control
I/ActivityManager(  954): Process com.google.android.music:main (pid 6435) has died
,D/UEI.SmartControl( 6625): -----IControl: 11
D/UEI.SmartControl( 6625): Internal service binding...
D/UEI.SmartControl( 6625): Caller: com.lge.qremote
D/UEI.SmartControl( 6625): ------------ IControl registerCallback...
I/UEI.SmartControl( 6625): Registering callback...
D/UEI.SmartControl( 6625): -----IControl: 19
D/UEI.SmartControl( 6625): Caller: com.lge.qremote
I/UEI.SmartControl( 6625): Registering Services Ready callback...
I/vclib   ( 6642): onServiceConnected
W/Babel   ( 6642): Attempted to change video mute state without an active call.
I/UEI.SmartControl( 6625): Notify client services are ready...
,D/UEI.SmartControl( 6625): -----IControl: 8
D/UEI.SmartControl( 6625): Caller: com.lge.qremote
D/libc-netbsd( 6642): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6642): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6642): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6642): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6642): propertyValue:false
I/NotificationManager( 6642): com.google.android.talk: cancel(10436) by com.google.android.talk
I/Babel   ( 6642): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  954): Killing 6328:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  954): failed to open /acct/uid_1000/pid_6328/cgroup.procs: No such file or directory
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6680): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6680): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6680): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6680): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6680): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6680):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6680):   adb logcat -s GAv4
,W/GAv4    ( 6680): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6680): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6680): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/WebViewFactory( 6680): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6680): Time to load native libraries: 1 ms (timestamps 8914-8915)
,I/LibraryLoader( 6680): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6680): Binding Chromium to main looper Looper (main, tid 1) {11a224ee}
I/LibraryLoader( 6680): Expected native library version number "",actual native library version number ""
I/chromium( 6680): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6680): Initializing chromium process, singleProcess=true
,W/art     ( 6680): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6680): ApplicationContext is null in ApplicationStatus
W/chromium( 6680): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6680): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6680): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6680): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6680): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6680): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6680): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6680): Remote Branch: 
I/Adreno-EGL( 6680): Local Patches: 
I/Adreno-EGL( 6680): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb3ac6440, uid 10079
,I/NSApplication( 6680): Starting up...
W/AudioManagerAndroid( 6680): Requires BLUETOOTH permission
,I/ActivityManager(  954): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6749 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  954): Killing 5035:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  954): failed to open /acct/uid_10106/pid_5035/cgroup.procs: No such file or directory
,I/ActivityManager(  954): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6769 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  954): Killing 6486:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_10021/pid_6486/cgroup.procs: No such file or directory
,W/ResourcesManager( 6769): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  954): Killing 6526:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_1000/pid_6526/cgroup.procs: No such file or directory
,I/ActivityManager(  954): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6793 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6793): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6793): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6793): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6793): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6793): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6793): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6793): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6793): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6793): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@304bd911: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6793): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6793): GMSCore installation verified
I/ConfigStore( 6793): Config Database version: 1
,D/WeatherService( 2644): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:40:0
,D/WeatherService( 2644): 2 : TimeTick Intent And Screen On
D/WeatherService( 2644): 2 : SDK version : 21
W/ActivityManager(  954): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2644): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2644): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2644): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2644): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2644): 2 : This is isUpdating : false
D/WeatherService( 2644): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2644): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2644): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2644): 2 : Fixed theme : optimus
D/WeatherReflect( 2644): 2 : Map key string is -2
I/MediaRouter( 6793): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/lim     ( 2644): 2 : time = 14:40
V/MusicLeanback( 6793): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/WeatherReflect( 2644): Model Name : LG-D722
D/WeatherTheme( 2644): 2 : Different view - status_min_formatted : 39 != 40
D/WeatherTheme( 2644): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2644): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2644): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2644): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1364): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1364): called onTimeUpdated()
,I/[SystemUI]Clock( 1364): called onTimeUpdated()
I/NetworkMonitor( 6793): type=WIFI subType= reason=null isConnected=true
I/LgeClockWidgetControlView( 1364): called onTimeUpdated()
,I/[SystemUI]DateView( 1364): called onTimeUpdated()
I/[SystemUI]DateView( 1364): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1364): handleTimeUpdate
D/Weather4x2_optimus( 2644): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2644): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2644): forecast size is 0
,D/Theme   ( 2644): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2644): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2644): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2644): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2644): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2644): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2644): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2644): url is : null
D/Theme   ( 2644): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2644): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2644): 2 : update view, appWidgetId: 2
D/WeatherService( 2644): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:40:0
I/NetworkMonitor( 6793): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  954): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6827 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6793): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ResourcesManager( 6827): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6827): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/GoogleURLConnFactory( 6793): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 6827): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  954): Killing 6561:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_10011/pid_6561/cgroup.procs: No such file or directory
,I/NotificationManager( 6793): com.google.android.music: cancel(1061) by com.google.android.music
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/LGEmail ( 6827): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6827): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6827): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  954): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6862 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 345us total 29.680ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.650ms total 25.755ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 24.229ms
I/HubEmail( 6827): JNI_OnLoad()
I/HubEmail( 6827): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6827): registerNatives()
I/HubEmail( 6827): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6827): registerNativeMethods()
I/HubEmail( 6827): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6827): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  954): Killing 6584:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  954): failed to open /acct/uid_10038/pid_6584/cgroup.procs: No such file or directory
,W/Settings( 6827): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AlarmManager(  954): RTC_WAKEUP set : Alarm{8d3bd87 type 0 when 1449754797472 com.google.android.gms} when 1449754797472
,D/LGDMClient( 6862): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6862): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/AlarmManager(  954): RTC_WAKEUP set : Alarm{102608dd type 0 when 1449754800822 com.google.android.googlequicksearchbox} when 1449754800822
W/ContextImpl( 6862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6862): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6862): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6862): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  954): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6890 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6862): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6862): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6862): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6862): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6862): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  954): Killing 6608:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_10051/pid_6608/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6890): onCreate
,W/AppUp4:DB( 6890):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6890):  setFingerPrint start
I/AppUp4:DB( 6890):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6890):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6890):  SDK version = 0
I/AppUp4:DB( 6890):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6890): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6890): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6890): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6890): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6890): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6890): onReceive
I/AppUp4:CustModeStarterReceiver( 6890): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6890): Context : android.app.ReceiverRestrictedContext@1c5bf265
D/AppUp4:CustFacade( 6890): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6890): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6890): begin check event
I/AppUp4:CustModeStarterReceiver( 6890): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6890): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6890): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6890): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6890): handleAsyncCustNotification do not startCustService
I/ActivityManager(  954): Killing 6625:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  954): failed to open /acct/uid_10089/pid_6625/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3216): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3216): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3216): networkInfo.isConnected() = false
,I/ActivityManager(  954): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6914 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6914): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6914): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6914): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  954): Killing 6642:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 6914): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6914): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6914): [parse] Load xml
V/TelephonyAutoProfiling( 6914): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6914): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6914): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  954): failed to open /acct/uid_10061/pid_6642/cgroup.procs: No such file or directory
,V/DownloadManager( 3242): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3242): DownloadService onCreate
I/DownloadManager( 3242): in removeSpuriousFiles
,I/NotificationManager( 3242): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@30a6124a on behalf of 3242
I/DownloadManager( 3242): in trimDatabase
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@3f8485bb on behalf of 3242
I/ActivityManager(  954): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6936 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3242): DownloadService onStartCommand
V/DownloadManager( 3242): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@2e3b0916 on behalf of 3242
I/CheckinService( 4204): Checkin interval check for package: unspecified last checkin: 1449754767527 min interval config: 0 actual interval: 33863
,I/CheckinService( 4204): Checking schedule, now: 1449754801399 next: 1449754797472
I/CheckinService( 4204): active receiver: enabled
,I/CheckinService( 4204): Preparing to send checkin request
I/EventLogService( 4204): Accumulating logs since 1449754760538
V/DownloadManager( 3242): DownloadService onDestroy
,D/WeatherAncestor( 2644): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:40:1
,D/UpdateThreadPoolManager( 2644): 2 : This is isUpdating : false
D/WeatherAncestor( 2644): connectivity changed - connection : true
D/Weather_cast( 2644): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2644): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:40:1
D/WeatherService( 2644): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4204): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  954): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6956 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/ActivityThread( 4204): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  954): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6973 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  954): RTC_WAKEUP set : Alarm{20a6a313 type 0 when 1449754801522 com.android.vending} when 1449754801522
W/ActivityManager(  954): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2644): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2644): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2644): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6956): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     (  954): Explicit concurrent mark sweep GC freed 18858(1025KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.098ms total 192.911ms
,D/Finsky  ( 6973): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Babel_SMS( 6956): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6956): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6956): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6956): MmsConfig.loadFromDatabase
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel_SMS( 6956): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6956): MmsConfig.loadFromResources
E/Babel_SMS( 6956): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6956): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6956): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6956): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 6956): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6956): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6956): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6956): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6956): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6956): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6956): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6956): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6956): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6956): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6956): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6956): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6956): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6956): found sensor: Motion Accel, handle=46
,I/ActivityManager(  954): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7015 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     ( 6956): CheckpointMarkThreadRoots callback created = 0xb042d880
,W/Settings( 6956): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6956): startup - clean
,I/art     ( 6956): CheckpointMarkThreadRoots callback created = 0xb042d850
,I/Babel   ( 6956): deleted: false for 0
,D/Finsky  ( 6973): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 6973): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6973): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6973): com.android.vending: cancel(-1050172287) by com.android.vending
W/ResourcesManager( 7015): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7015): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 6973): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6973): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6973): Skipping gmscore version check
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
V/MusicLeanback( 6793): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
W/AudioCapabilities( 6956): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6956): Unsupported mime audio/adpcm
,D/LGDMClient( 6862): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6862): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/AudioCapabilities( 6956): Unsupported mime audio/g726
W/Settings( 6827): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
W/ContextImpl( 6862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/System.out( 1731): propertyValue:false
W/AudioCapabilities( 6956): Unsupported mime audio/x-ms-wma
I/NetworkStateForAutoUpdateMonitor( 6890): [onReceive] BroadcastReceiver onReceive
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@39760c84 on behalf of 6973
I/NetworkStateForAutoUpdateMonitor( 6890): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6890): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6890): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6890): onReceive
I/AppUp4:CustModeStarterReceiver( 6890): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6890): Context : android.app.ReceiverRestrictedContext@1c5bf265
D/AppUp4:CustFacade( 6890): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6890): isSimDevice : true
,W/AudioCapabilities( 6956): Unsupported mime audio/wma-voice
D/AppUp4:CustModeStarterReceiver( 6890): begin check event
I/AppUp4:CustModeStarterReceiver( 6890): Event For GoodConnectivity, noConnectivity : false, but skip! 
W/VideoCapabilities( 6956): Unsupported mime video/mjpg
D/LGDMClient( 6862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LgeMiscReceiver( 3216): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3216): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3216): networkInfo.isConnected() = true
I/LGDMClient( 6862): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/PhoneState( 3216): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 6914): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6914): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 6862): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6862): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/Finsky  ( 6973): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/VideoCapabilities( 6956): Unsupported mime video/theora
,V/DownloadManager( 3242): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3242): DownloadService onCreate
E/LGDMClient( 6862): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6862): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6862): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6862): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/WeatherAncestor( 2644): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:40:2
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UpdateThreadPoolManager( 2644): 2 : This is isUpdating : false
D/WeatherAncestor( 2644): connectivity changed - connection : true
D/LGDMClient( 6862): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
D/Weather_cast( 2644): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2644): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:40:2
D/WeatherService( 2644): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/NotificationManager( 3242): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3242): in removeSpuriousFiles
W/ActivityManager(  954): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2644): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2644): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2644): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3242): DownloadService onStartCommand
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@151ff133 on behalf of 3242
V/DownloadManager( 3242): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3242): in trimDatabase
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@3a896cf0 on behalf of 3242
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@3d54b269 on behalf of 3242
D/Finsky  ( 6973): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 7015): VM with version 2.1.0 has multidex support
,I/MultiDex( 7015): install
I/MultiDex( 7015): VM has multidex support, MultiDex support library is disabled.
W/AudioCapabilities( 6956): Unsupported mime audio/evrc
W/AudioCapabilities( 6956): Unsupported mime audio/qcelp
W/VideoCapabilities( 6956): Unrecognized profile 2130706433 for video/avc
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/DownloadManager( 3242): DownloadService onDestroy
W/AudioCapabilities( 6956): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6956): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6956): Unsupported mime audio/evrc
W/VideoCapabilities( 6956): Unsupported mime video/mp4v-esdp
,V/JNIHelp ( 7015): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/VideoCapabilities( 6956): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6956): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6956): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6956): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6956): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6956): onServiceConnected
,W/Babel   ( 6956): Attempted to change video mute state without an active call.
I/art     ( 6769): CheckpointMarkThreadRoots callback created = 0xb042d490
I/NotificationManager( 6956): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6956): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6956): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6956): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6956): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6956): propertyValue:false
,W/ActivityThread( 7015): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7015): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@152b303e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7015): Installed default security provider GmsCore_OpenSSL
I/art     ( 6769): CheckpointMarkThreadRoots callback created = 0xb042d460
I/NotificationManager( 7015): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7015): com.google.android.gms: cancel(39789) by com.google.android.gms
I/Babel   ( 6956): connection state changed from UNKNOWN to CONNECTED
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  954): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7064 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/art     ( 7015): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7015): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  954): Killing 6793:com.google.android.music:main/u0a81 (adj 15): empty #11
D/Finsky  ( 6973): [870] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6973): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
W/ResourcesManager( 7064): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/NativeLibraryUtils( 7015): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  954): failed to open /acct/uid_10081/pid_6793/cgroup.procs: No such file or directory
I/ActivityManager(  954): Killing 6827:com.lge.email/u0a21 (adj 15): empty #11
,D/WVCdm   (  283): Instantiating CDM.
,I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
W/libprocessgroup(  954): failed to open /acct/uid_10021/pid_6827/cgroup.procs: No such file or directory
,W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
,W/WVCdm   (  283): L1 library not specified. Falling Back to L3
D/BluetoothManagerService(  954): Message: 20
D/BluetoothManagerService(  954): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e569b12:true
,D/BluetoothAdapterService(358200648)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@a4ceade
D/BluetoothAdapterService(358200648)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@a4ceade
I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
D/WVCdm   (  283): PrepareKeyRequest: nonce=1974941829
I/ActivityManager(  954): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7083 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7064): Create singleton instance
,I/AudioManager( 7064): getMode name:com.lge.qremote
,I/CheckinService( 4204): Checkin interval check for package: unspecified last checkin: 1449754767527 min interval config: 0 actual interval: 35693
,D/UEI.SmartControl( 7083): Quickset Services start...
,I/UEI.SmartControl( 7083): Manufacture = LGE
D/UEI.SmartControl( 7083): File observer start...
E/UEI.SmartControl( 7083): IR Port is disabled: false
D/UEI.SmartControl( 7083): Starting file observer...
D/UEI.SmartControl( 7083): Extracting JNI libs...
D/UEI.SmartControl( 7083): --- this system supports 32-bit or 64-bit only
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,E/MDM     ( 1731): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4204): Restart initialization of location
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 7064): getMode name:com.lge.qremote
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
I/art     ( 7015): CheckpointMarkThreadRoots callback created = 0xb04d4eb0
,W/ContextImpl( 3645): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/art     ( 7015): CheckpointMarkThreadRoots callback created = 0xb04d4ea0
,D/UEI.SmartControl( 7083): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7083): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7083): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  954): Process com.android.vending (pid 6973) has died
I/dex2oat ( 7114): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/UEI.SmartControl( 7083): --- Selecting new region: 2
,I/UEI.SmartControl( 7083): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7083): Platform has CIR...
D/UEI.SmartControl( 7083): NO CIR support, need to check package...
I/UEI.SmartControl( 7083): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7083): QS Service created
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/UEI.SmartControl( 7083): QS start get config
,I/dex2oat ( 7114): dex2oat took 112.902ms (threads: 4)
,I/Adreno-EGL( 7015): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7015): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7015): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7015): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7015): Remote Branch: 
I/Adreno-EGL( 7015): Local Patches: 
I/Adreno-EGL( 7015): Reconstruct Branch: 
,D/UEI.SmartControl( 7083): Loading JNI Libs...
D/UEI.SmartControl( 7083):  configuring local db...
,D/UEI.SmartControl( 7083):  ---- Has DB8: true
,D/UEI.SmartControl( 7083): QS start statue = true Error code = 0
D/UEI.SmartControl( 7083): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7083): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7083): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7083): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7083): IrrcClient ++ 
D/irrcClient( 7083): getIrrcService ++ 
D/irrcClient( 7083): getIrrcService -- 
D/irrcClient( 7083): IrrcClient -- 
W/irrc_jni( 7083): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7083): Services init done
,I/UEI.SmartControl( 7083): Device manager: loading config....
D/UEI.SmartControl( 7083): QS Service init finished
D/UEI.SmartControl( 7083): QS Service version name: 0.1.73
D/UEI.SmartControl( 7083): QS Service version code: 1073
D/UEI.SmartControl( 7083): Config is loaded...
D/UEI.SmartControl( 7083): Service requested: Control
D/UEI.SmartControl( 7083): Internal service binding...
D/UEI.SmartControl( 7083): -----IControl: 11
,D/UEI.SmartControl( 7083): Caller: com.lge.qremote
D/UEI.SmartControl( 7083): ------------ IControl registerCallback...
I/UEI.SmartControl( 7083): Registering callback...
D/UEI.SmartControl( 7083): -----IControl: 19
D/UEI.SmartControl( 7083): Caller: com.lge.qremote
I/UEI.SmartControl( 7083): Registering Services Ready callback...
I/UEI.SmartControl( 7083): Notify client services are ready...
D/UEI.SmartControl( 7083): -----IControl: 8
D/UEI.SmartControl( 7083): Caller: com.lge.qremote
I/AudioManager( 7064): getMode name:com.lge.qremote
,I/ActivityManager(  954): Killing 6890:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/UEI.SmartControl( 7083):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7083): Notify AllClients services are ready: 0
,I/Adreno-EGL( 7015): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7015): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7015): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7015): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7015): Remote Branch: 
I/Adreno-EGL( 7015): Local Patches: 
I/Adreno-EGL( 7015): Reconstruct Branch: 
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 114712662461; DSPS: 3857089; Offset : -3002056101
I/Adreno-EGL( 7015): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7015): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7015): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7015): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7015): Remote Branch: 
I/Adreno-EGL( 7015): Local Patches: 
I/Adreno-EGL( 7015): Reconstruct Branch: 
,W/libprocessgroup(  954): failed to open /acct/uid_10011/pid_6890/cgroup.procs: No such file or directory
,I/AudioManager( 7064): getMode name:com.lge.qremote
I/AudioManager( 7064): getMode name:com.lge.qremote
,I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=2550319345
I/MusicWidget( 2517): mDelayedStopHandler : unbind
,I/MusicBrowser( 2665): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2665): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2665): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2665): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2665): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2665): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2665): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2665): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  954):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@23aafddbcom.lge.music.MediaPlaybackService$6@3b890078
,D/MusicBrowser( 2665): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2665): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2665): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2665): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2665): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2a1e4fe1
,I/MusicBrowser( 2665): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2665): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2665): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2665): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2665): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2665): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2665): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2665): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2665): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2665): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2665): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2665): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2665): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2665): reset
,V/MediaPlayer[Native]( 2665): setListener
V/MediaPlayer[Native]( 2665): disconnect
V/MediaPlayer[Native]( 2665): destructor
V/AudioFlinger(  283): releasing 18 from 2665 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/MediaPlayer[Native]( 2665): disconnect
,D/MusicBrowser( 2665): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2665): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2665): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2665): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2665): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2665): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2665): [SmartShareManagerClient] unregisterListener: 743043921
W/SmartShareClient( 2665): [SmartShareManagerClient] unregisterListener invalid listener: 743043921
I/SmartShareClient( 2665): [SmartShareManagerClient] terminate service: 2665/MediaPlaybackService/684906959
E/HomeCloudIF( 2665): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2665): [SmartShareManagerClient] unbindService context:android.app.Application@254577b6
V/CloudHub( 2665): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2665): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2665): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2665): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2665): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  954): Killing 6862:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/CloudHub( 2665): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
,W/libprocessgroup(  954): failed to open /acct/uid_1000/pid_6862/cgroup.procs: No such file or directory
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): L3 Terminate.
V/AlarmManager(  954): ELAPSED_WAKEUP set : Alarm{2dc130e type 2 when 117952 android} when 117952
,I/CheckinRequestBuilder( 4204): Classify the device as Phone.
,D/libc-netbsd( 4204): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4204): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4204): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4204): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 4204): propertyValue:false
,D/libc-netbsd( 4204): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4204): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4204): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4204): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4204): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4204): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4204): Sending checkin request (9901 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/CheckinRequestBuilder( 4204): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4204): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6154): Explicit concurrent mark sweep GC freed 2141(94KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 908us total 34.535ms
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4204): Classify the device as Phone.
,I/CheckinTask( 4204): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4204): Checking schedule, now: 1449754808259 next: 1450282057253
I/CheckinService( 4204): active receiver: disabled
,I/CheckinService( 4204): Checking schedule, now: 1449754808310 next: 1450282057253
I/CheckinService( 4204): active receiver: disabled
,D/CheckinService( 4204): Recording last checkin time for package unspecified as 1449754808321
I/ActivityManager(  954): Killing 6936:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_10051/pid_6936/cgroup.procs: No such file or directory
,V/SetupWizard( 6914): Connected to Gservices successfully
I/ActivityManager(  954): Killing 6680:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_10079/pid_6680/cgroup.procs: No such file or directory
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7083): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1364): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  954): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1364): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1364): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1364): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1364): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1364): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1364): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1364): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1364): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1364): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1364): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1364): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1364): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1364): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1364): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/ResourcesManager( 6956): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6956): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotificationManager( 6956): com.google.android.talk: cancel(8) by com.google.android.talk
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  954): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7189 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/administrator(  954): Handling package changes for user 0
,V/JNIHelp ( 6956): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppUp4:AppBoxCP( 7189): onCreate
W/AppUp4:DB( 7189):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7189):  setFingerPrint start
I/AppUp4:DB( 7189):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7189):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 7189):  SDK version = 0
I/AppUp4:DB( 7189):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7189): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7189): onReceive
I/AppUp4:CustModeStarterReceiver( 7189): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7189): Context : android.app.ReceiverRestrictedContext@3e2f9a2e
D/AppUp4:CustFacade( 7189): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7189): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7189): begin check event
I/AppUp4:CustModeStarterReceiver( 7189): Event For Nothing, skip.
W/System  ( 6956): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6956): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  954): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7213 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationService(  954): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  954): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  954): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  954): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  954): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  954): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@f72af18
,W/ResourcesManager(  954): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  954): Process com.google.android.apps.plus (pid 6769) has died
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1785): getDefaultRoute
W/ResourceType(  954): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/lowmemorykiller(  244): Error writing /proc/6749/oom_score_adj; errno=22
I/art     (  954): Explicit concurrent mark sweep GC freed 32286(1493KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.437ms total 220.908ms
W/ResourcesManager( 7213): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7213): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7213): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/ActivityManager(  954): Process com.android.chrome (pid 6749) has died
,D/LocationProviderProxy(  954): applying state to connected service
,I/AppConfig( 7213): Total System Memory = 906309632
,I/GalleryUtils( 7213): Application Heap = 96 MB
I/AppConfig( 7213): App Tier : NOT_DEF
D/SystemHelper( 7213): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  954): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7236 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/art     (  302): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 23.167ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 21.063ms
,W/ResourcesManager( 7236): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7236): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7236): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7236): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7236): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 31.016ms
,I/SystemConfig( 7236): BUILD Country: EU
I/SystemConfig( 7236): BUILD Operator: OPEN
,I/ActivityManager(  954): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7255 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7236): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7236): existFile = false
I/SystemConfig( 7236): canReadFile = false
I/SystemConfig( 7236): systemFeature RCS result false
D/SystemConfig( 7236): refreshRcsSupport() :false
,I/LockScreenSettings( 7255): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7255): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7255): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7255): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7255): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7255): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  954): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7275 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  954): Killing 2665:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  283): 2665 died, releasing its sessions
V/AudioFlinger(  283):  pid 1748 @ 0
V/AudioFlinger(  283):  pid 3216 @ 1
V/AudioFlinger(  283):  pid 3216 @ 2
,W/libprocessgroup(  954): failed to open /acct/uid_10028/pid_2665/cgroup.procs: No such file or directory
W/ResourcesManager( 7275): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  954): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7300 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  954): Killing 6914:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_10038/pid_6914/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 140 ms] updated apps [took 139 ms] 
D/Finsky  ( 7300): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7300): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7300): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7300): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7300): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@275e6d8f on behalf of 7300
D/Ads     ( 7300): Skipping gmscore version check
D/Finsky  ( 7300): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7300): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  954): Killing 7015:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_10006/pid_7015/cgroup.procs: No such file or directory
,D/Finsky  ( 7300): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4204): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4204): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7300): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4204): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Icing   ( 4204): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4204): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1364): onReceive = com.lge.android.intent.action.BATTERYEX
D/charger_monitor(  482): init target 500000
I/[SystemUI]LGPowerUI( 1364): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1364): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 299, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
,I/[SystemUI]LGPowerUI( 1364): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  954): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1364): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
I/[SystemUI]BatterySaverHandler( 1364): onReceive = android.intent.action.BATTERY_CHANGED
,I/ActivityManager(  954): Killing 7083:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7064): android.os.DeadObjectException
,W/libprocessgroup(  954): failed to open /acct/uid_10089/pid_7083/cgroup.procs: No such file or directory
W/ActivityManager(  954): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/System.err( 7064): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7064): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7064): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7064): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7064): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7064): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7064): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7064): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7064): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7064): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7064): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7064): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7064): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7064): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7064): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7064): android.os.DeadObjectException
W/System.err( 7064): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7064): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7064): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7064): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7064): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7064): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7064): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7064): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7064): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7064): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7064): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7064): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7064): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7064): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7064): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  954): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7359 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7359): Quickset Services start...
,I/UEI.SmartControl( 7359): Manufacture = LGE
D/UEI.SmartControl( 7359): File observer start...
E/UEI.SmartControl( 7359): IR Port is disabled: false
D/UEI.SmartControl( 7359): Starting file observer...
D/UEI.SmartControl( 7359): Extracting JNI libs...
D/UEI.SmartControl( 7359): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7359): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7359): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7359): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7359): --- Selecting new region: 2
I/UEI.SmartControl( 7359): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7359): Platform has CIR...
D/UEI.SmartControl( 7359): NO CIR support, need to check package...
I/UEI.SmartControl( 7359): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7359): QS Service created
E/UEI.SmartControl( 7359): QS start get config
,D/UEI.SmartControl( 7359): Loading JNI Libs...
,D/UEI.SmartControl( 7359):  configuring local db...
D/UEI.SmartControl( 7359):  ---- Has DB8: true
,D/UEI.SmartControl( 7359): QS start statue = true Error code = 0
D/UEI.SmartControl( 7359): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7359): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7359): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7359): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7359): IrrcClient ++ 
D/irrcClient( 7359): getIrrcService ++ 
D/irrcClient( 7359): getIrrcService -- 
D/irrcClient( 7359): IrrcClient -- 
W/irrc_jni( 7359): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7359): Services init done
I/UEI.SmartControl( 7359): Device manager: loading config....
,D/UEI.SmartControl( 7359): QS Service init finished
D/UEI.SmartControl( 7359): QS Service version name: 0.1.73
D/UEI.SmartControl( 7359): Config is loaded...
D/UEI.SmartControl( 7359): QS Service version code: 1073
D/UEI.SmartControl( 7359): Service requested: Control
,I/ActivityManager(  954): Killing 7064:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  954): failed to open /acct/uid_10106/pid_7064/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7359):  ----- QS SDK is ready!!!
,D/UEI.SmartControl( 7359): Internal service binding...
I/UEI.SmartControl( 7359): Notify AllClients services are ready: 0
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7359): Internal timer expired: 1
,D/UEI.SmartControl( 7359): Service.onUnbind: IControl
D/UEI.SmartControl( 7359): Service.onDestroy
W/System.err( 7359): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1559b548
W/System.err( 7359): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7359): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7359): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7359): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7359): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7359): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7359): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7359): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7359): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7359): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7359): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7359): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7359): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7359): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7359): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7359): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1559b548
D/UEI.SmartControl( 7359): Shutdown IRRCPlayer... 
W/irrc_jni( 7359): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7359): ~IrrcClient ++ 
D/irrcClient( 7359): ~IrrcClient -- 
W/irrc_jni( 7359): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7359): Blaster closed
D/UEI.SmartControl( 7359): Blaster closed
D/UEI.SmartControl( 7359): Shut down QS...
,D/UEI.SmartControl( 7359): Stopped file observer...
I/UEI.SmartControl( 7359): QS lib stop result = true
D/UEI.SmartControl( 7359): QS shutdown complete
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 134713345578; DSPS: 4512471; Offset : -3002044189
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  954): ELAPSED_WAKEUP set : Alarm{221f513e type 2 when 144547 com.google.android.gms} when 144547
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1731): Vacuum at: now=1449754834175 tag=VacuumService
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  954): ALS enabled for SRE
D/PowerManagerServiceEx(  954): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29827 ms ago)
,D/qdlights(  954): set_light_backlight: 253
,D/qdlights(  954): set_light_backlight: 250
D/qdlights(  954): set_light_backlight: 247
,D/qdlights(  954): set_light_backlight: 243
,D/qdlights(  954): set_light_backlight: 240
,D/qdlights(  954): set_light_backlight: 237
,D/qdlights(  954): set_light_backlight: 233
,D/qdlights(  954): set_light_backlight: 230
,D/qdlights(  954): set_light_backlight: 227
,D/qdlights(  954): set_light_backlight: 223
,D/qdlights(  954): set_light_backlight: 220
,D/qdlights(  954): set_light_backlight: 217
,D/qdlights(  954): set_light_backlight: 213
,D/qdlights(  954): set_light_backlight: 210
,D/qdlights(  954): set_light_backlight: 207
,D/qdlights(  954): set_light_backlight: 203
,D/qdlights(  954): set_light_backlight: 200
,D/qdlights(  954): set_light_backlight: 197
,D/qdlights(  954): set_light_backlight: 193
,D/qdlights(  954): set_light_backlight: 190
,D/qdlights(  954): set_light_backlight: 187
,D/qdlights(  954): set_light_backlight: 183
,D/qdlights(  954): set_light_backlight: 180
,D/qdlights(  954): set_light_backlight: 177
,D/qdlights(  954): set_light_backlight: 173
,D/qdlights(  954): set_light_backlight: 170
,D/qdlights(  954): set_light_backlight: 167
,D/qdlights(  954): set_light_backlight: 163
,D/qdlights(  954): set_light_backlight: 160
,D/qdlights(  954): set_light_backlight: 157
,D/qdlights(  954): set_light_backlight: 153
,D/qdlights(  954): set_light_backlight: 150
,D/qdlights(  954): set_light_backlight: 147
,D/qdlights(  954): set_light_backlight: 143
,D/qdlights(  954): set_light_backlight: 140
,D/qdlights(  954): set_light_backlight: 137
,D/qdlights(  954): set_light_backlight: 133
,D/qdlights(  954): set_light_backlight: 130
,D/qdlights(  954): set_light_backlight: 127
,D/qdlights(  954): set_light_backlight: 123
,D/qdlights(  954): set_light_backlight: 120
,D/qdlights(  954): set_light_backlight: 117
,D/qdlights(  954): set_light_backlight: 113
,D/qdlights(  954): set_light_backlight: 110
,D/qdlights(  954): set_light_backlight: 107
,D/qdlights(  954): set_light_backlight: 103
,D/qdlights(  954): set_light_backlight: 100
,D/qdlights(  954): set_light_backlight: 97
,D/qdlights(  954): set_light_backlight: 93
,D/qdlights(  954): set_light_backlight: 90
,D/qdlights(  954): set_light_backlight: 87
,D/qdlights(  954): set_light_backlight: 83
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  954): set_light_backlight: 80
,D/qdlights(  954): set_light_backlight: 77
,D/qdlights(  954): set_light_backlight: 73
,D/qdlights(  954): set_light_backlight: 70
,D/qdlights(  954): set_light_backlight: 67
,D/qdlights(  954): set_light_backlight: 63
,D/qdlights(  954): set_light_backlight: 60
,D/qdlights(  954): set_light_backlight: 57
,D/qdlights(  954): set_light_backlight: 53
,D/qdlights(  954): set_light_backlight: 50
,D/qdlights(  954): set_light_backlight: 47
,D/qdlights(  954): set_light_backlight: 43
,D/qdlights(  954): set_light_backlight: 40
,D/qdlights(  954): set_light_backlight: 37
,D/qdlights(  954): set_light_backlight: 33
,D/qdlights(  954): set_light_backlight: 30
,D/qdlights(  954): set_light_backlight: 27
,D/qdlights(  954): set_light_backlight: 23
,D/qdlights(  954): set_light_backlight: 20
,D/qdlights(  954): set_light_backlight: 17
,D/qdlights(  954): set_light_backlight: 13
,D/qdlights(  954): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 154714800518; DSPS: 5167879; Offset : -3002053911
,I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  954): ALS enabled for SRE
D/PowerManagerServiceEx(  954): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36823 ms ago)
I/PowerManagerService(  954): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  954): ALS enabled for SRE
D/PowerManagerServiceEx(  954): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36831 ms ago)
W/ContextImpl(  954): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  954): Sleeping (uid 1000)...
,D/LPWGController(  954): [updateScreenState] screen on = false
D/LPWGController(  954): disable proximity sensor
D/LPWGController(  954): enable proximity sensor
I/SensorManager(  954): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@39406f97] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  954): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  954): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  954): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  954): activate: handle is 48, enable
V/sensors_hal_Ctx(  954): activate sensors is 1400000000000
D/sensors_hal_Thresh(  954): enable: handle=48
I/sensors_hal_SAM(  954): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  954): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  954): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  954): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  954): enable: Received response: 0
D/PowerManagerServiceEx(  954): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36870 ms ago)
I/Adreno-EGL(  954): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  954): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  954): Build Date: 03/02/15 Mon
I/Adreno-EGL(  954): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  954): Remote Branch: 
I/Adreno-EGL(  954): Local Patches: 
I/Adreno-EGL(  954): Reconstruct Branch: 
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1167 us)
,I/Sensors (  433): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  954): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  954): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  954): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  954): processInd: handle 48, count=1
V/sensors_hal_Thresh(  954): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  954): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  954): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  954): poll: count: 256
I/sensors_hal_Ctx(  954): poll: released wakelock sensor_ind
D/sensors_hal_Util(  954): waitForResponse: timeout=0
D/LPWGController(  954): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  954): current mode = 1  value = 1 1
I/LPWGController(  954): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  954): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  954): set_light_backlight: 0
,I/SensorManager(  954): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  954): activate: handle is 46, disable
V/sensors_hal_Ctx(  954): activate sensors is 1000000000000
D/sensors_hal_LP2(  954): enable: handle=46
D/sensors_hal_LP2(  954): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  954): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  954): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  954): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  954): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  954): Display changed displayId=0
,D/DSDPConnection( 1748): Display #0 changed.
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
D/SurfaceControl(  954): Excessive delay in setPowerMode(): 224ms
,I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  954): Got set_interactive hint
,D/KeyguardViewMediator( 1364): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1364): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
D/KeyguardViewMediator( 1364): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1364): handleNotifyScreenOff
,D/WifiServerServiceExt(  954): sendKtScanInterval  mRtspPlay : false
,D/ScreenTurnOffBySensor( 1364): unregisterProximitySensor
V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=on, calling pid 954
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  283): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1364): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/StatusBarWindowView( 1364): onScreenTurnedOff why = 3
,I/WifiServerServiceExt(  954): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1364): handleTimeUpdate
D/GpsLocationProvider(  954): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1364): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:true
I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/LEDService( 1802): stopPatternFlashing()
D/Cliptray Service( 1802): lockStatus = 0
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): updateLightsLocked : turn off led
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1802): RESTART MSG
,D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 3
D/NfcService( 1785): Discovery configuration equal, not updating.
D/Ulp_jni (  954): JNI:system_update. Event-0
D/SplitWindow(  954): check instance of lgWin Window{3040f1a2 u0 SearchPanel}
,D/InputDispatcher(  954): Window went away: Window{13fcf118 u0 SearchPanel}
,I/[SystemUI]Clock( 1364): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1364): time changed, timezoneChanged : false
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2644): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:40:47
,D/WeatherService( 2644): 2 : ACTION screen on
,D/WeatherService( 2644): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2644): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2644): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:40:47
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  954): ACTION_SCREEN_ON
D/AppCleanupService( 4062): android.intent.action.SCREEN_ON
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=off, calling pid 954
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/WifiController(  954): CMD_SCREEN_OFF 
D/WifiController(  954): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  954): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1364): onReceive = android.intent.action.SCREEN_OFF
,I/Sensors (  433): sns_pwr.c(301):releasing wakelock
,I/QCNEJ   ( 1838): |CORE| sendScreenState: state:false
I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1802): clear
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
I/LEDService( 1802): updateLightsLocked : turn on led
E/LEDService( 1802): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1802): Can't handle this request of patternId:0
D/LEDHandler( 1802): RESTART MSG
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
D/WeatherService( 2644): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:40:48
D/WeatherService( 2644): 2 : ACTION screen off
D/WeatherService( 2644): 2 : TimeTick Receiver Unregister
D/WeatherService( 2644): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:40:48
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  954): ACTION_SCREEN_OFF
D/AppCleanupService( 4062): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4062): AppUsageStatsSaveTask
E/NxpNfcJni( 1785): getReconnectState = 0x0
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
,D/KeyguardViewMediator( 1364): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  954): ELAPSED_WAKEUP set : Alarm{1a926e33 type 2 when 162741 com.android.systemui} when 162741
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1748): getCallState : 0
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1364): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1364): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1364): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1364): called onTimeUpdated()
,I/[SystemUI]Clock( 1364): called onTimeUpdated()
I/LgeClockWidgetControlView( 1364): called onTimeUpdated()
I/[SystemUI]DateView( 1364): called onTimeUpdated()
I/[SystemUI]DateView( 1364): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1364): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 174715439990; DSPS: 5823260; Offset : -3002055229
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1364): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1364): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1364): On Skip Timer : true
D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1364): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1364): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/[SystemUI]BatterySaverHandler( 1364): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  954): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
I/[SystemUI]LGPowerUI( 1364): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1364): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
,D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 297, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1364): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  954): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1364): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1364): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1364): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1364): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1364): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  954): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1364): onReceive = android.intent.action.BATTERY_CHANGED
D/PowerManagerServiceEx(  954): acquireWakeLockInternal: lock=475964912, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=954
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
V/AlarmManager(  954): ELAPSED_WAKEUP set : Alarm{327bf769 type 2 when 188669 com.google.android.gms} when 188669
D/PowerManagerServiceEx(  954): releaseWakeLockInternal: lock=475964912 [*alarm*], flags=0x0
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 42936(2MB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 13MB/22MB, paused 2.070ms total 142.755ms
,I/PhenotypeConfigurator( 1731): Scheduling Phenotype for one-off execution 12818 seconds from now (1449754878511)
,D/GetConfigurationSnapshotOperation( 1731): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1731): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1731): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  954): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 1731): propertyValue:false
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/AlarmManager(  954): ELAPSED_WAKEUP set : Alarm{6af64c6 type 2 when 189503 android} when 189503
,D/LocationManagerService(  954): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  954): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  954): android: cancelAsUser(2) by android
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  954): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  954): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 194716035034; DSPS: 6478639; Offset : -3002040514
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 214716712005; DSPS: 7134021; Offset : -3002034721
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1364): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1364): called onTimeUpdated()
I/[SystemUI]Clock( 1364): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1364): called onTimeUpdated()
I/[SystemUI]DateView( 1364): called onTimeUpdated()
I/[SystemUI]DateView( 1364): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1364): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 234717395904; DSPS: 7789404; Offset : -3002053222
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1364): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1364): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1364): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1364): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1364): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
I/[SystemUI]BatterySaverHandler( 1364): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  954): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 254718007771; DSPS: 8444784; Offset : -3002052877
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 274718604118; DSPS: 9100163; Offset : -3002034385
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1364): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1364): called onTimeUpdated()
I/[SystemUI]Clock( 1364): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1364): called onTimeUpdated()
I/[SystemUI]DateView( 1364): called onTimeUpdated()
I/[SystemUI]DateView( 1364): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1364): handleTimeUpdate
D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1364): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1364): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1364): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1364): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1364): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1364): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/[SystemUI]LGPowerUI( 1364): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1364): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1364): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  954): battery changed pluggedType: 2
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1364): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1364): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
I/[SystemUI]BatterySaverHandler( 1364): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  954): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 294719292235; DSPS: 9755546; Offset : -3002048330
,D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1364): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1364): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1364): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1364): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1364): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1364): On Skip Timer : true
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1364): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1364): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1364): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1364): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  954): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  954): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  954): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  954): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  954): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  954): tsOffsetIs: Apps: 314720271967; DSPS: 10410938; Offset : -3002045186
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC

```
