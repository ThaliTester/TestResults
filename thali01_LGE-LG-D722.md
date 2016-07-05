#### Test 72145431fb64fa4_thali01_LGE-LG-D722 Logs


```
--------- beginning of main
07-05 12:50:22.067   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:50:25.995   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:50:25.995   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:50:25.995   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 132310249485; DSPS: 4433875; Offset : -3005021414
07-05 12:50:26.181  5831  5831 D AndroidRuntime: 
07-05 12:50:26.181  5831  5831 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 12:50:26.187  5831  5831 D AndroidRuntime: CheckJNI is OFF
07-05 12:50:26.393  5831  5831 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-05 12:50:26.419   880  1726 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 12:50:26.508   880  1726 D ActivityManager: setTaskToReturnTo : TaskRecord{33a20d06 #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 12:50:26.508   880  1726 D ActivityManager: setTaskToReturnTo : TaskRecord{33a20d06 #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-05 12:50:26.520   880  1726 D WindowStateEx: AppWindowTokenEx init.. 
07-05 12:50:26.531   880  1054 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-05 12:50:26.549  1949  1949 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
07-05 12:50:26.551   880  1054 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-05 12:50:26.553   880  1726 D InputDispatcher: Focus left window: Window{12810241 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
07-05 12:50:26.554  5831  5831 D AndroidRuntime: Shutting down VM
07-05 12:50:26.567   880  1054 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-05 12:50:26.568   880  1054 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-05 12:50:26.581   880  1054 D SplitWindow: check instance of lgWin Window{3687b6de u0 Starting com.test.thalitest}
07-05 12:50:26.625   880  1062 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5852 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:50:26.644  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
07-05 12:50:26.693  2020  2020 I HotwordDetector: Closing mic
07-05 12:50:26.699  2020  2356 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@37a60fab
07-05 12:50:26.699  2020  2356 V AudioRecord: stop()
07-05 12:50:26.699  2020  2356 D AudioRecord: AudioRecord->stop()
07-05 12:50:26.700   286  1615 V AudioFlinger: RecordHandle::stop()
07-05 12:50:26.700   286  1615 V AudioFlinger: RecordThread::stop
07-05 12:50:26.703   286  1615 V AudioFlinger: Record stopped OK
07-05 12:50:26.703   286  1615 V AudioPolicyManager: stopInput() input 17
07-05 12:50:26.704   286  1615 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
07-05 12:50:26.704   286  1615 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
07-05 12:50:26.705   286  1064 V AudioPolicyService: AudioCommandThread() waking up
07-05 12:50:26.705   286  1064 V AudioPolicyService: AudioCommandThread() processing release audio patch
07-05 12:50:26.705   286  1064 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
07-05 12:50:26.705   286  1064 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
07-05 12:50:26.705   286  1064 V AudioFlinger: ThreadBase::setParameters() routing=0
07-05 12:50:26.705   286  1064 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-05 12:50:26.706  1949  1949 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
07-05 12:50:26.708   286  2530 V AudioFlinger: processConfigEvents_l() remaining events 1
07-05 12:50:26.708   286  2530 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c3f000
07-05 12:50:26.711   286  2530 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
07-05 12:50:26.724   880   967 I WindowStateAnimator: Starting window displayed
07-05 12:50:26.732   880  1052 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
07-05 12:50:26.736   880  1052 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
07-05 12:50:26.737  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
07-05 12:50:26.740  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
07-05 12:50:26.740  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
07-05 12:50:26.740  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-05 12:50:26.746   880  1052 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-05 12:50:26.746   880  1052 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-05 12:50:26.747   880  1052 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 12:50:26.747   880  1052 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2e979e17,  pkg=WindowManager.LayoutParams
07-05 12:50:26.747   880  1052 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-05 12:50:26.755   286  2530 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
07-05 12:50:26.755   286  2530 V audio_hw_primary: disable_audio_route: enter: usecase(7)
07-05 12:50:26.755   286  2530 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
07-05 12:50:26.755   286  2530 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-05 12:50:26.762   286  2530 V audio_hw_primary: disable_audio_route: exit
07-05 12:50:26.762   286  2530 E audio_hw_primary: disable_snd_device: enter 144
07-05 12:50:26.762   286  2530 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
07-05 12:50:26.762   286  2530 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
07-05 12:50:26.766   286  2530 V audio_hw_primary: stop_input_stream: exit: status(0)
07-05 12:50:26.766   286  2530 V audio_hw_primary: in_standby: exit:  status(0)
,07-05 12:50:26.775   286  2530 V AudioFlinger: RecordThread: loop stopping
07-05 12:50:26.775   286  1064 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 12:50:26.775   286  1615 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
07-05 12:50:26.775   286  1615 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
07-05 12:50:26.775   286  1615 V AudioPolicyService: AudioCommandThread() adding update audio patch list
07-05 12:50:26.775   286  1615 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
07-05 12:50:26.776   286  1065 V AudioPolicyService: AudioCommandThread() waking up
07-05 12:50:26.776   286  1065 V AudioPolicyService: AudioCommandThread() processing update audio patch list
07-05 12:50:26.776   286  1065 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 12:50:26.776   286  1615 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
07-05 12:50:26.776   286  1615 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
07-05 12:50:26.777   286  1064 V AudioPolicyService: AudioCommandThread() waking up
07-05 12:50:26.777   286  1064 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
07-05 12:50:26.777   286  1064 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 286
07-05 12:50:26.777   286  1064 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
07-05 12:50:26.777   286  1064 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-05 12:50:26.777   286  2530 V AudioFlinger: RecordThread: loop starting
07-05 12:50:26.777   286  2530 V AudioFlinger: processConfigEvents_l() remaining events 1
07-05 12:50:26.777   286  2530 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
07-05 12:50:26.777   286  2530 V audio_hw_primary: in_set_parameters: exit: status(0)
07-05 12:50:26.777   286  2530 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c3f000
07-05 12:50:26.777   286  2530 V AudioFlinger: RecordThread: loop stopping
07-05 12:50:26.779   286  1064 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 12:50:26.784  2020  2356 V AudioRecord: stop()
07-05 12:50:26.785  2020  2356 V AudioRecord: stop()
07-05 12:50:26.785  2020  2356 V AudioRecord: stop()
07-05 12:50:26.800   286   286 V AudioFlinger: RecordHandle::stop()
07-05 12:50:26.801   286   286 V AudioFlinger: RecordThread::stop
07-05 12:50:26.801   286   286 V AudioPolicyManager: releaseInput() 17
07-05 12:50:26.801   286   286 V AudioPolicyManager: closeInput(17)
07-05 12:50:26.801   286   286 V AudioFlinger: closeInput() 17
07-05 12:50:26.801   286   286 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:50:26.801  1372  1397 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:50:26.801   286   286 V AudioFlinger: ThreadBase::exit
07-05 12:50:26.801  2020  2048 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:50:26.801  2055  2071 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:50:26.801   286  2530 V AudioFlinger: RecordThread: loop starting
07-05 12:50:26.801   286  2530 V AudioFlinger: RecordThread 0xb3c3f000 exiting
07-05 12:50:26.802   286   286 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dd40)
07-05 12:50:26.802   286   286 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
07-05 12:50:26.802  2075  2092 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:50:26.802  3096  3111 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:50:26.803   880  1863 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:50:26.804  1789  1806 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-05 12:50:26.804   286   286 V audio_hw_primary: in_standby: exit:  status(0)
07-05 12:50:26.804   286   286 V AudioPolicyService: AudioCommandThread() adding update audio port list
07-05 12:50:26.804   286   286 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
07-05 12:50:26.804   286   286 V AudioPolicyManager: releaseInput() exit
07-05 12:50:26.804   286  1065 V AudioPolicyService: AudioCommandThread() waking up
07-05 12:50:26.804   286  1065 V AudioPolicyService: AudioCommandThread() processing update audio port list
07-05 12:50:26.804   286  1065 V AudioPolicyService: AudioCommandThread() going to sleep
07-05 12:50:26.805   286   286 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
07-05 12:50:26.805   286   286 V AudioFlinger: removeClient_l() pid 2020, calling pid 286
07-05 12:50:26.806   286  1615 V AudioFlinger: releasing 16 from 2020 for -1
07-05 12:50:26.806   286  1615 V AudioFlinger:  decremented refcount to 0
07-05 12:50:26.806   286  1615 V AudioFlinger: purging stale effects
07-05 12:50:26.814  2020  2526 I HotwordRecognitionRnr: Hotword detection finished
07-05 12:50:26.822  2020  2358 I HotwordRecognitionRnr: Stopping hotword detection.
07-05 12:50:26.868  5852  5852 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-05 12:50:26.955  5852  5852 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-05 12:50:27.003  5852  5852 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3318-3323)
07-05 12:50:27.003  5852  5852 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:50:27.026  5852  5852 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12be4717}
07-05 12:50:27.029  5852  5852 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:50:27.033  5852  5852 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 12:50:27.050  5852  5852 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 12:50:27.050  5852  5852 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:27.056  5852  5852 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 12:50:27.072   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
07-05 12:50:27.101  5852  5884 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-05 12:50:27.124  5852  5852 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-05 12:50:27.134  5852  5852 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 12:50:27.134  5852  5852 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 12:50:27.138  5852  5852 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:50:27.138  5852  5852 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:50:27.138  5852  5852 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 12:50:27.138  5852  5852 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 12:50:27.138  5852  5852 I Adreno-EGL: Remote Branch: 
07-05 12:50:27.138  5852  5852 I Adreno-EGL: Local Patches: 
07-05 12:50:27.138  5852  5852 I Adreno-EGL: Reconstruct Branch: 
07-05 12:50:27.268   286  1304 V AudioPolicyService: registerClient() client 0xb57eed00, uid 10030
07-05 12:50:27.319   880  1053 D BluetoothManagerService: Message: 20
07-05 12:50:27.319   880  1053 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a943789:true
07-05 12:50:27.323  2055  3353 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
07-05 12:50:27.421  5852  5852 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:27.434  5852  5852 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 12:50:27.438  5852  5852 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-05 12:50:27.442  5852  5852 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-05 12:50:27.442  5852  5852 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-05 12:50:27.455  5852  5852 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-05 12:50:27.461  5852  5852 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:27.461  5852  5852 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:27.516  5852  5852 I Activity: Activity.onPostResume() called 
07-05 12:50:27.523  5852  5921 D OpenGLRenderer: Render dirty regions requested: true
07-05 12:50:27.524  5852  5921 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 12:50:27.529  5852  5921 D OpenGLRenderer: Enabling debug mode 0
07-05 12:50:27.540  5852  5852 D Atlas   : Validating map...
07-05 12:50:27.545   880  1726 D SplitWindow: check instance of lgWin Window{19fd14f9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 12:50:27.555  5852  5897 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-05 12:50:27.587   880  1726 D InputDispatcher: Focus entered window: Window{19fd14f9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 12:50:27.651   880  2028 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
07-05 12:50:27.657   880  1054 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s71ms
07-05 12:50:27.658   880  1054 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{349b8fc7 u0 com.test.thalitest/.MainActivity t241} time:133977
07-05 12:50:27.679  5852  5852 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@31258859 time:133999
07-05 12:50:27.744   880  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{30779e4a type 2 when 134054 com.google.android.gms} when 134054
07-05 12:50:27.751  2372  5932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:27.751  2372  5932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:27.751  2372  5932 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:27.751  2372  5932 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:27.751   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:50:27.751   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:50:27.752   282  5935 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:50:27.752   282  5935 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:27.752   282  5935 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 12:50:27.757   880  1051 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 12:50:27.817  5852  5852 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5852
07-05 12:50:27.963  5852  5852 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 12:50:28.368  5852  5931 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426117888
,07-05 12:50:28.382  5852  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 12:50:28.382  5852  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 12:50:28.382  5852  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 12:50:28.382  5852  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 12:50:28.382  5852  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 12:50:28.382  5852  5931 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@209a0682 added. We now have 1 listener(s)
,07-05 12:50:28.390   880  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 12:50:28.397  5852  5931 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,07-05 12:50:28.399  5852  5931 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
07-05 12:50:28.400  5852  5931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 12:50:28.400  5852  5931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 12:50:28.411  5852  5931 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e2c39c9 added. We now have 1 listener(s)
,07-05 12:50:28.411  5852  5931 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 12:50:28.427  2055  2070 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
,07-05 12:50:28.430  5852  5931 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-05 12:50:28.441  5852  5931 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-05 12:50:28.441  5852  5931 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-05 12:50:28.447  5852  5931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 12:50:28.448   880   968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 12:50:28.449  5852  5931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
07-05 12:50:28.457  2055  2070 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
,07-05 12:50:28.459  5852  5931 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:50:28.459  5852  5931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:50:28.459  5852  5931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:50:28.459  5852  5931 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 12:50:28.459  5852  5931 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:50:28.459  5852  5931 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 12:50:28.459  5852  5931 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 12:50:28.459  5852  5931 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 12:50:28.459  5852  5931 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 12:50:28.459  5852  5931 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 12:50:28.460  5852  5931 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 12:50:28.629  5852  5852 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 12:50:28.637  5852  5866 I art     : Background sticky concurrent mark sweep GC freed 26102(1676KB) AllocSpace objects, 5(76KB) LOS objects, 7% free, 10MB/11MB, paused 6.832ms total 73.374ms
07-05 12:50:28.716  5852  5866 I art     : CheckpointMarkThreadRoots callback created = 0x9aa9d240
,07-05 12:50:28.749  5852  5866 I art     : CheckpointMarkThreadRoots callback created = 0x9aa9d210
,07-05 12:50:29.282  5852  5959 W jxcore-log: Initializing JXcore engine
07-05 12:50:29.282  5852  5959 W jxcore-log: JXcore engine is ready
,07-05 12:50:29.362  5959  5959 W Thread-674: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5043]" dev="sockfs" ino=5043 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-05 12:50:29.382  5959  5959 W Thread-674: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 12:50:29.382  5959  5959 W Thread-674: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8235]" dev="sockfs" ino=8235 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-05 12:50:29.382  5959  5959 W Thread-674: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-05 12:50:29.382  5959  5959 W Thread-674: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-05 12:50:29.382  5959  5959 W Thread-674: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[27159]" dev="sockfs" ino=27159 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-05 12:50:29.416  5852  5959 W jxcore-log: Starting JXcore engine
,07-05 12:50:29.567  5852  5959 W jxcore-log: Platform android
07-05 12:50:29.567  5852  5959 W jxcore-log: 
07-05 12:50:29.567  5852  5959 W jxcore-log: Process ARCH arm
07-05 12:50:29.567  5852  5959 W jxcore-log: 
,07-05 12:50:29.650   880  2039 I art     : Explicit concurrent mark sweep GC freed 42130(2004KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.116ms total 144.735ms
,07-05 12:50:29.858  5852  5959 I jxcore-log: JXcore Cordova bridge is ready!
07-05 12:50:29.858  5852  5959 I jxcore-log: 
07-05 12:50:29.859  5852  5959 W jxcore-log: JXcore engine is started
,07-05 12:50:29.864  5852  5931 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-05 12:50:29.865  5852  5852 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-05 12:50:31.507  2075  2075 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,07-05 12:50:31.522  2075  2075 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,07-05 12:50:32.076   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:50:34.474   880  1910 I ActivityManager: Process com.google.android.apps.docs (pid 5518) has died
,07-05 12:50:37.081   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:50:39.286   880  1056 I PowerManagerService: ALS enabled for SRE
07-05 12:50:39.286   880  1056 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (25606 ms ago)
,07-05 12:50:39.324   880  1348 D qdlights: set_light_backlight: 252
,07-05 12:50:39.336   880  1348 D qdlights: set_light_backlight: 249
,07-05 12:50:39.352   880  1348 D qdlights: set_light_backlight: 245
,07-05 12:50:39.369   880  1348 D qdlights: set_light_backlight: 242
,07-05 12:50:39.386   880  1348 D qdlights: set_light_backlight: 239
,07-05 12:50:39.403   880  1348 D qdlights: set_light_backlight: 235
,07-05 12:50:39.419   880  1348 D qdlights: set_light_backlight: 232
,07-05 12:50:39.436   880  1348 D qdlights: set_light_backlight: 229
,07-05 12:50:39.453   880  1348 D qdlights: set_light_backlight: 225
,07-05 12:50:39.469   880  1348 D qdlights: set_light_backlight: 222
,07-05 12:50:39.486   880  1348 D qdlights: set_light_backlight: 219
,07-05 12:50:39.502   880  1348 D qdlights: set_light_backlight: 215
,07-05 12:50:39.519   880  1348 D qdlights: set_light_backlight: 212
,07-05 12:50:39.536   880  1348 D qdlights: set_light_backlight: 209
,07-05 12:50:39.552   880  1348 D qdlights: set_light_backlight: 205
,07-05 12:50:39.569   880  1348 D qdlights: set_light_backlight: 202
,07-05 12:50:39.586   880  1348 D qdlights: set_light_backlight: 199
,07-05 12:50:39.603   880  1348 D qdlights: set_light_backlight: 195
,07-05 12:50:39.619   880  1348 D qdlights: set_light_backlight: 192
,07-05 12:50:39.636   880  1348 D qdlights: set_light_backlight: 188
,07-05 12:50:39.652   880  1348 D qdlights: set_light_backlight: 185
,07-05 12:50:39.669   880  1348 D qdlights: set_light_backlight: 182
,07-05 12:50:39.686   880  1348 D qdlights: set_light_backlight: 178
,07-05 12:50:39.702   880  1348 D qdlights: set_light_backlight: 175
,07-05 12:50:39.719   880  1348 D qdlights: set_light_backlight: 172
,07-05 12:50:39.736   880  1348 D qdlights: set_light_backlight: 168
,07-05 12:50:39.752   880  1348 D qdlights: set_light_backlight: 165
,07-05 12:50:39.769   880  1348 D qdlights: set_light_backlight: 162
,07-05 12:50:39.786   880  1348 D qdlights: set_light_backlight: 158
,07-05 12:50:39.802   880  1348 D qdlights: set_light_backlight: 155
,07-05 12:50:39.819   880  1348 D qdlights: set_light_backlight: 152
,07-05 12:50:39.836   880  1348 D qdlights: set_light_backlight: 148
,07-05 12:50:39.853   880  1348 D qdlights: set_light_backlight: 145
,07-05 12:50:39.869   880  1348 D qdlights: set_light_backlight: 142
,07-05 12:50:39.886   880  1348 D qdlights: set_light_backlight: 138
,07-05 12:50:39.903   880  1348 D qdlights: set_light_backlight: 135
,07-05 12:50:39.919   880  1348 D qdlights: set_light_backlight: 132
,07-05 12:50:39.936   880  1348 D qdlights: set_light_backlight: 128
,07-05 12:50:39.954   880  1348 D qdlights: set_light_backlight: 125
,07-05 12:50:39.969   880  1348 D qdlights: set_light_backlight: 122
,07-05 12:50:39.986   880  1348 D qdlights: set_light_backlight: 118
,07-05 12:50:40.003   880  1348 D qdlights: set_light_backlight: 115
,07-05 12:50:40.019   880  1348 D qdlights: set_light_backlight: 112
,07-05 12:50:40.036   880  1348 D qdlights: set_light_backlight: 108
,07-05 12:50:40.053   880  1348 D qdlights: set_light_backlight: 105
,07-05 12:50:40.069   880  1348 D qdlights: set_light_backlight: 102
,07-05 12:50:40.086   880  1348 D qdlights: set_light_backlight: 98
,07-05 12:50:40.103   880  1348 D qdlights: set_light_backlight: 95
,07-05 12:50:40.119   880  1348 D qdlights: set_light_backlight: 92
,07-05 12:50:40.136   880  1348 D qdlights: set_light_backlight: 88
,07-05 12:50:40.153   880  1348 D qdlights: set_light_backlight: 85
,07-05 12:50:40.169   880  1348 D qdlights: set_light_backlight: 82
,07-05 12:50:40.186   880  1348 D qdlights: set_light_backlight: 78
,07-05 12:50:40.203   880  1348 D qdlights: set_light_backlight: 75
,07-05 12:50:40.219   880  1348 D qdlights: set_light_backlight: 72
,07-05 12:50:40.236   880  1348 D qdlights: set_light_backlight: 68
,07-05 12:50:40.254   880  1348 D qdlights: set_light_backlight: 65
,07-05 12:50:40.269   880  1348 D qdlights: set_light_backlight: 62
,07-05 12:50:40.286   880  1348 D qdlights: set_light_backlight: 58
,07-05 12:50:40.303   880  1348 D qdlights: set_light_backlight: 55
,07-05 12:50:40.319   880  1348 D qdlights: set_light_backlight: 52
,07-05 12:50:40.336   880  1348 D qdlights: set_light_backlight: 48
,07-05 12:50:40.353   880  1348 D qdlights: set_light_backlight: 45
,07-05 12:50:40.369   880  1348 D qdlights: set_light_backlight: 42
,07-05 12:50:40.386   880  1348 D qdlights: set_light_backlight: 38
,07-05 12:50:40.403   880  1348 D qdlights: set_light_backlight: 35
,07-05 12:50:40.419   880  1348 D qdlights: set_light_backlight: 32
,07-05 12:50:40.436   880  1348 D qdlights: set_light_backlight: 28
,07-05 12:50:40.457   880  1348 D qdlights: set_light_backlight: 25
,07-05 12:50:40.469   880  1348 D qdlights: set_light_backlight: 22
,07-05 12:50:40.486   880  1348 D qdlights: set_light_backlight: 18
,07-05 12:50:40.503   880  1348 D qdlights: set_light_backlight: 15
,07-05 12:50:40.519   880  1348 D qdlights: set_light_backlight: 12
,07-05 12:50:40.536   880  1348 D qdlights: set_light_backlight: 10
,07-05 12:50:42.086   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:50:45.821  5852  5959 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 12:50:45.821  5852  5959 I jxcore-log: 
,07-05 12:50:45.825  5852  5959 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 12:50:45.825  5852  5959 I jxcore-log: 
07-05 12:50:45.828  2055  3353 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
07-05 12:50:45.829  5852  5959 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:50:45.829  5852  5959 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:50:45.829  5852  5959 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:50:45.829  5852  5959 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 12:50:45.829  5852  5959 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:50:45.829  5852  5959 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 12:50:45.829  5852  5959 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 12:50:45.829  5852  5959 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 12:50:45.830  2055  3353 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
07-05 12:50:45.831  5852  5959 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-05 12:50:45.834  5852  5959 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 12:50:45.834  5852  5959 I jxcore-log: 
,07-05 12:50:45.837  5852  5959 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 12:50:45.837  5852  5959 I jxcore-log: 
07-05 12:50:45.991   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:50:45.991   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:50:45.991   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 152311056406; DSPS: 5089261; Offset : -3005006883
,07-05 12:50:46.286   880  1056 I PowerManagerService: ALS enabled for SRE
07-05 12:50:46.286   880  1056 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32606 ms ago)
,07-05 12:50:46.290   880  1056 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-05 12:50:46.299   880  1056 I PowerManagerService: ALS enabled for SRE
07-05 12:50:46.299   880  1056 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (32619 ms ago)
,07-05 12:50:46.304   880  1056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
07-05 12:50:46.307   880  1056 I PowerManagerService: Sleeping (uid 1000)...
07-05 12:50:46.307   880  1056 D LPWGController: [updateScreenState] screen on = false
07-05 12:50:46.311   880  1056 D LPWGController: disable proximity sensor
,07-05 12:50:46.312   880  1056 D LPWGController: enable proximity sensor
07-05 12:50:46.323   880  1056 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@f9c498f] by com.android.server.power.ProximitySensorListener.enable():120
,07-05 12:50:46.329   880  1056 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
07-05 12:50:46.329   880  1056 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
07-05 12:50:46.329   880  1056 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
07-05 12:50:46.329   880  1056 I sensors_hal_Ctx: activate: handle is 48, enable
07-05 12:50:46.329   880  1056 V sensors_hal_Ctx: activate sensors is 1400000000000
07-05 12:50:46.329   880  1056 D sensors_hal_Thresh: enable: handle=48
07-05 12:50:46.329   880  1056 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
07-05 12:50:46.330   880  1056 D sensors_hal_Util: waitForResponse: timeout=1000
07-05 12:50:46.344   880   986 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
07-05 12:50:46.344   880   986 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
07-05 12:50:46.344   880  1056 D sensors_hal_Thresh: enable: Received response: 0
,07-05 12:50:46.345   880  1056 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (32664 ms ago)
07-05 12:50:46.370   880  1056 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:50:46.370   880  1056 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:50:46.370   880  1056 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 12:50:46.370   880  1056 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 12:50:46.370   880  1056 I Adreno-EGL: Remote Branch: 
07-05 12:50:46.370   880  1056 I Adreno-EGL: Local Patches: 
07-05 12:50:46.370   880  1056 I Adreno-EGL: Reconstruct Branch: 
,07-05 12:50:46.400   247  1060 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1075 us)
,07-05 12:50:46.466  5852  5959 I jxcore-log: Unit Test app is loaded
07-05 12:50:46.466  5852  5959 I jxcore-log: 
,07-05 12:50:46.488  5852  5959 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-05 12:50:46.488  5852  5959 I jxcore-log: 
,07-05 12:50:46.492  5852  5852 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-05 12:50:46.512   880  2134 D WifiServiceImplEx: setWifiEnabled: true pid=5852, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,07-05 12:50:46.518   880  2134 D WifiService: setWifiEnabled: true pid=5852, uid=10030
,07-05 12:50:46.546   880  2192 D WifiServiceImplEx: disconnect pid=5852, uid=10030, packageName=com.test.thalitest
07-05 12:50:46.546   880  1921 D WifiServiceImplEx: reconnect pid=5852, uid=10030, packageName=com.test.thalitest
07-05 12:50:46.552  5852  5959 I jxcore-log: My device name is: LGE-LG-D722
07-05 12:50:46.552  5852  5959 I jxcore-log: 
07-05 12:50:46.555  5852  5959 I jxcore-log: WARN testUtils: myNameCallback not set!
07-05 12:50:46.555  5852  5959 I jxcore-log: 
,07-05 12:50:46.567   880  1309 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-05 12:50:46.568   880  1309 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
07-05 12:50:46.572   431   975 I Sensors : sns_pwr.c(273):acquiring wakelock
07-05 12:50:46.573   880   986 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,07-05 12:50:46.576   880   986 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
07-05 12:50:46.576   880   986 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
07-05 12:50:46.576   880   986 D sensors_hal_Thresh: processInd: handle 48, count=1
07-05 12:50:46.576   880   986 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
07-05 12:50:46.576   880   986 I sensors_hal_Thresh: processInd : proximity state changed - FAR
07-05 12:50:46.576   880  1022 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
07-05 12:50:46.576   880  1309 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
07-05 12:50:46.576   880  1309 E WifiHW  : band=b
07-05 12:50:46.576   880  1309 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
07-05 12:50:46.576   880  1022 D sensors_hal_Ctx: poll: count: 256
07-05 12:50:46.576   880  1022 I sensors_hal_Ctx: poll: released wakelock sensor_ind
07-05 12:50:46.576   880  1022 D sensors_hal_Util: waitForResponse: timeout=0
07-05 12:50:46.577   880   880 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-05 12:50:46.582   880  1056 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
07-05 12:50:46.582   880  1056 I LPWGController: current mode = 1  value = 1 1
07-05 12:50:46.583   880  1056 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
07-05 12:50:46.584   282  1050 D SoftapController: Softap fwReload - Ok
,07-05 12:50:46.585   880   880 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-05 12:50:46.588   880   880 D Ulp_jni : JNI:system_update. Event-4
07-05 12:50:46.601   880  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:46.601   880  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:50:46.606   282  1050 D CommandListener: Setting iface cfg
07-05 12:50:46.607   282  1050 D CommandListener: Trying to bring down wlan0
07-05 12:50:46.608   282  1050 D CommandListener: Clearing all IP addresses on wlan0
07-05 12:50:46.615   880  1309 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,07-05 12:50:46.678   880  1056 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,07-05 12:50:46.681  6004  6004 I wpa_supplicant: Successfully initialized wpa_supplicant
07-05 12:50:46.722   880  1309 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-05 12:50:46.728  5852  5852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 12:50:46.732  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,07-05 12:50:46.765  6004  6004 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-05 12:50:46.765  6004  6004 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-05 12:50:46.766  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:46.758 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-05 12:50:46.766  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
07-05 12:50:46.779   880  1021 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6012 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-05 12:50:46.792   880   880 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,07-05 12:50:46.834  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,07-05 12:50:46.840  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,07-05 12:50:46.840  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-05 12:50:46.841  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
,07-05 12:50:46.922   880  1348 D qdlights: set_light_backlight: 0
,07-05 12:50:46.932   880  1056 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
07-05 12:50:46.932   880  1056 I sensors_hal_Ctx: activate: handle is 46, disable
07-05 12:50:46.932   880  1056 V sensors_hal_Ctx: activate sensors is 1000000000000
07-05 12:50:46.932   880  1056 D sensors_hal_LP2: enable: handle=46
07-05 12:50:46.932   880  1056 D sensors_hal_LP2: enable: Disabling sensor handle=46
07-05 12:50:46.933   880  1056 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
07-05 12:50:46.935   247   247 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
07-05 12:50:46.935   247   247 D qdhwcomposer: hwc_blank: Blanking display: 0
07-05 12:50:46.937   880  1054 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-05 12:50:46.938   880   880 V ActivityManager: Display changed displayId=0
,07-05 12:50:46.961  1789  1789 D DSDPConnection: Display #0 changed.
,07-05 12:50:47.021   880  1012 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
07-05 12:50:47.021   880  1012 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,07-05 12:50:47.090   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:50:47.103  6012  6012 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:50:47.104  6012  6012 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,07-05 12:50:47.104  6012  6012 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-05 12:50:47.105  6012  6012 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-05 12:50:47.106  6012  6012 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-05 12:50:47.121   247   247 D qdhwcomposer: hwc_blank: Done blanking display: 0
07-05 12:50:47.122   880  1348 D SurfaceControl: Excessive delay in setPowerMode(): 186ms
07-05 12:50:47.122   247   684 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-05 12:50:47.123   880  1348 I QCOM PowerHAL: Got set_interactive hint
07-05 12:50:47.149  5852  5852 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-05 12:50:47.149  5852  5852 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-05 12:50:47.149  1372  2474 D KeyguardViewMediator: onScreenTurnedOff(3)
,07-05 12:50:47.159  1372  2474 D KeyguardViewMediator: notifyScreenOffLocked
07-05 12:50:47.160  1331  1346 D SmartCoverViewMediator: onScreenTurnedOff(3)
07-05 12:50:47.172  1331  1346 D SmartCoverViewMediator: notifyScreenOffLocked
07-05 12:50:47.174  1331  1331 D SmartCoverViewMediator: handleNotifyScreenOFF
,07-05 12:50:47.187  5852  5852 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@64cf4a5 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@15a80baf, 16908290=android.view.AbsSavedState$1@15a80baf}, android:focusedViewId=100}]}]
07-05 12:50:47.187  5852  5852 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-05 12:50:47.187  5852  5852 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 12:50:47.187  5852  5852 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-05 12:50:47.188  1372  2474 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
07-05 12:50:47.189  1372  1372 D KeyguardViewMediator: handleNotifyScreenOff
07-05 12:50:47.204   880   880 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
,07-05 12:50:47.208  1372  1372 D ScreenTurnOffBySensor: unregisterProximitySensor
07-05 12:50:47.215   286   286 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 880
07-05 12:50:47.216   286   286 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 12:50:47.216   286   286 V voice   : voice_set_parameters: enter: screen_state=on
,07-05 12:50:47.219   286   286 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
07-05 12:50:47.219   286   286 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-05 12:50:47.219   286   286 V voice   : voice_set_parameters: exit with code(0)
07-05 12:50:47.219   286   286 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
07-05 12:50:47.219   286   286 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-05 12:50:47.219   286   286 V msm8974_platform: platform_set_parameters: exit with code(0)
07-05 12:50:47.219   286   286 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-05 12:50:47.220   286   286 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
07-05 12:50:47.220   286   286 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-05 12:50:47.220   286   286 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-05 12:50:47.221  1372  1372 D StatusBarWindowView: onScreenTurnedOff why = 3
07-05 12:50:47.226  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:50:47.228  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
,07-05 12:50:47.274  6012  6012 I IndexDatabaseHelper: Using schema version: 115
,07-05 12:50:47.277  6012  6012 I IndexDatabaseHelper: Index is fine
,07-05 12:50:47.435  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-05 12:50:47.514  6012  6012 D WiFiOffLoadUpdatePriority: remove : truetruefalse
07-05 12:50:47.519  6012  6012 D WiFiOffLoadUpdatePriority: remove2
07-05 12:50:47.519  6012  6012 V WiFiOffLoadSharedPrefsUtils: save wifi state
07-05 12:50:47.520  6012  6012 V WiFiOffLoadSharedPrefsUtils: save remove
07-05 12:50:47.520  6012  6012 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
07-05 12:50:47.521  6012  6012 D WiFiOffLoadBroadcast: S: false, R: true
,07-05 12:50:47.573   880  2583 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6033 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-05 12:50:47.583   880  1019 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-05 12:50:47.600   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 24.460ms
,07-05 12:50:47.625   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 24.554ms
,07-05 12:50:47.648   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 21.989ms
,07-05 12:50:47.680   880  1359 D SplitWindow: check instance of lgWin Window{215c2dfa u0 SearchPanel}
07-05 12:50:47.687  1911  1911 I QCNEJ   : |CORE| sendScreenState: state:true
,07-05 12:50:47.702  1875  2041 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,07-05 12:50:47.704  1875  2041 D LEDService: stopPatternFlashing()
07-05 12:50:47.704  1875  2041 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 12:50:47.706  1875  2041 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-05 12:50:47.706  1875  2041 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 12:50:47.708  1875  2041 I LEDService: updateLightsLocked : turn off led
07-05 12:50:47.708  1875  2041 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 12:50:47.708   880  1881 D InputDispatcher: Window went away: Window{b2c3633 u0 SearchPanel}
07-05 12:50:47.713  1875  2041 D LEDHandler: RESTART MSG
,07-05 12:50:47.715  1372  1372 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
07-05 12:50:47.734  1372  1372 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,07-05 12:50:47.747  1875  1875 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,07-05 12:50:47.749  1875  1875 D Cliptray Service: lockStatus = 0
07-05 12:50:47.754  1857  1857 D LNfcService: action : android.intent.action.SCREEN_ON
07-05 12:50:47.762   880   880 D Ulp_jni : JNI:system_update. Event-0
,07-05 12:50:47.768  1857  6051 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
07-05 12:50:47.768  1857  6051 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
07-05 12:50:47.768  1857  6051 D LNfcService: isRequireNfcCRouting() return true
07-05 12:50:47.768  1857  6051 D LNfcService: isHCERoutingtoHost() return : true
07-05 12:50:47.769  1857  6051 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-05 12:50:47.769  1857  6051 D NfcService: mEnableLPD: true
07-05 12:50:47.769  1857  6051 D NfcService: mEnableReader: false
07-05 12:50:47.769  1857  6051 D NfcService: mEnableHostRouting: true
07-05 12:50:47.769  1857  6051 D NfcService: newParams.techmask= mTechMask: default
07-05 12:50:47.769  1857  6051 D NfcService: mEnableLPD: true
07-05 12:50:47.769  1857  6051 D NfcService: mEnableReader: false
07-05 12:50:47.769  1857  6051 D NfcService: mEnableHostRouting: true
07-05 12:50:47.769  1857  6051 D NfcService: screenState= 3
07-05 12:50:47.769  1857  6051 D NfcService: Discovery configuration equal, not updating.
,07-05 12:50:47.779   282  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-05 12:50:47.780   282  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,07-05 12:50:47.797  1789  1789 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
07-05 12:50:47.824  6033  6033 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-05 12:50:47.826   880  1359 I ActivityManager: Killing 5612:com.google.android.apps.plus/u0a86 (adj 15): empty #11
07-05 12:50:47.838  6004  6004 E wpa_supplicant: USIM:  scard_init function
,07-05 12:50:47.841  6004  6004 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-05 12:50:47.843   282  1043 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
07-05 12:50:47.844   282  1043 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
07-05 12:50:47.845   282  1043 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
07-05 12:50:47.849   880  1051 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:47.849   880  1051 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:47.934  6004  6004 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-05 12:50:47.940   880  1948 W libprocessgroup: failed to open /acct/uid_10086/pid_5612/cgroup.procs: No such file or directory
07-05 12:50:47.943   880  1053 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-05 12:50:47.947   880  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:47.947   880  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:47.947   880  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:47.948   880  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:47.948   282  1045 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 12:50:47.948   282  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-05 12:50:47.948   282  6054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
,07-05 12:50:47.948   282  6054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:47.949   282  6054 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-05 12:50:47.950  6004  6004 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-05 12:50:47.951   880  1051 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 12:50:47.958  2822  2822 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:50:47
07-05 12:50:47.964  2822  2822 D WeatherService: 2 : ACTION screen on
,07-05 12:50:47.968  2822  2822 D WeatherService: 2 : shouldTimeTickRegistered : false
07-05 12:50:47.973   880  1309 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
07-05 12:50:47.974   880  1309 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-05 12:50:47.975   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:47.975   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:50:47.980   880   880 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-05 12:50:47.980   880  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:47.980   880  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:47.980  6012  6012 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-05 12:50:47.981  6012  6012 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-05 12:50:47.981  6012  6012 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-05 12:50:47.981  6012  6012 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-05 12:50:47.981  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
07-05 12:50:47.981  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:47.981 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-05 12:50:47.982  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
07-05 12:50:47.983  2055  3353 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
07-05 12:50:47.984  5852  5852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 12:50:47.984  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:50:47.984  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:50:47.984  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:50:47.984  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:50:47.984  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 12:50:47.984  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 12:50:47.984  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 12:50:47.985  6012  6012 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-05 12:50:47.985  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 12:50:47.985  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:47.985   880  1314 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-05 12:50:47.985  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-05 12:50:47.986  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
07-05 12:50:47.987  2055  3353 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
07-05 12:50:47.988  5852  5852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-05 12:50:47.988   880   880 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
,07-05 12:50:47.998  2822  2822 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-05 12:50:47.998  2822  2822 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:50:47
07-05 12:50:48.008   880  1309 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-05 12:50:48.009   880  1309 D WifiStateMachine: enableVerboseLogging : level 2
,07-05 12:50:48.011  3935  3935 D AppCleanupService: android.intent.action.SCREEN_ON
07-05 12:50:48.028   880  1309 D WifiStateMachine: Setting OUI to DA-A1-19
07-05 12:50:48.029   880  1309 D WifiNative-HAL: Setting external_sim to 1
,07-05 12:50:48.032   880  1309 I WifiNative-HAL: startHal
07-05 12:50:48.032   880  1309 E wifi    : getStaticLongField sWifiHalHandle 0x9b4a28ec
07-05 12:50:48.032   880  1309 I WifiHAL : Initializing wifi
07-05 12:50:48.032  5714  5714 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.032   880  1309 I WifiHAL : Creating socket
07-05 12:50:48.035  1875  1875 D WfdsService: Supplicant Connection state is changed : true
07-05 12:50:48.036   880  1309 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-05 12:50:48.036   880  1309 D wifi    : Did set static halHandle = 0xb06c8600
07-05 12:50:48.036   880  1309 D wifi    : halHandle = 0xb06c8600, mVM = 0xb487c280, mCls = 0x701d7a
07-05 12:50:48.036   880  1309 E wifi    : getStaticLongField sWifiHalHandle 0x9b4a289c
07-05 12:50:48.036   880  1309 D wifi    : array field set
07-05 12:50:48.036   880  1309 I WifiNative-HAL: interface[0] = wlan0
07-05 12:50:48.036   880  1309 I WifiNative-HAL: interface[1] = p2p0
07-05 12:50:48.037  1875  2138 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-05 12:50:48.037  1875  2138 D WfdsService: Set the WFDS Monitor: true
07-05 12:50:48.037   880  1309 D wifi    : setting scan oui 0xaafcf910
07-05 12:50:48.037   880  1309 D WifiHAL : Sending mac address OUI
07-05 12:50:48.037   880  1309 E WifiHAL : failed to set scanning mac OUI; result = -95
07-05 12:50:48.037   880  1309 D WifiStateMachine: Setting OUI to DA-A1-19
07-05 12:50:48.037   880  1309 I WifiNative-HAL: startHal
07-05 12:50:48.038   880  1309 D wifi    : setting scan oui 0xaafcf910
07-05 12:50:48.038   880  1309 D WifiHAL : Sending mac address OUI
07-05 12:50:48.038   880  1309 E WifiHAL : failed to set scanning mac OUI; result = -95
07-05 12:50:48.038   880  6057 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1335065088
07-05 12:50:48.038   880  6057 D wifi    : waitForHalEvents called, vm = 0xb487c280, obj = 0x701d7a, env = 0x9a78c080
07-05 12:50:48.038   880  6057 E wifi    : getStaticLongField sWifiHalHandle 0x95908b2c
07-05 12:50:48.041  1875  2138 D WfdsMonitor: WfdsMonitorThread create
07-05 12:50:48.043  1875  2138 D WfdsMonitor: WFDS Monitor is created and started
07-05 12:50:48.043  1875  2138 D WfdsService: WiFi: Supplicant connection re-established
,07-05 12:50:48.043   286  1615 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 880
07-05 12:50:48.043   286  1615 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-05 12:50:48.044   286  1615 V voice   : voice_set_parameters: enter: screen_state=off
07-05 12:50:48.044   286  1615 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
07-05 12:50:48.044   286  1615 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-05 12:50:48.044   286  1615 V voice   : voice_set_parameters: exit with code(0)
07-05 12:50:48.044   286  1615 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
07-05 12:50:48.044   286  1615 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-05 12:50:48.044   286  1615 V msm8974_platform: platform_set_parameters: exit with code(0)
07-05 12:50:48.044   286  1615 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-05 12:50:48.044   286  1615 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-05 12:50:48.044   286  1615 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-05 12:50:48.047   880   880 D WifiHS20: hidePasspointNotification off =false
07-05 12:50:48.048  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-05 12:50:48.049   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.049   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.049   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-05 12:50:48.050   880  1315 D WifiController: CMD_SCREEN_OFF 
07-05 12:50:48.050   880  1315 D WifiController: shouldWifiStayAwake TRUE
07-05 12:50:48.063  1875  6058 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,07-05 12:50:48.066  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:48.066 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-05 12:50:48.067  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-05 12:50:48.067  1875  6058 E CtrlSupplicant: Succeed to open control connection
07-05 12:50:48.067  1875  6058 E CtrlSupplicant: Succeed to open monitor connection
07-05 12:50:48.068  1875  6058 D WfdsMonitor: Supplicant connection established
07-05 12:50:48.068   880   880 D WifiScanningService: SCAN_AVAILABLE : 3
07-05 12:50:48.068   880   880 D RttService: SCAN_AVAILABLE : 3
07-05 12:50:48.068  1875  2138 D WfdsService: Connected to the supplicant for wfds
07-05 12:50:48.072   880  1330 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.072  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-05 12:50:48.072   431   441 I Sensors : sns_pwr.c(301):releasing wakelock
07-05 12:50:48.073   880  1329 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.073   880  1329 I WifiNative-HAL: startHal
07-05 12:50:48.073   880  1329 D wifi    : getting scan capabilities on interface[0] = 0xaafcf910
07-05 12:50:48.073   880  1329 D WifiHAL : Creating message to get scan capablities; iface = 24
07-05 12:50:48.073   880  1329 D wifi    : failed to get capabilities : -95
,07-05 12:50:48.074   880  1329 E WifiScanningService: could not get scan capabilities
07-05 12:50:48.074   880  1308 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.076   880  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:48.078   880  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:48.079   282  1050 D CommandListener: Setting iface cfg
07-05 12:50:48.080  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 12:50:48.080  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:48.080  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-05 12:50:48.081  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:48.081  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:48.081  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:48.082  6012  6012 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-05 12:50:48.086  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
07-05 12:50:48.086  6012  6012 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-05 12:50:48.087  6012  6012 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-05 12:50:48.087  6012  6012 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-05 12:50:48.087  6012  6012 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-05 12:50:48.087  6012  6012 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-05 12:50:48.087  6012  6012 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-05 12:50:48.089   282  1050 D CommandListener: Trying to bring up p2p0
07-05 12:50:48.089   880  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-05 12:50:48.089   880  1308 D LGWifiP2pService: P2pEnablingState
07-05 12:50:48.090   880  1308 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.090   880  1308 D LGWifiP2pService: P2p socket connection successful
07-05 12:50:48.090   880  1308 D LGWifiP2pService: P2pEnabledState
07-05 12:50:48.091   880  1308 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-05 12:50:48.092   880  1308 D LGWifiP2pService: before postfix = G3s-1
07-05 12:50:48.092   880  1308 D WifiServerServiceExt: postfix byte check : 5
07-05 12:50:48.092   880  1308 D LGWifiP2pService: after postfix = G3s-1
07-05 12:50:48.092   880  1309 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
07-05 12:50:48.093   880  1019 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
07-05 12:50:48.094   880  1308 D WifiNative-HAL: p2pGetDeviceAddress
07-05 12:50:48.094   880  1308 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
07-05 12:50:48.095   880  1309 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-05 12:50:48.097   880  1308 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
07-05 12:50:48.097  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-05 12:50:48.098  6004  6004 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,07-05 12:50:48.099   880  1309 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-05 12:50:48.105  1875  1875 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-05 12:50:48.107  6012  6012 D WiFiOffLoadUpdatePriority: remove : truetruetrue
07-05 12:50:48.111  1875  1875 D WfdsService: Update P2p Interface State: 3
,07-05 12:50:48.118  1911  1911 I QCNEJ   : |CORE| sendScreenState: state:false
07-05 12:50:48.119  1875  2041 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-05 12:50:48.120  1875  2041 D LEDService: stopPatternFlashing()
07-05 12:50:48.120  1875  2041 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 12:50:48.120  1875  1875 D VolumeVibrator: clear
07-05 12:50:48.121  1875  2041 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-05 12:50:48.121  1875  2041 D qdlights: set_light_notifications: 0,0,0,0,3
07-05 12:50:48.122  1875  1875 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
07-05 12:50:48.123  1875  2041 I LEDService: updateLightsLocked : turn on led
07-05 12:50:48.123  1857  1857 D LNfcService: action : android.intent.action.SCREEN_OFF
07-05 12:50:48.123  1875  2041 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
07-05 12:50:48.124  1875  2041 E LEDService: Can't handle this request of patternId:0
07-05 12:50:48.124  1875  2041 D LEDHandler: RESTART MSG
,07-05 12:50:48.125  1857  2224 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
07-05 12:50:48.145  1949  1949 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,07-05 12:50:48.160  6004  6004 E wpa_supplicant: disconnect_rssi_lvl: -100
,07-05 12:50:48.161   880  1309 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
07-05 12:50:48.162  6004  6004 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
07-05 12:50:48.163   880  1308 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-05 12:50:48.164   880  1309 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
07-05 12:50:48.174   880  1309 E WifiNative-wlan0: doBoolean: disable
07-05 12:50:48.183  1372  1395 I art     : Background partial concurrent mark sweep GC freed 6913(378KB) AllocSpace objects, 75(9MB) LOS objects, 40% free, 22MB/37MB, paused 1.782ms total 130.825ms
,07-05 12:50:48.207  6004  6004 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,07-05 12:50:48.209  6004  6004 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
07-05 12:50:48.210   880  2028 I ActivityManager: Process com.google.android.gms:car (pid 5576) has died
07-05 12:50:48.215   880  1308 D LGWifiP2pService: sending p2p connection changed broadcast
07-05 12:50:48.217   880  1308 D LGWifiP2pService: InactiveState
07-05 12:50:48.217   880  1308 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.217   880  1308 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.217   880  1308 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.217   880  1308 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.218   880  1308 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.218   880  1308 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.218   880   880 E WifiServerServiceExt: No p2p device connected
07-05 12:50:48.219  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
07-05 12:50:48.220  1789  1789 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
07-05 12:50:48.220  1875  1875 D WfdsService: WifiP2pState is changed : true
,07-05 12:50:48.223  1875  1875 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-05 12:50:48.225  1875  2138 D WfdsService: Receive the WFDS_ENABLE Method
07-05 12:50:48.225  1875  2138 D WfdsService: Set the WFDS Monitor: true
07-05 12:50:48.225  1875  2138 D WfdsService: Connected to the supplicant for wfds
07-05 12:50:48.225  1875  2138 D WfdsJNI : doCommand: WFDS_SET TRUE
07-05 12:50:48.225  1857  2574 E NxpNfcJni: getReconnectState = 0x0
07-05 12:50:48.227  1857  2224 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-05 12:50:48.227  1857  2224 D LCardEmulationManager: getDefaultRoute
07-05 12:50:48.227  1857  2224 D LNfcService: isRequireNfcCRouting() return true
07-05 12:50:48.228  1857  2224 D LNfcService: isHCERoutingtoHost() return : true
07-05 12:50:48.228  1857  2224 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-05 12:50:48.228  1857  2224 D NfcService: mEnableLPD: true
07-05 12:50:48.228  1857  2224 D NfcService: mEnableReader: false
07-05 12:50:48.228  1857  2224 D NfcService: mEnableHostRouting: true
,07-05 12:50:48.228  1857  2224 D NfcService: newParams.techmask= mTechMask: 0
07-05 12:50:48.228  1857  2224 D NfcService: mEnableLPD: true
07-05 12:50:48.228  1857  2224 D NfcService: mEnableReader: false
07-05 12:50:48.228  1857  2224 D NfcService: mEnableHostRouting: true
07-05 12:50:48.228  1857  2224 D NfcService: screenState= 1
07-05 12:50:48.231  2822  2822 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:50:48
07-05 12:50:48.231  2822  2822 D WeatherService: 2 : ACTION screen off
07-05 12:50:48.231  2822  2822 D WeatherService: 2 : TimeTick Receiver Unregister
07-05 12:50:48.232  2822  2822 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:50:48
,07-05 12:50:48.235  1875  1875 D WfdsService: isConnected: false
07-05 12:50:48.235  3935  3935 D AppCleanupService: android.intent.action.SCREEN_OFF
07-05 12:50:48.237   880  1308 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.237   880  1308 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.237   880  1308 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.238  3935  6064 D AppCleanupService: AppUsageStatsSaveTask
07-05 12:50:48.238   880  1308 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.238   880  1308 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.238   880  1308 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.238  1875  1875 D WfdsService: GroupInfoAvailable: mGroupInfo is null
07-05 12:50:48.243  6004  6004 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
,07-05 12:50:48.245  1875  2138 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
07-05 12:50:48.245  6004  6004 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
07-05 12:50:48.245  1875  2138 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
07-05 12:50:48.246  6004  6004 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
07-05 12:50:48.246  1875  2138 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
07-05 12:50:48.246  1875  2138 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
07-05 12:50:48.246  1875  2138 D WfdsService: selectPreferredScanChannel [6]
07-05 12:50:48.246  1875  2138 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
07-05 12:50:48.246  1875  2138 W WfdsService: DefaultState - msg [9441285] is not handled
07-05 12:50:48.249   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.249   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.250   880   880 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
07-05 12:50:48.253  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-05 12:50:48.253   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.253   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.253   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-05 12:50:48.254  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-05 12:50:48.254  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:48.254 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-05 12:50:48.254  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,07-05 12:50:48.257  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 12:50:48.257  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:48.257  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-05 12:50:48.257  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:48.258  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:48.258  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:48.290  1857  2574 E NxpNfcJni: getReconnectState = 0x0
,07-05 12:50:48.300   880   880 D LocSvc_java: onReceive
07-05 12:50:48.302  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-05 12:50:48.305  6004  6004 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-05 12:50:48.306  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-05 12:50:48.306   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.306   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.306   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-05 12:50:48.306  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:48.306 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-05 12:50:48.306  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-05 12:50:48.308  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 12:50:48.309  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:48.309  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-05 12:50:48.309   282  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-05 12:50:48.309  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:48.309   282  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-05 12:50:48.309   282  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-05 12:50:48.309  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:48.309  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:48.311  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-05 12:50:48.312   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.312   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.312   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-05 12:50:48.312  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-05 12:50:48.312  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:48.312 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-05 12:50:48.312  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-05 12:50:48.316  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 12:50:48.316  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:48.317  1372  1372 I [Sy,stemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-05 12:50:48.317  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:48.317  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:48.317  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:48.318  1789  1789 D GONS    : GONS isTestMode: false Country: 
07-05 12:50:48.320   880   880 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-05 12:50:48.320   880   880 D WifiServerServiceExt: setSupplicantStateSCANNING
07-05 12:50:48.334  6012  6012 D WiFiOffLoadUpdatePriority: remove1
07-05 12:50:48.334  6012  6012 V WiFiOffLoadSharedPrefsUtils: save remove
07-05 12:50:48.341  6004  6004 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-05 12:50:48.341  6004  6004 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-05 12:50:48.342   282  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-05 12:50:48.345  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-05 12:50:48.346   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.347   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.347   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-05 12:50:48.347  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-05 12:50:48.347  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:48.347 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-05 12:50:48.347  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-05 12:50:48.349  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 12:50:48.349  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:48.349  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-05 12:50:48.349  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:48.349  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:48.349  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:48.351  6012  6012 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
07-05 12:50:48.351  6012  6012 D WiFiOffLoadBroadcast: S: false, R: false
,07-05 12:50:48.352  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-05 12:50:48.352   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.352   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.352   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-05 12:50:48.353  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:48.352 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-05 12:50:48.353  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-05 12:50:48.354  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-05 12:50:48.355   880   880 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-05 12:50:48.355   880   880 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-05 12:50:48.356   880   880 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-05 12:50:48.356   880   880 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-05 12:50:48.358  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 12:50:48.358  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:48.358  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-05 12:50:48.358  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:48.358  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:48.358  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:48.373   880  1309 I WifiServiceExtension: setVHTCapabilityType  : false
,07-05 12:50:48.388   880  1309 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,07-05 12:50:48.389   880  1309 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
07-05 12:50:48.391   880  1309 I WifiServiceExtension: setSecurityType  : 2
07-05 12:50:48.403  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-05 12:50:48.403  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-05 12:50:48.403   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.403   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.404   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,07-05 12:50:48.406  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:48.405 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-05 12:50:48.406  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-05 12:50:48.408   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.408   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:48.408   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-05 12:50:48.409  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-05 12:50:48.410  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 12:50:48.410  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:48.41 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-05 12:50:48.410  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:48.410  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-05 12:50:48.410  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-05 12:50:48.410  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:48.410  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:48.410  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:48.411  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-05 12:50:48.415  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 12:50:48.415  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:48.415  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-05 12:50:48.415  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:48.415  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:48.415  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:48.423   880  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1,048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-05 12:50:48.426   880  1316 D ConnectivityService: Got NetworkAgent Messenger
07-05 12:50:48.426   880  6065 D WifiExtManager: WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@18c548e4
07-05 12:50:48.427   880  1309 D WifiExtManager: WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@12e82402
07-05 12:50:48.429   880  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-05 12:50:48.432   880  1316 D ConnectivityService: NetworkAgent connected
07-05 12:50:48.438  1875  1892 D WifiServiceExtension: isInternetCheckAvailable return false
07-05 12:50:48.439   880  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-05 12:50:48.450   880  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-05 12:50:48.460   282  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
07-05 12:50:48.461   880  1051 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:48.461   880  1051 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:48.461   880  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:48.461   880  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:48.462   282  1050 D CommandListener: Setting iface cfg
,07-05 12:50:48.468   880  1309 E WifiStateMachine: Start Dhcp Watchdog 1
07-05 12:50:48.469   880  6066 D DhcpStateMachine: StoppedState
07-05 12:50:48.469   880  6066 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.469   880  6066 D DhcpStateMachine: WaitBeforeStartState
07-05 12:50:48.472   880   880 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-05 12:50:48.472   880   880 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-05 12:50:48.474  6012  6012 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
07-05 12:50:48.474  6012  6012 D WiFiOffLoadUpdatePriority: connected SSID: null
,07-05 12:50:48.474  6012  6012 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
07-05 12:50:48.476   880   880 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-05 12:50:48.476   880   880 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-05 12:50:48.477   880  2583 D WifiServiceImplEx: addOrUpdateNetwork pid=6012, uid=1000, packageName=android.uid.system:1000
07-05 12:50:48.478   880  2583 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
07-05 12:50:48.480   880  1316 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-05 12:50:48.601   880  1309 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-05 12:50:48.601   880  1308 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31df7503 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.601   880  1309 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-05 12:50:48.601   880  1308 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31df7503 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.601   880  6066 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:48.602   880  6066 D DhcpStateMachine: DHCP Start wake lock is acquired.
,07-05 12:50:48.603   880  1309 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-05 12:50:48.603   880  1309 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
07-05 12:50:48.604   880   880 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-05 12:50:48.604   880   880 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-05 12:50:48.606   880   880 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-05 12:50:48.606   880   880 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-05 12:50:48.608   880  1309 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
07-05 12:50:48.658   880  1309 E WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
,07-05 12:50:48.668  6012  6012 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
07-05 12:50:48.669  6012  6012 D WiFiOffLoadUpdatePriority: configuration updated: 0
07-05 12:50:48.669   880  1309 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
,07-05 12:50:48.683  6012  6012 D WiFiOffLoadUpdatePriority: configuration saved: true
,07-05 12:50:48.685  6033  6033 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-05 12:50:48.739   880  1921 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6070 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-05 12:50:48.804   880  6066 D DhcpStateMachine: DHCPV4 request on wlan0
,07-05 12:50:48.807   880  6066 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-05 12:50:48.807   880  6066 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,07-05 12:50:48.826  6087  6087 I dhcpcd  : version 5.5.6 starting
07-05 12:50:48.829  6087  6087 E dhcpcd  : get_duid: Read-only file system
07-05 12:50:48.919  6087  6087 I dhcpcd  : wlan0: broadcasting for a lease
,07-05 12:50:48.947  6070  6070 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,07-05 12:50:48.947  6070  6070 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-05 12:50:48.956  6070  6070 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-05 12:50:48.958  6070  6070 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-05 12:50:48.963  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-05 12:50:48.970  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-05 12:50:48.975  6070  6095 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,07-05 12:50:48.979  6070  6095 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-05 12:50:48.984  6070  6094 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-05 12:50:48.992  6033  6033 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,07-05 12:50:48.995  6033  6033 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-05 12:50:48.995  6033  6033 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-05 12:50:49.041   880  1921 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6099 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-05 12:50:49.100   282  1043 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
07-05 12:50:49.101   880  1051 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:49.101   880  1051 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:49.131  6099  6099 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-05 12:50:49.216   880  1053 D BluetoothManagerService: Message: 20
07-05 12:50:49.216   880  1053 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1270817b:true
,07-05 12:50:49.227  2055  2070 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
07-05 12:50:49.228  2055  2071 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
,07-05 12:50:49.277  5644  5644 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-05 12:50:49.277  5644  5644 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-05 12:50:49.300  5644  5644 V [BNRBootReceiver]: Boot Receiver Return
07-05 12:50:49.304  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-05 12:50:49.308  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-05 12:50:49.320  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-05 12:50:49.323  6012  6012 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,07-05 12:50:49.325  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-05 12:50:49.329  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-05 12:50:49.339  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-05 12:50:49.344  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-05 12:50:49.355  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-05 12:50:49.359  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-05 12:50:49.368  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-05 12:50:49.373  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-05 12:50:49.382  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-05 12:50:49.387  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-05 12:50:49.397  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-05 12:50:49.402  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-05 12:50:49.513   880  1948 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6122 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:50:49.550  6099  6099 V LGMDMManager: Create singleton instance
,07-05 12:50:49.588  6122  6122 D UEI.SmartControl: Quickset Services start...
,07-05 12:50:49.593  6122  6122 I UEI.SmartControl: Manufacture = LGE
07-05 12:50:49.595  6122  6122 D UEI.SmartControl: File observer start...
07-05 12:50:49.596  6122  6122 E UEI.SmartControl: IR Port is disabled: false
07-05 12:50:49.596  6122  6122 D UEI.SmartControl: Starting file observer...
07-05 12:50:49.596  6122  6122 D UEI.SmartControl: Extracting JNI libs...
07-05 12:50:49.597  6122  6122 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-05 12:50:49.654  6099  6099 I AudioManager: getMode name:com.lge.qremote
,07-05 12:50:49.808  6122  6122 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-05 12:50:49.809  6122  6122 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-05 12:50:49.809  6122  6122 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-05 12:50:49.843  6122  6122 I UEI.SmartControl: --- Selecting new region: 2
07-05 12:50:49.844  6122  6122 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,07-05 12:50:49.849  6122  6122 D UEI.SmartControl: Platform has CIR...
07-05 12:50:49.851  6122  6122 D UEI.SmartControl: NO CIR support, need to check package...
07-05 12:50:49.851  6122  6122 I UEI.SmartControl: Model: LG-D722 uses JNI
07-05 12:50:49.854  6122  6122 D UEI.SmartControl: QS Service created
,07-05 12:50:49.878  6122  6122 E UEI.SmartControl: QS start get config
,07-05 12:50:49.935  6122  6122 D UEI.SmartControl: Loading JNI Libs...
,07-05 12:50:49.937  6122  6122 D UEI.SmartControl:  configuring local db...
07-05 12:50:49.973  6087  6087 I dhcpcd  : wlan0: offered 192.168.1.105 from 192.168.1.1
,07-05 12:50:50.150   282  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,07-05 12:50:50.152   880  1051 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:50.152   880  1051 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:50.153  6122  6122 D UEI.SmartControl:  ---- Has DB8: true
07-05 12:50:50.157   880  1316 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-05 12:50:50.160  6122  6122 D UEI.SmartControl: QS start statue = true Error code = 0
07-05 12:50:50.161  6122  6122 D UEI.SmartControl: QS version = v2.7.11.1_RC1
,07-05 12:50:50.162  6122  6122 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
07-05 12:50:50.167  6122  6122 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
07-05 12:50:50.206  6122  6122 W irrc_jni: IRRCPlayer_nativeInit ++ 
07-05 12:50:50.206  6122  6122 D irrcClient: IrrcClient ++ 
07-05 12:50:50.206  6122  6122 D irrcClient: getIrrcService ++ 
,07-05 12:50:50.209  6122  6122 D irrcClient: getIrrcService -- 
07-05 12:50:50.209  6122  6122 D irrcClient: IrrcClient -- 
07-05 12:50:50.209  6122  6122 W irrc_jni: IRRCPlayer_nativeInit -- 
07-05 12:50:50.218  6122  6122 D UEI.SmartControl: Services init done
07-05 12:50:50.223  6122  6148 I UEI.SmartControl: Device manager: loading config....
07-05 12:50:50.223  6122  6122 D UEI.SmartControl: QS Service init finished
,07-05 12:50:50.227  6122  6122 D UEI.SmartControl: QS Service version name: 0.1.73
07-05 12:50:50.228  6122  6122 D UEI.SmartControl: QS Service version code: 1073
,07-05 12:50:50.231  6122  6122 D UEI.SmartControl: Service requested: Control
07-05 12:50:50.232  6122  6148 D UEI.SmartControl: Config is loaded...
07-05 12:50:50.276  6122  6147 D UEI.SmartControl:  ----- QS SDK is ready!!!
07-05 12:50:50.277  6122  6147 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-05 12:50:50.280  6122  6122 D UEI.SmartControl: Request IControl service: devices are loaded...
07-05 12:50:50.283  6122  6122 D UEI.SmartControl: Internal service binding...
07-05 12:50:50.284  6122  6137 D UEI.SmartControl: -----IControl: 11
07-05 12:50:50.285  6122  6137 D UEI.SmartControl: Caller: com.lge.qremote
07-05 12:50:50.286  6122  6137 D UEI.SmartControl: ------------ IControl registerCallback...
07-05 12:50:50.287  6122  6137 I UEI.SmartControl: Registering callback...
07-05 12:50:50.288  6122  6138 D UEI.SmartControl: -----IControl: 19
07-05 12:50:50.289  6122  6138 D UEI.SmartControl: Caller: com.lge.qremote
07-05 12:50:50.290  6122  6138 I UEI.SmartControl: Registering Services Ready callback...
,07-05 12:50:50.292  6122  6138 I UEI.SmartControl: Notify client services are ready...
07-05 12:50:50.296  6122  6137 D UEI.SmartControl: -----IControl: 8
07-05 12:50:50.297  6122  6137 D UEI.SmartControl: Caller: com.lge.qremote
07-05 12:50:50.302  6099  6099 I AudioManager: getMode name:com.lge.qremote
,07-05 12:50:50.308   880  2028 I ActivityManager: Killing 5400:com.android.vending/u0a36 (adj 15): empty #11
07-05 12:50:50.410   880  2028 I ActivityManager: Killing 5661:com.android.providers.calendar/u0a14 (adj 15): empty #12
,07-05 12:50:50.561   880  1881 W libprocessgroup: failed to open /acct/uid_10036/pid_5400/cgroup.procs: No such file or directory
,07-05 12:50:50.564   880  1726 W libprocessgroup: failed to open /acct/uid_10014/pid_5661/cgroup.procs: No such file or directory
07-05 12:50:50.566  6099  6099 I AudioManager: getMode name:com.lge.qremote
07-05 12:50:50.591  6099  6099 I AudioManager: getMode name:com.lge.qremote
,07-05 12:50:52.095   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:50:52.171  1372  1372 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,07-05 12:50:52.173   880  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2c053bae type 2 when 158484 com.android.systemui} when 158484
,07-05 12:50:52.185  1789  1807 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-05 12:50:52.196  1789  1807 D PhoneUtils: getPhoneCount() sPhoneCount = 1
,07-05 12:50:52.196  1789  1807 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-05 12:50:52.201  1789  1807 V TelecomServiceImpl: getCallState : 0
07-05 12:50:52.202  1789  1806 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-05 12:50:52.202  1789  1806 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-05 12:50:52.202  1789  1806 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-05 12:50:52.204  1372  1372 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
07-05 12:50:52.204  1372  1372 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
07-05 12:50:52.205   880  1767 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:52.205   880  1767 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:52.205   880  1767 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:52.205   880  1767 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:52.206   282  1045 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 12:50:52.206   282  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-05 12:50:52.207   282  6155 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-05 12:50:52.207   282  6155 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:52.207   282  6155 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
,07-05 12:50:52.210   880  1051 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-05 12:50:53.822  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 12:50:53.822  5852  5959 I jxcore-log: 
,07-05 12:50:54.460  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 12:50:54.460  5852  5959 I jxcore-log: 
,07-05 12:50:54.497  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 12:50:54.497  5852  5959 I jxcore-log: 
,07-05 12:50:54.504  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 12:50:54.504  5852  5959 I jxcore-log: 
07-05 12:50:54.527  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 12:50:54.527  5852  5959 I jxcore-log: 
,07-05 12:50:54.534  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 12:50:54.534  5852  5959 I jxcore-log: 
07-05 12:50:54.884  6087  6087 I dhcpcd  : wlan0: acknowledged 192.168.1.105 from 192.168.1.1
,07-05 12:50:54.960  6087  6087 I dhcpcd  : wlan0: leased 192.168.1.105 for 172800 seconds
07-05 12:50:54.961   282  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,07-05 12:50:54.961   880  1051 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:54.961   880  1051 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:54.965   880  1316 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-05 12:50:55.213   880  6066 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:55.213   880  6066 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.214   880  6066 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:50:55.214   880  6066 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.214   880  6066 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:55.214   880  6066 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.214   880  6066 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:55.214   880  6066 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.214   880  6066 D DhcpStateMachine: DHCPV4 succeeded on wlan0
07-05 12:50:55.221   880  6066 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
07-05 12:50:55.221   880  6066 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-05 12:50:55.221   880  6066 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:55.222   880  6066 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.222   880  6066 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.105
07-05 12:50:55.222   880  6066 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-05 12:50:55.223   880  6066 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-05 12:50:55.223   880  6066 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
07-05 12:50:55.223   880  6066 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-05 12:50:55.223   880  6066 D DhcpStateMachine: RunningState
07-05 12:50:55.224   880  1308 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:55.224   880  1308 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:55.254   880  1316 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-05 12:50:55.255   880  1309 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-05 12:50:55.256   880  1316 D ConnectivityService: ignoring duplicate network state non-change
,07-05 12:50:55.260  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-05 12:50:55.265   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.265   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.265   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-05 12:50:55.266  1875  1891 D WifiServiceExtension: isInternetCheckAvailable return false
07-05 12:50:55.268  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-05 12:50:55.270  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-05 12:50:55.276  6122  6149 D UEI.SmartControl: Internal timer expired: 1
07-05 12:50:55.291   880  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-05 12:50:55.297   880  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-05 12:50:55.297   880  1316 D ConnectivityService: Adding iface wlan0 to network 100
07-05 12:50:55.299  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-127 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:55.299 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-05 12:50:55.299  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.105 ipV6Addr=
07-05 12:50:55.303  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,07-05 12:50:55.305   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.305   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.305   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-05 12:50:55.305  1875  1892 D WifiServiceExtension: isInternetCheckAvailable return false
07-05 12:50:55.307   880   880 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-05 12:50:55.309  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-05 12:50:55.309  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:55.309  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-05 12:50:55.310  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:55.310  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-127 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:55.308 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-05 12:50:55.311  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:55.311  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:55.312  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-05 12:50:55.312  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.105 ipV6Addr=
07-05 12:50:55.316  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,07-05 12:50:55.321   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.321   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.321   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-05 12:50:55.334  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-127 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:55.334 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-05 12:50:55.335  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.105 ipV6Addr=
,07-05 12:50:55.337  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,07-05 12:50:55.341  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:55.341  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-05 12:50:55.348   880   880 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-05 12:50:55.349   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.349   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.349   880   880 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,07-05 12:50:55.351  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-05 12:50:55.353  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-127 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-05 12:50:55.353 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-05 12:50:55.353  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.105 ipV6Addr=
07-05 12:50:55.356  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:55.357  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:55.357  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:55.361  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 0
07-05 12:50:55.363   880  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-05 12:50:55.364   880  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
07-05 12:50:55.365   282  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-05 12:50:55.365   282  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.365   282  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-05 12:50:55.365   282  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.366   880  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,07-05 12:50:55.366  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-05 12:50:55.367   282  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-05 12:50:55.367   282  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.374  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-05 12:50:55.374  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:55.374  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully_disconnected mWifiActivityIconId=(null)
07-05 12:50:55.377   282  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-05 12:50:55.377   282  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.379   880  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
07-05 12:50:55.379   282  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-05 12:50:55.379   282  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:50:55.382  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:55.383   880  1316 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-05 12:50:55.384   880  1316 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
07-05 12:50:55.384   880  1316 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
07-05 12:50:55.385   880  1316 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:55.385   880  1316 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.386  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:55.386  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:55.387   282  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
07-05 12:50:55.387   282  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.389  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 0
07-05 12:50:55.392  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,07-05 12:50:55.397  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:55.397  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully_disconnected mWifiActivityIconId=(null)
07-05 12:50:55.397  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-05 12:50:55.398  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-05 12:50:55.398  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
07-05 12:50:55.399   880  1316 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-05 12:50:55.399   880  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-05 12:50:55.400   880  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-05 12:50:55.401   880  1316 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-05 12:50:55.401   880  1316 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-05 12:50:55.401   880  1316 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-05 12:50:55.401   880  1316 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-05 12:50:55.401   880  1316 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:55.402   880  1316 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
07-05 12:50:55.402   880  1316 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:55.402   880  1316 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-05 12:50:55.402   880  1316 D ConnectivityService: currentScore = 0, newScore = 20
07-05 12:50:55.402   880  1316 D ConnectivityService:    accepting network in place of null
07-05 12:50:55.403   880  1316 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 12:50:55.404   880  1316 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
07-05 12:50:55.405   880  1309 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:55.405   880  1309 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-05 12:50:55.408  1789  1789 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:55.409  1789  1789 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
07-05 12:50:55.411   880  6065 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:55.411   880  6065 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-05 12:50:55.411   880  6065 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-05 12:50:55.420  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-05 12:50:55.427  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-05 12:50:55.430   880  1316 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-05 12:50:55.430   880  1316 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-05 12:50:55.431   880  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-05 12:50:55.434   880  1316 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-05 12:50:55.435   880  1316 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-05 12:50:55.435   880  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-05 12:50:55.437   880  1316 D ConnectivityService: validation of new default Network = false
07-05 12:50:55.439   880  1316 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-05 12:50:55.439  1911  1911 W QCNEJ   : |CORE| No family connected
07-05 12:50:55.439   880  1316 D DSQN    : enableDataServiceNotify 
07-05 12:50:55.439   880  1316 D DSQN    : start dsqn bin
07-05 12:50:55.440  1911  1911 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
07-05 12:50:55.440   880  6065 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
07-05 12:50:55.443  1911  1911 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
,07-05 12:50:55.445   880  6189 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
07-05 12:50:55.446   880  1053 D Tethering: MasterInitialState.processMessage what=3
07-05 12:50:55.447   880  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:55.447   880  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.447   880  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:55.448   880  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:55.448   282  1045 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 12:50:55.448   282  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-05 12:50:55.449   282  6190 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:50:55.449   282  6190 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:55.450   282  6190 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:50:55.450   282  6190 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:50:55.457  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-05 12:50:55.462   880  1316 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-05 12:50:55.462   880  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:55.464   880  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-05 12:50:55.468  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-05 12:50:55.471   880  1316 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-05 12:50:55.471   880  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:55.472   880  1316 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:55.474  1372  1727 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-05 12:50:55.478  5485  5812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-05 12:50:55.479  6191  6191 I DSQN    : DSQN samuel.seo ver 141203
07-05 12:50:55.480  6191  6191 E DSQN    : DSQN sock connect success to lgdatalistenerd
07-05 12:50:55.480  6191  6191 I DSQN    : created command queue thread
07-05 12:50:55.482  1372  1372 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,07-05 12:50:55.488  1372  1372 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
07-05 12:50:55.488  6033  6033 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-05 12:50:55.490  6191  6191 I DSQN    : Interface wlan0 address 192.168.1.105 0xc0a80169
07-05 12:50:55.490  6191  6191 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a80169
07-05 12:50:55.490  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-05 12:50:55.490  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:55.491  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully_disconnected mWifiActivityIconId=(null)
07-05 12:50:55.493  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-05 12:50:55.493  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:55.493  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully_disconnected mWifiActivityIconId=(null)
,07-05 12:50:55.497  6033  6033 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-05 12:50:55.507   282  6190 D libc-netbsd: res_queryN name = xxxxx succeed
,07-05 12:50:55.508   880  1307 I System.out: propertyValue:false
,07-05 12:50:55.509  6012  6012 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-05 12:50:55.516  6012  6012 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-05 12:50:55.523  6033  6033 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-05 12:50:55.523  6033  6033 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,07-05 12:50:55.546   880  1307 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-05 12:50:55.890  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-05 12:50:55.891  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:50:55.891  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:50:55.892  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:50:55.892  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:50:55.905   489   489 D charger_monitor: init target 500000
,07-05 12:50:55.914   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:50:55.945  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 309
07-05 12:50:55.945  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:50:55.945  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:50:55.945  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 309
,07-05 12:50:55.948   880  6189 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
07-05 12:50:55.948   880  6189 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:55.948   880  6189 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:55.949  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:50:55.949  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:50:55.949  5644  5644 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:50:55.950   880  6189 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
07-05 12:50:55.950   880  6189 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:55.951   282  1045 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 12:50:55.951   282  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-05 12:50:55.951  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:50:55.951   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.951  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:50:55.951   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.951  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:50:55.951  1875  2041 D LEDHandler: Battery Temp: 309, mChargingStatus=5, mChargingStop=false
07-05 12:50:55.952   282  6201 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
07-05 12:50:55.952   282  6201 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:55.952   880  1315 D WifiController: battery changed pluggedType: 2
07-05 12:50:55.952   282  6201 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:50:55.953   282  6201 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:50:55.979  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:50:55.979  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:50:55.979  1875  2041 D LEDHandler: Battery Temp: 309, mChargingStatus=5, mChargingStop=false
,07-05 12:50:55.979  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 309
07-05 12:50:55.979  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:50:55.980  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 309
07-05 12:50:55.980  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:50:55.980  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:50:55.980  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:50:55.982   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.982   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:50:55.982   880  1315 D WifiController: battery changed pluggedType: 2
07-05 12:50:55.983  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:50:55.984  5644  5644 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:50:55.998   282  6201 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:50:55.998   880  6189 I System.out: propertyValue:false
,07-05 12:50:55.998   880  6189 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
07-05 12:50:56.003   880  6065 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-05 12:50:56.020   880  6065 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:56.020   880  6065 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:50:56.049  6191  6193 I DSQN    : first global connection report this to start monitoring at DSQM.
07-05 12:50:56.049  6191  6193 I DSQN    : restart monitoring
,07-05 12:50:56.051  6191  6204 I DSQN    : dsqn report finish
07-05 12:50:56.051   282  1049 D LGDataListener: argv[0]=dsqncommand
07-05 12:50:56.051   282  1049 D LGDataListener: argv[1]=wlan0
07-05 12:50:56.051   282  1049 D LGDataListener: argv[2]=1
07-05 12:50:56.051   282  1049 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-05 12:50:56.053   880  1051 D DSQN    : DSQM DsqnNotification wlan0  1
07-05 12:50:56.053   880  1051 D DSQN    : start to monitor internet connection
07-05 12:50:56.081   880  6065 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jul 2016 10:50:55 GMT], X-Android-Received-Millis=[1467715856080], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467715856053]}
,07-05 12:50:56.082   880  6065 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-05 12:50:56.084  1875  1891 D WifiServiceExtension: isInternetCheckAvailable return false
07-05 12:50:56.084   880  6065 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
07-05 12:50:56.084   880  6065 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-05 12:50:56.089   880  1316 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
07-05 12:50:56.089   880  1316 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-05 12:50:56.089   880  1316 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-05 12:50:56.089   880  1316 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-05 12:50:56.089   880  1316 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-05 12:50:56.089   880  1316 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:56.089   880  1316 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
07-05 12:50:56.090   880  1316 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
07-05 12:50:56.090   880  1316 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-05 12:50:56.090   880  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:56.090   880  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-05 12:50:56.090   880  1316 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-05 12:50:56.091   880   880 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
07-05 12:50:56.093   880  1309 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
07-05 12:50:56.093  1372  1727 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-05 12:50:56.095   880  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:56.096   880  1316 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 12:50:56.097  5485  5812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-05 12:50:56.098   880  1316 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:56.098   880  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-05 12:50:56.099   880  1309 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:56.099   880  1309 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-05 12:50:56.099  1789  1789 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 12:50:56.100  1789  1789 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
07-05 12:50:56.114  1372  1372 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-05 12:50:56.115  1372  1372 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,07-05 12:50:56.118  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-05 12:50:56.118  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:56.118  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully_disconnected mWifiActivityIconId=(null)
07-05 12:50:56.121  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-05 12:50:56.121  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-05 12:50:56.121  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_1_fully mWifiActivityIconId=(null)
07-05 12:50:57.100   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 12:50:58.081  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 12:50:58.081  5852  5959 I jxcore-log: 
,07-05 12:50:58.099  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 12:50:58.099  5852  5959 I jxcore-log: 
,07-05 12:50:58.112  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 12:50:58.112  5852  5959 I jxcore-log: 
,07-05 12:50:58.309   880  1311 V WifiInternetCheck: Single check msg out of sync, ignoring.
,07-05 12:50:58.356  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 12:50:58.356  5852  5959 I jxcore-log: 
,07-05 12:50:58.436   880  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-05 12:50:58.450  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
,07-05 12:50:58.455   880   880 D LocSvc_java: onReceive
07-05 12:50:58.456   880   880 D LocSvc_java: got connectivity action
07-05 12:50:58.468  2055  2070 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
07-05 12:50:58.468   880  1767 D AlarmManagerService: Setting time of day to sec=1467715858
,07-05 12:50:58.469  5852  5852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 12:50:58.469  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:50:58.469  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:50:58.469  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:50:58.469  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:50:58.469  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 12:50:58.469  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:50:58.469  5852  5852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 12:50:58.176   880  1767 W AlarmManagerService: Unable to set rtc to 1467715858: Invalid argument
07-05 12:50:58.176   880   880 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
07-05 12:50:58.176   880   880 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-05 12:50:58.177  2055  2070 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
07-05 12:50:58.178  5852  5852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-05 12:50:58.185   880   880 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-05 12:50:58.191   880   880 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-05 12:50:58.191   880   880 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-05 12:50:58.191   880   880 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
,07-05 12:50:58.200   880  6205 D LocSvc_java: NTP server returned: 1467715855254 (Tue Jul 05 12:50:55 GMT+02:00 2016) reference: 161850 certainty: 9 system time offset: -2945
07-05 12:50:58.218   880  1021 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6206 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:50:58.223   880  6205 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
07-05 12:50:58.248  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 12:50:58.248  5852  5959 I jxcore-log: 
,07-05 12:50:58.256  2822  2822 D WeatherService: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:50:58
07-05 12:50:58.256  2822  2822 D WeatherService: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:50:58
07-05 12:50:58.258  1372  1372 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
07-05 12:50:58.259  1372  1372 I LgeClockWidgetControlView: time changed, timezoneChanged : false
07-05 12:50:58.259  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:50:58.294   880  1021 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=6233 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-05 12:50:58.296   880  1062 W ActivityManager: getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
07-05 12:50:58.311  1949  1949 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=5 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
,07-05 12:50:58.324  1949  1949 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 5
,07-05 12:50:58.370  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 12:50:58.370  5852  5959 I jxcore-log: 
07-05 12:50:58.370  2020  2020 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-05 12:50:58.385  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 12:50:58.385  5852  5959 I jxcore-log: 
07-05 12:50:58.386  1949  1949 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 5
,07-05 12:50:58.411  1949  1949 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,07-05 12:50:58.457  6233  6233 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:50:58.457  6233  6233 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-05 12:50:58.458  6233  6233 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-05 12:50:58.477   880  1019 I ActivityManager: Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6250 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-05 12:50:58.512   880  1019 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-05 12:50:58.593  6250  6250 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 12:50:58.606  6250  6250 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-05 12:50:58.606  6250  6250 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-05 12:50:58.683  2372  2372 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 12:50:58.740  6233  6233 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-05 12:50:58.762   286  1304 V AudioFlinger: 2075 died, releasing its sessions
07-05 12:50:58.762   286  1304 V AudioFlinger:  pid 1789 @ 0
07-05 12:50:58.762   286  1304 V AudioFlinger:  pid 3096 @ 1
07-05 12:50:58.762   286  1304 V AudioFlinger:  pid 3096 @ 2
,07-05 12:50:58.781  6233  6233 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,07-05 12:50:58.825   880   967 I ActivityManager: Process com.lge.music (pid 2075) has died
,07-05 12:50:58.841  6250  6250 I AppConfig: Total System Memory = 906309632
,07-05 12:50:58.844  6250  6250 I GalleryUtils: Application Heap = 96 MB
,07-05 12:50:58.847  6250  6250 I AppConfig: App Tier : NOT_DEF
07-05 12:50:58.859  6250  6250 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,07-05 12:50:58.871   880  1019 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 12:50:58.884  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 12:50:58.884  5852  5959 I jxcore-log: 
,07-05 12:50:58.947  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 12:50:58.947  5852  5959 I jxcore-log: 
,07-05 12:50:58.953   880  1019 E GpsLocationProvider: No APN found to select.
07-05 12:50:58.956  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 12:50:58.956  5852  5959 I jxcore-log: 
,07-05 12:50:58.972  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 12:50:58.972  5852  5959 I jxcore-log: 
07-05 12:50:58.976  5485  6285 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-05 12:50:58.994   880  6288 D LgeGpsConstants: Can't find 'ext_gps.conf'!!
07-05 12:50:58.994   880  6288 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:58.994   880  6288 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:58.995   880  6288 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:58.995   880  6288 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:58.995   282  1045 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 12:50:58.995   282  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
,07-05 12:50:59.001   282  6290 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:50:59.001   282  6290 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:59.002   282  6290 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:50:59.002   282  6290 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:50:59.010  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 12:50:59.010  5852  5959 I jxcore-log: 
,07-05 12:50:59.050  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 12:50:59.050  5852  5959 I jxcore-log: 
,07-05 12:50:59.060   282  6290 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:50:59.062   880  6288 I System.out: propertyValue:false
,07-05 12:50:59.072   880  1019 I NotificationManager: android: cancelAsUser(-1597574061) by android
,07-05 12:50:59.107   880  1019 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 36160, reason: UserStart, SyncResult: databaseError: true stats []
,07-05 12:50:59.111  2372  2372 D WearableService: callingUid 10006, callindPid: 2372
07-05 12:50:59.115   880  1019 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 198040, reason: UserStart
07-05 12:50:59.123   880  1019 I NotificationManager: android: cancelAsUser(716319171) by android
,07-05 12:50:59.134   880  6288 D LgeGpsLocationProvider: NTP server: europe.pool.ntp.org
07-05 12:50:59.134   880  6288 D LgeGpsLocationProvider: NTP server returned: 1467715859145 (Tue Jul 05 12:50:59 GMT+02:00 2016) reference: 165742 certainty: 35 system time offset: 11
07-05 12:50:59.139  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:50:59.140  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:50:59.203  6206  6206 I MusicStore: Database version: 120
,07-05 12:50:59.222   880  2028 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6298 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-05 12:50:59.246  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 12:50:59.246  5852  5959 I jxcore-log: 
,07-05 12:50:59.254  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 12:50:59.254  5852  5959 I jxcore-log: 
07-05 12:50:59.261   880  1311 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:59.261   880  1311 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:59.262   880  1311 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:59.262   880  1311 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:59.262   282  1045 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 12:50:59.262   282  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-05 12:50:59.262   282  6310 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:50:59.262   282  6310 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:59.263   282  6310 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:50:59.263   282  6310 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:50:59.274   880  1019 I NotificationManager: android: cancelAsUser(-1816247584) by android
,07-05 12:50:59.299   282  6310 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:50:59.303   880  1311 I System.out: propertyValue:false
,07-05 12:50:59.307   880  1312 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:59.307   880  1312 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:59.307   880  1312 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:59.308   880  1312 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:59.317   282  1045 E BandwidthController: [LG DATA] No such appUid: 1000
07-05 12:50:59.317   282  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-05 12:50:59.317   282  6320 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:50:59.317   282  6320 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:59.318   282  6320 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:50:59.318   282  6320 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:50:59.318   282  6320 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:50:59.318   880  1312 I System.out: propertyValue:false
,07-05 12:50:59.321  5852  5959 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 12:50:59.321  5852  5959 I jxcore-log: 
,07-05 12:50:59.339  2055  2071 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
07-05 12:50:59.340  2372  6321 I CheckinUtil: Classify the device as Phone.
07-05 12:50:59.343  5485  6284 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
07-05 12:50:59.346  5852  5959 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
07-05 12:50:59.350  5852  5959 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-05 12:50:59.350  5852  5959 I jxcore-log: 
,07-05 12:50:59.420   880  1019 I NotificationManager: android: cancelAsUser(353845882) by android
,07-05 12:50:59.429   880  1312 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
07-05 12:50:59.438   880  1019 I NotificationManager: android: cancelAsUser(-591465577) by android
,07-05 12:50:59.459   880  1019 I NotificationManager: android: cancelAsUser(-1597574061) by android
,07-05 12:50:59.497  5852  5959 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-05 12:50:59.497  5852  5959 I jxcore-log: 
07-05 12:50:59.498  5852  5959 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 12:50:59.498  5852  5959 I jxcore-log: 
,07-05 12:50:59.600   880  1948 I art     : Explicit concurrent mark sweep GC freed 100758(4MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 23MB/35MB, paused 1.995ms total 256.125ms
,07-05 12:50:59.605   880  1359 I ActivityManager: Process com.google.android.talk (pid 5714) has died
07-05 12:50:59.618  6298  6326 D ALBootInit: ====action==>android.intent.action.TIME_SET
,07-05 12:50:59.623  6298  6326 D ALBootInit: Alarm ALBootInit: TIME_SET
07-05 12:50:59.627  6298  6326 D Alarms  : [setNextAlert] start
07-05 12:50:59.627   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:50:59.627   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-05 12:50:59.627   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:50:59.628  6206  6206 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-05 12:50:59.645  6298  6326 D Alarms  : [setNextAlert] (1)
,07-05 12:50:59.648  6298  6326 D Alarms  :  minTime  = 0
07-05 12:50:59.650  6298  6326 D Alarms  :  -- OK multi -- 0
07-05 12:50:59.651  2372  6321 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:59.651  6298  6326 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
07-05 12:50:59.651  2372  6321 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:59.651  6298  6326 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
07-05 12:50:59.652  2372  6321 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:59.652  2372  6321 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:59.653   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:50:59.653   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:50:59.653   282  6330 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:50:59.654   282  6330 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:59.655   282  6330 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:50:59.655   282  6330 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:50:59.681  2372  6272 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:59.681  2372  6272 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:59.682  2372  6272 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:50:59.683  2372  6272 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:59.683   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:50:59.683   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:50:59.683   282  6331 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:50:59.684   282  6331 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:50:59.684   282  6331 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:50:59.684   282  6331 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:50:59.689  6298  6326 I CommonUtil: BUILD Operator: OPEN
07-05 12:50:59.691  6298  6326 D Alarms  : broadcastToWidgetProvider : false
07-05 12:50:59.695   880  1019 I NotificationManager: android: cancelAsUser(353845882) by android
,07-05 12:50:59.696  6298  6326 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
,07-05 12:50:59.752   880  1019 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6334 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-05 12:50:59.766   880  2583 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,07-05 12:50:59.772  6298  6298 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
07-05 12:50:59.774  6298  6298 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@12be4717
07-05 12:50:59.779  6298  6298 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@12be4717
,07-05 12:50:59.784  6298  6298 D QuickCoverProvider: onReceiver
,07-05 12:50:59.793   282  6330 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:50:59.793  2372  6321 I System.out: propertyValue:false
07-05 12:50:59.795   282  6331 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:50:59.795  2372  6272 I System.out: propertyValue:false
,07-05 12:50:59.814  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:50:59.815  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 12:50:59.818  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
07-05 12:50:59.819  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:50:59.819  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:50:59.820  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:50:59.820  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:50:59.832   880   968 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6351 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:50:59.861   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:50:59.861   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-05 12:50:59.861   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:50:59.862  6206  6206 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-05 12:50:59.867   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:50:59.867   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-05 12:50:59.867   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:50:59.869  6206  6206 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,07-05 12:50:59.879  2372  6321 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:59.879  2372  6321 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:50:59.902  2372  6272 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:50:59.902  2372  6272 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:50:59.914  6334  6334 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 12:50:59.928  6351  6351 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 12:50:59.949  6206  6206 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:50:59.949  6206  6206 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 12:50:59.954   880  1019 I NotificationManager: android: cancelAsUser(-591465577) by android
,07-05 12:51:00.017  6351  6351 D CalendarApplication: CalendarApplication.onCreate()
,07-05 12:51:00.027  6206  6206 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
07-05 12:51:00.038  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:51:00.038  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:51:00.038  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:51:00.039  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:51:00.039  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:51:00.040  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:51:00.041  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:51:00.047  6351  6351 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
07-05 12:51:00.049  6351  6351 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@166e70ca, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@399fc23b, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2ad5dd58, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@30903eb1, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@e6acf96, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@12be4717, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@7777704, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@253914ed, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@19fc4f22, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@6d63db3, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1b76ff70, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@341f12e9, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@32343b6e, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2f6d020f, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@ea4a29c, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@64cf4a5, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3deca07a, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@f01b02b, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@13a74c88, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@10bd3621, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@5944a46, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@6e92407, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1ea8a934, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@396135d, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@17bac4d2, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@ee9f9a3, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1ac124a0, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@31258859, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2a5c5c1e, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@a988cff, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@a23eacc, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@289d5115, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@4ee1c2a, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1872fa1b, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3d0ae7b8, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@8ee991, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3f29d0f6, lg_preferences_widget_info_calendars=com.android.calendar.ada,ptation.PreferenceKey$KeyData@36bd1cf7, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@b62c764, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@d278dcd, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@209a0682, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1a1c9193, lg_pr
07-05 12:51:00.058  6351  6351 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
07-05 12:51:00.087  6351  6351 D Config  : [init]
07-05 12:51:00.088  6351  6351 I Config  : LGCalendar ver.4.40.17
07-05 12:51:00.088  6351  6351 I Config  : start check model
07-05 12:51:00.088  6351  6351 I Config  : start check native_ca
07-05 12:51:00.089  6351  6351 I Config  : Config Operator=OPEN, Country=EU
07-05 12:51:00.090  6351  6351 D Config  : [setDefaultValuesToPref]
07-05 12:51:00.090  6351  6351 D Config  : [parseProfiles]
07-05 12:51:00.094  6351  6351 D ProfilesParser: [debug_displayParseInfos] profile.country = null
07-05 12:51:00.094  6351  6351 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
07-05 12:51:00.094  6351  6351 D Config  : [updateProfiletoCountryInfo]
,07-05 12:51:00.097  6351  6351 D GeneralPreference: [checkAndMigrateOldPreference]
07-05 12:51:00.135   880  1881 I ActivityManager: Process com.lge.bnr (pid 5644) has died
,07-05 12:51:00.156  6206  6206 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-05 12:51:00.159  6206  6206 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8bce51d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 12:51:00.160  6206  6206 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 12:51:00.160  6206  6206 D AndroidMusic: GMSCore installation verified
07-05 12:51:00.162  6351  6351 E AgendaWidgetManager: [updateWidgets] 
07-05 12:51:00.168  6351  6375 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
,07-05 12:51:00.172  6206  6206 I ConfigStore: Config Database version: 1
07-05 12:51:00.185  6351  6375 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,07-05 12:51:00.226  6351  6375 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
07-05 12:51:00.232  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
07-05 12:51:00.236  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
07-05 12:51:00.240  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,07-05 12:51:00.245  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
07-05 12:51:00.253  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
07-05 12:51:00.257  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,07-05 12:51:00.263  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
07-05 12:51:00.267  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
07-05 12:51:00.271  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,07-05 12:51:00.277  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
07-05 12:51:00.281  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
07-05 12:51:00.292  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,07-05 12:51:00.297  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
07-05 12:51:00.301  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
07-05 12:51:00.306  6351  6375 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
07-05 12:51:00.306  6351  6375 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,07-05 12:51:00.310  6351  6375 I AlertUtils: set default noti to content://media/internal/audio/media/38
07-05 12:51:00.317  6351  6375 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
07-05 12:51:00.368  5485  6281 D ChimeraConfigService: Fetched value, gms:chimera:dogfoods = null
07-05 12:51:00.369  5485  6281 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
07-05 12:51:00.369  5485  6281 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
,07-05 12:51:00.386   880  1863 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:00.425  2372  6272 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-05 12:51:00.446  6206  6206 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-05 12:51:00.452  2372  6272 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:00.452  2372  6272 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:00.452  2372  6272 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:00.452  2372  6272 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:00.453   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:00.453   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:00.453   282  6384 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:00.453   282  6384 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:00.453   282  6384 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:00.454   282  6384 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:00.454  6206  6206 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
07-05 12:51:00.475  6206  6206 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 12:51:00.520   880  1863 I ActivityManager: Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6385 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:00.567   880  1019 I NotificationManager: android: cancelAsUser(-1548111331) by android
,07-05 12:51:00.639   880  1019 I ActivityManager: Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6408 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:00.672   309   309 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 833us total 33.094ms
,07-05 12:51:00.679  6351  6351 D MonthWidgetProvider: [onReceive]
07-05 12:51:00.679  6351  6351 D CalendarWidgetProvider: [onReceive]
07-05 12:51:00.680  6351  6351 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
07-05 12:51:00.681  6351  6417 W HolidayIntentService: onHandleIntent
07-05 12:51:00.683  6351  6351 D CalendarTypeController: [onUpdateAndInitCalendarTime]
07-05 12:51:00.683  6351  6417 D HolidayDataLoader: readJsonAsset : holiday.json
,07-05 12:51:00.696  6206  6206 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
07-05 12:51:00.696   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 24.209ms
,07-05 12:51:00.698  6351  6351 D WeekWidgetProvider: [onReceive]
07-05 12:51:00.698  6351  6351 D CalendarWidgetProvider: [onReceive]
07-05 12:51:00.698  6351  6351 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,07-05 12:51:00.700  6351  6351 D CalendarTypeController: [onUpdateAndInitCalendarTime]
07-05 12:51:00.708  6206  6230 I art     : CheckpointMarkThreadRoots callback created = 0xaaf1c310
07-05 12:51:00.713  2822  2822 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:51:0
,07-05 12:51:00.721   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 23.656ms
07-05 12:51:00.723  2822  2822 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-05 12:51:00.726  2822  2822 D Weather_cast: 2 : set auto-update time : 7/5 15:51
,07-05 12:51:00.734  2822  2822 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:51:0
07-05 12:51:00.734  2822  2822 D WeatherService: 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
07-05 12:51:00.736  2822  2822 D WeatherService: 2 : shouldTimeTickRegistered : false
07-05 12:51:00.769   282  6384 D libc-netbsd: res_queryN name = xxxxx succeed
,07-05 12:51:00.772  2372  6272 I System.out: propertyValue:false
07-05 12:51:00.781  6206  6230 I art     : CheckpointMarkThreadRoots callback created = 0xaaf1c2f0
,07-05 12:51:00.798   880  2134 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6427 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-05 12:51:00.821  6351  6417 E HolidayIntentService: onHandleIntent:holiday data empty
,07-05 12:51:00.847  6385  6426 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-05 12:51:00.847  6385  6426 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 12:51:00.856  6206  6230 W art     : Suspending all threads took: 35.762ms
,07-05 12:51:00.906  6233  6233 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-05 12:51:00.948  6427  6427 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1467715860948
07-05 12:51:00.948  6427  6427 D         : TimeServiceNative: User Time to be set is 1467715860948
07-05 12:51:00.948  6427  6427 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-05 12:51:00.948  6427  6427 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-05 12:51:00.948  6427  6427 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1467715860948
07-05 12:51:00.948  6427  6427 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,07-05 12:51:00.950   348  1068 D QC-time-services: Daemon: Connection accepted:time_genoff
07-05 12:51:00.952   348  6447 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1467715860948
07-05 12:51:00.953   348  6447 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1467715860948, operation = 0
07-05 12:51:00.953   348  6447 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/16/70 14:51:45
07-05 12:51:00.953   348  6447 D QC-time-services: Daemon:Value read from RTC seconds = 27615105000
07-05 12:51:00.953   348  6447 D QC-time-services: Daemon:new time 1467715860948 
07-05 12:51:00.953   348  6447 D QC-time-services: Daemon: delta 1440100755948 genoff 1440100755948 
07-05 12:51:00.953   348  6447 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100755948 to memory
07-05 12:51:00.953   348  6447 D QC-time-services: Daemon:Opening File: /data/time/ats_2
07-05 12:51:00.953   348  6447 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
07-05 12:51:00.960  6385  6426 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
07-05 12:51:00.962   348  6447 D QC-time-services: Updating the TOD offset
07-05 12:51:00.962   348  6447 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100755948 to memory
07-05 12:51:00.962   348  6447 D QC-time-services: Daemon:Opening File: /data/time/ats_1
07-05 12:51:00.962   348  6447 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-05 12:51:00.970   348  6447 E QC-time-services: Daemon:Update to modem bit set
07-05 12:51:00.970   348  6447 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-05 12:51:00.970   348  6447 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124135955948
07-05 12:51:00.971  6427  6427 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
07-05 12:51:00.974   348  1066 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
07-05 12:51:00.974   348  1068 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-05 12:51:00.975   880   968 I ActivityManager: Process com.android.settings (pid 6012) has died
,07-05 12:51:01.006  6206  6206 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-05 12:51:01.090  6385  6426 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 12:51:01.091  6385  6426 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 12:51:01.117   880  2134 I ActivityManager: Process com.lge.lgdmsclient (pid 6070) has died
,07-05 12:51:01.122  6206  6206 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 12:51:01.170   880  2192 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6452 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-05 12:51:01.275   880  1936 I ActivityManager: Process com.lge.qremote (pid 6099) has died
,07-05 12:51:01.282  6233  6233 I HubEmail: JNI_OnLoad()
07-05 12:51:01.282  6233  6233 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-05 12:51:01.283  6233  6233 I HubEmail: registerNatives()
07-05 12:51:01.283  6233  6233 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-05 12:51:01.283  6233  6233 I HubEmail: registerNativeMethods()
07-05 12:51:01.283  6233  6233 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-05 12:51:01.284  6233  6233 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-05 12:51:01.289  6122  6122 D UEI.SmartControl: Service.onUnbind: IControl
07-05 12:51:01.289  6122  6122 D UEI.SmartControl: Service.onDestroy
,07-05 12:51:01.310  6122  6122 D UEI.SmartControl: Shutdown IRRCPlayer... 
,07-05 12:51:01.314   880   968 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
07-05 12:51:01.353   880  1359 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:01.356  6122  6122 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
07-05 12:51:01.356  6122  6122 D irrcClient: ~IrrcClient ++ 
07-05 12:51:01.356  6122  6122 D irrcClient: ~IrrcClient -- 
07-05 12:51:01.356  6122  6122 W irrc_jni: IRRCPlayer_nativeFinalize -- 
07-05 12:51:01.356  6122  6122 D UEI.SmartControl: Blaster closed
07-05 12:51:01.356  6122  6122 D UEI.SmartControl: Blaster closed
07-05 12:51:01.356  6122  6122 D UEI.SmartControl: Shut down QS...
07-05 12:51:01.356  6122  6122 D UEI.SmartControl: Stopped file observer...
07-05 12:51:01.359  1789  1789 I PhoneApp: onTrimMemory: 10
07-05 12:51:01.361  1789  1789 I PhoneApp: trim memory
07-05 12:51:01.371  6122  6122 I UEI.SmartControl: QS lib stop result = true
,07-05 12:51:01.374  6122  6122 D UEI.SmartControl: QS shutdown complete
07-05 12:51:01.379  6233  6473 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:51:01.384  6452  6452 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-05 12:51:01.384  6452  6452 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-05 12:51:01.394  6452  6452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-05 12:51:01.397  6452  6452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-05 12:51:01.409  2372  2407 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-05 12:51:01.432  6206  6297 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,07-05 12:51:01.455   880  1062 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6483 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-05 12:51:01.463  6452  6480 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-05 12:51:01.463  6452  6482 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-05 12:51:01.471  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 12:51:01.472  6452  6482 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-05 12:51:01.492  6452  6480 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,07-05 12:51:01.529  6408  6504 I Gmail   : getAccountsCursor
,07-05 12:51:01.537  6452  6480 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,07-05 12:51:01.576  6385  6402 W art     : Suspending all threads took: 13.264ms
,07-05 12:51:01.602  6385  6402 I art     : CheckpointMarkThreadRoots callback created = 0xb042db60
,07-05 12:51:01.635   880  1948 I ActivityManager: Process com.android.gallery3d (pid 6250) has died
,07-05 12:51:01.643  6385  6402 I art     : CheckpointMarkThreadRoots callback created = 0xb042db40
,07-05 12:51:01.644  6334  6348 I art     : CheckpointMarkThreadRoots callback created = 0xb042d570
07-05 12:51:01.660  6385  6477 D ChimeraCfgMgr: Reading stored module config
,07-05 12:51:01.663  6334  6401 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:51:01.682  1789  1789 I art     : Explicit concurrent mark sweep GC freed 28494(1560KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/18MB, paused 7.790ms total 293.152ms
,07-05 12:51:01.701  6334  6348 I art     : CheckpointMarkThreadRoots callback created = 0xb042d550
,07-05 12:51:01.723  6334  6348 W art     : Suspending all threads took: 8.605ms
,07-05 12:51:01.756   880  1910 I art     : Explicit concurrent mark sweep GC freed 20457(995KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 8.962ms total 223.579ms
,07-05 12:51:01.770   880  1948 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-05 12:51:01.772  6452  6452 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
07-05 12:51:01.773  6452  6452 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
07-05 12:51:01.773  6452  6452 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
07-05 12:51:01.778  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:01.779  6452  6452 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
07-05 12:51:01.799  6452  6452 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,07-05 12:51:01.809   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
07-05 12:51:01.821  6408  6408 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 12:51:01.830   880  1921 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
07-05 12:51:01.831  6408  6509 I Gmail   : Observing account changes for notifications
07-05 12:51:01.841  6334  6515 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:01.841  6334  6515 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,07-05 12:51:01.842   282  1045 E BandwidthController: [LG DATA] No such appUid: 10086
07-05 12:51:01.842   282  1045 D DnsProxyListener: App 10086 tries DNS query. Accept family:2 protocol:0
07-05 12:51:01.842   282  6520 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:01.842   282  6520 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
07-05 12:51:01.842   282  6520 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:01.843   282  6520 D libc-netbsd: res_queryN name = xxxxx succeed
,07-05 12:51:01.892  5421  5441 I art     : Explicit concurrent mark sweep GC freed 2260(89KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 2.711ms total 108.527ms
,07-05 12:51:01.897  6385  6385 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-05 12:51:01.900   880   968 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6524 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
07-05 12:51:01.901  6483  6483 I AppUp4:AppBoxCP: onCreate
07-05 12:51:01.902  6483  6483 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-05 12:51:01.910  6385  6385 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:01.910  6385  6385 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:01.915   880  1948 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
07-05 12:51:01.923  6483  6483 I AppUp4:DB:  setFingerPrint start
07-05 12:51:01.923  6483  6483 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,07-05 12:51:01.939  6408  6547 E Gmail   : Error finding the version of the Email provider.....
07-05 12:51:01.939  6408  6547 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-05 12:51:01.939  6408  6547 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-05 12:51:01.939  6408  6547 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
07-05 12:51:01.939  6408  6547 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-05 12:51:01.939  6408  6547 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-05 12:51:01.939  6408  6547 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:51:01.939  6408  6547 E Gmail   : 	at android.os.Looper.loop(Looper.java:135)
07-05 12:51:01.939  6408  6547 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:51:01.939  6408  6547 W EmailMigration: We do not support migrating this version of the Email provider.
,07-05 12:51:01.945  6408  6549 I Gmail   : getAccountsCursor
07-05 12:51:01.945  6408  6546 W Gmail   : Sync started for account: account:61035162
,07-05 12:51:01.957  6483  6483 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
07-05 12:51:01.957  6483  6483 I AppUp4:DB:  SDK version = 21
07-05 12:51:01.958  6483  6483 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-05 12:51:01.960  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:01.968  6483  6483 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,07-05 12:51:01.982  6483  6483 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-05 12:51:01.982  6483  6483 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,07-05 12:51:01.986   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:01.986  6483  6483 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-05 12:51:01.986   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
07-05 12:51:01.986   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:01.989  6483  6483 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-05 12:51:01.996  6385  6385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,07-05 12:51:01.999  6483  6483 I AppUp4:CustModeStarterReceiver: onReceive
07-05 12:51:01.999  6483  6483 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
07-05 12:51:02.013  6483  6483 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@e6acf96
07-05 12:51:02.013  6483  6483 D AppUp4:CustFacade: isCustomizationCompleted : false
,07-05 12:51:02.027  6483  6483 D AppUp4:CustFacade: isSimDevice : true
,07-05 12:51:02.029  6483  6483 D AppUp4:CustModeStarterReceiver: begin check event
07-05 12:51:02.029  6483  6483 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-05 12:51:02.032  6483  6483 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-05 12:51:02.043  6483  6553 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-05 12:51:02.043  6483  6553 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
,07-05 12:51:02.043  6483  6553 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-05 12:51:02.062  6385  6477 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,07-05 12:51:02.064  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:02.082  6385  6477 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000003@DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk': Failed to open oat filename for reading: No such file or directory
,07-05 12:51:02.085  6385  6477 D ChimeraFileApk: Classloading successful. Optimized code found.
07-05 12:51:02.183  3096  3096 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-05 12:51:02.183  3096  3096 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,07-05 12:51:02.187  3096  3096 I LgeMiscReceiver: networkInfo.isConnected() = true
07-05 12:51:02.196  6385  6477 D DynamitePackage: Instantiated singleton DynamitePackage.
,07-05 12:51:02.200  6385  6477 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
07-05 12:51:02.203  3096  3096 D PhoneState: setPdpRejectCasuse : false
07-05 12:51:02.260   880  1726 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6567 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,07-05 12:51:02.292  6524  6524 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
,07-05 12:51:02.304  6524  6524 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
07-05 12:51:02.313  1331  1331 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
,07-05 12:51:02.323  6524  6524 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
07-05 12:51:02.325  6524  6524 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
,07-05 12:51:02.326  6524  6524 V [BNRBootReceiver]: Boot Receiver Return
07-05 12:51:02.326  6524  6524 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:51:02.334  1372  1372 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
07-05 12:51:02.334  1372  1372 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
07-05 12:51:02.337  1372  1372 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
,07-05 12:51:02.395   880  1863 I ActivityManager: Process com.google.android.music:main (pid 6206) has died
,07-05 12:51:02.412  6408  6561 I Gmail   : notifyAccountChanged
,07-05 12:51:02.422  6408  6561 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 12:51:02.427  6408  6589 I Gmail   : getAccountsCursor
,07-05 12:51:02.431  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:02.438  2372  6272 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
07-05 12:51:02.449  6408  6546 I Gmail   : notifyAccountChanged
,07-05 12:51:02.461  6408  6561 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 12:51:02.478  2372  6272 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,07-05 12:51:02.514  6408  6561 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 12:51:02.521  6408  6561 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
07-05 12:51:02.526   880  2170 I ActivityManager: Process com.lge.clock (pid 6298) has died
,07-05 12:51:02.577  6385  6385 I NotificationManager: com.google.android.youtube: cancel(2) by com.google.android.youtube
,07-05 12:51:02.588  6567  6567 D PhoneMonitor: Register our PhoneStateListener
,07-05 12:51:02.633  6567  6567 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-05 12:51:02.633  6408  6505 I Gmail   : getAccountsCursor
,07-05 12:51:02.634  6567  6567 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-05 12:51:02.649   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:02.649   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
07-05 12:51:02.649   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:02.650  6385  6385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,07-05 12:51:02.659   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:02.659   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
07-05 12:51:02.659   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:02.661  6385  6385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
07-05 12:51:02.662   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:02.662   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
07-05 12:51:02.662   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:02.663  6385  6385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
07-05 12:51:02.671  6567  6567 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,07-05 12:51:02.680  6567  6567 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-05 12:51:02.686  6385  6385 W InstanceID/Rpc: Found 10006
,07-05 12:51:02.690  6567  6567 D TelephonyAutoProfiling: [parse] Load xml
,07-05 12:51:02.703  3117  3117 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,07-05 12:51:02.709  5485  6602 I CheckinService: Disabling old GoogleServicesFramework version
07-05 12:51:02.720  6567  6567 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,07-05 12:51:02.723  6567  6567 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
07-05 12:51:02.739  3117  3117 V DownloadManager: DownloadService onCreate
,07-05 12:51:02.751  6567  6567 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-05 12:51:02.760  3117  6603 I DownloadManager: in removeSpuriousFiles
,07-05 12:51:02.768  6385  6402 W art     : Suspending all threads took: 30.099ms
07-05 12:51:02.774   880  2170 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6606 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-05 12:51:02.775  3117  3117 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
,07-05 12:51:02.778  3117  6603 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,07-05 12:51:02.803  2372  2408 I art     : Explicit concurrent mark sweep GC freed 73617(4MB) AllocSpace objects, 54(887KB) LOS objects, 39% free, 14MB/24MB, paused 1.730ms total 163.216ms
,07-05 12:51:02.815  3117  6603 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@209a0682 on behalf of 3117
07-05 12:51:02.818  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:02.822   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:02.822   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
07-05 12:51:02.822   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:02.823  6385  6385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
07-05 12:51:02.829  2372  2402 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a8eb56c)
07-05 12:51:02.830  3117  6603 I DownloadManager: in trimDatabase
07-05 12:51:02.831  3117  6603 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,07-05 12:51:02.833  3117  6603 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1a1c9193 on behalf of 3117
07-05 12:51:02.843  3117  3117 V DownloadManager: DownloadService onStartCommand
,07-05 12:51:02.846  3117  6604 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
07-05 12:51:02.849  3117  6604 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2ce608ce on behalf of 3117
,07-05 12:51:02.972  3117  3117 V DownloadManager: DownloadService onDestroy
,07-05 12:51:02.985  6606  6606 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
07-05 12:51:02.986  6606  6606 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,07-05 12:51:02.997  2822  2822 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:51:2
07-05 12:51:03.003  2822  2822 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-05 12:51:03.003  6606  6606 V DrmService: Service onCreate
,07-05 12:51:03.012  6408  6546 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 24538, normalSync: true
07-05 12:51:03.015  6606  6606 D DrmService: Received new request = 2
,07-05 12:51:03.022  2822  2822 D WeatherAncestor: connectivity changed - connection : true
07-05 12:51:03.022  2822  2822 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-05 12:51:03.022  2822  2822 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:51:3
07-05 12:51:03.026  2822  2822 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
07-05 12:51:03.027  2822  2822 D WeatherService: 2 : shouldTimeTickRegistered : false
,07-05 12:51:03.036  6606  6662 I DrmSntpClient: Start Sync process
07-05 12:51:03.036  6606  6662 D DrmSntpClient: Server : 0
07-05 12:51:03.040  6606  6662 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:03.040  6606  6662 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:03.041  6606  6662 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:03.041  6606  6662 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:03.041   282  1045 E BandwidthController: [LG DATA] No such appUid: 10051
,07-05 12:51:03.041   282  1045 D DnsProxyListener: App 10051 tries DNS query. Accept family:0 protocol:0
07-05 12:51:03.041   282  6663 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:03.041   282  6663 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:03.042   282  6663 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:03.042   282  6663 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:03.078  6385  6635 I NotificationManager: com.google.android.youtube: cancel(10436) by com.google.android.youtube
,07-05 12:51:03.095  6385  6659 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:03.095  6385  6659 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:03.099  6385  6659 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:03.100  6385  6659 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:03.101   282  1045 E BandwidthController: [LG DATA] No such appUid: 10100
07-05 12:51:03.101   282  1045 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
07-05 12:51:03.102   282  6666 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:03.102   282  6666 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:03.102   282  6666 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:03.102   282  6666 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:03.127   282  6663 D libc-netbsd: res_queryN name = xxxxx succeed
,07-05 12:51:03.130  6606  6662 I System.out: propertyValue:false
07-05 12:51:03.146  5485  6669 I iu.SyncManager: SYNC; picasa accounts
,07-05 12:51:03.155   880   968 I ActivityManager: Process com.android.calendar (pid 6351) has died
07-05 12:51:03.183   282  6666 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:03.184  6385  6659 I System.out: propertyValue:false
,07-05 12:51:03.184  6385  6659 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:03.184  6385  6659 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:03.196  6606  6662 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
,07-05 12:51:03.204   294   294 V ILGDrmService: eDRM_SetDRMTime +++
07-05 12:51:03.206  5485  5485 D NetworkLogImpl: Loaded NetworkSpeedPredictor
07-05 12:51:03.216  2372  6671 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:03.216  2372  6671 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:03.217  5485  5485 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-05 12:51:03.219  5485  6605 I art     : Explicit concurrent mark sweep GC freed 16299(1289KB) AllocSpace objects, 30(480KB) LOS objects, 24% free, 15MB/20MB, paused 19.690ms total 348.288ms
07-05 12:51:03.224   294   294 I LGDRM   : [DRM] SET TIME : YR=2016, MON=7, DAY=5
07-05 12:51:03.224   294   294 I LGDRM   : [DRM] SET TIME : HR=10, MIN=51, SEC=3
07-05 12:51:03.234  2372  6671 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:03.234  2372  6671 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:03.234   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:03.234   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:03.235   282  6672 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:03.235   282  6672 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:03.235   282  6672 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:03.237   282  6672 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:03.249   294   294 V ILGDrmService: eDRM_SetDRMTime ---
,07-05 12:51:03.250  6606  6662 I DrmSntpClient: Synched
07-05 12:51:03.252  6606  6606 D DrmService: Completed !! request = 2
07-05 12:51:03.252  6606  6606 D DrmService: Request count = 0
07-05 12:51:03.253  6606  6606 V DrmService: Service onDestroy
07-05 12:51:03.256  6334  6334 I NotificationManager: com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
07-05 12:51:03.261  6408  6546 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:03.262  6408  6546 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 12:51:03.273  5485  6605 I CheckinChimeraService: Checking schedule, now: 1467715863271 next: 1467367653317
07-05 12:51:03.273  5485  6605 I CheckinChimeraService: active receiver: enabled
,07-05 12:51:03.287  5485  6669 I iu.UploadsManager: num queued entries: 0
07-05 12:51:03.288  5485  6669 I iu.UploadsManager: num updated entries: 0
07-05 12:51:03.289  5485  6669 I iu.SyncManager: NEXT; no task
,07-05 12:51:03.345  5485  6605 I CheckinChimeraService: Preparing to send checkin request
07-05 12:51:03.346  5485  6605 I EventLogChimeraService: Accumulating logs since 1467715141365
07-05 12:51:03.362   282  6672 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:03.362  2372  6671 I System.out: propertyValue:false
,07-05 12:51:03.415   880  1910 I ActivityManager: Process com.uei.lg.quicksetsdk.lite (pid 6122) has died
,07-05 12:51:03.445  2372  6671 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:03.445  2372  6671 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:03.466  6408  6546 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 12:51:03.469   880   968 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6676 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
07-05 12:51:03.542  6408  6546 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-05 12:51:03.542  6408  6423 I art     : CheckpointMarkThreadRoots callback created = 0xaaf6e170
07-05 12:51:03.544  6408  6546 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 12:51:03.571  6408  6423 I art     : CheckpointMarkThreadRoots callback created = 0xb042de10
,07-05 12:51:03.585   880   968 I ActivityManager: Process com.lge.sync (pid 6033) has died
,07-05 12:51:03.603   880  1019 I NotificationManager: android: cancelAsUser(2145784878) by android
,07-05 12:51:03.661   880  1019 I ActivityManager: Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6694 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,07-05 12:51:03.705  6676  6676 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-05 12:51:03.715   880  1936 I ActivityManager: Process com.lge.email (pid 6233) has died
,07-05 12:51:03.738  2372  6671 I GCM     : GCM config loaded
,07-05 12:51:03.825   880  1910 I ActivityManager: Process com.qualcomm.timeservice (pid 6427) has died
,07-05 12:51:03.862  6385  6647 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:03.862  6385  6647 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:03.867  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:03.867  6385  6647 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:03.867  6385  6647 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:03.868   282  1045 E BandwidthController: [LG DATA] No such appUid: 10100
07-05 12:51:03.868   282  1045 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
07-05 12:51:03.868   282  6717 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:03.868   282  6717 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:03.868   282  6717 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:03.870   282  6717 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:03.870   282  6717 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:03.876  6385  6647 I System.out: propertyValue:false
07-05 12:51:03.876  6385  6647 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:03.876  6385  6647 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:03.888   880  1921 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:04.060  6385  6647 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:04.060  6385  6647 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:04.130   880  1726 I art     : Explicit concurrent mark sweep GC freed 24385(1147KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.105ms total 173.618ms
,07-05 12:51:04.146   880  1062 I ActivityManager: Process com.lge.bnr (pid 6524) has died
,07-05 12:51:04.156  1789  1789 I PhoneApp: onTrimMemory: 10
,07-05 12:51:04.156  1789  1789 I PhoneApp: trim memory
07-05 12:51:04.163  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 12:51:04.241  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:04.256  5485  6722 V AccountUtils: 0 accounts found with uca feature
,07-05 12:51:04.276  5485  6722 I GamesSyncAdapter: Starting sync for 3a3529a
,07-05 12:51:04.302  6408  6546 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:04.302  6408  6546 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:04.303  6408  6546 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:04.303  6408  6546 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:04.303   282  1045 E BandwidthController: [LG DATA] No such appUid: 10053
07-05 12:51:04.303   282  1045 D DnsProxyListener: App 10053 tries DNS query. Accept family:0 protocol:0
07-05 12:51:04.303   282  6727 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:04.303   282  6727 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:04.304   282  6727 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:04.304   282  6727 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,07-05 12:51:04.314  6676  6728 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-05 12:51:04.314  6676  6728 I Babel_SMS: MmsConfig.loadMmsSettings
07-05 12:51:04.319  6676  6728 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-05 12:51:04.319  6676  6728 I Babel_SMS: MmsConfig.loadFromDatabase
,07-05 12:51:04.363  6676  6728 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-05 12:51:04.363  6676  6728 I Babel_SMS: MmsConfig.loadFromResources
07-05 12:51:04.366  6676  6728 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-05 12:51:04.366  6676  6728 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,07-05 12:51:04.383   282  6727 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:04.383  6408  6546 I System.out: propertyValue:false
07-05 12:51:04.384  6408  6546 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:04.384  6408  6546 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:04.494  6694  6694 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
07-05 12:51:04.494  6694  6694 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 12:51:04.494  6694  6694 I GAv4    :   adb logcat -s GAv4
,07-05 12:51:04.503  6676  6676 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
,07-05 12:51:04.503  6676  6676 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
07-05 12:51:04.503  6676  6676 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
07-05 12:51:04.504  6676  6676 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
07-05 12:51:04.504  6676  6676 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
07-05 12:51:04.504  6676  6676 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
07-05 12:51:04.504  6676  6676 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
07-05 12:51:04.522  6694  6694 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 12:51:04.536  6676  6676 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
07-05 12:51:04.536  6676  6676 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
07-05 12:51:04.536  6676  6676 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
07-05 12:51:04.536  6676  6676 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
07-05 12:51:04.536  6676  6676 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
07-05 12:51:04.536  6676  6676 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
07-05 12:51:04.536  6676  6676 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
07-05 12:51:04.536  6676  6676 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
07-05 12:51:04.538  6676  6676 D SensorManager: found sensor: Motion Accel, handle=46
,07-05 12:51:04.568  6694  6694 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 12:51:04.576  6694  6738 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-05 12:51:04.599  6694  6694 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,07-05 12:51:04.617  6676  6691 I art     : CheckpointMarkThreadRoots callback created = 0xb042d880
,07-05 12:51:04.625   880  2192 I ActivityManager: Process com.lge.appbox.client (pid 6483) has died
07-05 12:51:04.632  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:04.633  1789  1789 I PhoneApp: onTrimMemory: 10
07-05 12:51:04.633  1789  1789 I PhoneApp: trim memory
07-05 12:51:04.670  5485  6605 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,07-05 12:51:04.675  6676  6691 I art     : CheckpointMarkThreadRoots callback created = 0xb042d870
07-05 12:51:04.691  6676  6676 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:51:04.695  6676  6676 I Babel_Crash: startup - clean
07-05 12:51:04.720  5485  6605 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-05 12:51:04.721  6676  6741 I Babel   : deleted: false for 0
,07-05 12:51:04.849   880  1921 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6746 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 12:51:04.923  6694  6694 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:04.923  6694  6694 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 12:51:04.923  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:04.925   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:04.925   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
07-05 12:51:04.925   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:04.930  6694  6753 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:04.931  6694  6753 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 12:51:04.931  6694  6752 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
07-05 12:51:04.945  6676  6676 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,07-05 12:51:04.956  6676  6676 W AudioCapabilities: Unsupported mime audio/adpcm
07-05 12:51:04.957  6676  6676 W AudioCapabilities: Unsupported mime audio/g726
07-05 12:51:04.958  6676  6676 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-05 12:51:04.959  6676  6676 W AudioCapabilities: Unsupported mime audio/wma-voice
07-05 12:51:04.963  6676  6676 W VideoCapabilities: Unsupported mime video/mjpg
07-05 12:51:04.969   880  1359 I ActivityManager: Start proc com.google.android.play.games.ui for service com.google.android.play.games/com.google.android.gms.games.service.PlayGamesBridgeService: pid=6767 uid=10085 gids={50085, 9997} abi=armeabi-v7a
07-05 12:51:04.989  6694  6709 I art     : CheckpointMarkThreadRoots callback created = 0xb050ea70
,07-05 12:51:05.000  6676  6676 W VideoCapabilities: Unsupported mime video/theora
,07-05 12:51:05.013   880  2134 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:05.031  6694  6694 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 12:51:05.040  6694  6709 I art     : CheckpointMarkThreadRoots callback created = 0xb050ea50
,07-05 12:51:05.069  5485  5554 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:05.069  5485  5554 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:05.069  5485  5554 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:05.069  5485  5554 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:05.069   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:05.069   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,07-05 12:51:05.070   282  6786 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:05.070   282  6786 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:05.070   282  6786 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:05.070   282  6786 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:05.070   282  6786 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:05.073  5485  5554 I System.out: propertyValue:false
07-05 12:51:05.167  6694  6694 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-05 12:51:05.170  6694  6694 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 12:51:05.178  5421  6682 I art     : Explicit concurrent mark sweep GC freed 2760(109KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 404us total 113.222ms
07-05 12:51:05.212  6676  6676 W AudioCapabilities: Unsupported mime audio/evrc
07-05 12:51:05.214  6676  6676 W AudioCapabilities: Unsupported mime audio/qcelp
,07-05 12:51:05.225  6676  6676 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 12:51:05.269  6676  6676 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-05 12:51:05.277  6676  6676 W AudioCapabilities: Unsupported mime audio/qcelp
,07-05 12:51:05.279  6676  6676 W AudioCapabilities: Unsupported mime audio/evrc
07-05 12:51:05.290   880  2583 D WifiServiceImplEx: acquireWifiLock pid=6694, uid=10058, packageName=com.google.android.apps.docs, tag=BaseSyncManager
,07-05 12:51:05.319  6676  6676 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-05 12:51:05.337  6676  6676 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-05 12:51:05.347  6676  6676 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 12:51:05.349  6676  6676 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 12:51:05.352  6676  6676 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 12:51:05.360  6676  6676 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 12:51:05.365   880  2028 I ActivityManager: Process com.lge.lgdmsclient (pid 6452) has died
07-05 12:51:05.372  1789  1789 I PhoneApp: onTrimMemory: 15
07-05 12:51:05.372  1789  1789 I PhoneApp: trim memory
07-05 12:51:05.381  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:05.405  6676  6676 I vclib   : onServiceConnected
,07-05 12:51:05.411  5485  6722 I GamesSyncAdapter: Sync duration for 3a3529a: 1154
07-05 12:51:05.412  6676  6676 W Babel   : Attempted to change video mute state without an active call.
07-05 12:51:05.428  6676  6797 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:05.429  6676  6797 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:05.429  6676  6797 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:05.429  6676  6797 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:05.431   282  1045 E BandwidthController: [LG DATA] No such appUid: 10061
07-05 12:51:05.432   282  1045 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
07-05 12:51:05.432  6676  6676 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
07-05 12:51:05.432   282  6801 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:05.432   282  6801 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:05.433   282  6801 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:05.433   282  6801 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:05.433   282  6801 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:05.434  6676  6797 I System.out: propertyValue:false
,07-05 12:51:05.446  6694  6792 I NotificationManager: com.google.android.apps.docs: cancel(1) by com.google.android.apps.docs
,07-05 12:51:05.474  6767  6788 I NotificationManager: com.google.android.play.games: cancel(10436) by com.google.android.play.games
,07-05 12:51:05.497  6694  6792 W Flag    : Duration spec must be at least 2 characters long
,07-05 12:51:05.542  5485  6722 E PopupManager: No content view usable to display popups. Popups will not be displayed in response to this client's calls. Use setViewForPopups() to set your content view.
,07-05 12:51:05.582  6694  6792 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:05.582  6694  6792 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:05.584  6694  6792 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:05.584  6694  6792 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:05.584   282  1045 E BandwidthController: [LG DATA] No such appUid: 10058
07-05 12:51:05.584   282  1045 D DnsProxyListener: App 10058 tries DNS query. Accept family:0 protocol:0
07-05 12:51:05.586   282  6813 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:05.586   282  6813 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:05.587   282  6813 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:05.587   282  6813 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:05.590   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:05.590   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-05 12:51:05.590   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:05.591  6746  6812 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-05 12:51:05.602  5485  6811 W GamesServiceBroker: Client connected with SDK 8487000, Services 9256236, and Games 37230036
,07-05 12:51:05.606   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:05.606   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-05 12:51:05.606   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:05.606  6746  6812 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-05 12:51:05.626   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,07-05 12:51:05.626   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-05 12:51:05.626   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:05.630  6746  6746 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-05 12:51:05.630  6746  6746 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 12:51:05.630  6746  6746 I GAv4    :   adb logcat -s GAv4
07-05 12:51:05.635  6746  6814 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-05 12:51:05.639   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:05.639   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,07-05 12:51:05.640   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:05.640  6746  6814 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-05 12:51:05.675  6746  6746 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 12:51:05.685   282  6813 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:05.686  6676  6797 I Babel   : connection state changed from UNKNOWN to CONNECTED
07-05 12:51:05.688  6694  6792 I System.out: propertyValue:false
,07-05 12:51:05.697   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:51:05.697   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:51:05.697   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 172311863221; DSPS: 5744648; Offset : -3007073418
07-05 12:51:05.706  2372  2596 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:05.707  2372  2596 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:05.715  2372  2596 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:05.715  2372  2596 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:05.715   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:05.715   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:05.715   282  6817 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:05.715   282  6817 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:05.716   282  6817 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:05.716   282  6817 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:05.716   282  6817 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:05.717  2372  2596 I System.out: propertyValue:false
07-05 12:51:05.744  6746  6746 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 12:51:05.744  2372  6819 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-05 12:51:05.754  6746  6820 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-05 12:51:05.788  5485  6807 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
,07-05 12:51:05.890  2372  6819 I GLSUser : Method not found getActionBar
,07-05 12:51:05.902  2372  2596 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:05.902  2372  2596 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:05.960  2372  6819 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:05.960  2372  6819 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:05.971  6694  6792 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:05.971  6694  6792 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:05.975  5485  5485 D PlayCommon: [1] DfeRequest.deliverResponse: Not delivering second response for request=[[ ] https://android.clients.google.com/fdfe/api/experiments 0xe8d195d1 NORMAL 1]
,07-05 12:51:06.085  2372  2408 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:06.085  2372  2408 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:06.127  6408  6408 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
,07-05 12:51:06.201  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:06.228  2372  2408 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:06.228  2372  2408 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:06.232  2372  2688 W Herrevad: Invalid mccmnc 
07-05 12:51:06.237  2372  2688 W Herrevad: Invalid mccmnc 
07-05 12:51:06.269   880   967 I ActivityManager: Process com.google.android.setupwizard (pid 6567) has died
,07-05 12:51:06.270   243   243 E lowmemorykiller: Error writing /proc/6606/oom_score_adj; errno=22
,07-05 12:51:06.279  6408  6546 I Gmail   : checkLabelsSets changed the label sets to: included([^^out, ^r]), partial([^f]), all([^b, userlabel:93982, userlabel:90242001, userlabel:2914615, userlabel:90242029, userlabel:2914456, ^iim, ^k, ^p_aunsub, userlabel:3025, ^sq_ig_i_promo, userlabel:-1492276993, ^smartlabel_notification, userlabel:-1508083783, userlabel:382548592, ^imn, userlabel:90241997, userlabel:1680828287, ^all, userlabel:94101, ^imi, userlabel:-1492383895, ^f, userlabel:94076, userlabel:823616170, userlabel:-1492276994, userlabel:-1492276990, userlabel:3026, userlabel:-1492276991, ^u, ^t, ^smartlabel_group, ^s, ^smartlabel_personal, userlabel:-812318908, ^smartlabel_social, userlabel:2914593, ^p_mtunsub, ^sq_ig_i_personal, ^g, ^r, ^punsub, ^smartlabel_promo, userlabel:-1497452393, ^i, ^io_im, userlabel:2896756, userlabel:614875005, userlabel:-1492276992, ^p_bs, userlabel:-1711782184, userlabel:2907326, userlabel:93692, userlabel:-244132349, ^sq_ig_i_social, userlabel:90241971, userlabel:3011, userlabel:1123230114, ^p_abs])
07-05 12:51:06.281  1789  1789 I PhoneApp: onTrimMemory: 10
07-05 12:51:06.281  1789  1789 I PhoneApp: trim memory
07-05 12:51:06.283  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 12:51:06.288  6746  6746 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-05 12:51:06.304  6694  6792 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
07-05 12:51:06.304  6694  6792 E DefaultHttpIssuer: java.io.IOException
07-05 12:51:06.304  6694  6792 E DefaultHttpIssuer: 	at cjw.b(PG:159)
07-05 12:51:06.304  6694  6792 E DefaultHttpIssuer: 	at cju.b(PG:5072)
07-05 12:51:06.304  6694  6792 E DefaultHttpIssuer: 	at dlq.a(PG:18080)
07-05 12:51:06.304  6694  6792 E DefaultHttpIssuer: 	at dlt.run(PG:9611)
07-05 12:51:06.304  6694  6792 E DefaultHttpIssuer: 	at dlr.run(PG:3031)
07-05 12:51:06.305   880  2192 I ActivityManager: Process com.lge.drmservice (pid 6606) has died
,07-05 12:51:06.310  6694  6792 E BaseSyncManager: ClientFlagSyncException
07-05 12:51:06.310  6694  6792 E BaseSyncManager: ccd$a: IO Exception opening: https://ssl.gstatic.com/docs/android/drive/client_flags?1467715865497= Socket is closed
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at ccd.a(PG:1108)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at dlq.a(PG:18060)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at dlt.run(PG:9611)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at dlr.run(PG:3031)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: Caused by: java.net.SocketException: Socket is closed
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.checkOpen(:com.google.android.gms:251)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.access$000(:com.google.android.gms:58)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at rus.write(:com.google.android.gms:765)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at iat.a_(PG:78)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at iae.a_(PG:155)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at iaw.flush(PG:221)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at hyh$d.b(PG:381)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at hyt.a(PG:279)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at hya.a(PG:10245)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at hxn$a.a(PG:890)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at hvz.a(PG:50089)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at hvz$a.a(PG:230)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at hvz.a(PG:3201)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at clz.a(PG:127)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at cjr.a(PG:47)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at cjq.a(PG:22)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at cjs.a(PG:68)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at cjw.b(PG:92)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at cjw.a(PG:80)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at cju.b(PG:5140)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at cju.a(PG:1096)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	at ccd.a(PG:2062)
07-05 12:51:06.310  6694  6792 E BaseSyncManager: 	... 3 more
,07-05 12:51:06.345   880  1359 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:06.366  2372  2596 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-05 12:51:06.385  6746  6746 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2995-3000)
07-05 12:51:06.385  6746  6746 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 12:51:06.403  6746  6746 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b7fa1fb}
,07-05 12:51:06.406  6746  6746 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:51:06.410  6746  6746 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 12:51:06.435  6746  6746 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 12:51:06.437  6746  6746 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:51:06.441  6746  6746 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 12:51:06.509  6746  6746 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-05 12:51:06.522  6746  6746 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-05 12:51:06.522  6746  6746 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 12:51:06.523  6746  6746 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:51:06.523  6746  6746 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:51:06.523  6746  6746 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 12:51:06.523  6746  6746 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 12:51:06.523  6746  6746 I Adreno-EGL: Remote Branch: 
07-05 12:51:06.523  6746  6746 I Adreno-EGL: Local Patches: 
07-05 12:51:06.523  6746  6746 I Adreno-EGL: Reconstruct Branch: 
07-05 12:51:06.551   880  2134 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6854 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,07-05 12:51:06.585   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 315us total 32.857ms
,07-05 12:51:06.612   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 350us total 27.048ms
,07-05 12:51:06.640   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 337us total 26.933ms
,07-05 12:51:06.648  6854  6854 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:06.648  6854  6854 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 12:51:06.672  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:06.713   286  1354 V AudioPolicyService: registerClient() client 0xb4027280, uid 10079
07-05 12:51:06.716  6746  6879 W AudioManagerAndroid: Requires BLUETOOTH permission
07-05 12:51:06.729  6854  6854 I MultiDex: VM with version 2.1.0 has multidex support
07-05 12:51:06.729  6854  6854 I MultiDex: install
07-05 12:51:06.729  6854  6854 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 12:51:06.738  6746  6746 I NSApplication: Starting up...
07-05 12:51:06.814   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 12:51:06.817   880  1062 I art     : Explicit concurrent mark sweep GC freed 23476(1135KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 9.320ms total 171.131ms
07-05 12:51:06.819  6854  6854 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
07-05 12:51:06.857   880  2192 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6887 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:06.892  6408  6511 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
07-05 12:51:06.892  6854  6854 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-05 12:51:06.893  6854  6854 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1682a00b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-05 12:51:06.894  6854  6854 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 12:51:06.907   880  1948 I NotificationManager: android: cancelAsUser(2) by android
07-05 12:51:06.909  6854  6854 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
07-05 12:51:06.910  6854  6854 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
,07-05 12:51:06.923   880  1726 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:06.943  2372  2407 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
07-05 12:51:06.954   880  1062 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:06.967  2372  2408 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
07-05 12:51:06.967  5485  5485 I GAv4-SVC: Google Analytics 9.2.56 is starting up.
,07-05 12:51:06.976  6854  6854 D ChimeraCfgMgr: Reading stored module config
07-05 12:51:07.024  5485  6837 W InstanceID/Rpc: Found 10006
,07-05 12:51:07.121  6694  6792 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:07.121  6694  6792 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:07.122  6694  6792 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:07.122  6694  6792 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 12:51:07.122   282  1045 E BandwidthController: [LG DATA] No such appUid: 10058
07-05 12:51:07.122   282  1045 D DnsProxyListener: App 10058 tries DNS query. Accept family:0 protocol:0
07-05 12:51:07.122   282  6912 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:07.122   282  6912 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:07.123   282  6912 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:07.123   282  6912 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:07.145   880  1726 I ActivityManager: Process com.google.android.talk (pid 6676) has died
,07-05 12:51:07.210   282  6912 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:07.211  6694  6792 I System.out: propertyValue:false
,07-05 12:51:07.263  2372  2688 V NQFileLogger: [186] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
,07-05 12:51:07.266  6854  6907 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 12:51:07.284  6854  6854 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,07-05 12:51:07.285  6854  6854 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
07-05 12:51:07.295  2372  2688 V ProcessReports: [186] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,07-05 12:51:07.331  6408  6546 I art     : Explicit concurrent mark sweep GC freed 33833(1076KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 11MB/14MB, paused 605us total 68.776ms
,07-05 12:51:07.338  6408  6546 I Gmail   : getStartSyncRequest: handledServerOpId: 24708, upperFetchedConvoId: 1533541443347415040, lowerFetchedConvoId: 0, ackedClientOp: 0
07-05 12:51:07.346  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:07.358   880  1948 I NotificationManager: android: cancelAsUser(2) by android
07-05 12:51:07.407   286  1304 D WVCdm   : Instantiating CDM.
,07-05 12:51:07.408   286   286 I WVCdm   : CdmEngine::OpenSession
07-05 12:51:07.408   286   286 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
07-05 12:51:07.417  6854  6868 I art     : CheckpointMarkThreadRoots callback created = 0xb042d370
07-05 12:51:07.424  6694  6792 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:07.424  6694  6792 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:07.448  6854  6868 I art     : CheckpointMarkThreadRoots callback created = 0xb042d360
,07-05 12:51:07.474   286   286 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-05 12:51:07.475   286   286 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
,07-05 12:51:07.475   286   286 W WVCdm   : L1 library not specified. Falling Back to L3
07-05 12:51:07.485   880  1948 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6921 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
07-05 12:51:07.487   243   243 E lowmemorykiller: Error writing /proc/6385/oom_score_adj; errno=22
,07-05 12:51:07.544   286   286 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 12:51:07.548   286  1615 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 12:51:07.548   286  1615 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-05 12:51:07.548   286  1615 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 12:51:07.553   286  1615 D WVCdm   : PrepareKeyRequest: nonce=3731007902
07-05 12:51:07.595   880  1936 I ActivityManager: Process com.google.android.youtube (pid 6385) has died
,07-05 12:51:07.601  1789  1789 I PhoneApp: onTrimMemory: 10
07-05 12:51:07.601  1789  1789 I PhoneApp: trim memory
07-05 12:51:07.603  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:07.632  6854  6870 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:07.632  6854  6870 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:07.633  6854  6870 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:07.633  6854  6870 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:07.635   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:07.635   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:07.635   282  6941 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:07.635   282  6941 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:07.636   282  6941 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:07.636   282  6941 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:07.636   282  6941 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:07.636  6854  6870 I System.out: propertyValue:false
07-05 12:51:07.703  6921  6921 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,07-05 12:51:07.711  2822  2822 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:51:7
07-05 12:51:07.713  2822  2822 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-05 12:51:07.713  2822  2822 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
07-05 12:51:07.714  2822  2822 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:51:7
07-05 12:51:07.715  2822  2822 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,07-05 12:51:07.717  2822  2822 D WeatherService: 2 : shouldTimeTickRegistered : false
,07-05 12:51:07.781   880  2192 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.phenotype.service.PhenotypeCommitChimeraService (has extras) } U=0: not found
,07-05 12:51:07.801  1949  1949 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
07-05 12:51:07.804  5421  5441 I art     : Explicit concurrent mark sweep GC freed 2927(116KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 732us total 26.341ms
07-05 12:51:07.806  6694  6792 E DefaultHttpIssuer: Attempt to consume entity of HttpIssuer when no request is executing.
07-05 12:51:07.807  6694  6792 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
07-05 12:51:07.807  6694  6792 E DefaultHttpIssuer: java.io.IOException
07-05 12:51:07.807  6694  6792 E DefaultHttpIssuer: 	at cjw.b(PG:159)
07-05 12:51:07.807  6694  6792 E DefaultHttpIssuer: 	at cju.b(PG:5072)
07-05 12:51:07.807  6694  6792 E DefaultHttpIssuer: 	at dlh.b(PG:239)
07-05 12:51:07.807  6694  6792 E DefaultHttpIssuer: 	at dlh.a(PG:140)
07-05 12:51:07.807  6694  6792 E DefaultHttpIssuer: 	at dqo.a(PG:224)
07-05 12:51:07.807  6694  6792 E DefaultHttpIssuer: 	at dlt.run(PG:9618)
07-05 12:51:07.807  6694  6792 E DefaultHttpIssuer: 	at dlr.run(PG:3031)
,07-05 12:51:07.814  6694  6792 E BaseSyncManager: IOException
07-05 12:51:07.814  6694  6792 E BaseSyncManager: java.io.IOException: stream was reset: PROTOCOL_ERROR
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at hzd.b(PG:145)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at hya.b(PG:104)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at hxn.d(PG:917)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at hxn.a(PG:95)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at hxn$a.a(PG:902)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at hvz.a(PG:50089)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at hvz$a.a(PG:230)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at hvz.a(PG:3201)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at clz.a(PG:127)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at cjr.a(PG:47)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at cjq.a(PG:22)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at cjs.a(PG:68)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at cjw.b(PG:92)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at cjw.a(PG:80)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at cju.b(PG:5140)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at cju.a(PG:1096)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at dlh.b(PG:14062)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at dlh.a(PG:140)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at dqo.a(PG:224)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at dlt.run(PG:9618)
07-05 12:51:07.814  6694  6792 E BaseSyncManager: 	at dlr.run(PG:3031)
07-05 12:51:07.825  6854  6870 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:07.825  6854  6870 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:07.833   880  1921 D WifiServiceImplEx: releaseWifiLock pid=6694, uid=10058, packageName=com.google.android.apps.docs
,07-05 12:51:07.859   880  2583 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6949 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
07-05 12:51:07.865   880  1019 I NotificationManager: android: cancelAsUser(-1488629395) by android
07-05 12:51:07.869  1949  2753 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
07-05 12:51:07.870  1949  2753 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
,07-05 12:51:07.871   489   489 D charger_monitor: init target 500000
07-05 12:51:07.871  1949  2753 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
07-05 12:51:07.888   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-05 12:51:07.902  6408  6408 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
,07-05 12:51:07.912  1949  2753 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
07-05 12:51:07.912  1949  2753 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
,07-05 12:51:07.928  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:51:07.928  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:51:07.928  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:51:07.928  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:51:07.928  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-05 12:51:07.952  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
07-05 12:51:07.953  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:51:07.953  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
07-05 12:51:07.954  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:51:07.955  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:51:07.958  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:51:07.960  6408  6546 I Gmail   : StartSyncInfoProto: Personal inbox enabled: true
07-05 12:51:07.961  6746  6970 I SyncAdapterService: Ignoring sync request for non-current account
07-05 12:51:07.966  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:51:07.967  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:51:07.967  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:51:07.967  1875  2041 D LEDHandler: Battery Temp: 310, mChargingStatus=5, mChargingStop=false
,07-05 12:51:07.975   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:51:07.975   880  1315 D WifiController: battery changed pluggedType: 2
07-05 12:51:07.975   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:51:07.980  6408  6546 I Gmail   : StartSyncInfoProto: Personal inbox android config: com.google.c.c.a.a@6e43254
,07-05 12:51:07.988  6694  6959 I NotificationManager: com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
,07-05 12:51:07.998  5485  5545 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.ocr
07-05 12:51:08.012  2372  2688 W Herrevad: Invalid mccmnc 
,07-05 12:51:08.080  2372  6946 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 12:51:08.080  2372  2649 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
07-05 12:51:08.095  2372  6946 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-05 12:51:08.095  2372  2688 W Herrevad: Invalid mccmnc 
,07-05 12:51:08.095  2372  2649 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
07-05 12:51:08.112  2372  6946 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 12:51:08.113  2372  2649 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
07-05 12:51:08.113  2372  2649 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.tapandpay
07-05 12:51:08.146  6949  6949 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
,07-05 12:51:08.157  6949  6949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
07-05 12:51:08.159  1331  1331 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
,07-05 12:51:08.161  1372  1372 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
07-05 12:51:08.162  1372  1372 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
07-05 12:51:08.162  1372  1372 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
07-05 12:51:08.168  6949  6949 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
07-05 12:51:08.168  6949  6949 V [BNRBootReceiver]: Boot Receiver Return
07-05 12:51:08.169  6949  6949 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-05 12:51:08.172   880  1019 I NotificationManager: android: cancelAsUser(-701419433) by android
,07-05 12:51:08.200  2372  2372 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,07-05 12:51:08.207  2372  2688 V NQFileLogger: [186] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
07-05 12:51:08.213  2372  2688 V ProcessReports: [186] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
07-05 12:51:08.325   880  1359 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6977 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-05 12:51:08.455   880  1921 I ActivityManager: Process com.google.android.play.games.ui (pid 6767) has died
,07-05 12:51:08.506  6408  6546 I Gmail   : checkLabelsSets changed the label sets to: included([^^out, ^r]), partial([^f]), all([^b, userlabel:90242001, userlabel:93982, userlabel:2914615, userlabel:90242029, userlabel:2914456, ^iim, ^k, ^p_aunsub, userlabel:3025, ^sq_ig_i_promo, userlabel:-1492276993, ^smartlabel_notification, userlabel:-1508083783, userlabel:382548592, ^imn, userlabel:90241997, userlabel:1680828287, ^all, userlabel:94101, ^imi, ^f, userlabel:-1492383895, userlabel:94076, userlabel:823616170, userlabel:-1492276994, userlabel:-1492276990, userlabel:3026, userlabel:-1492276991, ^u, ^t, ^s, ^smartlabel_group, userlabel:-812318908, ^smartlabel_personal, ^smartlabel_social, ^p_mtunsub, userlabel:2914593, ^sq_ig_i_personal, ^g, ^punsub, ^r, userlabel:-1497452393, ^i, ^smartlabel_promo, ^io_im, userlabel:2896756, userlabel:614875005, userlabel:-1492276992, ^p_bs, userlabel:-1711782184, userlabel:93692, userlabel:2907326, userlabel:-244132349, ^sq_ig_i_social, userlabel:3011, userlabel:90241971, userlabel:1123230114, ^p_abs])
,07-05 12:51:08.535   880   968 I ActivityManager: Process com.android.chrome (pid 6887) has died
,07-05 12:51:08.561  5485  6975 I PeopleSync: onPerformSync() [5005f081]
,07-05 12:51:08.611  6408  6546 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 1539011633578246145, highestHandledServerOp: 24708, normalSync: true
,07-05 12:51:08.655  5485  6996 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-05 12:51:08.655  5485  6996 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-05 12:51:08.664  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:08.678   880  2583 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:08.716  6977  6977 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-05 12:51:08.769  5485  6997 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,07-05 12:51:08.788  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:08.928  5485  6975 I PeopleSync: Setting subscription: result=true [5005f081]
07-05 12:51:08.928  5485  6975 I PeopleSync: Starting sync, feed=null [5005f081]
,07-05 12:51:09.012  6977  7003 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-05 12:51:09.012  6977  7003 I Babel_SMS: MmsConfig.loadMmsSettings
,07-05 12:51:09.018  6977  7003 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-05 12:51:09.018  6977  7003 I Babel_SMS: MmsConfig.loadFromDatabase
07-05 12:51:09.029  5485  6975 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,07-05 12:51:09.033  6977  7003 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-05 12:51:09.033  6977  7003 I Babel_SMS: MmsConfig.loadFromResources
07-05 12:51:09.036  6977  7003 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-05 12:51:09.037  6977  7003 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,07-05 12:51:09.094  6977  6977 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
07-05 12:51:09.094  6977  6977 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
07-05 12:51:09.094  6977  6977 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
07-05 12:51:09.094  6977  6977 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
07-05 12:51:09.095  6977  6977 D SensorManager: found sensor: Motion Accel, handle=46
07-05 12:51:09.112   880  1921 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:09.138  2372  6839 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-05 12:51:09.150  6408  6408 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
,07-05 12:51:09.169  6977  6991 I art     : CheckpointMarkThreadRoots callback created = 0xb042d480
,07-05 12:51:09.196  6977  6991 I art     : CheckpointMarkThreadRoots callback created = 0xb042d460
,07-05 12:51:09.318   880  1359 E libprocessgroup: failed to kill 1 processes for processgroup 6334
07-05 12:51:09.318   880  1359 I ActivityManager: Process com.google.android.apps.plus (pid 6334) has died
,07-05 12:51:09.326  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:09.330  1789  1789 I PhoneApp: onTrimMemory: 10
07-05 12:51:09.330  1789  1789 I PhoneApp: trim memory
07-05 12:51:09.372  6977  6977 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:51:09.377  6977  6977 I Babel_Crash: startup - clean
07-05 12:51:09.403  2372  2372 W GCM-DMM : Force release of GOOGLE_C2DM lock
,07-05 12:51:09.404  2372  2372 W GCM-DMM : Force release of GOOGLE_C2DM lock
07-05 12:51:09.409  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:09.427  2372  2688 W Herrevad: Invalid mccmnc 
,07-05 12:51:09.432  2372  2688 W Herrevad: Invalid mccmnc 
,07-05 12:51:09.462  6408  6546 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 24722, normalSync: true
07-05 12:51:09.463  6408  6546 I Gmail   : lowestBackward conversation id 0
07-05 12:51:09.478  6977  7006 I Babel   : deleted: false for 0
07-05 12:51:09.478   880  2134 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:09.532  2372  2688 V NQFileLogger: [186] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
,07-05 12:51:09.550  2372  2688 V ProcessReports: [186] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,07-05 12:51:09.573  2372  6841 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-05 12:51:09.645  6408  6408 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
,07-05 12:51:09.657  6408  6408 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
,07-05 12:51:09.698  2372  2372 I art     : Explicit concurrent mark sweep GC freed 105067(6MB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 15MB/25MB, paused 10.835ms total 180.330ms
,07-05 12:51:09.721  5485  5485 I GCM     : Message from 745476177629 null
,07-05 12:51:09.735  6854  6869 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:09.735  6854  6869 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:09.735  6854  6869 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:09.735  6854  6869 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 12:51:09.738   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:09.738   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:09.739   282  7022 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:09.739   282  7022 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:09.739   282  7022 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:09.739   282  7022 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:09.739   282  7022 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:09.740  6854  6869 I System.out: propertyValue:false
07-05 12:51:09.745  5485  5485 I GCM     : Message from 745476177629 null
07-05 12:51:09.746  5485  7014 W IcingInternalCorpora: getNumBytesRead when not calculated.
07-05 12:51:09.764  6977  6977 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,07-05 12:51:09.768  6977  6977 W AudioCapabilities: Unsupported mime audio/adpcm
07-05 12:51:09.771  6977  6977 W AudioCapabilities: Unsupported mime audio/g726
07-05 12:51:09.773  6977  6977 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-05 12:51:09.774  6977  6977 W AudioCapabilities: Unsupported mime audio/wma-voice
07-05 12:51:09.777  6977  6977 W VideoCapabilities: Unsupported mime video/mjpg
07-05 12:51:09.790  6977  6977 W VideoCapabilities: Unsupported mime video/theora
,07-05 12:51:09.846  6977  6977 W AudioCapabilities: Unsupported mime audio/evrc
,07-05 12:51:09.866  6977  6977 W AudioCapabilities: Unsupported mime audio/qcelp
,07-05 12:51:09.878  6977  6977 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 12:51:09.888  6854  6869 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:09.888  6854  6869 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:09.926  6977  6977 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-05 12:51:09.933  6977  6977 W AudioCapabilities: Unsupported mime audio/qcelp
07-05 12:51:09.937  6977  6977 W AudioCapabilities: Unsupported mime audio/evrc
07-05 12:51:09.949  6977  6977 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-05 12:51:09.955   880  1062 I art     : Explicit concurrent mark sweep GC freed 37234(1602KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.417ms total 180.607ms
07-05 12:51:09.976  6977  6977 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-05 12:51:09.984  6977  6977 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 12:51:09.986  6977  6977 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 12:51:09.990  6977  6977 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 12:51:10.001  6977  6977 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 12:51:10.035   880   967 I ActivityManager: Process com.google.android.apps.docs (pid 6694) has died
,07-05 12:51:10.060  6977  6977 I vclib   : onServiceConnected
,07-05 12:51:10.063  6977  6977 W Babel   : Attempted to change video mute state without an active call.
07-05 12:51:10.082  6977  6977 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,07-05 12:51:10.133   286   286 I WVCdm   : CdmEngine::CloseSession
,07-05 12:51:10.143   286   286 I WVCdm   : L3 Terminate.
07-05 12:51:10.145   286  1354 I WVCdm   : CdmEngine::OpenSession
07-05 12:51:10.145   286  1354 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
07-05 12:51:10.166   286  1354 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-05 12:51:10.166   286  1354 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
07-05 12:51:10.166   286  1354 W WVCdm   : L1 library not specified. Falling Back to L3
07-05 12:51:10.185   880  1863 I ActivityManager: Process com.lge.clock (pid 6921) has died
,07-05 12:51:10.196  1789  1789 I PhoneApp: onTrimMemory: 15
07-05 12:51:10.196  1789  1789 I PhoneApp: trim memory
07-05 12:51:10.294   286  1354 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 12:51:10.296   286  1615 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 12:51:10.296   286  1615 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-05 12:51:10.296   286  1615 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 12:51:10.303   286  1615 D WVCdm   : PrepareKeyRequest: nonce=1825563735
07-05 12:51:10.351  6408  6546 I Gmail   : notifyAccountChanged
,07-05 12:51:10.358  6408  6504 I Gmail   : getAccountsCursor
07-05 12:51:10.394  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:10.419  5485  7026 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 12:51:10.420  6408  6546 I Gmail   : notifyAccountChanged
07-05 12:51:10.425  6408  6533 I Gmail   : getAccountsCursor
07-05 12:51:10.428  6408  6546 W Gmail   : Sync complete for account: account:61035162
07-05 12:51:10.453  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:10.462  2372  7030 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
07-05 12:51:10.480  6854  6870 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
07-05 12:51:10.480  6854  6870 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-05 12:51:10.503  1949  1949 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
07-05 12:51:10.505  6854  6870 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
07-05 12:51:10.506  6854  6870 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000003@DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk': Failed to open oat filename for reading: No such file or directory
,07-05 12:51:10.507  6854  6870 D ChimeraFileApk: Classloading successful. Optimized code found.
07-05 12:51:10.512  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:10.517  6854  6870 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
07-05 12:51:10.504  1949  2098 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,07-05 12:51:10.522  1949  2098 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
07-05 12:51:10.522  1949  2098 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,07-05 12:51:10.524  1949  2098 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
07-05 12:51:10.525  1949  2098 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
07-05 12:51:10.615  2372  7034 I NotificationManager: com.google.android.gms: cancel(1000) by com.google.android.gms
,07-05 12:51:10.626  2372  7034 W WakefulBroadcastReceiver: No active wake lock id #1
07-05 12:51:10.635  2372  7034 E GnotsPayloadUtil: Payload contains insufficient data to show the system notification.
,07-05 12:51:10.662  6854  6870 D GoogleCertificatesImpl: Fetched 163 Google release certificates
,07-05 12:51:10.725   243   243 E lowmemorykiller: Error writing /proc/6949/oom_score_adj; errno=22
,07-05 12:51:10.828  7035  7035 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_dg_cache/042D5D9E998807924918C70C2492E0203B21CB19/the.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_dg_cache/042D5D9E998807924918C70C2492E0203B21CB19/opt/the.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-05 12:51:10.865   880  2192 I ActivityManager: Process com.lge.bnr (pid 6949) has died
,07-05 12:51:10.870  1789  1789 I PhoneApp: onTrimMemory: 15
07-05 12:51:10.870  1789  1789 I PhoneApp: trim memory
07-05 12:51:10.964  7035  7035 I dex2oat : dex2oat took 132.727ms (threads: 4)
,07-05 12:51:10.983  5485  5545 I Icing   : Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,07-05 12:51:11.056  5485  5545 I Icing   : Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
,07-05 12:51:11.201  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 12:51:11.236   880  2583 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:11.251  2372  7034 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-05 12:51:11.455  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 12:51:11.459  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:11.466  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:11.475  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 12:51:11.476  5485  6995 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:11.476  5485  6995 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:11.476  5485  6995 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:11.476  5485  6995 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:11.476   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:11.476   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:11.476   282  7041 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:11.476   282  7041 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:11.477   282  7041 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:11.477   282  7041 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:11.477   282  7041 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:11.478  5485  6995 I System.out: propertyValue:false
,07-05 12:51:11.809  7045  7045 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=43 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-05 12:51:11.818   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
07-05 12:51:11.872  7045  7045 I dex2oat : dex2oat took 62.707ms (threads: 4)
,07-05 12:51:11.890  6854  6870 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:51:11.890  6854  6870 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:51:11.890  6854  6870 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 12:51:11.890  6854  6870 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 12:51:11.890  6854  6870 I Adreno-EGL: Remote Branch: 
07-05 12:51:11.890  6854  6870 I Adreno-EGL: Local Patches: 
07-05 12:51:11.890  6854  6870 I Adreno-EGL: Reconstruct Branch: 
,07-05 12:51:11.964  5485  6995 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:11.964  5485  6995 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:12.045  6854  6870 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:51:12.045  6854  6870 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:51:12.045  6854  6870 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 12:51:12.045  6854  6870 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 12:51:12.045  6854  6870 I Adreno-EGL: Remote Branch: 
07-05 12:51:12.045  6854  6870 I Adreno-EGL: Local Patches: 
07-05 12:51:12.045  6854  6870 I Adreno-EGL: Reconstruct Branch: 
,07-05 12:51:12.110   286  1354 I WVCdm   : CdmEngine::OpenSession
,07-05 12:51:12.470   880  1019 I NotificationManager: android: cancelAsUser(1479798955) by android
,07-05 12:51:12.564  5421  6621 I art     : Explicit concurrent mark sweep GC freed 2785(109KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 364us total 24.667ms
,07-05 12:51:12.601  6854  6869 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:51:12.601  6854  6869 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:51:12.601  6854  6869 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 12:51:12.601  6854  6869 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 12:51:12.601  6854  6869 I Adreno-EGL: Remote Branch: 
07-05 12:51:12.601  6854  6869 I Adreno-EGL: Local Patches: 
07-05 12:51:12.601  6854  6869 I Adreno-EGL: Reconstruct Branch: 
,07-05 12:51:12.685  5485  5485 I art     : Explicit concurrent mark sweep GC freed 25975(1551KB) AllocSpace objects, 15(491KB) LOS objects, 24% free, 16MB/22MB, paused 1.503ms total 103.263ms
,07-05 12:51:12.703  5485  5496 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-05 12:51:12.744  6854  6869 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:51:12.744  6854  6869 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:51:12.744  6854  6869 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 12:51:12.744  6854  6869 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 12:51:12.744  6854  6869 I Adreno-EGL: Remote Branch: 
07-05 12:51:12.744  6854  6869 I Adreno-EGL: Local Patches: 
07-05 12:51:12.744  6854  6869 I Adreno-EGL: Reconstruct Branch: 
,07-05 12:51:12.788   880  1019 I NotificationManager: android: cancelAsUser(-379682945) by android
,07-05 12:51:12.808  6854  6869 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:51:12.808  6854  6869 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:51:12.808  6854  6869 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 12:51:12.808  6854  6869 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 12:51:12.808  6854  6869 I Adreno-EGL: Remote Branch: 
07-05 12:51:12.808  6854  6869 I Adreno-EGL: Local Patches: 
07-05 12:51:12.808  6854  6869 I Adreno-EGL: Reconstruct Branch: 
,07-05 12:51:12.813   286   286 I WVCdm   : CdmEngine::CloseSession
07-05 12:51:12.845   880  1019 I ActivityManager: Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=7077 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:12.880   286  1354 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 12:51:12.908   286  1304 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 12:51:12.908   286  1304 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-05 12:51:12.908   286  1304 I WVCdm   : CdmEngine::GenerateKeyRequest
,07-05 12:51:12.913   286  1304 D WVCdm   : PrepareKeyRequest: nonce=1134496458
,07-05 12:51:13.135  2372  7010 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:13.135  2372  7010 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:13.135  2372  7010 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:13.135  2372  7010 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:13.136   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:13.136   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:13.136   282  7096 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:13.136   282  7096 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 12:51:13.136   282  7096 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:13.137   282  7096 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:13.137   282  7096 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:13.137  2372  7010 I System.out: propertyValue:false
07-05 12:51:13.173  7077  7077 I MusicStore: Database version: 120
,07-05 12:51:13.265   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:13.265   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-05 12:51:13.265   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
,07-05 12:51:13.268  7077  7077 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-05 12:51:13.338  2372  7010 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:13.338  2372  7010 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:13.385   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:13.385   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-05 12:51:13.385   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:13.386  7077  7077 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,07-05 12:51:13.392   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:13.392   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-05 12:51:13.392   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:13.392  7077  7077 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-05 12:51:13.401  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 12:51:13.405  1372  1372 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
07-05 12:51:13.406  1911  1911 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
07-05 12:51:13.420  1789  1789 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-05 12:51:13.445  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,07-05 12:51:13.459   880  1290 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 12:51:13.462  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
07-05 12:51:13.462  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
07-05 12:51:13.465  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
07-05 12:51:13.465  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
07-05 12:51:13.465  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
07-05 12:51:13.465  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
07-05 12:51:13.465  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
07-05 12:51:13.465  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
07-05 12:51:13.465  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
07-05 12:51:13.465  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
07-05 12:51:13.465  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
07-05 12:51:13.466  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
07-05 12:51:13.468  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-05 12:51:13.478  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-05 12:51:13.481  7077  7077 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:13.481  7077  7077 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 12:51:13.510  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-05 12:51:13.534  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,07-05 12:51:13.558  7077  7077 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 12:51:13.571  2372  2372 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=c04d48b5-5f43-4556-87d6-f1c7c10b1242
,07-05 12:51:13.598   880   967 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7110 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-05 12:51:13.602  6977  6990 W art     : Suspending all threads took: 17.019ms
07-05 12:51:13.611   880   880 D administrator: Handling package changes for user 0
,07-05 12:51:13.639  1949  1949 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,07-05 12:51:13.665  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 12:51:13.688  7077  7077 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-05 12:51:13.691  7077  7077 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8bce51d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 12:51:13.692  7077  7077 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 12:51:13.695  7077  7077 D AndroidMusic: GMSCore installation verified
07-05 12:51:13.931   880  1019 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 12:51:13.938   880   880 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-05 12:51:13.940   880   880 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-05 12:51:13.940   880   880 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
07-05 12:51:13.995   880  1019 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,07-05 12:51:13.997   880  1062 I ActivityManager: Process com.google.android.apps.magazines (pid 6746) has died
07-05 12:51:14.002  1789  1789 I PhoneApp: onTrimMemory: 15
07-05 12:51:14.002  1789  1789 I PhoneApp: trim memory
07-05 12:51:14.017   880   880 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,07-05 12:51:14.031  7077  7077 I ConfigStore: Config Database version: 1
07-05 12:51:14.046   880   880 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
07-05 12:51:14.047   880   880 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@101f571b
,07-05 12:51:14.071  6977  7109 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,07-05 12:51:14.092  6977  6977 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:14.092  6977  6977 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 12:51:14.111  7110  7110 I AppUp4:AppBoxCP: onCreate
07-05 12:51:14.114  7110  7110 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-05 12:51:14.133  7077  7092 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3f0
07-05 12:51:14.136  7110  7110 I AppUp4:DB:  setFingerPrint start
,07-05 12:51:14.137  7110  7110 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
07-05 12:51:14.164  7110  7110 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
07-05 12:51:14.164  7110  7110 I AppUp4:DB:  SDK version = 21
07-05 12:51:14.164  7110  7110 I AppUp4:DB:  beforefinger == newfinger no write in DB
,07-05 12:51:14.165  2372  7034 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-05 12:51:14.170  7077  7092 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3d0
07-05 12:51:14.177  7110  7110 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,07-05 12:51:14.184  2372  7034 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
07-05 12:51:14.198  2372  7034 V BaseAppContext: GmsRequestQueue started.
,07-05 12:51:14.199  6977  6977 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
07-05 12:51:14.219  7110  7110 I AppUp4:CustModeStarterReceiver: onReceive
,07-05 12:51:14.219  7110  7110 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
07-05 12:51:14.228  7110  7110 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@399fc23b
07-05 12:51:14.228  7110  7110 D AppUp4:CustFacade: isCustomizationCompleted : false
07-05 12:51:14.237  7110  7110 D AppUp4:CustFacade: isSimDevice : true
,07-05 12:51:14.238  7110  7110 D AppUp4:CustModeStarterReceiver: begin check event
07-05 12:51:14.238  7110  7110 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-05 12:51:14.255  7077  7077 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-05 12:51:14.267  2372  7133 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:14.267  2372  7133 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:14.267  2372  7133 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:14.267  2372  7133 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:14.268   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:14.268   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:14.268   282  7139 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:14.268   282  7139 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 12:51:14.268   282  7139 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:14.269   282  7139 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:14.269   282  7139 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:14.275  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-05 12:51:14.280  2372  7133 I System.out: propertyValue:false
07-05 12:51:14.316   880  1936 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7140 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-05 12:51:14.320  5485  5555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:14.320  5485  5555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:14.320  5485  5555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:14.321  5485  5555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:14.321   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:14.321   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:14.321   282  7146 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:14.321   282  7146 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:14.322   282  7146 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:14.322   282  7146 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:14.322   282  7146 D libc-netbsd: res_queryN name = xxxxx succeed
,07-05 12:51:14.323  5485  5555 I System.out: propertyValue:false
07-05 12:51:14.347  6977  6977 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 12:51:14.347  6977  6977 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 12:51:14.365  2372  2372 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-05 12:51:14.386  7077  7077 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-05 12:51:14.398  7077  7077 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-05 12:51:14.401   880  1019 D LocationProviderProxy: applying state to connected service
,07-05 12:51:14.427  7077  7077 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 12:51:14.445  7077  7160 I MusicLifecycle: Sync started
,07-05 12:51:14.465  7140  7140 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:51:14.466  7140  7140 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-05 12:51:14.466  7140  7140 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,07-05 12:51:14.501  6977  6977 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
07-05 12:51:14.649   880  1936 I art     : Explicit concurrent mark sweep GC freed 31480(1516KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 1.881ms total 166.727ms
,07-05 12:51:14.660  2372  2710 W GCoreFlp: No location to return for getLastLocation()
07-05 12:51:14.669  7077  7077 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 12:51:14.686  7077  7077 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-05 12:51:14.689  7077  7077 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 12:51:14.706  7140  7140 I AppConfig: Total System Memory = 906309632
,07-05 12:51:14.717  7140  7140 I GalleryUtils: Application Heap = 96 MB
07-05 12:51:14.732  7140  7140 I AppConfig: App Tier : NOT_DEF
,07-05 12:51:14.740  7140  7140 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
07-05 12:51:14.747  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 12:51:14.753  7077  7101 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
07-05 12:51:14.763  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 12:51:14.792  5485  7095 D UdcContextInitService: registered all accounts: true
,07-05 12:51:14.880   880  1948 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7171 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,07-05 12:51:14.967  2372  7034 W WakefulBroadcastReceiver: No active wake lock id #2
07-05 12:51:14.968  2372  2699 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 12:51:14.992  2372  2670 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-05 12:51:15.005  7171  7171 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:51:15.006  7171  7171 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-05 12:51:15.007  7171  7171 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,07-05 12:51:15.009  7171  7171 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-05 12:51:15.010  7171  7171 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,07-05 12:51:15.052  5421  5549 I art     : Explicit concurrent mark sweep GC freed 3001(117KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 398us total 31.644ms
,07-05 12:51:15.075   880  1921 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:15.089  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:15.099  2372  6839 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
07-05 12:51:15.108   880  1948 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:15.125   286  1354 I WVCdm   : CdmEngine::CloseSession
07-05 12:51:15.126  7077  7160 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:15.126  7077  7160 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:15.126  7077  7160 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:15.126  7077  7160 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:15.127   282  1045 E BandwidthController: [LG DATA] No such appUid: 10081
07-05 12:51:15.127   282  1045 D DnsProxyListener: App 10081 tries DNS query. Accept family:0 protocol:0
07-05 12:51:15.127   282  7192 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:15.127   282  7192 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:15.128   282  7192 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:15.128   282  7192 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:15.129   286  1354 I WVCdm   : L3 Terminate.
,07-05 12:51:15.164   282  7192 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:15.165  7077  7160 I System.out: propertyValue:false
07-05 12:51:15.192  6977  7162 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:51:15.226  7171  7171 I SystemConfig: BUILD Country: EU
,07-05 12:51:15.226  7171  7171 I SystemConfig: BUILD Operator: OPEN
07-05 12:51:15.251  6854  6870 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 12:51:15.251  6854  6870 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:51:15.251  6854  6870 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 12:51:15.251  6854  6870 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 12:51:15.251  6854  6870 I Adreno-EGL: Remote Branch: 
07-05 12:51:15.251  6854  6870 I Adreno-EGL: Local Patches: 
07-05 12:51:15.251  6854  6870 I Adreno-EGL: Reconstruct Branch: 
,07-05 12:51:15.288  7077  7160 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:15.288  7077  7160 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:15.291  6977  7198 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:15.291  6977  7198 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
07-05 12:51:15.291   282  1045 E BandwidthController: [LG DATA] No such appUid: 10061
07-05 12:51:15.291   282  1045 D DnsProxyListener: App 10061 tries DNS query. Accept family:2 protocol:0
07-05 12:51:15.291   282  7202 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:15.291   282  7202 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
07-05 12:51:15.292   282  7202 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:15.292   282  7202 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:15.300  2372  7196 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 12:51:15.302  2372  7187 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-05 12:51:15.340  5485  6605 I CheckinUtil: Classify the device as Phone.
,07-05 12:51:15.353  2372  7196 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-05 12:51:15.353  2372  7187 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 12:51:15.375  2372  2670 I art     : Explicit concurrent mark sweep GC freed 60267(3MB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 15MB/26MB, paused 2.373ms total 218.955ms
,07-05 12:51:15.418   880  1936 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7207 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:15.437  2372  7196 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 12:51:15.438  2372  7187 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-05 12:51:15.438  2372  7187 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
07-05 12:51:15.440  7171  7205 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-05 12:51:15.441  7171  7205 I SystemConfig: existFile = false
07-05 12:51:15.441  7171  7205 I SystemConfig: canReadFile = false
07-05 12:51:15.441  7171  7205 I SystemConfig: systemFeature RCS result false
07-05 12:51:15.441  7171  7205 D SystemConfig: refreshRcsSupport() :false
07-05 12:51:15.460  2372  7187 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 12:51:15.544   880  1936 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:15.546  7207  7207 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-05 12:51:15.567  2372  2670 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:15.567  2372  2670 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:15.568  2372  2670 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:15.568  2372  2670 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:15.568   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:15.568   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:15.568   282  7224 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:15.568   282  7224 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:15.569   282  7224 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:15.569   282  7224 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:15.569   282  7224 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:15.570  2372  2670 I System.out: propertyValue:false
,07-05 12:51:15.593  7207  7207 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,07-05 12:51:15.593  7207  7207 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-05 12:51:15.593  7207  7207 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-05 12:51:15.593  7207  7207 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-05 12:51:15.593  7207  7207 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-05 12:51:15.595  2372  7187 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:15.595  2372  7187 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:15.595  2372  7187 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:15.595  2372  7187 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:15.596   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:15.596   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:15.596   282  7226 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:15.596   282  7226 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:15.596   282  7226 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:15.597   282  7226 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:15.641   880   967 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7227 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:15.699   282  7226 D libc-netbsd: res_queryN name = xxxxx succeed
,07-05 12:51:15.700  2372  7187 I System.out: propertyValue:false
07-05 12:51:15.724  2372  2670 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:15.724  2372  2670 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:15.833  5485  6605 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:15.834  5485  6605 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:15.834  5485  6605 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:15.834  5485  6605 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:15.834   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:15.834   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:15.834   282  7245 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:15.834   282  7245 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:15.835   282  7245 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:15.835   282  7245 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:15.835   282  7245 D libc-netbsd: res_queryN name = xxxxx succeed
,07-05 12:51:15.836  5485  6605 I System.out: propertyValue:false
07-05 12:51:15.995  5485  6975 I PeopleSync: Sync finished, successful=true, took 6963ms
,07-05 12:51:16.031  5485  6975 I PeopleContactsSync: CP2 sync start [5005f081]
,07-05 12:51:16.037  7227  7227 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
07-05 12:51:16.041  5485  6975 I PeopleContactsSync: CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
07-05 12:51:16.046  5485  6975 I PeopleContactsSync: Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,07-05 12:51:16.107  5485  6975 I PeopleContactsSync: CP2 cleanup done, kept= duration=58 ms
07-05 12:51:16.110  5485  6975 I PeopleContactsSync: ===CP2 sync finished, success=true, time=75,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,07-05 12:51:16.129  5485  6975 I PeopleSync: ***Sync finished***, duration: 7554 [5005f081]
,07-05 12:51:16.150   880  1019 I NotificationManager: android: cancelAsUser(148851818) by android
07-05 12:51:16.205   880  1019 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService: pid=7255 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:16.221   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.034ms
,07-05 12:51:16.244   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.373ms
,07-05 12:51:16.265   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.001ms
,07-05 12:51:16.276  7255  7255 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 12:51:16.351  7227  7227 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(168): Dirty, need more hygiene.
,07-05 12:51:16.421  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:16.422  7227  7227 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-05 12:51:16.423  7227  7227 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-05 12:51:16.441  5485  6605 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:16.441  5485  6605 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:16.445  7227  7227 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
07-05 12:51:16.446   880  2134 I NotificationManager: android: cancelAsUser(2) by android
07-05 12:51:16.449  6977  7162 I art     : Note: end time exceeds epoch: 
07-05 12:51:16.476  6977  7289 I Babel   : Account registration complete:1-Redacted-21
,07-05 12:51:16.492  7227  7227 I Finsky  : [1] com.google.android.finsky.utils.bk.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
07-05 12:51:16.493  7227  7283 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:16.493  7227  7283 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:16.496  7227  7283 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:16.496  7227  7283 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:16.497   282  1045 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 12:51:16.497   282  1045 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 12:51:16.497   282  7302 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:16.497   282  7302 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:16.498   282  7302 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:16.498   282  7302 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:16.498   282  7302 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:16.499  7227  7283 I System.out: propertyValue:false
,07-05 12:51:16.536  6977  7289 I Babel   : ProcessRegisterDeviceResponse
07-05 12:51:16.536  6977  7289 I Babel   : Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
,07-05 12:51:16.545   880  1726 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:16.566  7227  7227 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1226): Installer kick - no action, not running yet
07-05 12:51:16.573  7227  7227 I Finsky  : [1] com.google.android.finsky.j.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,07-05 12:51:16.573  7227  7227 I Finsky  : [1] com.google.android.finsky.j.j.run(214): Finished loading 1 libraries.
07-05 12:51:16.583  3117  3133 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
07-05 12:51:16.584   880  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=2510306, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=880
07-05 12:51:16.596  3117  3133 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@ddd9efc on behalf of 7227
,07-05 12:51:16.602   880  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{25d6f1ee type 2 when 183166 com.google.android.talk} when 183166
,07-05 12:51:16.604  2372  2670 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-05 12:51:16.632  5485  7308 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 12:51:16.658  5485  7308 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 12:51:16.675  7227  7227 I Finsky  : [1] com.google.android.finsky.c.l.a(270): result=false type=4
,07-05 12:51:16.683  5485  5545 I Icing   : updateResources: need to parse owf{com.google.android.gms}
07-05 12:51:16.694  2372  2670 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-07-05 12:51:15.078+0200, stopTime=2016-07-05 12:51:16.690+0200, duration=1612ms
,07-05 12:51:16.713  7227  7227 I Finsky  : [1] com.google.android.finsky.services.bc.a(1050): Restore complete with 0 success and 0 failed.
,07-05 12:51:16.762   243   243 E lowmemorykiller: Error writing /proc/6408/oom_score_adj; errno=22
,07-05 12:51:16.803  5485  6605 I CheckinTask: Sending checkin request (29982 bytes)
,07-05 12:51:16.823   300   355 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-05 12:51:16.835   880  1881 I ActivityManager: Process com.google.android.gm (pid 6408) has died
,07-05 12:51:16.841  7227  7227 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 80
07-05 12:51:16.843  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:16.844  1789  1789 I PhoneApp: onTrimMemory: 10
07-05 12:51:16.844  1789  1789 I PhoneApp: trim memory
07-05 12:51:16.856  7077  7160 I MusicSyncAdapter: Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
,07-05 12:51:16.862  7077  7160 I MusicSyncAdapter: Periodic update
07-05 12:51:16.877  5485  7318 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 12:51:16.919  7077  7169 W MusicApiClient: Activity events list is null or empty. Skip reporting.
,07-05 12:51:17.076   880  1359 I art     : Explicit concurrent mark sweep GC freed 21386(975KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.349ms total 146.702ms
,07-05 12:51:17.079  7077  7160 I MusicLifecycle: Sync ended
07-05 12:51:17.079  2372  2670 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-05 12:51:17.091   880  1019 I NotificationManager: android: cancelAsUser(-1123058983) by android
07-05 12:51:17.116  2020  7329 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-05 12:51:17.155  7255  7273 I art     : CheckpointMarkThreadRoots callback created = 0xb042d920
,07-05 12:51:17.173  7255  7273 I art     : CheckpointMarkThreadRoots callback created = 0xb042d910
,07-05 12:51:17.177   880  2192 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7332 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 12:51:17.220   880  2028 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:17.225  5485  7338 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-05 12:51:17.238  2020  7329 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 120 ms] updated apps [took 120 ms] 
,07-05 12:51:17.274  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:17.284   880  1019 I NotificationManager: android: cancelAsUser(-1874035846) by android
07-05 12:51:17.289   880  1863 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:17.309   880  1019 I NotificationManager: android: cancelAsUser(1500439826) by android
,07-05 12:51:17.326  5485  7338 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:17.326  5485  7338 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:17.356   880  1288 V AlarmManager: RTC_WAKEUP set : Alarm{3276bc14 type 0 when 1467715877352 com.android.vending} when 1467715877352
07-05 12:51:17.357  7227  7227 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(17227): Beginning daily hygiene, foreground = false
,07-05 12:51:17.392   880  1019 I NotificationManager: android: cancelAsUser(-1816247584) by android
07-05 12:51:17.398  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:17.409   880  1936 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:17.444  7227  7252 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:51:17.446  7227  7252 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:17.446  7227  7252 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:17.446  7227  7252 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:17.447   282  1045 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 12:51:17.447   282  1045 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 12:51:17.447   282  7356 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:17.447   282  7356 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:17.448   282  7356 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:17.448   282  7356 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:17.448   282  7356 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:17.449  7227  7252 I System.out: propertyValue:false
07-05 12:51:17.481   880  1921 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,07-05 12:51:17.513   880  1910 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:17.533  2372  7187 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-05 12:51:17.539  5485  6605 I CheckinResponseProcessor: From server: 1 gservices updates and 1 deletes
07-05 12:51:17.585  7332  7363 I Gmail   : getAccountsCursor
,07-05 12:51:17.595  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:17.616  7332  7332 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 12:51:17.653   880  2134 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,07-05 12:51:17.687  5485  5498 W art     : Suspending all threads took: 6.301ms
,07-05 12:51:17.705   880  2583 I ActivityManager: Process com.android.gallery3d (pid 7140) has died
,07-05 12:51:17.711  7227  7227 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 10
07-05 12:51:17.712  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:17.714  1789  1789 I PhoneApp: onTrimMemory: 10
07-05 12:51:17.714  1789  1789 I PhoneApp: trim memory
07-05 12:51:17.726  7332  7372 E Gmail   : Error finding the version of the Email provider.....
07-05 12:51:17.726  7332  7372 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-05 12:51:17.726  7332  7372 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-05 12:51:17.726  7332  7372 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
07-05 12:51:17.726  7332  7372 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-05 12:51:17.726  7332  7372 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-05 12:51:17.726  7332  7372 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:51:17.726  7332  7372 E Gmail   : 	at android.os.Looper.loop(Looper.java:135)
07-05 12:51:17.726  7332  7372 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:51:17.726  7332  7372 W EmailMigration: We do not support migrating this version of the Email provider.
,07-05 12:51:17.729  7332  7374 I Gmail   : getAccountsCursor
07-05 12:51:17.738  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:17.746  2372  7136 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:17.746  2372  7136 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:17.746  2372  7136 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:17.746  2372  7136 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:17.746   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:17.746   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:17.747   282  7375 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:17.747   282  7375 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:17.747   282  7375 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:17.747   282  7375 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:17.755   880   967 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-05 12:51:17.764  7332  7378 I Gmail   : Observing account changes for notifications
07-05 12:51:17.771   880  1881 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,07-05 12:51:17.781  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:17.793   880  7379 I CertBlacklister: Certificate blacklist changed, updating...
,07-05 12:51:17.798   880  1936 I NotificationManager: android: cancelAsUser(2) by android
07-05 12:51:17.815   282  7375 D libc-netbsd: res_queryN name = xxxxx succeed
,07-05 12:51:17.818  2372  7136 I System.out: propertyValue:false
,07-05 12:51:17.860  5421  5440 I GservicesProvider: main difference update completed
,07-05 12:51:17.891  5421  5583 I art     : Explicit concurrent mark sweep GC freed 9874(485KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.288ms total 57.307ms
,07-05 12:51:17.915   880  1936 I ActivityManager: Process com.android.contacts (pid 7171) has died
,07-05 12:51:17.922  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:17.922  1789  1789 I PhoneApp: onTrimMemory: 10
07-05 12:51:17.922  1789  1789 I PhoneApp: trim memory
07-05 12:51:17.929  7227  7227 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 10
07-05 12:51:17.943   880  7379 I CertBlacklister: Certificate blacklist updated
,07-05 12:51:17.953   880  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{49d474 type 2 when 184562 com.google.android.gms} when 184562
07-05 12:51:17.967  5485  6605 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,07-05 12:51:17.970  5485  5545 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
07-05 12:51:17.990  5485  6605 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-05 12:51:17.994   880  1019 I NotificationManager: android: cancelAsUser(-1878923137) by android
,07-05 12:51:18.017  7332  7381 I Gmail   : notifyAccountChanged
,07-05 12:51:18.021  7332  7390 I Gmail   : getAccountsCursor
07-05 12:51:18.021  7332  7381 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
07-05 12:51:18.030   880   968 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7391 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-05 12:51:18.037  7332  7381 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 12:51:18.053  7332  7381 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 12:51:18.059  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:18.061  7332  7381 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 12:51:18.128   880  1863 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:18.170  7391  7391 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-05 12:51:18.241  7332  7363 I Gmail   : getAccountsCursor
,07-05 12:51:18.249  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:18.254  5485  5545 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,07-05 12:51:18.276  5485  7410 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-05 12:51:18.310   880  1019 I NotificationManager: android: cancelAsUser(-591465577) by android
07-05 12:51:18.335   880  1053 D BluetoothManagerService: Message: 20
07-05 12:51:18.335   880  1053 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@194628:true
,07-05 12:51:18.365   880  1019 I ActivityManager: Start proc com.lge.qmemoplus for service com.lge.qmemoplus/.network.googledrive.DriveSyncService: pid=7411 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,07-05 12:51:18.420  2055  2070 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
07-05 12:51:18.422  2055  2071 D BluetoothAdapterService(624497901): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f01b02b
,07-05 12:51:18.434   880  1936 I art     : Explicit concurrent mark sweep GC freed 22370(973KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 4.607ms total 171.282ms
07-05 12:51:18.468  7411  7411 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-05 12:51:18.510  5485  6605 I CheckinUtil: Classify the device as Phone.
,07-05 12:51:18.578   880  2170 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=7435 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,07-05 12:51:18.600  7411  7411 E App     : [App][onCreate()] 4.40.23
,07-05 12:51:18.618   243   243 E lowmemorykiller: Error writing /proc/7110/oom_score_adj; errno=22
,07-05 12:51:18.635   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:18.635   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-05 12:51:18.635   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:18.637  7077  7165 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,07-05 12:51:18.679   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:18.679   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
07-05 12:51:18.679   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
,07-05 12:51:18.679  7077  7165 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
07-05 12:51:18.690   880  1359 I ActivityManager: Process com.lge.appbox.client (pid 7110) has died
07-05 12:51:18.697  7227  7227 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 15
,07-05 12:51:18.708  1789  1789 I PhoneApp: onTrimMemory: 15
07-05 12:51:18.708  1789  1789 I PhoneApp: trim memory
,07-05 12:51:18.744  2372  7370 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_identity_app_security_threat
,07-05 12:51:18.761  2372  7370 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_google_g_icon
,07-05 12:51:18.785  7077  7433 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
,07-05 12:51:18.785  7077  7433 I MusicLeanback: Stop autocaching.
07-05 12:51:18.805   880  1019 I NotificationManager: android: cancelAsUser(2126026182) by android
,07-05 12:51:18.835   880  1881 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:18.839  6977  7298 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
07-05 12:51:18.839  6977  7298 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
07-05 12:51:18.854  5485  6605 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-05 12:51:18.914   880  1726 V NotificationService: enqueueNotificationInternal: pkg=com.google.android.gms id=1000 notification=Notification(pri=1 contentView=null vibrate=default sound=default defaults=0x7 flags=0x1 color=0x00000000 vis=PRIVATE publicVersion=Notification(pri=0 contentView=com.google.android.gms/0x1090079 vibrate=null sound=null defaults=0x0 flags=0x0 color=0x00000000 vis=PRIVATE))
,07-05 12:51:18.915   880  2028 I ActivityManager: Process com.lge.lockscreensettings (pid 7207) has died
07-05 12:51:18.918  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:18.924   880   880 D ZenLog  : intercepted: 0|com.google.android.gms|1000|ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227|10006,none
07-05 12:51:18.929   880   880 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
07-05 12:51:18.929   880   880 I NotificationServiceEx: LED remove() : mLights=0|com.google.android.gms|1000|ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227|10006
,07-05 12:51:18.935   880   880 D NotificationServiceEx: updateLightListLocked :r=0|com.google.android.gms|1000|ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227|10006, action=2
07-05 12:51:18.935  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:18.939   880   880 D NotificationServiceEx: notification=Notification(pri=1 contentView=null vibrate=default sound=default defaults=0x7 flags=0x1 color=0x00000000 vis=PRIVATE publicVersion=Notification(pri=0 contentView=com.google.android.gms/0x1090079 vibrate=null sound=null defaults=0x0 flags=0x0 color=0x00000000 vis=PRIVATE))
07-05 12:51:18.975  5485  6605 I CheckinChimeraService: Checking schedule, now: 1467715878975 next: 1468243127854
07-05 12:51:18.975  5485  6605 I CheckinChimeraService: active receiver: disabled
,07-05 12:51:18.987  6977  7162 I art     : Note: end time exceeds epoch: 
,07-05 12:51:19.001   880   880 D lightsbindercall: calling ... updateLightList
,07-05 12:51:19.001   880   880 E lightsbindercall: virtual void android::BpLEDManager::updateLightList(int32_t, int32_t, int, int32_t, int32_t, int32_t, const android::String16&) : Binder Transaction Start!!
07-05 12:51:19.016  1875  1891 D LEDService: updateLightListInternal() : action=2 pkg=com.google.android.gms
,07-05 12:51:19.032   880   880 E lightsbindercall: virtual void android::BpLEDManager::updateLightList(int32_t, int32_t, int, int32_t, int32_t, int32_t, const android::String16&) : Binder Transaction End!! (error code 0)
,07-05 12:51:19.055  5421  7397 I art     : Explicit concurrent mark sweep GC freed 3581(153KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 2.652ms total 51.304ms
,07-05 12:51:19.062   880  2192 I NotificationManager: android: cancelAsUser(2) by android
07-05 12:51:19.068  7411  7411 D AccountManager: setSyncFrequency
07-05 12:51:19.068  1331  1347 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:19.068  1372  2474 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-05 12:51:19.073  1372  2474 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 12:51:19.074  1331  1347 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 12:51:19.098  1331  1347 D SmartCoverUpdateMonitor: onNotificationPosted() : StatusBarNotification(pkg=com.google.android.gms user=UserHandle{0} id=1000 tag=ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227 score=10 key=0|com.google.android.gms|1000|ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227|10006: Notification(pri=1 contentView=com.google.android.gms/0x1090079 vibrate=default sound=default defaults=0x7 flags=0x1 color=0x00000000 vis=PRIVATE publicVersion=Notification(pri=0 contentView=com.google.android.gms/0x1090079 vibrate=null sound=null defaults=0x0 flags=0x0 color=0x00000000 vis=PRIVATE)))
,07-05 12:51:19.103  1331  1331 D SmartCoverUpdateMonitor: addNotification() qcn.getKey() : 0|com.google.android.gms|1000|ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227|10006
07-05 12:51:19.103  1331  1331 D LgeQuickCoverNotificationData: addNotification() : 0|com.google.android.gms|1000|ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227|10006
07-05 12:51:19.103  1331  1331 D LgeQuickCoverNotificationData: filterAndSort()
07-05 12:51:19.126   880  1863 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=7469 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,07-05 12:51:19.130  1331  1331 D LgeQuickCoverNotificationData: isNotificationForCurrentUser : true
,07-05 12:51:19.148  1331  1331 D LgeQuickCoverNotificationData: isNotificationForCurrentUser : true
07-05 12:51:19.150  1331  1331 D LgeQuickCoverNotificationData: isNotificationForCurrentUser : true
07-05 12:51:19.151  1331  1331 D LgeQuickCoverNotificationData: showAll3
07-05 12:51:19.151  1331  1331 D LgeQuickCoverNotificationData: showAll() Key : 0|com.google.android.gms|1000|ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227|10006 , GroupKey : 0|com.google.android.gms|1000|ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227|10006
07-05 12:51:19.151  1331  1331 D LgeQuickCoverNotificationData: showAll() Key : 0|com.lge.eula|262082|null|1000 , GroupKey : 0|com.lge.eula|262082|null|1000
07-05 12:51:19.152  1331  1331 D LgeQuickCoverNotificationData: showAll() Key : 0|com.android.systemui|2130839020|null|10025 , GroupKey : 0|com.android.systemui|2130839020|null|10025
,07-05 12:51:19.171  5485  5485 D CheckinChimeraService: Recording last checkin time for package unspecified as 1467715879170
,07-05 12:51:19.224  7411  7411 D DriveSyncService: onCreate
07-05 12:51:19.225  7411  7411 D DriveSyncService: onBind
07-05 12:51:19.234  7411  7488 D DriveSyncAdapter: onPerformSync() START
07-05 12:51:19.234  7411  7488 D DriveSyncAdapter: Not added account. Stop
07-05 12:51:19.245   880  1863 I ActivityManager: Process com.google.android.apps.plus (pid 7255) has died
,07-05 12:51:19.247  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:19.251   880  1019 I NotificationManager: android: cancelAsUser(1312559638) by android
07-05 12:51:19.299  7227  7227 I Finsky  : [1] com.google.android.finsky.selfupdate.f.a(163): Skipping DFE self-update. Local Version [80671300] >= Server Version [-1]
,07-05 12:51:19.303  5485  7486 I RemindersSync: Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=761:priority=5:group=main]
,07-05 12:51:19.415   880  1359 I ActivityManager: Process com.google.android.gm (pid 7332) has died
,07-05 12:51:19.421  2372  2372 I art     : Explicit concurrent mark sweep GC freed 45143(2MB) AllocSpace objects, 29(1138KB) LOS objects, 39% free, 16MB/26MB, paused 2.204ms total 193.463ms
07-05 12:51:19.423  1789  1789 I PhoneApp: onTrimMemory: 15
07-05 12:51:19.423  1789  1789 I PhoneApp: trim memory
07-05 12:51:19.425  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-05 12:51:19.432  7227  7227 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 15
,07-05 12:51:19.478   880  2192 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7492 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
07-05 12:51:19.487   880  1019 I NotificationManager: android: cancelAsUser(898701380) by android
07-05 12:51:19.499  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:19.533   880  1019 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=7509 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:19.563  7469  7469 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,07-05 12:51:19.565  2372  7370 W WakefulBroadcastReceiver: No active wake lock id #3
07-05 12:51:19.582  1372  1372 I [SystemUI]PhoneStatusBar: updateMediaMetaData(false): mMediaMetadata = null
,07-05 12:51:19.608  7469  7469 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,07-05 12:51:19.619   880  2192 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:19.622  7492  7492 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:19.622  7492  7492 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 12:51:19.629  7509  7509 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:51:19.638  7469  7469 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,07-05 12:51:19.643  7469  7469 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
07-05 12:51:19.701  5485  7538 D GmsModuleFndr: Beginning GMS chimera module scan
,07-05 12:51:19.703  5485  7538 D GmsModuleFndr: Module pkg com.google.android.gms.policy_auth not installed, skipping
07-05 12:51:19.709  5485  7538 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
07-05 12:51:19.710  5485  7538 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
07-05 12:51:19.711  5485  7538 D GmsModuleFndr: Module pkg com.google.android.gms.setup not installed, skipping
07-05 12:51:19.714  7492  7492 I MultiDex: VM with version 2.1.0 has multidex support
07-05 12:51:19.715  7492  7492 I MultiDex: install
07-05 12:51:19.715  7492  7492 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 12:51:19.744  5485  7308 D PeriodicTasksManager: Got new setting, will re-schedule periodic tasks.
,07-05 12:51:19.752  5485  7308 D PeriodicTasksManager: Scheduling periodical signal task every 86400 seconds
07-05 12:51:19.766  5485  7538 D ChimeraCfgMgr: Beginning module configuration check
,07-05 12:51:19.790  5485  7308 D PeriodicTasksManager: AdAttestation signal task scheduled
,07-05 12:51:19.829  5485  7538 D ChimeraCfgMgr: Module APKs unchanged, check complete
,07-05 12:51:19.837   880  1062 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-05 12:51:19.843  7492  7492 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 12:51:19.886  5421  6682 I art     : Explicit concurrent mark sweep GC freed 3888(165KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 928us total 34.223ms
,07-05 12:51:19.992  7492  7492 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-05 12:51:19.994  7492  7492 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1682a00b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 12:51:19.995  7492  7492 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 12:51:19.999  7492  7492 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
07-05 12:51:20.001  7492  7492 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
07-05 12:51:20.011  2372  7528 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:20.012  2372  7528 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:20.012  2372  7528 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:20.012  2372  7528 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 12:51:20.013   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:51:20.013   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:51:20.014   282  7547 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:20.014   282  7547 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:20.014   282  7547 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:20.014   282  7547 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:20.015   282  7547 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:51:20.015  2372  7528 I System.out: propertyValue:false
07-05 12:51:20.017  7492  7492 D ChimeraCfgMgr: Reading stored module config
07-05 12:51:20.089  2372  7550 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 12:51:20.094  2372  2372 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
07-05 12:51:20.125  5485  5485 D OcrModelBroadcastRcvr: com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 12:51:20.125  5485  5485 D OcrModelBroadcastRcvr: Updating OCR activity and model state
,07-05 12:51:20.149  5485  5485 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
07-05 12:51:20.213  7509  7524 I art     : CheckpointMarkThreadRoots callback created = 0xb042d710
,07-05 12:51:20.243  2372  7528 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:20.243  2372  7528 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:51:20.263  7509  7524 I art     : CheckpointMarkThreadRoots callback created = 0xb042d700
,07-05 12:51:20.297   880  2028 I ActivityManager: Process com.google.android.music:main (pid 7077) has died
,07-05 12:51:20.306  7227  7227 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 15
07-05 12:51:20.311   880  2583 W art     : Suspending all threads took: 7.333ms
,07-05 12:51:20.319  1789  1789 I PhoneApp: onTrimMemory: 15
07-05 12:51:20.319  1789  1789 I PhoneApp: trim memory
07-05 12:51:20.338   880  2583 I art     : Explicit concurrent mark sweep GC freed 20636(962KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 10.793ms total 185.987ms
,07-05 12:51:20.353  2372  2649 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
07-05 12:51:20.361  5485  5537 V PrereqChecker: Build version: 21
07-05 12:51:20.362  5485  5537 V PrereqChecker: Model: LG-D722
07-05 12:51:20.362  5485  5537 V PrereqChecker: CPU_ABI: armeabi-v7a
07-05 12:51:20.362  5485  5537 V PrereqChecker: CPU_ABI2: armeabi
,07-05 12:51:20.366  7492  7546 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 12:51:20.379  5485  5537 V PrereqChecker: Camera #0 is a rear-facing camera.
,07-05 12:51:20.386  5485  5537 D CreditCardPrerequisiteChecker: All prerequisites OK.
07-05 12:51:20.386  2372  2670 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
07-05 12:51:20.388  5485  5537 I OcrModelUpdtStIntSvc: Updating ocr activity enabled=false (gservicesFlag=false, lowRamDevice=false, prereqCheck=true)
,07-05 12:51:20.492  7492  7492 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
07-05 12:51:20.492  7492  7506 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3d0
,07-05 12:51:20.500  5421  6682 I art     : Explicit concurrent mark sweep GC freed 3373(131KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 3.578ms total 88.629ms
07-05 12:51:20.509  7492  7492 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,07-05 12:51:20.541   880  1019 I NotificationManager: android: cancelAsUser(2145784878) by android
,07-05 12:51:20.544  7492  7506 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3c0
,07-05 12:51:20.564  7492  7492 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
07-05 12:51:20.564  7492  7492 D CAR.SERVICE: onBind
,07-05 12:51:20.564  7492  7492 D CAR.SERVICE: CSB onClientsConnected
07-05 12:51:20.595  7492  7506 W art     : Suspending all threads took: 23.174ms
,07-05 12:51:20.613  7492  7492 D CAR.TEL.Service: Binding to InCallService
,07-05 12:51:20.624   880  2028 W ActivityManager: Unable to start service Intent { act=local_action cmp=com.google.android.gms/.car.InCallService2 } U=0: not found
07-05 12:51:20.625  7492  7492 E CAR.TEL.Service: Failed to bind to InCallService
07-05 12:51:20.638  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-05 12:51:20.641   489   489 D charger_monitor: init target 500000
07-05 12:51:20.643  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:51:20.643  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:51:20.644  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:51:20.644  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:51:20.646   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:51:20.675  2372  2408 I art     : Explicit concurrent mark sweep GC freed 19616(1292KB) AllocSpace objects, 8(176KB) LOS objects, 40% free, 15MB/26MB, paused 2.002ms total 121.864ms
,07-05 12:51:20.684  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 312
07-05 12:51:20.684  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:51:20.685  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 312
07-05 12:51:20.685  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:51:20.685  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:51:20.686  1875  2041 D LEDHandler: Battery Temp: 312, mChargingStatus=5, mChargingStop=false
07-05 12:51:20.686  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:51:20.688  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:51:20.688  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:51:20.689  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:51:20.690   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:51:20.690   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:51:20.690   880  1315 D WifiController: battery changed pluggedType: 2
,07-05 12:51:20.742  5485  5485 I art     : Explicit concurrent mark sweep GC freed 28649(1932KB) AllocSpace objects, 17(275KB) LOS objects, 24% free, 17MB/23MB, paused 2.295ms total 172.385ms
,07-05 12:51:20.753  7492  7507 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
,07-05 12:51:20.753  7492  7507 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-05 12:51:20.769  7492  7507 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,07-05 12:51:20.772  7492  7507 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000003@DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk': Failed to open oat filename for reading: No such file or directory
07-05 12:51:20.774  7492  7507 D ChimeraFileApk: Classloading successful. Optimized code found.
07-05 12:51:20.778  7492  7507 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
07-05 12:51:20.789  2372  2670 E GCoreUlr: Bad errorId configuring silent feedback
,07-05 12:51:20.861   880  1726 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:20.905  7492  7507 D GoogleCertificatesImpl: Fetched 163 Google release certificates
07-05 12:51:20.908  7492  7507 D CAR.SERVICE: Package validated; name: com.android.vending
,07-05 12:51:20.910  7492  7507 D CAR.SERVICE: Android Auto doesn't have car home but we  have at least on alias in default or enabled state. Nothing to do.
07-05 12:51:20.911  2372  2670 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
07-05 12:51:20.926  2372  2670 I GCoreUlr: Unbound from all location providers
07-05 12:51:20.926  2372  2670 I GCoreUlr: Place inference reporting - stop
,07-05 12:51:20.939  2372  2372 I GCoreUlr: DispatchingService.onDestroy()
07-05 12:51:20.939  2372  2372 I GCoreUlr: Stopping handler for UlrDispSvcFast
07-05 12:51:20.945  2372  2372 I GCoreUlr: Unbound from all location providers
07-05 12:51:20.946  2372  2372 I GCoreUlr: Place inference reporting - stop
,07-05 12:51:20.951  7227  7489 I NotificationManager: com.android.vending: cancel(10436) by com.android.vending
07-05 12:51:20.961   880  1019 I NotificationManager: android: cancelAsUser(-1548111331) by android
,07-05 12:51:20.973  5421  6682 I art     : Explicit concurrent mark sweep GC freed 2903(116KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 401us total 41.760ms
,07-05 12:51:21.018  7227  7241 I art     : CheckpointMarkThreadRoots callback created = 0xb042dde0
,07-05 12:51:21.020   880  2170 I NotificationManager: android: cancelAsUser(2) by android
07-05 12:51:21.037  2372  7528 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-05 12:51:21.051  7227  7241 I art     : CheckpointMarkThreadRoots callback created = 0xb042ddd0
,07-05 12:51:21.120  5485  5537 V UdcCtxListenerSrv: handle intent
,07-05 12:51:21.183   880  1359 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:21.198  5485  7569 I CheckinChimeraService: Checking schedule, now: 1467715881198 next: 1468243127854
07-05 12:51:21.198  5485  7569 I CheckinChimeraService: active receiver: disabled
,07-05 12:51:21.238  5485  5485 I DynamiteModule: Considering local module com.google.android.gms.flags:0 and remote module com.google.android.gms.flags:1
07-05 12:51:21.238  5485  5485 I DynamiteModule: Selected remote version of com.google.android.gms.flags, version >= 1
,07-05 12:51:21.347  2372  7528 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,07-05 12:51:21.384   880  1019 I NotificationManager: android: cancelAsUser(1222422273) by android
,07-05 12:51:21.390  5485  5485 I art     : Explicit concurrent mark sweep GC freed 7706(386KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 17MB/23MB, paused 1.766ms total 98.982ms
,07-05 12:51:21.424  2372  2649 I GCoreUlr: DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,07-05 12:51:21.428  5421  5549 I art     : Explicit concurrent mark sweep GC freed 3004(117KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 472us total 26.564ms
07-05 12:51:21.431  2372  2649 I GCoreUlr: Unbound from all location providers
07-05 12:51:21.431  2372  2649 I GCoreUlr: Place inference reporting - stop
07-05 12:51:21.441  2372  2372 I GCoreUlr: DispatchingService.onDestroy()
07-05 12:51:21.441  2372  2372 I GCoreUlr: Stopping handler for UlrDispSvcFast
,07-05 12:51:21.446  2372  2372 I GCoreUlr: Unbound from all location providers
,07-05 12:51:21.446  2372  2372 I GCoreUlr: Place inference reporting - stop
07-05 12:51:21.471   880  1936 W ActivityManager: Unable to start service Intent { act=com.google.android.gms.measurement.REFRESH_ENABLED_STATE pkg=com.google.android.gms } U=0: not found
,07-05 12:51:21.516   880  1863 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:21.546  5485  5485 I CmaSystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
,07-05 12:51:21.554  5485  5485 I CmaSystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
07-05 12:51:21.599  5485  5485 D CmaSystemUpdateService: onCreate
07-05 12:51:21.599  5485  5485 D CmaSystemUpdateService: mProcessPackageEnabled: false, mAutomaticUpdateEnabled: false
,07-05 12:51:21.615  5485  5485 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) }
,07-05 12:51:21.630   880  1019 I NotificationManager: android: cancelAsUser(-591465577) by android
,07-05 12:51:21.647  5485  5485 I CmaSystemUpdateService: connectivity change: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
07-05 12:51:21.647  5485  5485 I CmaSystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-05 12:51:21.650  5485  7576 I SystemUpdateTask: cancelUpdate (empty URL)
07-05 12:51:21.650  5485  7576 I CmaSystemUpdateService: active receiver: disabled
07-05 12:51:21.665  5485  7576 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_available
,07-05 12:51:21.672  5485  7576 I NotificationManager: com.google.android.gms: cancel(2130838212) by com.google.android.gms
,07-05 12:51:21.674  5485  5485 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) }
07-05 12:51:21.674  5485  7576 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_download_failure
07-05 12:51:21.680  5485  7576 I NotificationManager: com.google.android.gms: cancel(2130838213) by com.google.android.gms
,07-05 12:51:21.684   880  2170 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:21.714  5485  7580 I SystemUpdateTask: cancelUpdate (empty URL)
,07-05 12:51:21.714  5485  7580 I CmaSystemUpdateService: active receiver: disabled
,07-05 12:51:21.720  5485  7580 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_available
07-05 12:51:21.720  5485  7580 I NotificationManager: com.google.android.gms: cancel(2130838212) by com.google.android.gms
07-05 12:51:21.720  5485  7580 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_download_failure
07-05 12:51:21.720  5485  7580 I NotificationManager: com.google.android.gms: cancel(2130838213) by com.google.android.gms
07-05 12:51:21.725  5485  5485 D CmaSystemUpdateService: onDestroy
07-05 12:51:21.790   880   880 D PowerManagerServiceEx: releaseWakeLockInternal: lock=2510306 [*alarm*], flags=0x0
,07-05 12:51:21.815  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:21.823  2020  4327 I GservicesUpdateTask: Updating Gservices keys
07-05 12:51:21.828   300   355 I ThermalEngine: Sensor:pa_therm0:35000 mC
07-05 12:51:21.831   880  2134 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:51:21.912   880   967 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7585 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:21.942  7391  7391 V LGMDMManager: Create singleton instance
,07-05 12:51:21.969   880   968 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:22.026  7585  7585 D UEI.SmartControl: Quickset Services start...
,07-05 12:51:22.032  7585  7585 I UEI.SmartControl: Manufacture = LGE
07-05 12:51:22.036  7585  7585 D UEI.SmartControl: File observer start...
07-05 12:51:22.038  7585  7585 E UEI.SmartControl: IR Port is disabled: false
,07-05 12:51:22.038  7585  7585 D UEI.SmartControl: Starting file observer...
07-05 12:51:22.038  7585  7585 D UEI.SmartControl: Extracting JNI libs...
07-05 12:51:22.040  7585  7585 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-05 12:51:22.045  7391  7391 I AudioManager: getMode name:com.lge.qremote
07-05 12:51:22.096   880  2028 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7604 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:22.217   880   968 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:22.305   880  1359 I ActivityManager: Process com.lge.qmemoplus (pid 7411) has died
,07-05 12:51:22.315  2020  2020 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-05 12:51:22.315  1789  1789 I PhoneApp: onTrimMemory: 10
07-05 12:51:22.316  1789  1789 I PhoneApp: trim memory
07-05 12:51:22.404   880  2192 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,07-05 12:51:22.408  7227  7227 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:22.408  7227  7227 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 12:51:22.439  7227  7227 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 12:51:22.507  7227  7227 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(590): Logging device features
,07-05 12:51:22.508  7585  7585 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-05 12:51:22.509  7585  7585 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-05 12:51:22.509  7585  7585 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-05 12:51:22.514  7604  7625 I Gmail   : getAccountsCursor
07-05 12:51:22.528  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:22.536   880  1288 V AlarmManager: RTC_WAKEUP set : Alarm{2a07a83e type 0 when 1467715882529 com.android.vending} when 1467715882529
07-05 12:51:22.556  7604  7604 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 12:51:22.563  7227  7227 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(57): Cancelling accelerated self-Update check
07-05 12:51:22.578  7585  7585 I UEI.SmartControl: --- Selecting new region: 2
07-05 12:51:22.578  7585  7585 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,07-05 12:51:22.588  7585  7585 D UEI.SmartControl: Platform has CIR...
07-05 12:51:22.591  7585  7585 D UEI.SmartControl: NO CIR support, need to check package...
,07-05 12:51:22.592  7585  7585 I UEI.SmartControl: Model: LG-D722 uses JNI
,07-05 12:51:22.595   880  2134 I ActivityManager: Process com.google.android.partnersetup (pid 7435) has died
07-05 12:51:22.595  7585  7585 D UEI.SmartControl: QS Service created
07-05 12:51:22.600  1789  1789 I PhoneApp: onTrimMemory: 15
07-05 12:51:22.600  1789  1789 I PhoneApp: trim memory
07-05 12:51:22.610  7227  7227 W InstanceID/Rpc: Found 10006
,07-05 12:51:22.640  7585  7585 E UEI.SmartControl: QS start get config
,07-05 12:51:22.658   880  2028 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.download.MusicCommunicator: pid=7633 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 12:51:22.660   880  1948 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,07-05 12:51:22.693  7585  7585 D UEI.SmartControl: Loading JNI Libs...
,07-05 12:51:22.695   880  1881 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
07-05 12:51:22.696  7585  7585 D UEI.SmartControl:  configuring local db...
07-05 12:51:22.699  7227  7227 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 10
07-05 12:51:22.716   880  1948 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,07-05 12:51:22.722  7227  7227 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 15
07-05 12:51:22.731  2372  2408 D DeviceConnectionService: client connected with version: 8486000
,07-05 12:51:22.745  7604  7653 I Gmail   : getAccountsCursor
,07-05 12:51:22.747  2372  2372 D WearableService: callingUid 10006, callindPid: 2372
07-05 12:51:22.749  7604  7651 E Gmail   : Error finding the version of the Email provider.....
07-05 12:51:22.749  7604  7651 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-05 12:51:22.749  7604  7651 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-05 12:51:22.749  7604  7651 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
07-05 12:51:22.749  7604  7651 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-05 12:51:22.749  7604  7651 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-05 12:51:22.749  7604  7651 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:51:22.749  7604  7651 E Gmail   : 	at android.os.Looper.loop(Looper.java:135)
07-05 12:51:22.749  7604  7651 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:51:22.750  7604  7651 W EmailMigration: We do not support migrating this version of the Email provider.
07-05 12:51:22.755  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:22.768  7604  7642 I Gmail   : Observing account changes for notifications
,07-05 12:51:22.785  7227  7227 E Finsky  : [1] com.google.android.finsky.wear.bk.a(752): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-05 12:51:22.786  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:22.791  7227  7227 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6355): Dropping command=hygiene due to Gms not connected
07-05 12:51:22.806  5485  6602 I CheckinService: Done disabling old GoogleServicesFramework version
,07-05 12:51:22.905   880  2583 I ActivityManager: Process com.google.android.gms.unstable (pid 6854) has died
,07-05 12:51:22.926   880  1910 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:22.958  7633  7633 I MusicStore: Database version: 120
,07-05 12:51:22.974  7585  7585 D UEI.SmartControl:  ---- Has DB8: true
,07-05 12:51:22.982  7585  7585 D UEI.SmartControl: QS start statue = true Error code = 0
,07-05 12:51:22.982  7585  7585 D UEI.SmartControl: QS version = v2.7.11.1_RC1
07-05 12:51:22.983  7585  7585 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
07-05 12:51:22.984  7604  7657 I Gmail   : notifyAccountChanged
07-05 12:51:22.988  7604  7657 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
07-05 12:51:22.990  7585  7585 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,07-05 12:51:22.996  7604  7662 I Gmail   : getAccountsCursor
07-05 12:51:23.001  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:23.005  7604  7657 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 12:51:23.019  7604  7657 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 12:51:23.023  7604  7657 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 12:51:23.037  7585  7585 W irrc_jni: IRRCPlayer_nativeInit ++ 
,07-05 12:51:23.037  7585  7585 D irrcClient: IrrcClient ++ 
07-05 12:51:23.037  7585  7585 D irrcClient: getIrrcService ++ 
07-05 12:51:23.037  7585  7585 D irrcClient: getIrrcService -- 
07-05 12:51:23.038  7585  7585 D irrcClient: IrrcClient -- 
07-05 12:51:23.038  7585  7585 W irrc_jni: IRRCPlayer_nativeInit -- 
07-05 12:51:23.044  7585  7585 D UEI.SmartControl: Services init done
07-05 12:51:23.046  7585  7667 I UEI.SmartControl: Device manager: loading config....
07-05 12:51:23.052  7585  7667 D UEI.SmartControl: Config is loaded...
,07-05 12:51:23.076  7585  7666 D UEI.SmartControl:  ----- QS SDK is ready!!!
07-05 12:51:23.077  7585  7666 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-05 12:51:23.179   880  2134 I art     : Explicit concurrent mark sweep GC freed 27853(1295KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.523ms total 145.188ms
,07-05 12:51:23.182  7585  7585 D UEI.SmartControl: QS Service init finished
07-05 12:51:23.184  7585  7585 D UEI.SmartControl: QS Service version name: 0.1.73
07-05 12:51:23.185  7585  7585 D UEI.SmartControl: QS Service version code: 1073
07-05 12:51:23.186  7585  7585 D UEI.SmartControl: Service requested: Control
,07-05 12:51:23.188  7585  7585 D UEI.SmartControl: Service.onTrimMemory: 10
07-05 12:51:23.188  7585  7585 E UEI.SmartControl: Setup service releasing memory...
07-05 12:51:23.193   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:23.193   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-05 12:51:23.193   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:23.194  7585  7600 D UEI.SmartControl: -----IControl: 11
,07-05 12:51:23.196  7585  7600 D UEI.SmartControl: Caller: com.lge.qremote
07-05 12:51:23.197  7585  7600 D UEI.SmartControl: ------------ IControl registerCallback...
07-05 12:51:23.198  7585  7600 I UEI.SmartControl: Registering callback...
07-05 12:51:23.199  7633  7633 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-05 12:51:23.202  7585  7601 D UEI.SmartControl: -----IControl: 19
07-05 12:51:23.203  7585  7601 D UEI.SmartControl: Caller: com.lge.qremote
07-05 12:51:23.204  7585  7601 I UEI.SmartControl: Registering Services Ready callback...
07-05 12:51:23.205  7585  7601 I UEI.SmartControl: Notify client services are ready...
07-05 12:51:23.209  7585  7600 D UEI.SmartControl: -----IControl: 8
07-05 12:51:23.210  7585  7600 D UEI.SmartControl: Caller: com.lge.qremote
07-05 12:51:23.232  7585  7585 I art     : Explicit concurrent mark sweep GC freed 10549(753KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 392us total 42.990ms
07-05 12:51:23.233  7585  7585 D UEI.SmartControl: Service.onTrimMemory: 15
07-05 12:51:23.233  7585  7585 E UEI.SmartControl: Setup service releasing memory...
07-05 12:51:23.234  7585  7585 D UEI.SmartControl: Internal service binding...
,07-05 12:51:23.279  7604  7662 I Gmail   : getAccountsCursor
,07-05 12:51:23.283  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:51:23.350   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:23.350   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-05 12:51:23.350   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:23.350  7633  7633 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,07-05 12:51:23.353   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:23.353   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-05 12:51:23.353   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
,07-05 12:51:23.353  7633  7633 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-05 12:51:23.388  7633  7633 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:23.388  7633  7633 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 12:51:23.431  7633  7633 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 12:51:23.522  7633  7633 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-05 12:51:23.522  7633  7633 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8bce51d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 12:51:23.523  7633  7633 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 12:51:23.524  7633  7633 D AndroidMusic: GMSCore installation verified
,07-05 12:51:23.530  7633  7633 I ConfigStore: Config Database version: 1
,07-05 12:51:23.657  7633  7633 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
07-05 12:51:23.658  7633  7648 I art     : CheckpointMarkThreadRoots callback created = 0xaae192c0
,07-05 12:51:23.686  7633  7633 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 12:51:23.700  7633  7648 I art     : CheckpointMarkThreadRoots callback created = 0xaae192a0
,07-05 12:51:23.805  7633  7633 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 12:51:23.830  7633  7633 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-05 12:51:23.868   880  1881 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7684 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,07-05 12:51:23.871  7633  7633 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-05 12:51:23.892   309   309 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 24.585ms
,07-05 12:51:23.916   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 22.230ms
07-05 12:51:23.939   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 22.244ms
,07-05 12:51:23.961   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:23.961   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
07-05 12:51:23.961   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:51:23.961  7633  7681 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
,07-05 12:51:24.092  7633  7660 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,07-05 12:51:24.102  7633  7633 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
07-05 12:51:24.102  7633  7712 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
07-05 12:51:24.112  7684  7684 D PhoneMonitor: Register our PhoneStateListener
,07-05 12:51:24.142  7684  7684 V SetupWizard: Connected to Gservices successfully
,07-05 12:51:24.155  7684  7684 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,07-05 12:51:24.163  7684  7684 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-05 12:51:24.166  7684  7684 D TelephonyAutoProfiling: [parse] Load xml
07-05 12:51:24.180  7684  7684 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-05 12:51:24.180  7684  7684 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,07-05 12:51:24.186  2372  4162 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 12:51:24.194  7684  7684 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-05 12:51:24.231  7633  7633 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 12:51:24.231  7633  7725 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
07-05 12:51:24.250  7633  7721 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
07-05 12:51:24.250  7633  7721 I MusicLeanback: Stop autocaching.
,07-05 12:51:24.385   880  1863 I ActivityManager: Process com.google.android.talk (pid 6977) has died
,07-05 12:51:24.423   880  1936 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:24.459  5485  7726 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-05 12:51:24.460  5485  7726 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-05 12:51:24.491  2372  4672 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-05 12:51:24.576  7227  7732 I Finsky  : [855] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-05 12:51:24.576  7227  7227 I Finsky  : [1] com.google.android.vending.verifier.VerifyInstalledPackagesReceiver.onReceive(42): Verify installed apps requested
,07-05 12:51:24.585  7227  7283 I PlayCommon: [838] com.google.android.play.a.ak.a(33603): Starting to flush logs
,07-05 12:51:24.601  7391  7391 I AudioManager: getMode name:com.lge.qremote
07-05 12:51:24.601  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:51:24.606  7227  7733 I Finsky  : [856] com.google.android.vending.verifier.ac.a(103): Verifying installed packages
07-05 12:51:24.614   880  1062 I NotificationManager: android: cancelAsUser(2) by android
07-05 12:51:24.684  7391  7391 I AudioManager: getMode name:com.lge.qremote
,07-05 12:51:24.714  7391  7391 I AudioManager: getMode name:com.lge.qremote
,07-05 12:51:24.901  7227  7283 I PlayCommon: [838] com.google.android.play.a.ak.a(33613): Log flushed by 1 successful uploads
,07-05 12:51:24.912   880   968 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:25.698   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:51:25.698   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:51:25.698   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 192312815348; DSPS: 6400039; Offset : -3007067648
,07-05 12:51:25.872   880  1936 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:25.987  7492  7492 D CAR.SERVICE: onUnbind
07-05 12:51:25.988  7492  7492 D CAR.SERVICE: CSB onClientsDisconnected
,07-05 12:51:25.991  7492  7492 D CAR.SERVICE: tearDown
07-05 12:51:25.991  7492  7492 D CAR.SERVICE: tearDownCarState
07-05 12:51:25.992  7492  7492 D CAR.SERVICE: Skip, car not connected.
07-05 12:51:25.992  7492  7492 D CAR.SERVICE: tearDownClientState
07-05 12:51:25.994  7227  7252 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:25.994  7227  7252 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:51:25.998  7227  7252 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:51:25.998  7227  7252 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:25.998   282  1045 E BandwidthController: [LG DATA] No such appUid: 10036
07-05 12:51:25.998   282  1045 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-05 12:51:25.999   282  7750 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:51:25.999   282  7750 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:51:25.999   282  7750 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:51:25.999   282  7750 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:51:26.004  7492  7492 D CAR.SERVICE: requestStop
,07-05 12:51:26.006  7492  7492 D CAR.SERVICE: onDestroy
07-05 12:51:26.006  7492  7492 D CAR.SERVICE: tearDown
07-05 12:51:26.006  7492  7492 D CAR.SERVICE: tearDownCarState
07-05 12:51:26.006  7492  7492 D CAR.SERVICE: Skip, car not connected.
07-05 12:51:26.006  7492  7492 D CAR.SERVICE: tearDownClientState
07-05 12:51:26.006  7492  7492 D CAR.SERVICE: requestStop
07-05 12:51:26.018  7492  7492 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.CarCallService@29ba2739 that was originally bound here
07-05 12:51:26.018  7492  7492 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.CarCallService@29ba2739 that was originally bound here
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at irv.a(:com.google.android.gms:120)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at irv.a(:com.google.android.gms:137)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at com.google.android.gms.car.CarCallService.h(:com.google.android.gms:76)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at com.google.android.gms.car.CarCallService.<init>(:com.google.android.gms:64)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at fgl.i(:com.google.android.gms:551)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:163)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:160)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-05 12:51:26.018  7492  7492 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-05 12:51:26.019   880  1921 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@305b156c
,07-05 12:51:26.176   282  7750 D libc-netbsd: res_queryN name = xxxxx succeed
,07-05 12:51:26.192  7227  7252 I System.out: propertyValue:false
,07-05 12:51:26.741   880  1359 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:26.832   300   355 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-05 12:51:27.588  7604  7628 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 12:51:28.049  7585  7668 D UEI.SmartControl: Internal timer expired: 1
,07-05 12:51:28.514   880  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{249a1c58 type 2 when 195121 android} when 195121
,07-05 12:51:28.646  7633  7633 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 12:51:28.655  7633  7763 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
07-05 12:51:28.655  7633  7763 I MusicLeanback: Stop autocaching.
07-05 12:51:28.667  7633  7766 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 12:51:29.082  1372  1372 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-05 12:51:29.107  1911  1911 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,07-05 12:51:29.120   880  1290 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 12:51:29.195   880  1021 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7776 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
07-05 12:51:29.199  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-05 12:51:29.217   880   880 D administrator: Handling package changes for user 0
,07-05 12:51:29.225  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-05 12:51:29.229  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,07-05 12:51:29.327   880  1061 W PackageSettings: Skipping PackageSetting{3fac51fe com.example.hello/10317} due to missing metadata
,07-05 12:51:29.372  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
07-05 12:51:29.376  1949  1949 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,07-05 12:51:29.383  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
07-05 12:51:29.384  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
07-05 12:51:29.384  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
07-05 12:51:29.384  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
07-05 12:51:29.384  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
07-05 12:51:29.384  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
07-05 12:51:29.384  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
07-05 12:51:29.384  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
07-05 12:51:29.384  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
07-05 12:51:29.384  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
07-05 12:51:29.384  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
07-05 12:51:29.385  1372  1372 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
,07-05 12:51:29.385  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-05 12:51:29.396   880  1948 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 12:51:29.418  7776  7776 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-05 12:51:29.560   880   880 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-05 12:51:29.560   880   880 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-05 12:51:29.560   880   880 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,07-05 12:51:29.565   880   880 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
07-05 12:51:29.575   880   880 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,07-05 12:51:29.575   880   880 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1f8cfee1
07-05 12:51:29.621   880  1019 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 12:51:29.741   880  1019 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,07-05 12:51:29.785   880  1359 I ActivityManager: Process com.google.android.apps.plus (pid 7509) has died
,07-05 12:51:29.807  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,07-05 12:51:29.811  7776  7811 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-05 12:51:29.812  7776  7811 I Babel_SMS: MmsConfig.loadMmsSettings
07-05 12:51:29.817  7776  7811 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-05 12:51:29.817  7776  7811 I Babel_SMS: MmsConfig.loadFromDatabase
07-05 12:51:29.828  2372  2372 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-05 12:51:29.845   880  1019 D LocationProviderProxy: applying state to connected service
,07-05 12:51:29.887  7776  7811 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-05 12:51:29.887  7776  7811 I Babel_SMS: MmsConfig.loadFromResources
07-05 12:51:29.888  7776  7811 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-05 12:51:29.892  7776  7811 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-05 12:51:29.925  7776  7799 I art     : CheckpointMarkThreadRoots callback created = 0xb042d880
,07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
,07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
07-05 12:51:29.955  7776  7776 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
07-05 12:51:29.956  7776  7776 D SensorManager: found sensor: Motion Accel, handle=46
07-05 12:51:29.959  7776  7799 I art     : CheckpointMarkThreadRoots callback created = 0xaae47db0
07-05 12:51:30.023   880  1936 I art     : Explicit concurrent mark sweep GC freed 30744(1765KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.071ms total 158.339ms
,07-05 12:51:30.065  7776  7776 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:51:30.069  7776  7776 I Babel_Crash: startup - clean
07-05 12:51:30.083  7776  7822 I Babel   : deleted: false for 0
,07-05 12:51:30.153  7776  7776 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,07-05 12:51:30.159  7776  7776 W AudioCapabilities: Unsupported mime audio/adpcm
,07-05 12:51:30.161   880  1910 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7824 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
07-05 12:51:30.199  7776  7776 W AudioCapabilities: Unsupported mime audio/g726
,07-05 12:51:30.201  7776  7776 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-05 12:51:30.203  7776  7776 W AudioCapabilities: Unsupported mime audio/wma-voice
07-05 12:51:30.204  7776  7776 W VideoCapabilities: Unsupported mime video/mjpg
07-05 12:51:30.212  7776  7776 W VideoCapabilities: Unsupported mime video/theora
,07-05 12:51:30.239  7776  7776 W AudioCapabilities: Unsupported mime audio/evrc
07-05 12:51:30.241  7776  7776 W AudioCapabilities: Unsupported mime audio/qcelp
07-05 12:51:30.242  7776  7776 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 12:51:30.248  7776  7776 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-05 12:51:30.249  7776  7776 W AudioCapabilities: Unsupported mime audio/qcelp
07-05 12:51:30.250  7776  7776 W AudioCapabilities: Unsupported mime audio/evrc
07-05 12:51:30.276  7776  7776 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-05 12:51:30.298  7824  7824 I AppUp4:AppBoxCP: onCreate
07-05 12:51:30.301  7824  7824 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-05 12:51:30.307  7776  7776 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-05 12:51:30.315  7824  7824 I AppUp4:DB:  setFingerPrint start
07-05 12:51:30.315  7824  7824 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
07-05 12:51:30.316  7776  7776 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 12:51:30.318  7776  7776 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 12:51:30.319  7227  7252 D Volley  : [827] c.a: HTTP response for request=<[ ] https://safebrowsing.google.com/safebrowsing/clientreport/download-multi 0xc9395b26 NORMAL 5> [lifetime=4308], [size=84], [rc=200], [retryCount=0]
,07-05 12:51:30.324  7227  7227 I Finsky  : [1] com.google.android.vending.verifier.ac.b(136): Done verifying installed packages
07-05 12:51:30.325  7776  7776 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-05 12:51:30.327  7824  7824 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
07-05 12:51:30.327  7824  7824 I AppUp4:DB:  SDK version = 21
07-05 12:51:30.327  7824  7824 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-05 12:51:30.328  7824  7824 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-05 12:51:30.334  7776  7776 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 12:51:30.340  7824  7824 I AppUp4:CustModeStarterReceiver: onReceive
07-05 12:51:30.340  7824  7824 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
07-05 12:51:30.344  7824  7824 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@399fc23b
07-05 12:51:30.344  7824  7824 D AppUp4:CustFacade: isCustomizationCompleted : false
07-05 12:51:30.349  7824  7824 D AppUp4:CustFacade: isSimDevice : true
,07-05 12:51:30.350  7824  7824 D AppUp4:CustModeStarterReceiver: begin check event
07-05 12:51:30.351  7824  7824 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-05 12:51:30.352   880  1936 I ActivityManager: Killing 7469:com.google.android.configupdater/u0a3 (adj 15): empty #11
07-05 12:51:30.396   880  2028 W libprocessgroup: failed to open /acct/uid_10003/pid_7469/cgroup.procs: No such file or directory
,07-05 12:51:30.445   880  1921 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7845 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-05 12:51:30.469  7776  7776 I vclib   : onServiceConnected
,07-05 12:51:30.469  7776  7776 W Babel   : Attempted to change video mute state without an active call.
07-05 12:51:30.479  7776  7843 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
07-05 12:51:30.492  7776  7776 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:30.492  7776  7776 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 12:51:30.527  7845  7845 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:51:30.527  7845  7845 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-05 12:51:30.527  7845  7845 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,07-05 12:51:30.554  7776  7776 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 12:51:30.635  7776  7776 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-05 12:51:30.635  7776  7776 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 12:51:30.646  7776  7776 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,07-05 12:51:30.659  7845  7845 I AppConfig: Total System Memory = 906309632
,07-05 12:51:30.662  7845  7845 I GalleryUtils: Application Heap = 96 MB
07-05 12:51:30.672  7845  7845 I AppConfig: App Tier : NOT_DEF
,07-05 12:51:30.688  7845  7845 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,07-05 12:51:30.766   880  1863 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7866 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
07-05 12:51:30.767   880  1863 I ActivityManager: Killing 7684:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,07-05 12:51:30.799   880  1726 W libprocessgroup: failed to open /acct/uid_10038/pid_7684/cgroup.procs: No such file or directory
07-05 12:51:30.813  7866  7866 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 12:51:30.813  7866  7866 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-05 12:51:30.813  7866  7866 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-05 12:51:30.815  7866  7866 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-05 12:51:30.815  7866  7866 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-05 12:51:30.939  7866  7866 I SystemConfig: BUILD Country: EU
07-05 12:51:30.939  7866  7866 I SystemConfig: BUILD Operator: OPEN
,07-05 12:51:31.073   880  2134 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7892 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:31.075   880  2134 I ActivityManager: Killing 7227:com.android.vending/u0a36 (adj 15): empty #11
07-05 12:51:31.122   880  2192 W libprocessgroup: failed to open /acct/uid_10036/pid_7227/cgroup.procs: No such file or directory
,07-05 12:51:31.127  7866  7890 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-05 12:51:31.127  7866  7890 I SystemConfig: existFile = false
07-05 12:51:31.128  7866  7890 I SystemConfig: canReadFile = false
07-05 12:51:31.128  7866  7890 I SystemConfig: systemFeature RCS result false
07-05 12:51:31.128  7866  7890 D SystemConfig: refreshRcsSupport() :false
07-05 12:51:31.186  7892  7892 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-05 12:51:31.229  7892  7892 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-05 12:51:31.229  7892  7892 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-05 12:51:31.229  7892  7892 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-05 12:51:31.229  7892  7892 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-05 12:51:31.229  7892  7892 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,07-05 12:51:31.273   880  1910 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7909 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 12:51:31.274   880  1910 I ActivityManager: Killing 7604:com.google.android.gm/u0a53 (adj 15): empty #11
,07-05 12:51:31.316   880  1726 W libprocessgroup: failed to open /acct/uid_10053/pid_7604/cgroup.procs: No such file or directory
,07-05 12:51:31.523  7909  7909 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
,07-05 12:51:31.702  7909  7909 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(171): No need to run daily hygiene.
,07-05 12:51:31.723  7909  7909 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-05 12:51:31.723  7909  7909 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-05 12:51:31.728  7909  7909 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
07-05 12:51:31.746  7909  7909 I Finsky  : [1] com.google.android.finsky.utils.bk.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,07-05 12:51:31.777  3117  3311 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
,07-05 12:51:31.784  7909  7909 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1226): Installer kick - no action, not running yet
07-05 12:51:31.787  7909  7909 I Finsky  : [1] com.google.android.finsky.j.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-05 12:51:31.788  7909  7909 I Finsky  : [1] com.google.android.finsky.j.j.run(214): Finished loading 1 libraries.
07-05 12:51:31.792  3117  3311 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@20b5a985 on behalf of 7909
,07-05 12:51:31.820   880  1921 I ActivityManager: Killing 7492:com.google.android.gms:car/u0a6 (adj 15): empty #11
,07-05 12:51:31.840   300   355 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-05 12:51:31.877   880  2192 W libprocessgroup: failed to open /acct/uid_10006/pid_7492/cgroup.procs: No such file or directory
,07-05 12:51:31.889  5485  7960 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 12:51:31.929   880  2583 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7961 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:31.994  5485  7960 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 12:51:31.999  7909  7909 I Finsky  : [1] com.google.android.finsky.c.l.a(270): result=false type=4
,07-05 12:51:32.033  7909  7909 I Finsky  : [1] com.google.android.finsky.services.bc.a(1050): Restore complete with 0 success and 0 failed.
07-05 12:51:32.035  5485  5537 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,07-05 12:51:32.046  7961  7961 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 12:51:32.088  5485  7984 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 12:51:32.369  2020  7995 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-05 12:51:32.427  2020  7995 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 58 ms] updated apps [took 58 ms] 
,07-05 12:51:33.184  5485  5537 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,07-05 12:51:33.271  5485  5537 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,07-05 12:51:33.290  5485  5537 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,07-05 12:51:35.706   880  2028 I ActivityManager: Killing 7585:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,07-05 12:51:35.730  7391  7391 W System.err: android.os.DeadObjectException
,07-05 12:51:35.735  7391  7391 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-05 12:51:35.735  7391  7391 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-05 12:51:35.735  7391  7391 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-05 12:51:35.735  7391  7391 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
07-05 12:51:35.735  7391  7391 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
07-05 12:51:35.735  7391  7391 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
07-05 12:51:35.735  7391  7391 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 12:51:35.735  7391  7391 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 12:51:35.735  7391  7391 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 12:51:35.735  7391  7391 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-05 12:51:35.736  7391  7391 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:51:35.736  7391  7391 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:51:35.736  7391  7391 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-05 12:51:35.736  7391  7391 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-05 12:51:35.736  7391  7391 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-05 12:51:35.737  7391  7391 W System.err: android.os.DeadObjectException
07-05 12:51:35.737  7391  7391 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-05 12:51:35.737  7391  7391 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-05 12:51:35.738  7391  7391 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-05 12:51:35.738  7391  7391 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
07-05 12:51:35.738  7391  7391 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
07-05 12:51:35.738  7391  7391 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
07-05 12:51:35.738  7391  7391 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 12:51:35.738  7391  7391 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 12:51:35.738  7391  7391 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 12:51:35.738  7391  7391 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-05 12:51:35.738  7391  7391 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:51:35.738  7391  7391 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:51:35.738  7391  7391 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-05 12:51:35.738  7391  7391 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-05 12:51:35.738  7391  7391 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-05 12:51:35.741   880  1910 W libprocessgroup: failed to open /acct/uid_10089/pid_7585/cgroup.procs: No such file or directory
07-05 12:51:35.741   880  1910 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
07-05 12:51:35.796   880  2170 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=8004 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:51:35.920  8004  8004 D UEI.SmartControl: Quickset Services start...
,07-05 12:51:35.923  8004  8004 I UEI.SmartControl: Manufacture = LGE
,07-05 12:51:35.924  8004  8004 D UEI.SmartControl: File observer start...
07-05 12:51:35.926  8004  8004 E UEI.SmartControl: IR Port is disabled: false
07-05 12:51:35.926  8004  8004 D UEI.SmartControl: Starting file observer...
07-05 12:51:35.926  8004  8004 D UEI.SmartControl: Extracting JNI libs...
07-05 12:51:35.927  8004  8004 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-05 12:51:36.064  8004  8004 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,07-05 12:51:36.065  8004  8004 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,07-05 12:51:36.065  8004  8004 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-05 12:51:36.095  8004  8004 I UEI.SmartControl: --- Selecting new region: 2
07-05 12:51:36.095  8004  8004 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,07-05 12:51:36.099  8004  8004 D UEI.SmartControl: Platform has CIR...
07-05 12:51:36.100  8004  8004 D UEI.SmartControl: NO CIR support, need to check package...
07-05 12:51:36.101  8004  8004 I UEI.SmartControl: Model: LG-D722 uses JNI
07-05 12:51:36.103  8004  8004 D UEI.SmartControl: QS Service created
07-05 12:51:36.123  8004  8004 E UEI.SmartControl: QS start get config
,07-05 12:51:36.164  8004  8004 D UEI.SmartControl: Loading JNI Libs...
07-05 12:51:36.168  8004  8004 D UEI.SmartControl:  configuring local db...
,07-05 12:51:36.379  8004  8004 D UEI.SmartControl:  ---- Has DB8: true
07-05 12:51:36.389  8004  8004 D UEI.SmartControl: QS start statue = true Error code = 0
07-05 12:51:36.390  8004  8004 D UEI.SmartControl: QS version = v2.7.11.1_RC1
07-05 12:51:36.391  8004  8004 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,07-05 12:51:36.397  8004  8004 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
07-05 12:51:36.413  8004  8004 W irrc_jni: IRRCPlayer_nativeInit ++ 
,07-05 12:51:36.415  8004  8004 D irrcClient: IrrcClient ++ 
,07-05 12:51:36.415  8004  8004 D irrcClient: getIrrcService ++ 
07-05 12:51:36.415  8004  8004 D irrcClient: getIrrcService -- 
07-05 12:51:36.415  8004  8004 D irrcClient: IrrcClient -- 
07-05 12:51:36.416  8004  8004 W irrc_jni: IRRCPlayer_nativeInit -- 
07-05 12:51:36.421  8004  8004 D UEI.SmartControl: Services init done
07-05 12:51:36.425  8004  8004 D UEI.SmartControl: QS Service init finished
,07-05 12:51:36.428  8004  8004 D UEI.SmartControl: QS Service version name: 0.1.73
07-05 12:51:36.428  8004  8045 I UEI.SmartControl: Device manager: loading config....
07-05 12:51:36.429  8004  8004 D UEI.SmartControl: QS Service version code: 1073
07-05 12:51:36.430  8004  8004 D UEI.SmartControl: Service requested: Control
07-05 12:51:36.432  8004  8045 D UEI.SmartControl: Config is loaded...
07-05 12:51:36.462  8004  8044 D UEI.SmartControl:  ----- QS SDK is ready!!!
07-05 12:51:36.462  8004  8044 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-05 12:51:36.463  8004  8004 D UEI.SmartControl: Request IControl service: devices are loaded...
07-05 12:51:36.467   880  1910 I ActivityManager: Killing 7391:com.lge.qremote/u0a106 (adj 15): empty #11
07-05 12:51:36.481   880  2170 W libprocessgroup: failed to open /acct/uid_10106/pid_7391/cgroup.procs: No such file or directory
07-05 12:51:36.482  8004  8004 D UEI.SmartControl: Internal service binding...
,07-05 12:51:36.490   880  1288 V AlarmManager: RTC_WAKEUP set : Alarm{2f797e4 type 0 when 1467715896486 com.android.vending} when 1467715896486
07-05 12:51:36.493  7909  7946 I Finsky  : [931] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
07-05 12:51:36.616  7909  7946 I Finsky  : [931] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-05 12:51:36.620  7909  7909 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
07-05 12:51:36.845   300   355 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-05 12:51:38.109   880  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{120b544d type 2 when 204716 android} when 204716
,07-05 12:51:39.010   880  1726 I ActivityManager: Killing 7633:com.google.android.music:main/u0a81 (adj 15): empty #11
,07-05 12:51:39.046   880  1948 W libprocessgroup: failed to open /acct/uid_10081/pid_7633/cgroup.procs: No such file or directory
,07-05 12:51:41.425  8004  8046 D UEI.SmartControl: Internal timer expired: 1
,07-05 12:51:41.432  8004  8004 D UEI.SmartControl: Service.onUnbind: IControl
07-05 12:51:41.433  8004  8004 D UEI.SmartControl: Service.onDestroy
07-05 12:51:41.436  8004  8004 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@253914ed
07-05 12:51:41.436  8004  8004 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
07-05 12:51:41.436  8004  8004 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
07-05 12:51:41.436  8004  8004 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-05 12:51:41.437  8004  8004 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-05 12:51:41.437  8004  8004 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-05 12:51:41.437  8004  8004 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
07-05 12:51:41.437  8004  8004 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
07-05 12:51:41.437  8004  8004 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
07-05 12:51:41.437  8004  8004 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:51:41.437  8004  8004 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 12:51:41.437  8004  8004 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-05 12:51:41.437  8004  8004 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:51:41.438  8004  8004 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:51:41.438  8004  8004 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-05 12:51:41.438  8004  8004 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-05 12:51:41.438  8004  8004 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@253914ed
,07-05 12:51:41.443  8004  8004 D UEI.SmartControl: Shutdown IRRCPlayer... 
07-05 12:51:41.471  8004  8004 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
07-05 12:51:41.471  8004  8004 D irrcClient: ~IrrcClient ++ 
07-05 12:51:41.471  8004  8004 D irrcClient: ~IrrcClient -- 
07-05 12:51:41.471  8004  8004 W irrc_jni: IRRCPlayer_nativeFinalize -- 
07-05 12:51:41.471  8004  8004 D UEI.SmartControl: Blaster closed
07-05 12:51:41.471  8004  8004 D UEI.SmartControl: Blaster closed
07-05 12:51:41.471  8004  8004 D UEI.SmartControl: Shut down QS...
,07-05 12:51:41.475  8004  8004 D UEI.SmartControl: Stopped file observer...
07-05 12:51:41.477  8004  8004 I UEI.SmartControl: QS lib stop result = true
07-05 12:51:41.479  8004  8004 D UEI.SmartControl: QS shutdown complete
07-05 12:51:41.849   300   355 I ThermalEngine: Sensor:pa_therm0:35000 mC
,07-05 12:51:45.699   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:51:45.699   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:51:45.699   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 212314400549; DSPS: 7055451; Offset : -3007069178
,07-05 12:51:46.854   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 12:51:51.859   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 12:51:56.863   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 12:51:58.540   880  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{23108b02 type 2 when 225148 android} when 225148
,07-05 12:51:58.641   880  1019 I ActivityManager: Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=8052 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,07-05 12:51:58.735  5485  8082 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
07-05 12:51:58.748   880  1019 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 198040, reason: UserStart, SyncResult: databaseError: true stats []
,07-05 12:51:58.749   880  1019 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 290003, reason: UserStart
07-05 12:51:58.751   880  1019 I NotificationManager: android: cancelAsUser(716319171) by android
07-05 12:51:59.317  8052  8052 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
07-05 12:51:59.317  8052  8052 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 12:51:59.317  8052  8052 I GAv4    :   adb logcat -s GAv4
,07-05 12:51:59.333  8052  8052 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 12:51:59.357  8052  8052 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 12:51:59.365  8052  8099 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-05 12:51:59.382  8052  8052 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,07-05 12:51:59.575   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:51:59.575   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
07-05 12:51:59.575   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
,07-05 12:51:59.578  8052  8104 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
07-05 12:51:59.595  8052  8105 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:59.596  8052  8052 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:51:59.596  8052  8052 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 12:51:59.601  8052  8105 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 12:51:59.619  8052  8075 I art     : CheckpointMarkThreadRoots callback created = 0xaaf2e0b0
,07-05 12:51:59.647  8052  8052 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 12:51:59.678  8052  8075 I art     : CheckpointMarkThreadRoots callback created = 0xaaf2e240
07-05 12:51:59.716  8052  8052 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 12:51:59.717  8052  8052 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 12:51:59.743   880   968 I ActivityManager: Killing 7824:com.lge.appbox.client/u0a11 (adj 15): empty #11
,07-05 12:51:59.745   880  1019 I NotificationManager: android: cancelAsUser(-1488629395) by android
,07-05 12:51:59.777   880  1359 W libprocessgroup: failed to open /acct/uid_10011/pid_7824/cgroup.procs: No such file or directory
,07-05 12:51:59.779  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:52:00.036  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:52:00.036  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 12:52:00.048  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:52:00.053  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:52:00.054  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:52:00.055  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:52:00.056  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:52:01.868   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 12:52:05.700   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:52:05.700   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:52:05.700   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 232315153874; DSPS: 7710836; Offset : -3007079028
,07-05 12:52:06.872   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-05 12:52:11.877   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:52:16.882   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:52:20.807   489   489 D charger_monitor: init target 500000
,07-05 12:52:20.814   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:52:20.818  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:52:20.820  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,07-05 12:52:20.823  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:52:20.823  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:52:20.823  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:52:20.858  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:52:20.861  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:52:20.862  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:52:20.862  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:52:20.862  1875  2041 D LEDHandler: Battery Temp: 312, mChargingStatus=5, mChargingStop=false
07-05 12:52:20.863  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:52:20.864  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 312
07-05 12:52:20.864  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:52:20.868   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:52:20.868   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:52:20.869   880  1315 D WifiController: battery changed pluggedType: 2
07-05 12:52:20.864  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 312
07-05 12:52:20.874  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-05 12:52:21.886   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:52:25.701   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:52:25.701   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:52:25.701   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 252315984909; DSPS: 8366223; Offset : -3007072436
,07-05 12:52:26.891   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:52:28.652   880  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=2510306, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=880
,07-05 12:52:28.656   880  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{265c75b9 type 2 when 255261 android} when 255261
07-05 12:52:28.683   880   880 D PowerManagerServiceEx: releaseWakeLockInternal: lock=2510306 [*alarm*], flags=0x0
,07-05 12:52:28.720   880  1936 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-05 12:52:28.776  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:52:28.779  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-05 12:52:29.356   880  1936 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:52:29.373  2372  6841 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-05 12:52:29.435   880  2134 I ActivityManager: Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=8162 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 12:52:29.650  8162  8190 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:52:29.650  8162  8190 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 12:52:29.720  8162  8190 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 12:52:29.783  8162  8190 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-05 12:52:29.784  8162  8190 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 12:52:29.914  8162  8199 D ChimeraCfgMgr: Reading stored module config
07-05 12:52:29.914  8162  8177 I art     : CheckpointMarkThreadRoots callback created = 0xb042dd00
,07-05 12:52:29.953  8162  8177 I art     : CheckpointMarkThreadRoots callback created = 0xb042dce0
,07-05 12:52:30.021  8162  8162 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-05 12:52:30.032  8162  8162 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:52:30.032  8162  8162 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:52:30.077   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:52:30.077   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
07-05 12:52:30.077   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
,07-05 12:52:30.078  8162  8162 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
07-05 12:52:30.142   880  1948 I art     : Explicit concurrent mark sweep GC freed 39480(1802KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.987ms total 156.472ms
,07-05 12:52:30.206  8162  8199 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
07-05 12:52:30.208  8162  8199 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000003@DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk': Failed to open oat filename for reading: No such file or directory
,07-05 12:52:30.215  8162  8199 D ChimeraFileApk: Classloading successful. Optimized code found.
07-05 12:52:30.238  8162  8199 D DynamitePackage: Instantiated singleton DynamitePackage.
,07-05 12:52:30.240  8162  8199 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
,07-05 12:52:30.325  8162  8162 I NotificationManager: com.google.android.youtube: cancel(2) by com.google.android.youtube
,07-05 12:52:30.354   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:52:30.354   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
07-05 12:52:30.354   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
,07-05 12:52:30.359  8162  8162 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
07-05 12:52:30.362   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:52:30.362   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
07-05 12:52:30.362   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:52:30.363  8162  8162 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
07-05 12:52:30.364   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:52:30.364   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
07-05 12:52:30.364   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:52:30.365  8162  8162 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
07-05 12:52:30.374  8162  8162 W InstanceID/Rpc: Found 10006
,07-05 12:52:30.425   246   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-05 12:52:30.425   246   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
07-05 12:52:30.425   246   364 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:52:30.426  8162  8162 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,07-05 12:52:30.569  8162  8250 I NotificationManager: com.google.android.youtube: cancel(10436) by com.google.android.youtube
,07-05 12:52:30.602  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:52:30.604  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:52:30.604  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:52:30.604  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:52:30.605   282  1045 E BandwidthController: [LG DATA] No such appUid: 10100
07-05 12:52:30.605   282  1045 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
07-05 12:52:30.605   282  8270 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:52:30.605   282  8270 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:52:30.606   282  8270 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:52:30.606   282  8270 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:52:30.606   282  8270 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:52:30.607  8162  8263 I System.out: propertyValue:false
07-05 12:52:30.607  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:52:30.607  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:52:30.628  2372  2372 I art     : Explicit concurrent mark sweep GC freed 61753(3MB) AllocSpace objects, 30(535KB) LOS objects, 40% free, 15MB/26MB, paused 2.252ms total 140.259ms
,07-05 12:52:30.649   880  1863 I ActivityManager: Killing 7776:com.google.android.talk/u0a61 (adj 15): empty #11
,07-05 12:52:30.745   880  2134 W libprocessgroup: failed to open /acct/uid_10061/pid_7776/cgroup.procs: No such file or directory
,07-05 12:52:31.896   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:52:36.900   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:52:39.918  8162  8245 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:52:39.920  8162  8245 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:52:39.921  8162  8245 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:52:39.921  8162  8245 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:52:39.922   282  1045 E BandwidthController: [LG DATA] No such appUid: 10100
07-05 12:52:39.922   282  1045 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
07-05 12:52:39.922   282  8284 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:52:39.922   282  8284 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:52:39.923   282  8284 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:52:39.923   282  8284 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:52:39.964   282  8284 D libc-netbsd: res_queryN name = xxxxx succeed
,07-05 12:52:39.970  8162  8245 I System.out: propertyValue:false
07-05 12:52:39.971  8162  8245 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:52:39.971  8162  8245 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:52:40.026  8162  8245 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:52:40.026  8162  8245 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:52:41.905   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:52:45.702   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:52:45.702   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:52:45.702   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 272316733911; DSPS: 9021608; Offset : -3007086087
,07-05 12:52:46.909   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:52:51.914   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:52:56.918   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:53:00.053  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:53:00.053  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:53:00.053  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:53:00.058  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:53:00.058  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:53:00.059  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:53:00.059  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:53:01.923   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:53:05.702   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:53:05.702   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:53:05.702   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 292317481039; DSPS: 9676992; Offset : -3007070887
,07-05 12:53:06.928   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:53:11.932   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:53:16.446  2372  4197 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 12:53:16.937   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-05 12:53:20.959   489   489 D charger_monitor: init target 500000
,07-05 12:53:20.964   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:53:20.974  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:53:20.974  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:53:20.974  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:53:20.974  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:53:20.977  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:53:21.009  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:53:21.013  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
07-05 12:53:21.013  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:53:21.013  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:53:21.014  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:53:21.015  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:53:21.015  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:53:21.015  1875  2041 D LEDHandler: Battery Temp: 310, mChargingStatus=5, mChargingStop=false
07-05 12:53:21.015  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
07-05 12:53:21.018  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:53:21.021   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:53:21.021   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:53:21.025   880  1315 D WifiController: battery changed pluggedType: 2
07-05 12:53:21.942   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:53:25.703   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:53:25.703   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:53:25.703   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 312318241761; DSPS: 10332377; Offset : -3007073259
,07-05 12:53:26.946   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:53:31.951   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:53:36.955   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:53:41.960   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:53:45.704   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:53:45.704   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:53:45.704   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 332318917639; DSPS: 10987760; Offset : -3007099313
,07-05 12:53:46.964   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:53:51.969   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:53:55.156   880  3154 I LocationManagerService: remove e670d9
,07-05 12:53:55.164   880  3154 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-05 12:53:55.164   880  3154 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-05 12:53:55.165   880  3154 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-05 12:53:55.165   880  3154 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-05 12:53:55.165   880  3154 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-05 12:53:56.974   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:54:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:54:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:54:00.043  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:54:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:54:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:54:00.045  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:54:01.978   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:05.704   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:54:05.704   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:54:05.705   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 352319593672; DSPS: 11643142; Offset : -3007094640
,07-05 12:54:06.993   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:11.998   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:17.003   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:21.122   489   489 D charger_monitor: init target 500000
,07-05 12:54:21.129  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:54:21.129  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:54:21.130  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:54:21.130  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:54:21.130  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:54:21.131   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:54:21.172  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:54:21.176  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 309
07-05 12:54:21.177  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:54:21.177  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 309
07-05 12:54:21.178  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:54:21.178  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:54:21.179  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:54:21.179  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:54:21.179  1875  2041 D LEDHandler: Battery Temp: 309, mChargingStatus=5, mChargingStop=false
07-05 12:54:21.182  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:54:21.185   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:54:21.185   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:54:21.189   880  1315 D WifiController: battery changed pluggedType: 2
07-05 12:54:22.007   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:25.705   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:54:25.705   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:54:25.705   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 372320372884; DSPS: 12298527; Offset : -3007078497
,07-05 12:54:27.012   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:29.497  5485  5562 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 12:54:32.016   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:37.021   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:42.026   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:45.706   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:54:45.706   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:54:45.706   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 392321078189; DSPS: 12953910; Offset : -3007075071
,07-05 12:54:47.030   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:52.035   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:54:57.039   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:55:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:55:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:55:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:55:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:55:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:55:00.045  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:55:02.044   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:05.707   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:55:05.707   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:55:05.707   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 412321841306; DSPS: 13609295; Offset : -3007074867
,07-05 12:55:07.048   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:12.053   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:15.548  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:55:15.548  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:55:15.549  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:55:15.549  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:55:15.551  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:55:15.562   489   489 D charger_monitor: init target 500000
,07-05 12:55:15.568   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:55:15.602  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:55:15.605  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
07-05 12:55:15.605  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:55:15.606  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:55:15.607  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:55:15.607  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:55:15.607  1875  2041 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
07-05 12:55:15.608  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:55:15.609  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
07-05 12:55:15.610  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:55:15.614   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:55:15.614   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:55:15.618   880  1315 D WifiController: battery changed pluggedType: 2
07-05 12:55:15.653  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:55:15.657  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
07-05 12:55:15.657  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:55:15.657  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:55:15.659  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:55:15.659  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:55:15.659  1875  2041 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
07-05 12:55:15.660  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:55:15.660  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
07-05 12:55:15.663  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:55:15.666   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:55:15.667   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:55:15.670   880  1315 D WifiController: battery changed pluggedType: 2
07-05 12:55:17.058   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:21.279   489   489 D charger_monitor: init target 500000
,07-05 12:55:21.284   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:55:21.294  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:55:21.294  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:55:21.294  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:55:21.294  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:55:21.297  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:55:22.062   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:25.707   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:55:25.707   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:55:25.707   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 432322523069; DSPS: 14264678; Offset : -3007094800
,07-05 12:55:27.067   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:32.071   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:37.076   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:42.081   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:45.708   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:55:45.708   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:55:45.708   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 452323219833; DSPS: 14920060; Offset : -3007069552
,07-05 12:55:47.085   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:52.094   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:55:57.099   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:00.038  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:56:00.038  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:56:00.038  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:56:00.042  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:56:00.042  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:56:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:56:00.043  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:56:02.103   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:05.709   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:56:05.709   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:56:05.709   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 472323895971; DSPS: 15575443; Offset : -3007095214
,07-05 12:56:05.927  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:56:05.940  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:56:05.943  2372  2372 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 12:56:06.021  2372  6839 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:56:06.021  2372  6839 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:56:06.021  2372  6839 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:56:06.021  2372  6839 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:56:06.023   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:56:06.023   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:56:06.023   282  8325 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:56:06.024   282  8325 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:56:06.024   282  8325 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:56:06.024   282  8325 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:56:06.103   282  8325 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:56:06.104  2372  6839 I System.out: propertyValue:false
,07-05 12:56:06.223  2372  6839 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:56:06.223  2372  6839 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:56:06.619   880   968 I NotificationManager: android: cancelAsUser(2) by android
,07-05 12:56:06.638  2372  6839 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-05 12:56:06.647   880  1863 I NotificationManager: android: cancelAsUser(2) by android
07-05 12:56:06.693  5485  6822 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:56:06.694  5485  6822 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:56:06.694  5485  6822 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:56:06.694  5485  6822 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:56:06.695   282  1045 E BandwidthController: [LG DATA] No such appUid: 10006
07-05 12:56:06.695   282  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-05 12:56:06.697   282  8339 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:56:06.697   282  8339 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:56:06.697   282  8339 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:56:06.698   282  8339 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:56:06.698   282  8339 D libc-netbsd: res_queryN name = xxxxx succeed
07-05 12:56:06.699  5485  6822 I System.out: propertyValue:false
07-05 12:56:06.785  5485  6822 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:56:06.785  5485  6822 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:56:07.108   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:12.112   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:17.117   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:21.452   489   489 D charger_monitor: init target 500000
,07-05 12:56:21.457   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:56:21.466  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:56:21.466  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:56:21.466  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:56:21.466  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:56:21.469  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:56:21.503  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:56:21.507  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 306
07-05 12:56:21.507  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:56:21.507  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:56:21.508  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:56:21.508  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:56:21.509  1875  2041 D LEDHandler: Battery Temp: 306, mChargingStatus=5, mChargingStop=false
07-05 12:56:21.510  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:56:21.510  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 306
07-05 12:56:21.512  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:56:21.516   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:56:21.516   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:56:21.519   880  1315 D WifiController: battery changed pluggedType: 2
07-05 12:56:22.122   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:25.709   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:56:25.709   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:56:25.710   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 492324666901; DSPS: 16230828; Offset : -3007087564
,07-05 12:56:27.126   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:32.131   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:37.135   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:42.140   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:45.710   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:56:45.710   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:56:45.710   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 512325435799; DSPS: 16886213; Offset : -3007081604
,07-05 12:56:47.145   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:52.149   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:56:57.154   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:57:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:57:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:57:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:57:00.043  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:57:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:57:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:57:00.044  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:57:02.158   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:57:05.711   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:57:05.711   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:57:05.711   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 532326119229; DSPS: 17541595; Offset : -3007069431
,07-05 12:57:07.163   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:57:12.168   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:57:17.172   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:57:21.601   489   489 D charger_monitor: init target 500000
,07-05 12:57:21.607   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:57:21.608  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:57:21.608  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:57:21.608  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:57:21.608  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 12:57:21.614  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-05 12:57:21.651  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:57:21.653  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 305
07-05 12:57:21.654  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:57:21.654  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:57:21.656  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:57:21.656  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:57:21.656  1875  2041 D LEDHandler: Battery Temp: 305, mChargingStatus=5, mChargingStop=false
07-05 12:57:21.657  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:57:21.657  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 305
07-05 12:57:21.659  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:57:21.663   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:57:21.663   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:57:21.666   880  1315 D WifiController: battery changed pluggedType: 2
07-05 12:57:22.177   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:57:25.712   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:57:25.712   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:57:25.712   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 552326884117; DSPS: 18196981; Offset : -3007097922
,07-05 12:57:27.181   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:57:30.583  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:30.584  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:30.584  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:30.584  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-05 12:57:30.587   282  1045 E BandwidthController: [LG DATA] No such appUid: 10100
07-05 12:57:30.588   282  1045 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
07-05 12:57:30.588   282  8353 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-05 12:57:30.589   282  8353 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-05 12:57:30.589   282  8353 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-05 12:57:30.589   282  8353 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-05 12:57:30.630   282  8353 D libc-netbsd: res_queryN name = xxxxx succeed
,07-05 12:57:30.634  8162  8263 I System.out: propertyValue:false
07-05 12:57:30.634  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:30.634  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:30.901  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:30.901  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:30.901  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:57:30.904  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.055  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:57:31.058  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.059  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:31.059  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.214  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:57:31.217  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.218  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:31.218  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.367  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:57:31.370  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.370  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:31.370  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.518  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:31.518  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:57:31.522  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:31.522  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.675  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:31.675  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-05 12:57:31.678  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:31.678  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.829  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:57:31.832  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.832  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:31.832  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.981  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-05 12:57:31.982  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:31.985  8162  8263 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-05 12:57:31.986  8162  8263 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-05 12:57:32.186   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:57:37.191   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-05 12:57:42.195   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:57:45.713   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:57:45.713   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:57:45.713   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 572327646193; DSPS: 18852365; Offset : -3007068008
,07-05 12:57:47.200   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:57:52.204   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:57:57.209   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:00.038  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:58:00.038  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:58:00.038  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:58:00.042  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:58:00.042  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:58:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:58:00.044  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:58:02.214   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:05.713   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:58:05.713   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:58:05.713   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 592328387644; DSPS: 19507750; Offset : -3007089756
,07-05 12:58:06.647  2372  4197 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 12:58:07.218   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:12.223   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:17.227   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:21.759   489   489 D charger_monitor: init target 500000
,07-05 12:58:21.764   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:58:21.774  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:58:21.774  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:58:21.774  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:58:21.774  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:58:21.777  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:58:22.232   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:25.714   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:58:25.714   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:58:25.714   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 612329149771; DSPS: 20163135; Offset : -3007090516
,07-05 12:58:27.236   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:32.241   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:37.246   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:42.250   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:45.715   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:58:45.715   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:58:45.715   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 632329841118; DSPS: 20818517; Offset : -3007071025
,07-05 12:58:47.255   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:52.259   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:58:57.264   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 12:59:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 12:59:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 12:59:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 12:59:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:59:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 12:59:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 12:59:02.269   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:05.716   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:59:05.716   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:59:05.716   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 652330929131; DSPS: 21473913; Offset : -3007081202
,07-05 12:59:07.273   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:12.278   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:17.282   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:21.919   489   489 D charger_monitor: init target 500000
,07-05 12:59:21.924   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 12:59:21.933  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 12:59:21.934  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 12:59:21.934  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 12:59:21.934  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 12:59:21.937  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 12:59:21.971  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:59:21.974  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 304
07-05 12:59:21.974  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 12:59:21.976  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 12:59:21.976  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 12:59:21.976  1875  2041 D LEDHandler: Battery Temp: 304, mChargingStatus=5, mChargingStop=false
07-05 12:59:21.976  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 12:59:21.977  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:59:21.978  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 304
07-05 12:59:21.980  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 12:59:21.983   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 12:59:21.983   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:59:21.987   880  1315 D WifiController: battery changed pluggedType: 2
07-05 12:59:22.287   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:25.716   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:59:25.716   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:59:25.717   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 672331608812; DSPS: 22129295; Offset : -3007073221
,07-05 12:59:27.291   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:32.296   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:37.301   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:42.305   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:45.717   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 12:59:45.717   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 12:59:45.717   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 692332370939; DSPS: 22784680; Offset : -3007073643
,07-05 12:59:47.310   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:52.314   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 12:59:57.319   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:00:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:00:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:00:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:00:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:00:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:00:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:00:02.324   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:05.718   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:00:05.718   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:00:05.718   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 712333111973; DSPS: 23440065; Offset : -3007095783
,07-05 13:00:07.328   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:12.333   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:17.337   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:22.102   489   489 D charger_monitor: init target 500000
,07-05 13:00:22.107   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:00:22.108  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:00:22.108  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:00:22.108  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:00:22.108  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 13:00:22.108  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:00:22.142  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 13:00:22.146  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 304
07-05 13:00:22.148  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 13:00:22.148  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 13:00:22.149  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 13:00:22.149  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 13:00:22.149  1875  2041 D LEDHandler: Battery Temp: 304, mChargingStatus=5, mChargingStop=false
07-05 13:00:22.150  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:00:22.150  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 304
07-05 13:00:22.155   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 13:00:22.155   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 13:00:22.159   880  1315 D WifiController: battery changed pluggedType: 2
07-05 13:00:22.159  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:00:22.342   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:25.719   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:00:25.719   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:00:25.719   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 732333878268; DSPS: 24095450; Offset : -3007092635
,07-05 13:00:27.346   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:32.351   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:37.356   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:42.360   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:45.719   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:00:45.719   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:00:45.720   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 752334539145; DSPS: 24750831; Offset : -3007072549
,07-05 13:00:47.365   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:52.369   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:00:57.374   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:01:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:01:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:01:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:01:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:01:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:01:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:01:02.378   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:05.720   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:01:05.720   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:01:05.720   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 772335225023; DSPS: 25406214; Offset : -3007088628
,07-05 13:01:07.383   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:12.388   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:17.392   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:22.250   489   489 D charger_monitor: init target 500000
,07-05 13:01:22.255   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:01:22.262  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:01:22.262  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:01:22.262  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:01:22.263  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 13:01:22.264  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-05 13:01:22.300  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 13:01:22.302  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 303
07-05 13:01:22.304  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 13:01:22.304  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 13:01:22.304  1875  2041 D LEDHandler: Battery Temp: 303, mChargingStatus=5, mChargingStop=false
07-05 13:01:22.304  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 13:01:22.304  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 13:01:22.306  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:01:22.307  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 303
07-05 13:01:22.308  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:01:22.312   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 13:01:22.312   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 13:01:22.316   880  1315 D WifiController: battery changed pluggedType: 2
07-05 13:01:22.397   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:25.721   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:01:25.721   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:01:25.721   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 792335982047; DSPS: 26061599; Offset : -3007094491
,07-05 13:01:27.401   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:32.406   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:37.410   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:42.415   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:45.722   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:01:45.722   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:01:45.722   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 812336744123; DSPS: 26716984; Offset : -3007095068
,07-05 13:01:47.420   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:52.424   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:01:57.429   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:02:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:02:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:02:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:02:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:02:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:02:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:02:02.433   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:05.722   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:02:05.722   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:02:05.722   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 832337431302; DSPS: 27372366; Offset : -3007079719
,07-05 13:02:07.438   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:12.442   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:17.447   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:22.399   489   489 D charger_monitor: init target 500000
,07-05 13:02:22.404   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:02:22.414  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:02:22.414  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:02:22.414  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:02:22.414  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 13:02:22.417  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:02:22.451   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:22.454  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
07-05 13:02:22.454  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:02:22.455  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 13:02:22.455  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 13:02:22.455  1875  2041 D LEDHandler: Battery Temp: 302, mChargingStatus=5, mChargingStop=false
07-05 13:02:22.456  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:02:22.457  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 13:02:22.457  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 13:02:22.458  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 302
07-05 13:02:22.460  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:02:22.464   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 13:02:22.464   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 13:02:22.468   880  1315 D WifiController: battery changed pluggedType: 2
07-05 13:02:25.723   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:02:25.723   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:02:25.723   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 852338176034; DSPS: 28027750; Offset : -3007067148
,07-05 13:02:27.456   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:32.461   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:37.465   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:42.470   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:45.724   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:02:45.724   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:02:45.724   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 872339005713; DSPS: 28683138; Offset : -3007092066
,07-05 13:02:47.474   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:52.479   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:02:57.483   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:03:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:03:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:03:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:03:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:03:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:03:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:03:02.488   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:05.725   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:03:05.725   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:03:05.725   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 892339740706; DSPS: 29338522; Offset : -3007089520
,07-05 13:03:07.493   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:12.497   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:17.502   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:22.506   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:22.561   489   489 D charger_monitor: init target 500000
,07-05 13:03:22.566   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:03:22.575  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:03:22.576  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:03:22.576  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:03:22.576  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 13:03:22.578  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:03:25.726   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:03:25.726   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:03:25.726   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 912340742678; DSPS: 29993915; Offset : -3007094186
,07-05 13:03:27.511   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:32.515   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:37.520   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:42.524   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:45.726   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:03:45.726   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:03:45.726   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 932341502409; DSPS: 30649300; Offset : -3007097550
,07-05 13:03:47.529   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:52.534   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:57.538   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:03:58.251   880  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=2510306, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=880
,07-05 13:03:58.257   880  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{7d7f196 type 2 when 944860 com.android.bluetooth} when 944860
07-05 13:03:58.485  2055  3411 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
,07-05 13:03:58.485  2055  3411 W bt-smp  : Plain text(LSB ~ MSB) = 04 4a 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-05 13:03:58.487  2055  3411 W bt-smp  : Encrypted text(LSB ~ MSB) = 9c 65 ac 9b fc 56 e4 0c cd 82 d5 df f0 9a 37 73 
07-05 13:03:58.487  2055  3411 W bt-btm  : Stopping oneshot timer
07-05 13:03:58.491   880  1863 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8404 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
07-05 13:03:58.530   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 436us total 36.097ms
,07-05 13:03:58.562   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 395us total 31.100ms
,07-05 13:03:58.594   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 409us total 30.792ms
,07-05 13:03:58.697  8404  8404 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-05 13:03:58.706  8404  8404 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@399fc23b
07-05 13:03:58.708   880  2192 I ActivityManager: Killing 7845:com.android.gallery3d/u0a23 (adj 15): empty #11
07-05 13:03:58.708   880   880 D PowerManagerServiceEx: releaseWakeLockInternal: lock=2510306 [*alarm*], flags=0x0
07-05 13:03:58.836   880  1359 W libprocessgroup: failed to open /acct/uid_10023/pid_7845/cgroup.procs: No such file or directory
,07-05 13:04:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:04:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-05 13:04:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
07-05 13:04:00.042  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:04:00.042  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:04:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:04:00.043  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:04:02.543   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:04:05.727   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:04:05.727   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:04:05.727   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 952342233132; DSPS: 31304683; Offset : -3007068757
,07-05 13:04:07.547   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:04:12.552   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:04:17.556   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:04:22.561   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:04:22.722   489   489 D charger_monitor: init target 500000
,07-05 13:04:22.727   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:04:22.728  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:04:22.729  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:04:22.729  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:04:22.729  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:04:22.729  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 13:04:22.767  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 13:04:22.768  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,07-05 13:04:22.772  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 13:04:22.772  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 13:04:22.772  1875  2041 D LEDHandler: Battery Temp: 301, mChargingStatus=5, mChargingStop=false
07-05 13:04:22.773  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:04:22.774  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 301
07-05 13:04:22.774  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:04:22.774  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 301
07-05 13:04:22.777  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:04:22.780   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 13:04:22.780   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 13:04:22.784   880  1315 D WifiController: battery changed pluggedType: 2
07-05 13:04:25.728   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:04:25.728   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:04:25.728   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 972342922967; DSPS: 31960066; Offset : -3007081061
,07-05 13:04:27.566   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:04:32.570   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:04:37.575   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:04:42.579   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:04:45.728   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:04:45.729   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:04:45.729   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 992343697596; DSPS: 32615451; Offset : -3007069189
,07-05 13:04:47.584   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:04:52.588   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:04:57.593   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:00.036  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:05:00.036  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:05:00.036  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:05:00.040  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:05:00.040  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:05:00.041  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:05:00.042  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:05:02.598   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:05.729   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:05:05.729   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:05:05.729   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1012344450504; DSPS: 33270836; Offset : -3007079247
,07-05 13:05:07.602   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:12.607   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:17.611   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:22.616   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:22.882   489   489 D charger_monitor: init target 500000
,07-05 13:05:22.887   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:05:22.888  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:05:22.888  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:05:22.888  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:05:22.888  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 13:05:22.889  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:05:25.730   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:05:25.730   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:05:25.730   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1032345228830; DSPS: 33926222; Offset : -3007094170
,07-05 13:05:27.620   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:32.625   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:37.630   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:42.634   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:45.731   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:05:45.731   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:05:45.731   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1052345984031; DSPS: 34581606; Offset : -3007071624
,07-05 13:05:47.639   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:52.643   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:05:57.648   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:06:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:06:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:06:00.043  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:06:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:06:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:06:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:06:02.653   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:05.732   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:06:05.732   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:06:05.732   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1072346742460; DSPS: 35236991; Offset : -3007076422
,07-05 13:06:07.657   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:12.664   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:17.668   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:22.673   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:23.039   489   489 D charger_monitor: init target 500000
,07-05 13:06:23.047  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:06:23.047  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:06:23.047  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:06:23.048  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 13:06:23.048   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:06:23.054  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-05 13:06:23.091  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 13:06:23.094  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
07-05 13:06:23.095  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 13:06:23.095  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 13:06:23.095  1875  2041 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
07-05 13:06:23.096  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 13:06:23.096  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 13:06:23.097  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:06:23.098  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
07-05 13:06:23.100  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:06:23.103   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 13:06:23.103   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 13:06:23.107   880  1315 D WifiController: battery changed pluggedType: 2
07-05 13:06:25.732   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:06:25.732   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:06:25.732   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1092347520733; DSPS: 35892377; Offset : -3007091605
,07-05 13:06:27.678   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:32.682   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:37.687   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:42.691   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:45.733   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:06:45.733   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:06:45.733   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1112348280049; DSPS: 36547762; Offset : -3007095021
,07-05 13:06:47.696   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:52.700   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:06:57.705   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:07:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:07:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:07:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:07:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:07:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:07:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:07:02.710   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:05.734   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:07:05.734   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:07:05.734   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1132349058115; DSPS: 37203147; Offset : -3007080285
,07-05 13:07:07.714   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:12.719   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:17.723   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:22.728   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:23.202   489   489 D charger_monitor: init target 500000
,07-05 13:07:23.207   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:07:23.208  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:07:23.208  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:07:23.208  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:07:23.208  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 13:07:23.209  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:07:25.735   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:07:25.735   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:07:25.735   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1152349800868; DSPS: 37858531; Offset : -3007069251
,07-05 13:07:27.732   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:32.737   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:37.742   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:42.746   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:45.736   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:07:45.736   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:07:45.736   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1172350711016; DSPS: 38513921; Offset : -3007074760
,07-05 13:07:47.751   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:52.755   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:07:57.760   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:08:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:08:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:08:00.043  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:08:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:08:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:08:00.045  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:08:02.764   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:05.736   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:08:05.736   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:08:05.736   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1192351476582; DSPS: 39169306; Offset : -3007072317
,07-05 13:08:07.769   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:12.774   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:17.778   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:22.783   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:23.362   489   489 D charger_monitor: init target 500000
,07-05 13:08:23.367   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:08:23.368  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:08:23.368  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:08:23.368  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:08:23.368  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 13:08:23.368  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:08:25.737   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:08:25.737   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:08:25.737   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1212352165168; DSPS: 39824689; Offset : -3007085635
,07-05 13:08:27.787   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:32.792   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:37.500   880  1019 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 13:08:37.796   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:42.801   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:45.738   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:08:45.738   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:08:45.738   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1232352890785; DSPS: 40480073; Offset : -3007092049
,07-05 13:08:47.808   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:52.812   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:08:57.817   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:09:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:09:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:09:00.045  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:09:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:09:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:09:00.047  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:09:02.821   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:05.738   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:09:05.739   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:09:05.739   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1252353662809; DSPS: 41135458; Offset : -3007083563
,07-05 13:09:07.826   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:12.830   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:17.835   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:22.839   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:23.519   489   489 D charger_monitor: init target 500000
,07-05 13:09:23.524   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:09:23.533  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:09:23.533  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:09:23.534  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:09:23.534  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 13:09:23.536  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:09:25.739   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:09:25.739   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:09:25.739   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1272354415770; DSPS: 41790843; Offset : -3007094141
,07-05 13:09:27.844   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:32.849   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:37.853   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:42.858   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:45.740   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:09:45.740   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:09:45.740   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1292355103053; DSPS: 42446225; Offset : -3007077541
,07-05 13:09:47.862   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:52.867   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:09:57.871   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:00.041  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:10:00.041  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:10:00.041  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:10:00.046  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:10:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:10:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:10:00.047  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:10:02.876   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:05.741   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:10:05.741   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:10:05.741   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1312355859869; DSPS: 43101610; Offset : -3007083508
,07-05 13:10:07.881   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:12.885   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:17.890   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:22.894   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:23.681   489   489 D charger_monitor: init target 500000
,07-05 13:10:23.686   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:10:23.695  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:10:23.695  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:10:23.695  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:10:23.695  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 13:10:23.698  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:10:25.741   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:10:25.741   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:10:25.742   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1332356535642; DSPS: 43756992; Offset : -3007079669
,07-05 13:10:27.899   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:32.903   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:37.908   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:42.913   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:45.742   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:10:45.742   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:10:45.742   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1352357333969; DSPS: 44412378; Offset : -3007076023
,07-05 13:10:47.917   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:52.922   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:10:57.926   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:11:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:11:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:11:00.043  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:11:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:11:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:11:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:11:02.931   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:05.743   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:11:05.743   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:11:05.743   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1372358004742; DSPS: 45067760; Offset : -3007075099
,07-05 13:11:07.935   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:12.940   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:17.945   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:22.949   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:23.839   489   489 D charger_monitor: init target 500000
,07-05 13:11:23.845   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:11:23.854  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:11:23.854  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:11:23.854  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:11:23.854  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-05 13:11:23.857  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:11:23.891  2055  3355 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 13:11:23.894  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
07-05 13:11:23.895  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-05 13:11:23.895  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-05 13:11:23.896  1875  2041 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-05 13:11:23.896  1875  2041 D LEDHandler: Battery Level Remaining: 100%
07-05 13:11:23.897  1875  2041 D LEDHandler: Battery Temp: 299, mChargingStatus=5, mChargingStop=false
07-05 13:11:23.898  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:11:23.898  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
07-05 13:11:23.900  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-05 13:11:23.904   880   880 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-05 13:11:23.904   880   880 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 13:11:23.907   880  1315 D WifiController: battery changed pluggedType: 2
07-05 13:11:25.744   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:11:25.744   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:11:25.744   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1392358742703; DSPS: 45723144; Offset : -3007069743
,07-05 13:11:27.954   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:32.958   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:37.963   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:42.967   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:45.745   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:11:45.745   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:11:45.745   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1412359515560; DSPS: 46378530; Offset : -3007089900
,07-05 13:11:47.972   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:52.976   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:11:57.981   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:12:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:12:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:12:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:12:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:12:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:12:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:12:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:12:02.986   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:12:05.745   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:12:05.745   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:12:05.745   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1432360231230; DSPS: 47033913; Offset : -3007076238
,07-05 13:12:07.990   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:12:12.995   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:12:17.999   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-05 13:12:23.004   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:12:24.002   489   489 D charger_monitor: init target 500000
,07-05 13:12:24.007   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:12:24.008  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:12:24.008  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:12:24.008  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:12:24.008  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 13:12:24.008  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:12:25.746   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:12:25.746   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:12:25.746   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1452360923618; DSPS: 47689296; Offset : -3007086432
,07-05 13:12:28.008   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:12:33.013   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:12:38.018   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:12:43.022   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:12:45.746   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:12:45.746   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:12:45.747   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1472361650746; DSPS: 48344680; Offset : -3007090893
,07-05 13:12:48.027   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:12:53.031   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:12:58.036   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:13:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:13:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:13:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,07-05 13:13:00.043  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:13:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:13:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:13:00.045  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:13:03.040   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:13:05.747   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:13:05.747   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:13:05.747   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1492362399644; DSPS: 49000064; Offset : -3007074417
,07-05 13:13:08.045   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:13:13.049   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:13:18.054   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:13:23.059   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:13:24.162   489   489 D charger_monitor: init target 500000
,07-05 13:13:24.167   489   489 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-05 13:13:24.168  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-05 13:13:24.168  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-05 13:13:24.168  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-05 13:13:24.169  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
07-05 13:13:24.169  1875  1875 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-05 13:13:25.748   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:13:25.748   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:13:25.748   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1512363093282; DSPS: 49655447; Offset : -3007083725
,07-05 13:13:28.063   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:13:33.068   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:13:38.072   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:13:43.077   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:13:45.749   880   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-05 13:13:45.749   880   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-05 13:13:45.749   880   985 D sensors_hal_Time: tsOffsetIs: Apps: 1532363797442; DSPS: 50310830; Offset : -3007080531
,07-05 13:13:48.081   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-05 13:13:53.086   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),07-05 13:13:58.090   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
07-05 13:13:58.507  8516  8516 D AndroidRuntime: 
07-05 13:13:58.507  8516  8516 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 13:13:58.525  8516  8516 D AndroidRuntime: CheckJNI is OFF
07-05 13:13:58.896  8516  8516 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 13:13:58.950   880  1021 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
07-05 13:13:58.951   880  1021 I ActivityManager: Killing 5852:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
07-05 13:13:59.007   880  1948 I WindowState: WIN DEATH: Window{19fd14f9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 13:13:59.090   880  1948 D InputDispatcher: Focus left window: Window{19fd14f9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 13:13:59.091   880  1948 D InputDispatcher: Window went away: Window{19fd14f9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 13:13:59.097   880  1021 I ActivityManager:   Force finishing activity ActivityRecord{349b8fc7 u0 com.test.thalitest/.MainActivity t241}
07-05 13:13:59.120   880  1061 W PackageSettings: Skipping PackageSetting{3fac51fe com.example.hello/10317} due to missing metadata
07-05 13:13:59.184   880   880 V ActivityManager: Display changed displayId=0
07-05 13:13:59.195  1789  1789 D DSDPConnection: Display #0 changed.
07-05 13:13:59.220   880  1359 W ActivityManager: Spurious death for ProcessRecord{1291c117 5852:com.test.thalitest/u0a30}, curProc for 5852: null
07-05 13:13:59.226   880  1061 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
07-05 13:13:59.226  1949  1949 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
07-05 13:13:59.255  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-05 13:13:59.278  2372  2699 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 13:13:59.282   880  1290 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 13:13:59.315  3461  3461 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 13:13:59.321  1911  1911 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
07-05 13:13:59.321   880  1021 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8546 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-05 13:13:59.322  1949  1949 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
07-05 13:13:59.325  3461  3461 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-05 13:13:59.325  3461  3461 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-05 13:13:59.325  3461  3461 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
07-05 13:13:59.325  3461  3461 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 13:13:59.325  3461  3461 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 13:13:59.325  3461  3461 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-05 13:13:59.325  3461  3461 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-05 13:13:59.325  3461  3461 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 13:13:59.325  3461  3461 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 13:13:59.325  3461  3461 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-05 13:13:59.325  3461  3461 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-05 13:13:59.382  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-05 13:13:59.383  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
07-05 13:13:59.389  1949  2050 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
07-05 13:13:59.402  1949  1949 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-05 13:13:59.402  1372  1498 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-05 13:13:59.403  1372  1498 D KeyguardModel: createShortcutInfo...
07-05 13:13:59.404  1949  1949 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
07-05 13:13:59.404  2020  2020 I art     : Explicit concurrent mark sweep GC freed 15915(948KB) AllocSpace objects, 2(46KB) LOS objects, 40% free, 12MB/20MB, paused 1.174ms total 169.808ms
07-05 13:13:59.405  1949  1949 I Activity: Activity.onPostResume() called 
07-05 13:13:59.409  1372  1498 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-05 13:13:59.409  1372  1498 D KeyguardModel: createShortcutInfo...
07-05 13:13:59.426  1372  1498 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 13:13:59.427  1372  1498 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-05 13:13:59.438  1372  1498 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 13:13:59.445  1372  1498 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-05 13:13:59.445  1949  1949 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
07-05 13:13:59.455  1372  1498 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-05 13:13:59.455  1372  1498 D KeyguardModel: createShortcutInfo...
07-05 13:13:59.456  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-05 13:13:59.456  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-05 13:13:59.496  1372  1498 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-05 13:13:59.499  1372  1498 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 13:13:59.499  1372  1498 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-05 13:13:59.501  1372  1498 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-05 13:13:59.501  1372  1498 D KeyguardModel: createShortcutInfo...
07-05 13:13:59.512  1949  8565 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
07-05 13:13:59.519   880  1052 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
07-05 13:13:59.519  5485  5485 I art     : Explicit concurrent mark sweep GC freed 27311(1476KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 17MB/23MB, paused 11.376ms total 277.007ms
07-05 13:13:59.521   880   880 I art     : Explicit concurrent mark sweep GC freed 34034(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 12.090ms total 271.592ms
07-05 13:13:59.522  1372  1498 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 13:13:59.522   880  1052 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
07-05 13:13:59.523   880  1061 I art     : WaitForGcToComplete blocked for 79.745ms for cause Explicit
07-05 13:13:59.524   880  1936 D InputDispatcher: Focus entered window: Window{12810241 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
07-05 13:13:59.525  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
07-05 13:13:59.525  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
07-05 13:13:59.525  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
07-05 13:13:59.525  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-05 13:13:59.525  1372  1498 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-05 13:13:59.525  1372  1498 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-05 13:13:59.545   880  1052 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-05 13:13:59.545   880  1052 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-05 13:13:59.549  1372  1498 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 13:13:59.549  1372  1498 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-05 13:13:59.550   880  1052 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 13:13:59.551   880  1052 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2e979e17,  pkg=WindowManager.LayoutParams
07-05 13:13:59.551   880  1052 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-05 13:13:59.551  1372  1498 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-05 13:13:59.552  1372  1498 D KeyguardModel: createShortcutInfo...
07-05 13:13:59.556  1949  2304 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-05 13:13:59.556  1949  2304 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 13:13:59.556  1949  2304 I Adreno-EGL: Build Date: 03/02/15 Mon
07-05 13:13:59.556  1949  2304 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-05 13:13:59.556  1949  2304 I Adreno-EGL: Remote Branch: 
07-05 13:13:59.556  1949  2304 I Adreno-EGL: Local Patches: 
07-05 13:13:59.556  1949  2304 I Adreno-EGL: Reconstruct Branch: 
07-05 13:13:59.557  1949  2304 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 13:13:59.561  1372  1372 D KeyguardModel: handleShortcutListChanged...
07-05 13:13:59.563  1372  1498 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-05 13:13:59.563  1372  1498 D KeyguardModel: createShortcutInfo...
07-05 13:13:59.568  1372  1498 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-05 13:13:59.568  1372  1498 D KeyguardModel: createShortcutInfo...
07-05 13:13:59.569  1372  1498 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 13:13:59.569  1372  1498 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-05 13:13:59.571  1372  1498 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-05 13:13:59.571  1372  1498 D KeyguardModel: createShortcutInfo...
07-05 13:13:59.573  1372  1498 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 13:13:59.573  1372  1498 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-05 13:13:59.576  1372  1498 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-05 13:13:59.576  1372  1498 D KeyguardModel: createShortcutInfo...
07-05 13:13:59.578  1372  1498 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-05 13:13:59.578  1372  1498 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-05 13:13:59.580  1372  1498 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-05 13:13:59.580  1372  1498 D KeyguardModel: createShortcutInfo...
07-05 13:13:59.587  8546  8546 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 13:13:59.587  8546  8546 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-05 13:13:59.588  8546  8546 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-05 13:13:59.592  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 13:13:59.593  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 13:13:59.593  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
07-05 13:13:59.597  1372  1372 D KeyguardModel: handleShortcutListChanged...
07-05 13:13:59.612  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
07-05 13:13:59.613  1949  1949 I PhoneWindow: [setNavigationBarColor] color=0x 0
07-05 13:13:59.621   880  2583 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
07-05 13:13:59.622   880   880 D administrator: Handling package changes for user 0
07-05 13:13:59.625   880  2583 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5852 uid 10030
07-05 13:13:59.795  1949  1949 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
07-05 13:13:59.821  1949  1949 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
07-05 13:13:59.828   880  1054 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f5b5602 u0 com.lge.launcher2/.Launcher t240} time:1546443
07-05 13:13:59.854  2020  2020 I HotwordDetector: Closing mic
07-05 13:13:59.877  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
07-05 13:13:59.879  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-05 13:13:59.880  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-05 13:13:59.882  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
07-05 13:13:59.917  1949  1949 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
07-05 13:13:59.922  2020  2358 I HotwordRecognitionRnr: Stopping hotword detection.
07-05 13:13:59.929   880  1061 I art     : Explicit concurrent mark sweep GC freed 13009(1984KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 26.904ms total 403.219ms
07-05 13:13:59.960  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
07-05 13:13:59.961  1949  1949 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
07-05 13:13:59.961  1949  1949 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
07-05 13:13:59.976  1857  1857 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-05 13:13:59.976  1857  1857 D LCardEmulationManager: getDefaultRoute
07-05 13:14:00.009  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
07-05 13:14:00.013  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
07-05 13:14:00.013  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
07-05 13:14:00.014  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
07-05 13:14:00.018  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
07-05 13:14:00.020  8546  8546 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-05 13:14:00.028  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
07-05 13:14:00.028  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
07-05 13:14:00.032  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
07-05 13:14:00.033  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
07-05 13:14:00.033  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
07-05 13:14:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-05 13:14:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
07-05 13:14:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
07-05 13:14:00.040  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
07-05 13:14:00.040  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:14:00.041  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
07-05 13:14:00.042  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 13:14:00.044  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
07-05 13:14:00.046   880   880 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-05 13:14:00.046   880   880 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 13:14:00.050   880   880 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 13:14:00.052  8516  8516 D AndroidRuntime: Shutting down VM
07-05 13:14:00.054  1949  1949 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
07-05 13:14:00.055  8546  8546 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
07-05 13:14:00.059   880  1349 D TaskPersister: removeObsoleteFile: deleting file=241_task.xml
07-05 13:14:00.105   880  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8574 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
07-05 13:14:00.200  1949  1949 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
07-05 13:14:00.214   880  1062 I ActivityManager: Killing 7866:com.android.contacts/u0a18 (adj 15): empty #11
07-05 13:14:00.293  1949  1949 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-05 13:14:00.294  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
07-05 13:14:00.295  1949  1949 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
07-05 13:14:00.295  1949  1949 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
07-05 13:14:00.306   880  2170 W libprocessgroup: failed to open /acct/uid_10018/pid_7866/cgroup.procs: No such file or directory
07-05 13:14:00.452  8546  8546 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
07-05 13:14:00.482  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-05 13:14:00.485  1949  1949 I Choreographer: Skipped 39 frames!  The application may be doing too much work on its main thread.
07-05 13:14:00.491   880  2583 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8598 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
07-05 13:14:00.491   880  2583 I ActivityManager: Killing 7961:com.google.android.apps.plus/u0a86 (adj 15): empty #11
07-05 13:14:00.503  1949  1949 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
07-05 13:14:00.508  3461  3495 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
07-05 13:14:00.509  1949  1949 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: Error inserting f004=13 f005=8598 f002=1467717240507 f003=com.lge.appbox.client f006=10011
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:708)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2588)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3413)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
07-05 13:14:00.515  3461  3495 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3522)
07-05 13:14:00.518  1949  2184 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
07-05 13:14:00.518  1949  2184 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
07-05 13:14:00.520  1949  1949 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
07-05 13:14:00.522  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-05 13:14:00.525  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
07-05 13:14:00.527  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
07-05 13:14:00.528  1635  1635 E b       : Unable to connect to the editor to retrieve text... will retry later
07-05 13:14:00.529  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
07-05 13:14:00.531  1949  1949 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
07-05 13:14:00.534  1949  1949 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
07-05 13:14:00.534  1949  1949 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
07-05 13:14:00.536   880  1726 W libprocessgroup: failed to open /acct/uid_10086/pid_7961/cgroup.procs: No such file or directory

```
