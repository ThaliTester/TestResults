#### Test 54970261c23922d_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  846): Killing 5275:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10018/pid_5275/cgroup.procs: No such file or directory
,--------- beginning of main
D/AndroidRuntime( 5460): 
D/AndroidRuntime( 5460): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5460): CheckJNI is OFF
D/AlertService( 5419): Beginning updateAlertNotification
D/AlertService( 5419): No fired or scheduled alerts
I/NotificationManager( 5419): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5419): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5419): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5419): No events found starting within 1 week.
I/ActivityManager(  846): Killing 5294:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10069/pid_5294/cgroup.procs: No such file or directory
D/AndroidRuntime( 5460): Calling main entry com.android.commands.am.Am
I/ActivityManager(  846): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  846): setTaskToReturnTo : TaskRecord{302725dc #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  846): setTaskToReturnTo : TaskRecord{302725dc #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  846): AppWindowTokenEx init.. 
D/ContextHelper(  846): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  846): Focus left window: Window{23d27442 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5460): Shutting down VM
I/[LGHome]EVENT( 1949): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  846): check instance of lgWin Window{320b386 u0 Starting com.test.thalitest}
I/ActivityManager(  846): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5480 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1949): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 2026): Closing mic
I/MicrophoneInputStream( 2026): mic_close com.google.android.apps.gsa.speech.audio.u@1bfbde1f
V/AudioRecord( 2026): stop()
D/AudioRecord( 2026): AudioRecord->stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
V/AudioFlinger(  285): Record stopped OK
V/AudioPolicyManager(  285): stopInput() input 17
V/AudioPolicyService(  285): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  285): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  285): ThreadBase::setParameters() routing=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
I/[LGHome]EVENT( 1949): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  846): Starting window displayed
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3852000
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
I/SystemUI[Framework](  846): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  846): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  846): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  846): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f4c4d4a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1372): draw background and invalidate : color = 16000000
D/BarTransitions( 1372): draw background and invalidate : color = 16161616
V/audio_hw_primary(  285): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  285): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  285): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  285): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  285): disable_audio_route: exit
E/audio_hw_primary(  285): disable_snd_device: enter 144
D/hardware_info(  285): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  285): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  285): stop_input_stream: exit: status(0)
,V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyManager(  285): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  285): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  285): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  285): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyService(  285): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  285): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  285): setParameters(): io 17, keyvalue hotword_active=0, calling pid 285
V/AudioFlinger(  285): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  285): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  285): in_set_parameters: exit: status(0)
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3852000
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioRecord( 2026): stop()
V/AudioRecord( 2026): stop()
,V/AudioRecord( 2026): stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
V/AudioPolicyManager(  285): releaseInput() 17
V/AudioPolicyManager(  285): closeInput(17)
V/AudioFlinger(  285): releasing 16 from 2026 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/AudioFlinger(  285): closeInput() 17
V/AudioSystem(  285): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  846): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): ThreadBase::exit
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioSystem( 2026): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3122): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2735): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1753): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): RecordThread 0xb3852000 exiting
D/audio_hw_primary(  285): adev_close_input_stream: enter:stream_handle(0xb546e240)
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioPolicyService(  285): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  285): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyManager(  285): releaseInput() exit
V/AudioFlinger(  285): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  285): removeClient_l() pid 2026, calling pid 285
I/HotwordRecognitionRnr( 2026): Hotword detection finished
I/HotwordRecognitionRnr( 2026): Stopping hotword detection.
,D/ContextHelper( 5480): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 5480): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5480): Time to load native libraries: 5 ms (timestamps 2228-2233)
I/LibraryLoader( 5480): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5480): Binding Chromium to main looper Looper (main, tid 1) {fbbd9a7}
,I/LibraryLoader( 5480): Expected native library version number "",actual native library version number ""
I/chromium( 5480): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5480): Initializing chromium process, singleProcess=true
,W/art     ( 5480): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5480): ApplicationContext is null in ApplicationStatus
W/chromium( 5480): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5480): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5480): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5480): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5480): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5480): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5480): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5480): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5480): Remote Branch: 
I/Adreno-EGL( 5480): Local Patches: 
I/Adreno-EGL( 5480): Reconstruct Branch: 
,V/AudioPolicyService(  285): registerClient() client 0xb551ce60, uid 10316
,D/BluetoothManagerService(  846): Message: 20
,D/BluetoothManagerService(  846): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ebeaef8:true
D/BluetoothAdapter( 5480): 296446912: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  846): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5529 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 5529): Gservices pushing to system: true; secure/global: true
,W/art     ( 5480): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5480): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5480): CordovaWebView is running on device made by: LGE
,W/art     ( 5480): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5480): Attempt to remove local handle scope entry from IRT, ignoring
I/GoogleHttpClient( 5529): GMS http client unavailable, use old client
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{3f8fbf41 type 0 when 1451923428666 com.android.vending} when 1451923428666
,I/GoogleHttpClient( 5529): GMS http client unavailable, use old client
,I/Activity( 5480): Activity.onPostResume() called 
,D/OpenGLRenderer( 5480): Render dirty regions requested: true
I/OpenGLRenderer( 5480): Initialized EGL, version 1.4
D/OpenGLRenderer( 5480): Enabling debug mode 0
,D/Atlas   ( 5480): Validating map...
,D/SplitWindow(  846): check instance of lgWin Window{8580e7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5480): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  846): Focus entered window: Window{8580e7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  846): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  846): Displayed com.test.thalitest/.MainActivity: +1s132ms
I/Timeline(  846): Timeline: Activity_windows_visible id: ActivityRecord{125c56e5 u0 com.test.thalitest/.MainActivity t220} time:92930
I/Timeline( 5480): Timeline: Activity_idle id: android.os.BinderProxy@d402933 time:92939
,D/Finsky  ( 4953): [585] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4953): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  846): Killing 5311:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10086/pid_5311/cgroup.procs: No such file or directory
,W/BindingManager( 5480): Cannot call determinedVisibility() - never saw a connection for the pid: 5480
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/JsMessageQueue( 5480): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 5480): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622832128
D/JX-Cordova( 5480): jxcore cordova android initializing
,I/art     ( 5480): CheckpointMarkThreadRoots callback created = 0x9f662340
,I/art     ( 5480): CheckpointMarkThreadRoots callback created = 0x9f662310
,I/art     (  846): Explicit concurrent mark sweep GC freed 16104(788KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 3.768ms total 226.145ms
,W/jxcore-log( 5480): Initializing JXcore engine
,W/jxcore-log( 5480): JXcore engine is ready
W/jxcore-log( 5480): Starting JXcore engine
,W/.test.thalitest( 5480): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7911]" dev="sockfs" ino=7911 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5480): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5480): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5674]" dev="sockfs" ino=5674 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5480): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5480): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5480): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25330]" dev="sockfs" ino=25330 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5480): Platform android
W/jxcore-log( 5480): 
W/jxcore-log( 5480): Process ARCH arm
W/jxcore-log( 5480): 
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 96051827572; DSPS: 3246368; Offset : -3022524536
,I/jxcore-log( 5480): JXcore Cordova bridge is ready!
I/jxcore-log( 5480): 
,W/jxcore-log( 5480): JXcore engine is started
I/chromium( 5480): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 5480): Toggling radios to true
I/jxcore-log( 5480): 
,D/BluetoothManagerService(  846): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  846): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  846): Message: 1
D/BluetoothManagerService(  846): MESSAGE_ENABLE: mBluetooth = null
D/BluetoothAdapterService(784492867)( 2077): onBind()
,D/WifiServiceImplEx(  846): setWifiEnabled: true pid=5480, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/BluetoothManagerService(  846): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/LocationManagerService(  846): getAllProviders()=[passive, gps, network]
D/BluetoothManagerService(  846): Message: 40
D/BluetoothManagerService(  846): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/Ulp_jni (  846): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  846): JNI:system_update. Event-4
D/WifiService(  846): setWifiEnabled: true pid=5480, uid=10316
D/LocationManagerService(  846): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  846): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  846): JNI:system_update. Event-4
,D/WifiServiceImplEx(  846): disconnect pid=5480, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  846): reconnect pid=5480, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5480): Radios toggled
I/jxcore-log( 5480): 
,I/LGFTMITEM(  846): [GET_FTM][id=6], offset=12288
E/WifiHW  (  846): Wifi MAC Address = a0:39:f7:70:12:80
E/WifiHW  (  846): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  846): band=b
E/WifiHW  (  846): ": cur_etheraddr=a0:39:f7:70:12:80
,I/bluedroid( 2077): config_hci_snoop_log
D/SoftapController(  280): Softap fwReload - Ok
D/BluetoothManagerService(  846): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  846): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/CommandListener(  280): Setting iface cfg
D/CommandListener(  280): Trying to bring down wlan0
D/CommandListener(  280): Clearing all IP addresses on wlan0
V/LGMDMManagerInternal( 2077): Create singleton instance
E/WifiHW  (  846): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,I/wpa_supplicant( 5598): Successfully initialized wpa_supplicant
,D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
I/wpa_supplicant( 5598): rfkill: Cannot open RFKILL control device
D/BluetoothAdapterService(784492867)( 2077): enable() - Enable called with quiet mode status =  false
I/wpa_supplicant( 5598): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,D/BluetoothAdapterState( 2077): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2077): Setting state to 11
I/BluetoothAdapterState( 2077): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(784492867)( 2077): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  846): Message: 60
,D/BluetoothManagerService(  846): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  846): Bluetooth State Change Intent: 10 -> 11
D/BluetoothAdapterService(784492867)( 2077): processStart()
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2077): Unable to read settings
D/BtSettings.ProfileConfig( 2077): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2077): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2077): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2077): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2077): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 2077): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 2077): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2077): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2077): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2077): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2077): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/BluetoothAdapterService( 2077): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2077): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2077): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2077): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2077): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2077): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2077): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2077): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2077): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2077): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(784492867)( 2077): processStart() - Make Bond State Machine
D/BluetoothBondStateMachine( 2077): make
,D/BluetoothAdapterService( 2077): setAdapterService() - set to: null
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
D/LGBluetoothServiceAdapter( 2077): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 2077): StableState(): Entering Off State
I/ActivityManager(  846): Process com.google.android.talk (pid 5088) has died
D/BluetoothAdapterService( 2077): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2077): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/WifiMonitor(  846): startMonitoring(wlan0) with mConnected = false
D/BtSettings.ProfileConfig( 2077): Unable to read settings
D/BtSettings.ProfileConfig( 2077): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2077): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2077): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2077): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2077): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2077): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 2077): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 2077): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2077): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2077): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2077): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2077): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 2077): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(784492867)( 2077): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:53.188 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/ActivityManager(  846): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5601 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,D/LGBluetoothAPIService( 1833): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/WifiServerServiceExt(  846): WIFI_STATE_CHANGED_ACTION [2]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/BluetoothAdapterService( 2077): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2077): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2077): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(784492867)( 2077): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 2077): Received start request. Starting profile...
D/BluetoothHeadset(  846): Proxy object connected
D/BluetoothHeadset( 1753): Proxy object connected
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.WIFI_STATE_CHANGED at null
I/LGBluetoothHeadsetServiceJni( 2077): classInitNative: succeeds
D/BluetoothAdapterService( 2077): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2077): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2077): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(784492867)( 2077): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
D/BluetoothAdapterService( 2077): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2077): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2077): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(784492867)( 2077): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/LGBluetoothFeatureConfig( 2077): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 2077): classInitNative: succeeds
,D/BluetoothAdapterService( 2077): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2077): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2077): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(784492867)( 2077): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2077): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2077): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2077): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(784492867)( 2077): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
,D/HeadsetStateMachine( 2077): make
D/BluetoothHeadset( 1753): Proxy object connected
D/BluetoothAdapterService( 2077): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2077): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2077): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(784492867)( 2077): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/BluetoothHeadset( 1753): Proxy object connected
D/BluetoothAdapterService( 2077): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2077): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2077): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(784492867)( 2077): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 2077): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2077): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2077): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(784492867)( 2077): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
,D/BluetoothAdapterService( 2077): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2077): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 2077): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2077): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(784492867)( 2077): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/HeadsetStateMachine( 2077): max_hf_connections = 1
I/bluedroid( 2077): get_profile_interface handsfree
V/LGMDMManager( 2077): Create singleton instance
I/bt-btif ( 2077): btif_hf_get_interface
I/bt-btif ( 2077): init
D/bt-btif ( 2077): max_hf_clients = 1
D/bt-btif ( 2077): btif_max_hf_clients = 1
D/bt-btif ( 2077): btif_enable_service: current services:0xa0601330
I/[SystemUI]BluetoothHandler( 1372): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
V/ToneGenerator( 2077): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  285): registerClient() client 0xb40272e0, uid 1002
V/AudioPolicyManager(  285): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  285): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  285): getOutput() returns output 2
V/AudioFlinger(  285): registerClient() client 0xb383fe38, pid 2077
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  285): thread 0xb5651000 type 0 TID 1290 waking up
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  285): thread 0xb56eb000 type 0 TID 1291 waking up
V/AudioFlinger(  285): thread 0xb5735000 type 0 TID 1293 waking up
,V/AudioSystem( 2077): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/ToneGenerator( 2077): Create Track: 0xb4909480
V/AudioTrack( 2077): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 2077): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
I/AudioFlinger(  285): isAudioPlaybackHookOn() false
D/AudioTrack( 2077): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  285): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  285): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  285): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  285): getOutput() returns output 2
V/AudioSystem(  285): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  285): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb5651000
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  285): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  285): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3122): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3122): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  846): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  846): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1372): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1372): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1753): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1753): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2026): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2026): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2077): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2077): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 2735): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2735): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem(  846): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  846): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1372): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1372): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3122): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1753): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3122): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1753): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2026): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2077): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2026): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2077): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 2735): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2077): getLatency() output 2, latency 50
V/AudioSystem( 2735): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2077): getFrameCount() output 2, frameCount 960
V/AudioTrack( 2077): createTrack_l() output 2 afLatency 50
V/AudioTrack( 2077): Create normal PCM 0x1 Track
V/AudioSystem(  285): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  285): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  846): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  846): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1372): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1372): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 1753): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1753): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2026): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2026): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  285): createTrack() lSessionId: 22
V/AudioFlinger(  285): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioSystem( 3122): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3122): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 1
V/AudioSystem( 2735): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2735): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2077): ioConfigChanged() event 0, ioHandle 4
V/AudioTrack( 2077): Flags here  0x4 
V/AudioTrack( 2077): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  285): acquiring 22 from 2077, for 2077
V/AudioFlinger(  285):  added new entry for 22
V/ToneGenerator( 2077): ToneGenerator INIT OK, time: 97430
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
I/BluetoothAdapterState( 2077): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
V/AudioSystem( 2077): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
D/HeadsetStateMachine( 2077): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 2077): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2077): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 2077): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  285): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 2077
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb5651000
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
D/BluetoothA2dp(  846): Proxy object connected
D/A2dpService( 2077): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2077): classInitNative: succeeds
V/Avrcp   ( 2077): make
D/Avrcp   ( 2077): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 2077): get_profile_interface avrcp
I/bt-btif ( 2077): btif_rc_get_interface
I/bt-btif ( 2077): ## init ##
D/audio_hw_primary(  285): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  285): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  285): platform_set_parameters: enter: bt_samplerate=8000
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
I/LGBluetoothAvrcpServiceJni( 2077): classInitNative: succeeds
I/LGBluetoothAvrcpAdapter( 2077): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 2077): initNative: succeeds
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
,V/ToneGenerator( 2077): ToneGenerator destructor
V/ToneGenerator( 2077): stopTone
V/ToneGenerator( 2077): Delete Track: 0xb4909480
I/BluetoothAvrcpBrcmAdapterJni( 2077): classInitBrcmNative
V/AudioTrack( 2077): ~AudioTrack, releasing session id from 2077 on behalf of 2077
I/art     ( 1734): Explicit concurrent mark sweep GC freed 29388(1848KB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 13MB/22MB, paused 2.173ms total 179.623ms
V/AudioFlinger(  285): releasing 22 from 2077 for 2077
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/AudioFlinger(  285): remove track (4099) and delete from mixer
V/AudioPolicyService(  285): AudioCommandThread() adding release output 2
V/AudioPolicyService(  285): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  285): releaseOutput() 2
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioFlinger(  285): PlaybackThread::Track destructor
V/AudioFlinger(  285): removeClient_l() pid 2077, calling pid 285
I/BluetoothAvrcpBrcmAdapterJni( 2077): initBrcmNative
V/AudioService(  846): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,E/AudioService(  846): No RCC entry present to update
E/RemoteController( 2077): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2077): classInitNative
I/BluetoothA2dpServiceJni( 2077): classInitNative: succeeds
D/A2dpStateMachine( 2077): make
I/bluedroid( 2077): get_profile_interface a2dp
I/bt-btif ( 2077): btif_av_get_src_interface
I/bt-btif ( 2077): init
D/bt-btif ( 2077): btif_enable_service: current services:0xa0601330
I/LGBluetoothA2dpServiceJni( 2077): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 2077): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 2077): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 2077): [BTUI] init
D/LGBluetoothPowerControlManager( 2077): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  846): Message: 30
,D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
D/A2dpStateMachine( 2077): Enter Disconnected: -2
I/BluetoothHidServiceJni( 2077): classInitNative: succeeds
D/HidService( 2077): Received start request. Starting profile...
I/bluedroid( 2077): get_profile_interface hidhost
I/bt-btif ( 2077): btif_hh_get_interface
I/bt-btif ( 2077): init
D/bt-btif ( 2077): btif_enable_service: current services:0xa0601330
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
I/BluetoothHealthServiceJni( 2077): classInitNative: succeeds
,D/HealthService( 2077): Received start request. Starting profile...
I/bluedroid( 2077): get_profile_interface health
I/bt-btif ( 2077): btif_hl_get_interface
I/bt-btif ( 2077): init
D/bt-btif ( 2077): Process name (droid.bluetooth)
D/bt-btif ( 2077): btif_hl_soc_thread_init
D/bt-btif ( 2077): create_thread: entered
D/bt-btif ( 2077): create_thread: thread created successfully
D/bt-btif ( 2077): entered btif_hl_select_thread
D/bt-btif ( 2077): btif_hl_select_wakeup_init
D/bt-btif ( 2077): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 2077): max_s=55 
D/bt-btif ( 2077): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 2077): classInitNative: succeeds
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
I/BluetoothPanServiceJni( 2077): classInitNative(L105): succeeds
D/PanService( 2077): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2077): initializeNative(L110): pan
I/bluedroid( 2077): get_profile_interface pan
D/bt-btif ( 2077): stack_initialized = 0, btpan_cb.enabled:0
,I/LGBluetoothPanAdapter( 2077): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
,I/BtGatt.JNI( 2077): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 2077): handleDebugAction() action=null
D/BtGatt.GattService( 2077): Received start request. Starting profile...
D/BtGatt.GattService( 2077): start()
I/bluedroid( 2077): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 2077): advertise manager created
I/LGBluetoothGattAdapter( 2077): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 2077): setGattService:  set to: null
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
,D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
I/LGBluetoothMapAdapter( 2077): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 2077): BluetoothMapBinder()
D/BluetoothMapService( 2077): Received start request. Starting profile...
D/BluetoothMapService( 2077): start()
D/BluetoothMapEmailSettingsLoader( 2077): Found 0 applications
D/BluetoothMapEmailAppObserver( 2077): createReceiver()
D/BluetoothMapEmailAppObserver( 2077): initObservers()
D/BluetoothMapEmailAppObserver( 2077): getEnabledAccountItems()
,D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
I/BluetoothSAPServiceJni( 2077): classInitNative(L170): succeeds
,D/SapService( 2077): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 2077): initializeNative(L175): sap
I/bluedroid( 2077): get_profile_interface sap
I/bt-btif ( 2077): btif_sc_get_interface
I/bt-btif ( 2077): init
D/bt-btif ( 2077): btif_enable_service: current services:0xa0601330
I/LGBluetoothSapAdapter( 2077): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 2077): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 2077): [BTUI] initSapManager
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
D/LgeBluetoothSimManager( 1753): [BTUI] SAP_ENABLE_EVT
,V/BluetoothFTPServiceJni( 2077): classInitNative
I/BluetoothFTPServiceJni( 2077): classInitNative(L271): succeeds
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
D/BluetoothFTPService( 2077): BluetoothFtpBinder()
D/**BluetoothFTPService( 2077): Received start request. Starting profile...
V/BluetoothFTPService( 2077): FTP-Server Service start
D/BluetoothFTPServiceJni( 2077): initFtpNativeDataNative(L275): FTP
I/bluedroid( 2077): get_profile_interface ftp
I/bt-btif ( 2077): btif_fts_get_interface
I/bt-btif ( 2077): init
D/bt-btif ( 2077): btif_enable_service: current services:0xa0601330
D/BluetoothFTPServiceJni( 2077): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
D/LGBluetoothFeatureConfig( 2077): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 2077): classInitNative
I/BluetoothOPPServiceJni( 2077): classInitNative(L373): succeeds
V/OppService( 2077): Opp initBinder
,D/**OppService( 2077): Received start request. Starting profile...
D/OppService( 2077): Starting OppService 
D/LGBluetoothOppAdapter( 2077): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 2077): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 2077): send message
D/BluetoothOppPreference( 2077): Dumping Names:  
D/BluetoothOppPreference( 2077): {}
D/BluetoothOppPreference( 2077): Dumping Channels:  
D/BluetoothOppPreference( 2077): {}
D/OppService( 2077): Start()
W/BluetoothOPPServiceJni( 2077): initOppNative
D/BluetoothOPPServiceJni( 2077): initOppNative(L383): OPP
I/bluedroid( 2077): get_profile_interface opp
I/bt-btif ( 2077): btif_op_get_interface
D/BluetoothOPPServiceJni( 2077): initOppNative(L411): mOppCallbacksObj 1049850
D/BluetoothOPPServiceJni( 2077): initOppNative(L413): calling OPP init
,I/bt-btif ( 2077): btif_opp_init
D/bt-btif ( 2077): btif_enable_service: current services:0xa0601330
D/BluetoothOPPServiceJni( 2077): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 2077): initOppNative(L430): mOppCallbacksObj 1049850
V/OppService( 2077): setOppService(): set to: com.broadcom.bt.service.opp.OppService@236e2081
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
D/HeadsetStateMachine( 2077): Proxy object connected
D/LGBluetoothHfpAdapter( 2077): [BTUI] queryPhoneState
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - Message: 1
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(784492867)( 2077): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 2077): isTurningOnRadio()=false
D/BluetoothAdapterState( 2077): isTurningOffRadio()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2077): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2077): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2077): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 2077): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 2077): Proxy object connected
D/LGBluetoothPowerControlManager( 2077): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@32bcdf14
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - Message: 1
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(784492867)( 2077): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 2077): isTurningOnRadio()=false
D/BluetoothAdapterState( 2077): isTurningOffRadio()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2077): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 2077): Deleted complete outbound shares, number =  0
V/OppService( 2077): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 2077): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/OppService( 2077): pendingUpdate is :  true
V/BluetoothOppProvider( 2077): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2077): created cursor android.database.sqlite.SQLiteCursor@3db43bd on behalf of 
,D/BluetoothAdapterService( 2077): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - Message: 1
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(784492867)( 2077): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 2077): isTurningOnRadio()=false
D/BluetoothAdapterState( 2077): isTurningOffRadio()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2077): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 2077): created cursor android.database.sqlite.SQLiteCursor@142d9db2 on behalf of 
V/BluetoothOppNotification( 2077): update too frequent, put in queue
D/BluetoothAdapterService( 2077): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - Message: 1
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(784492867)( 2077): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 2077): isTurningOnRadio()=false
D/BluetoothAdapterState( 2077): isTurningOffRadio()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2077): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 2077): pendingUpdate is :  false
E/OppService( 2077): UpdateThread is Completed
D/BluetoothAdapterService( 2077): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 2077): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - Message: 1
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(784492867)( 2077): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 2077): isTurningOnRadio()=false
D/BluetoothAdapterState( 2077): isTurningOffRadio()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2077): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2077): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - Message: 1
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(784492867)( 2077): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 2077): isTurningOnRadio()=false
D/BluetoothAdapterState( 2077): isTurningOffRadio()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2077): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 2077): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2077): Handler(): got msg=1
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - Message: 1
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(784492867)( 2077): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 2077): isTurningOnRadio()=false
D/BluetoothAdapterState( 2077): isTurningOffRadio()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2077): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2077): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - Message: 1
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(784492867)( 2077): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 2077): isTurningOnRadio()=false
D/BluetoothAdapterState( 2077): isTurningOffRadio()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2077): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2077): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - Message: 1
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(784492867)( 2077): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 2077): isTurningOnRadio()=false
D/BluetoothAdapterState( 2077): isTurningOffRadio()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2077): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
W/ResourcesManager( 5601): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterService( 2077): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 2077): new notify threadi!
V/BluetoothOppNotification( 2077): send delay message
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - Message: 1
D/BluetoothAdapterService(784492867)( 2077): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(784492867)( 2077): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 2077): isTurningOnRadio()=false
D/BluetoothAdapterState( 2077): isTurningOffRadio()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2077): isQuietModeServiceTurningOff()=false
D/BluetoothAda,pterService( 2077): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(784492867)( 2077): onProfileServiceStateChange() - All profile services started.
,V/OppService( 2077): ContentObserver received notification
V/OppService( 2077): ContentObserver received notification
D/BluetoothAdapterState( 2077): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
V/OppService( 2077): pendingUpdate is :  true
I/bluedroid( 2077): enable
I/bt-btif ( 2077): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 2077): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/BluetoothOppProvider( 2077): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2077): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2077): created cursor android.database.sqlite.SQLiteCursor@27249103 on behalf of 
V/BluetoothOppProvider( 2077): created cursor android.database.sqlite.SQLiteCursor@3a12d880 on behalf of 
I/bt_hci_bdroid( 2077): init
I/bt_vendor( 2077): init
I/bt_vnd_conf( 2077): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2077): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
V/BluetoothOppNotification( 2077): mUpdateCompleteNotification = true
V/OppService( 2077): pendingUpdate is :  false
E/OppService( 2077): UpdateThread is Completed
I/bt-btif ( 2077): libbt-hci init returns 0
,V/BluetoothOppProvider( 2077): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 2077): created cursor android.database.sqlite.SQLiteCursor@2afd5eb9 on behalf of 
V/BluetoothOppNotification( 2077): outbound: succ-0  fail-0
I/NotificationManager( 2077): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 2077): outbound notification was removed.
V/BluetoothOppProvider( 2077): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 2077): created cursor android.database.sqlite.SQLiteCursor@3cd3e2fe on behalf of 
V/BluetoothOppNotification( 2077): inbound: succ-0  fail-0
I/NotificationManager( 2077): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
I/GKI_LINUX( 2077): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2077): btu_task pending for preload complete event
V/BluetoothOppNotification( 2077): inbound notification was removed.
V/BluetoothOppProvider( 2077): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2077): created cursor android.database.sqlite.SQLiteCursor@3d53a5f on behalf of 
I/IndexDatabaseHelper( 5601): Using schema version: 115
,I/IndexDatabaseHelper( 5601): Index is fine
I/bt_userial_vendor( 2077): userial vendor open: opening /dev/ttyHS99
,D/bt_userial_vendor( 2077): userial_vendor_open():UART is setup
I/bt_userial_vendor( 2077): device fd = 67 open
D/bt_hwcfg( 2077): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 2077): hw_config_cback state=1
,D/bt_hwcfg( 2077): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 2077): hw_config_cback state=4
D/bt_hwcfg( 2077): Chipset Name: BCM4334B0
D/bt_hwcfg( 2077): Chipset BCM4334B0
D/bt_hwcfg( 2077): Target name = [BCM4334B0]
I/bt_hwcfg( 2077): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 2077): hw_config_cback state=2
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 2077): hw_config_cback state=3
I/bt_hwcfg( 2077): bt vendor lib: set UART baud 4000000
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 2077): hw_config_cback state=5
,V/BluetoothPbapReceiver( 2077): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 2077): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2077): ***********state = 11
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5601): remove : truetruefalse
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5601): remove2
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
V/WiFiOffLoadSharedPrefsUtils( 5601): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 5601): save remove
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/WiFiOffLoadBroadcast( 5601): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5601): S: false, R: true
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/ActivityManager(  846): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5643 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/Tethering(  846): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/DSQN    (  846): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/BluetoothPermissionRequest( 5601): onReceive
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/LGBluetoothFeatureConfig( 5601):  get() - isFeatureLoaded : false
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
E/wpa_supplicant( 5598): USIM:  scard_init function
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/wpa_supplicant( 5598): rfkill: Cannot open RFKILL control device
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/Netd    (  280): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/Netd    (  280): M: Get netlink event, ifname: p2p0 action: 9
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/Netd    (  280): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/BluetoothManagerService(  846): Message: 20
D/BluetoothManagerService(  846): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@172712df:true
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
V/BluetoothSapReceiver( 2077): [BTUI] checkServiceStart
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/LGBluetoothStateChangeReceiver( 2077): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/wpa_supplicant( 5598): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,I/wpa_supplicant( 5598): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/WifiStateMachine(  846): MAC Addr from driver = a0:39:f7:70:12:80
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  846): setPowerSaveActivated(false)
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/ActivityManager(  846): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5664 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:54.234 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/WifiServerServiceExt(  846): WIFI_STATE_CHANGED_ACTION [3]
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/WifiServerServiceExt(  846): batteryPsActivateMsgHandler : state:0 event:3
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.WIFI_STATE_CHANGED at null
E/WifiServerServiceExt(  846): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2077): hw_config_cback state=6
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 2077): hw_config_cback state=6
E/WifiConfigStore(  846): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine(  846): enableVerboseLogging : level 2
,D/WifiStateMachine(  846): Setting OUI to DA-A1-19
D/WifiNative-HAL(  846): Setting external_sim to 1
D/WfdsService( 1833): Supplicant Connection state is changed : true
I/WifiNative-HAL(  846): startHal
E/wifi    (  846): getStaticLongField sWifiHalHandle 0x9b4488ec
I/WifiHAL (  846): Initializing wifi
I/WifiHAL (  846): Creating socket
D/WfdsService( 1833): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1833): Set the WFDS Monitor: true
I/WifiHAL (  846): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  846): Did set static halHandle = 0x9a342080
D/wifi    (  846): halHandle = 0x9a342080, mVM = 0xb487c280, mCls = 0x701b46
D/WfdsMonitor( 1833): WfdsMonitorThread create
E/wifi    (  846): getStaticLongField sWifiHalHandle 0x9b44889c
D/wifi    (  846): array field set
I/WifiNative-HAL(  846): interface[0] = wlan0
D/WfdsMonitor( 1833): WFDS Monitor is created and started
I/WifiNative-HAL(  846): interface[1] = p2p0
D/WfdsService( 1833): WiFi: Supplicant connection re-established
D/wifi    (  846): setting scan oui 0x9a3935c8
D/WifiHAL (  846): Sending mac address OUI
E/WifiHAL (  846): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  846): Setting OUI to DA-A1-19
I/WifiNative-HAL(  846): startHal
D/wifi    (  846): setting scan oui 0x9a3935c8
D/WifiHAL (  846): Sending mac address OUI
E/WifiHAL (  846): failed to set scanning mac OUI; result = -95
I/WifiNative-HAL(  846): Waiting for HAL events mWifiHalHandle=-1707859840
D/wifi    (  846): waitForHalEvents called, vm = 0xb487c280, obj = 0x701b46, env = 0xaaf05d60
E/wifi    (  846): getStaticLongField sWifiHalHandle 0x9958cb2c
,I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  846): hidePasspointNotification off =false
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/CtrlSupplicant( 1833): Access OK "@android:wpa_wlan0"
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:54.317 DNS addrs= 0.0.0.0, 0.0.0.0, 
E/CtrlSupplicant( 1833): Succeed to open control connection
E/CtrlSupplicant( 1833): Succeed to open monitor connection
D/WfdsMonitor( 1833): Supplicant connection established
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WfdsService( 1833): Connected to the supplicant for wfds
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
D/PCSuite ( 5643): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGWifiP2pService(  846): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Setting iface cfg
D/CommandListener(  280): Trying to bring up p2p0
D/WifiScanningService(  846): SCAN_AVAILABLE : 3
D/RttService(  846): SCAN_AVAILABLE : 3
D/WifiMonitor(  846): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService(  846): P2pEnablingState
,D/RttService(  846): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  846): DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  846): startHal
D/LGWifiP2pService(  846): P2p socket connection successful
D/LGWifiP2pService(  846): P2pEnabledState
D/wifi    (  846): getting scan capabilities on interface[0] = 0x9a3935c8
D/WifiHAL (  846): Creating message to get scan capablities; iface = 24
D/wifi    (  846): failed to get capabilities : -95
E/WifiScanningService(  846): could not get scan capabilities
D/UsbSettingsReceiver( 5601): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5601): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5601): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5601): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5601): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/LGWifiP2pService(  846): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  846): before postfix = G3s-1
D/WifiServerServiceExt(  846): postfix byte check : 5
D/LGWifiP2pService(  846): after postfix = G3s-1
I/WifiServerServiceExt(  846): set CMD_ADD_DEFAULT_PROFILE
D/WifiNative-HAL(  846): p2pGetDeviceAddress
I/WifiServerServiceExt(  846): setWifiDualbandAPConnection band : 1
D/WifiNative-HAL(  846): p2pGetDeviceAddress returning a2:39:f7:70:12:80
D/LGWifiP2pService(  846): DeviceAddress: a2:39:f7:70:12:80
D/WfdsService( 1833): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,D/WfdsService( 1833): Update P2p Interface State: 3
D/UsbSettingsControl( 5601): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 5601): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5601): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5601): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5601): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5601): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 5601): [AUTORUN] setTetherStatus() : status=false
I/bt_hwcfg( 2077): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2077): Settlement delay -- 100 ms
I/bt_hwcfg( 2077): Setting fw settlement delay to 100 
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadUpdatePriority( 5601): remove : truetruetrue
W/ResourcesManager( 5664): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/wpa_supplicant( 5598): nWIFIDualbandAPConnection: 1
D/LGWifiP2pService(  846): sending p2p persistent groups changed broadcast
,D/LGWifiP2pService(  846): sending p2p connection changed broadcast
I/WifiServerServiceExt(  846): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 5598): disconnect_rssi_lvl: -100
D/LGWifiP2pService(  846): InactiveState
I/WifiServerServiceExt(  846): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5598): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1833): WifiP2pState is changed : true
D/WfdsService( 1833): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1833): Receive the WFDS_ENABLE Method
D/WfdsService( 1833): Set the WFDS Monitor: true
D/WfdsService( 1833): Connected to the supplicant for wfds
D/WfdsJNI ( 1833): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 5598): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1833): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5598): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1833): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5598): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1833): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1833): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1833): selectPreferredScanChannel [6]
D/WfdsService( 1833): isConnected: false
D/WfdsService( 1833): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
I/WifiServerServiceExt(  846): set CMD_UPDATE_DEFAULT_PROFILE
,D/LGWifiP2pService(  846): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-18ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): DefaultState{ when=-18ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): InactiveState{ when=-19ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-19ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): DefaultState{ when=-19ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt(  846): No p2p device connected
D/WfdsService( 1833): GroupInfoAvailable: mGroupInfo is null
D/LGWifiP2pService(  846): InactiveState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): DefaultState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1833): DefaultState - msg [9441285] is not handled
I/wpa_supplicant( 5598): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
I/wpa_supplicant( 5598): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 5664): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
,I/ActivityManager(  846): Killing 5068:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/wpa_supplicant( 5598): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 2077): hw_config_cback state=2
,D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 2077): hw_config_cback state=7
I/bt_hwcfg( 2077): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2077): Setting local bd addr to F8:95:C7:87:85:54
W/libprocessgroup(  846): failed to open /acct/uid_10006/pid_5068/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/AuthorizationBluetoothService( 1734): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:54.51 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 2077): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 2077): hw_config_cback state=8
I/bt_hwcfg( 2077): vendor lib fwcfg completed
I/bt-btif ( 2077): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 2077): btu_task received preload complete event
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/wpa_supplicant( 5598): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/wpa_supplicant( 5598): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/        ( 2077): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 2077): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 2077): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 2077): BTE_InitTraceLevels -- TRC_PROTOCOL,0
D/LocSvc_java(  846): onReceive
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:54.533 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:54.542 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/GONS    ( 1753): GONS isTestMode: false Country: 
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:54.556 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:54.563 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
D/WifiServerServiceExt(  846): setSupplicantStateSCANNING
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/WiFiOffLoadUpdatePriority( 5601): remove1
V/WiFiOffLoadSharedPrefsUtils( 5601): save remove
,I/WifiServiceExtension(  846): setVHTCapabilityType  : false
D/WiFiOffLoadBroadcast( 5601): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5601): S: false, R: false
,I/WifiServerServiceExt(  846): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  846): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  846): setSecurityType  : 2
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:54.631 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:54.64 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/WifiExtManager(  846): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@2bd4922e
,D/ConnectivityService(  846): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  846): Got NetworkAgent Messenger
D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  846): NetworkAgent connected
D/WifiServiceExtension( 1833): isInternetCheckAvailable return false
E/WifiConfigStore(  846): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/bt-btif ( 2077): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,I/GKI_LINUX( 2077): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 2077): warning : media task started media_task_refcnt 1 
D/BT_PROF_AUDIO( 2077): created moving average (N=100)
D/BT_PROF_AUDIO( 2077): reset rate average
W/bt-btif ( 2077): overflow 0, enter 0, exit 0
E/WifiConfigStore(  846): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/bt-btif ( 2077): Calling BTA_HhEnable
E/bt-btif ( 2077): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 2077): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-smp  ( 2077): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2077): Plain text(LSB ~ MSB) = db 4c 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/BluetoothAdapterProperties( 2077): Address is:F8:95:C7:87:85:54
W/bt-smp  ( 2077): Encrypted text(LSB ~ MSB) = 51 d5 54 88 4e 63 df ff 8e d7 a5 66 0e e0 f2 a6 
W/bt-btm  ( 2077): Stopping oneshot timer
D/BluetoothAdapterProperties( 2077): Name is: G3s-1
D/BluetoothManagerService(  846): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  846): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 2077): Scan Mode:20
D/BluetoothAdapterProperties( 2077): Discoverable Timeout:120
V/BluetoothOppNotification( 2077): new notify threadi!
E/bt-btif ( 2077): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2077): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,V/BluetoothOppNotification( 2077): send delay message
E/bt-btif ( 2077): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 2077): BTA_JvEnable
E/bt-btif ( 2077): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 2077): btsock_ctrl_hci_init(L191): poll handle:6
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt-btif ( 2077): init_hci_slots(L136): in
D/IOP_DB_BT( 2077): db_open: file /etc/bluetooth/iop_bt.db
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/BluetoothOppProvider( 2077): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/CommandListener(  280): Setting iface cfg
D/IOP_DB_BT( 2077): db_open: db_open : handle 2690693084l, read 11046 bytes onto local cache
D/IOP_DB_BT( 2077): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 2077): db_query: result 1
I/        ( 2077): iop_db_open: iop_db_open status 0
E/bt-btif ( 2077): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 2077): btsock_ctrl_hci_init(L191): poll handle:6
D/bte_conf( 2077): Device ID record 1 : primary
D/bte_conf( 2077):   vendorId            = 00c4
D/bte_conf( 2077):   vendorIdSource      = 0001
D/bte_conf( 2077):   product             = 13a1
D/bte_conf( 2077):   version             = 1000
D/bte_conf( 2077):   clientExecutableURL = 
D/bte_conf( 2077):   serviceDescription  = 
D/bte_conf( 2077):   documentationURL    = 
D/bte_conf( 2077): bte_load_did_conf no section named DID2.
I/bt-btif ( 2077): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 2077): btif_hf_upstreams_evt: wrong handle = 8224 
I/bt-btif ( 2077): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 2077): opc_state_cb(L140):  opc_state_cb state:0
D/BluetoothAdapterState( 2077): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2077): ScanMode =  20
I/bt-btif ( 2077): bta_pan_co_init
D/BluetoothAdapterProperties( 2077): State =  11
D/BluetoothAdapterProperties( 2077): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 2077): Setting state to 12
I/BluetoothAdapterState( 2077): Bluetooth adapter state changed: 11-> 12
D/OppService( 2077): onOpcStateChange()
I/bt-btif ( 2077): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 2077): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 2077): Recieved MESSAGE_OPC_ENABLE
D/OppService( 2077): onOpsStateChange() :0
I/bt-btif ( 2077): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 2077): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 2077): onFtpServerEnabled: /storage
I/bt-btif ( 2077): HAL bt_hal_cbacks->adapter_properties_cb
D/LGBluetoothFeatureConfig( 2077): isPrivacyLogsEnabled : true
D/BluetoothAdapterService(784492867)( 2077): updateAdapterState() - Broadcasting state to 1 receivers.
D/OppService( 2077): Recieved MESSAGE_OPS_ENABLE
,D/BluetoothManagerService(  846): Message: 60
I/BluetoothAdapterState( 2077): Entering On State
V/BluetoothOppProvider( 2077): created cursor android.database.sqlite.SQLiteCursor@1e0cfcac on behalf of 
I/BluetoothAdapterState( 2077): Entering On State from state = 11
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
V/BluetoothOppNotification( 2077): mUpdateCompleteNotification = true
D/BluetoothAdapterService(784492867)( 2077): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(784492867)( 2077): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 2077): [BTUI] autoConnect() : not allowed
D/BluetoothAdapterProperties( 2077): Scan Mode:21
I/bt-btif ( 2077): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 2077): Discoverable Timeout:120
D/BluetoothPanServiceJni( 2077): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  846): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  846): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothA2dp( 2077): onBluetoothStateChange: up=true
D/bt_h4   ( 2077): vendor lib postload completed
D/BluetoothHeadset( 1753): onBluetoothStateChange: up=true
D/BluetoothA2dp(  846): onBluetoothStateChange: up=true
D/BluetoothHeadset(  846): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1753): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1753): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 2077): [BTUI] OnState
D/LGBluetoothServiceAdapter( 2077): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 2077): [BTUI]         local_name: G3s-1
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
E/BluetoothManagerService(  846): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothAdapterService(784492867)( 2077): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(784492867)( 2077): autoConnect() - Initiate auto connection on BT on...
D/BluetoothManagerService(  846): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService( 2077): [BTUI] autoConnect() : not allowed
V/BluetoothOppProvider( 2077): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
D/BluetoothManagerService(  846): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  846): Message: 40
D/BluetoothManagerService(  846): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothOppProvider( 2077): created cursor android.database.sqlite.SQLiteCursor@198c2d75 on behalf of 
,V/BluetoothOppNotification( 2077): outbound: succ-0  fail-0
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
I/NotificationManager( 2077): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 2077): outbound notification was removed.
V/BluetoothOppProvider( 2077): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
I/BluetoothMapService( 2077): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2077): STATE_ON
V/BluetoothMapService( 2077): Handler(): got msg=1
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
D/BluetoothMapMasInstance( 2077): Map Service startRfcommSocketListener
D/LGBluetoothAPIService( 1833): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothOppProvider( 2077): created cursor android.database.sqlite.SQLiteCursor@3407310a on behalf of 
E/WifiStateMachine(  846): Start Dhcp Watchdog 1
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateASSOCIATED
D/LGBluetoothAPIService( 1833): Message: 1
,D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateFOUR_WAY_HANDSHAKE
D/LGBluetoothAPIService( 1833): MESSAGE_BOOT_COMPLETED
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt(  846): setSupplicantStateGROUP_HANDSHAKE
D/DhcpStateMachine(  846): StoppedState
D/DhcpStateMachine(  846): StoppedState{ when=-10ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  846): WaitBeforeStartState
D/WiFiOffLoadUpdatePriority( 5601): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5601): connected SSID: null
D/WiFiOffLoadUpdatePriority( 5601): private wpa: "NG700" 300
I/QCNEJ   ( 1886): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/LGBluetoothAPIService( 1833): [BTUI] LGBluetoothAPIService Binding Success
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-55 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:54.746 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiServiceImplEx(  846): addOrUpdateNetwork pid=5601, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  846):  uid = 1000 SSID "NG700" nid=0
D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateCOMPLETED
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
D/BluetoothMapMasInstance( 2077): MAS initSocket()
D/BluetoothMapMasInstance( 2077):   masId = 00
D/BluetoothMapMasInstance( 2077):   msgTypes = 0e
D/BluetoothMapMasInstance( 2077):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2077):   SDP string = 000eSMS/MMS
D/BluetoothAdapterService( 2077): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec26943
D/BluetoothManagerService(  846): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1372): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
V/BluetoothOppNotification( 2077): inbound: succ-0  fail-0
,V/BluetoothPbapService( 2077): Pbap Service onCreate
V/BluetoothPbapService( 2077): Starting PBAP service
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
W/BluetoothAdapter( 2077): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothPbapAdapter( 2077): [BTUI] getInstance : create
,V/BluetoothPbapService( 2077): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2077): state: 12
I/bt-btif ( 2077): BTA_JvCreateRecordByUser
I/bt-btif ( 2077): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 2077): [BTUI] createSocketChannel FD=84 mFd=0
V/BluetoothMapMasInstance( 2077): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2077): Accepting socket connection...
D/LGBluetoothAPIServer( 2077): [BTUI] onCreate()
D/LGBluetoothAPIServer( 2077): [BTUI] onBind()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/NotificationManager( 2077): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
V/BluetoothPbapService( 2077): Handler(): got msg=1
D/LGBluetoothAPIService( 1833): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1833): Message: 100
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
V/BluetoothPbapService( 2077): Pbap Service startRfcommSocketListener
D/LGBluetoothAPIService( 1833): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 2077): Pbap Service initSocket
D/BluetoothManagerService(  846): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 2077): inbound notification was removed.
V/BluetoothOppProvider( 2077): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
W/BluetoothAdapter( 2077): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2077): BTA_JvCreateRecordByUser
I/bt-btif ( 2077): BTA_JvRfcommStartServer
,D/LGBluetoothServiceAdapter( 2077): [BTUI] createSocketChannel FD=85 mFd=84
V/BluetoothPbapService( 2077): Succeed to create listening socket 
V/BluetoothPbapService( 2077): Accepting socket connection...
V/BluetoothOppProvider( 2077): created cursor android.database.sqlite.SQLiteCursor@29ff2bf1 on behalf of 
E/WifiStateMachine(  846): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  846): Current State is mWaitBeforeStartState.
,D/LGWifiP2pService(  846): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1a7f6fb6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1a7f6fb6 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  846): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  846): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  846): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  846): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
E/WifiConfigStore(  846):  key="NG700"WPA_PSK netId=0 uid=0/1000
E/WifiConfigStore(  846): Setting BSSID for "NG700"WPA_PSK to any
,D/WiFiOffLoadUpdatePriority( 5601):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5601): configuration updated: 0
I/WifiServerServiceExt(  846): set CMD_UPDATE_DEFAULT_PROFILE
,D/WiFiOffLoadUpdatePriority( 5601): configuration saved: true
,D/PCSuite ( 5643): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 5601): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager(  846): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5702 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 337us total 21.616ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.542ms
,V/BluetoothPbapReceiver( 2077): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2077): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2077): ***********state = 12
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
,D/LocalBluetoothProfileManager( 5601): Adding local A2DP profile
D/BluetoothManagerService(  846): Message: 30
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.228ms
D/LocalBluetoothProfileManager( 5601): Adding local HEADSET profile
D/BluetoothManagerService(  846): Message: 30
,D/DhcpStateMachine(  846): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  846): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  846): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/BluetoothManagerService(  846): Message: 30
,D/BluetoothManagerService(  846): Message: 30
I/dhcpcd  ( 5719): version 5.5.6 starting
D/LocalBluetoothProfileManager( 5601): Adding local MAP profile
D/BluetoothMap( 5601): Create BluetoothMap proxy object
,E/dhcpcd  ( 5719): get_duid: Read-only file system
D/BluetoothManagerService(  846): Message: 30
D/BluetoothManagerService(  846): Message: 30
D/LocalBluetoothProfileManager( 5601): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 2077): Pbap Service onBind
,D/LGBluetoothUserBindClient( 5601): [BTUI] initUserBindClient
W/ContextImpl( 5601): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 5601): finishStartingService: stopping service
D/BluetoothA2dp( 5601): Proxy object connected
,D/A2dpProfile( 5601): Bluetooth service connected
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
D/BluetoothHeadset( 5601): Proxy object connected
D/HeadsetProfile( 5601): Bluetooth service connected
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
D/BluetoothInputDevice( 5601): Proxy object connected
D/HidProfile( 5601): Bluetooth service connected
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
D/BluetoothPan( 5601): BluetoothPAN Proxy object connected
D/PanProfile( 5601): Bluetooth service connected
,D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
D/BluetoothMap( 5601): Proxy object connected
D/MapProfile( 5601): Bluetooth service connected
D/BluetoothMap( 5601): getConnectedDevices()
D/BluetoothAdapterService(784492867)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19df6631
V/BluetoothMapService( 2077): getConnectedDevices()
D/BluetoothPbap( 5601): Proxy object connected
D/PbapServerProfile( 5601): Bluetooth service connected
D/LGBluetoothUserBindClient( 5601): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 5601): onReceive
,D/LGBluetoothFeatureConfig( 5601): isPrivacyLogsEnabled : true
I/dhcpcd  ( 5719): wlan0: broadcasting for a lease
D/LGBluetoothUtils( 5601): [BTUI] FileNotFound: readProperty
I/ActivityManager(  846): Killing 5183:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10053/pid_5183/cgroup.procs: No such file or directory
,V/BluetoothOppReceiver( 2077): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
V/BluetoothOppManager( 2077): restoreApplicationData! falsefalsenullnull
D/LGDMClient( 5702): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5702): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/BluetoothSapReceiver( 2077): [BTUI] checkServiceStart
,W/ContextImpl( 5702): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGBluetoothStateChangeReceiver( 2077): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
W/ContextImpl( 5702): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/AuthorizationBluetoothService( 1734): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
D/LGDMClient( 5702): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5702): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 5643): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5643): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5643): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 5702): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/ActivityManager(  846): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5739 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  846): Killing 4010:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10006/pid_4010/cgroup.procs: No such file or directory
,V/[BNRBootReceiver]( 5739): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5739): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{3f565a97 type 2 when 99560 com.google.android.gms} when 99560
V/[BNRBootReceiver]( 5739): Boot Receiver Return
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 5601): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
I/ActivityManager(  846): Killing 5419:com.android.calendar/u0a13 (adj 15): empty #11
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  846): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/dhcpcd  ( 5719): wlan0: offered 192.168.1.134 from 192.168.1.1
,I/Netd    (  280): M: Get netlink event, ifname: p2p0 action: 6
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  846): failed to open /acct/uid_10013/pid_5419/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5762 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5762): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5762): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5762): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5762): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5762): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5762): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5762): MmsConfig.loadFromResources
E/Babel_SMS( 5762): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5762): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5762): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5762): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5762): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5762): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5762): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5762): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5762): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5762): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5762): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5762): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5762): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5762): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5762): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5762): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5762): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5762): found sensor: Motion Accel, handle=46
,W/Settings( 5762): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5762): startup - clean
I/art     ( 5762): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/art     ( 5762): CheckpointMarkThreadRoots callback created = 0xb042d860
,I/Babel   ( 5762): deleted: false for 0
,V/AudioFlinger(  285): thread 0xb5735000 type 0 TID 1293 going to sleep
V/AudioFlinger(  285): thread 0xb56eb000 type 0 TID 1291 going to sleep
V/AudioFlinger(  285): thread 0xb5651000 type 0 TID 1290 going to sleep
W/AudioCapabilities( 5762): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5762): Unsupported mime audio/adpcm
W/AudioCapabilities( 5762): Unsupported mime audio/g726
W/AudioCapabilities( 5762): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5762): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5762): Unsupported mime video/mjpg
W/VideoCapabilities( 5762): Unsupported mime video/theora
W/AudioCapabilities( 5762): Unsupported mime audio/evrc
,W/AudioCapabilities( 5762): Unsupported mime audio/qcelp
W/VideoCapabilities( 5762): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5762): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5762): Unsupported mime audio/qcelp
W/AudioCapabilities( 5762): Unsupported mime audio/evrc
W/VideoCapabilities( 5762): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5762): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5762): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5762): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5762): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5762): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  846): Killing 5390:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,W/libprocessgroup(  846): failed to open /acct/uid_10014/pid_5390/cgroup.procs: No such file or directory
,I/vclib   ( 5762): onServiceConnected
W/Babel   ( 5762): Attempted to change video mute state without an active call.
I/NotificationManager( 5762): com.google.android.talk: cancel(10436) by com.google.android.talk
I/dhcpcd  ( 5719): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5719): wlan0: leased 192.168.1.134 for 86400 seconds
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  846): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  846): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  846): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  846): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  846): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  846): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  846): bShouldSendDhcpAction Result: true
D/DhcpStateMachine(  846): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  846): RunningState
D/LGWifiP2pService(  846): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine(  846): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  846): ignoring duplicate network state non-change
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  846): Adding iface wlan0 to network 100
D/WifiServiceExtension( 1833): isInternetCheckAvailable return false
D/WifiServiceExtension( 1833): isInternetCheckAvailable return false
D/WifiHS20(  846): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:57.112 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:57.118 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:57.121 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 3
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine(  846): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiHS20(  846): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1886): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:57.139 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1886): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 3
,E/ConnectivityService(  846): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  846): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  846): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  846): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  846): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  846): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  846): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  846): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  846): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  846):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  846):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):     satisfied: NetworkReques,t [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  846): currentScore = 0, newScore = 20
D/ConnectivityService(  846):    accepting network in place of null
D/ConnectivityService(  846): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WIFI    (  846): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  846):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1753): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  846): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] Start DNSResolver start to wait
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] wait 500ms before dns check
,E/ConnectivityService(  846): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  846): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/ConnectivityService(  846): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  846): MasterInitialState.processMessage what=3
D/CSLegacyTypeTracker(  846): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  846): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  846): validation of new default Network = false
D/ConnectivityService(  846): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  846): enableDataServiceNotify 
D/DSQN    (  846): start dsqn bin
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
,W/QCNEJ   ( 1886): |CORE| No family connected
I/QCNEJ   ( 1886): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1886): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  846): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  846): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/DSQN    ( 5829): DSQN samuel.seo ver 141203
,E/DSQN    ( 5829): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5829): created command queue thread
I/DSQN    ( 5829): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5829): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  846): propertyValue:false
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
I/PCSuite ( 5643): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5643): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/NetworkPolicy(  846): [LG_RESTRICTED] checkMobilePolicy_type()
V/WiFiOffLoadBroadcast( 5601): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5601): MCCMNC not supported: null
I/PCSuite ( 5643): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5643): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] DNSResolver start dns
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out(  846): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Checking http://clients3.google.com/generate_204 on "NG700"
I/QCNEJ   ( 1886): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:03:57.76 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5829): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5829): restart monitoring
,I/DSQN    ( 5829): dsqn report finish
D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  846): DSQM DsqnNotification wlan0  1
D/DSQN    (  846): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 04 Jan 2016 16:03:55 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451923437834], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451923437807]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1833): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Validated
D/ConnectivityService(  846): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  846):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  846): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  846): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
,D/ConnectivityService(  846): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  846): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  846):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1753): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiDataContinuityService(  846): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  846): set CMD_CAPTIVE_CHECK_COMPLETED
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/rmt_storage(  276): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  276): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  276): wakelock acquired: 1, error no: 42
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  276): 
I/rmt_storage(  276): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=361126491, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,D/WeatherService( 2729): 2 : TimeTick Intent has been received, Time(hour:min:sec) 17:4:0
D/WeatherService( 2729): 2 : TimeTick Intent And Screen On
D/WeatherService( 2729): 2 : SDK version : 21
W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2729): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2729): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2729): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/WeatherService( 2729): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2729): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2729): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2729): 2 : Fixed theme : optimus
D/WeatherReflect( 2729): 2 : Map key string is -2
D/lim     ( 2729): 2 : time = 17:04
I/WeatherReflect( 2729): Model Name : LG-D722
D/WeatherTheme( 2729): 2 : Different view - status_min_formatted : 03 != 04
D/WeatherTheme( 2729): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2729): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
,D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2729): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/Weather4x2_optimus( 2729): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2729): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2729): forecast size is 0
,D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2729): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2729): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2729): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2729): url is : null
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2729): 2 : update view, appWidgetId: 2
,V/WifiInternetCheck(  846): Single check msg out of sync, ignoring.
D/WeatherService( 2729): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 17:4:0
D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=361126491 [*alarm*], flags=0x0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  846): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  846): onReceive
D/LocSvc_java(  846): got connectivity action
,D/LocSvc_java(  846): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  846): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  846): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  846): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  846): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  846): Sending msg: 5 arg1:0 arg2:1
I/ActivityManager(  846): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5858 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AlarmManagerService(  846): Setting time of day to sec=1451923438
W/AlarmManagerService(  846): Unable to set rtc to 1451923438: Invalid argument
D/LocSvc_java(  846): NTP server returned: 1451923435532 (Mon Jan 04 17:03:55 GMT+01:00 2016) reference: 101333 certainty: 10 system time offset: -2973
D/LocSvc_java(  846): Sending msg: 10 arg1:0 arg2:1
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1949): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/LocSvc_java(  846): reportXtraServer 
D/LocSvc_java(  846):  server1=http://xtrapath1.izatcloud.net/xtra2.bin
D/LocSvc_java(  846):  server2=http://xtrapath2.izatcloud.net/xtra2.bin
D/LocSvc_java(  846):  server3=http://xtrapath3.izatcloud.net/xtra2.bin
D/LocSvc_java(  846): xtraDownloadRequest
D/LocSvc_java(  846): Sending msg: 6 arg1:0 arg2:1
I/[SystemUI]Clock( 1372): onReceive = android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
D/WeatherService( 2729): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 17:3:58
,D/WeatherService( 2729): 2 : requestRefreshAppWidget, isUpdateStart : false
I/ActivityManager(  846): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5872 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/WeatherService( 2729): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2729): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2729): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2729): 2 : Fixed theme : optimus
,I/ActivityManager(  846): Start proc com.google.android.gms for service com.google.android.gms/.auth.api.credentials.sync.CredentialSyncService: pid=5900 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
E/[LgeWidgetLib]LgeAppWidgetHostView( 1949): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/WeatherReflect( 2729): 2 : Map key string is -2
W/ActivityManager(  846): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
D/lim     ( 2729): 2 : time = 17:03
I/WeatherReflect( 2729): Model Name : LG-D722
D/WeatherTheme( 2729): 2 : Different view - status_min_formatted : 04 != 03
,D/WeatherTheme( 2729): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out(  846): propertyValue:false
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WeatherReflect( 2729): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2729): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[LGHome]LGDateChangeReceiver( 1949): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=4 currentDate=-1 dayofweek=2 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 1949): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 4
,W/ResourcesManager( 5872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5872): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5872): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/Weather4x2_optimus( 2729): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
,D/Weather4x2_optimus( 2729): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2729): forecast size is 0
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2729): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2729): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2729): setTouchIntent, appWidgetId: 2
I/ActivityManager(  846): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5918 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/LocSvc_java(  846): calling native_inject_xtra_data
D/LocSvc_java(  846): Sending msg: 11 arg1:0 arg2:1
,D/GpsLocationProvider(  846): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[LGHome]LGCalendarIcon( 1949): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 4
,I/[LGHome]Launcher( 1949): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 5900): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5900): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  846): Process com.android.vending (pid 4953) has died
,D/Theme_WeatherAncestor_optimus( 2729): url is : null
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2729): 2 : update view, appWidgetId: 2
,D/WeatherService( 2729): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 17:3:58
I/MultiDex( 5900): VM with version 2.1.0 has multidex support
,I/MultiDex( 5900): install
I/MultiDex( 5900): VM has multidex support, MultiDex support library is disabled.
I/[LgeWidgetLib]LgeAppWidgetHostView( 1949): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/art     (  846): Explicit concurrent mark sweep GC freed 75212(3MB) AllocSpace objects, 4(106KB) LOS objects, 33% free, 23MB/34MB, paused 4.735ms total 351.910ms
,I/LGEmail ( 5872): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1949): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
D/LGEmail ( 5872): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
W/ResourcesManager( 5918): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5918): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  846): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5938 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 5918): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,E/GpsLocationProvider(  846): No APN found to select.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LgeGpsConstants(  846): Can't find 'ext_gps.conf'!!
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/MusicStore( 5858): Database version: 120
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
,V/JNIHelp ( 5900): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out(  846): propertyValue:false
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  846): propertyValue:false
,V/WifiInternetCheck(  846): isHttpConnectionAvailable - We got a valid response : 204
,I/AppConfig( 5918): Total System Memory = 906309632
W/ActivityThread( 5900): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5900): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d53a5f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/GalleryUtils( 5918): Application Heap = 96 MB
I/ProviderInstaller( 5900): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5900): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5900): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/AppConfig( 5918): App Tier : NOT_DEF
D/SystemHelper( 5918): region [EU], country [EU], operator [OPEN], sub-operator []
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out(  846): propertyValue:false
W/ResourcesManager( 5938): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5938): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  846): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=5978 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
D/LgeGpsLocationProvider(  846): NTP server: europe.pool.ntp.org
,D/LgeGpsLocationProvider(  846): NTP server returned: 1451923439655 (Mon Jan 04 17:03:59 GMT+01:00 2016) reference: 105631 certainty: 31 system time offset: -136
,I/ActivityManager(  846): Process com.lge.settings.easy (pid 5664) has died
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5858): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/JNIHelp ( 5938): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  846): Process com.lge.lgdmsclient (pid 5702) has died
,D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=361126491, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,W/art     ( 5900): Suspending all threads took: 85.073ms
,I/NotificationManager(  846): android: cancelAsUser(-1597574061) by android
,W/System  ( 5938): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5938): Installed default security provider GmsCore_OpenSSL
I/art     ( 5900): Background sticky concurrent mark sweep GC freed 24486(1290KB) AllocSpace objects, 5(80KB) LOS objects, 10% free, 10MB/11MB, paused 99.461ms total 204.043ms
I/art     ( 5900): CheckpointMarkThreadRoots callback created = 0xaaf52bf0
D/NativeLibraryUtils( 5900): Install completed successfully. count=14 extracted=0
,D/ALBootInit( 5978): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 5978): Alarm ALBootInit: TIME_SET
D/Alarms  ( 5978): [setNextAlert] start
I/art     ( 5900): CheckpointMarkThreadRoots callback created = 0xaaf52bd0
,I/art     ( 5900): Background partial concurrent mark sweep GC freed 627(116KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 10MB/16MB, paused 7.081ms total 62.552ms
,D/Alarms  ( 5978): [setNextAlert] (1)
D/Alarms  ( 5978):  minTime  = 0
D/Alarms  ( 5978):  -- OK multi -- 0
E/jeny.kim( 5978): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 5978): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,I/CommonUtil( 5978): BUILD Operator: OPEN
,D/Alarms  ( 5978): broadcastToWidgetProvider : false
D/Alarms  ( 5978): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,V/SettingsProvider(  846): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 5978): onReceive: android.intent.action.TIME_SET
,V/DigitalAppWidgetProvider( 5978): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1284d1fd
V/DigitalAppWidgetProvider( 5978): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1284d1fd
,I/NotificationManager(  846): android: cancelAsUser(-1816247584) by android
D/QuickCoverProvider( 5978): onReceiver
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/art     ( 5900): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5900): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  846): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6019 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5858): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5858): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 5858): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5858): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/ActivityThread( 5900): Failed to find provider info for com.android.contacts.metadata
,V/JNIHelp ( 5858): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/art     ( 5938): Suspending all threads took: 7.108ms
,I/art     ( 5938): CheckpointMarkThreadRoots callback created = 0xaaf379d0
,W/ActivityThread( 5858): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5858): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@fcd61b0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5858): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5858): GMSCore installation verified
,E/YouTube MDX( 5938): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/art     ( 5938): CheckpointMarkThreadRoots callback created = 0xb4958de0
I/ActivityManager(  846): Process com.google.android.talk (pid 5762) has died
,D/CalendarApplication( 6019): CalendarApplication.onCreate()
D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ConfigStore( 5858): Config Database version: 1
D/PreferenceKeysParser( 6019): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6019): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@38184fa8, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@e8f4ac1, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2e0fd266, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@fbbd9a7, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2d76be54, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1284d1fd, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@136aef2, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2ec26943, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@11ab6bc0, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@175190f9, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@217cc83e, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2518569f, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@13bb83ec, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3d9143b5, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@c792a4a, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@39b5bdbb, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2bd2f2d8, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@19df6631, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1027a116, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@20f87a97, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@26f06484, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1513346d, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@c74b8a2, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@d402933, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@15144f0, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@143baa69, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@189bcee, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2d4a258f, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3b9dc01c, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@245b8425, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@36d8b9fa, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@344d8bab, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@16d4c208, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@25e53da1, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@6e87bc6, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@7d73787, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@22f7f6b4, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@33f712dd, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1be08e52, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2f65c523, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.Pr,eferenceKey$KeyData@c77ca20, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@356ffd9, 
,D/GeneralPreferenceUtils( 6019): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6019): [init]
I/Config  ( 6019): LGCalendar ver.4.40.17
I/Config  ( 6019): start check model
I/Config  ( 6019): start check native_ca
I/Config  ( 6019): Config Operator=OPEN, Country=EU
D/Config  ( 6019): [setDefaultValuesToPref]
D/Config  ( 6019): [parseProfiles]
,D/ProfilesParser( 6019): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6019): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6019): [updateProfiletoCountryInfo]
D/GeneralPreference( 6019): [checkAndMigrateOldPreference]
D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 37397, reason: UserStart, SyncResult: databaseError: true stats []
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
D/SyncManager(  846): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 138366, reason: UserStart
I/NotificationManager(  846): android: cancelAsUser(716319171) by android
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/AgendaWidgetManager( 6019): [updateWidgets] 
,I/InitNotificationRingtoneService( 6019): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6019): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,W/ResourcesManager( 5938): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5938): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  846): Process com.lge.bnr (pid 5739) has died
,I/AlertUtils( 6019): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
E/Auth.Api.Credentials( 5900): [CredentialSyncAdapter] Unknown sync event.
I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6019): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6019): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6019): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6019): End InitializeAlertRingtoneService.onHandleIntent
,I/NotificationManager(  846): android: cancelAsUser(-591465577) by android
I/NotificationManager( 5938): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 5938): Found 10006
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/dex2oat ( 6065): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-375626393.jar --oat-fd=42 --oat-location=/data/data/com.google.android.youtube/cache/ads-375626393.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/MonthWidgetProvider( 6019): [onReceive]
D/CalendarWidgetProvider( 6019): [onReceive]
D/CalendarWidgetProvider( 6019): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,D/CalendarTypeController( 6019): [onUpdateAndInitCalendarTime]
W/HolidayIntentService( 6019): onHandleIntent
D/HolidayDataLoader( 6019): readJsonAsset : holiday.json
E/HolidayIntentService( 6019): onHandleIntent:holiday data empty
,I/NotificationManager(  846): android: cancelAsUser(-1816247584) by android
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/dex2oat ( 6065): dex2oat took 167.598ms (threads: 4)
,I/art     (  846): Explicit concurrent mark sweep GC freed 27898(1336KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 3.075ms total 237.057ms
,D/WeekWidgetProvider( 6019): [onReceive]
D/CalendarWidgetProvider( 6019): [onReceive]
D/CalendarWidgetProvider( 6019): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6019): [onUpdateAndInitCalendarTime]
D/WeatherAncestor( 2729): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 17:4:1
,D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/Weather_cast( 2729): 2 : set auto-update time : 1/4 20:4
D/WeatherAncestor( 2729): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 17:4:1
D/WeatherService( 2729): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
,I/MediaRouter( 5858): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/ActivityManager(  846): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6109 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/PhenotypeConfigurator( 1734): Server returned 404
W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
I/NotificationManager(  846): android: cancelAsUser(-1597574061) by android
D/Weather.Utils( 2729): 2 : Utils getTopActivity com.lge.launcher2 / true
V/MusicLeanback( 5858): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/WeatherService( 2729): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/NetworkMonitor( 5858): type=WIFI subType= reason=null isConnected=true
,I/NotificationManager( 5938): com.google.android.youtube: cancel(10436) by com.google.android.youtube
D/TimeService( 6109): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1451923441780
D/        ( 6109): TimeServiceNative: User Time to be set is 1451923441780
D/QC-time-services( 6109): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6109): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6109): Lib:time_genoff_operation: pargs->ts_val = 1451923441780
D/QC-time-services( 6109): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  329): Daemon: Connection accepted:time_genoff
D/QC-time-services(  329): Daemon:Received base = 2, unit = 1, operation = 0,value = 1451923441780
D/QC-time-services(  329): Daemon:genoff_opr: Base = 2, val = 1451923441780, operation = 0
D/QC-time-services(  329): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/17/70 20:5:40
,D/QC-time-services(  329): Daemon:Value read from RTC seconds = 11822740000
D/QC-time-services(  329): Daemon:new time 1451923441780 
D/QC-time-services(  329): Daemon: delta 1440100701780 genoff 1440100701780 
D/QC-time-services(  329): Daemon:genoff_persistent_update: Writing genoff = 1440100701780 to memory
D/QC-time-services(  329): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  329): Daemon:time_persistent_memory_opr:Genoff write operation 
D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  280): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
,D/ConnectivityService(  846): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/QC-time-services(  329): Updating the TOD offset
D/QC-time-services(  329): Daemon:genoff_persistent_update: Writing genoff = 1440100701780 to memory
D/QC-time-services(  329): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  329): Daemon:time_persistent_memory_opr:Genoff write operation 
D/ConnectivityService(  846): dumpNetworkRequest
D/ConnectivityService(  846):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  846):     Requests:
D/ConnectivityService(  846):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846):     Lingered:
D/ConnectivityService(  846): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846): apparently satisfied.  currentScore=60
D/ConnectivityService(  846): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 5900): CM callback handler got msg 524290
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 5938): propertyValue:false
E/QC-time-services(  329): Daemon:Update to modem bit set
D/QC-time-services(  329): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  329): Daemon: Base = 2, Value being sent to MODEM = 1124135901780
D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/QC-time-services( 6109): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  329): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  329): Daemon: Time-services: Waiting to acceptconnection
I/NetworkMonitor( 5858): type=WIFI subType= reason=null isConnected=true
,I/CheckinService( 5900): Checkin interval check for package: unspecified last checkin: 1450837195376 min interval config: 0 actual interval: 1086246571
,I/GHttpClientFactory( 5858): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5858): Using platform SSLCertificateSocketFactory
D/eas_req ( 5872): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/ChimeraCfgMgr( 5900): Reading stored module config
,I/NotificationManager(  846): android: cancelAsUser(-591465577) by android
,D/ChimeraCfgMgr( 5900): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5900): Loading module APK com.google.android.play.games
D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 5529): Explicit concurrent mark sweep GC freed 1733(74KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.202ms total 71.185ms
,I/ActivityManager(  846): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6149 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 309us total 25.916ms
,I/NotificationManager( 5858): com.google.android.music: cancel(1061) by com.google.android.music
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.915ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 28.846ms
I/HubEmail( 5872): JNI_OnLoad()
I/HubEmail( 5872): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5872): registerNatives()
I/HubEmail( 5872): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5872): registerNativeMethods()
I/HubEmail( 5872): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 5872): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  846): Process com.android.settings (pid 5601) has died
,W/Settings( 5872): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WeatherService( 2729): 2 : TimeTick Intent has been received, Time(hour:min:sec) 17:4:2
,D/WeatherService( 2729): 2 : TimeTick Intent And Screen On
D/WeatherService( 2729): 2 : SDK version : 21
W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2729): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2729): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2729): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/WeatherService( 2729): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2729): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2729): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2729): 2 : Fixed theme : optimus
D/WeatherReflect( 2729): 2 : Map key string is -2
,D/LGDMClient( 6149): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6149): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/lim     ( 2729): 2 : time = 17:04
I/WeatherReflect( 2729): Model Name : LG-D722
D/WeatherTheme( 2729): 2 : Different view - status_min_formatted : 03 != 04
D/WeatherTheme( 2729): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2729): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2729): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/GamesSyncServiceMain( 5900): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 5900): Failed to execute periodic sync, missing client context - aborting
W/ContextImpl( 6149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6149): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6149): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/Weather4x2_optimus( 2729): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2729): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2729): forecast size is 0
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2729): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2729): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2729): setTouchIntent, appWidgetId: 2
D/LGDMClient( 6149): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6176 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/Theme_WeatherAncestor_optimus( 2729): url is : null
I/LGDMClient( 6149): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2729): 2 : update view, appWidgetId: 2
,D/WeatherService( 2729): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 17:4:2
D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=361126491 [*alarm*], flags=0x0
,W/ContextImpl( 6149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6149): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6149): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6149): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6149): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6149): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/NotificationManager(  846): android: cancelAsUser(-1548111331) by android
,I/ActivityManager(  846): Killing 5161:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5134): android.os.DeadObjectException
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
W/System.err( 5134): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5134): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5134): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5134): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5134): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5134): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5134): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5134): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5134): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5134): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5134): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5134): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5134): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5134): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5134): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5134): android.os.DeadObjectException
W/System.err( 5134): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5134): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5134): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5134): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5134): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5134): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5134): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5134): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5134): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5134): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5134): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5134): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5134): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5134): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5134): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/AppUp4:AppBoxCP( 6176): onCreate
W/AppUp4:DB( 6176):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6176):  setFingerPrint start
I/AppUp4:DB( 6176):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6176):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6176):  SDK version = 0
I/AppUp4:DB( 6176):  beforefinger == newfinger no write in DB
I/[LgeWidgetLib]LgeAppWidgetHostView( 1949): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/libprocessgroup(  846): failed to kill 1 processes for processgroup 5161
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1949): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/ActivityManager(  846): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/AppUp4:AppBoxApplication( 6176): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6176): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6176): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6176): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6176): [onReceive] request level :IDLE....
,I/ActivityManager(  846): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6195 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6204 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager(  846): android: cancelAsUser(-1816247584) by android
I/ActivityManager(  846): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6223 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/AppUp4:CustModeStarterReceiver( 6176): onReceive
I/AppUp4:CustModeStarterReceiver( 6176): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6176): Context : android.app.ReceiverRestrictedContext@2d76be54
D/AppUp4:CustFacade( 6176): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6176): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6176): begin check event
I/AppUp4:CustModeStarterReceiver( 6176): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6176): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
W/DriveInitializer( 5900): Awaiting to be initialized
,W/DriveInitializer( 5900): Background init thread started
D/AppUp4:CustModeStarterReceiver( 6176): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6176): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6176): handleAsyncCustNotification do not startCustService
I/ActivityManager(  846): Killing 5643:com.lge.sync/1000 (adj 15): empty #11
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5900): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,D/UEI.SmartControl( 6204): Quickset Services start...
I/UEI.SmartControl( 6204): Manufacture = LGE
D/UEI.SmartControl( 6204): File observer start...
,E/UEI.SmartControl( 6204): IR Port is disabled: false
D/UEI.SmartControl( 6204): Starting file observer...
D/UEI.SmartControl( 6204): Extracting JNI libs...
,D/UEI.SmartControl( 6204): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  846): Process com.lge.qremote (pid 5134) has died
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_5643/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3122): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,D/UEI.SmartControl( 6204): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6204): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6204): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/LgeMiscReceiver( 3122): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3122): networkInfo.isConnected() = true
,D/PhoneState( 3122): setPdpRejectCasuse : false
,I/ActivityManager(  846): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6272 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/UEI.SmartControl( 6204): --- Selecting new region: 2
I/UEI.SmartControl( 6204): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6204): Platform has CIR...
,D/UEI.SmartControl( 6204): NO CIR support, need to check package...
I/UEI.SmartControl( 6204): Model: LG-D722 uses JNI
W/DriveInitializer( 5900): Background init thread ended
D/UEI.SmartControl( 6204): QS Service created
I/ActivityManager(  846): Process com.lge.clock (pid 5978) has died
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6195): getAccountsCursor
,E/UEI.SmartControl( 6204): QS start get config
I/NotificationManager( 5900): com.google.android.gms: cancel(10436) by com.google.android.gms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 6204): Loading JNI Libs...
W/GAV2    ( 6195): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/UEI.SmartControl( 6204):  configuring local db...
,I/NotificationManager(  846): android: cancelAsUser(353845882) by android
,I/GAv4    ( 6223): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6223):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6223):   adb logcat -s GAv4
E/Gmail   ( 6195): Error finding the version of the Email provider.....
E/Gmail   ( 6195): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6195): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6195): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6195): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6195): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6195): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6195): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6195): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PhoneMonitor( 6272): Register our PhoneStateListener
I/Gmail   ( 6195): getAccountsCursor
W/EmailMigration( 6195): We do not support migrating this version of the Email provider.
D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  280): App 10100 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Gmail   ( 6195): Sync started for account: account:61035162
E/BandwidthController(  280): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  280): App 10100 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
W/GAv4    ( 6223): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 5938): propertyValue:false
D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/System.out( 5938): propertyValue:false
D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/GAv4    ( 6223): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/MobileConnectivityChangeReceiver( 6272): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6272): onReceive CONNECTIVITY_CHANGE networkType=1
,W/GAv4    ( 6223): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 6223): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
V/DownloadManager( 3144): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3144): DownloadService onCreate
,I/ActivityManager(  846): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6324 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/DownloadManager( 3144): in removeSpuriousFiles
,I/NotificationManager( 3144): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3144): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/PhoneMonitor( 6272): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6272): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6272): [parse] Load xml
V/TelephonyAutoProfiling( 6272): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6272): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3144): created cursor android.database.sqlite.SQLiteCursor@2f65c523 on behalf of 3144
,W/ActivityManager(  846): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/PhoneMonitor( 6272): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/UEI.SmartControl( 6204):  ---- Has DB8: true
,D/UEI.SmartControl( 6204): QS start statue = true Error code = 0
D/UEI.SmartControl( 6204): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6204): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6204): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6204): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6204): IrrcClient ++ 
D/irrcClient( 6204): getIrrcService ++ 
,D/irrcClient( 6204): getIrrcService -- 
D/irrcClient( 6204): IrrcClient -- 
W/irrc_jni( 6204): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6204): Services init done
I/UEI.SmartControl( 6204): Device manager: loading config....
D/UEI.SmartControl( 6204): Config is loaded...
,D/UEI.SmartControl( 6204):  ----- QS SDK is ready!!!
,I/art     (  846): Explicit concurrent mark sweep GC freed 25745(1185KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.743ms total 168.187ms
I/UEI.SmartControl( 6204): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6204): QS Service init finished
I/Gmail   ( 6195): Observing account changes for notifications
,I/DownloadManager( 3144): in trimDatabase
V/DownloadManager( 3144): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3144): DownloadService onStartCommand
V/DownloadManager( 3144): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 6204): QS Service version name: 0.1.73
V/DownloadManager( 3144): created cursor android.database.sqlite.SQLiteCursor@21c5907f on behalf of 3144
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/UEI.SmartControl( 6204): QS Service version code: 1073
D/UEI.SmartControl( 6204): Service requested: Control
V/DownloadManager( 3144): created cursor android.database.sqlite.SQLiteCursor@28d53d9e on behalf of 3144
D/UEI.SmartControl( 6204): Service.onUnbind: IControl
I/CheckinService( 5900): Checkin interval check for package: unspecified last checkin: 1450837195376 min interval config: 0 actual interval: 1086249301
W/ResourcesManager( 6223): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6204): Service.onDestroy
W/ResourcesManager( 6223): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6204): Shutdown IRRCPlayer... 
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,I/art     ( 6223): CheckpointMarkThreadRoots callback created = 0xaaf29310
W/ContextImpl( 6223): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/irrc_jni( 6204): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6204): ~IrrcClient ++ 
D/irrcClient( 6204): ~IrrcClient -- 
W/irrc_jni( 6204): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6204): Blaster closed
,D/UEI.SmartControl( 6204): Blaster closed
D/UEI.SmartControl( 6204): Shut down QS...
D/UEI.SmartControl( 6204): Stopped file observer...
I/UEI.SmartControl( 6204): QS lib stop result = true
D/UEI.SmartControl( 6204): QS shutdown complete
D/UEI.SmartControl( 6204): QS Service created
,I/CheckinService( 5900): Disabling old GoogleServicesFramework version
E/UEI.SmartControl( 6204): QS start get config
,I/art     ( 6223): CheckpointMarkThreadRoots callback created = 0xaaf292f0
V/JNIHelp ( 6223): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/UEI.SmartControl( 6204):  configuring local db...
,D/DrmBroadcastReceiver( 6324): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6324): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6324): Service onCreate
D/WeatherAncestor( 2729): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:4:4
D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/DrmService( 6324): Received new request = 2
D/WeatherAncestor( 2729): connectivity changed - connection : true
D/libc-netbsd( 5938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DrmSntpClient( 6324): Start Sync process
D/DrmSntpClient( 6324): Server : 0
D/Weather_cast( 2729): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2729): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:4:4
D/WeatherService( 2729): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd( 6324): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6324): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6324): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6324): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  280): App 10051 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6361 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2729): 2 : Utils getTopActivity com.lge.launcher2 / true
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6324): propertyValue:false
W/System  ( 6223): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6223): Installed default security provider GmsCore_OpenSSL
,D/WeatherService( 2729): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/DownloadManager( 3144): DownloadService onDestroy
,I/LGDrmClient( 6324): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  292): eDRM_SetDRMTime +++
I/LGDRM   (  292): [DRM] SET TIME : YR=2016, MON=1, DAY=4
I/LGDRM   (  292): [DRM] SET TIME : HR=16, MIN=4, SEC=3
I/Gmail   ( 6195): notifyAccountChanged
,I/Gmail   ( 6195): getAccountsCursor
V/ILGDrmService(  292): eDRM_SetDRMTime ---
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DrmSntpClient( 6324): Synched
D/DrmService( 6324): Completed !! request = 2
D/DrmService( 6324): Request count = 0
I/CheckinService( 5900): Checking schedule, now: 1451923445002 next: 1450837225338
I/CheckinService( 5900): active receiver: enabled
V/DrmService( 6324): Service onDestroy
,I/Gmail   ( 6195): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/CheckinService( 5900): Preparing to send checkin request
I/EventLogService( 5900): Accumulating logs since 1451923401792
,I/Gmail   ( 6195): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6195): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6195): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/WifiServiceImplEx(  846): acquireWifiLock pid=6223, uid=10058, packageName=com.google.android.apps.docs, tag=BaseSyncManager
,I/Gmail   ( 6195): notifyAccountChanged
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6361): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationManager( 6223): com.google.android.apps.docs: cancel(1) by com.google.android.apps.docs
,I/Gmail   ( 6195): getAccountsCursor
,D/UEI.SmartControl( 6204):  ---- Has DB8: true
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 6204): QS start statue = true Error code = 0
D/UEI.SmartControl( 6204): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6204): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6204): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6204): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6204): IrrcClient ++ 
D/irrcClient( 6204): getIrrcService ++ 
,D/irrcClient( 6204): getIrrcService -- 
D/irrcClient( 6204): IrrcClient -- 
W/irrc_jni( 6204): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6204): Services init done
I/UEI.SmartControl( 6204): Device manager: loading config....
,D/UEI.SmartControl( 6204): QS Service init finished
D/UEI.SmartControl( 6204): QS Service version name: 0.1.73
D/UEI.SmartControl( 6204): QS Service version code: 1073
D/UEI.SmartControl( 6204): Service requested: Control
D/UEI.SmartControl( 6204): Config is loaded...
W/Flag    ( 6223): Duration spec must be at least 2 characters long
,D/UEI.SmartControl( 6204): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6204):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6204): Notify AllClients services are ready: 0
I/ActivityManager(  846): Killing 6019:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10013/pid_6019/cgroup.procs: No such file or directory
,E/ActivityThread( 6204): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@2ec26943 that was originally bound here
E/ActivityThread( 6204): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@2ec26943 that was originally bound here
E/ActivityThread( 6204): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6204): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6204): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6204): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6204): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6204): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6204): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6204): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6204): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6204): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6204): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6204): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6204): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6204): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6204): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6204): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6204): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6204): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6204): Internal service binding...
,I/ActivityManager(  846): Killing 5938:com.google.android.youtube/u0a100 (adj 15): empty #11
,I/Gmail   ( 6195): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13775, normalSync: true
I/chromium( 5480): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/libc-netbsd( 6223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10058
D/DnsProxyListener(  280): App 10058 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 6223): propertyValue:false
I/CheckinRequestBuilder( 5900): Checkin reason type: 8 attempt count: 1
W/ActivityManager(  846): Application dead when creating service ServiceRecord{1a6d4795 u0 com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator}
W/libprocessgroup(  846): failed to open /acct/uid_10100/pid_5938/cgroup.procs: No such file or directory
,W/ActivityManager(  846): Scheduling restart of crashed service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator in 1000ms
W/ActivityManager(  846): Scheduling restart of crashed service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator in 4000ms
W/ActivityManager(  846): Spurious death for ProcessRecord{1f4056d1 0:com.google.android.youtube/u0a100}, curProc for 5938: null
,E/ActivityThread( 5900): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 6195): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6195): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc-netbsd( 6223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  846): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6398 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 5900): Explicit concurrent mark sweep GC freed 17183(1467KB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 12MB/21MB, paused 1.465ms total 145.257ms
,W/art     ( 6195): Suspending all threads took: 5.683ms
,V/JNIHelp ( 6195): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/Babel_SMS( 6361): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6361): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6361): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6361): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6361): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6361): MmsConfig.loadFromResources
E/Babel_SMS( 6361): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6361): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/System  ( 6195): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6195): Installed default security provider GmsCore_OpenSSL
,D/SensorManager( 6361): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6361): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 6361): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6361): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6361): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6361): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6361): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6361): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6361): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6361): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6361): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6361): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6361): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6361): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6361): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6361): found sensor: Motion Accel, handle=46
W/ResourcesManager( 6398): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6398): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  846): Process com.google.android.music:main (pid 5858) has died
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  846): android: cancelAsUser(2) by android
,W/Settings( 6361): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6361): startup - clean
I/art     ( 6361): CheckpointMarkThreadRoots callback created = 0xb042d870
,V/JNIHelp ( 6398): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 6361): CheckpointMarkThreadRoots callback created = 0xb042d850
I/Babel   ( 6361): deleted: false for 0
,I/art     ( 5529): Explicit concurrent mark sweep GC freed 2863(115KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 4.562ms total 72.386ms
,W/System  ( 6398): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6398): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  846): Process com.android.gallery3d (pid 5918) has died
,D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10053
D/DnsProxyListener(  280): App 10053 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 6195): propertyValue:false
D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  846): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6436 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6361): Unsupported mime audio/x-lg-flac
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioCapabilities( 6361): Unsupported mime audio/adpcm
W/AudioCapabilities( 6361): Unsupported mime audio/g726
,W/AudioCapabilities( 6361): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6361): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6361): Unsupported mime video/mjpg
,I/art     ( 6195): CheckpointMarkThreadRoots callback created = 0xaaf06370
,W/VideoCapabilities( 6361): Unsupported mime video/theora
,I/art     ( 6195): CheckpointMarkThreadRoots callback created = 0xb051be40
,W/AudioCapabilities( 6361): Unsupported mime audio/evrc
,W/AudioCapabilities( 6361): Unsupported mime audio/qcelp
W/VideoCapabilities( 6361): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6361): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6361): Unsupported mime audio/qcelp
W/AudioCapabilities( 6361): Unsupported mime audio/evrc
,W/VideoCapabilities( 6361): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6361): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager(  846): Process com.qualcomm.timeservice (pid 6109) has died
W/VideoCapabilities( 6361): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6361): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6361): Unrecognized profile 2130706433 for video/avc
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
W/VideoCapabilities( 6361): Unrecognized profile 2130706433 for video/avc
,I/art     ( 6398): CheckpointMarkThreadRoots callback created = 0xb042dba0
I/vclib   ( 6361): onServiceConnected
W/Babel   ( 6361): Attempted to change video mute state without an active call.
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
,I/NotificationManager( 6361): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6361): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6361): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6361): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6361): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6361): propertyValue:false
,W/ResourcesManager( 6398): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6398): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 6398): CheckpointMarkThreadRoots callback created = 0xb4958de0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Babel   ( 6361): connection state changed from UNKNOWN to CONNECTED
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/art     ( 6398): Suspending all threads took: 11.203ms
,I/ActivityManager(  846): Process com.lge.email (pid 5872) has died
,D/UEI.SmartControl( 6204): Service.onTrimMemory: 80
E/UEI.SmartControl( 6204): Setup service releasing memory...
I/PhoneApp( 1753): onTrimMemory: 10
I/PhoneApp( 1753): trim memory
E/YouTube MDX( 6398): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/ChimeraCfgMgr( 5900): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5900): Module APK com.google.android.play.games already loaded
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/BackgroundMemoryTrimmer( 2026): Trimming objects from memory, since app is in the background.
D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/UEI.SmartControl( 6204): file observer is disposed!
,I/art     ( 6204): Explicit concurrent mark sweep GC freed 16002(1258KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 7MB/9MB, paused 452us total 73.453ms
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6398): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6436): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6436): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6436): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6436):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6436):   adb logcat -s GAv4
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6436): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/GAv4    ( 6436): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6436): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6436): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6436): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/dex2oat ( 6480): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-375626393.jar --oat-fd=34 --oat-location=/data/data/com.google.android.youtube/cache/ads-375626393.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/NotificationManager( 6195): com.google.android.gm: cancel(10436) by com.google.android.gm
I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,I/NotificationManager(  846): android: cancelAsUser(2) by android
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
I/dex2oat ( 6480): dex2oat took 149.948ms (threads: 4)
,D/libc-netbsd( 6223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10058
D/DnsProxyListener(  280): App 10058 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/art     (  846): Explicit concurrent mark sweep GC freed 18404(917KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.299ms total 172.108ms
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/ActivityManager(  846): Process com.lge.appbox.client (pid 6176) has died
I/System.out( 6223): propertyValue:false
,D/UEI.SmartControl( 6204): Service.onTrimMemory: 80
E/UEI.SmartControl( 6204): Setup service releasing memory...
I/BackgroundMemoryTrimmer( 2026): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1753): onTrimMemory: 10
I/PhoneApp( 1753): trim memory
,D/libc-netbsd( 6223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 6398): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6398): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6398): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6398): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
I/ActivityManager(  846): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6523 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
E/DefaultHttpIssuer( 6223): Attempt to consume entity of HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 6223): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 6223): java.io.IOException
E/DefaultHttpIssuer( 6223): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 6223): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 6223): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 6223): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 6223): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 6223): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 6223): 	at dlr.run(PG:3031)
,E/BaseSyncManager( 6223): IOException
E/BaseSyncManager( 6223): java.io.IOException: stream was reset: PROTOCOL_ERROR
E/BaseSyncManager( 6223): 	at hzd.b(PG:145)
E/BaseSyncManager( 6223): 	at hya.b(PG:104)
E/BaseSyncManager( 6223): 	at hxn.d(PG:917)
E/BaseSyncManager( 6223): 	at hxn.a(PG:95)
E/BaseSyncManager( 6223): 	at hxn$a.a(PG:902)
E/BaseSyncManager( 6223): 	at hvz.a(PG:50089)
E/BaseSyncManager( 6223): 	at hvz$a.a(PG:230)
E/BaseSyncManager( 6223): 	at hvz.a(PG:3201)
E/BaseSyncManager( 6223): 	at clz.a(PG:127)
E/BaseSyncManager( 6223): 	at cjr.a(PG:47)
E/BaseSyncManager( 6223): 	at cjq.a(PG:22)
E/BaseSyncManager( 6223): 	at cjs.a(PG:68)
E/BaseSyncManager( 6223): 	at cjw.b(PG:92)
E/BaseSyncManager( 6223): 	at cjw.a(PG:80)
E/BaseSyncManager( 6223): 	at cju.b(PG:5140)
E/BaseSyncManager( 6223): 	at cju.a(PG:1096)
E/BaseSyncManager( 6223): 	at dlh.b(PG:14062)
E/BaseSyncManager( 6223): 	at dlh.a(PG:140)
E/BaseSyncManager( 6223): 	at dqo.a(PG:224)
E/BaseSyncManager( 6223): 	at dlt.run(PG:9618)
E/BaseSyncManager( 6223): 	at dlr.run(PG:3031)
,W/InstanceID/Rpc( 6398): Found 10006
D/WifiServiceImplEx(  846): releaseWifiLock pid=6223, uid=10058, packageName=com.google.android.apps.docs
,I/NotificationManager(  846): android: cancelAsUser(-1488629395) by android
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6398): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,W/ResourcesManager( 6523): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6523): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6523): VM with version 2.1.0 has multidex support
I/MultiDex( 6523): install
I/MultiDex( 6523): VM has multidex support, MultiDex support library is disabled.
,I/WebViewFactory( 6436): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/NotificationManager( 6223): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/LibraryLoader( 6436): Time to load native libraries: 4 ms (timestamps 3600-3604)
,I/ActivityManager(  846): Process com.google.android.setupwizard (pid 6272) has died
I/LibraryLoader( 6436): Expected native library version number "",actual native library version number ""
D/UEI.SmartControl( 6204): Service.onTrimMemory: 60
E/UEI.SmartControl( 6204): Setup service releasing memory...
I/BackgroundMemoryTrimmer( 2026): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1753): onTrimMemory: 10
,I/PhoneApp( 1753): trim memory
V/WebViewChromiumFactoryProvider( 6436): Binding Chromium to main looper Looper (main, tid 1) {236e2081}
I/LibraryLoader( 6436): Expected native library version number "",actual native library version number ""
,I/chromium( 6436): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/NotificationManager(  846): android: cancelAsUser(353845882) by android
V/JNIHelp ( 6523): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/BrowserStartupController( 6436): Initializing chromium process, singleProcess=true
W/art     ( 6436): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6436): ApplicationContext is null in ApplicationStatus
,I/NotificationManager( 6398): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  280): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6398): propertyValue:false
D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ActivityThread( 6523): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6523): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1987d111: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6523): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6523): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6523): com.google.android.gms: cancel(39789) by com.google.android.gms
W/chromium( 6436): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6436): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6436): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6436): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6436): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6436): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6436): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6436): Remote Branch: 
I/Adreno-EGL( 6436): Local Patches: 
I/Adreno-EGL( 6436): Reconstruct Branch: 
D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 6523): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6523): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
V/AudioPolicyService(  285): registerClient() client 0xb551cd40, uid 10079
,W/AudioManagerAndroid( 6436): Requires BLUETOOTH permission
,I/art     ( 6195): Explicit concurrent mark sweep GC freed 11555(404KB) AllocSpace objects, 1(39KB) LOS objects, 25% free, 10MB/14MB, paused 636us total 102.706ms
,I/NSApplication( 6436): Starting up...
,D/WVCdm   (  285): Instantiating CDM.
,I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Dec 11 2014 16:13:16
I/ActivityManager(  846): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6597 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 6523): Install completed successfully. count=14 extracted=0
I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 23.751ms
,W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  285): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  285): L1 library not specified. Falling Back to L3
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 22.442ms
I/Gmail   ( 6195): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13921, normalSync: true
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 21.418ms
I/Gmail   ( 6195): lowestBackward conversation id 0
I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
D/WVCdm   (  285): PrepareKeyRequest: nonce=3754423396
I/ActivityManager(  846): Process com.uei.lg.quicksetsdk.lite (pid 6204) has died
,I/SyncAdapterService( 6436): Ignoring sync request for non-current account
,I/GoogleURLConnFactory( 6523): Using platform SSLCertificateSocketFactory
,I/NotificationManager(  846): android: cancelAsUser(-701419433) by android
,D/libc-netbsd( 6523): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6523): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6523): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6523): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6523): propertyValue:false
I/Icing   ( 5900): Storage manager: low false usage 1.69MB avail 2.36GB capacity 4.06GB
,D/libc-netbsd( 6523): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6523): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6523): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6523): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  846): Process com.lge.lgdmsclient (pid 6149) has died
,I/GAv4-SVC( 5900): Google Analytics 8.4.89 is starting up.
I/GAV2    ( 6195): Thread[GAThread,5,main]: No campaign data found.
,D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  280): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6398): propertyValue:false
D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  846): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6640 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 6523): CheckpointMarkThreadRoots callback created = 0xb042dba0
,I/art     ( 6523): CheckpointMarkThreadRoots callback created = 0xb042db90
,I/PeopleSync( 5900): onPerformSync() [5005f081]
,W/ResourcesManager( 6640): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  846): Process com.google.android.talk (pid 6361) has died
,I/BackgroundMemoryTrimmer( 2026): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1753): onTrimMemory: 10
I/PhoneApp( 1753): trim memory
I/PeopleDatabaseHelper( 5900): cleanUpNonGplusAccounts done.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5900): updateResources: need to parse f{com.google.android.gms}
,I/dex2oat ( 6664): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/InstanceID/Rpc( 5900): Found 10006
,I/dex2oat ( 6664): dex2oat took 164.919ms (threads: 4)
I/Adreno-EGL( 6523): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6523): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6523): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6523): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6523): Remote Branch: 
I/Adreno-EGL( 6523): Local Patches: 
I/Adreno-EGL( 6523): Reconstruct Branch: 
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/PeopleSync( 5900): Setting subscription: result=true [5005f081]
I/PeopleSync( 5900): Starting sync, feed=null [5005f081]
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,I/CheckinService( 5900): Checkin interval check for package: unspecified last checkin: 1450837195376 min interval config: 0 actual interval: 1086254820
,I/dex2oat ( 6676): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads-375626393.jar --oat-fd=93 --oat-location=/data/data/com.google.android.gms/cache/ads-375626393.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 116053512929; DSPS: 3901783; Offset : -3022522464
I/Icing   ( 5900): Internal init done: storage state 0
,W/BaseAppContext( 5900): Using Auth Proxy for data requests.
,I/NotificationManager( 6195): com.google.android.gm: cancel(10436) by com.google.android.gm
I/NotificationManager( 6195): com.google.android.gm: cancel(10436) by com.google.android.gm
I/art     ( 5529): Explicit concurrent mark sweep GC freed 3039(120KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 544us total 26.925ms
,I/Icing   ( 5900): Post-init done
I/dex2oat ( 6676): dex2oat took 141.250ms (threads: 4)
E/BaseAppContext( 5900): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5900): Using Auth Proxy for data requests.
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 68542(4MB) AllocSpace objects, 39(647KB) LOS objects, 40% free, 13MB/23MB, paused 2.555ms total 137.902ms
I/Adreno-EGL( 6523): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6523): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6523): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6523): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6523): Remote Branch: 
I/Adreno-EGL( 6523): Local Patches: 
I/Adreno-EGL( 6523): Reconstruct Branch: 
,W/BaseAppContext( 5900): Using Auth Proxy for data requests.
,I/WVCdm   (  285): CdmEngine::CloseSession
I/WVCdm   (  285): L3 Terminate.
,I/PeopleSync( 5900): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
I/iu.SyncManager( 5900): SYNC; picasa accounts
,I/Adreno-EGL( 6523): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6523): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6523): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6523): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6523): Remote Branch: 
I/Adreno-EGL( 6523): Local Patches: 
I/Adreno-EGL( 6523): Reconstruct Branch: 
I/Gmail   ( 6195): notifyAccountChanged
I/Gmail   ( 6195): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6195): notifyAccountChanged
W/Gmail   ( 6195): Sync complete for account: account:61035162
,I/NotificationManager(  846): android: cancelAsUser(1479798955) by android
I/Gmail   ( 6195): getAccountsCursor
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkLogImpl( 5900): Loaded NetworkSpeedPredictor
I/iu.Environment( 5900): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 5900): num queued entries: 0
I/iu.UploadsManager( 5900): num updated entries: 0
I/iu.SyncManager( 5900): NEXT; no task
,I/MusicWidget( 2640): mDelayedStopHandler : unbind
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
I/MusicBrowser( 2735): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2735): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2735): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2735): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2735): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2735): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2735): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2735): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
I/art     ( 5900): Explicit concurrent mark sweep GC freed 42777(3MB) AllocSpace objects, 43(688KB) LOS objects, 25% free, 13MB/17MB, paused 2.827ms total 142.162ms
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/GCM     ( 1734): GCM config loaded
,I/art     (  846): Explicit concurrent mark sweep GC freed 33812(1565KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/34MB, paused 2.640ms total 201.787ms
I/MediaFocusControl(  846):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1513346dcom.lge.music.MediaPlaybackService$6@c74b8a2
,D/WearableService( 1734): callingUid 10006, callindPid: 1734
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/MusicBrowser( 2735): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2735): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2735): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2735): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationInitializer( 5900): Restart initialization of location
,I/MusicBrowser( 2735): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@11ab6bc0
I/MusicBrowser( 2735): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/MusicBrowser( 2735): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2735): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2735): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2735): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2735): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2735): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2735): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2735): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2735): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
E/MDM     ( 1734): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/MusicBrowser( 2735): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2735): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2735): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2735): reset
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/NotificationManager(  846): android: cancelAsUser(2) by android
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Dec 11 2014 16:13:16
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,V/MediaPlayer[Native]( 2735): setListener
V/MediaPlayer[Native]( 2735): disconnect
V/MediaPlayer[Native]( 2735): destructor
V/AudioFlinger(  285): releasing 19 from 2735 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/MediaPlayer[Native]( 2735): disconnect
,W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  285): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  285): L1 library not specified. Falling Back to L3
D/MusicBrowser( 2735): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/ActivityManager(  846): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6726 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/SmartShareClient( 2735): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2735): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2735): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2735): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2735): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2735): [SmartShareManagerClient] unregisterListener: 222308659
W/SmartShareClient( 2735): [SmartShareManagerClient] unregisterListener invalid listener: 222308659
I/SmartShareClient( 2735): [SmartShareManagerClient] terminate service: 2735/MediaPlaybackService/772788838
,E/HomeCloudIF( 2735): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2735): [SmartShareManagerClient] unbindService context:android.app.Application@15144f0
I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
V/CloudHub( 2735): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2735): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
D/WVCdm   (  285): PrepareKeyRequest: nonce=1769518341
I/CloudHub( 2735): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/NotificationManager(  846): android: cancelAsUser(2) by android
I/MusicBrowser( 2735): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2735): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
I/CloudHub( 2735): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29974
W/IcingInternalCorpora( 5900): getNumBytesRead when not calculated.
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  846): Process com.google.android.apps.docs (pid 6223) has died
,I/DigitalAppWidgetProvider( 6726): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 2729): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 17:4:11
D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/Weather_cast( 2729): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2729): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 17:4:11
D/WeatherService( 2729): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/Weather.Utils( 2729): 2 : Utils getTopActivity com.lge.launcher2 / true
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
D/WeatherService( 2729): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/System.out( 5900): propertyValue:false
,I/NotificationManager(  846): android: cancelAsUser(-1878923137) by android
W/BaseAppContext( 5900): Using Auth Proxy for data requests.
,W/BaseAppContext( 5900): Using Auth Proxy for data requests.
I/VacuumService( 1734): Vacuum at: now=1451923451542 tag=VacuumService
W/BaseAppContext( 5900): Using Auth Proxy for data requests.
W/BaseAppContext( 5900): Using Auth Proxy for data requests.
D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/BaseAppContext( 5900): Using Auth Proxy for data requests.
W/BaseAppContext( 5900): Using Auth Proxy for data requests.
,W/BaseAppContext( 5900): Using Auth Proxy for data requests.
,D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  846): android: cancelAsUser(-379682945) by android
,E/MDM     ( 1734): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/ContextImpl( 3394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  846): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6757 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocationInitializer( 5900): Restart initialization of location
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,I/Icing   ( 5900): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
I/MusicStore( 6757): Database version: 120
,I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6789 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  846): Process com.google.android.apps.magazines (pid 6436) has died
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6757): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/Icing   ( 5900): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
W/ResourcesManager( 6789): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6757): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6757): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6757): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,V/JNIHelp ( 6757): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 6757): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6757): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@fcd61b0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6757): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6757): GMSCore installation verified
,I/ConfigStore( 6757): Config Database version: 1
,I/MediaRouter( 6757): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/art     ( 5529): Explicit concurrent mark sweep GC freed 2622(103KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.632ms total 48.707ms
,E/Volley  ( 5900): [757] BasicNetwork.performRequest: Unexpected response code 410 for https://www.googleapis.com/plus/v2whitelisted/people/me/people/all?prettyPrint=false&fields=items(etag,id,names,nicknames,images,urls,sortKeys,taglines,emails,phoneNumbers,addresses,metadata,memberships,legacyFields/mobileOwnerId),nextPageToken,nextSyncToken&customResponseMaskingType=menagerie&includeAffinity=gplusAutocomplete&includeAffinity=chatAutocomplete&includeAffinity=emailAutocomplete&includeOthers=true&maxResults=100&orderBy=modified&syncToken=COnR86CeKhIBMRjeEioECAEQAQ
,I/PeopleSync( 5900): Sync Token out of date, syncing all people/gaia-map
I/ActivityManager(  846): Process com.lge.drmservice (pid 6324) has died
,I/GHttpClientFactory( 6757): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6757): Using platform SSLCertificateSocketFactory
,I/NetworkMonitor( 6757): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/MusicLifecycle( 6757): Sync started
,I/Babel_SMS( 6789): MmsConfig: mnc/mcc: 0/0
,D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Babel_SMS( 6789): MmsConfig.loadMmsSettings
,I/art     ( 6789): CheckpointMarkThreadRoots callback created = 0xb042d550
,I/WVCdm   (  285): CdmEngine::CloseSession
,I/art     (  846): Explicit concurrent mark sweep GC freed 27021(1270KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.519ms total 168.661ms
I/WVCdm   (  285): L3 Terminate.
I/NetworkMonitor( 6757): type=WIFI subType= reason=null isConnected=true
I/Babel_SMS( 6789): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6789): MmsConfig.loadFromDatabase
,I/GHttpClientFactory( 6757): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     ( 6789): CheckpointMarkThreadRoots callback created = 0xb042d520
E/Babel_SMS( 6789): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6789): MmsConfig.loadFromResources
E/Babel_SMS( 6789): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6789): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6789): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6789): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6789): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6789): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6789): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6789): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6789): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6789): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6789): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6789): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6789): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6789): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6789): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6789): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6789): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6789): found sensor: Motion Accel, handle=46
,I/ActivityManager(  846): Process com.google.android.apps.plus (pid 6640) has died
,I/PhoneApp( 1753): onTrimMemory: 10
I/PhoneApp( 1753): trim memory
I/BackgroundMemoryTrimmer( 2026): Trimming objects from memory, since app is in the background.
I/GoogleURLConnFactory( 6757): Using platform SSLCertificateSocketFactory
I/art     ( 6757): CheckpointMarkThreadRoots callback created = 0xb042d470
,W/Settings( 6789): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6789): startup - clean
I/NotificationManager( 6757): com.google.android.music: cancel(1061) by com.google.android.music
,I/Babel   ( 6789): deleted: false for 0
I/art     ( 6757): CheckpointMarkThreadRoots callback created = 0xb042d440
,I/PeopleSync( 5900): Sync finished, successful=true, took 3088ms
,I/PeopleContactsSync( 5900): CP2 sync start [5005f081]
,I/PeopleContactsSync( 5900): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
I/PeopleContactsSync( 5900): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
I/NotificationManager(  846): android: cancelAsUser(2) by android
D/libc-netbsd( 6757): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6757): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6757): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6757): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10081
D/DnsProxyListener(  280): App 10081 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
W/AudioCapabilities( 6789): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6789): Unsupported mime audio/adpcm
W/AudioCapabilities( 6789): Unsupported mime audio/g726
,W/AudioCapabilities( 6789): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6789): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6789): Unsupported mime video/mjpg
W/VideoCapabilities( 6789): Unsupported mime video/theora
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 6757): propertyValue:false
W/AudioCapabilities( 6789): Unsupported mime audio/evrc
,W/AudioCapabilities( 6789): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6789): Unrecognized profile 2130706433 for video/avc
I/art     ( 5900): Explicit concurrent mark sweep GC freed 24786(1587KB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 14MB/23MB, paused 1.980ms total 121.377ms
W/AudioCapabilities( 6789): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6789): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6789): Unsupported mime audio/evrc
,W/SQLiteConnectionPool( 5900): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/VideoCapabilities( 6789): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6789): Unsupported profile 4 for video/mp4v-es
,D/libc-netbsd( 6757): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6757): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/PeopleContactsSync( 5900): CP2 cleanup done, kept= duration=188 ms
I/PeopleContactsSync( 5900): ===CP2 sync finished, success=true, time=218,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
W/VideoCapabilities( 6789): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6789): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6789): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6789): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6789): onServiceConnected
,W/Babel   ( 6789): Attempted to change video mute state without an active call.
I/PeopleSync( 5900): ***Sync finished***, duration: 4570 [5005f081]
I/NotificationManager( 6789): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/ChimeraCfgMgr( 5900): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5900): Module APK com.google.android.play.games already loaded
,I/NotificationManager(  846): android: cancelAsUser(148851818) by android
D/libc-netbsd( 6757): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6757): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  846): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6838 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/PlaySystemBroadcastReceiver( 5900): Processed handlePeopleChanged at 119758
,W/ResourcesManager( 6838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 5900): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5900): Module APK com.google.android.play.games already loaded
,I/MusicSyncAdapter( 6757): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 6757): Periodic update
,W/BaseAppContext( 5900): Using Auth Proxy for data requests.
W/BaseAppContext( 5900): Using Auth Proxy for data requests.
W/BaseAppContext( 5900): Using Auth Proxy for data requests.
,W/MusicApiClient( 6757): Activity events list is null or empty. Skip reporting.
I/ActivityManager(  846): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=6860 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicLifecycle( 6757): Sync ended
W/BaseAppContext( 5900): Using Auth Proxy for data requests.
,W/BaseAppContext( 5900): Using Auth Proxy for data requests.
W/BaseAppContext( 5900): Using Auth Proxy for data requests.
I/NotificationManager(  846): android: cancelAsUser(-1123058983) by android
,W/BaseAppContext( 5900): Using Auth Proxy for data requests.
,E/Auth.Api.Credentials( 5900): [CredentialSyncAdapter] Unknown sync event.
,I/NotificationManager(  846): android: cancelAsUser(-591465577) by android
I/CheckinRequestBuilder( 5900): Classify the device as Phone.
,D/Finsky  ( 6860): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/NotificationManager(  846): android: cancelAsUser(-1874035846) by android
,I/GoogleURLConnFactory( 5900): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DataBroker( 5900): No player ID found and calling context is not the dest app
I/NotificationManager(  846): android: cancelAsUser(2) by android
,D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 5900): propertyValue:false
,D/Finsky  ( 6860): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 5900): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,W/Settings( 6860): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6860): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager(  846): android: cancelAsUser(2) by android
I/NotificationManager( 6860): com.android.vending: cancel(-1050172287) by com.android.vending
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Finsky  ( 6860): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,D/Finsky  ( 6860): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6860): Skipping gmscore version check
V/DownloadManager( 3144): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
I/System.out( 6860): propertyValue:false
,I/CheckinTask( 5900): Sending checkin request (10835 bytes)
V/DownloadManager( 3144): created cursor android.database.sqlite.SQLiteCursor@352ec095 on behalf of 6860
D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/MusicLeanback( 6757): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6757): Stop autocaching.
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6757): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6757): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
D/Finsky  ( 6860): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6860): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/art     (  846): Explicit concurrent mark sweep GC freed 26554(1185KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.306ms total 170.025ms
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6757): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
,I/art     ( 5529): Explicit concurrent mark sweep GC freed 3227(130KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.704ms total 28.227ms
W/art     ( 6838): Attempt to remove local handle scope entry from IRT, ignoring
,D/libc-netbsd( 6838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,E/BandwidthController(  280): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  280): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
E/GmsUtils( 6757): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6757): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/CheckinRequestBuilder( 5900): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5900): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5900): Classify the device as Phone.
,I/CheckinTask( 5900): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5900): Checking schedule, now: 1451923455655 next: 1452450704651
I/CheckinService( 5900): active receiver: disabled
,I/CheckinService( 5900): Checking schedule, now: 1451923455690 next: 1452450704651
I/CheckinService( 5900): active receiver: disabled
D/CheckinService( 5900): Recording last checkin time for package unspecified as 1451923455699
,I/ActivityManager(  846): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6952 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6952): Register our PhoneStateListener
,V/SetupWizard( 6952): Connected to Gservices successfully
,D/PhoneMonitor( 6952): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6952): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6952): [parse] Load xml
D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/TelephonyAutoProfiling( 6952): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6952): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6952): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/Finsky  ( 6860): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{37ff721 type 0 when 1451923455992 com.android.vending} when 1451923455992
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  846): android: cancelAsUser(2) by android
D/libc-netbsd( 6860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6860): propertyValue:false
D/libc-netbsd( 6860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  846): android: cancelAsUser(2126026182) by android
,D/libc-netbsd( 6860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  846): android: cancelAsUser(1500439826) by android
,I/NotificationManager( 6838): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,I/ActivityManager(  846): Start proc com.lge.qmemoplus for service com.lge.qmemoplus/.network.googledrive.DriveSyncService: pid=6984 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/NotificationManager(  846): android: cancelAsUser(2145784878) by android
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,W/ResourcesManager( 6984): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/charger_monitor(  482): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/WifiController(  846): battery changed pluggedType: 2
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
D/WifiController(  846): battery changed pluggedType: 2
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
V/AudioFlinger(  285): 2735 died, releasing its sessions
V/AudioFlinger(  285):  pid 1753 @ 0
V/AudioFlinger(  285):  pid 3122 @ 1
V/AudioFlinger(  285):  pid 3122 @ 2
D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10100
,D/DnsProxyListener(  280): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  846): Process com.lge.music (pid 2735) has died
,I/qtaguid ( 6860): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6860): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 6860): untagSocket(44) failed with errno -22
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6398): propertyValue:false
D/Finsky  ( 6860): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/App     ( 6984): [App][onCreate()] 4.40.23
,D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  846): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7016 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/RemindersSync( 5900): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=803:priority=5:group=main]
,I/NotificationManager(  846): android: cancelAsUser(898701380) by android
,W/ResourcesManager( 7016): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7016): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7016): VM with version 2.1.0 has multidex support
I/MultiDex( 7016): install
I/MultiDex( 7016): VM has multidex support, MultiDex support library is disabled.
,I/qtaguid ( 6860): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6860): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 6860): untagSocket(44) failed with errno -22
,D/AccountManager( 6984): setSyncFrequency
,V/JNIHelp ( 7016): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/GCoreUlr( 1734): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1734): Using Auth Proxy for data requests.
,D/DriveSyncService( 6984): onCreate
D/DriveSyncService( 6984): onBind
D/DriveSyncAdapter( 6984): onPerformSync() START
,D/DriveSyncAdapter( 6984): Not added account. Stop
I/ActivityManager(  846): Killing 6597:com.android.chrome/u0a48 (adj 15): empty #11
,I/NotificationManager(  846): android: cancelAsUser(1312559638) by android
W/ActivityThread( 7016): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7016): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1987d111: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7016): Installed default security provider GmsCore_OpenSSL
E/BaseAppContext( 1734): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/NotificationManager( 7016): com.google.android.gms: cancel(10436) by com.google.android.gms
W/libprocessgroup(  846): failed to open /acct/uid_10048/pid_6597/cgroup.procs: No such file or directory
I/NotificationManager( 7016): com.google.android.gms: cancel(39789) by com.google.android.gms
,D/ChimeraCfgMgr( 7016): Reading stored module config
,E/MDM     ( 1734): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5900): Restart initialization of location
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ChimeraCfgMgr( 7016): Loading module com.google.android.gms.car from APK com.google.android.gms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
I/art     ( 6860): CheckpointMarkThreadRoots callback created = 0xb042d300
,I/art     ( 6860): CheckpointMarkThreadRoots callback created = 0xb042d260
,D/CAR.SERVICE( 7016): Connecting to CarCallService...
,D/NativeLibraryUtils( 7016): Install completed successfully. count=14 extracted=0
,I/art     ( 7016): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7016): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 7016): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 7016): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 7016): Creating a new PhoneAdapter instance
W/ActivityManager(  846): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7016): setListener: com.google.android.gms.car.dn@32bcdf14
W/ActivityManager(  846): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7016): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 7016): Starting CarCallService with initial phone null
I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/NotificationManager( 7016): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,D/CAR.SERVICE( 7016): Package validated; name: com.android.vending
,I/NotificationManager( 6860): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6860): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/MusicLeanback( 6757): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6757): Stop autocaching.
,E/GmsUtils( 6757): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6757): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/GCoreUlr( 1734): GCM ID uploaded for account#2#
,I/GCoreUlr( 1734): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1734): DispatchingService.onCreate()
,I/NotificationManager(  846): android: cancelAsUser(1222422273) by android
,I/qtaguid ( 6860): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6860): Untagging socket 44 failed errno=-22
,W/NetworkManagementSocketTagger( 6860): untagSocket(44) failed with errno -22
I/GCoreUlr( 1734): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1734): Unbound from all location providers
I/GCoreUlr( 1734): Place inference reporting - stopped
I/GCoreUlr( 1734): DispatchingService.onDestroy()
,I/GCoreUlr( 1734): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1734): Unbound from all location providers
I/GCoreUlr( 1734): Place inference reporting - stopped
D/Finsky  ( 6860): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.googlequicksearchbox to true
,D/Finsky  ( 6860): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.googlequicksearchbox from  to d_AAAAAAADF8w=
,W/ResourcesManager( 6860): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6860): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6860): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{1423f0af type 0 when 1451923458431 com.android.vending} when 1451923458431
,D/DeviceConnectionService( 1734): client connected with version: 8296000
,D/Finsky  ( 6860): [830] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6860): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  846): android: cancelAsUser(2) by android
D/Finsky  ( 6860): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,D/Finsky  ( 6860): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6860): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/art     (  846): Explicit concurrent mark sweep GC freed 25919(1181KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.313ms total 166.175ms
,I/ActivityManager(  846): Killing 6726:com.lge.clock/u0a10 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10010/pid_6726/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Killing 6398:com.google.android.youtube/u0a100 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10100/pid_6398/cgroup.procs: No such file or directory
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/charger_monitor(  482): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1833): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  846): Killing 6789:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10061/pid_6789/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 7016): mConnectedToCar = false, abort
,E/ActivityThread( 7016): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3ab37c7c that was originally bound here
E/ActivityThread( 7016): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3ab37c7c that was originally bound here
E/ActivityThread( 7016): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 7016): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 7016): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 7016): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 7016): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7016): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7016): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7016): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 7016): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 7016): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 7016): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 7016): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 7016): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 7016): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 7016): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 7016): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 7016): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7016): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7016): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 7016): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7016): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7016): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 7016): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 7016): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2f370567 that was originally bound here
E/ActivityThread( 7016): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2f370567 that was originally bound here
E/ActivityThread( 7016): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 7016): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 7016): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 7016): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 7016): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7016): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 7016): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 7016): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 7016): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 7016): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 7016): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 7016): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 7016): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 7016): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 7016): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 7016): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7016): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7016): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 7016): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7016): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7016): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 7016): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  846): Unbind failed: could not find connection for android.os.BinderProxy@178d95f9
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
I/QCNEJ   ( 1886): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:04:23.077 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/CheckinService( 5900): Done disabling old GoogleServicesFramework version
,I/QCNEJ   ( 1886): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7101 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1949): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1949): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1949): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1949): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  846): Handling package changes for user 0
,W/ResourcesManager( 7101): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/QCNEJ   ( 1886): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:04:26.088 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/NotificationService(  846): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  846): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  846): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  846): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  846): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@19d5620a
I/Babel_SMS( 7101): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7101): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7101): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7101): MmsConfig.loadFromDatabase
D/LCardEmulationManager( 1806): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1806): getDefaultRoute
,W/ResourcesManager(  846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Babel_SMS( 7101): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7101): MmsConfig.loadFromResources
E/Babel_SMS( 7101): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7101): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  846): Process com.google.android.gm (pid 6195) has died
,D/SensorManager( 7101): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7101): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7101): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7101): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 7101): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7101): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7101): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7101): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7101): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7101): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7101): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7101): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7101): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7101): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7101): found sensor: LGE Relative Motion Detector Sensor, handle=34
,D/SensorManager( 7101): found sensor: Motion Accel, handle=46
I/art     ( 7101): CheckpointMarkThreadRoots callback created = 0xaaf61630
W/Settings( 7101): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ResourceType(  846): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/art     ( 7101): CheckpointMarkThreadRoots callback created = 0xaaf61610
I/Babel_Crash( 7101): startup - clean
I/Babel   ( 7101): deleted: false for 0
,I/[LGHome]EVENT( 1949): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/AudioCapabilities( 7101): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7101): Unsupported mime audio/adpcm
W/AudioCapabilities( 7101): Unsupported mime audio/g726
W/AudioCapabilities( 7101): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7101): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7101): Unsupported mime video/mjpg
W/VideoCapabilities( 7101): Unsupported mime video/theora
W/AudioCapabilities( 7101): Unsupported mime audio/evrc
,I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7148 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/AudioCapabilities( 7101): Unsupported mime audio/qcelp
,D/LocationProviderProxy(  846): applying state to connected service
I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 29.266ms
W/VideoCapabilities( 7101): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7101): Unsupported mime audio/amr-wb-plus
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 281us total 26.987ms
W/AudioCapabilities( 7101): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7101): Unsupported mime audio/evrc
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 21.824ms
W/VideoCapabilities( 7101): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7101): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7101): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7101): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7101): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7101): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 7148): onCreate
,W/AppUp4:DB( 7148):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7148):  setFingerPrint start
I/AppUp4:DB( 7148):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7148):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7148):  SDK version = 0
I/AppUp4:DB( 7148):  beforefinger == newfinger no write in DB
I/ActivityManager(  846): Process com.google.android.apps.plus (pid 6838) has died
,D/AppUp4:AppBoxApplication( 7148): AppBoxApplication onCreate()
I/vclib   ( 7101): onServiceConnected
W/Babel   ( 7101): Attempted to change video mute state without an active call.
I/NotificationManager( 7101): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 7148): onReceive
I/AppUp4:CustModeStarterReceiver( 7148): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7148): Context : android.app.ReceiverRestrictedContext@e8f4ac1
D/AppUp4:CustFacade( 7148): isCustomizationCompleted : false
W/ResourcesManager( 7101): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7101): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AppUp4:CustFacade( 7148): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7148): begin check event
I/AppUp4:CustModeStarterReceiver( 7148): Event For Nothing, skip.
V/JNIHelp ( 7101): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  846): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7173 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/System  ( 7101): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7101): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager( 7173): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7173): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7173): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/NotificationManager( 7101): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 7173): Total System Memory = 906309632
,I/GalleryUtils( 7173): Application Heap = 96 MB
I/AppConfig( 7173): App Tier : NOT_DEF
,D/SystemHelper( 7173): region [EU], country [EU], operator [OPEN], sub-operator []
I/art     ( 1734): Explicit concurrent mark sweep GC freed 71446(4MB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 14MB/23MB, paused 1.528ms total 127.175ms
I/NotificationManager( 7101): com.google.android.talk: cancel(10436) by com.google.android.talk
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  846): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7200 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
W/ResourcesManager( 7200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7200): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7200): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7200): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7200): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/SystemConfig( 7200): BUILD Country: EU
I/SystemConfig( 7200): BUILD Operator: OPEN
,I/ActivityManager(  846): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7225 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 6952:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,W/libprocessgroup(  846): failed to open /acct/uid_10038/pid_6952/cgroup.procs: No such file or directory
I/SystemConfig( 7200): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7200): existFile = false
I/SystemConfig( 7200): canReadFile = false
I/SystemConfig( 7200): systemFeature RCS result false
,D/SystemConfig( 7200): refreshRcsSupport() :false
I/LockScreenSettings( 7225): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,W/art     ( 7101): Attempt to remove local handle scope entry from IRT, ignoring
D/LockScreenSettings( 7225): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7225): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7225): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7225): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7225): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/libc-netbsd( 7101): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7101): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/ActivityManager(  846): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7260 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  846): Killing 6984:com.lge.qmemoplus/1000 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_6984/cgroup.procs: No such file or directory
,W/ResourcesManager( 7260): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/PhenotypeConfigurator( 1734): Scheduling Phenotype for one-off execution 11631 seconds from now (1451923468307)
,D/GetConfigurationSnapshotOperation( 1734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
,I/art     ( 3144): Explicit concurrent mark sweep GC freed 5682(384KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 406us total 89.838ms
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
I/UpdateIcingCorporaServi( 2026): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  846): Killing 6757:com.google.android.music:main/u0a81 (adj 15): empty #11
I/ActivityManager(  846): Process com.android.vending (pid 6860) has died
,W/libprocessgroup(  846): failed to open /acct/uid_10081/pid_6757/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 2026): UpdateCorporaTask done [took 76 ms] updated apps [took 76 ms] 
,I/ActivityManager(  846): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7296 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 7101): Note: end time exceeds epoch: 
,I/Babel   ( 7101): Account registration complete:1-Redacted-21
,I/Babel   ( 7101): ProcessRegisterDeviceResponse
,I/Babel   ( 7101): Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{11dd587a type 2 when 134628 com.google.android.talk} when 134628
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{90f4e21 type 2 when 134696 android} when 134696
,D/Finsky  ( 7296): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7296): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7296): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7296): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7296): com.android.vending: cancel(-1050172287) by com.android.vending
I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,V/DownloadManager( 3144): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3144): created cursor android.database.sqlite.SQLiteCursor@2bd395aa on behalf of 7296
D/Ads     ( 7296): Skipping gmscore version check
D/Finsky  ( 7296): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7296): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7296): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 5900): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 7296): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/PackageBroadcastService( 5900): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5900): updateResources: need to parse f{com.google.android.gms}
,E/Babel   ( 7101): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
E/Babel   ( 7101): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     (  846): Explicit concurrent mark sweep GC freed 35588(1688KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.217ms total 185.398ms
,I/art     ( 7101): Note: end time exceeds epoch: 
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 136054425161; DSPS: 4557173; Offset : -3022526827
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/Icing   ( 5900): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 5900): Loaded CLD2 Version V2.0 - 20141016
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
I/Icing   ( 5900): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{321cf80b type 0 when 1451923472845 com.android.vending} when 1451923472845
,D/Finsky  ( 7296): [870] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7296): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  846): Killing 7016:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10006/pid_7016/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
D/WifiController(  846): battery changed pluggedType: 2
,D/charger_monitor(  482): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/QCNEJ   ( 1886): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:04:38.161 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1886): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:04:41.188 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  846): ALS enabled for SRE
D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29463 ms ago)
,D/qdlights(  846): set_light_backlight: 252
,D/qdlights(  846): set_light_backlight: 249
D/qdlights(  846): set_light_backlight: 246
,D/qdlights(  846): set_light_backlight: 242
,D/qdlights(  846): set_light_backlight: 239
,D/qdlights(  846): set_light_backlight: 235
,D/qdlights(  846): set_light_backlight: 232
,D/qdlights(  846): set_light_backlight: 229
,D/qdlights(  846): set_light_backlight: 225
,D/qdlights(  846): set_light_backlight: 222
,D/qdlights(  846): set_light_backlight: 219
,D/qdlights(  846): set_light_backlight: 215
,D/qdlights(  846): set_light_backlight: 212
,D/qdlights(  846): set_light_backlight: 209
,D/qdlights(  846): set_light_backlight: 205
,D/qdlights(  846): set_light_backlight: 202
,D/qdlights(  846): set_light_backlight: 199
,D/qdlights(  846): set_light_backlight: 195
,D/qdlights(  846): set_light_backlight: 192
,D/qdlights(  846): set_light_backlight: 189
,D/qdlights(  846): set_light_backlight: 185
,D/qdlights(  846): set_light_backlight: 182
,D/qdlights(  846): set_light_backlight: 179
,D/qdlights(  846): set_light_backlight: 175
,D/qdlights(  846): set_light_backlight: 172
,D/qdlights(  846): set_light_backlight: 168
,D/qdlights(  846): set_light_backlight: 165
,D/qdlights(  846): set_light_backlight: 162
,D/qdlights(  846): set_light_backlight: 158
,D/qdlights(  846): set_light_backlight: 155
,D/qdlights(  846): set_light_backlight: 152
,D/qdlights(  846): set_light_backlight: 148
,I/QCNEJ   ( 1886): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:04:44.216 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/qdlights(  846): set_light_backlight: 145
D/qdlights(  846): set_light_backlight: 142
,D/qdlights(  846): set_light_backlight: 138
,D/qdlights(  846): set_light_backlight: 135
,D/qdlights(  846): set_light_backlight: 130
,D/qdlights(  846): set_light_backlight: 127
,D/qdlights(  846): set_light_backlight: 123
,D/qdlights(  846): set_light_backlight: 120
,D/qdlights(  846): set_light_backlight: 117
,D/qdlights(  846): set_light_backlight: 113
,D/qdlights(  846): set_light_backlight: 110
,D/qdlights(  846): set_light_backlight: 107
,D/qdlights(  846): set_light_backlight: 103
,D/qdlights(  846): set_light_backlight: 100
,D/qdlights(  846): set_light_backlight: 97
,D/qdlights(  846): set_light_backlight: 93
,D/qdlights(  846): set_light_backlight: 90
,D/qdlights(  846): set_light_backlight: 87
,D/qdlights(  846): set_light_backlight: 83
,D/qdlights(  846): set_light_backlight: 80
,D/qdlights(  846): set_light_backlight: 77
,D/qdlights(  846): set_light_backlight: 73
,D/qdlights(  846): set_light_backlight: 70
,D/qdlights(  846): set_light_backlight: 67
,D/qdlights(  846): set_light_backlight: 63
,D/qdlights(  846): set_light_backlight: 60
,D/qdlights(  846): set_light_backlight: 57
,D/qdlights(  846): set_light_backlight: 53
,D/qdlights(  846): set_light_backlight: 50
,D/qdlights(  846): set_light_backlight: 47
,D/qdlights(  846): set_light_backlight: 43
,D/qdlights(  846): set_light_backlight: 40
,D/qdlights(  846): set_light_backlight: 37
,D/qdlights(  846): set_light_backlight: 33
,D/qdlights(  846): set_light_backlight: 30
,D/qdlights(  846): set_light_backlight: 27
,D/qdlights(  846): set_light_backlight: 23
,D/qdlights(  846): set_light_backlight: 20
,D/qdlights(  846): set_light_backlight: 17
,D/qdlights(  846): set_light_backlight: 13
,D/qdlights(  846): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1886): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1886): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-04 17:04:47.247 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 156055134008; DSPS: 5212556; Offset : -3022518348
,I/PowerManagerService(  846): ALS enabled for SRE
D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36446 ms ago)
I/PowerManagerService(  846): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  846): ALS enabled for SRE
,D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36465 ms ago)
W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  846): Sleeping (uid 1000)...
D/LPWGController(  846): [updateScreenState] screen on = false
,D/LPWGController(  846): disable proximity sensor
D/LPWGController(  846): enable proximity sensor
I/SensorManager(  846): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@d6b26e8] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  846): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  846): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  846): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  846): activate: handle is 48, enable
,V/sensors_hal_Ctx(  846): activate sensors is 1400000000000
D/sensors_hal_Thresh(  846): enable: handle=48
I/sensors_hal_SAM(  846): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  846): waitForResponse: timeout=1000
V/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  846): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  846): enable: Received response: 0
D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36519 ms ago)
,I/Adreno-EGL(  846): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  846): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  846): Build Date: 03/02/15 Mon
I/Adreno-EGL(  846): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  846): Remote Branch: 
I/Adreno-EGL(  846): Local Patches: 
I/Adreno-EGL(  846): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (972 us)
,I/Sensors (  422): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  846): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  846): processInd: handle 48, count=1
V/sensors_hal_Thresh(  846): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  846): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  846): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  846): poll: count: 256
I/sensors_hal_Ctx(  846): poll: released wakelock sensor_ind
D/sensors_hal_Util(  846): waitForResponse: timeout=0
D/LPWGController(  846): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  846): current mode = 1  value = 1 1
I/LPWGController(  846): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  846): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  846): set_light_backlight: 0
,I/SensorManager(  846): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  846): activate: handle is 46, disable
V/sensors_hal_Ctx(  846): activate sensors is 1000000000000
D/sensors_hal_LP2(  846): enable: handle=46
D/sensors_hal_LP2(  846): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  846): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
I/DisplayManagerService(  846): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  846): Display changed displayId=0
V/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  846): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1753): Display #0 changed.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
D/SurfaceControl(  846): Excessive delay in setPowerMode(): 180ms
I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  846): Got set_interactive hint
,D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1372): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1372): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
,D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/WifiServerServiceExt(  846): sendKtScanInterval  mRtspPlay : false
I/WifiServerServiceExt(  846): set CMD_KT_SCAN_INTERVAL
V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=on, calling pid 846
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
,V/voice   (  285): voice_set_parameters: enter: screen_state=on
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  285): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
D/GpsLocationProvider(  846): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/SplitWindow(  846): check instance of lgWin Window{13a109e7 u0 SearchPanel}
,I/QCNEJ   ( 1886): |CORE| sendScreenState: state:true
,D/InputDispatcher(  846): Window went away: Window{2988f57 u0 SearchPanel}
,I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,I/LEDService( 1833): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1833): stopPatternFlashing()
D/qdlights( 1833): set_light_notifications: 0,0,0,0,3
I/LEDService( 1833): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1833): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1833): updateLightsLocked : turn off led
D/qdlights( 1833): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1833): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1833): lockStatus = 0
D/LEDHandler( 1833): RESTART MSG
D/LNfcService( 1806): action : android.intent.action.SCREEN_ON
,D/NfcServiceNXP( 1806): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1806): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1806): isRequireNfcCRouting() return true
D/LNfcService( 1806): isHCERoutingtoHost() return : true
D/NfcService( 1806): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1806): mEnableLPD: true
D/NfcService( 1806): mEnableReader: false
D/NfcService( 1806): mEnableHostRouting: true
D/NfcService( 1806): newParams.techmask= mTechMask: default
D/NfcService( 1806): mEnableLPD: true
D/NfcService( 1806): mEnableReader: false
D/NfcService( 1806): mEnableHostRouting: true
D/NfcService( 1806): screenState= 3
D/NfcService( 1806): Discovery configuration equal, not updating.
D/Ulp_jni (  846): JNI:system_update. Event-0
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2729): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:4:52
,D/WeatherService( 2729): 2 : ACTION screen on
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2729): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2729): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:4:52
,I/Sensors (  422): sns_pwr.c(301):releasing wakelock
D/AppCleanupService( 3876): android.intent.action.SCREEN_ON
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): ACTION_SCREEN_ON
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=off, calling pid 846
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
D/WifiController(  846): CMD_SCREEN_OFF 
D/WifiController(  846): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
D/GpsLocationProvider(  846): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1886): |CORE| sendScreenState: state:false
I/LEDService( 1833): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1833): stopPatternFlashing()
D/qdlights( 1833): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1833): clear
I/LEDService( 1833): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1833): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1833): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1806): action : android.intent.action.SCREEN_OFF
I/LEDService( 1833): updateLightsLocked : turn on led
E/LEDService( 1833): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1833): Can't handle this request of patternId:0
D/LEDHandler( 1833): RESTART MSG
,D/NfcServiceNXP( 1806): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1949): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2729): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:4:52
D/WeatherService( 2729): 2 : ACTION screen off
D/WeatherService( 2729): 2 : TimeTick Receiver Unregister
D/WeatherService( 2729): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:4:52
,D/AppCleanupService( 3876): android.intent.action.SCREEN_OFF
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): ACTION_SCREEN_OFF
,D/AppCleanupService( 3876): AppUsageStatsSaveTask
E/NxpNfcJni( 1806): getReconnectState = 0x0
,D/LCardEmulationManager( 1806): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1806): getDefaultRoute
D/LNfcService( 1806): isRequireNfcCRouting() return true
D/LNfcService( 1806): isHCERoutingtoHost() return : true
D/NfcService( 1806): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1806): mEnableLPD: true
D/NfcService( 1806): mEnableReader: false
D/NfcService( 1806): mEnableHostRouting: true
D/NfcService( 1806): newParams.techmask= mTechMask: 0
D/NfcService( 1806): mEnableLPD: true
D/NfcService( 1806): mEnableReader: false
D/NfcService( 1806): mEnableHostRouting: true
,D/NfcService( 1806): screenState= 1
E/NxpNfcJni( 1806): getReconnectState = 0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{3c3fc994 type 2 when 162380 com.android.systemui} when 162380
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1753): getCallState : 0
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{130c1c3d type 2 when 165096 android} when 165096
,I/ActivityManager(  846): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7427 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/ActivityThread( 5900): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 138366, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  846): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 228938, reason: UserStart
I/NotificationManager(  846): android: cancelAsUser(716319171) by android
D/ChimeraCfgMgr( 5900): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5900): Module APK com.google.android.play.games already loaded
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 5900): 0 accounts found with uca feature
I/GamesSyncAdapter( 5900): Starting sync for 3a3529a
I/GamesSyncAdapter( 5900): Sync duration for 3a3529a: 16
,D/ChimeraCfgMgr( 5900): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5900): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 7427): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7427):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7427):   adb logcat -s GAv4
,W/GAv4    ( 7427): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7427): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7427): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 7427): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,D/ChimeraCfgMgr( 5900): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5900): Module APK com.google.android.play.games already loaded
,I/NotificationManager(  846): android: cancelAsUser(-715483196) by android
I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7427): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 7427): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7427): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7427): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7427): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 7427): CheckpointMarkThreadRoots callback created = 0xaaf282f0
,V/JNIHelp ( 7427): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 7427): CheckpointMarkThreadRoots callback created = 0xaaf282d0
,W/System  ( 7427): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7427): Installed default security provider GmsCore_OpenSSL
I/NotificationManager(  846): android: cancelAsUser(-1488629395) by android
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  846): Killing 6523:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10006/pid_6523/cgroup.procs: No such file or directory
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 176056046136; DSPS: 5867946; Offset : -3022522060
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=361126491, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{10a7a1f4 type 2 when 187564 android} when 187564
D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=361126491 [*alarm*], flags=0x0
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{21707d1d type 2 when 188381 com.google.android.gms} when 188381
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{24724b92 type 2 when 195182 android} when 195182
,I/rmt_storage(  276): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
I/rmt_storage(  276): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  276): wakelock acquired: 1, error no: 42
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  276): 
I/rmt_storage(  276): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 196058039878; DSPS: 6523371; Offset : -3022512064
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 216060834142; DSPS: 7178823; Offset : -3022525105
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 236062543353; DSPS: 7834239; Offset : -3022525452
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ClearcutLoggerApiImpl( 5900): disconnect managed GoogleApiClient
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 256063646678; DSPS: 8489635; Offset : -3022520890
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 276065529952; DSPS: 9145057; Offset : -3022529237
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 296067792757; DSPS: 9800491; Offset : -3022524914
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 263, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 316069434311; DSPS: 10455905; Offset : -3022532951
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 336071747898; DSPS: 11111341; Offset : -3022537372
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/LocationManagerService(  846): remove 2bfc50ca
D/LocationManagerService(  846): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  846): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  846): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  846): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=361126491, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=361126491 [*alarm*], flags=0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 356073625859; DSPS: 11766762; Offset : -3022520957
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 263, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 376074650278; DSPS: 12422156; Offset : -3022533667
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 396076278396; DSPS: 13077569; Offset : -3022523137
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 416078470784; DSPS: 13733001; Offset : -3022528170
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 261, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 261
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 261
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 436080155360; DSPS: 14388416; Offset : -3022522061
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 260
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 260
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 260, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 456081956759; DSPS: 15043835; Offset : -3022520939
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,I/NotificationManager(  846): android: cancelAsUser(2) by android
I/ActivityManager(  846): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7541 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 5900): propertyValue:false
D/libc-netbsd( 5900): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5900): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 7541): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7541): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7541): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7541): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7541): Installed default security provider GmsCore_OpenSSL
,W/art     ( 7541): Suspending all threads took: 16.510ms
,I/art     ( 7541): CheckpointMarkThreadRoots callback created = 0xb042d820
,W/ResourcesManager( 7541): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7541): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 7541): CheckpointMarkThreadRoots callback created = 0xb4958de0
,E/YouTube MDX( 7541): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/dex2oat ( 7597): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-375626393.jar --oat-fd=31 --oat-location=/data/data/com.google.android.youtube/cache/ads-375626393.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7541): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/dex2oat ( 7597): dex2oat took 101.192ms (threads: 4)
,I/NotificationManager( 7541): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7541): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7541): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7541): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 7541): Found 10006
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7541): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  846): Process com.android.gallery3d (pid 7173) has died
,I/NotificationManager( 7541): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  280): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 7541): propertyValue:false
D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 476083792063; DSPS: 15699255; Offset : -3022518487
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 496084537368; DSPS: 16354640; Offset : -3022534090
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 516086203402; DSPS: 17010054; Offset : -3022518140
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 536088089748; DSPS: 17665476; Offset : -3022521853
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 259, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 259
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 259
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 556089515418; DSPS: 18320883; Offset : -3022530821
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 576090912650; DSPS: 18976289; Offset : -3022537060
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 596092946027; DSPS: 19631715; Offset : -3022518026
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 257, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 257
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 257
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 616094759354; DSPS: 20287135; Offset : -3022535727
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 636095882835; DSPS: 20942531; Offset : -3022510670
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 656096909755; DSPS: 21597925; Offset : -3022521218
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 256, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 256
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 256
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 676098542976; DSPS: 22253339; Offset : -3022536258
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 696100946927; DSPS: 22908777; Offset : -3022512756
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 716102654941; DSPS: 23564193; Offset : -3022515681
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 255
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 255
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 255, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 736103402172; DSPS: 24219578; Offset : -3022529123
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 756104904664; DSPS: 24874987; Offset : -3022522044
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  280): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 7541): propertyValue:false
D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7541): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7541): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 776106415907; DSPS: 25530397; Offset : -3022538867
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 255, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 255
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 255
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 796108102722; DSPS: 26185812; Offset : -3022528567
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 816110431673; DSPS: 26841248; Offset : -3022520879
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 836112107239; DSPS: 27496663; Offset : -3022521774
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 254
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 254
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 254, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 856113475772; DSPS: 28152068; Offset : -3022526402
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 876115743473; DSPS: 28807502; Offset : -3022519137
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 254
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 254
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 254, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 254
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 254
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 254, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 254
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 254
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 254, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 896117249351; DSPS: 29462912; Offset : -3022539165
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 253, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 253
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 253
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 916118892676; DSPS: 30118325; Offset : -3022511135
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 936120547774; DSPS: 30773740; Offset : -3022534686
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 956122059588; DSPS: 31429149; Offset : -3022517947
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 253, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 253
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 253
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 976123577185; DSPS: 32084559; Offset : -3022528365
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 996125845927; DSPS: 32739993; Offset : -3022516048
,D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=361126491, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{354dc8ee type 2 when 998583 com.android.bluetooth} when 998583
W/bt-smp  ( 2077): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2077): Plain text(LSB ~ MSB) = 50 3b 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2077): Encrypted text(LSB ~ MSB) = 91 92 c1 ab f4 a4 14 a4 c5 0e e8 ce fa f8 3e cd 
W/bt-btm  ( 2077): Stopping oneshot timer
I/ActivityManager(  846): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7730 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 7730): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7730): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@e8f4ac1
,D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=361126491 [*alarm*], flags=0x0
I/ActivityManager(  846): Killing 7148:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10011/pid_7148/cgroup.procs: No such file or directory
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1016126762274; DSPS: 33395383; Offset : -3022515436
,D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=361126491, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{3b6b418f type 2 when 1016850 com.google.android.gms} when 1016850
,D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=361126491 [*alarm*], flags=0x0
,I/GCM     ( 5900): Message from null null
,E/GCM     ( 5900): Dropping message from null
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 252
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 252
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 252, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1036128475963; DSPS: 34050799; Offset : -3022510576
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1056130373457; DSPS: 34706222; Offset : -3022535585
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1076132023501; DSPS: 35361636; Offset : -3022533438
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 252, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 252
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 252
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1096134305317; DSPS: 36017070; Offset : -3022510002
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1116136583590; DSPS: 36672505; Offset : -3022520494
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1136138373217; DSPS: 37327924; Offset : -3022531327
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 251, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 251
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 251
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1156140201336; DSPS: 37983344; Offset : -3022536476
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1176142531588; DSPS: 38638780; Offset : -3022523606
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1196144942101; DSPS: 39294219; Offset : -3022523982
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 250, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 250
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 250
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1216146449177; DSPS: 39949628; Offset : -3022512033
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/UsageStatsService(  846): User[0] Flushing usage stats to disk
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1236148744325; DSPS: 40605064; Offset : -3022538174
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1256151020672; DSPS: 41260498; Offset : -3022518435
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 250, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 250
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 250
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1276152536966; DSPS: 41915908; Offset : -3022527838
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1296153581281; DSPS: 42571302; Offset : -3022521094
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1316154667889; DSPS: 43226698; Offset : -3022533275
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1336156786735; DSPS: 43882127; Offset : -3022520143
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1356157957509; DSPS: 44537525; Offset : -3022508827
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1376160547709; DSPS: 45192970; Offset : -3022512805
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 250, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 250
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 250
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1396162197493; DSPS: 45848384; Offset : -3022510788
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1416163718786; DSPS: 46503794; Offset : -3022515426
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 250, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 250
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 250
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 250
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 250
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 250, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1436165418416; DSPS: 47159210; Offset : -3022524781
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 249, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 249
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 249
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1456166649189; DSPS: 47814610; Offset : -3022514710
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1476169178765; DSPS: 48470053; Offset : -3022518328
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1496171532039; DSPS: 49125490; Offset : -3022514776
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 249, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 249
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 249
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1516173044010; DSPS: 49780900; Offset : -3022528711
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1536174067649; DSPS: 50436293; Offset : -3022512255
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1556176183422; DSPS: 51091723; Offset : -3022532687
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 248, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 248
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 248
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1576177308831; DSPS: 51747120; Offset : -3022536246
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1596178806636; DSPS: 52402529; Offset : -3022533830
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1616181078712; DSPS: 53057963; Offset : -3022522032
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 248, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 248
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 248
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1636182663809; DSPS: 53713375; Offset : -3022521688
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1656184059478; DSPS: 54368781; Offset : -3022529880
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1676186232386; DSPS: 55024212; Offset : -3022523902
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 248, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 248
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 248
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1696187355817; DSPS: 55679609; Offset : -3022529517
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1716188733308; DSPS: 56335014; Offset : -3022525551
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1736190641737; DSPS: 56990436; Offset : -3022509264
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 248, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 248
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 248
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1756192166731; DSPS: 57645846; Offset : -3022509942
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1776193627244; DSPS: 58301254; Offset : -3022514324
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1796196160570; DSPS: 58956697; Offset : -3022514191
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 247
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 247
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 247, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1816197428635; DSPS: 59612099; Offset : -3022527682
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1836199446492; DSPS: 60267525; Offset : -3022525887
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 247
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 247
,I/QCNEJ   ( 1886): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1886): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1833): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1833): Battery Level Remaining: 100%
D/LEDHandler( 1833): Battery Temp: 247, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  846): battery changed pluggedType: 2
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1856201392006; DSPS: 60922949; Offset : -3022531362
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1833): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1876203036946; DSPS: 61578363; Offset : -3022534659
,D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=361126491, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{12c80025 type 0 when 1451925202041 com.google.android.gms} when 1451925202041
I/ProcessStatsService(  846): Prepared write state in 26ms
,I/ProcessStatsService(  846): Prepared write state in 12ms
,I/ProcessStatsService(  846): Prepared write state in 36ms
,D/LocationManagerService(  846): getAllProviders()=[passive, gps, network]
,I/DigitalAppWidgetProvider( 7730): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7730): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@e8f4ac1
D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=361126491 [*alarm*], flags=0x0
I/EventLogService( 5900): Aggregate from 1451923445283 (log), 1451923401792 (data)
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3144): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3144): created cursor android.database.sqlite.SQLiteCursor@c2cb59b on behalf of 5900
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
,V/DownloadManager( 3144): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3144): created cursor android.database.sqlite.SQLiteCursor@1f40bd38 on behalf of 5900
V/DownloadManager( 3144): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3144): created cursor android.database.sqlite.SQLiteCursor@1987d111 on behalf of 5900
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1896204101469; DSPS: 62233758; Offset : -3022537912
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{27476938 type 2 when 1898730 com.android.bluetooth} when 1898730
,W/bt-smp  ( 2077): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2077): Plain text(LSB ~ MSB) = 20 2b 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2077): Encrypted text(LSB ~ MSB) = 20 24 8c 1e f8 ed 2f af 08 c1 0a f8 ef 7c f8 97 
W/bt-btm  ( 2077): Stopping oneshot timer
I/ThermalEngine(  298): Sensor:pa_therm0:25000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7921): 
D/AndroidRuntime( 7921): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7921): CheckJNI is OFF
D/AndroidRuntime( 7921): Calling main entry com.android.commands.pm.Pm
I/art     (  846): Explicit concurrent mark sweep GC freed 80335(4MB) AllocSpace objects, 13(385KB) LOS objects, 33% free, 23MB/35MB, paused 2.344ms total 169.108ms
I/ActivityManager(  846): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  846): Killing 5480:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  846): WIN DEATH: Window{8580e7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  846): Focus left window: Window{8580e7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  846): Window went away: Window{8580e7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  846): Skipping PackageSetting{3ae4ee88 com.example.hello/10317} due to missing metadata
I/ActivityManager(  846):   Force finishing activity ActivityRecord{125c56e5 u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  846): Display changed displayId=0
D/DSDPConnection( 1753): Display #0 changed.
W/ActivityManager(  846): Spurious death for ProcessRecord{14c70d11 5480:com.test.thalitest/u0a316}, curProc for 5480: null
I/ActivityManager(  846): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1949): [Launcher.java:5203:onStart()]onStart
I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1886): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/ActivityManager(  846): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7947 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/System.err( 3394): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3394): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3394): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3394): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3394): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3394): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3394): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3394): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3394): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3394): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3394): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3394): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1949): [Launcher.java:776:onResume()]onResume
W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1949): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/art     ( 2026): Explicit concurrent mark sweep GC freed 8266(483KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 2.135ms total 151.493ms
I/[LGHome]Launcher.Model( 1949): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1949): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1949): [Launcher.java:929:onResume()]onResume end
I/Activity( 1949): Activity.onPostResume() called 
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]EVENT( 1949): [Launcher.java:986:onPause()]onPause
W/[LGHome]LGWallpaperInfo( 1949): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1949): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 7947): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7947): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7947): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemUI[Framework](  846): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/administrator(  846): Handling package changes for user 0
W/PhoneWindowManagerEx(  846): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  846): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  846): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f4c4d4a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  846): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  846): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  846): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  846): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f4c4d4a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  846): Focus entered window: Window{23d27442 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1949): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1949): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1949): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1372): handleShortcutListChanged...
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]EVENT( 1949): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1372): handleShortcutListChanged...
I/[LGHome]EVENT( 1949): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1949): [setNavigationBarColor] color=0x 0
I/art     (  846): Explicit concurrent mark sweep GC freed 13185(981KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.225ms total 322.987ms
I/LGEmail ( 7947): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7947): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/AndroidRuntime( 7921): Shutting down VM
I/NotificationService(  846): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  846): Receieved: android.intent.action.PACKAGE_REMOVED
D/LCardEmulationManager( 1806): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1806): getDefaultRoute
D/TaskPersister(  846): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
W/InputMethodManagerService(  846): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  846): Got RemoteException sending setActive(false) notification to pid 5480 uid 10316
I/[LGHome]Launcher.Model( 1949): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1949): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline(  846): Timeline: Activity_windows_visible id: ActivityRecord{233e3135 u0 com.lge.launcher2/.Launcher t219} time:1904272
I/[LGHome]EVENT( 1949): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1949): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1949): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1949): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1949): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1949): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1949): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1949): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1949): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
E/b       ( 1620): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]EVENT( 1949): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1949): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1949): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/PackageChangeReceiver( 7947): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7984 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  846): Killing 7200:com.android.contacts/u0a18 (adj 15): empty #11
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/ResourcesManager(  846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1949): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/libprocessgroup(  846): failed to open /acct/uid_10018/pid_7200/cgroup.procs: No such file or directory

```
