#### Test 50650278b28a87a_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{37704a9b type 0 when 1449671211375 com.android.vending} when 1449671211375
--------- beginning of main
D/Finsky  ( 4870): [570] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4870): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 5258): 
D/AndroidRuntime( 5258): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5258): CheckJNI is OFF
D/AndroidRuntime( 5258): Calling main entry com.android.commands.am.Am
I/ActivityManager(  846): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  846): setTaskToReturnTo : TaskRecord{206d2e38 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  846): setTaskToReturnTo : TaskRecord{206d2e38 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  846): AppWindowTokenEx init.. 
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/ContextHelper(  846): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  846): Focus left window: Window{3ad1bccf u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5258): Shutting down VM
D/SplitWindow(  846): check instance of lgWin Window{7261902 u0 Starting com.test.thalitest}
I/ActivityManager(  846): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5278 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 317us total 28.636ms
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 30.600ms
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 26.820ms
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1935): Closing mic
I/WindowStateAnimator(  846): Starting window displayed
I/MicrophoneInputStream( 1935): mic_close com.google.android.apps.gsa.speech.audio.u@aff7bca
V/AudioRecord( 1935): stop()
D/AudioRecord( 1935): AudioRecord->stop()
V/AudioFlinger(  273): RecordHandle::stop()
V/AudioFlinger(  273): RecordThread::stop
V/AudioFlinger(  273): Record stopped OK
V/AudioPolicyManager(  273): stopInput() input 17
I/SystemUI[Framework](  846): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/AudioPolicyService(  273): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  273): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  273): AudioCommandThread() waking up
V/AudioPolicyService(  273): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  273): releaseAudioPatch handle 18
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/AudioFlinger::PatchPanel(  273): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  273): ThreadBase::setParameters() routing=0
V/AudioFlinger(  273): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  273): processConfigEvents_l() remaining events 1
V/AudioFlinger(  273): processConfigEvents_l() DONE thread 0xb4393000
W/PhoneWindowManagerEx(  846): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  846): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  846): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3cd0d778,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/audio_hw_primary(  273): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1375): draw background and invalidate : color = 10000000
D/BarTransitions( 1375): draw background and invalidate : color = 11111111
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
V/audio_hw_primary(  273): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  273): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  273): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  273): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  273): disable_audio_route: exit
E/audio_hw_primary(  273): disable_snd_device: enter 144
D/hardware_info(  273): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  273): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  273): stop_input_stream: exit: status(0)
V/audio_hw_primary(  273): in_standby: exit:  status(0)
V/AudioFlinger(  273): RecordThread: loop stopping
V/AudioPolicyService(  273): AudioCommandThread() going to sleep
V/AudioPolicyManager(  273): resetInputDevice() releaseAudioPatch returned -22
,V/AudioPolicyManager(  273): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  273): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  273): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  273): AudioCommandThread() waking up
V/AudioPolicyService(  273): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  273): AudioCommandThread() going to sleep
V/AudioPolicyService(  273): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  273): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  273): AudioCommandThread() waking up
V/AudioPolicyService(  273): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  273): setParameters(): io 17, keyvalue hotword_active=0, calling pid 273
V/AudioFlinger(  273): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  273): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  273): RecordThread: loop starting
V/AudioFlinger(  273): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  273): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  273): in_set_parameters: exit: status(0)
V/AudioFlinger(  273): processConfigEvents_l() DONE thread 0xb4393000
V/AudioFlinger(  273): RecordThread: loop stopping
V/AudioPolicyService(  273): AudioCommandThread() going to sleep
V/AudioRecord( 1935): stop()
,V/AudioRecord( 1935): stop()
V/AudioRecord( 1935): stop()
V/AudioFlinger(  273): RecordHandle::stop()
V/AudioFlinger(  273): RecordThread::stop
V/AudioPolicyManager(  273): releaseInput() 17
V/AudioPolicyManager(  273): closeInput(17)
V/AudioFlinger(  273): releasing 16 from 1935 for -1
V/AudioFlinger(  273):  decremented refcount to 0
V/AudioFlinger(  273): purging stale effects
V/AudioFlinger(  273): closeInput() 17
V/AudioSystem(  273): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1935): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  273): ThreadBase::exit
V/AudioSystem(  846): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2061): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3096): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  273): RecordThread: loop starting
V/AudioSystem( 1375): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  273): RecordThread 0xb4393000 exiting
D/audio_hw_primary(  273): adev_close_input_stream: enter:stream_handle(0xb4036520)
,D/audio_hw_primary(  273): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  273): in_standby: exit:  status(0)
V/AudioPolicyService(  273): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  273): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  273): AudioCommandThread() waking up
V/AudioPolicyService(  273): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  273): AudioCommandThread() going to sleep
V/AudioPolicyManager(  273): releaseInput() exit
V/AudioFlinger(  273): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  273): removeClient_l() pid 1935, calling pid 273
I/HotwordRecognitionRnr( 1935): Stopping hotword detection.
I/HotwordRecognitionRnr( 1935): Hotword detection finished
D/ContextHelper( 5278): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 5278): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5278): Time to load native libraries: 1 ms (timestamps 4014-4015)
,I/LibraryLoader( 5278): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5278): Binding Chromium to main looper Looper (main, tid 1) {26f7b2f2}
I/LibraryLoader( 5278): Expected native library version number "",actual native library version number ""
,I/chromium( 5278): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5278): Initializing chromium process, singleProcess=true
,W/art     ( 5278): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5278): ApplicationContext is null in ApplicationStatus
W/chromium( 5278): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5278): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5278): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5278): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5278): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5278): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5278): Remote Branch: 
I/Adreno-EGL( 5278): Local Patches: 
I/Adreno-EGL( 5278): Reconstruct Branch: 
,V/AudioPolicyService(  273): registerClient() client 0xb4027820, uid 10316
,D/BluetoothManagerService(  846): Message: 20
D/BluetoothManagerService(  846): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32e1a014:true
,D/BluetoothAdapter( 5278): 581064629: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5278): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5278): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5278): CordovaWebView is running on device made by: LGE
,W/art     ( 5278): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5278): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 5278): Activity.onPostResume() called 
,D/OpenGLRenderer( 5278): Render dirty regions requested: true
I/OpenGLRenderer( 5278): Initialized EGL, version 1.4
D/OpenGLRenderer( 5278): Enabling debug mode 0
,D/Atlas   ( 5278): Validating map...
,D/SplitWindow(  846): check instance of lgWin Window{18b73644 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5278): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  846): Focus entered window: Window{18b73644 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  846): Displayed com.test.thalitest/.MainActivity: +1s243ms
I/Timeline(  846): Timeline: Activity_windows_visible id: ActivityRecord{9e1ee11 u0 com.test.thalitest/.MainActivity t220} time:94719
,W/InputMethodManagerService(  846): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Timeline( 5278): Timeline: Activity_idle id: android.os.BinderProxy@1c3000ee time:94757
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 94821395177; DSPS: 3198471; Offset : -2790246934
,W/BindingManager( 5278): Cannot call determinedVisibility() - never saw a connection for the pid: 5278
,D/JsMessageQueue( 5278): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5278): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622839296
,D/JX-Cordova( 5278): jxcore cordova android initializing
I/art     ( 5278): CheckpointMarkThreadRoots callback created = 0xb04ecd20
,I/art     ( 5278): CheckpointMarkThreadRoots callback created = 0xb04eccf0
,W/art     ( 5278): Suspending all threads took: 5.514ms
,I/art     ( 5278): Background sticky concurrent mark sweep GC freed 29153(3MB) AllocSpace objects, 11(2MB) LOS objects, 26% free, 14MB/20MB, paused 8.214ms total 68.799ms
,I/art     (  846): Explicit concurrent mark sweep GC freed 16052(736KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 5.082ms total 178.714ms
,W/jxcore-log( 5278): Initializing JXcore engine
,W/jxcore-log( 5278): JXcore engine is ready
W/jxcore-log( 5278): Starting JXcore engine
,W/.test.thalitest( 5278): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7733]" dev="sockfs" ino=7733 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5278): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5278): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6678]" dev="sockfs" ino=6678 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 5278): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5278): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5278): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25722]" dev="sockfs" ino=25722 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5278): Platform android
W/jxcore-log( 5278): 
W/jxcore-log( 5278): Process ARCH arm
W/jxcore-log( 5278): 
,I/jxcore-log( 5278): JXcore Cordova bridge is ready!
I/jxcore-log( 5278): 
W/jxcore-log( 5278): JXcore engine is started
,I/chromium( 5278): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 5278): Skipped 175 frames!  The application may be doing too much work on its main thread.
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/jxcore-log( 5278): Toggling radios to true
I/jxcore-log( 5278): 
,D/BluetoothManagerService(  846): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  846): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  846): Message: 1
D/BluetoothManagerService(  846): MESSAGE_ENABLE: mBluetooth = null
D/SettingsProvider(  846): User 0 external modification to /data/data/com.android.providers.settings/databases/settings.db; event=2
D/SettingsProvider(  846): User 0 updating our caches for /data/data/com.android.providers.settings/databases/settings.db
D/SettingsProvider(  846): row count exceeds max cache entries for table system
,D/BluetoothAdapterService(1011485758)( 1988): onBind()
,D/WifiServiceImplEx(  846): setWifiEnabled: true pid=5278, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  846): setWifiEnabled: true pid=5278, uid=10316
,D/BluetoothManagerService(  846): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  846): Message: 40
D/BluetoothManagerService(  846): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/LocationManagerService(  846): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  846): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  846): JNI:system_update. Event-4
,D/WifiServiceImplEx(  846): disconnect pid=5278, uid=10316, packageName=com.test.thalitest
D/LocationManagerService(  846): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  846): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  846): JNI:system_update. Event-4
D/WifiServiceImplEx(  846): reconnect pid=5278, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5278): Radios toggled
I/jxcore-log( 5278): 
D/BluetoothManagerService(  846): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/LGFTMITEM(  846): [GET_FTM][id=6], offset=12288
,E/WifiHW  (  846): Wifi MAC Address = a0:39:f7:70:12:80
E/WifiHW  (  846): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  846): band=b
E/WifiHW  (  846): ": cur_etheraddr=a0:39:f7:70:12:80
I/bluedroid( 1988): config_hci_snoop_log
,D/SoftapController(  269): Softap fwReload - Ok
D/BluetoothManagerService(  846): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  846): Broadcasting onBluetoothServiceUp() to 10 receivers.
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/CommandListener(  269): Setting iface cfg
D/CommandListener(  269): Trying to bring down wlan0
D/CommandListener(  269): Clearing all IP addresses on wlan0
V/LGMDMManagerInternal( 1988): Create singleton instance
E/WifiHW  (  846): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,I/wpa_supplicant( 5397): Successfully initialized wpa_supplicant
,D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
D/BluetoothAdapterService(1011485758)( 1988): enable() - Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1988): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1988): Setting state to 11
I/BluetoothAdapterState( 1988): Bluetooth adapter state changed: 10-> 11
I/jxcore-log( 5278): Got Device Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 5278): 
D/WifiMonitor(  846): startMonitoring(wlan0) with mConnected = false
,I/jxcore-log( 5278): Perf Test app loaded loaded
I/jxcore-log( 5278): 
I/wpa_supplicant( 5397): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5397): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BluetoothAdapterService(1011485758)( 1988): updateAdapterState() - Broadcasting state to 1 receivers.
I/jxcore-log( 5278): check test folder
I/jxcore-log( 5278): 
,D/BluetoothManagerService(  846): Message: 60
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothManagerService(  846): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  846): Bluetooth State Change Intent: 10 -> 11
I/jxcore-log( 5278): found test : ./testFindPeers.js
I/jxcore-log( 5278): 
D/BluetoothAdapterService(1011485758)( 1988): processStart()
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:26:59.51 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 1988): Unable to read settings
D/BtSettings.ProfileConfig( 1988): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1988): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1988): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1988): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1988): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1988): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1988): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1988): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/jxcore-log( 5278): found test : ./testSendData.js
I/jxcore-log( 5278): 
I/ActivityManager(  846): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5407 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,I/WifiServerServiceExt(  846): WIFI_STATE_CHANGED_ACTION [2]
D/LGBluetoothAPIService( 1804): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1011485758)( 1988): processStart() - Make Bond State Machine
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/BluetoothBondStateMachine( 1988): make
,D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
,D/BluetoothAdapterService( 1988): setAdapterService() - set to: null
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
D/LGBluetoothServiceAdapter( 1988): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 1988): StableState(): Entering Off State
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1988): Unable to read settings
D/BtSettings.ProfileConfig( 1988): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1988): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1988): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1988): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1988): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1988): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1988): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1988): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(1011485758)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(1011485758)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(1011485758)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
D/BluetoothHeadset(  846): Proxy object connected
D/BluetoothHeadset( 1751): Proxy object connected
D/HeadsetService( 1988): Received start request. Starting profile...
,I/LGBluetoothHeadsetServiceJni( 1988): classInitNative: succeeds
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(1011485758)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(1011485758)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/LGBluetoothFeatureConfig( 1988): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 1988): classInitNative: succeeds
D/HeadsetStateMachine( 1988): make
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(1011485758)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
,D/BluetoothHeadset( 1751): Proxy object connected
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(1011485758)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/BluetoothHeadset( 1751): Proxy object connected
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
,D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1988): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1011485758)( 1988): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
I/chromium( 5278): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1988): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1011485758)( 1988): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
,I/[SystemUI]BluetoothHandler( 1375): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/HeadsetStateMachine( 1988): max_hf_connections = 1
I/bluedroid( 1988): get_profile_interface handsfree
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1988): Not skipping com.broadcom.bt.service.opp.OppService
,D/BluetoothAdapterService(1011485758)( 1988): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
V/LGMDMManager( 1988): Create singleton instance
I/bt-btif ( 1988): btif_hf_get_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): max_hf_clients = 1
D/bt-btif ( 1988): btif_max_hf_clients = 1
D/bt-btif ( 1988): btif_enable_service: current services:0xa060c330
I/BluetoothAdapterState( 1988): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,V/ToneGenerator( 1988): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  273): registerClient() client 0xb551c7a0, uid 1002
V/AudioPolicyManager(  273): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  273): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  273): getOutput() returns output 2
V/AudioFlinger(  273): registerClient() client 0xb40331d8, pid 1988
V/AudioFlinger(  273): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  273): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  273): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  273): thread 0xb5651000 type 0 TID 1293 waking up
,V/AudioFlinger(  273): thread 0xb56eb000 type 0 TID 1294 waking up
,V/AudioFlinger(  273): thread 0xb5735000 type 0 TID 1297 waking up
V/AudioFlinger(  273): processConfigEvents_l() remaining events 1
V/AudioFlinger(  273): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioFlinger(  273): processConfigEvents_l() remaining events 1
V/AudioFlinger(  273): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioFlinger(  273): processConfigEvents_l() remaining events 1
V/AudioFlinger(  273): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  273): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  273): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1988): ioConfigChanged() event 0, ioHandle 6
V/AudioFlinger(  273): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem(  273): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1988): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem(  273): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1988): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  273): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem(  846): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  846): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  846): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  846): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1375): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1375): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1375): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1375): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1751): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1751): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1751): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1751): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1988): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1935): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1935): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1935): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1935): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2061): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2061): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2061): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2061): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3096): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3096): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  273): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  273): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1988): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 3096): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3096): ioConfigChanged() opening already existing output! 2
V/ToneGenerator( 1988): Create Track: 0xb4909480
V/AudioTrack( 1988): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 1988): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
I/AudioFlinger(  273): isAudioPlaybackHookOn() false
V/AudioFlinger(  273): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem(  846): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  846): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1935): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1935): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1375): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1375): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2061): ioConf,igChanged() event 0, ioHandle 4
V/AudioSystem( 2061): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3096): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3096): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1751): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1751): ioConfigChanged() opening already existing output! 4
D/AudioTrack( 1988): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioSystem( 1988): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1988): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioPolicyManager(  273): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  273): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  273): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  273): getOutput() returns output 2
V/AudioSystem( 1988): getLatency() output 2, latency 50
V/AudioSystem( 1988): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1988): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1988): Create normal PCM 0x1 Track
V/AudioFlinger(  273): createTrack() lSessionId: 22
V/AudioFlinger(  273): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  273): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 1988): Flags here  0x4 
V/AudioTrack( 1988): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  273): acquiring 22 from 1988, for 1988
V/AudioFlinger(  273):  added new entry for 22
V/ToneGenerator( 1988): ToneGenerator INIT OK, time: 101028
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
V/AudioFlinger(  273): processConfigEvents_l() remaining events 1
V/AudioFlinger(  273): processConfigEvents_l() DONE thread 0xb5651000
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
D/HeadsetStateMachine( 1988): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 1988): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1988): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1988): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  273): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1988
D/audio_hw_primary(  273): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  273): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  273): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  273): voice_extn_compress_voip_set_parameters: exit
V/voice   (  273): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  273): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  273): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  273): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  273): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  273): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  273): adev_set_parameters: exit with code(0)
V/ToneGenerator( 1988): ToneGenerator destructor
V/ToneGenerator( 1988): stopTone
V/ToneGenerator( 1988): Delete Track: 0xb4909480
V/AudioTrack( 1988): ~AudioTrack, releasing session id from 1988 on behalf of 1988
V/AudioFlinger(  273): releasing 22 from 1988 for 1988
V/AudioFlinger(  273):  decremented refcount to 0
V/AudioFlinger(  273): purging stale effects
V/AudioFlinger(  273): remove track (4099) and delete from mixer
V/AudioPolicyService(  273): AudioCommandThread() adding release output 2
V/AudioPolicyService(  273): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  273): AudioCommandThread() waking up
V/AudioPolicyService(  273): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  273): releaseOutput() 2
V/AudioPolicyService(  273): AudioCommandThread() going to sleep
V/AudioFlinger(  273): PlaybackThread::Track destructor
V/AudioFlinger(  273): removeClient_l() pid 1988, calling pid 273
D/A2dpService( 1988): Received start request. Starting profile...
D/BluetoothA2dp(  846): Proxy object connected
I/BluetoothAvrcpServiceJni( 1988): classInitNative: succeeds
V/Avrcp   ( 1988): make
D/Avrcp   ( 1988): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1988): get_profile_interface avrcp
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
I/bt-btif ( 1988): btif_rc_get_interface
I/bt-btif ( 1988): ## init ##
I/LGBluetoothAvrcpServiceJni( 1988): classInitNative: succeeds
I/LGBluetoothAvrcpAdapter( 1988): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 1988): initNative: succeeds
,I/ActivityManager(  846): Process com.google.android.talk (pid 4918) has died
I/BluetoothAvrcpBrcmAdapterJni( 1988): classInitBrcmNative
I/BluetoothAvrcpBrcmAdapterJni( 1988): initBrcmNative
,V/AudioService(  846): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
E/AudioService(  846): No RCC entry present to update
,E/RemoteController( 1988): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1988): classInitNative
I/BluetoothA2dpServiceJni( 1988): classInitNative: succeeds
D/A2dpStateMachine( 1988): make
I/bluedroid( 1988): get_profile_interface a2dp
I/bt-btif ( 1988): btif_av_get_src_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): btif_enable_service: current services:0xa060c330
I/LGBluetoothA2dpServiceJni( 1988): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1988): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1988): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1988): [BTUI] init
D/LGBluetoothPowerControlManager( 1988): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  846): Message: 30
,D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
D/A2dpStateMachine( 1988): Enter Disconnected: -2
I/BluetoothHidServiceJni( 1988): classInitNative: succeeds
D/HidService( 1988): Received start request. Starting profile...
I/bluedroid( 1988): get_profile_interface hidhost
I/bt-btif ( 1988): btif_hh_get_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): btif_enable_service: current services:0xa060c330
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
I/BluetoothHealthServiceJni( 1988): classInitNative: succeeds
D/HealthService( 1988): Received start request. Starting profile...
I/bluedroid( 1988): get_profile_interface health
I/bt-btif ( 1988): btif_hl_get_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): Process name (droid.bluetooth)
D/bt-btif ( 1988): btif_hl_soc_thread_init
D/bt-btif ( 1988): create_thread: entered
D/bt-btif ( 1988): create_thread: thread created successfully
D/bt-btif ( 1988): entered btif_hl_select_thread
D/bt-btif ( 1988): btif_hl_select_wakeup_init
D/bt-btif ( 1988): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1988): max_s=55 
D/bt-btif ( 1988): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 1988): classInitNative: succeeds
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
,I/BluetoothPanServiceJni( 1988): classInitNative(L105): succeeds
D/PanService( 1988): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1988): initializeNative(L110): pan
I/bluedroid( 1988): get_profile_interface pan
D/bt-btif ( 1988): stack_initialized = 0, btpan_cb.enabled:0
I/LGBluetoothPanAdapter( 1988): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
,I/BtGatt.JNI( 1988): classInitNative(L901): classInitNative: Success!
D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=278032789, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
D/BtGatt.DebugUtils( 1988): handleDebugAction() action=null
D/BtGatt.GattService( 1988): Received start request. Starting profile...
D/BtGatt.GattService( 1988): start()
I/bluedroid( 1988): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1988): advertise manager created
I/LGBluetoothGattAdapter( 1988): [BTUI] getInstance : create [LGBluetoothGattAdapter]
,D/LGBluetoothGattAdapter( 1988): setGattService:  set to: null
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
I/LGBluetoothMapAdapter( 1988): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1988): BluetoothMapBinder()
D/BluetoothMapService( 1988): Received start request. Starting profile...
D/BluetoothMapService( 1988): start()
D/BluetoothMapEmailSettingsLoader( 1988): Found 0 applications
D/BluetoothMapEmailAppObserver( 1988): createReceiver()
,D/BluetoothMapEmailAppObserver( 1988): initObservers()
D/BluetoothMapEmailAppObserver( 1988): getEnabledAccountItems()
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
I/BluetoothSAPServiceJni( 1988): classInitNative(L170): succeeds
,D/SapService( 1988): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1988): initializeNative(L175): sap
I/bluedroid( 1988): get_profile_interface sap
I/bt-btif ( 1988): btif_sc_get_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): btif_enable_service: current services:0xa060c330
I/LGBluetoothSapAdapter( 1988): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1988): [BTUI] Create LGBluetoothSapManager Instance
I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
D/LGBluetoothSapManager( 1988): [BTUI] initSapManager
I/[SystemUI]Clock( 1375): called onTimeUpdated()
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
V/BluetoothFTPServiceJni( 1988): classInitNative
I/BluetoothFTPServiceJni( 1988): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
D/BluetoothFTPService( 1988): BluetoothFtpBinder()
,D/**BluetoothFTPService( 1988): Received start request. Starting profile...
V/BluetoothFTPService( 1988): FTP-Server Service start
W/ResourcesManager( 5407): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LgeBluetoothSimManager( 1751): [BTUI] SAP_ENABLE_EVT
W/ResourcesManager( 5407): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5407): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothFTPServiceJni( 1988): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1988): get_profile_interface ftp
I/bt-btif ( 1988): btif_fts_get_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): btif_enable_service: current services:0xa060c330
D/BluetoothFTPServiceJni( 1988): initFtpNativeDataNative(L317): FTP init done
W/ResourcesManager( 5407): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
D/HeadsetStateMachine( 1988): Proxy object connected
W/ResourcesManager( 5407): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/LGBluetoothHfpAdapter( 1988): [BTUI] queryPhoneState
D/LGBluetoothFeatureConfig( 1988): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1988): classInitNative
I/BluetoothOPPServiceJni( 1988): classInitNative(L373): succeeds
V/OppService( 1988): Opp initBinder
,D/**OppService( 1988): Received start request. Starting profile...
D/OppService( 1988): Starting OppService 
D/LGBluetoothOppAdapter( 1988): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 1988): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 1988): send message
D/BluetoothOppPreference( 1988): Dumping Names:  
D/BluetoothOppPreference( 1988): {}
D/BluetoothOppPreference( 1988): Dumping Channels:  
D/BluetoothOppPreference( 1988): {}
D/OppService( 1988): Start()
W/BluetoothOPPServiceJni( 1988): initOppNative
D/BluetoothOPPServiceJni( 1988): initOppNative(L383): OPP
I/bluedroid( 1988): get_profile_interface opp
,I/bt-btif ( 1988): btif_op_get_interface
D/BluetoothOPPServiceJni( 1988): initOppNative(L411): mOppCallbacksObj 1049854
D/BluetoothOPPServiceJni( 1988): initOppNative(L413): calling OPP init
I/bt-btif ( 1988): btif_opp_init
D/bt-btif ( 1988): btif_enable_service: current services:0xa060c330
D/BluetoothOPPServiceJni( 1988): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1988): initOppNative(L430): mOppCallbacksObj 1049854
V/OppService( 1988): setOppService(): set to: com.broadcom.bt.service.opp.OppService@13b14314
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1011485758)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
V/OppService( 1988): pendingUpdate is :  true
D/BluetoothA2dp( 1988): Proxy object connected
D/LGBluetoothPowerControlManager( 1988): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@1a61d7bd
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1011485758)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
,D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1011485758)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetPhoneState( 1988): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1988): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1011485758)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
V/OppService( 1988): Deleted complete outbound shares, number =  0
,V/PanService( 1988): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1011485758)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1988): Deleted complete inbound failed shares, number = 0
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1011485758)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1988): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1988): Handler(): got msg=1
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1011485758)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@3fe97c80 on behalf of 
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1011485758)( 1988): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1011485758)( 1988): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1988): new notify threadi!
V/BluetoothOppNotification( 1988): send delay message
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(1011485758)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1011485758)( 1988): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(1011485758)( 1988): onProfileServiceStateChange() - All profile services started.
V/OppService( 1988): ContentObserver received notification
V/OppService( 1988): ContentObserver received notification
D/BluetoothAdapterState( 1988): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1988): enable
I/bt-btif ( 1988): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1988): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@255932b9 on behalf of 
,I/GKI_LINUX( 1988): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1988): btu_task pending for preload complete event
I/bt_hci_bdroid( 1988): init
I/bt_vendor( 1988): init
I/bt_vnd_conf( 1988): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1988): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@88526fe on behalf of 
I/bt-btif ( 1988): libbt-hci init returns 0
V/OppService( 1988): pendingUpdate is :  true
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppNotification( 1988): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@19072e5f on behalf of 
V/BluetoothOppNotification( 1988): update too frequent, put in queue
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/OppService( 1988): pendingUpdate is :  false
E/OppService( 1988): UpdateThread is Completed
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@14a9e0ac on behalf of 
V/BluetoothOppNotification( 1988): outbound: succ-0  fail-0
I/NotificationManager( 1988): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1988): outbound notification was removed.
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@3fd14175 on behalf of 
,V/BluetoothOppNotification( 1988): inbound: succ-0  fail-0
I/NotificationManager( 1988): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1988): inbound notification was removed.
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@388b50a on behalf of 
I/IndexDatabaseHelper( 5407): Using schema version: 115
,I/ActivityManager(  846): Process com.google.android.gms:car (pid 4986) has died
I/IndexDatabaseHelper( 5407): Index is fine
I/bt_userial_vendor( 1988): userial vendor open: opening /dev/ttyHS99
,D/bt_userial_vendor( 1988): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1988): device fd = 67 open
D/bt_hwcfg( 1988): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 1988): hw_config_cback state=1
,D/bt_hwcfg( 1988): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1988): hw_config_cback state=4
D/bt_hwcfg( 1988): Chipset Name: BCM4334B0
D/bt_hwcfg( 1988): Chipset BCM4334B0
D/bt_hwcfg( 1988): Target name = [BCM4334B0]
I/bt_hwcfg( 1988): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1988): hw_config_cback state=2
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1988): hw_config_cback state=3
I/bt_hwcfg( 1988): bt vendor lib: set UART baud 4000000
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1988): hw_config_cback state=5
,V/BluetoothPbapReceiver( 1988): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1988): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1988): ***********state = 11
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5407): remove : truetruefalse
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5407): remove2
V/WiFiOffLoadSharedPrefsUtils( 5407): save wifi state
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
V/WiFiOffLoadSharedPrefsUtils( 5407): save remove
D/WiFiOffLoadBroadcast( 5407): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WiFiOffLoadBroadcast( 5407): S: false, R: true
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/Netd    (  269): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  269): M: Get netlink event, ifname: wlan0 action: 4
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/ActivityManager(  846): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5451 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/Tethering(  846): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1988): hw_config_cback state=6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 1000
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/DnsProxyListener(  269): App 1000 tries DNS query. Accept family:0 protocol:0
D/bt_hwcfg( 1988): hw_config_cback state=6
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/DSQN    (  846): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/BluetoothPermissionRequest( 5407): onReceive
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LGBluetoothFeatureConfig( 5407):  get() - isFeatureLoaded : false
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
E/wpa_supplicant( 5397): USIM:  scard_init function
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/wpa_supplicant( 5397): rfkill: Cannot open RFKILL control device
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  269): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  269): M: Get netlink event, ifname: p2p0 action: 9
I/Netd    (  269): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/BluetoothManagerService(  846): Message: 20
D/BluetoothManagerService(  846): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fb10b6e:true
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/wpa_supplicant( 5397): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
V/BluetoothSapReceiver( 1988): [BTUI] checkServiceStart
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/LGBluetoothStateChangeReceiver( 1988): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/wpa_supplicant( 5397): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiStateMachine(  846): MAC Addr from driver = a0:39:f7:70:12:80
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  846): setPowerSaveActivated(false)
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/ActivityManager(  846): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5471 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
I/WifiServerServiceExt(  846): WIFI_STATE_CHANGED_ACTION [3]
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
E/WifiServerServiceExt(  846): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiServerServiceExt(  846): batteryPsActivateMsgHandler : state:0 event:3
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:00.638 DNS addrs= 0.0.0.0, 0.0.0.0, 
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
E/WifiConfigStore(  846): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/WifiStateMachine(  846): enableVerboseLogging : level 2
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiStateMachine(  846): Setting OUI to DA-A1-19
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsService( 1804): Supplicant Connection state is changed : true
D/WfdsService( 1804): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1804): Set the WFDS Monitor: true
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsMonitor( 1804): WfdsMonitorThread create
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsMonitor( 1804): WFDS Monitor is created and started
D/WfdsService( 1804): WiFi: Supplicant connection re-established
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/WifiNative-HAL(  846): Setting external_sim to 1
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiNative-HAL(  846): startHal
E/wifi    (  846): getStaticLongField sWifiHalHandle 0x9b32a8ec
I/WifiHAL (  846): Initializing wifi
I/WifiHAL (  846): Creating socket
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
E/CtrlSupplicant( 1804): Access OK "@android:wpa_wlan0"
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
E/CtrlSupplicant( 1804): Succeed to open control connection
E/CtrlSupplicant( 1804): Succeed to open monitor connection
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsMonitor( 1804): Supplicant connection established
D/PCSuite ( 5451): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/WfdsService( 1804): Connected to the supplicant for wfds
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiHAL (  846): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  846): Did set static halHandle = 0x99c5a500
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/UsbSettingsReceiver( 5407): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/bt_hwcfg( 1988): hw_config_cback state=6
D/UsbSettingsReceiver( 5407): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5407): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5407): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/UsbSettingsReceiver( 5407): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/wifi    (  846): halHandle = 0x99c5a500, mVM = 0xb487c280, mCls = 0xa01956
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1988): hw_config_cback state=6
E/wifi    (  846): getStaticLongField sWifiHalHandle 0x9b32a89c
D/wifi    (  846): array field set
I/WifiNative-HAL(  846): interface[0] = wlan0
I/WifiNative-HAL(  846): interface[1] = p2p0
D/wifi    (  846): setting scan oui 0x9d9065e0
D/WifiHAL (  846): Sending mac address OUI
E/WifiHAL (  846): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  846): Setting OUI to DA-A1-19
I/WifiNative-HAL(  846): startHal
D/wifi    (  846): setting scan oui 0x9d9065e0
D/WifiHAL (  846): Sending mac address OUI
E/WifiHAL (  846): failed to set scanning mac OUI; result = -95
I/WifiNative-HAL(  846): Waiting for HAL events mWifiHalHandle=-1715100416
D/wifi    (  846): waitForHalEvents called, vm = 0xb487c280, obj = 0xa01956, env = 0xaaf6fef0
E/wifi    (  846): getStaticLongField sWifiHalHandle 0x99259b2c
D/UsbSettingsControl( 5407): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 5407): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5407): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5407): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5407): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5407): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 5407): [AUTORUN] setTetherStatus() : status=false
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  846): hidePasspointNotification off =false
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:00.738 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WiFiOffLoadUpdatePriority( 5407): remove : truetruetrue
,I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/LGWifiP2pService(  846): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  269): Setting iface cfg
D/CommandListener(  269): Trying to bring up p2p0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/WifiScanningService(  846): SCAN_AVAILABLE : 3
D/RttService(  846): SCAN_AVAILABLE : 3
D/RttService(  846): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor(  846): startMonitoring(p2p0) with mConnected = true
D/WifiScanningService(  846): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnablingState
I/WifiNative-HAL(  846): startHal
D/LGWifiP2pService(  846): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2p socket connection successful
D/LGWifiP2pService(  846): P2pEnabledState
D/wifi    (  846): getting scan capabilities on interface[0] = 0x9d9065e0
D/WifiHAL (  846): Creating message to get scan capablities; iface = 24
D/wifi    (  846): failed to get capabilities : -95
E/WifiScanningService(  846): could not get scan capabilities
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/LGWifiP2pService(  846): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  846): before postfix = G3s-1
D/WifiServerServiceExt(  846): postfix byte check : 5
D/LGWifiP2pService(  846): after postfix = G3s-1
I/WifiServerServiceExt(  846): set CMD_ADD_DEFAULT_PROFILE
D/WifiNative-HAL(  846): p2pGetDeviceAddress
I/WifiServerServiceExt(  846): setWifiDualbandAPConnection band : 1
D/WifiNative-HAL(  846): p2pGetDeviceAddress returning a2:39:f7:70:12:80
D/LGWifiP2pService(  846): DeviceAddress: a2:39:f7:70:12:80
E/wpa_supplicant( 5397): nWIFIDualbandAPConnection: 1
D/WfdsService( 1804): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
I/WifiServerServiceExt(  846): set CMD_DISCONNECT_RSSI_LVL : -100
,D/WfdsService( 1804): Update P2p Interface State: 3
E/wpa_supplicant( 5397): disconnect_rssi_lvl: -100
,D/LGWifiP2pService(  846): sending p2p persistent groups changed broadcast
D/LGWifiP2pService(  846): sending p2p connection changed broadcast
D/WfdsService( 1804): WifiP2pState is changed : true
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1804): Receive the WFDS_ENABLE Method
,D/WfdsService( 1804): Set the WFDS Monitor: true
D/WfdsService( 1804): Connected to the supplicant for wfds
D/LGWifiP2pService(  846): InactiveState
D/WfdsJNI ( 1804): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 5397): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1804): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5397): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1804): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5397): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1804): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsService( 1804): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/LGWifiP2pService(  846): InactiveState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): DefaultState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): InactiveState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): DefaultState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt(  846): No p2p device connected
D/WfdsJNI ( 1804): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1804): selectPreferredScanChannel [6]
D/WfdsService( 1804): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
I/WifiServerServiceExt(  846): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5397): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
I/WifiServerServiceExt(  846): set CMD_UPDATE_DEFAULT_PROFILE
W/ResourcesManager( 5471): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WfdsService( 1804): isConnected: false
D/LGWifiP2pService(  846): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  846): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): InactiveState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1804): GroupInfoAvailable: mGroupInfo is null
D/LGWifiP2pService(  846): DefaultState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/bt_hwcfg( 1988): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 1988): Settlement delay -- 100 ms
I/bt_hwcfg( 1988): Setting fw settlement delay to 100 
W/WfdsService( 1804): DefaultState - msg [9441285] is not handled
I/wpa_supplicant( 5397): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,I/wpa_supplicant( 5397): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LGBluetoothProfileConnectionReceiver_EasySetting( 5471): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
,D/AuthorizationBluetoothService( 1959): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WeatherService( 2672): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:27:0
D/WeatherService( 2672): 2 : TimeTick Intent And Screen On
D/WeatherService( 2672): 2 : SDK version : 21
W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2672): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2672): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2672): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2672): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2672): 2 : This is isUpdating : false
D/WeatherService( 2672): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2672): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2672): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2672): 2 : Fixed theme : optimus
D/WeatherReflect( 2672): 2 : Map key string is -2
D/lim     ( 2672): 2 : time = 15:27
I/WeatherReflect( 2672): Model Name : LG-D722
D/WeatherTheme( 2672): 2 : Different view - status_min_formatted : 26 != 27
D/WeatherTheme( 2672): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2672): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2672): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:00.866 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/Netd    (  269): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  269): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  269): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 5397): wlan0: Associated with c0:ff:d4:d3:aa:48
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:00.883 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LocSvc_java(  846): onReceive
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:00.886 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,D/GONS    ( 1751): GONS isTestMode: false Country: 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateSCANNING
D/WiFiOffLoadUpdatePriority( 5407): remove1
V/WiFiOffLoadSharedPrefsUtils( 5407): save remove
,D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1988): hw_config_cback state=2
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:00.914 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1988): hw_config_cback state=7
I/bt_hwcfg( 1988): bt vendor lib: set UART baud 4000000
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/bt_hwcfg( 1988): Setting local bd addr to F8:95:C7:87:85:54
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:00.922 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 5397): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5397): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  269): M: Get netlink event, ifname: wlan0 action: 4
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/Weather4x2_optimus( 2672): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2672): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2672): forecast size is 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2672): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2672): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2672): setTouchIntent, appWidgetId: 2
D/WiFiOffLoadBroadcast( 5407): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5407): S: false, R: false
D/Theme_WeatherAncestor_optimus( 2672): url is : null
D/Theme   ( 2672): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2672): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/WeatherAncestor( 2672): 2 : update view, appWidgetId: 2
I/WifiServiceExtension(  846): setVHTCapabilityType  : false
D/WeatherService( 2672): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:27:0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1988): hw_config_cback state=8
I/bt_hwcfg( 1988): vendor lib fwcfg completed
I/bt-btif ( 1988): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 1988): btu_task received preload complete event
D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=278032789 [*alarm*], flags=0x0
,I/WifiServerServiceExt(  846): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  846): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  846): setSecurityType  : 2
I/        ( 1988): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 1988): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 1988): BTE_InitTraceLevels -- TRC_PROTOCOL,0
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:00.988 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:00.993 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  846): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  846): Got NetworkAgent Messenger
,D/WifiExtManager(  846): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@18ad2c1e
D/WifiExtManager(  846): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@2611cff
D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  846): NetworkAgent connected
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
E/WifiConfigStore(  846): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  846): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  269): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  269): Setting iface cfg
D/DhcpStateMachine(  846): StoppedState
E/WifiStateMachine(  846): Start Dhcp Watchdog 1
,D/DhcpStateMachine(  846): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  846): WaitBeforeStartState
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateGROUP_HANDSHAKE
D/WiFiOffLoadUpdatePriority( 5407): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5407): connected SSID: null
D/WiFiOffLoadUpdatePriority( 5407): private wpa: "NG700" 300
D/WifiServiceImplEx(  846): addOrUpdateNetwork pid=5407, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  846):  uid = 1000 SSID "NG700" nid=0
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:01.051 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateCOMPLETED
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/bt-btif ( 1988): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,I/GKI_LINUX( 1988): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1988): warning : media task started media_task_refcnt 1 
W/bt-smp  ( 1988): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1988): Plain text(LSB ~ MSB) = 36 bc 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1988): Encrypted text(LSB ~ MSB) = 75 b4 5d 36 e6 65 8e 5d 68 7a d4 26 54 1f e5 73 
W/bt-btm  ( 1988): Stopping oneshot timer
D/BT_PROF_AUDIO( 1988): created moving average (N=100)
D/BT_PROF_AUDIO( 1988): reset rate average
W/bt-btif ( 1988): overflow 0, enter 0, exit 0
E/bt-btif ( 1988): Calling BTA_HhEnable
E/bt-btif ( 1988): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1988): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1988): Address is:F8:95:C7:87:85:54
D/BluetoothManagerService(  846): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  846): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 1988): Name is: G3s-1
D/BluetoothAdapterProperties( 1988): Scan Mode:20
D/BluetoothAdapterProperties( 1988): Discoverable Timeout:120
E/bt-btif ( 1988): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1988): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 1988): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1988): BTA_JvEnable
E/bt-btif ( 1988): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 1988): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 1988): init_hci_slots(L136): in
D/IOP_DB_BT( 1988): db_open: file /etc/bluetooth/iop_bt.db
V/BluetoothOppNotification( 1988): new notify threadi!
V/BluetoothOppNotification( 1988): send delay message
D/IOP_DB_BT( 1988): db_open: db_open : handle 2690738140l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1988): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1988): db_query: result 1
I/        ( 1988): iop_db_open: iop_db_open status 0
E/bt-btif ( 1988): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1988): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 1988): bta_pan_co_init
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/bte_conf( 1988): Device ID record 1 : primary
D/bte_conf( 1988):   vendorId            = 00c4
D/bte_conf( 1988):   vendorIdSource      = 0001
D/bte_conf( 1988):   product             = 13a1
D/bte_conf( 1988):   version             = 1000
D/bte_conf( 1988):   clientExecutableURL = 
D/bte_conf( 1988):   serviceDescription  = 
D/bte_conf( 1988):   documentationURL    = 
D/bte_conf( 1988): bte_load_did_conf no section named DID2.
I/bt-btif ( 1988): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1988): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1988): ScanMode =  20
D/BluetoothAdapterProperties( 1988): State =  11
D/BluetoothAdapterProperties( 1988): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 1988): Setting state to 12
I/BluetoothAdapterState( 1988): Bluetooth adapter state changed: 11-> 12
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@381a517b on behalf of 
D/BluetoothAdapterService(1011485758)( 1988): updateAdapterState() - Broadcasting state to 1 receivers.
E/bt-btif ( 1988): btif_hf_upstreams_evt: wrong handle = 12336 
I/bt-btif ( 1988): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1988): opc_state_cb(L140):  opc_state_cb state:0
D/BluetoothManagerService(  846): Message: 60
D/OppService( 1988): onOpcStateChange()
D/BluetoothManagerService(  846): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  846): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/OppService( 1988): Recieved MESSAGE_OPC_ENABLE
D/BluetoothHeadset( 1751): onBluetoothStateChange: up=true
D/BluetoothA2dp(  846): onBluetoothStateChange: up=true
D/LGBluetoothFeatureConfig( 1988): isPrivacyLogsEnabled : true
D/BluetoothA2dp( 1988): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 1988): Entering On State
I/BluetoothAdapterState( 1988): Entering On State from state = 11
D/BluetoothHeadset( 1751): onBluetoothStateChange: up=true
D/BluetoothHeadset(  846): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1751): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
D/BluetoothAdapterService(1011485758)( 1988): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(1011485758)( 1988): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1988): [BTUI] autoConnect() : not allowed
E/BluetoothManagerService(  846): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  846): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothServiceAdapter( 1988): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1988): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 1988): [BTUI]         local_name: G3s-1
I/bt-btif ( 1988): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1988): ops_state_cb(L223):  ops_state_cb state:0
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
D/BluetoothAdapterService(1011485758)( 1988): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(1011485758)( 1988): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1988): [BTUI] autoConnect() : not allowed
D/OppService( 1988): onOpsStateChange() :0
I/bt-btif ( 1988): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1988): operation_cmpl_callback(L192):  oper:3 status:0
,I/BluetoothFTPService( 1988): onFtpServerEnabled: /storage
D/OppService( 1988): Recieved MESSAGE_OPS_ENABLE
D/BluetoothPanServiceJni( 1988): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  846): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
I/bt-btif ( 1988): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  846): Message: 40
D/BluetoothManagerService(  846): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
E/WifiStateMachine(  846): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  846): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  846): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1a7fb3da target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1a7fb3da target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  846): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/LGBluetoothAPIService( 1804): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterProperties( 1988): Scan Mode:21
I/bt-btif ( 1988): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1988): Discoverable Timeout:120
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1375): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
V/LgDhcpStateMachineHelper(  846): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  846): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
,D/DhcpStateMachine(  846): DHCP Start wake lock is acquired.
D/LGBluetoothAPIService( 1804): Message: 1
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
I/BluetoothMapService( 1988): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1988): STATE_ON
V/BluetoothMapService( 1988): Handler(): got msg=1
D/WifiServerServiceExt(  846): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  846): setSupplicantStateCOMPLETED
D/BluetoothMapMasInstance( 1988): Map Service startRfcommSocketListener
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
D/BluetoothMapMasInstance( 1988): MAS initSocket()
D/bt_h4   ( 1988): vendor lib postload completed
D/BluetoothMapMasInstance( 1988):   masId = 00
D/BluetoothMapMasInstance( 1988):   msgTypes = 0e
D/BluetoothMapMasInstance( 1988):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1988):   SDP string = 000eSMS/MMS
D/LGBluetoothAPIService( 1804): MESSAGE_BOOT_COMPLETED
E/WifiConfigStore(  846):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/BluetoothManagerService(  846): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/LGBluetoothAPIService( 1804): [BTUI] LGBluetoothAPIService Binding Success
V/BluetoothOppNotification( 1988): mUpdateCompleteNotification = true
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c4a0c3e
W/BluetoothAdapter( 1988): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothPbapService( 1988): Pbap Service onCreate
V/BluetoothPbapService( 1988): Starting PBAP service
I/bt-btif ( 1988): BTA_JvCreateRecordByUser
I/bt-btif ( 1988): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1988): [BTUI] createSocketChannel FD=84 mFd=0
V/BluetoothMapMasInstance( 1988): Succeed to create listening socket 
D/BluetoothMapMasInstance( 1988): Accepting socket connection...
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
,D/LGBluetoothPbapAdapter( 1988): [BTUI] getInstance : create
V/BluetoothPbapService( 1988): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1988): state: 12
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@31817ff1 on behalf of 
D/LGBluetoothAPIServer( 1988): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1988): [BTUI] onBind()
V/BluetoothOppNotification( 1988): outbound: succ-0  fail-0
V/BluetoothPbapService( 1988): Handler(): got msg=1
I/NotificationManager( 1988): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothPbapService( 1988): Pbap Service startRfcommSocketListener
D/LGBluetoothAPIService( 1804): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1804): Message: 100
D/LGBluetoothAPIService( 1804): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 1988): Pbap Service initSocket
D/BluetoothManagerService(  846): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 1988): outbound notification was removed.
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
W/BluetoothAdapter( 1988): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1988): BTA_JvCreateRecordByUser
,V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@21728a57 on behalf of 
V/BluetoothOppNotification( 1988): inbound: succ-0  fail-0
I/bt-btif ( 1988): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1988): [BTUI] createSocketChannel FD=85 mFd=84
V/BluetoothPbapService( 1988): Succeed to create listening socket 
V/BluetoothPbapService( 1988): Accepting socket connection...
I/NotificationManager( 1988): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1988): inbound notification was removed.
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@3a359944 on behalf of 
E/WifiConfigStore(  846): Setting BSSID for "NG700"WPA_PSK to any
,D/WiFiOffLoadUpdatePriority( 5407):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5407): configuration updated: 0
I/WifiServerServiceExt(  846): set CMD_UPDATE_DEFAULT_PROFILE
D/WiFiOffLoadUpdatePriority( 5407): configuration saved: true
,D/PCSuite ( 5451): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 5407): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ActivityManager(  846): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5508 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
V/BluetoothPbapReceiver( 1988): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1988): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1988): ***********state = 12
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
,D/LocalBluetoothProfileManager( 5407): Adding local A2DP profile
D/BluetoothManagerService(  846): Message: 30
D/LocalBluetoothProfileManager( 5407): Adding local HEADSET profile
D/BluetoothManagerService(  846): Message: 30
D/BluetoothManagerService(  846): Message: 30
,D/BluetoothManagerService(  846): Message: 30
D/LocalBluetoothProfileManager( 5407): Adding local MAP profile
D/BluetoothMap( 5407): Create BluetoothMap proxy object
D/BluetoothManagerService(  846): Message: 30
,D/BluetoothManagerService(  846): Message: 30
D/LocalBluetoothProfileManager( 5407): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 1988): Pbap Service onBind
D/LGBluetoothUserBindClient( 5407): [BTUI] initUserBindClient
W/ContextImpl( 5407): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 5407): finishStartingService: stopping service
D/BluetoothA2dp( 5407): Proxy object connected
,D/A2dpProfile( 5407): Bluetooth service connected
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
D/BluetoothHeadset( 5407): Proxy object connected
D/HeadsetProfile( 5407): Bluetooth service connected
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
D/BluetoothInputDevice( 5407): Proxy object connected
D/DhcpStateMachine(  846): DHCPV4 request on wlan0
D/HidProfile( 5407): Bluetooth service connected
V/LgDhcpStateMachineHelper(  846): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  846): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
D/BluetoothPan( 5407): BluetoothPAN Proxy object connected
D/PanProfile( 5407): Bluetooth service connected
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
,D/BluetoothMap( 5407): Proxy object connected
D/MapProfile( 5407): Bluetooth service connected
D/BluetoothMap( 5407): getConnectedDevices()
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
V/BluetoothMapService( 1988): getConnectedDevices()
D/BluetoothPbap( 5407): Proxy object connected
D/PbapServerProfile( 5407): Bluetooth service connected
D/LGBluetoothUserBindClient( 5407): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 5407): onReceive
I/dhcpcd  ( 5529): version 5.5.6 starting
D/LGBluetoothFeatureConfig( 5407): isPrivacyLogsEnabled : true
,E/dhcpcd  ( 5529): get_duid: Read-only file system
D/LGBluetoothUtils( 5407): [BTUI] FileNotFound: readProperty
I/ActivityManager(  846): Killing 4823:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/LGDMClient( 5508): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5508): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/BluetoothOppReceiver( 1988): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,W/libprocessgroup(  846): failed to open /acct/uid_10086/pid_4823/cgroup.procs: No such file or directory
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/BluetoothOppManager( 1988): restoreApplicationData! falsefalsenullnull
V/BluetoothSapReceiver( 1988): [BTUI] checkServiceStart
,D/LGBluetoothStateChangeReceiver( 1988): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDMClient( 5508): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
D/AuthorizationBluetoothService( 1959): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/dhcpcd  ( 5529): wlan0: rebinding lease of 192.168.1.134
,D/LGDMClient( 5508): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 5451): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/LGDMClient( 5508): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,D/PCSuite ( 5451): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5451): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/dhcpcd  ( 5529): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5529): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  269): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  846): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5548 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  846): Killing 5109:com.google.android.gm/u0a53 (adj 15): empty #11
D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
W/libprocessgroup(  846): failed to open /acct/uid_10053/pid_5109/cgroup.procs: No such file or directory
,V/[BNRBootReceiver]( 5548): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5548): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5548): Boot Receiver Return
,V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 5407): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  846): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  846): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  846): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  846): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  846): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  846): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  846): bShouldSendDhcpAction Result: true
D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
D/LGWifiP2pService(  846): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  846): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  846): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  846): RunningState
E/WifiStateMachine(  846): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/ConnectivityService(  846): ignoring duplicate network state non-change
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:01.789 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
,D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  846): Adding iface wlan0 to network 100
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:01.801 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine(  846): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/WifiHS20(  846): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:01.824 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  846): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 3
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:01.833 DNS addrs= 192.168.1.1, 0.0.0.0, 
E/ConnectivityService(  846): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  846): Adding Route [fe80::/64 -> :: wlan0] to network 100
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  846): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  846): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  846): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  846): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  846): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 3
D/Nat464Xlat(  846): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  846): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846): notifyType PRE,CHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  846):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  846):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  846): currentScore = 0, newScore = 20
D/ConnectivityService(  846):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  846): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/WIFI    (  846): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  846):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  846): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1751): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
E/ConnectivityService(  846): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  846): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] Start DNSResolver start to wait
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] wait 500ms before dns check
D/ConnectivityService(  846): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  846): [e] list.add(nai) empty : false size: 1
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  846): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  846): MasterInitialState.processMessage what=3
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  269): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
,D/ConnectivityService(  846): validation of new default Network = false
D/ConnectivityService(  846): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  846): enableDataServiceNotify 
D/DSQN    (  846): start dsqn bin
D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/DSQN    (  846): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy(  846): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
D/ConnectivityService(  846): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/rmt_storage(  266): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  266): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  266): wakelock acquired: 1, error no: 42
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/DSQN    ( 5596): DSQN samuel.seo ver 141203
E/DSQN    ( 5596): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5596): created command queue thread
I/DSQN    ( 5596): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5596): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
D/ConnectivityService(  846): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
I/PCSuite ( 5451): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5451): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  266): 
I/rmt_storage(  266): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
V/WiFiOffLoadBroadcast( 5407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5407): MCCMNC not supported: null
I/PCSuite ( 5451): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5451): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  846): Killing 3880:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10006/pid_3880/cgroup.procs: No such file or directory
,I/Netd    (  269): M: Get netlink event, ifname: p2p0 action: 6
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] DNSResolver start dns
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  269): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
I/Netd    (  269): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
D/ConnectivityService(  846): identical MTU - not setting
D/Nat464Xlat(  846): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  846): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:02.403 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out(  846): propertyValue:false
D/ConnectivityService(  846): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): [LWD] DNSResolver end dns
D/ConnectivityService(  846): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  846): enableDataServiceNotify 
D/DSQN    (  846): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524295
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Checking http://clients3.google.com/generate_204 on "NG700"
,D/DSQN    (  846): dsqn is running restart
I/DSQN    ( 5606): DSQN samuel.seo ver 141203
E/DSQN    ( 5606): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5606): created command queue thread
I/DSQN    ( 5606): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5606): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 5606): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5606): restart monitoring
,I/DSQN    ( 5606): dsqn report finish
D/LGDataListener(  269): argv[0]=dsqncommand
D/LGDataListener(  269): argv[1]=wlan0
D/LGDataListener(  269): argv[2]=1
D/LGDataListener(  269): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  846): DSQM DsqnNotification wlan0  1
D/DSQN    (  846): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 14:27:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449671222489], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449671222468]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  846): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
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
D/ConnectivityService(  846): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
D/WIFI    (  846): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  846):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiDataContinuityService(  846): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  846): set CMD_CAPTIVE_CHECK_COMPLETED
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/NotificationManager( 1935): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/AudioFlinger(  273): thread 0xb5651000 type 0 TID 1293 going to sleep
,V/AudioFlinger(  273): thread 0xb56eb000 type 0 TID 1294 going to sleep
V/AudioFlinger(  273): thread 0xb5735000 type 0 TID 1297 going to sleep
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-09 15:27:04.069 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/BluetoothAdapterService(1011485758)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@dc1c884
,I/jxcore-log( 5278): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 5278): 
V/WifiInternetCheck(  846): Single check msg out of sync, ignoring.
,D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  846): onReceive
D/LocSvc_java(  846): got connectivity action
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  269): App 1000 tries DNS query. Accept family:0 protocol:0
D/LocSvc_java(  846): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  846): Sending msg: 4 arg1:1 arg2:1
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  846): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  846): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  846): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  846): Sending msg: 5 arg1:0 arg2:1
,D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out(  846): propertyValue:false
,D/GpsLocationProvider(  846): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  846): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5619 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/AlarmManagerService(  846): Setting time of day to sec=1449671225
W/AlarmManagerService(  846): Unable to set rtc to 1449671225: Invalid argument
D/LocSvc_java(  846): NTP server returned: 1449671225258 (Wed Dec 09 15:27:05 GMT+01:00 2015) reference: 106226 certainty: 12 system time offset: 1
D/LocSvc_java(  846): Sending msg: 10 arg1:0 arg2:1
,I/ActivityManager(  846): Start proc com.google.android.gms for service com.google.android.gms/.auth.api.credentials.sync.CredentialSyncService: pid=5654 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/[SystemUI]Clock( 1375): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,I/CalendarProvider2( 5189): onReceive() android.intent.action.TIME_SET
,D/CalendarProvider2( 5189): Scheduling check of next Alarm
D/WeatherService( 2672): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:27:5
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/WeatherService( 2672): 2 : requestRefreshAppWidget, isUpdateStart : false
,I/ActivityManager(  846): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5671 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ActivityManager(  846): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,I/[LGHome]LGDateChangeReceiver( 1877): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=9 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
,D/UpdateThreadPoolManager( 2672): 2 : This is isUpdating : false
D/WeatherService( 2672): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2672): 2 : buildUpdate, appWidgetId: 2
,I/[LGHome]LGCalendarIcon( 1877): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 9
D/WeatherTheme( 2672): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2672): 2 : Fixed theme : optimus
D/WeatherReflect( 2672): 2 : Map key string is -2
D/lim     ( 2672): 2 : time = 15:27
I/WeatherReflect( 2672): Model Name : LG-D722
D/WeatherTheme( 2672): 2 : exactly same view!
D/WeatherTheme( 2672): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2672): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:27:5
I/[LGHome]LGCalendarIcon( 1877): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 9
I/ActivityManager(  846): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5689 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  846): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5706 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5689): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5689): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationManager(  846): android: cancelAsUser(353845882) by android
W/ResourcesManager( 5689): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 5654): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5654): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 5671): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5671): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5671): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/GpsLocationProvider(  846): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/MultiDex( 5654): VM with version 2.1.0 has multidex support
,I/MultiDex( 5654): install
I/MultiDex( 5654): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  846): Process com.android.vending (pid 4870) has died
E/GpsLocationProvider(  846): No APN found to select.
,I/AppConfig( 5689): Total System Memory = 906309632
I/GalleryUtils( 5689): Application Heap = 96 MB
I/AppConfig( 5689): App Tier : NOT_DEF
,D/SystemHelper( 5689): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  846): Process com.android.calendar (pid 5217) has died
,D/LgeGpsConstants(  846): Can't find 'ext_gps.conf'!!
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  269): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
W/ResourcesManager( 5706): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5706): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotificationManager(  846): android: cancelAsUser(-1597574061) by android
I/LGEmail ( 5671): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 5671): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,V/JNIHelp ( 5706): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/art     (  846): Explicit concurrent mark sweep GC freed 80551(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/34MB, paused 2.885ms total 264.553ms
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/MusicStore( 5619): Database version: 120
W/System  ( 5706): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5706): Installed default security provider GmsCore_OpenSSL
I/art     ( 1959): Explicit concurrent mark sweep GC freed 15495(1067KB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 11MB/19MB, paused 1.904ms total 136.642ms
,V/JNIHelp ( 5654): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5619): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ActivityThread( 5654): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5654): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@388b50a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5654): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  846): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=5752 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  269): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 22.528ms
I/NotificationManager( 5654): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5654): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 327us total 23.593ms
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out(  846): propertyValue:false
,D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  269): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out(  846): propertyValue:false
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 383us total 22.175ms
,I/NotificationManager(  846): android: cancelAsUser(-1548111331) by android
,V/WifiInternetCheck(  846): isHttpConnectionAvailable - We got a valid response : 204
I/NotificationManager(  846): android: cancelAsUser(-1597574061) by android
,D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out(  846): propertyValue:false
I/ActivityManager(  846): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5783 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5619): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5619): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/NativeLibraryUtils( 5654): Install completed successfully. count=13 extracted=0
,D/ALBootInit( 5752): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 5752): Alarm ALBootInit: TIME_SET
D/Alarms  ( 5752): [setNextAlert] start
W/ResourcesManager( 5619): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5619): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/YouTube MDX( 5706): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/Alarms  ( 5752): [setNextAlert] (1)
I/art     ( 5706): CheckpointMarkThreadRoots callback created = 0xb042dbb0
D/Alarms  ( 5752):  minTime  = 0
,D/Alarms  ( 5752):  -- OK multi -- 0
E/jeny.kim( 5752): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 5752): [setNextAlert]setNextAlert temp_AlarmLinkText + 
W/ResourcesManager( 5783): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/libc-netbsd( 5706): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5706): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CommonUtil( 5752): BUILD Operator: OPEN
,D/Alarms  ( 5752): broadcastToWidgetProvider : false
D/Alarms  ( 5752): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/JNIHelp ( 5619): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,V/SettingsProvider(  846): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
W/BackupManagerService(  846): dataChanged but no participant pkg='com.android.providers.settings' uid=10010
,I/DigitalAppWidgetProvider( 5752): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 5752): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@323e0fc0
V/DigitalAppWidgetProvider( 5752): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@323e0fc0
,I/art     ( 5706): CheckpointMarkThreadRoots callback created = 0xb4958de0
D/QuickCoverProvider( 5752): onReceiver
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5706): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/ActivityManager(  846): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=5817 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityThread( 5619): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5619): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@297e6d4f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5619): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  846): Killing 5189:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/AndroidMusic( 5619): GMSCore installation verified
,W/ResourcesManager( 5706): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5706): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  846): failed to open /acct/uid_10014/pid_5189/cgroup.procs: No such file or directory
,I/ConfigStore( 5619): Config Database version: 1
W/ResourcesManager( 5817): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 5817): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 5817): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5817): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@215f4da7, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@35672254, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@a5765fd, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@26f7b2f2, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@29291d43, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@323e0fc0, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3bb964f9, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3c4a0c3e, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@31364a9f, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@14d467ec, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@22a257b5, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@d6ae4a, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1bbef1bb, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2f9616d8, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@edba31, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@6d96516, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2c60ee97, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@dc1c884, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@b2c86d, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@367ebca2, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@18bbdd33, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@dd4e8f0, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1c407e69, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1c3000ee, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@6cd198f, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@36b7a41c, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@9d99825, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@f9f3dfa, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@150bbfab, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@33a8e608, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@273091a1, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3f933fc6, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@844ab87, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@22ea5ab4, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@20a3a6dd, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2e739252, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3b367923, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@232c6e20, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1038d3d9, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2b94819e, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2bed847f, lg_preferences_recent_ti,mezones=com.android.calendar.adaptation.PreferenceKey$KeyData@bba4c4c, lg_
,D/GeneralPreferenceUtils( 5817): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5817): [init]
I/Config  ( 5817): LGCalendar ver.4.40.17
,I/Config  ( 5817): start check model
I/Config  ( 5817): start check native_ca
,I/Config  ( 5817): Config Operator=OPEN, Country=EU
D/Config  ( 5817): [setDefaultValuesToPref]
D/Config  ( 5817): [parseProfiles]
D/ProfilesParser( 5817): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5817): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5817): [updateProfiletoCountryInfo]
D/GeneralPreference( 5817): [checkAndMigrateOldPreference]
I/ActivityManager(  846): Process com.lge.bnr (pid 5548) has died
,E/AgendaWidgetManager( 5817): [updateWidgets] 
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 5654): [CredentialSyncAdapter] Unknown sync event.
,I/dex2oat ( 5841): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-62999011.jar --oat-fd=42 --oat-location=/data/data/com.google.android.youtube/cache/ads-62999011.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/NotificationManager( 5706): com.google.android.youtube: cancel(2) by com.google.android.youtube
,I/NotificationManager(  846): android: cancelAsUser(-591465577) by android
,D/ConnectivityService(  846): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  846): dumpNetworkRequest
D/ConnectivityService(  846):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  846):     Requests:
D/ConnectivityService(  846):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846):     Lingered:
D/ConnectivityService(  846): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  846): apparently satisfied.  currentScore=60
D/ConnectivityService(  846): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 5654): CM callback handler got msg 524290
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5706): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5706): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5706): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 5706): Found 10006
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5706): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/MediaRouter( 5619): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5619): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5619): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  846): Process com.lge.lgdmsclient (pid 5508) has died
,I/dex2oat ( 5841): dex2oat took 291.389ms (threads: 4)
,I/NetworkMonitor( 5619): type=WIFI subType= reason=null isConnected=true
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5654): Loading module APK com.google.android.play.games
I/GHttpClientFactory( 5619): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/DriveInitializer( 5654): Awaiting to be initialized
W/DriveInitializer( 5654): Background init thread started
,I/GoogleURLConnFactory( 5619): Using platform SSLCertificateSocketFactory
I/art     ( 5654): CheckpointMarkThreadRoots callback created = 0xb042d5e0
,D/eas_req ( 5671): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/libc-netbsd( 5706): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5706): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5706): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5706): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  269): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out( 5706): propertyValue:false
D/libc-netbsd( 5706): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5706): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5654): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
I/ActivityManager(  846): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5900 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     ( 5654): CheckpointMarkThreadRoots callback created = 0xb0562c60
I/InitNotificationRingtoneService( 5817): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 5817): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
D/MonthWidgetProvider( 5817): [onReceive]
D/CalendarWidgetProvider( 5817): [onReceive]
D/CalendarWidgetProvider( 5817): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5817): [onUpdateAndInitCalendarTime]
W/HolidayIntentService( 5817): onHandleIntent
,D/HolidayDataLoader( 5817): readJsonAsset : holiday.json
I/ActivityManager(  846): Process com.lge.settings.easy (pid 5471) has died
D/WeekWidgetProvider( 5817): [onReceive]
D/CalendarWidgetProvider( 5817): [onReceive]
D/CalendarWidgetProvider( 5817): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 5817): [onUpdateAndInitCalendarTime]
D/WeatherAncestor( 2672): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:27:7
D/UpdateThreadPoolManager( 2672): 2 : This is isUpdating : false
,D/Weather_cast( 2672): 2 : set auto-update time : 12/9 18:27
,D/WeatherAncestor( 2672): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:27:7
D/WeatherService( 2672): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
I/HubEmail( 5671): JNI_OnLoad()
I/HubEmail( 5671): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5671): registerNatives()
I/HubEmail( 5671): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5671): registerNativeMethods()
I/HubEmail( 5671): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 5671): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  846): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5922 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2672): 2 : Utils getTopActivity com.lge.launcher2 / true
I/AlertUtils( 5817): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,E/HolidayIntentService( 5817): onHandleIntent:holiday data empty
D/WeatherService( 2672): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2672): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/Settings( 5671): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/NotificationManager( 5619): com.google.android.music: cancel(1061) by com.google.android.music
,I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
D/libc-netbsd( 5706): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5706): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/DriveInitializer( 5654): Background init thread ended
I/art     (  846): Explicit concurrent mark sweep GC freed 25223(1279KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.795ms total 165.896ms
,I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/ActivityManager(  846): Process com.android.settings (pid 5407) has died
I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5817): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,D/LGDMClient( 5900): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 5900): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/AlertUtils( 5817): set default noti to content://media/internal/audio/media/38
W/ContextImpl( 5900): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,I/InitNotificationRingtoneService( 5817): End InitializeAlertRingtoneService.onHandleIntent
W/ContextImpl( 5900): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
I/NotificationManager( 5706): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,D/LGDMClient( 5900): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 5900): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/TimeService( 5922): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449671228348
D/        ( 5922): TimeServiceNative: User Time to be set is 1449671228348
D/QC-time-services( 5922): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 5922): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5922): Lib:time_genoff_operation: pargs->ts_val = 1449671228348
D/QC-time-services( 5922): Lib:time_genoff_operation: Send to server  passed!!
D/LGDMClient( 5900): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/QC-time-services(  320): Daemon: Connection accepted:time_genoff
D/QC-time-services(  320): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449671228348
D/QC-time-services(  320): Daemon:genoff_opr: Base = 2, val = 1449671228348, operation = 0
D/QC-time-services(  320): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/21/70 18:28:55
D/QC-time-services(  320): Daemon:Value read from RTC seconds = 9570535000
D/QC-time-services(  320): Daemon:new time 1449671228348 
D/QC-time-services(  320): Daemon: delta 1440100693348 genoff 1440100693348 
D/QC-time-services(  320): Daemon:genoff_persistent_update: Writing genoff = 1440100693348 to memory
D/QC-time-services(  320): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  320): Daemon:time_persistent_memory_opr:Genoff write operation 
I/LGDMClient( 5900): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 1959): propertyValue:false
D/QC-time-services(  320): Updating the TOD offset
D/QC-time-services(  320): Daemon:genoff_persistent_update: Writing genoff = 1440100693348 to memory
D/QC-time-services(  320): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  320): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  320): Daemon:Update to modem bit set
D/QC-time-services(  320): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 5922): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  320): Daemon: Base = 2, Value being sent to MODEM = 1124135893348
E/QC-time-services(  320): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  320): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=5966 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ContextImpl( 5900): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 5900): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 5900): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 5900): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 5900): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 5900): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/NotificationManager(  846): android: cancelAsUser(-591465577) by android
,I/NotificationManager(  846): android: cancelAsUser(353845882) by android
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     ( 1959): Explicit concurrent mark sweep GC freed 18092(930KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 11MB/19MB, paused 2.179ms total 84.507ms
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AccountUtils( 5654): 0 accounts found with uca feature
,I/GamesSyncAdapter( 5654): Starting sync for 3a3529a
I/AppUp4:AppBoxCP( 5966): onCreate
,W/AppUp4:DB( 5966):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5966):  setFingerPrint start
I/AppUp4:DB( 5966):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5966):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5966):  SDK version = 0
I/AppUp4:DB( 5966):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5966): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 5966): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 5966): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 5966): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 5966): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 5966): onReceive
,I/AppUp4:CustModeStarterReceiver( 5966): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 5966): Context : android.app.ReceiverRestrictedContext@29291d43
D/AppUp4:CustFacade( 5966): isCustomizationCompleted : false
,I/CheckinService( 5654): Checkin interval check for package: unspecified last checkin: 1449594679709 min interval config: 0 actual interval: 76548928
D/AppUp4:CustFacade( 5966): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5966): begin check event
I/AppUp4:CustModeStarterReceiver( 5966): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 5966): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 5966): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 5966): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 5966): handleAsyncCustNotification do not startCustService
I/ActivityManager(  846): Killing 4650:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/NotificationManager( 5654): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/NotificationManager( 1959): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  846): Process com.lge.qremote (pid 4954) has died
,E/lowmemorykiller(  242): Error opening /proc/4650/oom_score_adj; errno=2
W/ActivityManager(  846): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  846): android.os.DeadObjectException
W/ActivityManager(  846): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  846): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  846): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  846): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  846): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  846): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  846): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  846): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  846): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  846): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
,W/ActivityManager(  846): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  846): android.os.DeadObjectException
W/ActivityManager(  846): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  846): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  846): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  846): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  846): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  846): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  846): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  846): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  846): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  846): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  846): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  846): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/libprocessgroup(  846): failed to open /acct/uid_10089/pid_4650/cgroup.procs: No such file or directory
W/BaseAppContext( 5654): Using Auth Proxy for data requests.
,I/LgeMiscReceiver( 3096): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3096): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3096): networkInfo.isConnected() = true
D/PhoneState( 3096): setPdpRejectCasuse : false
,I/ActivityManager(  846): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5998 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/BaseAppContext( 5654): Using Auth Proxy for data requests.
,W/art     ( 5783): Attempt to remove local handle scope entry from IRT, ignoring
,W/BaseAppContext( 5654): Using Auth Proxy for data requests.
,W/BaseAppContext( 5654): Using Auth Proxy for data requests.
,D/libc-netbsd( 5783): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5783): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  269): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  269): App 10086 tries DNS query. Accept family:2 protocol:0
W/BaseAppContext( 5654): Using Auth Proxy for data requests.
D/libc-netbsd( 5706): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5706): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5706): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5706): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  269): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
I/NotificationManager(  846): android: cancelAsUser(-1874035846) by android
,W/BaseAppContext( 5654): Using Auth Proxy for data requests.
D/PhoneMonitor( 5998): Register our PhoneStateListener
,D/libc-netbsd(  269): res_queryN name = xxxxx succeed
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out( 5706): propertyValue:false
D/libc-netbsd( 5706): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5706): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/MobileConnectivityChangeReceiver( 5998): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5998): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  846): Process com.lge.clock (pid 5752) has died
,D/libc-netbsd( 5706): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5706): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinService( 5654): Checkin interval check for package: unspecified last checkin: 1449594679709 min interval config: 0 actual interval: 76549574
I/NotificationManager(  846): android: cancelAsUser(353845882) by android
V/DownloadManager( 3117): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3117): DownloadService onCreate
,D/PhoneMonitor( 5998): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/DownloadManager( 3117): in removeSpuriousFiles
V/TelephonyAutoProfiling( 5998): [loadFeatureFromXml] *** start feature loading from xml
I/NotificationManager( 3117): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/TelephonyAutoProfiling( 5998): [parse] Load xml
,V/DownloadManager( 3117): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/TelephonyAutoProfiling( 5998): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5998): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5998): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@2b94819e on behalf of 3117
,I/ActivityManager(  846): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6039 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3117): DownloadService onStartCommand
I/DownloadManager( 3117): in trimDatabase
V/DownloadManager( 3117): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@bba4c4c on behalf of 3117
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@1059d495 on behalf of 3117
I/ActivityManager(  846): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6055 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,V/DownloadManager( 3117): DownloadService onDestroy
,I/CheckinService( 5654): Disabling old GoogleServicesFramework version
,D/DrmBroadcastReceiver( 6039): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6039): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6039): Service onCreate
D/DrmService( 6039): Received new request = 2
D/WeatherAncestor( 2672): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:9
,D/UpdateThreadPoolManager( 2672): 2 : This is isUpdating : false
I/DrmSntpClient( 6039): Start Sync process
D/DrmSntpClient( 6039): Server : 0
D/WeatherAncestor( 2672): connectivity changed - connection : true
,I/CheckinService( 5654): Checking schedule, now: 1449671229585 next: 1449594709645
I/CheckinService( 5654): active receiver: enabled
D/Weather_cast( 2672): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2672): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:9
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WeatherService( 2672): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd( 6039): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6039): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  269): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
,W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2672): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2672): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2672): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/CheckinService( 5654): Preparing to send checkin request
I/EventLogService( 5654): Accumulating logs since 1449670679213
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out( 6039): propertyValue:false
I/LGDrmClient( 6039): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  278): eDRM_SetDRMTime +++
I/LGDRM   (  278): [DRM] SET TIME : YR=2015, MON=12, DAY=9
I/LGDRM   (  278): [DRM] SET TIME : HR=14, MIN=27, SEC=8
,V/ILGDrmService(  278): eDRM_SetDRMTime ---
,I/DrmSntpClient( 6039): Synched
,D/DrmService( 6039): Completed !! request = 2
D/DrmService( 6039): Request count = 0
V/DrmService( 6039): Service onDestroy
I/ActivityManager(  846): Killing 5451:com.lge.sync/1000 (adj 15): empty #11
I/art     ( 5654): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 5654): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_5451/cgroup.procs: No such file or directory
,I/iu.SyncManager( 5654): SYNC; picasa accounts
,D/NetworkLogImpl( 5654): Loaded NetworkSpeedPredictor
I/iu.Environment( 5654): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  846): Process com.google.android.youtube (pid 5706) has died
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 5654): num queued entries: 0
,I/iu.UploadsManager( 5654): num updated entries: 0
I/iu.SyncManager( 5654): NEXT; no task
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6096 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 1959): propertyValue:false
I/GAv4    ( 6055): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6055):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6055):   adb logcat -s GAv4
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 6055): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GamesSyncAdapter( 5654): User is not G+ enabled. Aborting sync
I/GamesSyncAdapter( 5654): Sync duration for 3a3529a: 1630
,W/GAv4    ( 6055): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6055): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6055): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{23ffc473 type 2 when 111380 com.android.providers.calendar} when 111380
,I/art     (  846): Explicit concurrent mark sweep GC freed 20435(966KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 7.295ms total 220.689ms
I/GCM     ( 1959): GCM config loaded
W/art     ( 6055): Suspending all threads took: 5.781ms
,I/NotificationManager( 5783): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,W/ResourcesManager( 6096): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  846): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6128 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5654): Module APK com.google.android.play.games already loaded
,W/SQLiteConnectionPool( 5654): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager(  846): Process com.google.android.music:main (pid 5619) has died
,W/ResourcesManager( 6055): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6055): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
I/NotificationManager(  846): android: cancelAsUser(2145784878) by android
,I/art     ( 6055): CheckpointMarkThreadRoots callback created = 0xaaf29250
,W/ResourcesManager( 6055): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6055): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ContextImpl( 6055): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
,V/JNIHelp ( 6055): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/art     ( 6055): CheckpointMarkThreadRoots callback created = 0xb0512a80
,I/CheckinRequestBuilder( 5654): Checkin reason type: 8 attempt count: 1
,W/System  ( 6055): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6055): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager( 6128): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6128): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/ActivityThread( 5654): Failed to find provider info for com.google.android.wearable.settings
,V/JNIHelp ( 6128): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/PeopleSync( 5654): onPerformSync() [5005f081]
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5654): Module APK com.google.android.play.games already loaded
W/System  ( 6128): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6128): Installed default security provider GmsCore_OpenSSL
D/WifiServiceImplEx(  846): acquireWifiLock pid=6055, uid=10058, packageName=com.google.android.apps.docs, tag=BaseSyncManager
I/art     ( 1959): Explicit concurrent mark sweep GC freed 14183(907KB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 11MB/19MB, paused 2.008ms total 121.259ms
,I/NotificationManager( 5654): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6055): com.google.android.apps.docs: cancel(1) by com.google.android.apps.docs
,W/Flag    ( 6055): Duration spec must be at least 2 characters long
,I/PeopleDatabaseHelper( 5654): cleanUpNonGplusAccounts done.
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 6055): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6055): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6055): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6055): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10058
D/DnsProxyListener(  269): App 10058 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
I/Babel_SMS( 6096): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6096): MmsConfig.loadMmsSettings
,W/art     ( 6128): Suspending all threads took: 15.093ms
I/Babel_SMS( 6096): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6096): MmsConfig.loadFromDatabase
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 6055): propertyValue:false
,E/YouTube MDX( 6128): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
E/Babel_SMS( 6096): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6096): MmsConfig.loadFromResources
E/Babel_SMS( 6096): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6096): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/libc-netbsd( 6128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 6128): CheckpointMarkThreadRoots callback created = 0xb042d850
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,I/art     ( 6128): CheckpointMarkThreadRoots callback created = 0xb4958de0
W/ContextImpl( 6128): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
D/libc-netbsd( 6055): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6055): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/InstanceID/Rpc( 5654): Found 10006
D/SensorManager( 6096): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6096): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6096): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6096): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6096): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6096): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6096): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6096): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6096): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6096): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6096): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6096): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6096): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6096): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6096): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6096): found sensor: Motion Accel, handle=46
,W/ResourcesManager( 6128): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6128): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/art     ( 6096): Suspending all threads took: 10.109ms
,I/art     ( 6096): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/art     ( 6096): CheckpointMarkThreadRoots callback created = 0xb042d850
,E/DefaultHttpIssuer( 6055): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 6055): java.io.IOException
E/DefaultHttpIssuer( 6055): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 6055): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 6055): 	at dlq.a(PG:18080)
E/DefaultHttpIssuer( 6055): 	at dlt.run(PG:9611)
E/DefaultHttpIssuer( 6055): 	at dlr.run(PG:3031)
E/BaseSyncManager( 6055): ClientFlagSyncException
E/BaseSyncManager( 6055): ccd$a: IO Exception opening: https://ssl.gstatic.com/docs/android/drive/client_flags?1449671231194= Socket is closed
E/BaseSyncManager( 6055): 	at ccd.a(PG:1108)
E/BaseSyncManager( 6055): 	at dlq.a(PG:18060)
E/BaseSyncManager( 6055): 	at dlt.run(PG:9611)
E/BaseSyncManager( 6055): 	at dlr.run(PG:3031)
E/BaseSyncManager( 6055): Caused by: java.net.SocketException: Socket is closed
E/BaseSyncManager( 6055): 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.checkOpen(SourceFile:251)
E/BaseSyncManager( 6055): 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.access$000(SourceFile:58)
E/BaseSyncManager( 6055): 	at com.google.android.gms.org.conscrypt.t.write(SourceFile:760)
E/BaseSyncManager( 6055): 	at iat.a_(PG:78)
E/BaseSyncManager( 6055): 	at iae.a_(PG:155)
E/BaseSyncManager( 6055): 	at iaw.flush(PG:221)
E/BaseSyncManager( 6055): 	at hyh$d.b(PG:381)
E/BaseSyncManager( 6055): 	at hyt.a(PG:279)
E/BaseSyncManager( 6055): 	at hya.a(PG:10245)
E/BaseSyncManager( 6055): 	at hxn$a.a(PG:890)
E/BaseSyncManager( 6055): 	at hvz.a(PG:50089)
E/BaseSyncManager( 6055): 	at hvz$a.a(PG:230)
E/BaseSyncManager( 6055): 	at hvz.a(PG:3201)
E/BaseSyncManager( 6055): 	at clz.a(PG:127)
E/BaseSyncManager( 6055): 	at cjr.a(PG:47)
E/BaseSyncManager( 6055): 	at cjq.a(PG:22)
E/BaseSyncManager( 6055): 	at cjs.a(PG:68)
E/BaseSyncManager( 6055): 	at cjw.b(PG:92)
E/BaseSyncManager( 6055): 	at cjw.a(PG:80)
E/BaseSyncManager( 6055): 	at cju.b(PG:5140)
E/BaseSyncManager( 6055): 	at cju.a(PG:1096)
E/BaseSyncManager( 6055): 	at ccd.a(PG:2062)
E/BaseSyncManager( 6055): 	... 3 more
,I/ActivityManager(  846): Process com.lge.email (pid 5671) has died
W/Settings( 6096): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6096): startup - clean
I/ActivityManager(  846): Process com.android.calendar (pid 5817) has died
,I/PeopleSync( 5654): Setting subscription: result=true [5005f081]
I/PeopleSync( 5654): Starting sync, feed=null [5005f081]
,I/Babel   ( 6096): deleted: false for 0
I/dex2oat ( 6206): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-62999011.jar --oat-fd=42 --oat-location=/data/data/com.google.android.youtube/cache/ads-62999011.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/NotificationManager( 6128): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6128): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6128): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6128): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
I/ActivityManager(  846): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6220 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  302): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 24.396ms
,I/dex2oat ( 6206): dex2oat took 136.944ms (threads: 4)
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.912ms
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/InstanceID/Rpc( 6128): Found 10006
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.310ms
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 1959): propertyValue:false
W/AudioCapabilities( 6096): Unsupported mime audio/x-lg-flac
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6128): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
W/AudioCapabilities( 6096): Unsupported mime audio/adpcm
W/AudioCapabilities( 6096): Unsupported mime audio/g726
W/AudioCapabilities( 6096): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6096): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6096): Unsupported mime video/mjpg
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/VideoCapabilities( 6096): Unsupported mime video/theora
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/BaseAppContext( 5654): Using Auth Proxy for data requests.
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/BaseAppContext( 5654): Using Auth Proxy for data requests.
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/AudioCapabilities( 6096): Unsupported mime audio/evrc
W/AudioCapabilities( 6096): Unsupported mime audio/qcelp
W/VideoCapabilities( 6096): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6096): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6096): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6096): Unsupported mime audio/evrc
W/BaseAppContext( 5654): Using Auth Proxy for data requests.
,W/VideoCapabilities( 6096): Unsupported mime video/mp4v-esdp
I/PeopleSync( 5654): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/libc-netbsd( 6128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  269): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 6128): propertyValue:false
D/libc-netbsd( 6128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/VideoCapabilities( 6096): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6096): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6096): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6096): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6096): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  846): Process com.android.gallery3d (pid 5689) has died
,I/vclib   ( 6096): onServiceConnected
W/Babel   ( 6096): Attempted to change video mute state without an active call.
,I/NotificationManager( 6128): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,D/libc-netbsd( 6096): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6096): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6096): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6096): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  269): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 6096): propertyValue:false
I/NotificationManager( 6096): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/NotificationManager(  846): android: cancelAsUser(2) by android
D/libc-netbsd( 6128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Babel   ( 6096): connection state changed from UNKNOWN to CONNECTED
I/NotificationManager( 1959): com.google.android.gms: cancel(0) by com.google.android.gms
,I/NotificationManager(  846): android: cancelAsUser(2) by android
I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/NotificationManager( 1959): com.google.android.gms: cancel(0) by com.google.android.gms
,D/libc-netbsd( 6055): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6055): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6055): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6055): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10058
D/DnsProxyListener(  269): App 10058 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6220): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6220): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out( 6055): propertyValue:false
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6220): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6220): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6220): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6220):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6220):   adb logcat -s GAv4
D/libc-netbsd( 6055): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6055): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/GAv4    ( 6220): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6220): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6220): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/ActivityManager(  846): Process com.qualcomm.timeservice (pid 5922) has died
E/DefaultHttpIssuer( 6055): Attempt to consume entity of HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 6055): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 6055): java.io.IOException
E/DefaultHttpIssuer( 6055): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 6055): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 6055): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 6055): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 6055): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 6055): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 6055): 	at dlr.run(PG:3031)
E/BaseSyncManager( 6055): IOException
E/BaseSyncManager( 6055): java.io.IOException: stream was reset: PROTOCOL_ERROR
E/BaseSyncManager( 6055): 	at hzd.b(PG:145)
E/BaseSyncManager( 6055): 	at hya.b(PG:104)
E/BaseSyncManager( 6055): 	at hxn.d(PG:917)
E/BaseSyncManager( 6055): 	at hxn.a(PG:95)
E/BaseSyncManager( 6055): 	at hxn$a.a(PG:902)
E/BaseSyncManager( 6055): 	at hvz.a(PG:50089)
E/BaseSyncManager( 6055): 	at hvz$a.a(PG:230)
E/BaseSyncManager( 6055): 	at hvz.a(PG:3201)
E/BaseSyncManager( 6055): 	at clz.a(PG:127)
E/BaseSyncManager( 6055): 	at cjr.a(PG:47)
E/BaseSyncManager( 6055): 	at cjq.a(PG:22)
E/BaseSyncManager( 6055): 	at cjs.a(PG:68)
E/BaseSyncManager( 6055): 	at cjw.b(PG:92)
E/BaseSyncManager( 6055): 	at cjw.a(PG:80)
E/BaseSyncManager( 6055): 	at cju.b(PG:5140)
E/BaseSyncManager( 6055): 	at cju.a(PG:1096)
E/BaseSyncManager( 6055): 	at dlh.b(PG:14062)
E/BaseSyncManager( 6055): 	at dlh.a(PG:140)
E/BaseSyncManager( 6055): 	at dqo.a(PG:224)
E/BaseSyncManager( 6055): 	at dlt.run(PG:9618)
E/BaseSyncManager( 6055): 	at dlr.run(PG:3031)
,D/WifiServiceImplEx(  846): releaseWifiLock pid=6055, uid=10058, packageName=com.google.android.apps.docs
I/NotificationManager( 1959): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  846): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6282 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/NotificationManager(  846): android: cancelAsUser(-1488629395) by android
,W/BaseAppContext( 5654): Using Auth Proxy for data requests.
W/BaseAppContext( 5654): Using Auth Proxy for data requests.
,W/ResourcesManager( 6282): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/NotificationManager( 6055): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
W/ResourcesManager( 6282): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/BaseAppContext( 5654): Using Auth Proxy for data requests.
W/BaseAppContext( 5654): Using Auth Proxy for data requests.
,I/MultiDex( 6282): VM with version 2.1.0 has multidex support
I/MultiDex( 6282): install
I/MultiDex( 6282): VM has multidex support, MultiDex support library is disabled.
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/art     ( 1959): Explicit concurrent mark sweep GC freed 15264(946KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 11MB/19MB, paused 1.706ms total 83.008ms
,W/BaseAppContext( 5654): Using Auth Proxy for data requests.
V/JNIHelp ( 6282): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/BaseAppContext( 5654): Using Auth Proxy for data requests.
,W/BaseAppContext( 5654): Using Auth Proxy for data requests.
,W/ActivityThread( 6282): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6282): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a33d8e4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6282): Installed default security provider GmsCore_OpenSSL
I/art     (  846): Explicit concurrent mark sweep GC freed 26956(1348KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/34MB, paused 2.333ms total 162.194ms
,I/NotificationManager( 6282): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6282): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 6282): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 6282): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 5654): propertyValue:false
I/WebViewFactory( 6220): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  846): Process com.lge.lgdmsclient (pid 5900) has died
,D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  846): android: cancelAsUser(-379682945) by android
I/ActivityManager(  846): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6327 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/LibraryLoader( 6220): Time to load native libraries: 18 ms (timestamps 4221-4239)
I/LibraryLoader( 6220): Expected native library version number "",actual native library version number ""
,D/WVCdm   (  273): Instantiating CDM.
D/NativeLibraryUtils( 6282): Install completed successfully. count=13 extracted=0
,I/WVCdm   (  273): CdmEngine::OpenSession
I/WVCdm   (  273): Level3 Library Dec 11 2014 16:13:16
D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/WebViewChromiumFactoryProvider( 6220): Binding Chromium to main looper Looper (main, tid 1) {13b14314}
I/LibraryLoader( 6220): Expected native library version number "",actual native library version number ""
,D/libc-netbsd( 6128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  269): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 6128): propertyValue:false
I/chromium( 6220): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/libc-netbsd( 6128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/BrowserStartupController( 6220): Initializing chromium process, singleProcess=true
,W/art     ( 6220): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6220): ApplicationContext is null in ApplicationStatus
W/WVCdm   (  273): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  273): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  273): L1 library not specified. Falling Back to L3
,I/GoogleURLConnFactory( 6282): Using platform SSLCertificateSocketFactory
,D/libc-netbsd( 6128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 6282): propertyValue:false
W/chromium( 6220): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6220): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6220): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6220): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6220): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6220): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6220): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6220): Remote Branch: 
I/Adreno-EGL( 6220): Local Patches: 
I/Adreno-EGL( 6220): Reconstruct Branch: 
I/WVCdm   (  273): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  273): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  273): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  273): CdmEngine::GenerateKeyRequest
D/WVCdm   (  273): PrepareKeyRequest: nonce=1983661680
,D/libc-netbsd( 6282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/AudioPolicyService(  273): registerClient() client 0xb41440c0, uid 10079
,W/AudioManagerAndroid( 6220): Requires BLUETOOTH permission
,I/NSApplication( 6220): Starting up...
I/ActivityManager(  846): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6372 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     ( 6282): CheckpointMarkThreadRoots callback created = 0xb042f130
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 114823130430; DSPS: 3853888; Offset : -2790256731
,I/Gmail   ( 6327): getAccountsCursor
,I/art     ( 6282): CheckpointMarkThreadRoots callback created = 0xaae47e20
,W/GAV2    ( 6327): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  846): Process com.lge.appbox.client (pid 5966) has died
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5654): Explicit concurrent mark sweep GC freed 23990(1645KB) AllocSpace objects, 15(240KB) LOS objects, 24% free, 13MB/18MB, paused 1.864ms total 279.608ms
I/ActivityManager(  846): Process com.google.android.setupwizard (pid 5998) has died
,W/ActivityManager(  846): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  846): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/Gmail   ( 6327): Sync started for account: account:61035162
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Gmail   ( 6327): Error finding the version of the Email provider.....
E/Gmail   ( 6327): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6327): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6327): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6327): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6327): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6327): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6327): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6327): We do not support migrating this version of the Email provider.
I/Gmail   ( 6327): Observing account changes for notifications
I/Gmail   ( 6327): getAccountsCursor
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [80] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/VacuumService( 1959): Vacuum at: now=1449671234343 tag=VacuumService
,I/Gmail   ( 6327): notifyAccountChanged
,D/LocationInitializer( 5654): Restart initialization of location
,I/Gmail   ( 6327): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/GCM     ( 1959): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Gmail   ( 6327): notifyAccountChanged
D/AuthorizationBluetoothService( 1959): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/Gmail   ( 6327): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1959): com.google.android.gms: cancel(0) by com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 5654): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1959): location=null
I/Gmail   ( 6327): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6327): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  846): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6422 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/MusicWidget( 2609): mDelayedStopHandler : unbind
,I/MusicBrowser( 2061): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2061): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2061): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2061): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2061): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2061): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2061): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2061): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  846):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@dd4e8f0com.lge.music.MediaPlaybackService$6@1c407e69
D/MusicBrowser( 2061): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2061): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/WVCdm   (  273): CdmEngine::OpenSession
,I/art     ( 1959): Explicit concurrent mark sweep GC freed 21528(1253KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/19MB, paused 1.701ms total 75.101ms
,I/ActivityManager(  846): Process com.lge.drmservice (pid 6039) has died
,I/MusicBrowser( 2061): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/art     (  846): Explicit concurrent mark sweep GC freed 23481(1074KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.156ms total 160.349ms
I/MusicBrowser( 2061): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicBrowser( 2061): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@31364a9f
,I/MusicBrowser( 2061): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/DigitalAppWidgetProvider( 6422): onReceive: android.intent.action.ALARM_CHANGED
I/MusicBrowser( 2061): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2061): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2061): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2061): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2061): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/Gmail   ( 6327): getAccountsCursor
,I/MusicBrowser( 2061): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2061): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/WeatherAncestor( 2672): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:27:15
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UpdateThreadPoolManager( 2672): 2 : This is isUpdating : false
I/MusicBrowser( 2061): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2061): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo ,
D/Weather_cast( 2672): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
I/Gmail   ( 6327): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12087, normalSync: true
D/WeatherAncestor( 2672): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:27:15
D/WeatherService( 2672): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,I/MusicBrowser( 2061): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2061): [MediaPlaybackService.java:6745:release()] oooooo 
W/ActivityManager(  846): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2672): 2 : Utils getTopActivity com.lge.launcher2 / true
I/MusicBrowser( 2061): [MediaPlaybackService.java:6706:stop()] oooooo 
D/WeatherService( 2672): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2672): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/MediaPlayer[Native]( 2061): reset
I/Gmail   ( 6327): getAccountsCursor
,V/MediaPlayer[Native]( 2061): setListener
V/MediaPlayer[Native]( 2061): disconnect
V/MediaPlayer[Native]( 2061): destructor
V/AudioFlinger(  273): releasing 19 from 2061 for -1
V/AudioFlinger(  273):  decremented refcount to 0
V/AudioFlinger(  273): purging stale effects
,V/MediaPlayer[Native]( 2061): disconnect
D/MusicBrowser( 2061): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2061): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2061): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2061): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2061): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2061): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2061): [SmartShareManagerClient] unregisterListener: 472908014
W/SmartShareClient( 2061): [SmartShareManagerClient] unregisterListener invalid listener: 472908014
I/SmartShareClient( 2061): [SmartShareManagerClient] terminate service: 2061/MediaPlaybackService/173499901
E/HomeCloudIF( 2061): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2061): [SmartShareManagerClient] unbindService context:android.app.Application@6cd198f
,I/ActivityManager(  846): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6446 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Volley  ( 5654): [680] BasicNetwork.performRequest: Unexpected response code 410 for https://www.googleapis.com/plus/v2whitelisted/people/me/people/all?prettyPrint=false&fields=items(etag,id,names,nicknames,images,urls,sortKeys,taglines,emails,phoneNumbers,addresses,metadata,memberships,legacyFields/mobileOwnerId),nextPageToken,nextSyncToken&customResponseMaskingType=menagerie&includeAffinity=gplusAutocomplete&includeAffinity=chatAutocomplete&includeAffinity=emailAutocomplete&includeOthers=true&maxResults=100&orderBy=modified&syncToken=CNvSy9mXKhIBMRjbEioECAEQAQ
I/PeopleSync( 5654): Sync Token out of date, syncing all people/gaia-map
,V/CloudHub( 2061): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2061): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2061): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2061): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2061): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2061): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29987
,W/ResourcesManager( 6446): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/UdcCache:FPQuery( 5654): Bootstrapping UDC settings cache for all accounts
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6327): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6327): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/GAv4-SVC( 5654): Google Analytics 8.3.01 is starting up.
D/CalendarProvider2( 6446): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@14a09ec1
,V/JNIHelp ( 6327): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/CalendarProvider2( 6446): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6446): Created com.android.providers.calendar.CalendarAlarmManager@26f7b2f2(com.android.providers.calendar.CalendarProvider2@14a09ec1)
D/CalendarProviderBroadcastReceiver( 6446): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 6446): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6446): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6446): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 6446): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 6446): [IntentService] Release Lock
D/CalendarProvider2( 6446): CalendarProviderIntentService.onDestroy()
,W/System  ( 6327): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6327): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/art     ( 6096): WaitForGcToComplete blocked for 60.149ms for cause HomogeneousSpaceCompact
,W/ContextImpl( 3352): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,E/MDM     ( 1732): [82] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1959): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 5654): Restart initialization of location
D/AuthorizationBluetoothService( 1959): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1959): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 5654): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1959): location=null
D/libc-netbsd( 6327): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6327): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6327): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6327): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10053
D/DnsProxyListener(  269): App 10053 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out( 6327): propertyValue:false
D/libc-netbsd( 6327): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6327): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/WVCdm   (  273): CdmEngine::CloseSession
,I/PeopleSync( 5654): Sync finished, successful=true, took 3657ms
I/WVCdm   (  273): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  273): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  273): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  273): CdmEngine::GenerateKeyRequest
D/WVCdm   (  273): PrepareKeyRequest: nonce=2900212888
I/PeopleSync( 5654): ***Sync finished***, duration: 4943 [5005f081]
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5654): Module APK com.google.android.play.games already loaded
,I/art     ( 6327): CheckpointMarkThreadRoots callback created = 0xaaf063d0
,W/PlaySystemBroadcastReceiver( 5654): Processed handlePeopleChanged at 116911
D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5654): Module APK com.google.android.play.games already loaded
I/NotificationManager(  846): android: cancelAsUser(148851818) by android
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5654): Module APK com.google.android.play.games already loaded
I/art     ( 6327): CheckpointMarkThreadRoots callback created = 0xb056e130
,I/ActivityManager(  846): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6490 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 6327): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6327): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/DataBroker( 5654): No player ID found and calling context is not the dest app
,I/MusicStore( 6490): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6490): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6490): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6490): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/LgeGpsLocationProvider(  846): requestTime failed
,W/ResourcesManager( 6490): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6490): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6490): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 6490): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6490): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@297e6d4f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6490): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6490): GMSCore installation verified
,I/ConfigStore( 6490): Config Database version: 1
,I/MediaRouter( 6490): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 6490): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6490): Using platform SSLCertificateSocketFactory
,I/NetworkMonitor( 6490): type=WIFI subType= reason=null isConnected=true
,I/MusicLifecycle( 6490): Sync started
I/NetworkMonitor( 6490): type=WIFI subType= reason=null isConnected=true
,I/art     ( 6490): CheckpointMarkThreadRoots callback created = 0xb042d400
I/GHttpClientFactory( 6490): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6490): Using platform SSLCertificateSocketFactory
I/art     ( 6490): CheckpointMarkThreadRoots callback created = 0xb042d3d0
,I/NotificationManager( 6490): com.google.android.music: cancel(1061) by com.google.android.music
,I/art     ( 5783): CheckpointMarkThreadRoots callback created = 0x9d41e950
,I/art     ( 5783): CheckpointMarkThreadRoots callback created = 0x9d41e940
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1959): Explicit concurrent mark sweep GC freed 16489(986KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/19MB, paused 1.398ms total 55.691ms
,I/NotificationManager(  846): android: cancelAsUser(2) by android
D/libc-netbsd( 6490): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6490): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6490): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6490): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  269): [LG DATA] No such appUid: 10081
D/DnsProxyListener(  269): App 10081 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 6490): propertyValue:false
D/libc-netbsd( 6490): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6490): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6490): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6490): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager( 6327): com.google.android.gm: cancel(10436) by com.google.android.gm
,I/art     (  846): Explicit concurrent mark sweep GC freed 19586(898KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.296ms total 149.917ms
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NQFileLogger( 1959): [196] e.a: about to write to file
,V/ProcessReports( 1959): [196] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,I/MusicSyncAdapter( 6490): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 6490): Periodic update
,W/MusicApiClient( 6490): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 6490): Sync ended
,I/ActivityManager(  846): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=6547 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager(  846): android: cancelAsUser(-1123058983) by android
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6490): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/SyncAdapterService( 6220): Ignoring sync request for non-current account
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6490): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
,I/MusicLeanback( 6490): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6490): Stop autocaching.
I/ActivityManager(  846): Process com.google.android.apps.docs (pid 6055) has died
,I/NotificationManager(  846): android: cancelAsUser(-701419433) by android
I/GoogleURLConnFactory( 5654): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 6327): Explicit concurrent mark sweep GC freed 5362(212KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 10MB/14MB, paused 1.070ms total 63.910ms
I/Gmail   ( 6327): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12110, normalSync: true
I/Gmail   ( 6327): lowestBackward conversation id 0
I/NotificationManager(  846): android: cancelAsUser(2) by android
,D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 5654): propertyValue:false
I/WVCdm   (  273): CdmEngine::CloseSession
,I/WVCdm   (  273): L3 Terminate.
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  846): Process com.google.android.youtube (pid 6128) has died
I/Icing   ( 5654): Storage manager: low false usage 1.61MB avail 2.02GB capacity 3.45GB
,W/Icing   ( 5654): Received bad json for section weights override -- ignoring.
,D/Finsky  ( 6547): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/Icing   ( 5654): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 5654): Received bad json for section weights override -- ignoring.
W/Icing   ( 5654): Received bad json for corpus context scoring override -- ignoring.
I/dex2oat ( 6579): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=45 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dex2oat ( 6579): dex2oat took 101.091ms (threads: 4)
,I/Adreno-EGL( 6282): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6282): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6282): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6282): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6282): Remote Branch: 
I/Adreno-EGL( 6282): Local Patches: 
I/Adreno-EGL( 6282): Reconstruct Branch: 
,I/ActivityManager(  846): Process com.google.android.apps.plus (pid 5783) has died
,D/Finsky  ( 6547): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6547): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6547): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6547): com.android.vending: cancel(-1050172287) by com.android.vending
,I/Adreno-EGL( 6282): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6282): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6282): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6282): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6282): Remote Branch: 
I/Adreno-EGL( 6282): Local Patches: 
I/Adreno-EGL( 6282): Reconstruct Branch: 
,V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@2dfe99b on behalf of 6547
D/Finsky  ( 6547): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6547): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6547): Skipping gmscore version check
D/Finsky  ( 6547): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6547): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Adreno-EGL( 6282): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6282): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6282): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6282): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6282): Remote Branch: 
I/Adreno-EGL( 6282): Local Patches: 
I/Adreno-EGL( 6282): Reconstruct Branch: 
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6490): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
,I/Icing   ( 5654): updateResources: need to parse f{com.google.android.gms}
,E/GmsUtils( 6490): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6490): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Icing   ( 5654): Internal init done: storage state 0
,I/CheckinRequestBuilder( 5654): Classify the device as Phone.
,I/Icing   ( 5654): Post-init done
I/NotificationManager( 6327): com.google.android.gm: cancel(10436) by com.google.android.gm
I/NotificationManager( 6327): com.google.android.gm: cancel(10436) by com.google.android.gm
I/art     ( 5654): WaitForGcToComplete blocked for 35.545ms for cause Explicit
,I/art     ( 5654): Explicit concurrent mark sweep GC freed 6921(260KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 14MB/24MB, paused 1.483ms total 73.360ms
,I/GAV2    ( 6327): Thread[GAThread,5,main]: No campaign data found.
,I/Gmail   ( 6327): notifyAccountChanged
,I/Gmail   ( 6327): getAccountsCursor
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6327): notifyAccountChanged
,W/Gmail   ( 6327): Sync complete for account: account:61035162
I/Gmail   ( 6327): getAccountsCursor
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  846): android: cancelAsUser(1479798955) by android
,I/ActivityManager(  846): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.apps.photos.service.GooglePhotoDownsyncService: pid=6627 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 6627): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  846): android: cancelAsUser(2126026182) by android
D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/AudioFlinger(  273): 2061 died, releasing its sessions
V/AudioFlinger(  273):  pid 1751 @ 0
V/AudioFlinger(  273):  pid 3096 @ 1
V/AudioFlinger(  273):  pid 3096 @ 2
I/CheckinTask( 5654): Sending checkin request (9754 bytes)
,I/ActivityManager(  846): Start proc com.lge.qmemoplus for service com.lge.qmemoplus/.network.googledrive.DriveSyncService: pid=6650 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  846): Process com.lge.music (pid 2061) has died
,W/ResourcesManager( 6650): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,E/App     ( 6650): [App][onCreate()] 4.40.21
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{cdbed6b type 0 when 1449671239504 com.android.vending} when 1449671239504
,D/Finsky  ( 6547): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  846): android: cancelAsUser(1500439826) by android
I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/RemindersSync( 5654): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=740:priority=5:group=main]
,I/NotificationManager(  846): android: cancelAsUser(898701380) by android
,I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
D/libc-netbsd( 6547): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6547): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6547): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6547): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  269): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 6547): propertyValue:false
D/libc-netbsd( 6547): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
D/libc-netbsd( 6547): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/CheckinRequestBuilder( 5654): Checkin reason type: 8 attempt count: 1
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/AccountManager( 6650): setSyncFrequency
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/art     ( 1732): Explicit concurrent mark sweep GC freed 14246(845KB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 11MB/18MB, paused 1.766ms total 184.428ms
I/ActivityManager(  846): Process com.android.chrome (pid 6372) has died
,E/ActivityThread( 5654): Failed to find provider info for com.google.android.wearable.settings
E/DataBuffer( 1732): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@22788b72)
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  846): Handling package changes for user 0
,D/DriveSyncService( 6650): onCreate
,D/DriveSyncService( 6650): onBind
D/libc-netbsd( 6547): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6547): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6686 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/Icing   ( 5654): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,I/art     (  846): Explicit concurrent mark sweep GC freed 33066(1463KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 10.532ms total 295.600ms
,I/Icing   ( 5654): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
,I/AppUp4:AppBoxCP( 6686): onCreate
,W/AppUp4:DB( 6686):  [AppBoxDatabaseHelper] construct
I/NotificationManager( 6096): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:DB( 6686):  setFingerPrint start
I/AppUp4:DB( 6686):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,W/ResourcesManager( 6096): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6096): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:DB( 6686):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6686):  SDK version = 0
I/AppUp4:DB( 6686):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6686): AppBoxApplication onCreate()
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationService(  846): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  846): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  846): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,I/art     ( 1959): Explicit concurrent mark sweep GC freed 9709(566KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 11MB/19MB, paused 5.833ms total 160.584ms
,I/AppUp4:CustModeStarterReceiver( 6686): onReceive
I/AppUp4:CustModeStarterReceiver( 6686): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,V/BackupManagerService(  846): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  846): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2c874782
D/AppUp4:CustFacade( 6686): Context : android.app.ReceiverRestrictedContext@35672254
D/AppUp4:CustFacade( 6686): isCustomizationCompleted : false
V/JNIHelp ( 6096): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/BaseAppContext( 1732): Using Auth Proxy for data requests.
I/NotificationManager(  846): android: cancelAsUser(2) by android
D/AppUp4:CustFacade( 6686): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6686): begin check event
I/AppUp4:CustModeStarterReceiver( 6686): Event For Nothing, skip.
I/ActivityManager(  846): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6709 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/qtaguid ( 6547): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6547): Untagging socket 41 failed errno=-22
,W/NetworkManagementSocketTagger( 6547): untagSocket(41) failed with errno -22
I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 21.985ms
W/System  ( 6096): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6096): Installed default security provider GmsCore_OpenSSL
D/Finsky  ( 6547): [1] SelfUpdateScheduler.checkForSelfUpdate: Starting DFE self-update from local version [80430000] to server version [80430500]
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 26.002ms
,I/ActivityManager(  846): Process com.lge.clock (pid 6422) has died
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 336us total 23.418ms
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,W/ResourcesManager( 6709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6709): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6709): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager(  846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  846): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6733 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourceType(  846): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  846): Process com.google.android.apps.magazines (pid 6220) has died
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/PhoneApp( 1751): onTrimMemory: 10
I/PhoneApp( 1751): trim memory
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/AppConfig( 6709): Total System Memory = 906309632
I/BackgroundMemoryTrimmer( 1935): Trimming objects from memory, since app is in the background.
I/GalleryUtils( 6709): Application Heap = 96 MB
I/qtaguid ( 6547): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6547): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6547): untagSocket(41) failed with errno -22
,I/AppConfig( 6709): App Tier : NOT_DEF
D/Finsky  ( 6547): [1] DownloadImpl.setState: Duplicate state set for 'com.android.vending' (0). Already in that state
W/ResourcesManager( 6733): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6733): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 6547): [1] DownloadQueueImpl.add: Download com.android.vending added to DownloadQueue
,D/Finsky  ( 6547): [1] DownloadImpl.setState: com.android.vending from 0 to 1.
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/SystemHelper( 6709): region [EU], country [EU], operator [OPEN], sub-operator []
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@3b65e138 on behalf of 6547
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 1959): propertyValue:false
,I/CheckinRequestBuilder( 5654): Classify the device as Phone.
,I/installd(  274): free_cache(0) avail 2545389568
,D/Finsky  ( 6547): [1] StartNextDownloadRunnable.run: Download com.android.vending starting
I/MultiDex( 6733): VM with version 2.1.0 has multidex support
,I/MultiDex( 6733): install
,I/MultiDex( 6733): VM has multidex support, MultiDex support library is disabled.
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/DownloadManager( 3117): initiating download with UID 10036
V/DownloadManager( 3117): other UID 1000
I/DownloadManager( 3117): insert() mimeType is null / COLUMN_TYPESORT_INDEX =100
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  846): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6760 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
E/lowmemorykiller(  242): Error opening /proc/6446/oom_score_adj; errno=2
,I/ActivityManager(  846): Process com.android.providers.calendar (pid 6446) has died
,I/PhoneApp( 1751): onTrimMemory: 10
I/PhoneApp( 1751): trim memory
I/BackgroundMemoryTrimmer( 1935): Trimming objects from memory, since app is in the background.
V/DownloadManager( 3117): DownloadService onCreate
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/DownloadManager( 3117): in removeSpuriousFiles
I/NotificationManager( 3117): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/qtaguid ( 6547): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6547): Untagging socket 41 failed errno=-22
D/Finsky  ( 6547): [760] DownloadQueueImpl$7.run: Enqueued com.android.vending as content://downloads/my_downloads/70
W/NetworkManagementSocketTagger( 6547): untagSocket(41) failed with errno -22
D/Finsky  ( 6547): [1] DownloadImpl.setState: com.android.vending from 1 to 2.
D/Finsky  ( 6547): [1] DownloadQueueImpl.onStart: com.android.vending: onStart
V/DownloadManager( 3117): DownloadService onStartCommand
V/DownloadManager( 3117): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@2fc98477 on behalf of 3117
V/GmsNetworkLocationProvi( 1732): DISABLE
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@2a33d8e4 on behalf of 3117
I/DownloadManager( 3117): in trimDatabase
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/CheckinTask( 5654): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5654): Checking schedule, now: 1449671241124 next: 1450198490104
I/CheckinService( 5654): active receiver: disabled
,W/ResourcesManager( 6760): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6760): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6760): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6760): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 6760): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@2881014d on behalf of 3117
D/CheckinService( 5654): Recording last checkin time for package unspecified as 1449671241158
,V/JNIHelp ( 6733): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@1be13402 on behalf of 6547
D/DriveSyncAdapter( 6650): onPerformSync() START
D/DriveSyncAdapter( 6650): Not added account. Stop
I/NotificationManager(  846): android: cancelAsUser(1312559638) by android
,D/LocationProviderProxy(  846): applying state to connected service
,D/Finsky  ( 6547): [1] DownloadQueueImpl.notifyProgress: com.android.vending: onProgress 0/-1 Status: 190.
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/NotificationManager(  846): android: cancelAsUser(2) by android
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  482): init target 500000
V/DownloadManager( 3117): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@3847f113 on behalf of 3117
D/DownloadManager( 3117): DB Update : status 192
I/NotificationManager( 1959): com.google.android.gms: cancel(0) by com.google.android.gms
,E/Auth.Api.Credentials( 5654): [CredentialSyncAdapter] Unknown sync event.
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@29c79f50 on behalf of 6547
W/ActivityThread( 6733): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6733): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a33d8e4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6733): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6733): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6733): com.google.android.gms: cancel(39789) by com.google.android.gms
D/Finsky  ( 6547): [1] DownloadQueueImpl.notifyProgress: com.android.vending: onProgress 0/-1 Status: 192.
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 298, mChargingStatus=5, mChargingStop=false
D/WifiController(  846): battery changed pluggedType: 2
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/charger_monitor(  482): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
I/NotificationManager(  846): android: cancelAsUser(-591465577) by android
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/LEDHandler( 1804): Battery Temp: 297, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
V/DownloadManager( 3117): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@3d328e4e on behalf of 3117
,V/DownloadManager( 3117): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@14368b6f on behalf of 3117
V/DownloadManager( 3117): processing updated download 70, status: 192
V/DownloadManager( 3117): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@8f607c on behalf of 3117
I/DownloadManager( 3117): Download 70 starting
,I/DownloadManager( 3117): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
I/DownloadManager( 3117): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
D/DownloadManager( 3117): fileSize : -1state.mContinuingDownload :false
,D/libc-netbsd( 3117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 3117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  269): [LG DATA] No such appUid: 10019
D/DnsProxyListener(  269): App 10019 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 3117): propertyValue:false
D/libc-netbsd( 3117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  846): Process com.google.android.music:main (pid 6490) has died
E/lowmemorykiller(  242): Error writing /proc/6627/oom_score_adj; errno=22
,I/PhoneApp( 1751): onTrimMemory: 10
I/PhoneApp( 1751): trim memory
,I/BackgroundMemoryTrimmer( 1935): Trimming objects from memory, since app is in the background.
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
I/SystemConfig( 6760): BUILD Country: EU
,I/SystemConfig( 6760): BUILD Operator: OPEN
I/ActivityManager(  846): Process com.google.android.apps.plus (pid 6627) has died
D/NativeLibraryUtils( 6733): Install completed successfully. count=13 extracted=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 6547): CheckpointMarkThreadRoots callback created = 0xb042d250
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 6547): CheckpointMarkThreadRoots callback created = 0xb042d1f0
,W/ActivityThread( 3117): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/libc-netbsd( 3117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  846): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6795 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Process com.google.android.gm (pid 6327) has died
,I/SystemConfig( 6760): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6760): existFile = false
I/SystemConfig( 6760): canReadFile = false
I/SystemConfig( 6760): systemFeature RCS result false
D/SystemConfig( 6760): refreshRcsSupport() :false
I/art     ( 6733): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 6733): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/LockScreenSettings( 6795): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/NotificationManager( 6733): com.google.android.gms: cancel(10436) by com.google.android.gms
D/libc-netbsd( 3117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 3117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 3117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10019
D/DnsProxyListener(  269): App 10019 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
I/NotificationManager( 6547): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6547): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out( 3117): propertyValue:false
D/PackageBroadcastService( 5654): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/libc-netbsd( 3117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/art     ( 6547): Suspending all threads took: 7.310ms
,I/ActivityManager(  846): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6819 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  846): Process com.android.gallery3d (pid 6709) has died
,I/PackageBroadcastService( 5654): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5654): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd( 3117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/Finsky  ( 6547): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 6547): [1] DailyHygiene.access$600: Logging device features
V/DownloadManager( 3117): Content-Disposition: null
V/DownloadManager( 3117): Content-Length: 15156597
,V/DownloadManager( 3117): Content-Location: null
V/DownloadManager( 3117): Content-Type: application/vnd.android.package-archive
V/DownloadManager( 3117): ETag: d53a3d97_66e20f40_edd2f347_77eaad4a_353febfd
V/DownloadManager( 3117): Transfer-Encoding: null
V/DownloadManager( 3117): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 3117): Min update size = 65536
V/DownloadManager( 3117): using default filename
I/DownloadManager( 3117): in verifySpace, destination: 2, path: downloadfile, length: 15156597
I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2545360896
D/DownloadManager( 3117): initial value of space = 209715200
,D/DownloadManager( 3117): file count in data dir = 0
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 209715200
V/DownloadManager( 3117): adding extension from type
V/DownloadManager( 3117): target file: /data/data/com.android.providers.downloads/cache/downloadfile.apk
V/AlarmManager(  846): RTC_WAKEUP set : Alarm{1fbe61ee type 0 when 1449671242183 com.android.vending} when 1449671242183
I/DowlnoadThread( 3117): updateDatabaseFromHeaders mMimeType =application/vnd.android.package-archivefilename=/data/data/com.android.providers.downloads/cache/downloadfile.apk
I/DownloadProvider.LgeUtils( 3117): getTypeSortIndex mimeType is =application/vnd.android.package-archive / filename=/data/data/com.android.providers.downloads/cache/downloadfile.apk
I/DownloadProvider.LgeUtils( 3117): getTypeSortIndex mediaType is =application / extension=apk
I/DownloadProvider.LgeUtils( 3117): getTypeSortIndex  index is =100
I/DowlnoadThread( 3117): updateDatabaseFromHeaders  COLUMN_TYPESORT_INDEX =100
,V/DownloadManager( 3117): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,I/art     (  846): Explicit concurrent mark sweep GC freed 23402(1150KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.312ms total 153.005ms
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@13b14314 on behalf of 3117
D/DeviceConnectionService( 1732): client connected with version: 8296000
D/DownloadManager( 3117): DB Update : etag d53a3d97_66e20f40_edd2f347_77eaad4a_353febfd
D/DownloadManager( 3117): DB Update : title downloadfile.apk
D/DownloadManager( 3117): DB Update : _data /data/data/com.android.providers.downloads/cache/downloadfile.apk
D/DownloadManager( 3117): DB Update : total_bytes 15156597
D/DownloadManager( 3117): DB Update : type_sort_index 100
D/DownloadManager( 3117): DB Update : mimetype application/vnd.android.package-archive
V/DownloadManager( 3117): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@1a61d7bd on behalf of 3117
I/DownloadManager( 3117): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@2492a1b2 on behalf of 6547
I/LGDrmClient( 3117): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  278): eDRM_GetObjectInfo +++
V/DownloadManager( 3117): processing updated download 70, status: 192
V/ILGDrmService(  278): eDRM_GetObjectInfo ---
V/DownloadManager( 3117): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@15f4503 on behalf of 3117
V/DownloadManager( 3117): ID : 70, transferData threadNum -1 start for https://android.clients.google.com/market/download/Download?packageName=com.android.vending&versionCode=80430500&ch=zen2II1nK1Sx2swLcCn16w&ssl=1&token=AOTCm0QrrKcf_CO0kbTwEKs9NSfvWx5lfUwzdTZAPWrunhwGALXu2AtaHvLbv0fjukqjP3q3t7KH5M83emAqblsCdk__ZEm2MBGFpb2eUsuvEzoH6OMKl3Wj02DQni-v0YV5P96yggGd1GRpBw7gQwGTWQM45JLZ4xr8Cso5M-KL595-4TZ1JMUNTd68BJ_ubXg-3XxPgYdYuhb4sfak42DqnJzeG4Ua&downloadId=-9056996361769904021
,D/DownloadManager( 3117): DB Update : current_bytes 32768
V/DownloadManager( 3117): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/GCoreUlr( 1732): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@3fe97c80 on behalf of 3117
I/GCoreUlr( 1732): DispatchingService.onCreate()
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@255932b9 on behalf of 6547
V/DownloadManager( 3117): processing updated download 70, status: 192
V/DownloadManager( 3117): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@88526fe on behalf of 3117
I/NotificationManager(  846): android: cancelAsUser(1222422273) by android
,I/GCoreUlr( 1732): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1732): Unbound from all location providers
I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2544336896
D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 208699392
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 208699392
,I/GCoreUlr( 1732): DispatchingService.onDestroy()
I/GCoreUlr( 1732): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1732): Unbound from all location providers
,I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2543284224
D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 207650816
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 207650816
I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 87 ms] updated apps [took 87 ms] 
,I/ActivityManager(  846): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6850 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/art     ( 6819): CheckpointMarkThreadRoots callback created = 0xb042d490
,I/art     ( 6819): CheckpointMarkThreadRoots callback created = 0xb042d470
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2542231552
D/PhoneMonitor( 6850): Register our PhoneStateListener
,D/DownloadManager( 3117): initial value of space = 209715200
,D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 206602240
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 206602240
V/SetupWizard( 6850): Connected to Gservices successfully
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PhoneMonitor( 6850): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6850): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6850): [parse] Load xml
V/TelephonyAutoProfiling( 6850): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6850): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/WearableService( 1732): callingUid 10006, callindPid: 1732
E/MDM     ( 1732): [88] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/PhoneMonitor( 6850): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1959): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1959): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1959): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5654): Restart initialization of location
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1959): com.google.android.gms: cancel(0) by com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 5654): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1959): location=null
,I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
D/Finsky  ( 6547): [780] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2541182976
D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 205553664
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 205553664
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/art     ( 1959): Explicit concurrent mark sweep GC freed 14428(860KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/19MB, paused 1.572ms total 63.831ms
,D/libc-netbsd( 6547): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6547): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6547): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6547): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  269): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2540130304
D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 204505088
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 204505088
,D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out( 6547): propertyValue:false
I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2539077632
D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 203456512
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 203456512
,I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
,I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2538024960
D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 202407936
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 202407936
I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2536976384
D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 201359360
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 201359360
,D/DownloadManager( 3117): DB Update : current_bytes 8486912
,V/DownloadManager( 3117): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@19072e5f on behalf of 3117
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@14a9e0ac on behalf of 6547
,V/DownloadManager( 3117): processing updated download 70, status: 192
V/DownloadManager( 3117): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@3fd14175 on behalf of 3117
,I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
,I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2535985152
,D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 200310784
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 200310784
I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2534932480
D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 199262208
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 199262208
,I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
,I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2533879808
D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 198213632
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 198213632
I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2532827136
,D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 197165056
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 197165056
,I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2531778560
,D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 196116480
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 196116480
I/DownloadManager( 3117): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.apk, length: 32768
,I/DownloadManager( 3117): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2530725888
D/DownloadManager( 3117): initial value of space = 209715200
D/DownloadManager( 3117): file count in data dir = 1
D/DownloadManager( 3117): remain space = 195067904
I/DownloadManager( 3117): available space (in bytes) in downloads data dir: 195067904
D/DownloadManager( 3117): ID : 70, transferData threadNum -1 is completed
D/DownloadManager( 3117): DB Update : current_bytes 15156597
,V/DownloadManager( 3117): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@388b50a on behalf of 3117
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@381a517b on behalf of 6547
V/LFT     ( 3117): notifyThroughDatabase after updateDB  id :  70, mstatus : 192, largemode : 0, settingMode : 0
,D/DownloadManager( 3117): notifyThroughDatabase start id : 70 name : /data/data/com.android.providers.downloads/cache/downloadfile.apk status : 200
V/DownloadManager( 3117): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@282a5b98 on behalf of 3117
V/DownloadManager( 3117): processing updated download 70, status: 192
V/DownloadManager( 3117): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@31817ff1 on behalf of 3117
D/DownloadManager( 3117): DB Update : numfailed 0
D/DownloadManager( 3117): DB Update : method 0
D/DownloadManager( 3117): DB Update : _data /data/data/com.android.providers.downloads/cache/downloadfile.apk
D/DownloadManager( 3117): DB Update : lastmod 1449671245207
D/DownloadManager( 3117): DB Update : status 200
D/DownloadManager( 3117): DB Update : mimetype application/vnd.android.package-archive
V/DownloadManager( 3117): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@2e8517d6 on behalf of 3117
,I/DownloadManager( 3117): Download 70 finished with status SUCCESS
D/Finsky  ( 6547): [1] DownloadBroadcastReceiver.onReceive: Intent received at DownloadBroadcastReceiver
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@21728a57 on behalf of 6547
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/Finsky  ( 6547): [1] DownloadQueueImpl.notifyProgress: com.android.vending: onProgress 15156597/15156597 Status: 200.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@3a359944 on behalf of 6547
V/DownloadManager( 3117): DownloadService onDestroy
,D/Finsky  ( 6547): [1] DownloadImpl.setState: com.android.vending from 2 to 3.
,D/Finsky  ( 6547): [1] DownloadQueueImpl.onComplete: com.android.vending: onComplete
D/Finsky  ( 6547): [1] DownloadQueueImpl.remove: Download com.android.vending removed from DownloadQueue
I/installd(  274): free_cache(0) avail 2530230272
D/Finsky  ( 6547): [1] SelfUpdateScheduler.onComplete: Self-update ready to be installed, waiting for market to close.
V/Herrevad( 5654): NQAS connected
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,I/CheckinService( 5654): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  846): Killing 6096:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10061/pid_6096/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6919 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
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
,D/administrator(  846): Handling package changes for user 0
,W/ResourcesManager( 6919): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  846): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  846): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  846): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  846): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/BackupManagerService(  846): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1adacb96
W/ResourcesManager(  846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  846): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
V/GmsNetworkLocationProvi( 1732): DISABLE
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  846): applying state to connected service
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1786): getDefaultRoute
I/art     ( 5654): Explicit concurrent mark sweep GC freed 23721(1825KB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 14MB/24MB, paused 1.781ms total 101.251ms
,I/Babel_SMS( 6919): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6919): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6919): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6919): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6919): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6919): MmsConfig.loadFromResources
E/Babel_SMS( 6919): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6919): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     (  846): Explicit concurrent mark sweep GC freed 35904(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.518ms total 191.836ms
D/SensorManager( 6919): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6919): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6919): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 6919): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6919): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6919): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6919): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 6919): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6919): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6919): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6919): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6919): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6919): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6919): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6919): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6919): found sensor: Motion Accel, handle=46
I/art     ( 6919): CheckpointMarkThreadRoots callback created = 0xaaf23460
,W/Settings( 6919): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6919): startup - clean
I/art     ( 6919): CheckpointMarkThreadRoots callback created = 0xaaf23440
I/Babel   ( 6919): deleted: false for 0
,I/AppUp4:CustModeStarterReceiver( 6686): onReceive
I/AppUp4:CustModeStarterReceiver( 6686): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6686): Context : android.app.ReceiverRestrictedContext@35672254
D/AppUp4:CustFacade( 6686): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6686): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6686): begin check event
I/AppUp4:CustModeStarterReceiver( 6686): Event For Nothing, skip.
W/AudioCapabilities( 6919): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6919): Unsupported mime audio/adpcm
W/AudioCapabilities( 6919): Unsupported mime audio/g726
,W/AudioCapabilities( 6919): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6919): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6919): Unsupported mime video/mjpg
W/VideoCapabilities( 6919): Unsupported mime video/theora
,I/ActivityManager(  846): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6957 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/AudioCapabilities( 6919): Unsupported mime audio/evrc
,W/AudioCapabilities( 6919): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6919): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6919): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6919): Unsupported mime audio/qcelp
W/AudioCapabilities( 6919): Unsupported mime audio/evrc
W/ResourcesManager( 6957): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6957): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6957): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/VideoCapabilities( 6919): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6919): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6919): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6919): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6919): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6919): Unrecognized profile 2130706433 for video/avc
I/AppConfig( 6957): Total System Memory = 906309632
,I/GalleryUtils( 6957): Application Heap = 96 MB
I/AppConfig( 6957): App Tier : NOT_DEF
,D/SystemHelper( 6957): region [EU], country [EU], operator [OPEN], sub-operator []
D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/PackageBroadcastService( 5654): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/vclib   ( 6919): onServiceConnected
I/PackageBroadcastService( 5654): Null package name or gms related package.  Ignoreing.
W/Babel   ( 6919): Attempted to change video mute state without an active call.
,I/NotificationManager( 6919): com.google.android.talk: cancel(8) by com.google.android.talk
I/Icing   ( 5654): updateResources: need to parse f{com.google.android.gms}
I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/ResourcesManager( 6919): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6919): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 43 ms] updated apps [took 43 ms] 
,V/JNIHelp ( 6919): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 6919): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6919): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6919): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 134827688704; DSPS: 4509398; Offset : -2790275597
,V/DownloadManager( 3117): openFile uri: content://downloads/my_downloads/70, mode: r, uid: 10036
,V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; selection is null; selectionArgs is null; sort is _id.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@3712db62 on behalf of 6547
V/DownloadManager( 3117): row 70 available
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@1ab74f3 on behalf of 6547
V/DownloadManager( 3117): filename in openFile: /data/data/com.android.providers.downloads/cache/downloadfile.apk
V/DownloadManager( 3117): file exists in openFile
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@1a9505b0 on behalf of 6547
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{3c879b2c type 2 when 136573 android} when 136573
,V/DownloadManager( 3117): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@f4f3c29 on behalf of 6547
I/ActivityManager(  846): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7009 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,D/Finsky  ( 6547): [1] PackageVerificationReceiver.onReceive: Skipping verification because own installation
,D/Finsky  ( 6547): [1] PackageVerificationReceiver.onReceive: Verification requested, id = 0
D/DefContainer( 7009): Copying /data/data/com.android.providers.downloads/cache/downloadfile.apk to base.apk
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  846): Killing 6650:com.lge.qmemoplus/1000 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_6650/cgroup.procs: No such file or directory
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{367db830 type 0 when 1449671257166 com.android.vending} when 1449671257166
,I/art     (  846): Background sticky concurrent mark sweep GC freed 133719(4MB) AllocSpace objects, 15(2MB) LOS objects, 20% free, 28MB/35MB, paused 4.620ms total 288.197ms
,D/Finsky  ( 6547): [770] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6547): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  846): Killing 6850:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
W/libprocessgroup(  846): failed to open /acct/uid_10038/pid_6850/cgroup.procs: No such file or directory
,D/PackageManager(  846): Renaming /data/app/vmdl495144649.tmp to /data/app/com.android.vending-1, and oldCodePath : /data/app/com.android.vending-2
,I/art     (  846): Background partial concurrent mark sweep GC freed 174424(7MB) AllocSpace objects, 13(2MB) LOS objects, 33% free, 27MB/41MB, paused 3.275ms total 170.950ms
,W/PackageManager(  846): Trying to update system app code path from /data/app/com.android.vending-2 to /data/app/com.android.vending-1
I/ActivityManager(  846): Force stopping com.android.vending appid=10036 user=-1: replace sys pkg
I/ActivityManager(  846): Killing 6547:com.android.vending/u0a36 (adj 9): stop com.android.vending
,I/art     (  846): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.android.vending-1@base.apk@classes.dex' for file location '/data/app/com.android.vending-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     (  846): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.android.vending-1/arm/base.odex' for file location '/data/app/com.android.vending-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/PackageManager(  846): Running dexopt on: /data/app/com.android.vending-1/base.apk pkg=com.android.vending isa=arm vmSafeMode=false
,W/ActivityManager(  846): Spurious death for ProcessRecord{3ce5067c 6547:com.android.vending/u0a36}, curProc for 6547: null
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/dex2oat ( 7046): /system/bin/dex2oat --zip-fd=6 --zip-location=/data/app/com.android.vending-1/base.apk --oat-fd=7 --oat-location=/data/dalvik-cache/arm/data@app@com.android.vending-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  846): ALS enabled for SRE
D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28178 ms ago)
,D/qdlights(  846): set_light_backlight: 254
,D/qdlights(  846): set_light_backlight: 251
D/qdlights(  846): set_light_backlight: 248
,D/qdlights(  846): set_light_backlight: 244
,D/qdlights(  846): set_light_backlight: 241
,D/qdlights(  846): set_light_backlight: 238
,D/qdlights(  846): set_light_backlight: 234
D/qdlights(  846): set_light_backlight: 231
D/qdlights(  846): set_light_backlight: 228
,D/qdlights(  846): set_light_backlight: 224
D/qdlights(  846): set_light_backlight: 221
,D/qdlights(  846): set_light_backlight: 218
,D/qdlights(  846): set_light_backlight: 214
,D/qdlights(  846): set_light_backlight: 211
,D/qdlights(  846): set_light_backlight: 208
,D/qdlights(  846): set_light_backlight: 204
,D/qdlights(  846): set_light_backlight: 201
,D/qdlights(  846): set_light_backlight: 198
,D/qdlights(  846): set_light_backlight: 194
,D/qdlights(  846): set_light_backlight: 191
D/qdlights(  846): set_light_backlight: 188
,D/qdlights(  846): set_light_backlight: 184
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/qdlights(  846): set_light_backlight: 181
D/qdlights(  846): set_light_backlight: 178
,D/qdlights(  846): set_light_backlight: 174
,D/qdlights(  846): set_light_backlight: 171
,D/qdlights(  846): set_light_backlight: 168
,D/qdlights(  846): set_light_backlight: 164
,D/qdlights(  846): set_light_backlight: 161
,D/qdlights(  846): set_light_backlight: 158
,D/qdlights(  846): set_light_backlight: 154
,D/qdlights(  846): set_light_backlight: 151
,D/qdlights(  846): set_light_backlight: 148
,D/qdlights(  846): set_light_backlight: 144
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
D/qdlights(  846): set_light_backlight: 141
,D/qdlights(  846): set_light_backlight: 138
D/qdlights(  846): set_light_backlight: 134
,D/qdlights(  846): set_light_backlight: 131
D/qdlights(  846): set_light_backlight: 128
,D/qdlights(  846): set_light_backlight: 124
,D/qdlights(  846): set_light_backlight: 121
,D/qdlights(  846): set_light_backlight: 118
,D/qdlights(  846): set_light_backlight: 114
,D/qdlights(  846): set_light_backlight: 111
,D/qdlights(  846): set_light_backlight: 108
D/qdlights(  846): set_light_backlight: 104
D/qdlights(  846): set_light_backlight: 101
,D/qdlights(  846): set_light_backlight: 98
D/qdlights(  846): set_light_backlight: 94
,D/qdlights(  846): set_light_backlight: 91
D/qdlights(  846): set_light_backlight: 88
,D/qdlights(  846): set_light_backlight: 84
D/qdlights(  846): set_light_backlight: 81
,D/qdlights(  846): set_light_backlight: 78
D/qdlights(  846): set_light_backlight: 74
,D/qdlights(  846): set_light_backlight: 71
D/qdlights(  846): set_light_backlight: 68
,D/qdlights(  846): set_light_backlight: 64
D/qdlights(  846): set_light_backlight: 61
,D/qdlights(  846): set_light_backlight: 58
,D/qdlights(  846): set_light_backlight: 54
,D/qdlights(  846): set_light_backlight: 51
,D/qdlights(  846): set_light_backlight: 48
D/qdlights(  846): set_light_backlight: 44
,D/qdlights(  846): set_light_backlight: 41
D/qdlights(  846): set_light_backlight: 38
,D/qdlights(  846): set_light_backlight: 34
,D/qdlights(  846): set_light_backlight: 31
,D/qdlights(  846): set_light_backlight: 28
,D/qdlights(  846): set_light_backlight: 24
,D/qdlights(  846): set_light_backlight: 21
,D/qdlights(  846): set_light_backlight: 18
,D/qdlights(  846): set_light_backlight: 14
,D/qdlights(  846): set_light_backlight: 11
,D/qdlights(  846): set_light_backlight: 10
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/dex2oat ( 7046): dex2oat took 12.855s (threads: 4)
,I/ActivityManager(  846): Force stopping com.android.vending appid=10036 user=-1: update pkg
,W/PackageManager(  846): Code path for pkg : com.android.vending changing from /data/app/com.android.vending-2 to /data/app/com.android.vending-1
W/PackageManager(  846): Resource path for pkg : com.android.vending changing from /data/app/com.android.vending-2 to /data/app/com.android.vending-1
W/PackageSettings(  846): Skipping PackageSetting{5bece2b com.example.hello/10030} due to missing metadata
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PackageManager(  846): Un-granting permission android.permission.WRITE_MEDIA_STORAGE from package com.android.providers.downloads.ui (protectionLevel=18 flags=0x48be44)
W/PackageManager(  846): Not granting permission android.permission.SEND_DOWNLOAD_COMPLETED_INTENTS to package com.android.vending (protectionLevel=2 flags=0x404abec5)
W/PackageManager(  846): Unknown permission android.permission.SEND_SMS_NO_CONFIRMATION in package com.android.vending
W/PackageManager(  846): Unknown permission android.permission.USE_FINGERPRINT in package com.android.vending
W/PackageManager(  846): Unknown permission android.permission.GET_PACKAGE_IMPORTANCE in package com.android.vending
W/PackageManager(  846): Unknown permission android.permission.GET_ACCOUNTS_PRIVILEGED in package com.android.vending
W/PackageManager(  846): Unknown permission android.permission.INSTALL_GRANT_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  846): Unknown permission android.permission.GRANT_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  846): Unknown permission android.permission.REVOKE_RUNTIME_PERMISSIONS in package com.android.vending
,W/PackageManager(  846): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.android.vending
W/PackageManager(  846): Not granting permission android.permission.BATTERY_STATS to package com.android.vending (protectionLevel=50 flags=0x404abec5)
W/PackageSettings(  846): Skipping PackageSetting{5bece2b com.example.hello/10030} due to missing metadata
,I/ActivityManager(  846): Force stopping com.android.vending appid=10036 user=0: pkg removed
,D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_REMOVED
I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.android.vending
I/art     ( 1877): Explicit concurrent mark sweep GC freed 8908(484KB) AllocSpace objects, 6(737KB) LOS objects, 24% free, 15MB/20MB, paused 485us total 137.246ms
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.android.vending flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.android.vending flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 2
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  846): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7122 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_ADDED
,I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
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
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_ADDED, packageName : com.android.vending
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
,W/Settings(  846): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.android.vending flg=0x4000010 (has extras) }
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.android.vending flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 2
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
,D/KeyguardModel( 1375): handleShortcutListChanged...
I/art     (  846): Explicit concurrent mark sweep GC freed 93773(4MB) AllocSpace objects, 13(1065KB) LOS objects, 33% free, 23MB/34MB, paused 6.289ms total 309.277ms
D/administrator(  846): Handling package changes for user 0
I/NotificationService(  846): action=android.intent.action.PACKAGE_REMOVED queryReplace=true
D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.android.vending flg=0x4000010 (has extras) }
D/JobSchedulerService(  846): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  846): WaitForGcToComplete blocked for 63.986ms for cause Explicit
W/ResourcesManager( 7122): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7122): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7122): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/NotificationService(  846): action=android.intent.action.PACKAGE_ADDED queryReplace=false
D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.android.vending flg=0x4000010 (has extras) }
,I/LGEmail ( 7122): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/BackupManagerService(  846): Now staging backup of com.android.vending
D/LGEmail ( 7122): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/art     (  846): Explicit concurrent mark sweep GC freed 5645(324KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 5.754ms total 271.374ms
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,I/PackageManager(  846): Observer no longer exists.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PackageChangeReceiver( 7122): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  846): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7147 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  846): Killing 6282:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/ResourcesManager(  846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  846): failed to open /acct/uid_10006/pid_6282/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,W/ResourceType(  846): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourceType(  846): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7147): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7147): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7147): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7147): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7147): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 7147): Using schema version: 115
,I/IndexDatabaseHelper( 7147): Index is fine
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1786): getDefaultRoute
D/PackageIntentReceiver( 7147): Not supported Hotkey customization function 
,D/HideNavigationAppsReceiver( 7147): Receive package name : com.android.vending, replacing=true, action=android.intent.action.PACKAGE_REMOVED
D/HideNavigationAppsReceiver( 7147): replacing : true
D/ButtonCombinationReceiver( 7147): Receive package name : com.android.vending
,D/ButtonCombinationReceiver( 7147): replacing : true
I/ActivityManager(  846): Killing 6733:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10006/pid_6733/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7168 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 20.977ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 21.692ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.813ms
W/ContextImpl( 7168): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2663 
,D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/PackageBroadcastService( 5654): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.android.vending
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5654): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1959): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1959): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  846): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7188 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 6919:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10061/pid_6919/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 154828497862; DSPS: 5164784; Offset : -2790260157
,I/GAv4    ( 7188): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7188):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7188):   adb logcat -s GAv4
,W/GAv4    ( 7188): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7188): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7188): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7188): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,I/PowerManagerService(  846): ALS enabled for SRE
,D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35161 ms ago)
I/PowerManagerService(  846): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  846): ALS enabled for SRE
,D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35181 ms ago)
W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  846): Sleeping (uid 1000)...
,D/LPWGController(  846): [updateScreenState] screen on = false
D/LPWGController(  846): disable proximity sensor
D/LPWGController(  846): enable proximity sensor
,I/SensorManager(  846): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1eead53c] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  846): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  846): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  846): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  846): activate: handle is 48, enable
V/sensors_hal_Ctx(  846): activate sensors is 1400000000000
D/sensors_hal_Thresh(  846): enable: handle=48
I/sensors_hal_SAM(  846): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  846): waitForResponse: timeout=1000
V/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  846): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  846): enable: Received response: 0
D/PowerManagerServiceEx(  846): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35269 ms ago)
,I/Adreno-EGL(  846): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  846): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  846): Build Date: 03/02/15 Mon
I/Adreno-EGL(  846): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  846): Remote Branch: 
I/Adreno-EGL(  846): Local Patches: 
I/Adreno-EGL(  846): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (174 us)
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7188): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 7188): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7188): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Sensors (  389): sns_pwr.c(273):acquiring wakelock
,I/ActivityManager(  846): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=7235 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
V/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  846): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  846): processInd: handle 48, count=1
V/sensors_hal_Thresh(  846): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  846): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  846): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  846): poll: count: 256
,I/sensors_hal_Ctx(  846): poll: released wakelock sensor_ind
D/sensors_hal_Util(  846): waitForResponse: timeout=0
D/LPWGController(  846): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  846): current mode = 1  value = 1 1
I/LPWGController(  846): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/ActivityManager(  846): Killing 7009:com.android.defcontainer/u0a4 (adj 15): empty #11
I/art     ( 7188): CheckpointMarkThreadRoots callback created = 0xaaf1a1f0
,W/libprocessgroup(  846): failed to open /acct/uid_10004/pid_7009/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/LPWGController(  846): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/art     ( 7188): CheckpointMarkThreadRoots callback created = 0xb050fa80
,V/JNIHelp ( 7188): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/[BNRAppListMgrReceiver]( 7235): android.intent.action.PACKAGE_REMOVED : com.android.vending
,W/System  ( 7188): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7188): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  846): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7259 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  846): Killing 7122:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10021/pid_7122/cgroup.procs: No such file or directory
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/qdlights(  846): set_light_backlight: 0
,I/SensorManager(  846): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  846): activate: handle is 46, disable
V/sensors_hal_Ctx(  846): activate sensors is 1000000000000
D/sensors_hal_LP2(  846): enable: handle=46
D/sensors_hal_LP2(  846): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  846): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  846): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  846): Display changed displayId=0
,V/sensors_hal_SAM(  846): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
,D/sensors_hal_LP2(  846): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1751): Display #0 changed.
D/Finsky  ( 7259): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  846): Excessive delay in setPowerMode(): 199ms
I/QCOM PowerHAL(  846): Got set_interactive hint
D/KeyguardViewMediator( 1375): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1375): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1375): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1375): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1375): unregisterProximitySensor
,D/StatusBarWindowView( 1375): onScreenTurnedOff why = 3
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/WifiServerServiceExt(  846): sendKtScanInterval  mRtspPlay : false
,I/WifiServerServiceExt(  846): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  273): setParameters(): io 0, keyvalue screen_state=on, calling pid 846
D/audio_hw_primary(  273): adev_set_parameters: enter: screen_state=on
,V/voice   (  273): voice_set_parameters: enter: screen_state=on
V/compress_voip(  273): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  273): voice_extn_compress_voip_set_parameters: exit
V/voice   (  273): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  273): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  273): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  273): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  273): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  273): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  273): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  273): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/GpsLocationProvider(  846): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
,I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1804): lockStatus = 0
I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
,D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn off led
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1804): RESTART MSG
,D/Finsky  ( 7259): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/SplitWindow(  846): check instance of lgWin Window{378ed540 u0 SearchPanel}
,W/Settings( 7259): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7259): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7259): com.android.vending: cancel(-1050172287) by com.android.vending
,D/InputDispatcher(  846): Window went away: Window{4cc835c u0 SearchPanel}
,I/[SystemUI]Clock( 1375): onReceive = android.intent.action.SCREEN_ON
,I/NotificationManager( 7259): com.android.vending: cancel(-1050172287) by com.android.vending
,I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
I/ActivityManager(  846): Process com.android.settings (pid 7147) has died
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
,D/Ulp_jni (  846): JNI:system_update. Event-0
V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@19c74bae on behalf of 7259
,D/Ads     ( 7259): Skipping gmscore version check
I/ActivityManager(  846): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7323 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/Finsky  ( 7259): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7259): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7259): [1] InstallerImpl.access$500: Attempt recovery of content://downloads/my_downloads/70 200
,D/Finsky  ( 7259): [1] InstallerImpl.access$500: Releasing content://downloads/my_downloads/70 200
,D/Finsky  ( 7259): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2672): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:27:55
D/Finsky  ( 7259): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/WeatherService( 2672): 2 : ACTION screen on
D/WeatherService( 2672): 2 : shouldTimeTickRegistered : false
W/ResourcesManager( 7323): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7323): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7323): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/Weather_cast( 2672): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2672): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:27:55
D/AppCleanupService( 3807): android.intent.action.SCREEN_ON
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): ACTION_SCREEN_ON
V/AudioFlinger(  273): setParameters(): io 0, keyvalue screen_state=off, calling pid 846
D/audio_hw_primary(  273): adev_set_parameters: enter: screen_state=off
V/voice   (  273): voice_set_parameters: enter: screen_state=off
V/compress_voip(  273): voice_extn_compress_voip_set_parameters: enter: screen_state=off
,V/compress_voip(  273): voice_extn_compress_voip_set_parameters: exit
V/voice   (  273): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  273): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  273): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  273): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  273): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  273): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  273): adev_set_parameters: exit with code(0)
D/WifiController(  846): CMD_SCREEN_OFF 
D/WifiController(  846): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  846): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1804): clear
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn on led
E/LEDService( 1804): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1804): Can't handle this request of patternId:0
D/LEDHandler( 1804): RESTART MSG
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2672): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:27:55
D/WeatherService( 2672): 2 : ACTION screen off
I/LGEmail ( 7323): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/WeatherService( 2672): 2 : TimeTick Receiver Unregister
D/WeatherService( 2672): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:27:55
D/AppCleanupService( 3807): android.intent.action.SCREEN_OFF
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  846): ACTION_SCREEN_OFF
D/AppCleanupService( 3807): AppUsageStatsSaveTask
D/LGEmail ( 7323): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
E/NxpNfcJni( 1786): getReconnectState = 0x0
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
,E/NxpNfcJni( 1786): getReconnectState = 0x0
,I/PackageChangeReceiver( 7323): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  846): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=7347 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  846): Killing 6686:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10011/pid_6686/cgroup.procs: No such file or directory
,I/Sensors (  389): sns_pwr.c(301):releasing wakelock
I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7368 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 6957:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10023/pid_6957/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7368): onCreate
,W/AppUp4:DB( 7368):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7368):  setFingerPrint start
I/AppUp4:DB( 7368):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7368):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7368):  SDK version = 0
I/AppUp4:DB( 7368):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7368): AppBoxApplication onCreate()
I/ActivityManager(  846): Killing 6760:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10018/pid_6760/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7391 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7391): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7391): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7391): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 7391): Total System Memory = 906309632
,I/GalleryUtils( 7391): Application Heap = 96 MB
I/AppConfig( 7391): App Tier : NOT_DEF
D/SystemHelper( 7391): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  846): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7410 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 7168:com.android.keychain/1000 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_7168/cgroup.procs: No such file or directory
,W/ResourcesManager( 7410): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7410): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7410): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7410): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7410): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 7410): BUILD Country: EU
I/SystemConfig( 7410): BUILD Operator: OPEN
,I/LockScreenSettings( 6795): New app installed broadcast received ..
,I/SystemConfig( 7410): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7410): existFile = false
I/SystemConfig( 7410): canReadFile = false
I/SystemConfig( 7410): systemFeature RCS result false
D/SystemConfig( 7410): refreshRcsSupport() :false
I/LockScreenSettings( 6795): Number of installed packages  1
I/ActivityManager(  846): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=7429 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 7188:com.google.android.apps.docs/u0a58 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10058/pid_7188/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 7429): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 7429): uri : package:com.android.vending
,I/ActivityManager(  846): Killing 6819:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_10086/pid_6819/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5654): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 5654): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.android.vending
D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5654): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5654): Submit a task: h
,I/PeopleContactsSync( 5654): CP2 sync disabled
D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/h       ( 5654): Processing package: com.android.vending
D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/a       ( 5654): Look up (com.android.vending:80430500) returned no result
D/h       ( 5654): Starting Hash for package com.android.vending:6.0.5
,D/GCM     ( 1959): GcmService start Intent { act=com.google.android.gms.gcm.PACKAGE_REPLACED cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gms.gcm.PACKAGE_REPLACED
,I/ActivityManager(  846): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7452 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/h       ( 5654): Package com.android.vending's hash: 8d58d5fed273b866768764e239b5727f4c6e27a8ff1606fe5661974af1a8cca3
,D/a       ( 5654): Look up (com.android.vending:80430500) returned no result
D/h       ( 5654): Saved the app info in cache for package:com.android.vending.
,I/GAv4    ( 7452): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7452):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7452):   adb logcat -s GAv4
W/GAv4    ( 7452): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7452): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7452): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 7452): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7452): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 7452): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7452): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  846): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7487 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7452): CheckpointMarkThreadRoots callback created = 0xaaf2a1f0
,I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 22.602ms
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.947ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.958ms
,V/JNIHelp ( 7452): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/ResourcesManager( 7487): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 7452): CheckpointMarkThreadRoots callback created = 0xb050fa70
,W/System  ( 7452): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7452): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  846): Killing 7235:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_7235/cgroup.procs: No such file or directory
,I/art     (  846): Explicit concurrent mark sweep GC freed 41790(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.399ms total 165.591ms
,I/ActivityManager(  846): Killing 7259:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10036/pid_7259/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=7527 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.android.vending, CONTACTS=MAYBE
,D/[BNRAppListMgrReceiver]( 7527): android.intent.action.PACKAGE_ADDED : com.android.vending
,D/LauncherStateReceiver2( 7410): .activities.CallLogSearchResolverActivity enable(1)/disable(2) : 2
,D/LauncherStateReceiver2( 7410): .DialtactsRecentCallsEntryActivity enable(1)/disable(2) : 2
D/LauncherStateReceiver2( 7410): .alias.SpeedDialListActivity enable(1)/disable(2) : 2
I/ActivityManager(  846): Start proc com.lge.sizechangable.weather.platform for broadcast com.lge.sizechangable.weather.platform/com.lge.sizechangable.weather.receiver.WSReceiver: pid=7545 uid=10075 gids={50075, 9997, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 234 ms] updated apps [took 234 ms] 
I/art     ( 7545): Almond Protected OAT
,I/ActivityManager(  846): Killing 7323:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10021/pid_7323/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5654): Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.android.vending
D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 5654): Submit a task: h
D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/PeopleContactsSync( 5654): CP2 sync disabled
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/h       ( 5654): Processing package: com.android.vending
E/NetworkScheduler.SchedulerReceiver( 1959): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1959): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/GassUtils( 5654): Found app info for package com.android.vending:80430500. Hash: 8d58d5fed273b866768764e239b5727f4c6e27a8ff1606fe5661974af1a8cca3
D/h       ( 5654): Found info for package com.android.vending in db.
,I/ActivityManager(  846): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=7576 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7576): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7576): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7576): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7576): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7576): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7576):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7576):   adb logcat -s GAv4
,W/GAv4    ( 7576): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7576): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7576): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 7576): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7576): Time to load native libraries: 3 ms (timestamps 728-731)
,I/LibraryLoader( 7576): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7576): Binding Chromium to main looper Looper (main, tid 1) {13b14314}
,I/LibraryLoader( 7576): Expected native library version number "",actual native library version number ""
,I/chromium( 7576): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7576): Initializing chromium process, singleProcess=true
,W/art     ( 7576): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7576): ApplicationContext is null in ApplicationStatus
W/chromium( 7576): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7576): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7576): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7576): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7576): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7576): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7576): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7576): Remote Branch: 
I/Adreno-EGL( 7576): Local Patches: 
I/Adreno-EGL( 7576): Reconstruct Branch: 
V/AudioPolicyService(  273): registerClient() client 0xb4027300, uid 10079
,W/AudioManagerAndroid( 7576): Requires BLUETOOTH permission
I/NSApplication( 7576): Starting up...
,I/ActivityManager(  846): Killing 7347:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/Icing   ( 5654): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
W/libprocessgroup(  846): failed to open /acct/uid_10009/pid_7347/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.DeviceBroadcastReceiver: pid=7638 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,D/Icing   ( 5654): Loaded CLD2 Version V2.0 - 20141016
W/ResourcesManager( 7638): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=278032789, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{3f322ee1 type 2 when 161111 com.android.systemui} when 161111
E/App     ( 7638): [App][onCreate()] 4.40.21
,I/Icing   ( 5654): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
,I/[SystemUI]Clock( 1375): called onTimeUpdated()
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
,D/AccountManager( 7638): setSyncFrequency
,D/DeviceBroadcastReceiver( 7638): [DeviceBroadcastReceiver]android.intent.action.PACKAGE_REPLACED
,D/KeyguardViewMediator( 1375): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
I/ActivityManager(  846): Killing 7368:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
W/libprocessgroup(  846): failed to open /acct/uid_10011/pid_7368/cgroup.procs: No such file or directory
V/TelecomServiceImpl( 1751): getCallState : 0
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1375): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1375): doKeyguard: not showing because lockscreen is off
D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=278032789 [*alarm*], flags=0x0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  482): init target 500000
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  846): Killing 7391:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10023/pid_7391/cgroup.procs: No such file or directory
,I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/ActivityManager(  846): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7669 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
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
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator(  846): Handling package changes for user 0
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7669): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/NotificationService(  846): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  846): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  846): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  846): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  846): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2e1b69dd
,W/ResourcesManager(  846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType(  846): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1732): DISABLE
I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  846): applying state to connected service
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 21401(1373KB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 11MB/19MB, paused 1.750ms total 100.599ms
E/DataBuffer( 1732): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@76df3fa)
I/Babel_SMS( 7669): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7669): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7669): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7669): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7669): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7669): MmsConfig.loadFromResources
,E/Babel_SMS( 7669): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7669): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7669): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7669): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7669): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7669): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7669): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7669): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7669): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7669): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7669): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7669): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7669): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7669): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7669): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7669): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7669): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7669): found sensor: Motion Accel, handle=46
I/art     ( 7669): CheckpointMarkThreadRoots callback created = 0xaaf5d2c0
W/Settings( 7669): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7669): startup - clean
I/art     ( 7669): CheckpointMarkThreadRoots callback created = 0xaaf5d2a0
I/Babel   ( 7669): deleted: false for 0
,W/AudioCapabilities( 7669): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7669): Unsupported mime audio/adpcm
W/AudioCapabilities( 7669): Unsupported mime audio/g726
W/AudioCapabilities( 7669): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7669): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7669): Unsupported mime video/mjpg
I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7709 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/VideoCapabilities( 7669): Unsupported mime video/theora
,W/AudioCapabilities( 7669): Unsupported mime audio/evrc
,W/AudioCapabilities( 7669): Unsupported mime audio/qcelp
W/VideoCapabilities( 7669): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7669): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7669): Unsupported mime audio/qcelp
W/AudioCapabilities( 7669): Unsupported mime audio/evrc
W/VideoCapabilities( 7669): Unsupported mime video/mp4v-esdp
,I/AppUp4:AppBoxCP( 7709): onCreate
W/AppUp4:DB( 7709):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7709):  setFingerPrint start
I/AppUp4:DB( 7709):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/VideoCapabilities( 7669): Unsupported profile 4 for video/mp4v-es
I/AppUp4:DB( 7709):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7709):  SDK version = 0
,I/AppUp4:DB( 7709):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7709): AppBoxApplication onCreate()
W/VideoCapabilities( 7669): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7669): Unrecognized profile 2130706433 for video/avc
I/AppUp4:CustModeStarterReceiver( 7709): onReceive
I/AppUp4:CustModeStarterReceiver( 7709): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
W/VideoCapabilities( 7669): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 7709): Context : android.app.ReceiverRestrictedContext@35672254
D/AppUp4:CustFacade( 7709): isCustomizationCompleted : false
W/VideoCapabilities( 7669): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 7709): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7709): begin check event
I/AppUp4:CustModeStarterReceiver( 7709): Event For Nothing, skip.
I/ActivityManager(  846): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7734 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 7669): onServiceConnected
I/NotificationManager( 7669): com.google.android.talk: cancel(8) by com.google.android.talk
,W/Babel   ( 7669): Attempted to change video mute state without an active call.
W/ResourcesManager( 7669): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7669): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7734): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7734): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7734): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 7669): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/AppConfig( 7734): Total System Memory = 906309632
,I/GalleryUtils( 7734): Application Heap = 96 MB
I/AppConfig( 7734): App Tier : NOT_DEF
D/SystemHelper( 7734): region [EU], country [EU], operator [OPEN], sub-operator []
,W/System  ( 7669): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7669): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  846): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7756 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  846): RTC_WAKEUP set : Alarm{3546aff3 type 0 when 1449671290510 com.android.vending} when 1449671290510
I/NotificationManager( 7669): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6795): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  846): Killing 7429:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_7429/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5654): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5654): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5654): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 44 ms] updated apps [took 44 ms] 
,D/Finsky  ( 7756): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7756): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7756): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7756): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7756): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3117): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3117): created cursor android.database.sqlite.SQLiteCursor@297e6d4f on behalf of 7756
D/Finsky  ( 7756): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7756): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7756): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 7756): Skipping gmscore version check
V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{33ddda61 type 2 when 172142 android} when 172142
,D/Finsky  ( 7756): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5654): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 7452): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7452): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  846): Explicit concurrent mark sweep GC freed 33861(1850KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 3.120ms total 172.468ms
,I/NotificationManager(  846): android: cancelAsUser(-1488629395) by android
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AccountUtils( 5654): 0 accounts found with uca feature
I/GamesSyncAdapter( 5654): Starting sync for 3a3529a
,I/GamesSyncAdapter( 5654): Sync duration for 3a3529a: 2
D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5654): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 5654): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5654): Module APK com.google.android.play.games already loaded
,I/NotificationManager(  846): android: cancelAsUser(-715483196) by android
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  846): android: cancelAsUser(2) by android
,D/libc-netbsd( 7756): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7756): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7756): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7756): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10036
,D/DnsProxyListener(  269): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 7756): propertyValue:false
D/libc-netbsd( 7756): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7756): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7756): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7756): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/Finsky  ( 7756): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 1 successful.
,D/Finsky  ( 7756): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  846): Killing 7527:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_7527/cgroup.procs: No such file or directory
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 174829382282; DSPS: 5820173; Offset : -2790260487
,I/ActivityManager(  846): Killing 7545:com.lge.sizechangable.weather.platform/u0a75 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10075/pid_7545/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Killing 7576:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  846): failed to open /acct/uid_10079/pid_7576/cgroup.procs: No such file or directory
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{271adc28 type 2 when 186756 com.google.android.gms} when 186756
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{4741d41 type 2 when 188350 android} when 188350
,D/UdcCache:FPQuery( 5654): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1959): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1959): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 1959): propertyValue:false
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 1959): propertyValue:false
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/NotificationManager( 1959): com.google.android.gms: cancel(0) by com.google.android.gms
,D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1959):  no longer exists, so no auth token.
D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1959): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 194830168525; DSPS: 6475559; Offset : -2790267441
,I/ClearcutLoggerApiImpl( 1959): disconnect managed GoogleApiClient
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{1a55021 type 2 when 202218 android} when 202218
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 214830932163; DSPS: 7130944; Offset : -2790266560
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 234831602207; DSPS: 7786326; Offset : -2790267902
,I/ClearcutLoggerApiImpl( 5654): disconnect managed GoogleApiClient
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 254832280741; DSPS: 8441708; Offset : -2790261015
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 274833006150; DSPS: 9097092; Offset : -2790267846
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 294833770257; DSPS: 9752477; Offset : -2790266652
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 314834442645; DSPS: 10407859; Offset : -2790265703
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5278): Connected to the server!
I/jxcore-log( 5278): 
,I/chromium( 5278): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 334835195919; DSPS: 11063244; Offset : -2790275368
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  846): remove 2991669c
,D/LocationManagerService(  846): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  846): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  846): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  846): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  846): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=278032789, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,I/ActivityManager(  846): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7894 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 7894): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7894): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@35672254
I/ActivityManager(  846): Killing 7638:com.lge.qmemoplus/1000 (adj 15): empty #11
W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_7638/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=278032789 [*alarm*], flags=0x0
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 354835958828; DSPS: 11718629; Offset : -2790275164
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 374836664966; DSPS: 12374012; Offset : -2790273040
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 394837402614; DSPS: 13029396; Offset : -2790266590
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out( 1959): propertyValue:false
D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/NotificationManager( 1959): com.google.android.gms: cancel(0) by com.google.android.gms
,I/NotificationManager(  846): android: cancelAsUser(2) by android
,I/ActivityManager(  846): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7960 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 5654): propertyValue:false
D/libc-netbsd( 5654): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5654): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 7960): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7960): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7960): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 7960): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7960): Installed default security provider GmsCore_OpenSSL
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,W/ResourcesManager( 7960): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7960): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 7960): CheckpointMarkThreadRoots callback created = 0xb042dc40
E/YouTube MDX( 7960): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/art     ( 7960): CheckpointMarkThreadRoots callback created = 0xb042dc30
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dex2oat ( 8009): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-62999011.jar --oat-fd=25 --oat-location=/data/data/com.google.android.youtube/cache/ads-62999011.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7960): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/dex2oat ( 8009): dex2oat took 105.186ms (threads: 4)
,I/NotificationManager( 7960): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7960): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7960): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7960): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 7960): Found 10006
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7960): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  846): Killing 7709:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/NotificationManager( 7960): com.google.android.youtube: cancel(10436) by com.google.android.youtube
W/libprocessgroup(  846): failed to open /acct/uid_10011/pid_7709/cgroup.procs: No such file or directory
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  269): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 7960): propertyValue:false
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  846): tsOffsetIs: Apps: 414838188232; DSPS: 13684782; Offset : -2790274299
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  269): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  269): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out( 7960): propertyValue:false
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 434838870255; DSPS: 14340164; Offset : -2790263194
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 454839549154; DSPS: 14995546; Offset : -2790255682
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1959): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  846): android: cancelAsUser(2) by android
,D/libc-netbsd( 7756): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7756): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7756): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7756): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  269): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out( 7756): propertyValue:false
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 474840564460; DSPS: 15650940; Offset : -2790278129
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 494841325285; DSPS: 16306325; Offset : -2790279958
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 514842184392; DSPS: 16961713; Offset : -2790275499
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 534842858447; DSPS: 17617095; Offset : -2790272779
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 554843609429; DSPS: 18272480; Offset : -2790284737
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 574844285463; DSPS: 18927862; Offset : -2790280271
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 594844959518; DSPS: 19583244; Offset : -2790277316
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 614845639977; DSPS: 20238626; Offset : -2790268400
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 634846397471; DSPS: 20894011; Offset : -2790273898
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 654847167880; DSPS: 21549396; Offset : -2790266272
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 674847915945; DSPS: 22204781; Offset : -2790281147
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 694848701458; DSPS: 22860166; Offset : -2790258808
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  269): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  269): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
,I/System.out( 7960): propertyValue:false
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 714849467440; DSPS: 23515551; Offset : -2790255895
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  269): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 7960): propertyValue:false
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  269): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  269): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  269): res_queryN name = xxxxx succeed
I/System.out( 7960): propertyValue:false
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 734850649204; DSPS: 24170950; Offset : -2790264213
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 754851319092; DSPS: 24826332; Offset : -2790265868
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 774852056064; DSPS: 25481716; Offset : -2790261266
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 794852821890; DSPS: 26137101; Offset : -2790258249
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 814853575163; DSPS: 26792486; Offset : -2790268097
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 834854246041; DSPS: 27447868; Offset : -2790268476
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 854854919210; DSPS: 28103250; Offset : -2790266824
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 874855596806; DSPS: 28758632; Offset : -2790260641
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 894856369716; DSPS: 29414018; Offset : -2790280719
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 914857040802; DSPS: 30069400; Offset : -2790281149
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 934857804075; DSPS: 30724785; Offset : -2790280712
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 954858552193; DSPS: 31380169; Offset : -2790265328
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 974859303747; DSPS: 32035554; Offset : -2790276688
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 994859974521; DSPS: 32690936; Offset : -2790276936
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=278032789, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{137309eb type 2 when 1002187 com.android.bluetooth} when 1002187
D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=278032789 [*alarm*], flags=0x0
,W/bt-smp  ( 1988): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1988): Plain text(LSB ~ MSB) = 4c 65 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1988): Encrypted text(LSB ~ MSB) = d8 f4 7b ca 2f b7 12 d8 16 56 1f b5 ef 6e 86 96 
W/bt-btm  ( 1988): Stopping oneshot timer
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1014860944306; DSPS: 33346328; Offset : -2790283974
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1034861617944; DSPS: 34001710; Offset : -2790281957
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1054862355801; DSPS: 34657094; Offset : -2790276053
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1074863111366; DSPS: 35312479; Offset : -2790283870
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1094863955941; DSPS: 35967866; Offset : -2790262931
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1114864697288; DSPS: 36623251; Offset : -2790284367
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1134865368843; DSPS: 37278633; Offset : -2790284303
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1154866127272; DSPS: 37934017; Offset : -2790258504
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=278032789, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{2bc30348 type 2 when 1167970 android} when 1167970
D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=278032789 [*alarm*], flags=0x0
,I/NotificationManager(  846): android: cancelAsUser(-1548111331) by android
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{1c31019 type 2 when 1011635 com.google.android.gms} when 1011635
,I/NotificationManager(  846): android: cancelAsUser(2145784878) by android
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1174866858046; DSPS: 38589401; Offset : -2790260387
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1194867614601; DSPS: 39244786; Offset : -2790266745
,D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=278032789, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{3b4ba8de type 2 when 1198822 android} when 1198822
I/DigitalAppWidgetProvider( 7894): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7894): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@35672254
D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=278032789 [*alarm*], flags=0x0
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1214868291521; DSPS: 39900168; Offset : -2790260847
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  846): User[0] Flushing usage stats to disk
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1234869052815; DSPS: 40555553; Offset : -2790264264
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1254869815255; DSPS: 41210938; Offset : -2790262836
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1274870991498; DSPS: 41866337; Offset : -2790276961
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1294871664303; DSPS: 42521719; Offset : -2790275751
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1314872331691; DSPS: 43177101; Offset : -2790279801
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1334873109184; DSPS: 43832486; Offset : -2790264935
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1354875731103; DSPS: 44487932; Offset : -2790267346
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1374876614168; DSPS: 45143321; Offset : -2790269551
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1394877361139; DSPS: 45798706; Offset : -2790285858
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1414878030142; DSPS: 46454087; Offset : -2790257464
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1434878782374; DSPS: 47109472; Offset : -2790268041
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1454879558095; DSPS: 47764857; Offset : -2790255338
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1474880574963; DSPS: 48420251; Offset : -2790276067
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1494881247404; DSPS: 49075633; Offset : -2790275014
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1514882081354; DSPS: 49731020; Offset : -2790265194
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1534882837753; DSPS: 50386405; Offset : -2790271474
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1554883505766; DSPS: 51041787; Offset : -2790274901
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  846): battery changed pluggedType: 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1574884365967; DSPS: 51697175; Offset : -2790268800
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1594885027782; DSPS: 52352557; Offset : -2790278920
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1614885705951; DSPS: 53007939; Offset : -2790272058
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1634886388652; DSPS: 53663321; Offset : -2790260979
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1654887049478; DSPS: 54318703; Offset : -2790271410
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1674887721501; DSPS: 54974085; Offset : -2790270564
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1694888390973; DSPS: 55629467; Offset : -2790272610
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1714889147215; DSPS: 56284852; Offset : -2790279230
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1734889919707; DSPS: 56940237; Offset : -2790269650
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1754890705899; DSPS: 57595623; Offset : -2790276968
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1774891381151; DSPS: 58251005; Offset : -2790273024
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1794892054477; DSPS: 58906387; Offset : -2790270824
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1814892800251; DSPS: 59561771; Offset : -2790257862
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1834893561180; DSPS: 60217156; Offset : -2790259744
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1854894296745; DSPS: 60872540; Offset : -2790256652
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  846): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  846): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  846): battery changed pluggedType: 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1874894969238; DSPS: 61527923; Offset : -2790286011
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  846): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  846): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  846): tsOffsetIs: Apps: 1894895647251; DSPS: 62183305; Offset : -2790279359
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/PowerManagerServiceEx(  846): acquireWakeLockInternal: lock=278032789, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=846
,V/AlarmManager(  846): ELAPSED_WAKEUP set : Alarm{1f5e58c type 2 when 1902336 com.android.bluetooth} when 1902336
,W/bt-smp  ( 1988): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1988): Plain text(LSB ~ MSB) = 9d c5 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1988): Encrypted text(LSB ~ MSB) = 0b e4 d6 be 94 34 4e 12 b8 04 da 01 f9 db 3b 50 
W/bt-btm  ( 1988): Stopping oneshot timer
I/ProcessStatsService(  846): Prepared write state in 16ms
,I/ProcessStatsService(  846): Prepared write state in 13ms
,D/PowerManagerServiceEx(  846): releaseWakeLockInternal: lock=278032789 [*alarm*], flags=0x0
,I/ProcessStatsService(  846): Prepared write state in 10ms
,I/ProcessStatsService(  846): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-42-41.bin
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8318): 
D/AndroidRuntime( 8318): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8318): CheckJNI is OFF
I/ActivityManager(  846): Process com.google.android.talk (pid 7669) has died
D/AndroidRuntime( 8318): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  846): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  846): Killing 5278:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  846): WIN DEATH: Window{18b73644 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  846): Focus left window: Window{18b73644 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  846): Window went away: Window{18b73644 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  846): Skipping PackageSetting{5bece2b com.example.hello/10030} due to missing metadata
I/ActivityManager(  846):   Force finishing activity ActivityRecord{9e1ee11 u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  846): Display changed displayId=0
D/DSDPConnection( 1751): Display #0 changed.
W/ActivityManager(  846): Spurious death for ProcessRecord{17eb94d5 5278:com.test.thalitest/u0a316}, curProc for 5278: null
I/ActivityManager(  846): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3352): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
W/System.err( 3352): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3352): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3352): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3352): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3352): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3352): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3352): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3352): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3352): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3352): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3352): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 1935): Explicit concurrent mark sweep GC freed 28255(1723KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 4.117ms total 111.629ms
I/ActivityManager(  846): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8351 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.320ms
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.791ms
I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.369ms
I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
I/Activity( 1877): Activity.onPostResume() called 
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
I/art     (  846): Explicit concurrent mark sweep GC freed 68992(3MB) AllocSpace objects, 13(343KB) LOS objects, 33% free, 23MB/35MB, paused 3.145ms total 242.303ms
I/art     (  846): WaitForGcToComplete blocked for 136.139ms for cause Explicit
W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/SystemUI[Framework](  846): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/InputDispatcher(  846): Focus entered window: Window{3ad1bccf u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourcesManager( 8351): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8351): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8351): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/PhoneWindowManagerEx(  846): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  846): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  846): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3cd0d778,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1375): handleShortcutListChanged...
I/SystemUI[Framework](  846): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/PhoneWindowManagerEx(  846): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  846): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  846): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3cd0d778,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  846): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
D/KeyguardModel( 1375): handleShortcutListChanged...
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
D/administrator(  846): Handling package changes for user 0
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  846): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  846): Got RemoteException sending setActive(false) notification to pid 5278 uid 10316
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  846): Timeline: Activity_windows_visible id: ActivityRecord{95f2e5e u0 com.lge.launcher2/.Launcher t219} time:1905440
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1609): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/art     (  846): Explicit concurrent mark sweep GC freed 9471(562KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 5.276ms total 350.875ms
I/NotificationService(  846): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  846): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/LGEmail ( 8351): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  846): removeObsoleteFile: deleting file=220_task.xml
D/LGEmail ( 8351): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/AndroidRuntime( 8318): Shutting down VM
W/ResourcesManager(  846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType(  846): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/PackageChangeReceiver( 8351): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  846): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8378 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/AppUp4:AppBoxCP( 8378): onCreate
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
W/AppUp4:DB( 8378):  [AppBoxDatabaseHelper] construct
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/AppUp4:DB( 8378):  setFingerPrint start
I/AppUp4:DB( 8378):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8378):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8378):  SDK version = 0
I/AppUp4:DB( 8378):  beforefinger == newfinger no write in DB
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/AppUp4:AppBoxApplication( 8378): AppBoxApplication onCreate()
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/AppUp4:PreloadHelper( 8378): added Exclude : com.test.thalitest
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  846): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8401 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  846): Killing 7734:com.android.gallery3d/u0a23 (adj 15): empty #11
I/Timeline( 1877): Timeline: Activity_idle id: android.os.BinderProxy@1a9505b0 time:1906050
W/libprocessgroup(  846): failed to open /acct/uid_10023/pid_7734/cgroup.procs: No such file or directory
E/SharedPreferencesImpl( 1877): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
I/art     ( 1877): Explicit concurrent mark sweep GC freed 21190(1141KB) AllocSpace objects, 15(1532KB) LOS objects, 39% free, 15MB/25MB, paused 937us total 53.055ms

```
