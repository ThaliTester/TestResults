#### Test 57132760f6ec045_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
D/AndroidRuntime( 5532): 
D/AndroidRuntime( 5532): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5532): CheckJNI is OFF
D/AndroidRuntime( 5532): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  838): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  838): setTaskToReturnTo : TaskRecord{25f5806f #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  838): setTaskToReturnTo : TaskRecord{25f5806f #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  838): AppWindowTokenEx init.. 
D/ContextHelper(  838): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  838): Focus left window: Window{348a03bd u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5532): Shutting down VM
I/[LGHome]EVENT( 1872): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  838): check instance of lgWin Window{38f2c181 u0 Starting com.test.thalitest}
I/ActivityManager(  838): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5552 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1872): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1930): Closing mic
I/MicrophoneInputStream( 1930): mic_close com.google.android.apps.gsa.speech.audio.u@3829138b
I/[LGHome]EVENT( 1872): [Launcher.java:5214:onStop()]onStop
V/AudioRecord( 1930): stop()
D/AudioRecord( 1930): AudioRecord->stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioFlinger(  278): Record stopped OK
V/AudioPolicyManager(  278): stopInput() input 17
V/AudioPolicyService(  278): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  278): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  278): ThreadBase::setParameters() routing=0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
I/WindowStateAnimator(  838): Starting window displayed
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3d7c000
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/SystemUI[Framework](  838): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  838): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  838): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  838): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@15038ce3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
,I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1370): draw background and invalidate : color = 13000000
,D/BarTransitions( 1370): draw background and invalidate : color = 13121212
V/audio_hw_primary(  278): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  278): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
,V/audio_hw_primary(  278): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  278): disable_audio_route: exit
E/audio_hw_primary(  278): disable_snd_device: enter 144
D/hardware_info(  278): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  278): disable_snd_device: snd_device(144: lg-vr-handset-mic)
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
V/AudioPolicyService(  278): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  278): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  278): setParameters(): io 17, keyvalue hotword_active=0, calling pid 278
V/AudioFlinger(  278): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  278): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  278): in_set_parameters: exit: status(0)
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3d7c000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioRecord( 1930): stop()
,V/AudioRecord( 1930): stop()
V/AudioRecord( 1930): stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioPolicyManager(  278): releaseInput() 17
V/AudioPolicyManager(  278): closeInput(17)
V/AudioFlinger(  278): closeInput() 17
V/AudioSystem(  278): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1746): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): ThreadBase::exit
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioSystem( 1930): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  838): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): RecordThread 0xb3d7c000 exiting
V/AudioSystem( 3109): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2081): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioFlinger(  278): removeClient_l() pid 1930, calling pid 278
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioFlinger(  278): releasing 16 from 1930 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
I/HotwordRecognitionRnr( 1930): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1930): Hotword detection finished
D/ContextHelper( 5552): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 5552): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5552): Time to load native libraries: 4 ms (timestamps 68-72)
,I/LibraryLoader( 5552): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5552): Binding Chromium to main looper Looper (main, tid 1) {2e2a6593}
,I/LibraryLoader( 5552): Expected native library version number "",actual native library version number ""
I/chromium( 5552): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5552): Initializing chromium process, singleProcess=true
W/art     ( 5552): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5552): ApplicationContext is null in ApplicationStatus
W/chromium( 5552): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5552): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5552): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5552): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5552): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5552): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5552): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5552): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5552): Remote Branch: 
I/Adreno-EGL( 5552): Local Patches: 
I/Adreno-EGL( 5552): Reconstruct Branch: 
,V/AudioPolicyService(  278): registerClient() client 0xb551c880, uid 10316
,D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6aed67b:true
D/BluetoothAdapter( 5552): 990627823: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5552): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5552): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5552): CordovaWebView is running on device made by: LGE
,W/art     ( 5552): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5552): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5552): Activity.onPostResume() called 
,D/OpenGLRenderer( 5552): Render dirty regions requested: true
I/OpenGLRenderer( 5552): Initialized EGL, version 1.4
D/OpenGLRenderer( 5552): Enabling debug mode 0
,D/Atlas   ( 5552): Validating map...
,D/SplitWindow(  838): check instance of lgWin Window{351e546b u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5552): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  838): Focus entered window: Window{351e546b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  838): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  838): Displayed com.test.thalitest/.MainActivity: +1s130ms
I/Timeline(  838): Timeline: Activity_windows_visible id: ActivityRecord{3b83b17c u0 com.test.thalitest/.MainActivity t222} time:100722
I/Timeline( 5552): Timeline: Activity_idle id: android.os.BinderProxy@27e48adf time:100744
,W/BindingManager( 5552): Cannot call determinedVisibility() - never saw a connection for the pid: 5552
,D/JsMessageQueue( 5552): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5552): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618650112
,I/chromium( 5552): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5552): CheckpointMarkThreadRoots callback created = 0xb04ecd00
,I/art     ( 5552): CheckpointMarkThreadRoots callback created = 0xb04eccd0
,I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  269): wakelock acquired: 1, error no: 42
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  269): 
I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/jxcore-log( 5552): Initializing JXcore engine
,W/jxcore-log( 5552): JXcore engine is ready
I/art     ( 5552): Background sticky concurrent mark sweep GC freed 48443(4MB) AllocSpace objects, 0(0B) LOS objects, 14% free, 22MB/26MB, paused 5.446ms total 79.249ms
,W/Thread-641( 5635): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6577]" dev="sockfs" ino=6577 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-641( 5635): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-641( 5635): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7507]" dev="sockfs" ino=7507 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-641( 5635): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-641( 5635): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-641( 5635): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25948]" dev="sockfs" ino=25948 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5552): Starting JXcore engine
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,W/jxcore-log( 5552): Platform android
W/jxcore-log( 5552): 
W/jxcore-log( 5552): Process ARCH arm
W/jxcore-log( 5552): 
,I/jxcore-log( 5552): JXcore Cordova bridge is ready!
I/jxcore-log( 5552): 
W/jxcore-log( 5552): JXcore engine is started
,I/jxcore-log( 5552): Toggling radios to true
I/jxcore-log( 5552): 
,D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  838): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  838): Message: 1
D/BluetoothManagerService(  838): MESSAGE_ENABLE: mBluetooth = null
D/BluetoothAdapterService(990627823)( 1980): onBind()
,D/BluetoothManagerService(  838): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/BluetoothManagerService(  838): Message: 40
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  838): JNI:system_update. Event-4
,D/WifiServiceImplEx(  838): setWifiEnabled: true pid=5552, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  838): setWifiEnabled: true pid=5552, uid=10316
,D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  838): JNI:system_update. Event-4
I/bluedroid( 1980): config_hci_snoop_log
D/WifiServiceImplEx(  838): disconnect pid=5552, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  838): reconnect pid=5552, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5552): Radios toggled
I/jxcore-log( 5552): 
I/jxcore-log( 5552): My device name is: LGE-LG-D722
I/jxcore-log( 5552): 
D/BluetoothManagerService(  838): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  838): Broadcasting onBluetoothServiceUp() to 9 receivers.
I/LGFTMITEM(  838): [GET_FTM][id=6], offset=12288
E/WifiHW  (  838): Wifi MAC Address = a0:39:f7:70:12:80
,E/WifiHW  (  838): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  838): band=b
E/WifiHW  (  838): ": cur_etheraddr=a0:39:f7:70:12:80
D/SoftapController(  274): Softap fwReload - Ok
,V/LGMDMManagerInternal( 1980): Create singleton instance
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
D/CommandListener(  274): Trying to bring down wlan0
D/CommandListener(  274): Clearing all IP addresses on wlan0
,E/WifiHW  (  838): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
I/wpa_supplicant( 5656): Successfully initialized wpa_supplicant
,D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/BluetoothAdapterService(990627823)( 1980): enable() - Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1980): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1980): Setting state to 11
I/BluetoothAdapterState( 1980): Bluetooth adapter state changed: 10-> 11
D/WifiMonitor(  838): startMonitoring(wlan0) with mConnected = false
D/BluetoothAdapterService(990627823)( 1980): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  838): Message: 60
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 10 -> 11
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,D/BluetoothAdapterService(990627823)( 1980): processStart()
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:36.855 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 5656): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5656): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,I/ActivityManager(  838): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5666 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/LGBluetoothAPIService( 1800): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [2]
,D/BtSettings.ProfileConfig( 1980): Unable to read settings
D/BtSettings.ProfileConfig( 1980): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1980): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1980): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1980): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1980): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 1980): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1980): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1980): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1980): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1980): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1980): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/BluetoothAdapterService( 1980): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1980): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1980): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1980): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1980): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1980): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1980): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/BluetoothAdapterService( 1980): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1980): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1980): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(990627823)( 1980): processStart() - Make Bond State Machine
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/BluetoothBondStateMachine( 1980): make
D/BluetoothAdapterService( 1980): setAdapterService() - set to: null
,D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
D/LGBluetoothServiceAdapter( 1980): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 1980): StableState(): Entering Off State
D/BluetoothAdapterService( 1980): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1980): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1980): Unable to read settings
D/BtSettings.ProfileConfig( 1980): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1980): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1980): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1980): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1980): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1980): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 1980): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1980): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1980): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1980): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1980): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1980): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1980): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(990627823)( 1980): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/BluetoothAdapterService( 1980): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1980): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1980): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(990627823)( 1980): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
I/[SystemUI]BluetoothHandler( 1370): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/BluetoothHeadset( 1746): Proxy object connected
D/BluetoothHeadset(  838): Proxy object connected
D/HeadsetService( 1980): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 1980): classInitNative: succeeds
D/BluetoothAdapterService( 1980): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1980): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1980): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(990627823)( 1980): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
,D/LGBluetoothFeatureConfig( 1980): isPrivacyLogsEnabled : true
D/BluetoothAdapterService( 1980): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1980): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1980): Not skipping com.android.bluetooth.hdp.HealthService
I/BluetoothHeadsetServiceJni( 1980): classInitNative: succeeds
D/BluetoothAdapterService(990627823)( 1980): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/HeadsetStateMachine( 1980): make
D/BluetoothHeadset( 1746): Proxy object connected
D/BluetoothAdapterService( 1980): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1980): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1980): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(990627823)( 1980): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
,D/BluetoothHeadset( 1746): Proxy object connected
D/BluetoothAdapterService( 1980): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1980): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1980): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(990627823)( 1980): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1980): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1980): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1980): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(990627823)( 1980): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 1980): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1980): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1980): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(990627823)( 1980): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1980): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1980): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1980): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(990627823)( 1980): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1980): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1980): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
,D/BtSettings.ProfileConfig( 1980): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1980): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(990627823)( 1980): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
,V/LGMDMManager( 1980): Create singleton instance
I/BluetoothAdapterState( 1980): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 1980): max_hf_connections = 1
I/bluedroid( 1980): get_profile_interface handsfree
,I/bt-btif ( 1980): btif_hf_get_interface
I/bt-btif ( 1980): init
D/bt-btif ( 1980): max_hf_clients = 1
D/bt-btif ( 1980): btif_max_hf_clients = 1
D/bt-btif ( 1980): btif_enable_service: current services:0xa06c9330
V/ToneGenerator( 1980): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  278): registerClient() client 0xb4027200, uid 1002
V/AudioPolicyManager(  278): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,V/AudioPolicyManagerEx(  278): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  278): getOutput() returns output 2
V/AudioFlinger(  278): registerClient() client 0xb40336a0, pid 1980
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 0
V/AudioSystem( 1980): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  278): thread 0xb5651000 type 0 TID 1291 waking up
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioFlinger(  278): thread 0xb5735000 type 0 TID 1295 waking up
V/AudioFlinger(  278): thread 0xb56eb000 type 0 TID 1292 waking up
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  278): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  278): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  838): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  838): ioConfigChanged() opening already existing output! 2
V/ToneGenerator( 1980): Create Track: 0xb4908a80
V/AudioSystem( 1370): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1370): ioConfigChanged() opening already existing output! 2
V/AudioTrack( 1980): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 1980): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioSystem( 1930): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1930): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 1746): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1980): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1746): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1980): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 2081): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2081): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  278): ioConfigChanged() event 0, ioHandle 4
I/AudioFlinger(  278): isAudioPlaybackHookOn() false
V/AudioSystem(  278): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3109): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1370): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1370): ioConfigChanged() opening already existing output! 4
D/AudioTrack( 1980): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 2081): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2081): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  278): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  278): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  838): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  838): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem(  838): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  838): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1930): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1930): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1930): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1930): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1370): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1,370): ioConfigChanged() opening already existing output! 6
V/AudioPolicyManager(  278): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioSystem( 1746): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1746): ioConfigChanged() opening already existing output! 4
V/AudioPolicyManager(  278): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioSystem( 3109): ioConfigChanged() opening already existing output! 2
V/AudioPolicyManagerEx(  278): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  278): getOutput() returns output 2
V/AudioSystem( 1746): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1746): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1980): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1980): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 1980): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1980): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 3109): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3109): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1980): getLatency() output 2, latency 50
V/AudioSystem( 3109): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1980): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1980): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1980): Create normal PCM 0x1 Track
V/AudioSystem( 3109): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  278): createTrack() lSessionId: 22
V/AudioFlinger(  278): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioSystem( 2081): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2081): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 1980): Flags here  0x4 
V/AudioTrack( 1980): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  278): acquiring 22 from 1980, for 1980
V/AudioFlinger(  278):  added new entry for 22
V/ToneGenerator( 1980): ToneGenerator INIT OK, time: 105142
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
D/HeadsetStateMachine( 1980): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 1980): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1980): [BTUI] listenForMultiSimPhoneState : start = false
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb5651000
D/HeadsetStateMachine( 1980): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  278): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1980
D/BluetoothA2dp(  838): Proxy object connected
D/A2dpService( 1980): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 1980): classInitNative: succeeds
V/Avrcp   ( 1980): make
D/Avrcp   ( 1980): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1980): get_profile_interface avrcp
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/audio_hw_primary(  278): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  278): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  278): platform_set_parameters: enter: bt_samplerate=8000
I/bt-btif ( 1980): btif_rc_get_interface
I/bt-btif ( 1980): ## init ##
I/LGBluetoothAvrcpServiceJni( 1980): classInitNative: succeeds
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
V/ToneGenerator( 1980): ToneGenerator destructor
V/ToneGenerator( 1980): stopTone
V/ToneGenerator( 1980): Delete Track: 0xb4908a80
V/AudioTrack( 1980): ~AudioTrack, releasing session id from 1980 on behalf of 1980
V/AudioFlinger(  278): remove track (4099) and delete from mixer
V/AudioFlinger(  278): releasing 22 from 1980 for 1980
V/AudioPolicyService(  278): AudioCommandThread() adding release output 2
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/AudioPolicyService(  278): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  278): PlaybackThread::Track destructor
V/AudioFlinger(  278): removeClient_l() pid 1980, calling pid 278
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  278): releaseOutput() 2
I/LGBluetoothAvrcpAdapter( 1980): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 1980): initNative: succeeds
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
I/BluetoothAvrcpBrcmAdapterJni( 1980): classInitBrcmNative
,I/BluetoothAvrcpBrcmAdapterJni( 1980): initBrcmNative
V/AudioService(  838): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,E/AudioService(  838): No RCC entry present to update
E/RemoteController( 1980): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1980): classInitNative
I/BluetoothA2dpServiceJni( 1980): classInitNative: succeeds
D/A2dpStateMachine( 1980): make
I/bluedroid( 1980): get_profile_interface a2dp
I/bt-btif ( 1980): btif_av_get_src_interface
I/bt-btif ( 1980): init
D/bt-btif ( 1980): btif_enable_service: current services:0xa06c9330
I/LGBluetoothA2dpServiceJni( 1980): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1980): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1980): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1980): [BTUI] init
,D/LGBluetoothPowerControlManager( 1980): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  838): Message: 30
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
I/BluetoothHidServiceJni( 1980): classInitNative: succeeds
D/A2dpStateMachine( 1980): Enter Disconnected: -2
D/HidService( 1980): Received start request. Starting profile...
I/bluedroid( 1980): get_profile_interface hidhost
I/bt-btif ( 1980): btif_hh_get_interface
I/bt-btif ( 1980): init
D/bt-btif ( 1980): btif_enable_service: current services:0xa06c9330
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
,I/BluetoothHealthServiceJni( 1980): classInitNative: succeeds
D/HealthService( 1980): Received start request. Starting profile...
I/bluedroid( 1980): get_profile_interface health
I/bt-btif ( 1980): btif_hl_get_interface
I/bt-btif ( 1980): init
D/bt-btif ( 1980): Process name (droid.bluetooth)
D/bt-btif ( 1980): btif_hl_soc_thread_init
D/bt-btif ( 1980): create_thread: entered
D/bt-btif ( 1980): create_thread: thread created successfully
D/bt-btif ( 1980): entered btif_hl_select_thread
D/bt-btif ( 1980): btif_hl_select_wakeup_init
D/bt-btif ( 1980): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1980): max_s=55 
D/bt-btif ( 1980): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 1980): classInitNative: succeeds
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
I/BluetoothPanServiceJni( 1980): classInitNative(L105): succeeds
D/PanService( 1980): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1980): initializeNative(L110): pan
I/bluedroid( 1980): get_profile_interface pan
D/bt-btif ( 1980): stack_initialized = 0, btpan_cb.enabled:0
,I/LGBluetoothPanAdapter( 1980): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
,I/BtGatt.JNI( 1980): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 1980): handleDebugAction() action=null
D/BtGatt.GattService( 1980): Received start request. Starting profile...
D/BtGatt.GattService( 1980): start()
I/bluedroid( 1980): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1980): advertise manager created
I/LGBluetoothGattAdapter( 1980): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 1980): setGattService:  set to: null
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
,D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
I/LGBluetoothMapAdapter( 1980): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1980): BluetoothMapBinder()
D/BluetoothMapService( 1980): Received start request. Starting profile...
D/BluetoothMapService( 1980): start()
D/BluetoothMapEmailSettingsLoader( 1980): Found 0 applications
D/BluetoothMapEmailAppObserver( 1980): createReceiver()
,W/ResourcesManager( 5666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5666): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5666): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5666): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5666): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager(  838): Process com.google.android.gms:car (pid 5192) has died
,D/BluetoothMapEmailAppObserver( 1980): initObservers()
D/BluetoothMapEmailAppObserver( 1980): getEnabledAccountItems()
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
,I/BluetoothSAPServiceJni( 1980): classInitNative(L170): succeeds
D/SapService( 1980): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1980): initializeNative(L175): sap
I/bluedroid( 1980): get_profile_interface sap
I/bt-btif ( 1980): btif_sc_get_interface
I/bt-btif ( 1980): init
D/bt-btif ( 1980): btif_enable_service: current services:0xa06c9330
I/LGBluetoothSapAdapter( 1980): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1980): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1980): [BTUI] initSapManager
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
,D/LgeBluetoothSimManager( 1746): [BTUI] SAP_ENABLE_EVT
V/BluetoothFTPServiceJni( 1980): classInitNative
I/BluetoothFTPServiceJni( 1980): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
D/BluetoothFTPService( 1980): BluetoothFtpBinder()
,D/**BluetoothFTPService( 1980): Received start request. Starting profile...
V/BluetoothFTPService( 1980): FTP-Server Service start
D/BluetoothFTPServiceJni( 1980): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1980): get_profile_interface ftp
I/bt-btif ( 1980): btif_fts_get_interface
I/bt-btif ( 1980): init
D/bt-btif ( 1980): btif_enable_service: current services:0xa06c9330
D/BluetoothFTPServiceJni( 1980): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
D/LGBluetoothFeatureConfig( 1980): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1980): classInitNative
I/BluetoothOPPServiceJni( 1980): classInitNative(L373): succeeds
V/OppService( 1980): Opp initBinder
D/**OppService( 1980): Received start request. Starting profile...
D/OppService( 1980): Starting OppService 
D/LGBluetoothOppAdapter( 1980): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 1980): com.android.bluetooth: cancelAll by com.android.bluetooth
,V/BluetoothOppNotification( 1980): send message
D/BluetoothOppPreference( 1980): Dumping Names:  
D/BluetoothOppPreference( 1980): {}
D/BluetoothOppPreference( 1980): Dumping Channels:  
D/BluetoothOppPreference( 1980): {}
D/OppService( 1980): Start()
W/BluetoothOPPServiceJni( 1980): initOppNative
D/BluetoothOPPServiceJni( 1980): initOppNative(L383): OPP
I/bluedroid( 1980): get_profile_interface opp
I/bt-btif ( 1980): btif_op_get_interface
D/BluetoothOPPServiceJni( 1980): initOppNative(L411): mOppCallbacksObj 2098426
D/BluetoothOPPServiceJni( 1980): initOppNative(L413): calling OPP init
,I/bt-btif ( 1980): btif_opp_init
D/bt-btif ( 1980): btif_enable_service: current services:0xa06c9330
D/BluetoothOPPServiceJni( 1980): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1980): initOppNative(L430): mOppCallbacksObj 2098426
V/OppService( 1980): setOppService(): set to: com.broadcom.bt.service.opp.OppService@1f77038d
D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
D/HeadsetStateMachine( 1980): Proxy object connected
D/LGBluetoothHfpAdapter( 1980): [BTUI] queryPhoneState
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - Message: 1
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(990627823)( 1980): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
I/IndexDatabaseHelper( 5666): Using schema version: 115
D/BluetoothAdapterState( 1980): isTurningOnRadio()=false
D/BluetoothAdapterState( 1980): isTurningOffRadio()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1980): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1980): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 1980): Proxy object connected
D/LGBluetoothPowerControlManager( 1980): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@34cfa942
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - Message: 1
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(990627823)( 1980): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1980): isTurningOnRadio()=false
D/BluetoothAdapterState( 1980): isTurningOffRadio()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1980): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetStateMachine( 1980): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 1980): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1980): Disconnected process message: 11, size: 0
V/OppService( 1980): pendingUpdate is :  true
D/BluetoothAdapterService( 1980): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - Message: 1
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(990627823)( 1980): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1980): isTurningOnRadio()=false
D/BluetoothAdapterState( 1980): isTurningOffRadio()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1980): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 1980): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - Message: 1
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(990627823)( 1980): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1980): isTurningOnRadio()=false
D/BluetoothAdapterState( 1980): isTurningOffRadio()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1980): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
I/IndexDatabaseHelper( 5666): Index is fine
V/OppService( 1980): Deleted complete outbound shares, number =  0
D/BluetoothAdapterService( 1980): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - Message: 1
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(990627823)( 1980): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1980): isTurningOnRadio()=false
D/BluetoothAdapterState( 1980): isTurningOffRadio()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1980): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1980): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 1980): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1980): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 1980): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - Message: 1
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(990627823)( 1980): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1980): isTurningOnRadio()=false
D/BluetoothAdapterState( 1980): isTurningOffRadio()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1980): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1980): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1980): Profile still not running:com.broadcom.bt.service.opp.OppService
,V/BluetoothMapService( 1980): Handler(): got msg=1
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - Message: 1
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(990627823)( 1980): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1980): isTurningOnRadio()=false
D/BluetoothAdapterState( 1980): isTurningOffRadio()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1980): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1980): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - Message: 1
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(990627823)( 1980): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1980): isTurningOnRadio()=false
D/BluetoothAdapterState( 1980): isTurningOffRadio()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1980): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1980): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - Message: 1
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(990627823)( 1980): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1980): isTurningOnRadio()=false
D/BluetoothAdapterState( 1980): isTurningOffRadio()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1980): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1980): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1980): new notify threadi!
V/BluetoothOppNotification( 1980): send delay message
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - Message: 1
D/BluetoothAdapterService(990627823)( 1980): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(990627823)( 1980): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1980): isTurningOnRadio()=false
D/BluetoothAdapterState( 1980): isTurningOffRadio()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1980): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1980): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(990627823)( 1980): onProfileServiceStateChange() - All profile services started.
V/OppService( 1980): ContentObserver received notification
V/OppService( 1980): ContentObserver received notification
V/BluetoothOppProvider( 1980): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/BluetoothAdapterState( 1980),: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1980): enable
I/bt-btif ( 1980): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1980): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
I/GKI_LINUX( 1980): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1980): btu_task pending for preload complete event
,I/bt_hci_bdroid( 1980): init
I/bt_vendor( 1980): init
I/bt_vnd_conf( 1980): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1980): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1980): libbt-hci init returns 0
I/ActivityManager(  838): Process com.google.android.gm (pid 5367) has died
,I/bt_userial_vendor( 1980): userial vendor open: opening /dev/ttyHS99
,D/bt_userial_vendor( 1980): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1980): device fd = 70 open
D/bt_hwcfg( 1980): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 1980): hw_config_cback state=1
,D/bt_hwcfg( 1980): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1980): hw_config_cback state=4
D/bt_hwcfg( 1980): Chipset Name: BCM4334B0
D/bt_hwcfg( 1980): Chipset BCM4334B0
D/bt_hwcfg( 1980): Target name = [BCM4334B0]
I/bt_hwcfg( 1980): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1980): hw_config_cback state=2
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1980): hw_config_cback state=3
I/bt_hwcfg( 1980): bt vendor lib: set UART baud 4000000
I/art     (  838): Explicit concurrent mark sweep GC freed 17995(924KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.360ms total 176.720ms
,V/BluetoothOppProvider( 1980): created cursor android.database.sqlite.SQLiteCursor@235d4b89 on behalf of 
V/BluetoothOppProvider( 1980): created cursor android.database.sqlite.SQLiteCursor@30b3178e on behalf of 
V/BluetoothOppProvider( 1980): created cursor android.database.sqlite.SQLiteCursor@13427baf on behalf of 
V/OppService( 1980): pendingUpdate is :  true
V/BluetoothOppNotification( 1980): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1980): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1980): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1980): created cursor android.database.sqlite.SQLiteCursor@d582bbc on behalf of 
V/BluetoothOppNotification( 1980): update too frequent, put in queue
,V/BluetoothOppProvider( 1980): created cursor android.database.sqlite.SQLiteCursor@1b461745 on behalf of 
V/BluetoothOppNotification( 1980): outbound: succ-0  fail-0
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1980): hw_config_cback state=5
I/NotificationManager( 1980): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1980): outbound notification was removed.
V/BluetoothOppProvider( 1980): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1980): created cursor android.database.sqlite.SQLiteCursor@3c4d1e9a on behalf of 
V/BluetoothOppNotification( 1980): inbound: succ-0  fail-0
I/NotificationManager( 1980): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1980): inbound notification was removed.
V/BluetoothOppProvider( 1980): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1980): created cursor android.database.sqlite.SQLiteCursor@314523cb on behalf of 
V/OppService( 1980): pendingUpdate is :  false
E/OppService( 1980): UpdateThread is Completed
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
V/BluetoothPbapReceiver( 1980): PbapReceiver onReceive 
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
V/BluetoothPbapReceiver( 1980): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1980): ***********state = 11
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/Tethering(  838): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5666): remove : truetruefalse
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5666): remove2
V/WiFiOffLoadSharedPrefsUtils( 5666): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 5666): save remove
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/WiFiOffLoadBroadcast( 5666): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5666): S: false, R: true
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
E/wpa_supplicant( 5656): USIM:  scard_init function
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
I/wpa_supplicant( 5656): rfkill: Cannot open RFKILL control device
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 9
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
I/ActivityManager(  838): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5711 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,I/wpa_supplicant( 5656): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/BluetoothPermissionRequest( 5666): onReceive
I/wpa_supplicant( 5656): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/LGBluetoothFeatureConfig( 5666):  get() - isFeatureLoaded : false
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/WifiStateMachine(  838): MAC Addr from driver = a0:39:f7:70:12:80
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  838): setPowerSaveActivated(false)
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:38.048 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [3]
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
I/WifiServerServiceExt(  838): batteryPsActivateMsgHandler : state:0 event:3
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
E/WifiServerServiceExt(  838): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1adb5c59:true
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
V/BluetoothSapReceiver( 1980): [BTUI] checkServiceStart
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/LGBluetoothStateChangeReceiver( 1980): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
E/WifiConfigStore(  838): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1980): hw_config_cback state=6
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1980): hw_config_cback state=6
I/ActivityManager(  838): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5730 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/WifiStateMachine(  838): enableVerboseLogging : level 2
D/WifiStateMachine(  838): Setting OUI to DA-A1-19
D/WifiNative-HAL(  838): Setting external_sim to 1
I/WifiNative-HAL(  838): startHal
E/wifi    (  838): getStaticLongField sWifiHalHandle 0x9ab4f8ec
I/WifiHAL (  838): Initializing wifi
I/WifiHAL (  838): Creating socket
I/WifiHAL (  838): Initialized Wifi HAL Successfully; vendor cmd = 103
,D/wifi    (  838): Did set static halHandle = 0xb04ae300
D/wifi    (  838): halHandle = 0xb04ae300, mVM = 0xb487c280, mCls = 0x201d5a
E/wifi    (  838): getStaticLongField sWifiHalHandle 0x9ab4f89c
D/wifi    (  838): array field set
I/WifiNative-HAL(  838): interface[0] = wlan0
I/WifiNative-HAL(  838): interface[1] = p2p0
D/wifi    (  838): setting scan oui 0xb04b6ac0
D/WifiHAL (  838): Sending mac address OUI
E/WifiHAL (  838): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  838): Setting OUI to DA-A1-19
I/WifiNative-HAL(  838): startHal
D/wifi    (  838): setting scan oui 0xb04b6ac0
D/WifiHAL (  838): Sending mac address OUI
E/WifiHAL (  838): failed to set scanning mac OUI; result = -95
I/WifiNative-HAL(  838): Waiting for HAL events mWifiHalHandle=-1337269504
D/wifi    (  838): waitForHalEvents called, vm = 0xb487c280, obj = 0x201d5a, env = 0xaaf0f400
E/wifi    (  838): getStaticLongField sWifiHalHandle 0x999deb2c
D/PCSuite ( 5711): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/WifiHS20(  838): hidePasspointNotification off =false
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  838): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
D/CommandListener(  274): Trying to bring up p2p0
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WfdsService( 1800): Supplicant Connection state is changed : true
D/WfdsService( 1800): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1800): Set the WFDS Monitor: true
W/Settings( 5170): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdsMonitor( 1800): WfdsMonitorThread create
D/WfdsMonitor( 1800): WFDS Monitor is created and started
D/WfdsService( 1800): WiFi: Supplicant connection re-established
D/WifiMonitor(  838): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService(  838): P2pEnablingState
D/LGWifiP2pService(  838): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2p socket connection successful
D/LGWifiP2pService(  838): P2pEnabledState
D/WifiScanningService(  838): SCAN_AVAILABLE : 3
D/RttService(  838): SCAN_AVAILABLE : 3
D/RttService(  838): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  838): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  838): startHal
,I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/wifi    (  838): getting scan capabilities on interface[0] = 0xb04b6ac0
D/WifiHAL (  838): Creating message to get scan capablities; iface = 24
D/wifi    (  838): failed to get capabilities : -95
D/LGWifiP2pService(  838): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  838): before postfix = G3s-1
D/WifiServerServiceExt(  838): postfix byte check : 5
D/LGWifiP2pService(  838): after postfix = G3s-1
E/WifiScanningService(  838): could not get scan capabilities
D/WifiNative-HAL(  838): p2pGetDeviceAddress
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:38.179 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiNative-HAL(  838): p2pGetDeviceAddress returning a2:39:f7:70:12:80
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/WifiServerServiceExt(  838): set CMD_ADD_DEFAULT_PROFILE
D/LGWifiP2pService(  838): DeviceAddress: a2:39:f7:70:12:80
D/WfdsService( 1800): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,D/WfdsService( 1800): Update P2p Interface State: 3
E/CtrlSupplicant( 1800): Access OK "@android:wpa_wlan0"
I/WifiServerServiceExt(  838): setWifiDualbandAPConnection band : 1
E/CtrlSupplicant( 1800): Succeed to open control connection
E/CtrlSupplicant( 1800): Succeed to open monitor connection
D/UsbSettingsReceiver( 5666): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5666): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5666): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5666): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5666): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/wpa_supplicant( 5656): nWIFIDualbandAPConnection: 1
I/WifiServerServiceExt(  838): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 5656): disconnect_rssi_lvl: -100
D/LGWifiP2pService(  838): sending p2p persistent groups changed broadcast
D/LGWifiP2pService(  838): sending p2p connection changed broadcast
D/WfdsMonitor( 1800): Supplicant connection established
D/WfdsService( 1800): Connected to the supplicant for wfds
D/WfdsService( 1800): WifiP2pState is changed : true
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1800): Receive the WFDS_ENABLE Method
D/WfdsService( 1800): Set the WFDS Monitor: true
D/WfdsService( 1800): Connected to the supplicant for wfds
D/WfdsJNI ( 1800): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 5656): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/LGWifiP2pService(  838): InactiveState
D/WfdsService( 1800): WIFI_P2P_CONNECTION_CHANGED_ACTION
I/bt_hwcfg( 1980): bt vendor lib: set UART baud 115200
I/WifiServerServiceExt(  838): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
D/WfdsJNI ( 1800): doCommand: WFDS_GET_MAC_ADDRESS
D/bt_hwcfg( 1980): Settlement delay -- 100 ms
I/bt_hwcfg( 1980): Setting fw settlement delay to 100 
I/wpa_supplicant( 5656): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
E/wpa_supplicant( 5656): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
D/WfdsJNI ( 1800): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5656): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsJNI ( 1800): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1800): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/LGWifiP2pService(  838): P2pEnabledState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1800): selectPreferredScanChannel [6]
D/LGWifiP2pService(  838): InactiveState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1800): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
D/LGWifiP2pService(  838): P2pEnabledState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt(  838): No p2p device connected
I/WifiServerServiceExt(  838): set CMD_UPDATE_DEFAULT_PROFILE
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1800): isConnected: false
D/WfdsService( 1800): GroupInfoAvailable: mGroupInfo is null
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1800): DefaultState - msg [9441285] is not handled
D/UsbSettingsControl( 5666): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 5666): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5666): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5666): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5666): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5666): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 5666): [AUTORUN] setTetherStatus() : status=false
V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
I/wpa_supplicant( 5656): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,I/wpa_supplicant( 5656): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WiFiOffLoadUpdatePriority( 5666): remove : truetruetrue
W/ResourcesManager( 5730): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:38.298 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/LGBluetoothProfileConnectionReceiver_EasySetting( 5730): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/AuthorizationBluetoothService( 1728): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:38.316 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LocSvc_java(  838): onReceive
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:38.32 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateSCANNING
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateASSOCIATING
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1980): hw_config_cback state=2
,D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1980): hw_config_cback state=7
I/bt_hwcfg( 1980): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1980): Setting local bd addr to F8:95:C7:87:85:54
D/WiFiOffLoadUpdatePriority( 5666): remove1
V/WiFiOffLoadSharedPrefsUtils( 5666): save remove
,D/GONS    ( 1746): GONS isTestMode: false Country: 
D/bt_hwcfg( 1980): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1980): hw_config_cback state=8
I/bt_hwcfg( 1980): vendor lib fwcfg completed
I/bt-btif ( 1980): HC preload_cb 0 [0:SUCCESS 1:FAIL]
,I/bt-btu  ( 1980): btu_task received preload complete event
D/WiFiOffLoadBroadcast( 5666): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5666): S: false, R: false
D/WiFiOffLoadUpdatePriority( 5666): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5666): connected SSID: null
,D/WiFiOffLoadUpdatePriority( 5666): private wpa: "NG700" 300
I/        ( 1980): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 1980): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 1980): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 1980): BTE_InitTraceLevels -- TRC_PROTOCOL,0
D/WifiServiceImplEx(  838): addOrUpdateNetwork pid=5666, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  838):  uid = 1000 SSID "NG700" nid=0
E/WifiConfigStore(  838):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WiFiOffLoadUpdatePriority( 5666):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5666): configuration updated: 0
,I/WifiServerServiceExt(  838): set CMD_UPDATE_DEFAULT_PROFILE
D/WiFiOffLoadUpdatePriority( 5666): configuration saved: true
,D/PCSuite ( 5711): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  838): Killing 5469:com.android.calendar/u0a13 (adj 15): empty #11
E/bt-btif ( 1980): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,I/GKI_LINUX( 1980): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1980): warning : media task started media_task_refcnt 1 
W/bt-smp  ( 1980): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1980): Plain text(LSB ~ MSB) = ad b9 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1980): Encrypted text(LSB ~ MSB) = 1c 9c 45 c6 67 85 5a 70 90 65 5e 2c 86 63 ef 31 
W/bt-btm  ( 1980): Stopping oneshot timer
E/bt-btif ( 1980): Calling BTA_HhEnable
E/bt-btif ( 1980): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1980): HAL bt_hal_cbacks->adapter_properties_cb
D/BT_PROF_AUDIO( 1980): created moving average (N=100)
D/BT_PROF_AUDIO( 1980): reset rate average
W/bt-btif ( 1980): overflow 0, enter 0, exit 0
D/BluetoothAdapterProperties( 1980): Address is:F8:95:C7:87:85:54
W/libprocessgroup(  838): failed to open /acct/uid_10013/pid_5469/cgroup.procs: No such file or directory
D/BluetoothAdapterProperties( 1980): Name is: G3s-1
,D/BluetoothAdapterProperties( 1980): Scan Mode:20
D/BluetoothManagerService(  838): Bluetooth Adapter name changed to G3s-1
D/BluetoothAdapterProperties( 1980): Discoverable Timeout:120
D/BluetoothManagerService(  838): Stored Bluetooth name: G3s-1
E/bt-btif ( 1980): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1980): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 1980): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1980): BTA_JvEnable
E/bt-btif ( 1980): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 1980): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 1980): init_hci_slots(L136): in
D/IOP_DB_BT( 1980): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 1980): db_open: db_open : handle 2691512284l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1980): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1980): db_query: result 1
I/        ( 1980): iop_db_open: iop_db_open status 0
E/bt-btif ( 1980): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1980): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 1980): bta_pan_co_init
D/bte_conf( 1980): Device ID record 1 : primary
D/bte_conf( 1980):   vendorId            = 00c4
D/bte_conf( 1980):   vendorIdSource      = 0001
D/bte_conf( 1980):   product             = 13a1
D/bte_conf( 1980):   version             = 1000
D/bte_conf( 1980):   clientExecutableURL = 
D/bte_conf( 1980):   serviceDescription  = 
D/bte_conf( 1980):   documentationURL    = 
D/bte_conf( 1980): bte_load_did_conf no section named DID2.
I/bt-btif ( 1980): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 1980): btif_hf_upstreams_evt: wrong handle = 12346 
I/bt-btif ( 1980): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1980): opc_state_cb(L140):  opc_state_cb state:0
D/BluetoothAdapterState( 1980): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1980): ScanMode =  20
D/BluetoothAdapterProperties( 1980): State =  11
D/BluetoothAdapterProperties( 1980): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 1980): Setting state to 12
,I/BluetoothAdapterState( 1980): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(990627823)( 1980): updateAdapterState() - Broadcasting state to 1 receivers.
D/OppService( 1980): onOpcStateChange()
D/OppService( 1980): Recieved MESSAGE_OPC_ENABLE
D/LGBluetoothFeatureConfig( 1980): isPrivacyLogsEnabled : true
I/bt-btif ( 1980): HAL bt_op_callbacks->ops_state_cb
D/BluetoothManagerService(  838): Message: 60
D/BluetoothOPPServiceJni( 1980): ops_state_cb(L223):  ops_state_cb state:0
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/OppService( 1980): onOpsStateChange() :0
I/bt-btif ( 1980): HAL bt_fts_callbacks->operation_cmpl_cb
I/BluetoothAdapterState( 1980): Entering On State
D/BluetoothFTPServiceJni( 1980): operation_cmpl_callback(L192):  oper:3 status:0
D/BluetoothManagerService(  838): Broadcasting onBluetoothStateChange(true) to 6 receivers.
I/BluetoothAdapterState( 1980): Entering On State from state = 11
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=true
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/BluetoothAdapterService(990627823)( 1980): isQuetModeEnabled() - Enabled = false
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=true
D/BluetoothAdapterService(990627823)( 1980): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1980): [BTUI] autoConnect() : not allowed
D/OppService( 1980): Recieved MESSAGE_OPS_ENABLE
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=true
D/BluetoothHeadset(  838): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1980): onBluetoothStateChange: up=true
I/BluetoothFTPService( 1980): onFtpServerEnabled: /storage
D/LGBluetoothServiceAdapter( 1980): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1980): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 1980): [BTUI]         local_name: G3s-1
D/BluetoothPanServiceJni( 1980): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 1980): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothA2dp(  838): onBluetoothStateChange: up=true
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/BluetoothAdapterService(990627823)( 1980): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(990627823)( 1980): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1980): [BTUI] autoConnect() : not allowed
V/BluetoothOppNotification( 1980): new notify threadi!
V/BluetoothOppNotification( 1980): send delay message
D/bt_h4   ( 1980): vendor lib postload completed
,V/BluetoothOppProvider( 1980): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1980): created cursor android.database.sqlite.SQLiteCursor@55a47a8 on behalf of 
V/BluetoothOppNotification( 1980): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1980): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1980): created cursor android.database.sqlite.SQLiteCursor@1d35e2c1 on behalf of 
V/BluetoothOppNotification( 1980): outbound: succ-0  fail-0
I/NotificationManager( 1980): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1980): outbound notification was removed.
V/BluetoothOppProvider( 1980): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1980): created cursor android.database.sqlite.SQLiteCursor@3d4e8a66 on behalf of 
V/BluetoothOppNotification( 1980): inbound: succ-0  fail-0
I/NotificationManager( 1980): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1980): inbound notification was removed.
V/BluetoothOppProvider( 1980): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1980): created cursor android.database.sqlite.SQLiteCursor@398031a7 on behalf of 
I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5763 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/BluetoothAdapterProperties( 1980): Scan Mode:21
I/bt-btif ( 1980): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1980): Discoverable Timeout:120
,E/BluetoothManagerService(  838): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothAPIService( 1800): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/BluetoothManagerService(  838): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1370): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
D/BluetoothManagerService(  838): Message: 40
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1800): Message: 1
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/LGBluetoothAPIService( 1800): MESSAGE_BOOT_COMPLETED
I/BluetoothMapService( 1980): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1980): STATE_ON
,W/ContextImpl( 5666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/LGBluetoothAPIService( 1800): [BTUI] LGBluetoothAPIService Binding Success
,D/BluetoothAdapterService( 1980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b0bc7ef
V/BluetoothPbapService( 1980): Pbap Service onCreate
V/BluetoothPbapService( 1980): Starting PBAP service
,D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/LGBluetoothPbapAdapter( 1980): [BTUI] getInstance : create
V/BluetoothPbapService( 1980): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapService( 1980): state: 12
V/BluetoothMapService( 1980): Handler(): got msg=1
D/BluetoothMapMasInstance( 1980): Map Service startRfcommSocketListener
D/LGBluetoothAPIServer( 1980): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1980): [BTUI] onBind()
V/BluetoothPbapReceiver( 1980): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1980): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1980): ***********state = 12
D/BluetoothMapMasInstance( 1980): MAS initSocket()
D/BluetoothMapMasInstance( 1980):   masId = 00
D/BluetoothMapMasInstance( 1980):   msgTypes = 0e
D/BluetoothMapMasInstance( 1980):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1980):   SDP string = 000eSMS/MMS
D/LGBluetoothAPIService( 1800): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
V/BluetoothPbapService( 1980): Handler(): got msg=1
V/BluetoothPbapService( 1980): Pbap Service startRfcommSocketListener
D/LGBluetoothAPIService( 1800): Message: 100
D/LGBluetoothAPIService( 1800): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothPbapService( 1980): Pbap Service initSocket
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 1980): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 5666): Adding local A2DP profile
I/bt-btif ( 1980): BTA_JvCreateRecordByUser
I/bt-btif ( 1980): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1980): [BTUI] createSocketChannel FD=83 mFd=0
V/BluetoothMapMasInstance( 1980): Succeed to create listening socket 
D/BluetoothMapMasInstance( 1980): Accepting socket connection...
W/BluetoothAdapter( 1980): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  838): Message: 30
I/bt-btif ( 1980): BTA_JvCreateRecordByUser
I/bt-btif ( 1980): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1980): [BTUI] createSocketChannel FD=85 mFd=83
V/BluetoothPbapService( 1980): Succeed to create listening socket 
V/BluetoothPbapService( 1980): Accepting socket connection...
D/LocalBluetoothProfileManager( 5666): Adding local HEADSET profile
D/BluetoothManagerService(  838): Message: 30
D/BluetoothManagerService(  838): Message: 30
,D/BluetoothManagerService(  838): Message: 30
D/LocalBluetoothProfileManager( 5666): Adding local MAP profile
D/BluetoothMap( 5666): Create BluetoothMap proxy object
D/BluetoothManagerService(  838): Message: 30
D/BluetoothManagerService(  838): Message: 30
,D/LocalBluetoothProfileManager( 5666): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 1980): Pbap Service onBind
D/LGBluetoothUserBindClient( 5666): [BTUI] initUserBindClient
W/ContextImpl( 5666): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 5666): finishStartingService: stopping service
D/BluetoothA2dp( 5666): Proxy object connected
,D/A2dpProfile( 5666): Bluetooth service connected
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/BluetoothHeadset( 5666): Proxy object connected
D/HeadsetProfile( 5666): Bluetooth service connected
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/BluetoothInputDevice( 5666): Proxy object connected
,D/HidProfile( 5666): Bluetooth service connected
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
D/BluetoothPan( 5666): BluetoothPAN Proxy object connected
D/PanProfile( 5666): Bluetooth service connected
D/LGDMClient( 5763): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5763): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 5763): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
W/ContextImpl( 5763): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/BluetoothMap( 5666): Proxy object connected
D/MapProfile( 5666): Bluetooth service connected
,D/BluetoothMap( 5666): getConnectedDevices()
D/BluetoothAdapterService(990627823)( 1980): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@cb6383d
V/BluetoothMapService( 1980): getConnectedDevices()
D/BluetoothPbap( 5666): Proxy object connected
D/PbapServerProfile( 5666): Bluetooth service connected
D/LGBluetoothUserBindClient( 5666): [BTUI] onServiceConnected
,V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
D/BluetoothPermissionRequest( 5666): onReceive
D/LGDMClient( 5763): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5763): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGBluetoothFeatureConfig( 5666): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 5666): [BTUI] FileNotFound: readProperty
,I/PCSuite ( 5711): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
V/BluetoothOppReceiver( 1980): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
D/PCSuite ( 5711): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5711): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 5763): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,V/BluetoothOppManager( 1980): restoreApplicationData! falsefalsenullnull
V/BluetoothSapReceiver( 1980): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 1980): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/AuthorizationBluetoothService( 1728): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  838): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5795 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  838): Killing 4026:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10006/pid_4026/cgroup.procs: No such file or directory
,V/[BNRBootReceiver]( 5795): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5795): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5795): Boot Receiver Return
W/MainApplication( 5795): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 5666): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 5656): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateASSOCIATED
I/ActivityManager(  838): Killing 5440:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/wpa_supplicant( 5656): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 5656): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
W/libprocessgroup(  838): failed to open /acct/uid_10014/pid_5440/cgroup.procs: No such file or directory
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:39.23 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/WifiServiceExtension(  838): setVHTCapabilityType  : false
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:39.241 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt(  838): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  838): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  838): setSecurityType  : 2
D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:39.283 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:39.284 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,D/WifiExtManager(  838): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@1f62db3a
,D/ConnectivityService(  838): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  838): Got NetworkAgent Messenger
D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  838): NetworkAgent connected
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
E/WifiStateMachine(  838): Start Dhcp Watchdog 1
D/DhcpStateMachine(  838): StoppedState
D/DhcpStateMachine(  838): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  838): WaitBeforeStartState
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateGROUP_HANDSHAKE
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-70 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:39.373 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateCOMPLETED
E/WifiStateMachine(  838): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService(  838): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2d78eddb target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2d78eddb target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine(  838): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  838): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  838): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  838): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  838): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateCOMPLETED
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 6
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  838): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  838): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  838): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5827): version 5.5.6 starting
E/dhcpcd  ( 5827): get_duid: Read-only file system
,I/dhcpcd  ( 5827): wlan0: broadcasting for a lease
,V/AudioFlinger(  278): thread 0xb56eb000 type 0 TID 1292 going to sleep
,V/AudioFlinger(  278): thread 0xb5651000 type 0 TID 1291 going to sleep
V/AudioFlinger(  278): thread 0xb5735000 type 0 TID 1295 going to sleep
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,I/ActivityManager(  838): Process com.google.android.talk (pid 5170) has died
,I/ActivityManager(  838): Process com.android.vending (pid 5034) has died
,I/dhcpcd  ( 5827): wlan0: offered 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5827): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5827): wlan0: leased 192.168.1.134 for 86400 seconds
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  838): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  838): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  838): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  838): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  838): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  838): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  838): bShouldSendDhcpAction Result: true
D/DhcpStateMachine(  838): DHCP Start/Renew wake lock is released.
D/LGWifiP2pService(  838): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  838): RunningState
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine(  838): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  838): ignoring duplicate network state non-change
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WifiHS20(  838): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService(  838): Adding iface wlan0 to network 100
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine(  838): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-70 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:42.127 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
D/WifiHS20(  838): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-70 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:42.13 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-70 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:42.133 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-70 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:42.136 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 2
D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
E/ConnectivityService(  838): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  838): Adding Route [fe80::/64 -> :: wlan0] to network 100
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  838): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,D/ConnectivityService(  838): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  838): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  838): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  838): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  838): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  838): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  838): currentScore = 0, newScore = 20
D/ConnectivityService(  838):    accepting network in place of null
D/ConnectivityService(  838): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
D/WIFI    (  838): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1746): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  838): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  838): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  838): [e] list.add(nai) empty : false size: 1
D/Tethering(  838): MasterInitialState.processMessage what=3
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
W/QCNEJ   ( 1835): |CORE| No family connected
I/QCNEJ   ( 1835): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/ConnectivityService(  838): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/ConnectivityService(  838): validation of new default Network = false
D/ConnectivityService(  838): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  838): enableDataServiceNotify 
D/DSQN    (  838): start dsqn bin
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/QCNEJ   ( 1835): |CORE| sendDefaultNwMsg: default = 1
V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] Start DNSResolver start to wait
,D/ConnectivityService(  838): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] wait 500ms before dns check
D/ConnectivityService(  838): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/DSQN    ( 5888): DSQN samuel.seo ver 141203
E/DSQN    ( 5888): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5888): created command queue thread
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
I/DSQN    ( 5888): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5888): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,V/NetworkPolicy(  838): [LG_RESTRICTED] checkMobilePolicy_type()
,D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
I/PCSuite ( 5711): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5711): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5666): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5666): MCCMNC not supported: null
I/PCSuite ( 5711): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5711): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:42.386 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/ContextImpl( 3409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] DNSResolver start dns
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{61bdc24 type 2 when 111264 com.google.android.gms} when 111264
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/jxcore-log( 5552): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5552): 
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out(  838): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 1728): propertyValue:false
I/jxcore-log( 5552): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5552): 
,I/jxcore-log( 5552): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5552): 
I/jxcore-log( 5552): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5552): 
,I/jxcore-log( 5552): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5552): 
,I/jxcore-log( 5552): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5552): 
I/jxcore-log( 5552): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5552): 
,V/WifiInternetCheck(  838): Single check msg out of sync, ignoring.
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  838): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/DSQN    ( 5888): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5888): restart monitoring
,I/DSQN    ( 5888): dsqn report finish
D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  838): DSQM DsqnNotification wlan0  1
D/DSQN    (  838): start to monitor internet connection
D/LocSvc_java(  838): onReceive
D/LocSvc_java(  838): got connectivity action
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  838): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  838): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  838): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  838): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  838): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  838): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  838): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5916 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NetworkChangeNotifierAutoDetect( 1930): Network connectivity changed, type is: 2
,I/ActivityManager(  838): Start proc com.google.android.gms for service com.google.android.gms/.auth.api.credentials.sync.CredentialSyncService: pid=5945 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  838): tsOffsetIs: Apps: 113449043346; DSPS: 3816067; Offset : -3015770288
I/ActivityManager(  838): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5956 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 23.703ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.537ms
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  838): propertyValue:false
I/System.out(  838): propertyValue:false
I/System.out(  838): propertyValue:false
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.567ms
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 25 Jan 2016 21:42:44 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453758165516], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453758165250]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Validated
D/ConnectivityService(  838): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  838): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  838): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  838): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
D/WIFI    (  838): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1746): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/ActivityManager(  838): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5973 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/WifiDataContinuityService(  838): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
,I/WifiServerServiceExt(  838): set CMD_CAPTIVE_CHECK_COMPLETED
,D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/GpsLocationProvider(  838): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LocSvc_java(  838): NTP server returned: 1453758164949 (Mon Jan 25 22:42:44 GMT+01:00 2016) reference: 113676 certainty: 68 system time offset: -709
D/AlarmManagerService(  838): Setting time of day to sec=1453758164
W/AlarmManagerService(  838): Unable to set rtc to 1453758164: Invalid argument
D/LocSvc_java(  838): Sending msg: 10 arg1:0 arg2:1
,W/ResourcesManager( 5945): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5945): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 5973): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5973): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5973): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/LocSvc_java(  838): reportXtraServer 
D/LocSvc_java(  838):  server1=http://xtrapath1.izatcloud.net/xtra2.bin
D/LocSvc_java(  838):  server2=http://xtrapath2.izatcloud.net/xtra2.bin
D/LocSvc_java(  838):  server3=http://xtrapath3.izatcloud.net/xtra2.bin
D/LocSvc_java(  838): xtraDownloadRequest
D/LocSvc_java(  838): Sending msg: 6 arg1:0 arg2:1
I/[SystemUI]Clock( 1370): onReceive = android.intent.action.TIME_SET
,D/WeatherService( 2653): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 22:42:44
I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
D/WeatherService( 2653): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2653): 2 : This is isUpdating : false
D/WeatherService( 2653): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2653): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2653): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2653): 2 : Fixed theme : optimus
,D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/WeatherReflect( 2653): 2 : Map key string is -2
I/ActivityManager(  838): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=6003 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ActivityManager(  838): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,D/lim     ( 2653): 2 : time = 22:42
I/WeatherReflect( 2653): Model Name : LG-D722
D/WeatherTheme( 2653): 2 : exactly same view!
D/WeatherTheme( 2653): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2653): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 22:42:45
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out(  838): propertyValue:false
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[LGHome]LGDateChangeReceiver( 1872): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=25 currentDate=-1 dayofweek=2 currentDayOfWeek=-1
,I/MultiDex( 5945): VM with version 2.1.0 has multidex support
,I/MultiDex( 5945): install
I/MultiDex( 5945): VM has multidex support, MultiDex support library is disabled.
I/[LGHome]LGCalendarIcon( 1872): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 25
,I/ActivityManager(  838): Process com.google.process.gapps (pid 3769) has died
E/GpsLocationProvider(  838): No APN found to select.
,I/AppConfig( 5973): Total System Memory = 906309632
I/GalleryUtils( 5973): Application Heap = 96 MB
I/AppConfig( 5973): App Tier : NOT_DEF
,I/[LGHome]LGCalendarIcon( 1872): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 25
D/SystemHelper( 5973): region [EU], country [EU], operator [OPEN], sub-operator []
I/[LGHome]Launcher( 1872): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 6003): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6003): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6003): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LgeGpsConstants(  838): Can't find 'ext_gps.conf'!!
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,W/ResourcesManager( 5956): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5956): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/NotificationManager(  838): android: cancelAsUser(-1597574061) by android
,V/JNIHelp ( 5956): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  838): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6030 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/GCM     ( 1728): GCM config loaded
,I/ActivityManager(  838): Process com.lge.lgdmsclient (pid 5763) has died
I/MusicStore( 5916): Database version: 120
W/System  ( 5956): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5956): Installed default security provider GmsCore_OpenSSL
I/LGEmail ( 6003): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6003): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out(  838): propertyValue:false
I/GservicesProvider( 6030): Gservices pushing to system: true; secure/global: true
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/LgeGpsLocationProvider(  838): NTP server: europe.pool.ntp.org
D/LgeGpsLocationProvider(  838): NTP server returned: 1453758165616 (Mon Jan 25 22:42:45 GMT+01:00 2016) reference: 114397 certainty: 35 system time offset: -40
,I/GoogleHttpClient( 6030): GMS http client unavailable, use old client
,I/ActivityManager(  838): Process com.lge.bnr (pid 5795) has died
,I/GoogleHttpClient( 6030): GMS http client unavailable, use old client
,I/ActivityManager(  838): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6070 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/jxcore-log( 5552): Test app app.js loaded
I/jxcore-log( 5552): 
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  838): propertyValue:false
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  838): propertyValue:false
,I/chromium( 5552): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5552): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 5552): BLE advertisement is supported,
I/jxcore-log( 5552): 
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5916): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/LocSvc_java(  838): calling native_inject_xtra_data
D/LocSvc_java(  838): Sending msg: 11 arg1:0 arg2:1
,I/art     (  838): Explicit concurrent mark sweep GC freed 79076(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 8.704ms total 276.175ms
V/JNIHelp ( 5945): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/MusicWidget( 2608): mDelayedStopHandler : unbind
,W/ActivityThread( 5945): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5945): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@314523cb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5945): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  838): Process com.android.settings (pid 5666) has died
,I/NotificationManager( 5945): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5945): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ALBootInit( 6070): ====action==>android.intent.action.TIME_SET
,V/WifiInternetCheck(  838): isHttpConnectionAvailable - We got a valid response : 204
I/MusicBrowser( 2081): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2081): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2081): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/ALBootInit( 6070): Alarm ALBootInit: TIME_SET
D/MusicBrowser( 2081): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/Alarms  ( 6070): [setNextAlert] start
D/MusicBrowser( 2081): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
,D/MusicBrowser( 2081): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/Alarms  ( 6070): [setNextAlert] (1)
,I/MusicBrowser( 2081): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,D/Alarms  ( 6070):  minTime  = 0
I/MusicBrowser( 2081): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
D/Alarms  ( 6070):  -- OK multi -- 0
E/jeny.kim( 6070): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6070): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/MediaFocusControl(  838):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1bd31b39com.lge.music.MediaPlaybackService$6@3244257e
,D/MusicBrowser( 2081): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/CommonUtil( 6070): BUILD Operator: OPEN
,D/Alarms  ( 6070): broadcastToWidgetProvider : false
D/Alarms  ( 6070): Enter formatDayAndTime(final Context context, long timeInMiliSec)
I/MusicBrowser( 2081): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2081): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2081): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
V/SettingsProvider(  838): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/MusicBrowser( 2081): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@cc922fc
I/DigitalAppWidgetProvider( 6070): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6070): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@31602dc9
I/MusicBrowser( 2081): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
V/DigitalAppWidgetProvider( 6070): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@31602dc9
W/ResourcesManager( 5956): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5956): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MusicBrowser( 2081): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2081): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2081): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2081): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2081): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/QuickCoverProvider( 6070): onReceiver
,I/MusicBrowser( 2081): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/ActivityManager(  838): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6105 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/art     ( 5945): Suspending all threads took: 5.831ms
I/MusicBrowser( 2081): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2081): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2081): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5916): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/MusicBrowser( 2081): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2081): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2081): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2081): reset
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5916): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/NativeLibraryUtils( 5945): Install completed successfully. count=14 extracted=0
I/art     ( 5956): CheckpointMarkThreadRoots callback created = 0xb042db50
,V/MediaPlayer[Native]( 2081): setListener
V/MediaPlayer[Native]( 2081): disconnect
V/MediaPlayer[Native]( 2081): destructor
V/AudioFlinger(  278): releasing 19 from 2081 for -1
,V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/MediaPlayer[Native]( 2081): disconnect
D/MusicBrowser( 2081): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
W/ResourcesManager( 5916): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5916): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SmartShareClient( 2081): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2081): [SmartShareManagerClient] smartshare client enabled
W/ResourcesManager( 6105): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/MusicBrowser( 2081): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2081): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2081): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2081): [SmartShareManagerClient] unregisterListener: 669289183
W/SmartShareClient( 2081): [SmartShareManagerClient] unregisterListener invalid listener: 669289183
E/YouTube MDX( 5956): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/SmartShareClient( 2081): [SmartShareManagerClient] terminate service: 2081/MediaPlaybackService/799713922
,E/HomeCloudIF( 2081): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2081): [SmartShareManagerClient] unbindService context:android.app.Application@2619432c
D/libc-netbsd( 5956): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5956): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 5956): CheckpointMarkThreadRoots callback created = 0xb4958de0
V/CloudHub( 2081): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2081): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2081): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2081): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2081): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2081): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
,W/art     ( 5956): Suspending all threads took: 14.701ms
V/JNIHelp ( 5916): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/CalendarApplication( 6105): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6105): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6105): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2ff1cb64, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@94441cd, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2faaaa82, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2e2a6593, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@35b239d0, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@31602dc9, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@65cecce, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3b0bc7ef, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@cc922fc, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@534dd85, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2cdf07da, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3bf6f40b, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@120372e8, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3feacd01, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1135c7a6, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@71ec5e7, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2010d594, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@cb6383d, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2ae6b832, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3907d983, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2aefb700, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1bd31b39, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3244257e, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@27e48adf, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2619432c, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@b4131f5, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@791b8a, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@30b0f5fb, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@216d6618, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1f3ff871, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@24556656, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3a0ef6d7, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@8decbc4, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@68aaaad, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@37d991e2, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@8e22973, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@32dee030, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@265444a9, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@282ea2e, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2abe9cf, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2989cf5c, lg_preferences_recent_ti,mezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2a038265, lg
,D/GeneralPreferenceUtils( 6105): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
E/ActivityThread( 5945): Failed to find provider info for com.android.contacts.metadata
D/Config  ( 6105): [init]
,I/Config  ( 6105): LGCalendar ver.4.40.17
I/Config  ( 6105): start check model
I/Config  ( 6105): start check native_ca
I/Config  ( 6105): Config Operator=OPEN, Country=EU
D/Config  ( 6105): [setDefaultValuesToPref]
D/Config  ( 6105): [parseProfiles]
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SyncManager(  838): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 36411, reason: UserStart, SyncResult: databaseError: true stats []
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ProfilesParser( 6105): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6105): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6105): [updateProfiletoCountryInfo]
D/GeneralPreference( 6105): [checkAndMigrateOldPreference]
D/SyncManager(  838): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 147852, reason: UserStart
I/NotificationManager(  838): android: cancelAsUser(716319171) by android
W/ResourcesManager( 5956): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5956): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/AgendaWidgetManager( 6105): [updateWidgets] 
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5956): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
W/ActivityThread( 5916): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5916): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23dbfbec: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5916): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5916): GMSCore installation verified
,I/ActivityManager(  838): Process com.lge.settings.easy (pid 5730) has died
,I/ConfigStore( 5916): Config Database version: 1
,I/ActivityManager(  838): Process com.lge.qremote (pid 5084) has died
,D/ChimeraCfgMgr( 5945): Reading stored module config
,I/PhoneApp( 1746): onTrimMemory: 10
I/PhoneApp( 1746): trim memory
I/art     ( 5945): CheckpointMarkThreadRoots callback created = 0xaaf1b410
,D/UEI.SmartControl( 5343): Service.onUnbind: IControl
D/UEI.SmartControl( 5343): Service.onDestroy
I/NotificationManager(  838): android: cancelAsUser(-1816247584) by android
I/BackgroundMemoryTrimmer( 1930): Trimming objects from memory, since app is in the background.
,D/UEI.SmartControl( 5343): Shutdown IRRCPlayer... 
,D/ChimeraCfgMgr( 5945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5945): Loading module APK com.google.android.play.games
W/irrc_jni( 5343): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5343): ~IrrcClient ++ 
D/irrcClient( 5343): ~IrrcClient -- 
W/irrc_jni( 5343): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5343): Blaster closed
D/UEI.SmartControl( 5343): Blaster closed
D/UEI.SmartControl( 5343): Shut down QS...
D/UEI.SmartControl( 5343): Stopped file observer...
,I/art     ( 5945): CheckpointMarkThreadRoots callback created = 0xaaf1b3f0
I/UEI.SmartControl( 5343): QS lib stop result = true
,D/UEI.SmartControl( 5343): QS shutdown complete
,I/NotificationManager( 5956): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5956): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/MediaRouter( 5916): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5956): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
D/ConnectivityService(  838): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5956): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
D/ConnectivityService(  838): dumpNetworkRequest
D/ConnectivityService(  838):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  838):     Requests:
D/ConnectivityService(  838):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):     Lingered:
D/ConnectivityService(  838): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  838): apparently satisfied.  currentScore=60
D/ConnectivityService(  838): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 5945): CM callback handler got msg 524290
W/InstanceID/Rpc( 5956): Found 10006
,V/MusicLeanback( 5916): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/ActivityManager(  838): Process com.uei.lg.quicksetsdk.lite (pid 5343) has died
,I/dex2oat ( 6152): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-265434818.jar --oat-fd=34 --oat-location=/data/data/com.google.android.youtube/cache/ads-265434818.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/PhoneApp( 1746): onTrimMemory: 10
I/PhoneApp( 1746): trim memory
I/BackgroundMemoryTrimmer( 1930): Trimming objects from memory, since app is in the background.
,I/NetworkMonitor( 5916): type=WIFI subType= reason=null isConnected=true
,I/NotificationManager(  838): android: cancelAsUser(-591465577) by android
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5956): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  838): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6173 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager(  838): android: cancelAsUser(-1548111331) by android
I/NetworkMonitor( 5916): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  838): Process com.lge.sync (pid 5711) has died
,I/PhoneApp( 1746): onTrimMemory: 15
I/PhoneApp( 1746): trim memory
I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:42:47.716 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/dex2oat ( 6152): dex2oat took 335.837ms (threads: 4)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,W/ResourcesManager( 6173): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NotificationManager(  838): android: cancelAsUser(-1816247584) by android
,D/eas_req ( 6003): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/ActivityManager(  838): Process com.android.gallery3d (pid 5973) has died
,I/GHttpClientFactory( 5916): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/libc-netbsd( 5956): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5956): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5956): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5956): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  274): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/GoogleURLConnFactory( 1728): Using platform SSLCertificateSocketFactory
I/InitNotificationRingtoneService( 6105): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6105): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/ActivityManager(  838): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6223 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/HolidayIntentService( 6105): onHandleIntent
D/MonthWidgetProvider( 6105): [onReceive]
D/CalendarWidgetProvider( 6105): [onReceive]
D/CalendarWidgetProvider( 6105): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/HolidayDataLoader( 6105): readJsonAsset : holiday.json
D/CalendarTypeController( 6105): [onUpdateAndInitCalendarTime]
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 5956): propertyValue:false
D/libc-netbsd( 5956): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5956): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6241 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     ( 6030): Explicit concurrent mark sweep GC freed 7704(389KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 1.124ms total 160.394ms
,I/GoogleURLConnFactory( 5916): Using platform SSLCertificateSocketFactory
,E/HolidayIntentService( 6105): onHandleIntent:holiday data empty
D/WeekWidgetProvider( 6105): [onReceive]
,D/CalendarWidgetProvider( 6105): [onReceive]
D/CalendarWidgetProvider( 6105): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6105): [onUpdateAndInitCalendarTime]
I/art     ( 5945): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5945): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/WeatherAncestor( 2653): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 22:42:48
D/UpdateThreadPoolManager( 2653): 2 : This is isUpdating : false
D/Weather_cast( 2653): 2 : set auto-update time : 1/26 1:42
,I/HubEmail( 6003): JNI_OnLoad()
I/HubEmail( 6003): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6003): registerNatives()
I/HubEmail( 6003): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6003): registerNativeMethods()
I/HubEmail( 6003): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6003): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/WeatherAncestor( 2653): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 22:42:48
D/WeatherService( 2653): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
V/AudioFlinger(  278): 2081 died, releasing its sessions
V/AudioFlinger(  278):  pid 1746 @ 0
V/AudioFlinger(  278):  pid 3109 @ 1
V/AudioFlinger(  278):  pid 3109 @ 2
,I/AlertUtils( 6105): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/ActivityManager(  838): Process com.lge.music (pid 2081) has died
,I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/ActivityManager(  838): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6267 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2653): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2653): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2653): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/libc-netbsd( 5956): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5956): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
W/Settings( 6003): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6241): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6241): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6241): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,I/NotificationManager( 5956): com.google.android.youtube: cancel(10436) by com.google.android.youtube
I/ActivityManager(  838): Process com.lge.clock (pid 6070) has died
,I/art     (  838): Explicit concurrent mark sweep GC freed 29788(1386KB) AllocSpace objects, 2(74KB) LOS objects, 33% free, 23MB/34MB, paused 2.589ms total 183.788ms
,W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
W/ContextImpl( 6241): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6105): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6105): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/LGDMClient( 6241): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6241): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/TimeService( 6267): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453758168544
D/        ( 6267): TimeServiceNative: User Time to be set is 1453758168544
D/QC-time-services( 6267): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6267): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6267): Lib:time_genoff_operation: pargs->ts_val = 1453758168544
,D/QC-time-services(  323): Daemon: Connection accepted:time_genoff
D/QC-time-services( 6267): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  323): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453758168544
D/QC-time-services(  323): Daemon:genoff_opr: Base = 2, val = 1453758168544, operation = 0
D/QC-time-services(  323): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/8/70 1:44:21
D/QC-time-services(  323): Daemon:Value read from RTC seconds = 13657461000
D/QC-time-services(  323): Daemon:new time 1453758168544 
D/QC-time-services(  323): Daemon: delta 1440100707544 genoff 1440100707544 
D/QC-time-services(  323): Daemon:genoff_persistent_update: Writing genoff = 1440100707544 to memory
D/QC-time-services(  323): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  323): Daemon:time_persistent_memory_opr:Genoff write operation 
I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6301 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AlertUtils( 6105): set default noti to content://media/internal/audio/media/38
D/QC-time-services(  323): Updating the TOD offset
D/QC-time-services(  323): Daemon:genoff_persistent_update: Writing genoff = 1440100707544 to memory
D/QC-time-services(  323): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  323): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  323): Daemon:Update to modem bit set
D/QC-time-services(  323): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  323): Daemon: Base = 2, Value being sent to MODEM = 1124135907544
I/NotificationManager( 5916): com.google.android.music: cancel(1061) by com.google.android.music
I/InitNotificationRingtoneService( 6105): End InitializeAlertRingtoneService.onHandleIntent
E/QC-time-services( 6267): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  323): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  323): Daemon: Time-services: Waiting to acceptconnection
D/LGDMClient( 6241): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6241): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6241): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6241): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6241): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6241): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6241): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6241): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  838): Process com.google.android.music:main (pid 5916) has died
,I/PhoneApp( 1746): onTrimMemory: 15
I/PhoneApp( 1746): trim memory
,I/Gmail   ( 6223): getAccountsCursor
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 5945): Checkin interval check for package: unspecified last checkin: 1453416289192 min interval config: 0 actual interval: 341879566
W/GAV2    ( 6223): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/DriveInitializer( 5945): Awaiting to be initialized
W/DriveInitializer( 5945): Background init thread started
,W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5945): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
I/Gmail   ( 6223): getAccountsCursor
,W/art     ( 6173): Suspending all threads took: 21.495ms
,E/Gmail   ( 6223): Error finding the version of the Email provider.....
E/Gmail   ( 6223): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6223): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6223): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6223): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6223): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6223): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6223): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6223): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6223): We do not support migrating this version of the Email provider.
W/Gmail   ( 6223): Sync started for account: account:61035162
I/art     ( 6173): CheckpointMarkThreadRoots callback created = 0xb0521980
,I/AppUp4:AppBoxCP( 6301): onCreate
,W/AppUp4:DB( 6301):  [AppBoxDatabaseHelper] construct
I/art     ( 6173): CheckpointMarkThreadRoots callback created = 0xb0521960
,I/AppUp4:DB( 6301):  setFingerPrint start
I/AppUp4:DB( 6301):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6301):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6301):  SDK version = 0
I/AppUp4:DB( 6301):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6301): AppBoxApplication onCreate()
W/ActivityManager(  838): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/NetworkStateForAutoUpdateMonitor( 6301): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6301): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6301): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6301): [onReceive] request level :IDLE....
W/DriveInitializer( 5945): Background init thread ended
,I/AppUp4:CustModeStarterReceiver( 6301): onReceive
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AppUp4:CustModeStarterReceiver( 6301): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6223): Observing account changes for notifications
D/AppUp4:CustFacade( 6301): Context : android.app.ReceiverRestrictedContext@35b239d0
,D/AppUp4:CustFacade( 6301): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6301): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6301): begin check event
I/AppUp4:CustModeStarterReceiver( 6301): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 6301): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6301): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6301): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6301): handleAsyncCustNotification do not startCustService
,I/NotificationManager( 5945): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager(  838): android: cancelAsUser(353845882) by android
,I/LgeMiscReceiver( 3109): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3109): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3109): networkInfo.isConnected() = true
D/PhoneState( 3109): setPdpRejectCasuse : false
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6366 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  302): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.266ms
,I/Gmail   ( 6223): notifyAccountChanged
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.022ms
,I/Gmail   ( 6223): getAccountsCursor
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/Gmail   ( 6223): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/System.out( 1728): propertyValue:false
I/Gmail   ( 6223): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.950ms
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6223): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6223): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Gmail   ( 6223): notifyAccountChanged
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Gmail   ( 6223): getAccountsCursor
,D/PhoneMonitor( 6366): Register our PhoneStateListener
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/MobileConnectivityChangeReceiver( 6366): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6366): onReceive CONNECTIVITY_CHANGE networkType=1
D/libc-netbsd( 5956): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5956): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5956): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5956): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  274): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/CheckinService( 5945): Checkin interval check for package: unspecified last checkin: 1453416289192 min interval config: 0 actual interval: 341880283
,V/DownloadManager( 3131): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3131): DownloadService onCreate
,I/DownloadManager( 3131): in removeSpuriousFiles
V/DownloadManager( 3131): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3131): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3131): created cursor android.database.sqlite.SQLiteCursor@2abe9cf on behalf of 3131
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 5956): propertyValue:false
D/libc-netbsd( 5956): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5956): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DownloadManager( 3131): in trimDatabase
V/DownloadManager( 3131): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/PhoneMonitor( 6366): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/DownloadManager( 3131): created cursor android.database.sqlite.SQLiteCursor@2a038265 on behalf of 3131
V/TelephonyAutoProfiling( 6366): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6366): [parse] Load xml
V/TelephonyAutoProfiling( 6366): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6366): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6366): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  838): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6398 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3131): DownloadService onStartCommand
D/libc-netbsd( 5956): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5956): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/DownloadManager( 3131): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3131): created cursor android.database.sqlite.SQLiteCursor@39a753eb on behalf of 3131
I/CheckinService( 5945): Disabling old GoogleServicesFramework version
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/Gmail   ( 6223): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15576, normalSync: true
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,I/CheckinService( 5945): Checking schedule, now: 1453758169660 next: 1453416319141
I/CheckinService( 5945): active receiver: enabled
,D/DrmBroadcastReceiver( 6398): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6398): 1  network is available. Sync DRM Time with NTP
,I/CheckinService( 5945): Preparing to send checkin request
I/EventLogService( 5945): Accumulating logs since 1453757734518
V/DrmService( 6398): Service onCreate
D/WeatherAncestor( 2653): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:42:49
,D/DrmService( 6398): Received new request = 2
V/DownloadManager( 3131): DownloadService onDestroy
D/UpdateThreadPoolManager( 2653): 2 : This is isUpdating : false
I/DrmSntpClient( 6398): Start Sync process
D/DrmSntpClient( 6398): Server : 0
,D/WeatherAncestor( 2653): connectivity changed - connection : true
D/Weather_cast( 2653): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2653): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:42:49
,D/WeatherService( 2653): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6398): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6398): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  274): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
W/art     ( 6173): Attempt to remove local handle scope entry from IRT, ignoring
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6398): propertyValue:false
I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6421 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2653): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2653): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2653): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
I/LGDrmClient( 6398): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  287): eDRM_SetDRMTime +++
I/LGDRM   (  287): [DRM] SET TIME : YR=2016, MON=1, DAY=25
I/LGDRM   (  287): [DRM] SET TIME : HR=21, MIN=42, SEC=48
,V/ILGDrmService(  287): eDRM_SetDRMTime ---
I/DrmSntpClient( 6398): Synched
D/DrmService( 6398): Completed !! request = 2
D/DrmService( 6398): Request count = 0
V/DrmService( 6398): Service onDestroy
D/libc-netbsd( 6173): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6173): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  274): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  274): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
W/ResourcesManager( 6223): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6223): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/art     ( 6173): Suspending all threads took: 12.113ms
,W/ResourcesManager( 6421): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/PhenotypeConfigurator( 1728): Server returned 404
,V/JNIHelp ( 6223): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/art     ( 6173): Suspending all threads took: 9.758ms
,I/CheckinRequestBuilder( 5945): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5945): Failed to find provider info for com.google.android.wearable.settings
W/System  ( 6223): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6223): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6030): Explicit concurrent mark sweep GC freed 2723(109KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 817us total 35.989ms
,I/art     (  838): Explicit concurrent mark sweep GC freed 13928(683KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 3.768ms total 185.296ms
,I/ActivityManager(  838): Process com.lge.email (pid 6003) has died
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,D/ChimeraCfgMgr( 5945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5945): Module APK com.google.android.play.games already loaded
,I/art     ( 6223): CheckpointMarkThreadRoots callback created = 0xaaf1adf0
,D/libc-netbsd( 6223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10053
D/DnsProxyListener(  274): App 10053 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,I/art     ( 6223): CheckpointMarkThreadRoots callback created = 0xb054fde0
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 6223): propertyValue:false
D/libc-netbsd( 6223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     ( 5945): Background sticky concurrent mark sweep GC freed 14683(1204KB) AllocSpace objects, 20(320KB) LOS objects, 9% free, 12MB/14MB, paused 14.849ms total 93.547ms
I/GamesSyncServiceMain( 5945): Found unexpected GCM tag when scheduling; aborting
,I/Babel_SMS( 6421): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6421): MmsConfig.loadMmsSettings
W/GamesSyncServiceMain( 5945): Failed to execute periodic sync, missing client context - aborting
I/Babel_SMS( 6421): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6421): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6421): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6421): MmsConfig.loadFromResources
E/Babel_SMS( 6421): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6421): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/libc-netbsd( 6223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 6421): CheckpointMarkThreadRoots callback created = 0xb042d870
,D/SensorManager( 6421): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6421): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6421): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6421): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6421): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6421): found sensor: LGE Linear Acceleration Sensor, handle=30
,D/SensorManager( 6421): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6421): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6421): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6421): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6421): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6421): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6421): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6421): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6421): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6421): found sensor: Motion Accel, handle=46
I/art     ( 6421): CheckpointMarkThreadRoots callback created = 0xb042d860
,I/NotificationManager( 6173): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
I/NotificationManager(  838): android: cancelAsUser(2) by android
,W/Settings( 6421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
I/Babel_Crash( 6421): startup - clean
I/NotificationManager(  838): android: cancelAsUser(2145784878) by android
,I/Babel   ( 6421): deleted: false for 0
I/art     ( 1728): Explicit concurrent mark sweep GC freed 60856(3MB) AllocSpace objects, 46(759KB) LOS objects, 39% free, 14MB/23MB, paused 4.274ms total 153.975ms
,I/ActivityManager(  838): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6476 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  838): Process com.qualcomm.timeservice (pid 6267) has died
,I/ActivityManager(  838): Process com.android.calendar (pid 6105) has died
,W/art     ( 6421): Suspending all threads took: 8.319ms
,W/AudioCapabilities( 6421): Unsupported mime audio/x-lg-flac
,W/InstanceID/Rpc( 5945): Found 10006
W/AudioCapabilities( 6421): Unsupported mime audio/adpcm
W/AudioCapabilities( 6421): Unsupported mime audio/g726
,W/AudioCapabilities( 6421): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6421): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6421): Unsupported mime video/mjpg
I/ActivityManager(  838): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6493 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/VideoCapabilities( 6421): Unsupported mime video/theora
,I/ActivityManager(  838): Process com.lge.appbox.client (pid 6301) has died
,W/ResourcesManager( 6493): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6493): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/AudioCapabilities( 6421): Unsupported mime audio/evrc
,W/AudioCapabilities( 6421): Unsupported mime audio/qcelp
W/VideoCapabilities( 6421): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6421): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6421): Unsupported mime audio/qcelp
W/AudioCapabilities( 6421): Unsupported mime audio/evrc
I/MultiDex( 6493): VM with version 2.1.0 has multidex support
I/MultiDex( 6493): install
I/MultiDex( 6493): VM has multidex support, MultiDex support library is disabled.
,W/VideoCapabilities( 6421): Unsupported mime video/mp4v-esdp
I/VacuumService( 1728): Vacuum at: now=1453758171524 tag=VacuumService
V/JNIHelp ( 6493): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/VideoCapabilities( 6421): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6421): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6421): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6421): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6421): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6421): onServiceConnected
,W/Babel   ( 6421): Attempted to change video mute state without an active call.
W/ActivityThread( 6493): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6493): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@258991d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6493): Installed default security provider GmsCore_OpenSSL
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6476): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/NotificationManager( 6421): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6421): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6421): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6421): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6421): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,I/NotificationManager( 6493): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6493): com.google.android.gms: cancel(39789) by com.google.android.gms
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
W/ContextImpl( 6476): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6421): propertyValue:false
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6476): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6476): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/art     ( 6493): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6493): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/GAv4    ( 6476): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6476):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6476):   adb logcat -s GAv4
,I/Babel   ( 6421): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 6476): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6476): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6476): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NativeLibraryUtils( 6493): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
I/NotificationManager( 6223): com.google.android.gm: cancel(10436) by com.google.android.gm
,W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=3218554609
I/ActivityManager(  838): Process com.lge.lgdmsclient (pid 6241) has died
,I/BackgroundMemoryTrimmer( 1930): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1746): onTrimMemory: 10
I/PhoneApp( 1746): trim memory
I/GoogleURLConnFactory( 6493): Using platform SSLCertificateSocketFactory
,D/libc-netbsd( 6493): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6493): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6493): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6493): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/System.out( 6493): propertyValue:false
I/WebViewFactory( 6476): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/libc-netbsd( 6493): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6493): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6493): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6493): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/LibraryLoader( 6476): Time to load native libraries: 2 ms (timestamps 1167-1169)
I/LibraryLoader( 6476): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6476): Binding Chromium to main looper Looper (main, tid 1) {1f77038d}
I/LibraryLoader( 6476): Expected native library version number "",actual native library version number ""
I/chromium( 6476): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6476): Initializing chromium process, singleProcess=true
,W/art     ( 6476): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6476): ApplicationContext is null in ApplicationStatus
W/chromium( 6476): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6476): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6476): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6476): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6476): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6476): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6476): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6476): Remote Branch: 
I/Adreno-EGL( 6476): Local Patches: 
I/Adreno-EGL( 6476): Reconstruct Branch: 
V/AudioPolicyService(  278): registerClient() client 0xb3c1bb40, uid 10079
I/NSApplication( 6476): Starting up...
,W/AudioManagerAndroid( 6476): Requires BLUETOOTH permission
I/art     ( 6493): CheckpointMarkThreadRoots callback created = 0xb04ccee0
,I/SyncAdapterService( 6476): Ignoring sync request for non-current account
I/art     ( 6493): CheckpointMarkThreadRoots callback created = 0xb04cced0
,I/ActivityManager(  838): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6573 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  838): Process com.google.android.setupwizard (pid 6366) has died
,I/NotificationManager(  838): android: cancelAsUser(-701419433) by android
I/PeopleSync( 5945): onPerformSync() [5005f081]
,I/art     (  838): Explicit concurrent mark sweep GC freed 36620(1689KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.502ms total 167.222ms
,I/art     ( 6223): Explicit concurrent mark sweep GC freed 7597(288KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 10MB/14MB, paused 609us total 60.324ms
,I/PeopleDatabaseHelper( 5945): cleanUpNonGplusAccounts done.
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6223): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15703, normalSync: true
,I/Gmail   ( 6223): lowestBackward conversation id 0
I/Icing   ( 5945): Storage manager: low false usage 1.74MB avail 2.37GB capacity 4.06GB
,I/PeopleSync( 5945): Setting subscription: result=true [5005f081]
I/PeopleSync( 5945): Starting sync, feed=null [5005f081]
,I/dex2oat ( 6595): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/lowmemorykiller(  243): Error writing /proc/6173/oom_score_adj; errno=22
,I/dex2oat ( 6595): dex2oat took 107.662ms (threads: 4)
,D/charger_monitor(  482): init target 500000
,I/Adreno-EGL( 6493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6493): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6493): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6493): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6493): Remote Branch: 
I/Adreno-EGL( 6493): Local Patches: 
I/Adreno-EGL( 6493): Reconstruct Branch: 
D/charger_monitor(  482): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/Adreno-EGL( 6493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6493): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6493): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6493): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6493): Remote Branch: 
I/Adreno-EGL( 6493): Local Patches: 
I/Adreno-EGL( 6493): Reconstruct Branch: 
,I/ActivityManager(  838): Process com.google.android.apps.plus (pid 6173) has died
,I/BackgroundMemoryTrimmer( 1930): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1746): onTrimMemory: 10
I/PhoneApp( 1746): trim memory
I/ActivityManager(  838): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6610 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  838): battery changed pluggedType: 2
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1980): Disconnected process message: 10, size: 0
D/HeadsetStateMachine( 1980): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
,I/Adreno-EGL( 6493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6493): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6493): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6493): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6493): Remote Branch: 
I/Adreno-EGL( 6493): Local Patches: 
I/Adreno-EGL( 6493): Reconstruct Branch: 
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,I/GAv4-SVC( 5945): Google Analytics 8.4.89 is starting up.
I/GAV2    ( 6223): Thread[GAThread,5,main]: No campaign data found.
,W/ResourcesManager( 6610): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 6030): Explicit concurrent mark sweep GC freed 2787(112KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.923ms total 51.486ms
,W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,E/BaseAppContext( 5945): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,I/WVCdm   (  278): CdmEngine::OpenSession
,W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,I/PeopleSync( 5945): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/WVCdm   (  278): CdmEngine::CloseSession
,I/Icing   ( 5945): updateResources: need to parse f{com.google.android.gms}
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=2843212807
I/art     ( 5945): Background sticky concurrent mark sweep GC freed 4258(303KB) AllocSpace objects, 3(48KB) LOS objects, 2% free, 14MB/14MB, paused 8.629ms total 43.934ms
,I/iu.SyncManager( 5945): SYNC; picasa accounts
,D/NetworkLogImpl( 5945): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5945): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/art     ( 5945): Background sticky concurrent mark sweep GC freed 1483(117KB) AllocSpace objects, 3(48KB) LOS objects, 1% free, 14MB/14MB, paused 8.790ms total 36.697ms
,I/iu.UploadsManager( 5945): num queued entries: 0
I/iu.UploadsManager( 5945): num updated entries: 0
I/iu.SyncManager( 5945): NEXT; no task
D/ConnectivityService(  838): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): ValidatedState{ when=-1ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=-4ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Forcing reevaluation
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  838): Process com.google.android.youtube (pid 5956) has died
D/WearableService( 1728): callingUid 10006, callindPid: 1728
,E/MDM     ( 1728): [101] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5945): Restart initialization of location
D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  838): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6661 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/Icing   ( 5945): Internal init done: storage state 0
,W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
,I/NotificationManager( 6223): com.google.android.gm: cancel(10436) by com.google.android.gm
I/NotificationManager( 6223): com.google.android.gm: cancel(10436) by com.google.android.gm
I/Icing   ( 5945): Post-init done
,W/IcingInternalCorpora( 5945): getNumBytesRead when not calculated.
,D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5945): propertyValue:false
I/DigitalAppWidgetProvider( 6661): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2653): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 22:42:55
,D/UpdateThreadPoolManager( 2653): 2 : This is isUpdating : false
D/Weather_cast( 2653): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2653): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 22:42:55
D/WeatherService( 2653): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2653): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2653): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2653): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Gmail   ( 6223): notifyAccountChanged
I/Gmail   ( 6223): getAccountsCursor
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6223): notifyAccountChanged
,W/Gmail   ( 6223): Sync complete for account: account:61035162
I/NotificationManager(  838): android: cancelAsUser(1479798955) by android
,I/Gmail   ( 6223): getAccountsCursor
W/BaseAppContext( 5945): Using Auth Proxy for data requests.
W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BaseAppContext( 5945): Using Auth Proxy for data requests.
W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  838): android: cancelAsUser(-379682945) by android
E/MDM     ( 1728): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  838): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6692 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LocationInitializer( 5945): Restart initialization of location
,D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
,I/MusicStore( 6692): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6692): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6692): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6692): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6692): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6692): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6692): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6692): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6692): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23dbfbec: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6692): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6692): GMSCore installation verified
I/ConfigStore( 6692): Config Database version: 1
,I/Icing   ( 5945): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,I/art     (  838): Explicit concurrent mark sweep GC freed 26351(1274KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.324ms total 155.472ms
,I/Icing   ( 5945): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
I/art     ( 6030): Explicit concurrent mark sweep GC freed 2926(111KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 986us total 33.068ms
,I/MediaRouter( 6692): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 6692): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6692): Using platform SSLCertificateSocketFactory
I/art     ( 6692): CheckpointMarkThreadRoots callback created = 0xb042d3f0
I/MusicLifecycle( 6692): Sync started
I/NetworkMonitor( 6692): type=WIFI subType= reason=null isConnected=true
,I/art     ( 6692): CheckpointMarkThreadRoots callback created = 0xb042d3d0
,I/NetworkMonitor( 6692): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 6692): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6692): Using platform SSLCertificateSocketFactory
I/NotificationManager( 6692): com.google.android.music: cancel(1061) by com.google.android.music
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  838): android: cancelAsUser(2) by android
D/libc-netbsd( 6692): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6692): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6692): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6692): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10081
D/DnsProxyListener(  274): App 10081 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6692): propertyValue:false
,I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): L3 Terminate.
D/libc-netbsd( 6692): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6692): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/PeopleSync( 5945): Sync finished, successful=true, took 2434ms
,I/PeopleContactsSync( 5945): CP2 sync start [5005f081]
,I/PeopleContactsSync( 5945): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
I/PeopleContactsSync( 5945): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/libc-netbsd( 6692): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6692): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 5945): Explicit concurrent mark sweep GC freed 16407(1217KB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 13MB/23MB, paused 1.759ms total 73.268ms
I/CheckinRequestBuilder( 5945): Classify the device as Phone.
,W/SQLiteConnectionPool( 5945): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/PeopleContactsSync( 5945): CP2 cleanup done, kept= duration=127 ms
,I/PeopleContactsSync( 5945): ===CP2 sync finished, success=true, time=141,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
I/PeopleSync( 5945): ***Sync finished***, duration: 3858 [5005f081]
,D/ChimeraCfgMgr( 5945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5945): Module APK com.google.android.play.games already loaded
,I/NotificationManager(  838): android: cancelAsUser(148851818) by android
W/PlaySystemBroadcastReceiver( 5945): Processed handlePeopleChanged at 125587
,D/ChimeraCfgMgr( 5945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5945): Module APK com.google.android.play.games already loaded
,I/MusicSyncAdapter( 6692): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 6692): Periodic update
,D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5945): propertyValue:false
E/Auth.Api.Credentials( 5945): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  838): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=6751 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  838): android: cancelAsUser(-591465577) by android
,D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/BaseAppContext( 5945): Using Auth Proxy for data requests.
W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,I/CheckinTask( 5945): Sending checkin request (10798 bytes)
,W/MusicApiClient( 6692): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 6692): Sync ended
I/NotificationManager(  838): android: cancelAsUser(-1123058983) by android
,W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,I/GoogleURLConnFactory( 5945): Using platform SSLCertificateSocketFactory
W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,W/BaseAppContext( 5945): Using Auth Proxy for data requests.
W/BaseAppContext( 5945): Using Auth Proxy for data requests.
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 5945): Using Auth Proxy for data requests.
,I/NotificationManager(  838): android: cancelAsUser(1500439826) by android
I/NotificationManager(  838): android: cancelAsUser(2) by android
D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  838): Start proc com.lge.qmemoplus for service com.lge.qmemoplus/.network.googledrive.DriveSyncService: pid=6771 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/ResourcesManager( 6771): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  838): Process com.google.android.apps.magazines (pid 6476) has died
,E/App     ( 6771): [App][onCreate()] 4.40.23
I/CheckinResponseProcessor( 5945): From server: 7 gservices updates and 2 deletes
,D/Finsky  ( 6751): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/CertBlacklister(  838): Certificate blacklist changed, updating...
,I/CertBlacklister(  838): Certificate blacklist updated
,I/GservicesProvider( 6030): main difference update completed
,I/CheckinRequestBuilder( 5945): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5945): Failed to find provider info for com.google.android.wearable.settings
W/DataBroker( 5945): No player ID found and calling context is not the dest app
,D/AccountManager( 6771): setSyncFrequency
,I/art     ( 6030): Explicit concurrent mark sweep GC freed 8783(432KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 10.930ms total 43.129ms
,D/DriveSyncService( 6771): onCreate
,D/DriveSyncService( 6771): onBind
,D/Finsky  ( 6751): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/DriveSyncAdapter( 6771): onPerformSync() START
D/DriveSyncAdapter( 6771): Not added account. Stop
I/NotificationManager(  838): android: cancelAsUser(1312559638) by android
,W/Settings( 6751): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6751): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6751): com.android.vending: cancel(-1050172287) by com.android.vending
I/ActivityManager(  838): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6819 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 308us total 22.438ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 21ms
,I/ActivityManager(  838): Process com.android.chrome (pid 6573) has died
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.131ms
,V/DownloadManager( 3131): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3131): created cursor android.database.sqlite.SQLiteCursor@12aedfe1 on behalf of 6751
,I/NotificationManager( 5945): com.google.android.gms: cancel(10436) by com.google.android.gms
,W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/art     (  838): Explicit concurrent mark sweep GC freed 27599(1201KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 1.854ms total 155.597ms
,I/CheckinRequestBuilder( 5945): Classify the device as Phone.
I/CheckinTask( 5945): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/AppConfig( 6819): Total System Memory = 906309632
I/GalleryUtils( 6819): Application Heap = 96 MB
,D/Ads     ( 6751): Skipping gmscore version check
I/AppConfig( 6819): App Tier : NOT_DEF
I/CheckinService( 5945): Checking schedule, now: 1453758178308 next: 1454285427284
D/Finsky  ( 6751): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/CheckinService( 5945): active receiver: disabled
D/Finsky  ( 6751): [1] Libraries$2.run: Finished loading 1 libraries.
,D/SystemHelper( 6819): region [EU], country [EU], operator [OPEN], sub-operator []
,D/Finsky  ( 6751): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/charger_monitor(  482): init target 500000
,I/ActivityManager(  838): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6844 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,D/CheckinService( 5945): Recording last checkin time for package unspecified as 1453758178398
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/charger_monitor(  482): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
D/LEDHandler( 1800): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
D/HeadsetStateMachine( 1980): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/NotificationManager(  838): android: cancelAsUser(-1597574061) by android
,I/MusicLeanback( 6692): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6692): Stop autocaching.
D/Finsky  ( 6751): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6692): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6692): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
,I/ActivityManager(  838): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6878 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/RemindersSync( 5945): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=760:priority=5:group=main]
I/NotificationManager(  838): android: cancelAsUser(898701380) by android
,E/UpdateRequestReceiver( 6878): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6878): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6878): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6878): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  838): Killing 6398:com.lge.drmservice/u0a51 (adj 15): empty #11
I/art     ( 6030): Explicit concurrent mark sweep GC freed 4295(192KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.380ms total 30.844ms
,W/libprocessgroup(  838): failed to open /acct/uid_10051/pid_6398/cgroup.procs: No such file or directory
,W/BaseAppContext( 1728): Using Auth Proxy for data requests.
,E/BaseAppContext( 1728): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/GservicesUpdateTask( 1930): Updating Gservices keys
,D/Finsky  ( 6751): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  838): RTC_WAKEUP set : Alarm{231257fd type 0 when 1453758178942 com.android.vending} when 1453758178942
I/art     ( 5945): Explicit concurrent mark sweep GC freed 32625(2MB) AllocSpace objects, 24(406KB) LOS objects, 40% free, 15MB/25MB, paused 1.877ms total 118.348ms
,I/CheckinService( 5945): Checkin interval check for package: unspecified last checkin: 1453758178398 min interval config: 0 actual interval: 625
I/CheckinService( 5945): Checking schedule, now: 1453758179045 next: 1454285427284
I/CheckinService( 5945): active receiver: disabled
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 47177(2MB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 14MB/23MB, paused 5.600ms total 118.420ms
,I/SystemUpdateService( 5945): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SystemUpdateService( 5945): onCreate
,I/NotificationManager(  838): android: cancelAsUser(2) by android
D/SystemUpdateService( 5945): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 5945): cancelUpdate (empty URL)
I/SystemUpdateService( 5945): active receiver: disabled
,I/NotificationManager( 5945): com.google.android.gms: cancel(2130838165) by com.google.android.gms
I/NotificationManager( 5945): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,I/NotificationManager(  838): android: cancelAsUser(2126026182) by android
,I/art     ( 6030): Explicit concurrent mark sweep GC freed 2879(112KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.125ms total 30.171ms
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
I/NotificationManager(  838): android: cancelAsUser(2145784878) by android
D/SystemUpdateService( 5945): onDestroy
,D/libc-netbsd( 6751): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6751): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6751): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6751): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6751): propertyValue:false
D/libc-netbsd( 6751): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6751): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/DynamiteModule( 5945): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5945): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 5945): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 5945): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 5945): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 5945): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5945): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5945): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5945): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5945): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5945): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 5945): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 5945): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 5945): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 5945): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5945): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 5945): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 5945): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 5945): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 5945): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 5945): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 5945): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 5945): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 5945): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 5945): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 5945): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 5945): 		... 17 more
E/DynamiteModule( 5945): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 5945): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DynamiteModule( 5945): Selected local version of com.google.android.gms.flags
I/PhenotypeConfigurator( 1728): Scheduling Phenotype for one-off execution 3352 seconds from now (1453758179550)
,I/art     ( 6610): CheckpointMarkThreadRoots callback created = 0xb042df20
,D/GetConfigurationSnapshotOperation( 1728): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/art     ( 6610): CheckpointMarkThreadRoots callback created = 0xaafa3290
I/PhenotypeFlagCommitter( 1728): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1728): Using platform SSLCertificateSocketFactory
I/art     (  838): Explicit concurrent mark sweep GC freed 23804(1094KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.297ms total 159.962ms
,D/libc-netbsd( 6751): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6751): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  838): Process com.google.android.talk (pid 6421) has died
,I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  838): Reconfiguring input devices.  changes=0x00000010
I/art     ( 6030): Explicit concurrent mark sweep GC freed 2927(115KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 2.819ms total 79.761ms
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[LGHome]EVENT( 1872): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/art     ( 5945): Explicit concurrent mark sweep GC freed 13437(832KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 15MB/25MB, paused 1.902ms total 111.310ms
,I/[LGHome]LGPlusHomeDBManager( 1872): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1872): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1872): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  838): Handling package changes for user 0
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/SystemEventReceiver( 5945): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 5945): Updating ocr activity enabled=false
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1728): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=343120508, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
I/GCoreUlr( 1728): DispatchingService.onCreate()
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 1728): propertyValue:false
I/ActivityManager(  838): Process com.lge.clock (pid 6661) has died
I/GCoreUlr( 1728): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/ActivityManager(  838): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,I/GCoreUlr( 1728): Unbound from all location providers
I/GCoreUlr( 1728): Place inference reporting - stopped
D/OcrModelManager( 5945): Updating downloaded model state (gservices changed)
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationService(  838): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  838): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  838): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  838): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{2619aa3f type 2 when 129127 com.google.android.gms} when 129127
D/WeatherService( 2653): 2 : TimeTick Intent has been received, Time(hour:min:sec) 22:43:0
D/WeatherService( 2653): 2 : TimeTick Intent And Screen On
D/WeatherService( 2653): 2 : SDK version : 21
,I/NotificationManager(  838): android: cancelAsUser(2) by android
W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2653): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2653): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2653): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2653): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2653): 2 : This is isUpdating : false
D/WeatherService( 2653): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2653): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2653): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2653): 2 : Fixed theme : optimus
D/WeatherReflect( 2653): 2 : Map key string is -2
,D/lim     ( 2653): 2 : time = 22:43
I/WeatherReflect( 2653): Model Name : LG-D722
D/WeatherTheme( 2653): 2 : Different view - status_min_formatted : 42 != 43
D/WeatherTheme( 2653): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2653): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2653): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2653): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2653): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2653): currentPackage=com.lge.sizechangable.weather.theme.optimus
,W/ResourcesManager(  838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/qtaguid ( 6751): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6751): Untagging socket 41 failed errno=-22
D/Weather4x2_optimus( 2653): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2653): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2653): forecast size is 0
,D/Theme   ( 2653): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2653): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2653): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2653): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2653): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2653): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
W/NetworkManagementSocketTagger( 6751): untagSocket(41) failed with errno -22
D/Theme   ( 2653): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2653): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2653): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2653): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2653): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2653): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2653): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2653): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2653): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2653): url is : null
D/Theme   ( 2653): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2653): EnableTheme(home): com.lge.launcher2.theme.optimus
,D/Theme   ( 2653): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2653): 2 : update view, appWidgetId: 2
D/WeatherService( 2653): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 22:43:0
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Finsky  ( 6751): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 30434(1837KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 14MB/23MB, paused 23.188ms total 152.962ms
,W/ResourceType(  838): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/art     ( 6030): Explicit concurrent mark sweep GC freed 2554(101KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.011ms total 27.642ms
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  838): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6951 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1872): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  838): Process com.google.android.gm (pid 6223) has died
,I/PhoneApp( 1746): onTrimMemory: 10
,I/PhoneApp( 1746): trim memory
I/BackgroundMemoryTrimmer( 1930): Trimming objects from memory, since app is in the background.
W/ResourcesManager( 6951): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6951): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/[LgeWidgetLib]LgeAppWidgetHostView( 1872): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1872): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/NotificationManager(  838): android: cancelAsUser(-1874035846) by android
,I/NotificationManager(  838): android: cancelAsUser(1222422273) by android
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/GCM     ( 1728): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/GCoreUlr( 1728): DispatchingService.onDestroy()
I/GCoreUlr( 1728): Stopping handler for UlrDispSvcFast
I/System.out( 1728): propertyValue:false
I/MultiDex( 6951): VM with version 2.1.0 has multidex support
I/MultiDex( 6951): install
I/MultiDex( 6951): VM has multidex support, MultiDex support library is disabled.
I/GCoreUlr( 1728): Unbound from all location providers
I/GCoreUlr( 1728): Place inference reporting - stopped
V/BackupManagerService(  838): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/NotificationManager(  838): android: cancelAsUser(2) by android
V/BackupManagerService(  838): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1f766988
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreNlp( 1728): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  838): applying state to connected service
,I/NotificationManager(  838): android: cancelAsUser(2) by android
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,I/PeopleSync( 5945): onPerformSync() [5005f081]
V/JNIHelp ( 6951): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  838): android: cancelAsUser(-591465577) by android
,W/ActivityThread( 6951): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6951): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@258991d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6951): Installed default security provider GmsCore_OpenSSL
,I/qtaguid ( 6751): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6751): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6751): untagSocket(41) failed with errno -22
,I/ActivityManager(  838): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6979 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/NotificationManager( 6951): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6951): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6951): Reading stored module config
,D/ChimeraCfgMgr( 6951): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/CAR.SERVICE( 6951): Connecting to CarCallService...
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GCoreUlr( 1728): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1728): DispatchingService.onCreate()
I/art     ( 6951): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6951): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7003 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/NativeLibraryUtils( 6951): Install completed successfully. count=14 extracted=0
,I/art     ( 6751): CheckpointMarkThreadRoots callback created = 0xaae7b5a0
,D/CAR.SERVICE( 6951): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6951): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6951): Creating a new PhoneAdapter instance
W/ActivityManager(  838): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6951): setListener: com.google.android.gms.car.dn@89e3690
,W/ActivityManager(  838): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6951): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6951): Starting CarCallService with initial phone null
I/art     ( 6751): CheckpointMarkThreadRoots callback created = 0xb042d660
I/GCoreUlr( 1728): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/NotificationManager( 6951): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6951): Package validated; name: com.android.vending
,D/PhoneMonitor( 7003): Register our PhoneStateListener
I/NotificationManager( 6751): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6751): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/art     ( 6030): Explicit concurrent mark sweep GC freed 3223(128KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 7.338ms total 66.977ms
,V/SetupWizard( 7003): Connected to Gservices successfully
,I/GAv4    ( 6979): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6979):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6979):   adb logcat -s GAv4
,W/GAv4    ( 6979): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/PeopleSync( 5945): Setting subscription: result=true [5005f081]
,D/PhoneMonitor( 7003): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7003): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7003): [parse] Load xml
W/GAv4    ( 6979): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
V/TelephonyAutoProfiling( 7003): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7003): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
W/GAv4    ( 6979): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/PhoneMonitor( 7003): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/AnalyticsTrackerProxyImpl( 6979): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,D/GCM     ( 1728): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/NotificationManager(  838): android: cancelAsUser(148851818) by android
,I/art     (  838): Explicit concurrent mark sweep GC freed 32746(1640KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 2.313ms total 172.377ms
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6979): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
,W/GeofencerStateMachine( 1728): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1728): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,W/ResourcesManager( 6979): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6979): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6979): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6979): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 6979): CheckpointMarkThreadRoots callback created = 0xb050fa70
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/JNIHelp ( 6979): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 6979): CheckpointMarkThreadRoots callback created = 0xb050fa50
I/GCoreUlr( 1728): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6692): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
D/WearableService( 1728): callingUid 10006, callindPid: 1728
,I/GCoreUlr( 1728): Unbound from all location providers
I/GCoreUlr( 1728): Place inference reporting - stopped
,W/System  ( 6979): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6979): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1728): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/ctxmgr  ( 1728): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,I/GCoreUlr( 1728): DispatchingService.onDestroy()
I/GCoreUlr( 1728): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1728): Unbound from all location providers
I/GCoreUlr( 1728): Place inference reporting - stopped
,E/ctxmgr  ( 1728): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,E/GmsUtils( 6692): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6692): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/WifiServiceImplEx(  838): acquireWifiLock pid=6979, uid=10058, packageName=com.google.android.apps.docs, tag=BaseSyncManager
I/NotificationManager( 6979): com.google.android.apps.docs: cancel(1) by com.google.android.apps.docs
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
W/Flag    ( 6979): Duration spec must be at least 2 characters long
,D/libc-netbsd( 6979): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6979): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6979): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6979): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10058
D/DnsProxyListener(  274): App 10058 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/art     ( 1728): Explicit concurrent mark sweep GC freed 52305(2MB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 15MB/25MB, paused 1.664ms total 138.671ms
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6979): propertyValue:false
I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7057 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/libc-netbsd( 6979): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6979): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/NotificationManager(  838): android: cancelAsUser(-1548111331) by android
W/ResourcesManager( 7057): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/NotificationManager(  838): android: cancelAsUser(898701380) by android
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
I/qtaguid ( 6751): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6751): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6751): untagSocket(41) failed with errno -22
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Babel_SMS( 7057): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7057): MmsConfig.loadMmsSettings
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Babel_SMS( 7057): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7057): MmsConfig.loadFromDatabase
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/Finsky  ( 6751): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.marvin.talkback to true
E/Babel_SMS( 7057): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7057): MmsConfig.loadFromResources
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Finsky  ( 6751): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.marvin.talkback from  to d_AAAAAAADF8w=
E/Babel_SMS( 7057): canonicalizeMccMnc: invalid mccmnc nullnull
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Babel_SMS( 7057): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/SensorManager( 7057): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7057): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7057): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7057): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7057): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7057): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7057): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7057): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7057): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7057): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7057): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7057): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7057): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7057): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7057): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7057): found sensor: Motion Accel, handle=46
,W/art     ( 7057): Suspending all threads took: 8.424ms
,I/art     ( 7057): CheckpointMarkThreadRoots callback created = 0xb042d880
,W/Settings( 7057): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7057): startup - clean
I/art     ( 7057): CheckpointMarkThreadRoots callback created = 0xb042d860
,I/NotificationManager(  838): android: cancelAsUser(-1878923137) by android
I/Babel   ( 7057): deleted: false for 0
,I/NotificationManager(  838): android: cancelAsUser(2) by android
W/ResourcesManager( 6751): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6751): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,I/NotificationManager(  838): android: cancelAsUser(2) by android
W/ResourcesManager( 6751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/AudioCapabilities( 7057): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7057): Unsupported mime audio/adpcm
W/AudioCapabilities( 7057): Unsupported mime audio/g726
W/AudioCapabilities( 7057): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7057): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7057): Unsupported mime video/mjpg
W/VideoCapabilities( 7057): Unsupported mime video/theora
,I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7092 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/Finsky  ( 6751): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  838): RTC_WAKEUP set : Alarm{2b977f97 type 0 when 1453758183873 com.android.vending} when 1453758183873
,D/libc-netbsd( 6979): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6979): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6979): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6979): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10058
D/DnsProxyListener(  274): App 10058 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
W/AudioCapabilities( 7057): Unsupported mime audio/evrc
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6979): propertyValue:false
W/AudioCapabilities( 7057): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7057): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7057): Unsupported mime audio/qcelp
W/AudioCapabilities( 7057): Unsupported mime audio/evrc
D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 6979): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6979): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AppUp4:AppBoxCP( 7092): onCreate
W/AppUp4:DB( 7092):  [AppBoxDatabaseHelper] construct
W/VideoCapabilities( 7057): Unsupported mime video/mp4v-esdp
,I/AppUp4:DB( 7092):  setFingerPrint start
I/AppUp4:DB( 7092):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/ActivityManager(  838): Process com.lge.qmemoplus (pid 6771) has died
D/DeviceConnectionService( 1728): client connected with version: 8296000
,I/VideoCapabilities( 7057): Unsupported profile 4 for video/mp4v-es
,I/AppUp4:DB( 7092):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7092):  SDK version = 0
I/AppUp4:DB( 7092):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7092): AppBoxApplication onCreate()
W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
D/Finsky  ( 6751): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6751): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  838): Killing 6819:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:CustModeStarterReceiver( 7092): onReceive
I/AppUp4:CustModeStarterReceiver( 7092): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7092): Context : android.app.ReceiverRestrictedContext@94441cd
D/AppUp4:CustFacade( 7092): isCustomizationCompleted : false
E/DefaultHttpIssuer( 6979): Attempt to consume entity of HttpIssuer when no request is executing.
,E/DefaultHttpIssuer( 6979): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 6979): java.io.IOException
E/DefaultHttpIssuer( 6979): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 6979): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 6979): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 6979): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 6979): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 6979): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 6979): 	at dlr.run(PG:3031)
E/BaseSyncManager( 6979): IOException
E/BaseSyncManager( 6979): java.io.IOException: stream was reset: CANCEL
E/BaseSyncManager( 6979): 	at hzd.b(PG:145)
E/BaseSyncManager( 6979): 	at hya.b(PG:104)
E/BaseSyncManager( 6979): 	at hxn.d(PG:917)
E/BaseSyncManager( 6979): 	at hxn.a(PG:95)
E/BaseSyncManager( 6979): 	at hxn$a.a(PG:902)
E/BaseSyncManager( 6979): 	at hvz.a(PG:50089)
E/BaseSyncManager( 6979): 	at hvz$a.a(PG:230)
E/BaseSyncManager( 6979): 	at hvz.a(PG:3201)
E/BaseSyncManager( 6979): 	at clz.a(PG:127)
E/BaseSyncManager( 6979): 	at cjr.a(PG:47)
E/BaseSyncManager( 6979): 	at cjq.a(PG:22)
E/BaseSyncManager( 6979): 	at cjs.a(PG:68)
E/BaseSyncManager( 6979): 	at cjw.b(PG:92)
E/BaseSyncManager( 6979): 	at cjw.a(PG:80)
E/BaseSyncManager( 6979): 	at cju.b(PG:5140)
E/BaseSyncManager( 6979): 	at cju.a(PG:1096)
E/BaseSyncManager( 6979): 	at dlh.b(PG:14062)
E/BaseSyncManager( 6979): 	at dlh.a(PG:140)
E/BaseSyncManager( 6979): 	at dqo.a(PG:224)
E/BaseSyncManager( 6979): 	at dlt.run(PG:9618)
E/BaseSyncManager( 6979): 	at dlr.run(PG:3031)
D/WifiServiceImplEx(  838): releaseWifiLock pid=6979, uid=10058, packageName=com.google.android.apps.docs
W/libprocessgroup(  838): failed to open /acct/uid_10023/pid_6819/cgroup.procs: No such file or directory
,D/AppUp4:CustFacade( 7092): isSimDevice : true
I/NotificationManager(  838): android: cancelAsUser(-1488629395) by android
D/AppUp4:CustModeStarterReceiver( 7092): begin check event
I/AppUp4:CustModeStarterReceiver( 7092): Event For Nothing, skip.
I/ActivityManager(  838): Killing 6844:com.google.android.partnersetup/u0a9 (adj 15): empty #11
I/NotificationManager( 6979): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager(  838): Killing 6878:com.google.android.configupdater/u0a3 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10003/pid_6878/cgroup.procs: No such file or directory
,W/libprocessgroup(  838): failed to open /acct/uid_10009/pid_6844/cgroup.procs: No such file or directory
I/vclib   ( 7057): onServiceConnected
W/Babel   ( 7057): Attempted to change video mute state without an active call.
,I/NotificationManager( 7057): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7057): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7057): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  838): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7121 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
V/JNIHelp ( 7057): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7121): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7121): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7121): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,W/System  ( 7057): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7057): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  838): Process com.google.android.gms.unstable (pid 6493) has died
I/NotificationManager( 7057): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 7121): Total System Memory = 906309632
,I/GalleryUtils( 7121): Application Heap = 96 MB
,I/AppConfig( 7121): App Tier : NOT_DEF
,D/SystemHelper( 7121): region [EU], country [EU], operator [OPEN], sub-operator []
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 133450712662; DSPS: 4471483; Offset : -3015813733
I/ActivityManager(  838): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7143 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7143): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7143): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7143): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7143): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7143): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
I/SystemConfig( 7143): BUILD Country: EU
,I/SystemConfig( 7143): BUILD Operator: OPEN
D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager(  838): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7168 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  838): Killing 6610:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/ConnectivityService(  838): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@118f5fdd)
,D/ConnectivityService(  838): dumpNetworkRequest
D/ConnectivityService(  838):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  838):     Requests:
D/ConnectivityService(  838):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):     Lingered:
,D/ConnectivityService(  838): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  838): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/libprocessgroup(  838): failed to open /acct/uid_10086/pid_6610/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Process com.google.android.gms (pid 5945) has died
,I/SystemConfig( 7143): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7143): existFile = false
I/SystemConfig( 7143): canReadFile = false
I/SystemConfig( 7143): systemFeature RCS result false
D/SystemConfig( 7143): refreshRcsSupport() :false
I/LockScreenSettings( 7168): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7168): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7168): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7168): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7168): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7168): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  838): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7195 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.747ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.777ms
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 22.793ms
,W/ResourcesManager( 7195): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1930): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  838): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=7226 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 6692:com.google.android.music:main/u0a81 (adj 15): empty #11
I/UpdateIcingCorporaServi( 1930): UpdateCorporaTask done [took 84 ms] updated apps [took 84 ms] 
W/libprocessgroup(  838): failed to open /acct/uid_10081/pid_6692/cgroup.procs: No such file or directory
,W/ResourcesManager( 7226): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7226): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7226): VM with version 2.1.0 has multidex support
I/MultiDex( 7226): install
,I/MultiDex( 7226): VM has multidex support, MultiDex support library is disabled.
,I/art     (  838): Explicit concurrent mark sweep GC freed 33581(1667KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 2.739ms total 154.188ms
,V/JNIHelp ( 7226): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7226): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7226): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@314523cb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7226): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7226): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7226): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 7226): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 7226): Null package name or gms related package.  Ignoreing.
E/MDM     ( 1728): [101] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 7226): Restart initialization of location
,D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  838): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=7259 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7226): Background sticky concurrent mark sweep GC freed 26650(1405KB) AllocSpace objects, 6(96KB) LOS objects, 8% free, 10MB/11MB, paused 10.164ms total 168.146ms
,I/art     ( 7226): CheckpointMarkThreadRoots callback created = 0xb05473c0
I/art     ( 7226): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7226): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7226): Install completed successfully. count=14 extracted=0
,I/Icing   ( 7226): Storage manager: low false usage 1.74MB avail 2.37GB capacity 4.06GB
,I/art     ( 7226): CheckpointMarkThreadRoots callback created = 0xb05473b0
,I/art     ( 7226): Background partial concurrent mark sweep GC freed 2817(317KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/17MB, paused 8.792ms total 110.596ms
,I/art     ( 7226): Background sticky concurrent mark sweep GC freed 1076(91KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 10MB/17MB, paused 6.747ms total 44.074ms
,W/IcingInternalCorpora( 7226): getNumBytesRead when not calculated.
,I/art     ( 7226): Background partial concurrent mark sweep GC freed 2285(181KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 10MB/18MB, paused 8.661ms total 58.672ms
,I/MusicStore( 7259): Database version: 120
W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7259): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  838): Process com.google.android.apps.docs (pid 6979) has died
,D/CAR.SERVICE( 6951): mConnectedToCar = false, abort
E/ActivityThread( 6951): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2895d078 that was originally bound here
E/ActivityThread( 6951): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2895d078 that was originally bound here
E/ActivityThread( 6951): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6951): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6951): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6951): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6951): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6951): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6951): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6951): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6951): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6951): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6951): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6951): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6951): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6951): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6951): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6951): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6951): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6951): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6951): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6951): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6951): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6951): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6951): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2d095d53 that was originally bound here
E/ActivityThread( 6951): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2d095d53 that was originally bound here
E/ActivityThread( 6951): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6951): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6951): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6951): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6951): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6951): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6951): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6951): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6951): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6951): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6951): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6951): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6951): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6951): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6951): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6951): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6951): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6951): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6951): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6951): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6951): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  838): Unbind failed: could not find connection for android.os.BinderProxy@32e6bbfe
I/Icing   ( 7226): updateResources: need to parse f{com.google.android.gms}
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7259): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7259): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7259): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7259): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7259): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Icing   ( 7226): Internal init done: storage state 0
,I/NotificationManager( 7226): com.google.android.gms: cancel(10436) by com.google.android.gms
W/ActivityThread( 7259): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7259): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23dbfbec: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7259): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7259): GMSCore installation verified
,I/ConfigStore( 7259): Config Database version: 1
,I/Icing   ( 7226): Post-init done
,I/Icing   ( 7226): updateResources: need to parse f{com.google.android.gms}
,I/art     ( 6030): Explicit concurrent mark sweep GC freed 2839(114KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 443us total 31.709ms
,I/MediaRouter( 7259): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 7259): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7259): type=WIFI subType= reason=null isConnected=true
,I/MusicLeanback( 7259): Stop autocaching.
,I/MusicLeanback( 7259): Stop autocaching.
D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=343120508 [*alarm*], flags=0x0
I/MusicLeanback( 7259): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7259): Stop autocaching.
D/Finsky  ( 6751): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
D/Finsky  ( 6751): [790] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/MusicLeanback( 7259): Stop autocaching.
,I/GHttpClientFactory( 7259): Using our fixed implementation of GMSCore's GoogleHttpClient
E/MDM     ( 1728): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/GoogleURLConnFactory( 7259): Using platform SSLCertificateSocketFactory
D/Finsky  ( 6751): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
D/LocationInitializer( 7226): Restart initialization of location
,D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 7259): CheckpointMarkThreadRoots callback created = 0xaaf1a580
,I/NotificationManager(  838): android: cancelAsUser(2) by android
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1728): No location to return for getLastLocation()
,W/FusedLocationProvider( 1728): location=null
I/art     ( 7259): CheckpointMarkThreadRoots callback created = 0xaaf1a550
,D/libc-netbsd( 6751): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6751): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6751): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6751): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6751): propertyValue:false
,I/NotificationManager( 7259): com.google.android.music: cancel(1061) by com.google.android.music
,E/GmsUtils( 7259): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 7259): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Icing   ( 7226): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 7226): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 7226): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/PackageSettings(  838): Skipping PackageSetting{1647252d com.example.hello/10317} due to missing metadata
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  838): Killing 7003:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10038/pid_7003/cgroup.procs: No such file or directory
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-68 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:43:11.804 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MusicLeanback( 7259): Conditions not met for autocaching. okToAttempt=false
E/GmsUtils( 7259): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7259): Stop autocaching.
,E/GmsUtils( 7259): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  838): Killing 7092:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10011/pid_7092/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:43:17.834 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/AlarmManager(  838): RTC_WAKEUP set : Alarm{3f07129c type 0 when 1453758197812 com.android.vending} when 1453758197812
D/Finsky  ( 6751): [780] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6751): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/PowerManagerService(  838): ALS enabled for SRE
,D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28004 ms ago)
D/qdlights(  838): set_light_backlight: 251
,D/qdlights(  838): set_light_backlight: 248
,D/qdlights(  838): set_light_backlight: 245
,D/qdlights(  838): set_light_backlight: 241
,D/qdlights(  838): set_light_backlight: 238
,D/qdlights(  838): set_light_backlight: 235
,D/qdlights(  838): set_light_backlight: 231
,D/qdlights(  838): set_light_backlight: 228
,D/qdlights(  838): set_light_backlight: 225
,D/qdlights(  838): set_light_backlight: 221
,D/qdlights(  838): set_light_backlight: 218
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  838): set_light_backlight: 215
,D/qdlights(  838): set_light_backlight: 211
,D/qdlights(  838): set_light_backlight: 208
,D/qdlights(  838): set_light_backlight: 205
,D/qdlights(  838): set_light_backlight: 201
,D/qdlights(  838): set_light_backlight: 198
,D/qdlights(  838): set_light_backlight: 195
,D/qdlights(  838): set_light_backlight: 191
,D/qdlights(  838): set_light_backlight: 188
,D/qdlights(  838): set_light_backlight: 185
,D/qdlights(  838): set_light_backlight: 181
,D/qdlights(  838): set_light_backlight: 178
,D/qdlights(  838): set_light_backlight: 175
,D/qdlights(  838): set_light_backlight: 171
,D/qdlights(  838): set_light_backlight: 168
,D/qdlights(  838): set_light_backlight: 165
,D/qdlights(  838): set_light_backlight: 161
,D/qdlights(  838): set_light_backlight: 158
,D/qdlights(  838): set_light_backlight: 155
,D/qdlights(  838): set_light_backlight: 151
,D/qdlights(  838): set_light_backlight: 148
,D/qdlights(  838): set_light_backlight: 145
,D/qdlights(  838): set_light_backlight: 141
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
D/qdlights(  838): set_light_backlight: 138
,D/qdlights(  838): set_light_backlight: 135
,D/qdlights(  838): set_light_backlight: 131
,D/qdlights(  838): set_light_backlight: 128
,D/qdlights(  838): set_light_backlight: 125
,D/qdlights(  838): set_light_backlight: 121
,D/qdlights(  838): set_light_backlight: 118
,D/qdlights(  838): set_light_backlight: 115
,D/qdlights(  838): set_light_backlight: 111
,D/qdlights(  838): set_light_backlight: 108
,D/qdlights(  838): set_light_backlight: 105
,D/qdlights(  838): set_light_backlight: 101
,D/qdlights(  838): set_light_backlight: 98
,D/qdlights(  838): set_light_backlight: 95
,D/qdlights(  838): set_light_backlight: 91
,D/qdlights(  838): set_light_backlight: 88
,D/qdlights(  838): set_light_backlight: 85
,D/qdlights(  838): set_light_backlight: 81
,D/qdlights(  838): set_light_backlight: 78
,D/qdlights(  838): set_light_backlight: 75
,D/qdlights(  838): set_light_backlight: 71
,D/qdlights(  838): set_light_backlight: 68
,D/qdlights(  838): set_light_backlight: 65
,D/qdlights(  838): set_light_backlight: 61
,D/qdlights(  838): set_light_backlight: 58
,D/qdlights(  838): set_light_backlight: 55
,D/qdlights(  838): set_light_backlight: 51
,D/qdlights(  838): set_light_backlight: 48
,D/qdlights(  838): set_light_backlight: 45
,D/qdlights(  838): set_light_backlight: 41
,D/qdlights(  838): set_light_backlight: 38
,D/qdlights(  838): set_light_backlight: 35
,D/qdlights(  838): set_light_backlight: 31
,D/qdlights(  838): set_light_backlight: 28
,D/qdlights(  838): set_light_backlight: 25
,D/qdlights(  838): set_light_backlight: 21
,D/qdlights(  838): set_light_backlight: 18
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/qdlights(  838): set_light_backlight: 15
D/qdlights(  838): set_light_backlight: 11
,D/qdlights(  838): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-69 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:43:23.862 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 153451455259; DSPS: 5126867; Offset : -3015803532
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  838): ALS enabled for SRE
D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34993 ms ago)
I/PowerManagerService(  838): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  838): ALS enabled for SRE
D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35017 ms ago)
W/ContextImpl(  838): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  838): Sleeping (uid 1000)...
D/LPWGController(  838): [updateScreenState] screen on = false
D/LPWGController(  838): disable proximity sensor
,D/LPWGController(  838): enable proximity sensor
I/SensorManager(  838): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3e56a4a5] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  838): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  838): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  838): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  838): activate: handle is 48, enable
V/sensors_hal_Ctx(  838): activate sensors is 1400000000000
D/sensors_hal_Thresh(  838): enable: handle=48
I/sensors_hal_SAM(  838): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
,D/sensors_hal_Util(  838): waitForResponse: timeout=1000
V/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  838): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
,D/sensors_hal_Thresh(  838): enable: Received response: 0
D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35091 ms ago)
I/Adreno-EGL(  838): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  838): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  838): Build Date: 03/02/15 Mon
I/Adreno-EGL(  838): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  838): Remote Branch: 
I/Adreno-EGL(  838): Local Patches: 
I/Adreno-EGL(  838): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (977 us)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Sensors (  416): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  838): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  838): processInd: handle 48, count=1
V/sensors_hal_Thresh(  838): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  838): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  838): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  838): poll: count: 256
I/sensors_hal_Ctx(  838): poll: released wakelock sensor_ind
D/sensors_hal_Util(  838): waitForResponse: timeout=0
D/LPWGController(  838): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  838): current mode = 1  value = 1 1
I/LPWGController(  838): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  838): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-25 22:43:26.869 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  838): set_light_backlight: 0
,I/SensorManager(  838): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  838): activate: handle is 46, disable
V/sensors_hal_Ctx(  838): activate sensors is 1000000000000
D/sensors_hal_LP2(  838): enable: handle=46
D/sensors_hal_LP2(  838): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  838): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
I/DisplayManagerService(  838): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  838): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  838): Display changed displayId=0
,D/DSDPConnection( 1746): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  838): Excessive delay in setPowerMode(): 170ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  838): Got set_interactive hint
,D/KeyguardViewMediator( 1370): onScreenTurnedOff(3)
,D/WifiServerServiceExt(  838): sendKtScanInterval  mRtspPlay : false
I/WifiServerServiceExt(  838): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 838
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
,D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_ON
,D/KeyguardViewMediator( 1370): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1327): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1370): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1370): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1370): unregisterProximitySensor
,D/StatusBarWindowView( 1370): onScreenTurnedOff why = 3
D/SmartCoverViewMediator( 1327): notifyScreenOffLocked
D/SmartCoverViewMediator( 1327): handleNotifyScreenOFF
,I/ActivityManager(  838): Process com.google.android.gms:car (pid 6951) has died
,D/GpsLocationProvider(  838): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1835): |CORE| sendScreenState: state:true
I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1800): stopPatternFlashing()
,I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1800): lockStatus = 0
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): updateLightsLocked : turn off led
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1800): RESTART MSG
D/SplitWindow(  838): check instance of lgWin Window{3fc0bc88 u0 SearchPanel}
,D/LNfcService( 1782): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1782): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1782): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
,D/LNfcService( 1782): isRequireNfcCRouting() return true
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
D/InputDispatcher(  838): Window went away: Window{25822d7e u0 SearchPanel}
I/[SystemUI]Clock( 1370): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
,D/Ulp_jni (  838): JNI:system_update. Event-0
,V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2653): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 22:43:27
,D/WeatherService( 2653): 2 : ACTION screen on
D/WeatherService( 2653): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2653): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2653): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 22:43:27
,D/AppCleanupService( 3866): android.intent.action.SCREEN_ON
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): ACTION_SCREEN_ON
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 838
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
,V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/WifiController(  838): CMD_SCREEN_OFF 
D/WifiController(  838): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_OFF
D/GpsLocationProvider(  838): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1835): |CORE| sendScreenState: state:false
,I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1800): clear
I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): updateLightsLocked : turn on led
E/LEDService( 1800): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1800): Can't handle this request of patternId:0
D/LEDHandler( 1800): RESTART MSG
D/LNfcService( 1782): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1782): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1872): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2653): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 22:43:27
D/WeatherService( 2653): 2 : ACTION screen off
D/WeatherService( 2653): 2 : TimeTick Receiver Unregister
D/WeatherService( 2653): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 22:43:27
D/AppCleanupService( 3866): android.intent.action.SCREEN_OFF
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): ACTION_SCREEN_OFF
D/AppCleanupService( 3866): AppUsageStatsSaveTask
E/NxpNfcJni( 1782): getReconnectState = 0x0
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
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
I/Sensors (  416): sns_pwr.c(301):releasing wakelock
E/NxpNfcJni( 1782): getReconnectState = 0x0
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1370): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{37b1e621 type 2 when 160985 com.android.systemui} when 160985
,D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1746): getCallState : 0
,D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1370): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1370): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 173452207074; DSPS: 5782251; Offset : -3015784451
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{9633a46 type 2 when 186753 com.google.android.gms} when 186753
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{13255407 type 2 when 186893 android} when 186893
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/art     (  838): Explicit concurrent mark sweep GC freed 34067(1931KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 3.049ms total 213.298ms
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1980): Disconnected process message: 10, size: 0
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/ChimeraCfgMgr( 7226): Reading stored module config
,I/ActivityManager(  838): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7406 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
D/ChimeraCfgMgr( 7226): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7226): Loading module APK com.google.android.play.games
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 7226): 0 accounts found with uca feature
I/GamesSyncAdapter( 7226): Starting sync for 3a3529a
W/BaseAppContext( 7226): Using Auth Proxy for data requests.
,E/BaseAppContext( 7226): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 7226): Using Auth Proxy for data requests.
W/BaseAppContext( 7226): Using Auth Proxy for data requests.
,W/BaseAppContext( 7226): Using Auth Proxy for data requests.
,W/BaseAppContext( 7226): Using Auth Proxy for data requests.
W/BaseAppContext( 7226): Using Auth Proxy for data requests.
W/BaseAppContext( 7226): Using Auth Proxy for data requests.
,I/GAv4    ( 7406): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7406):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7406):   adb logcat -s GAv4
,W/GAv4    ( 7406): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7406): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7406): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 7406): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7406): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 7406): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7406): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7406): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7406): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 7406): CheckpointMarkThreadRoots callback created = 0xb050fab0
,V/JNIHelp ( 7406): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 7406): CheckpointMarkThreadRoots callback created = 0xb050fa90
,W/System  ( 7406): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7406): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  838): Process com.android.contacts (pid 7143) has died
,I/NotificationManager(  838): android: cancelAsUser(-1488629395) by android
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/GamesSyncAdapter( 7226): Sync duration for 3a3529a: 945
,D/ChimeraCfgMgr( 7226): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7226): Module APK com.google.android.play.games already loaded
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/NotificationManager(  838): android: cancelAsUser(-715483196) by android
,D/ChimeraCfgMgr( 7226): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7226): Module APK com.google.android.play.games already loaded
,I/NotificationManager( 7226): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 193452937587; DSPS: 6437635; Offset : -3015786204
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1728): disconnect managed GoogleApiClient
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  269): wakelock acquired: 1, error no: 42
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  269): 
I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 213453689922; DSPS: 7093020; Offset : -3015796861
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=343120508, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{1fb90901 type 2 when 217537 android} when 217537
,D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=343120508 [*alarm*], flags=0x0
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{1a4d53a6 type 2 when 192279 android} when 192279
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 233454379968; DSPS: 7748403; Offset : -3015808666
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1980): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1980): Disconnected process message: 10, size: 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
D/HeadsetStateMachine( 1980): Disconnected process message: 10, size: 0
V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{1acd61e7 type 2 when 247694 android} when 247694
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 253455068033; DSPS: 8403785; Offset : -3015791911
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 273455810057; DSPS: 9059169; Offset : -3015782439
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 293456494997; DSPS: 9714552; Offset : -3015799351
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1980): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 313457250874; DSPS: 10369937; Offset : -3015806335
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 333458005138; DSPS: 11025321; Offset : -3015784701
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  838): remove cb71450
,D/LocationManagerService(  838): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  838): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  838): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 353458689713; DSPS: 11680704; Offset : -3015802370
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1980): Disconnected process message: 10, size: 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 373459363091; DSPS: 12336086; Offset : -3015799700
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 393460444647; DSPS: 12991481; Offset : -3015786650
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 413461118962; DSPS: 13646863; Offset : -3015783540
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5552): --= Surplus to requirements =--
I/jxcore-log( 5552): 
I/jxcore-log( 5552): ****TEST TOOK:  ms ****
I/jxcore-log( 5552): 
I/jxcore-log( 5552): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5552): 
,D/AndroidRuntime( 7524): 
D/AndroidRuntime( 7524): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7524): CheckJNI is OFF
,D/AndroidRuntime( 7524): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  838): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  838): Killing 5552:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  838): Skipping PackageSetting{1647252d com.example.hello/10317} due to missing metadata
,I/WindowState(  838): WIN DEATH: Window{351e546b u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  838): Focus left window: Window{351e546b u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  838): Window went away: Window{351e546b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  838):   Force finishing activity ActivityRecord{3b83b17c u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  838): Display changed displayId=0
D/DSDPConnection( 1746): Display #0 changed.
,W/ActivityManager(  838): Spurious death for ProcessRecord{1cf14194 5552:com.test.thalitest/u0a316}, curProc for 5552: null
I/ActivityManager(  838): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,I/ActivityManager(  838):   Force finishing activity ActivityRecord{3b83b17c u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  838): Duplicate finish request for ActivityRecord{3b83b17c u0 com.test.thalitest/.MainActivity t222 f}
,D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader(  838): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1728): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  838): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7553 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     ( 1930): Explicit concurrent mark sweep GC freed 9912(594KB) AllocSpace objects, 2(47KB) LOS objects, 39% free, 12MB/21MB, paused 2.379ms total 164.682ms
I/[LGHome]EVENT( 1872): [Launcher.java:5203:onStart()]onStart
W/System.err( 3409): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 3409): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3409): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3409): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3409): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3409): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3409): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3409): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3409): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3409): 	at java.lang.reflect.Method.invoke(Method.java:372)
I/[LGHome]EVENT( 1872): [Launcher.java:776:onResume()]onResume
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1872): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
W/System.err( 3409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1872): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1872): [Launcher.java:929:onResume()]onResume end
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
I/art     (  838): Explicit concurrent mark sweep GC freed 20354(1317KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 4.211ms total 272.910ms
I/Activity( 1872): Activity.onPostResume() called 
,I/[LGHome]Launcher.Model( 1872): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/art     (  838): WaitForGcToComplete blocked for 228.313ms for cause Explicit
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1872): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
,W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): handleShortcutListChanged...
,W/[LGHome]LGWallpaperInfo( 1872): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1872): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
,W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): handleShortcutListChanged...
W/ResourcesManager( 7553): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7553): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7553): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemUI[Framework](  838): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/InputDispatcher(  838): Focus entered window: Window{348a03bd u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/Adreno-EGL( 1872): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 1872): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 1872): Build Date: 03/02/15 Mon
I/Adreno-EGL( 1872): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 1872): Remote Branch: 
I/Adreno-EGL( 1872): Local Patches: 
I/Adreno-EGL( 1872): Reconstruct Branch: 
W/PhoneWindowManagerEx(  838): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  838): setLGSystemUiVisibility(0x0)
I/OpenGLRenderer( 1872): Initialized EGL, version 1.4
D/StatusBarManagerServiceEx(  838): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@15038ce3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  838): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  838): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  838): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  838): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@15038ce3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/administrator(  838): Handling package changes for user 0
I/[LGHome]EVENT( 1872): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1872): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1872): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1872): [Launcher.java:5214:onStop()]onStop
I/art     ( 1782): Background sticky concurrent mark sweep GC freed 90388(5MB) AllocSpace objects, 0(0B) LOS objects, 36% free, 8MB/14MB, paused 6.146ms total 69.164ms
,I/[LGHome]EVENT( 1872): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1872): [setNavigationBarColor] color=0x 0
I/art     (  838): Explicit concurrent mark sweep GC freed 4544(257KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.814ms total 301.409ms
,W/InputMethodManagerService(  838): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  838): Got RemoteException sending setActive(false) notification to pid 5552 uid 10316
I/NotificationService(  838): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  838): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  838): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  838): removeObsoleteFile: deleting file=222_task.xml
,D/PhoneStatusBar( 1370): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
I/LGEmail ( 7553): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[LGHome]Launcher.Model( 1872): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1872): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7524): Shutting down VM
,I/Timeline(  838): Timeline: Activity_windows_visible id: ActivityRecord{2ff69987 u0 com.lge.launcher2/.Launcher t221} time:427098
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
,D/LGEmail ( 7553): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]EVENT( 1872): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1872): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1872): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1872): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/IInputConnectionWrapper( 1872): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1872): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1872): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1618): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1872): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1872): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1872): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,W/IInputConnectionWrapper( 1872): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1872): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1872): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
,W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1872): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/PackageChangeReceiver( 7553): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/ResourcesManager(  838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7586 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a

```
