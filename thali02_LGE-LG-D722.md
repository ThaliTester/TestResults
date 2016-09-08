#### Test 83627337315fde5_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
09-08 14:31:25.731   293   349 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-08 14:31:28.247  5716  5716 D AndroidRuntime: 
09-08 14:31:28.247  5716  5716 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-08 14:31:28.254  5716  5716 D AndroidRuntime: CheckJNI is OFF
09-08 14:31:28.480  5716  5716 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 14:31:28.507   971  1383 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 14:31:28.562   971  1383 D ActivityManager: setTaskToReturnTo : TaskRecord{11aeb814 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-08 14:31:28.565   971  1383 D ActivityManager: setTaskToReturnTo : TaskRecord{11aeb814 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-08 14:31:28.586   971  1383 D WindowStateEx: AppWindowTokenEx init.. 
09-08 14:31:28.606   971  1056 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-08 14:31:28.632   971  1383 D InputDispatcher: Focus left window: Window{3582038e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-08 14:31:28.634  1953  1953 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
09-08 14:31:28.634  5716  5716 D AndroidRuntime: Shutting down VM
09-08 14:31:28.638   971  1056 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-08 14:31:28.661   971  1056 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-08 14:31:28.661   971  1056 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-08 14:31:28.679   971  1056 D SplitWindow: check instance of lgWin Window{1c40f5ac u0 Starting com.test.thalitest}
09-08 14:31:28.714   971  1324 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5737 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-08 14:31:28.740  1953  1953 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
09-08 14:31:28.811   971  2043 I WindowStateAnimator: Starting window displayed
09-08 14:31:28.814  1953  1953 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
09-08 14:31:28.821   971  1054 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
09-08 14:31:28.823  2036  2036 I HotwordDetector: Closing mic
09-08 14:31:28.823   971  1054 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
09-08 14:31:28.827   971  1054 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-08 14:31:28.827   971  1054 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-08 14:31:28.828  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
09-08 14:31:28.831  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
09-08 14:31:28.831  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
09-08 14:31:28.831  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-08 14:31:28.836   971  1054 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-08 14:31:28.841   971  1054 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ac048f0,  pkg=WindowManager.LayoutParams
09-08 14:31:28.841   971  1054 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-08 14:31:28.859  2036  2527 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1cd2fae9
09-08 14:31:28.859  2036  2527 V AudioRecord: stop()
09-08 14:31:28.859  2036  2527 D AudioRecord: AudioRecord->stop()
09-08 14:31:28.860   279  1295 V AudioFlinger: RecordHandle::stop()
09-08 14:31:28.860   279  1295 V AudioFlinger: RecordThread::stop
09-08 14:31:28.864   279  1295 V AudioFlinger: Record stopped OK
09-08 14:31:28.866   279  1295 V AudioPolicyManager: stopInput() input 17
09-08 14:31:28.868   279  1295 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
09-08 14:31:28.869   279  1295 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
09-08 14:31:28.869   279  1139 V AudioPolicyService: AudioCommandThread() waking up
09-08 14:31:28.869   279  1139 V AudioPolicyService: AudioCommandThread() processing release audio patch
09-08 14:31:28.869   279  1139 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
09-08 14:31:28.870   279  1139 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
09-08 14:31:28.870   279  1139 V AudioFlinger: ThreadBase::setParameters() routing=0
09-08 14:31:28.874   279  2542 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
09-08 14:31:28.916   279  2542 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
09-08 14:31:28.916   279  2542 V audio_hw_primary: disable_audio_route: enter: usecase(7)
09-08 14:31:28.916   279  2542 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
09-08 14:31:28.916   279  2542 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-08 14:31:28.920   279  2542 V audio_hw_primary: disable_audio_route: exit
09-08 14:31:28.920   279  2542 E audio_hw_primary: disable_snd_device: enter 144
09-08 14:31:28.920   279  2542 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
09-08 14:31:28.920   279  2542 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
09-08 14:31:28.924   279  2542 V audio_hw_primary: stop_input_stream: exit: status(0)
09-08 14:31:28.924   279  2542 V audio_hw_primary: in_standby: exit:  status(0)
09-08 14:31:28.924   279  2542 V AudioFlinger: RecordThread: loop stopping
09-08 14:31:28.925   279  1139 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-08 14:31:28.925   279  2542 V AudioFlinger: RecordThread: loop starting
09-08 14:31:28.925   279  2542 V AudioFlinger: processConfigEvents_l() remaining events 1
09-08 14:31:28.925   279  2542 V AudioFlinger: processConfigEvents_l() DONE thread 0xb385b000
09-08 14:31:28.925   279  2542 V AudioFlinger: RecordThread: loop stopping
09-08 14:31:28.925   279  1139 V AudioPolicyService: AudioCommandThread() going to sleep
09-08 14:31:28.925   279  1295 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
09-08 14:31:28.925   279  1295 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
09-08 14:31:28.925   279  1295 V AudioPolicyService: AudioCommandThread() adding update audio patch list
09-08 14:31:28.925   279  1295 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
09-08 14:31:28.925   279  1140 V AudioPolicyService: AudioCommandThread() waking up
09-08 14:31:28.926   279  1140 V AudioPolicyService: AudioCommandThread() processing update audio patch list
09-08 14:31:28.926   279  1140 V AudioPolicyService: AudioCommandThread() going to sleep
09-08 14:31:28.927   279  1295 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
09-08 14:31:28.927   279  1295 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
09-08 14:31:28.928   279  1139 V AudioPolicyService: AudioCommandThread() waking up
09-08 14:31:28.928   279  1139 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
09-08 14:31:28.928   279  1139 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 279
09-08 14:31:28.928   279  1139 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
09-08 14:31:28.928   279  1139 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-08 14:31:28.928   279  2542 V AudioFlinger: RecordThread: loop starting
09-08 14:31:28.928   279  2542 V AudioFlinger: processConfigEvents_l() remaining events 1
09-08 14:31:28.928   279  2542 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
09-08 14:31:28.929   279  2542 V audio_hw_primary: in_set_parameters: exit: status(0)
09-08 14:31:28.929   279  2542 V AudioFlinger: processConfigEvents_l() DONE thread 0xb385b000
09-08 14:31:28.929   279  2542 V AudioFlinger: RecordThread: loop stopping
09-08 14:31:28.929   279  1139 V AudioPolicyService: AudioCommandThread() going to sleep
09-08 14:31:28.935  2036  2527 V AudioRecord: stop()
09-08 14:31:28.936  2036  2527 V AudioRecord: stop()
09-08 14:31:28.936  2036  2527 V AudioRecord: stop()
09-08 14:31:28.937   279  1610 V AudioFlinger: releasing 16 from 2036 for -1
09-08 14:31:28.937   279  1610 V AudioFlinger:  decremented refcount to 0
09-08 14:31:28.937   279  1610 V AudioFlinger: purging stale effects
09-08 14:31:28.938   279  1325 V AudioFlinger: RecordHandle::stop()
09-08 14:31:28.938   279  1325 V AudioFlinger: RecordThread::stop
09-08 14:31:28.938   279  1325 V AudioPolicyManager: releaseInput() 17
09-08 14:31:28.938   279  1325 V AudioPolicyManager: closeInput(17)
09-08 14:31:28.938   279  1325 V AudioFlinger: closeInput() 17
09-08 14:31:28.938   279  1325 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-08 14:31:28.938  1373  1804 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-08 14:31:28.938   279  1325 V AudioFlinger: ThreadBase::exit
09-08 14:31:28.938   279  2542 V AudioFlinger: RecordThread: loop starting
09-08 14:31:28.938  3073  3089 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-08 14:31:28.938  1758  1787 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-08 14:31:28.938   279  2542 V AudioFlinger: RecordThread 0xb385b000 exiting
09-08 14:31:28.938  2036  2055 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-08 14:31:28.939  2082  2102 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-08 14:31:28.939  2103  2126 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-08 14:31:28.939   971  1640 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-08 14:31:28.940   279  1325 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546e1a0)
09-08 14:31:28.940   279  1325 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
09-08 14:31:28.940   279  1325 V audio_hw_primary: in_standby: exit:  status(0)
09-08 14:31:28.940   279  1325 V AudioPolicyService: AudioCommandThread() adding update audio port list
09-08 14:31:28.940   279  1325 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
09-08 14:31:28.941   279  1325 V AudioPolicyManager: releaseInput() exit
09-08 14:31:28.941   279  1325 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
09-08 14:31:28.941   279  1325 V AudioFlinger: removeClient_l() pid 2036, calling pid 279
09-08 14:31:28.942   279  1140 V AudioPolicyService: AudioCommandThread() waking up
09-08 14:31:28.942   279  1140 V AudioPolicyService: AudioCommandThread() processing update audio port list
09-08 14:31:28.943   279  1140 V AudioPolicyService: AudioCommandThread() going to sleep
09-08 14:31:28.944  2036  2532 I HotwordRecognitionRnr: Stopping hotword detection.
09-08 14:31:28.957  2036  2539 I HotwordRecognitionRnr: Hotword detection finished
09-08 14:31:28.962  5737  5737 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-08 14:31:29.094  5737  5737 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
09-08 14:31:29.171  5737  5737 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 6492-6504)
09-08 14:31:29.171  5737  5737 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:31:29.210  5737  5737 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33117216}
09-08 14:31:29.212  5737  5737 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:31:29.217  5737  5737 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 14:31:29.236  5737  5737 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 14:31:29.241  5737  5737 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 14:31:29.245  5737  5737 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 14:31:29.306  5737  5776 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
09-08 14:31:29.330  5737  5737 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-08 14:31:29.341  5737  5737 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 14:31:29.341  5737  5737 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 14:31:29.343  5737  5737 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:31:29.343  5737  5737 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:31:29.343  5737  5737 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:31:29.343  5737  5737 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:31:29.343  5737  5737 I Adreno-EGL: Remote Branch: 
09-08 14:31:29.343  5737  5737 I Adreno-EGL: Local Patches: 
09-08 14:31:29.343  5737  5737 I Adreno-EGL: Reconstruct Branch: 
09-08 14:31:29.472   279  1295 V AudioPolicyService: registerClient() client 0xb4027040, uid 10030
09-08 14:31:29.512   971  1055 D BluetoothManagerService: Message: 20
09-08 14:31:29.515   971  1055 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b04f64f:true
09-08 14:31:29.517  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:29.623  5737  5737 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 14:31:29.633  5737  5737 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-08 14:31:29.642  5737  5737 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-08 14:31:29.644  5737  5737 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-08 14:31:29.644  5737  5737 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-08 14:31:29.658  5737  5737 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-08 14:31:29.665  5737  5737 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 14:31:29.665  5737  5737 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 14:31:29.716  5737  5737 I Activity: Activity.onPostResume() called 
,09-08 14:31:29.725  5737  5803 D OpenGLRenderer: Render dirty regions requested: true
09-08 14:31:29.725  5737  5803 I OpenGLRenderer: Initialized EGL, version 1.4
09-08 14:31:29.733  5737  5803 D OpenGLRenderer: Enabling debug mode 0
,09-08 14:31:29.748  5737  5737 D Atlas   : Validating map...
,09-08 14:31:29.752   971   990 D SplitWindow: check instance of lgWin Window{1336113f u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 14:31:29.766  5737  5785 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-08 14:31:29.801   971  1383 D InputDispatcher: Focus entered window: Window{1336113f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-08 14:31:29.865   971   988 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,09-08 14:31:29.872   971  1056 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s203ms
09-08 14:31:29.872   971  1056 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36f2a8bd u0 com.test.thalitest/.MainActivity t259} time:117206
09-08 14:31:29.892  5737  5737 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@fcf5320 time:117226
,09-08 14:31:30.015  5737  5737 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5737
,09-08 14:31:30.680  5737  5737 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 14:31:30.736   293   349 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-08 14:31:30.804  5737  5809 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426139904
,09-08 14:31:30.825  5737  5809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 14:31:30.825  5737  5809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 14:31:30.825  5737  5809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 14:31:30.825  5737  5809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 14:31:30.825  5737  5809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 14:31:30.825  5737  5809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b1ab24d added. We now have 1 listener(s)
09-08 14:31:30.834   971  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:30.839  5737  5809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,09-08 14:31:30.841  5737  5809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-08 14:31:30.842  5737  5809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:30.842  5737  5809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 14:31:30.848  5737  5809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b6dc450 added. We now have 1 listener(s)
09-08 14:31:30.848  5737  5809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:30.864  5737  5809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:30.864  5737  5809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 14:31:30.865  5737  5809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 14:31:30.865  5737  5809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-08 14:31:30.865  5737  5809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-08 14:31:30.869  5737  5809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:30.869   971   990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:30.870  5737  5809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
09-08 14:31:30.877  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:31:30.881  5737  5809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-08 14:31:30.881  5737  5809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:30.881  5737  5809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:30.881  5737  5809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:30.881  5737  5809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:30.881  5737  5809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:30.881  5737  5809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:30.881  5737  5809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:30.881  5737  5809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:30.881  5737  5809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 14:31:30.882  5737  5809 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:30.883  5737  5809 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 14:31:30.924  5737  5737 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 14:31:31.008  2103  2103 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19951
,09-08 14:31:31.059  5737  5751 I art     : CheckpointMarkThreadRoots callback created = 0x9ee517f0
,09-08 14:31:31.093  5737  5751 I art     : CheckpointMarkThreadRoots callback created = 0x9ee517c0
,09-08 14:31:31.683  5737  5825 W jxcore-log: Initializing JXcore engine
09-08 14:31:31.683  5737  5825 W jxcore-log: JXcore engine is ready
,09-08 14:31:31.738  5825  5825 W Thread-664: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5732]" dev="sockfs" ino=5732 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-08 14:31:31.738  5825  5825 W Thread-664: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 14:31:31.738  5825  5825 W Thread-664: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7425]" dev="sockfs" ino=7425 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-08 14:31:31.738  5825  5825 W Thread-664: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-08 14:31:31.738  5825  5825 W Thread-664: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-08 14:31:31.738  5825  5825 W Thread-664: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26940]" dev="sockfs" ino=26940 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-08 14:31:31.776  5737  5825 W jxcore-log: Starting JXcore engine
,09-08 14:31:31.918  5737  5825 W jxcore-log: Platform android
09-08 14:31:31.918  5737  5825 W jxcore-log: 
09-08 14:31:31.919  5737  5825 W jxcore-log: Process ARCH arm
09-08 14:31:31.919  5737  5825 W jxcore-log: 
,09-08 14:31:32.211  5737  5825 I jxcore-log: JXcore Cordova bridge is ready!
09-08 14:31:32.211  5737  5825 I jxcore-log: 
,09-08 14:31:32.211  5737  5825 W jxcore-log: JXcore engine is started
09-08 14:31:32.218  5737  5809 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-08 14:31:32.220  5737  5737 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-08 14:31:35.740   293   349 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-08 14:31:37.156   971  1974 I ActivityManager: Process com.google.android.apps.docs (pid 5489) has died
,09-08 14:31:38.896   971  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{27c60e type 2 when 120000 com.google.android.gms} when 120000
,09-08 14:31:38.898   971  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2c1bc82f type 2 when 121068 com.google.android.gms} when 121068
,09-08 14:31:39.197   971  1324 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:39.199   971  1317 D ConnectivityService: dumpNetworkRequest
,09-08 14:31:39.301  5434  5866 W DriveInitializer: Background init thread started
,09-08 14:31:39.354   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:31:39.354   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
,09-08 14:31:39.354   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:31:39.359  5434  5866 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,09-08 14:31:39.423  5434  5866 W DriveInitializer: Background init thread ended
,09-08 14:31:39.763  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-08 14:31:39.763  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-08 14:31:39.763  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-08 14:31:39.763  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-08 14:31:39.764  1861  1861 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-08 14:31:39.770   488   488 D charger_monitor: init target 500000
09-08 14:31:39.800  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 320
09-08 14:31:39.800  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-08 14:31:39.800  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 320
,09-08 14:31:39.804  2082  3307 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-08 14:31:39.804  1861  2047 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-08 14:31:39.804  1861  2047 D LEDHandler: Battery Level Remaining: 100%
09-08 14:31:39.805  1861  2047 D LEDHandler: Battery Temp: 320, mChargingStatus=5, mChargingStop=false
09-08 14:31:39.805  1914  1914 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-08 14:31:39.805  1914  1914 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-08 14:31:39.806  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-08 14:31:39.807   971  1316 D WifiController: battery changed pluggedType: 2
09-08 14:31:39.808  5594  5594 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-08 14:31:39.823   488   488 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-08 14:31:40.745   293   349 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-08 14:31:44.957   971  1003 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-08 14:31:44.957   971  1003 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-08 14:31:44.957   971  1003 D sensors_hal_Time: tsOffsetIs: Apps: 132290901464; DSPS: 4426491; Offset : -2806628343
,09-08 14:31:45.750   293   349 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-08 14:31:47.651  5737  5825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 14:31:47.651  5737  5825 I jxcore-log: 
09-08 14:31:47.654  5737  5825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 14:31:47.654  5737  5825 I jxcore-log: 
,09-08 14:31:47.659  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:47.660  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:47.660  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:47.660  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:47.660  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:47.660  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:47.660  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:47.660  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:47.660  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:47.662  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:47.663  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:47.666  5737  5825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 14:31:47.666  5737  5825 I jxcore-log: 
09-08 14:31:47.669  5737  5825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 14:31:47.669  5737  5825 I jxcore-log: 
,09-08 14:31:48.461  5737  5825 I jxcore-log: Unit Test app is loaded
09-08 14:31:48.461  5737  5825 I jxcore-log: 
,09-08 14:31:48.473  5737  5825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:31:48.473  5737  5825 I jxcore-log: 
,09-08 14:31:48.482  5737  5737 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-08 14:31:48.493   971  1901 D WifiServiceImplEx: setWifiEnabled: true pid=5737, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,09-08 14:31:48.499   971  1901 D WifiService: setWifiEnabled: true pid=5737, uid=10030
,09-08 14:31:48.526   971  1951 D WifiServiceImplEx: disconnect pid=5737, uid=10030, packageName=com.test.thalitest
09-08 14:31:48.527   971   990 D WifiServiceImplEx: reconnect pid=5737, uid=10030, packageName=com.test.thalitest
09-08 14:31:48.538  5737  5825 D executeNativeTests: Running unit tests
,09-08 14:31:48.541  5737  5825 D BluetoothAdapter: enable(): BT is already enabled..!
09-08 14:31:48.542   971  1640 D WifiServiceImplEx: setWifiEnabled: true pid=5737, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
09-08 14:31:48.542   971  1640 D WifiService: setWifiEnabled: true pid=5737, uid=10030
09-08 14:31:48.544   971  1316 D WifiController: Mismatch in the state 1
09-08 14:31:48.550   971  1309 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-08 14:31:48.551   971  1309 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
,09-08 14:31:48.558   971   971 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:31:48.559   971  1309 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
09-08 14:31:48.559   971  1309 E WifiHW  : band=b
09-08 14:31:48.559   971  1309 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
09-08 14:31:48.560   971   971 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:31:48.569   971   971 D Ulp_jni : JNI:system_update. Event-4
,09-08 14:31:48.573   274  1044 D SoftapController: Softap fwReload - Ok
09-08 14:31:48.590   971  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:48.590   971  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-08 14:31:48.596   274  1044 D CommandListener: Setting iface cfg
09-08 14:31:48.596   274  1044 D CommandListener: Trying to bring down wlan0
09-08 14:31:48.597   274  1044 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:31:48.604   971  1309 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-08 14:31:48.671  5881  5881 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 14:31:48.708   971  1309 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-08 14:31:48.715  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:48.737  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:48.738  5881  5881 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 14:31:48.738  5881  5881 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-08 14:31:48.754  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:48.75 DNS addrs= 0.0.0.0, 0.0.0.0, 
,09-08 14:31:48.764   971  1046 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5882 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
09-08 14:31:48.769  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
,09-08 14:31:48.777   971   971 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-08 14:31:48.807  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,09-08 14:31:48.814  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:48.814  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
09-08 14:31:48.817  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
,09-08 14:31:49.058  5882  5882 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:31:49.059  5882  5882 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-08 14:31:49.059  5882  5882 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 14:31:49.060  5882  5882 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 14:31:49.061  5882  5882 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-08 14:31:49.161  5882  5882 I IndexDatabaseHelper: Using schema version: 115
,09-08 14:31:49.163  5882  5882 I IndexDatabaseHelper: Index is fine
09-08 14:31:49.307  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:49.351  5882  5882 D WiFiOffLoadUpdatePriority: remove : truetruefalse
09-08 14:31:49.354  5882  5882 D WiFiOffLoadUpdatePriority: remove2
09-08 14:31:49.355  5882  5882 V WiFiOffLoadSharedPrefsUtils: save wifi state
09-08 14:31:49.355  5882  5882 V WiFiOffLoadSharedPrefsUtils: save remove
09-08 14:31:49.356  5882  5882 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
09-08 14:31:49.356  5882  5882 D WiFiOffLoadBroadcast: S: false, R: true
09-08 14:31:49.390   971  1951 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5910 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-08 14:31:49.509  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:31:49.512   971  1640 I ActivityManager: Killing 5400:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,09-08 14:31:49.548   971  2043 W libprocessgroup: failed to open /acct/uid_10069/pid_5400/cgroup.procs: No such file or directory
,09-08 14:31:49.834   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-08 14:31:49.837   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:31:49.863   971  1055 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-08 14:31:49.865   971  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:49.865   971  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:49.865   971  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:49.866   971  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:49.867   274  1039 E BandwidthController: [LG DATA] No such appUid: 1000
09-08 14:31:49.867   274  1039 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-08 14:31:49.867   274  5934 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
09-08 14:31:49.867   274  5934 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:49.867   274  5934 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
09-08 14:31:49.869   971  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-08 14:31:49.879  5881  5881 E wpa_supplicant: USIM:  scard_init function
09-08 14:31:49.879  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:31:49.879  5882  5882 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:31:49.879  5882  5882 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:31:49.879  5882  5882 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-08 14:31:49.882  5881  5881 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 14:31:49.882  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:31:49.883   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-08 14:31:49.884   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
09-08 14:31:49.885   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-08 14:31:49.887   971  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:49.887   971  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:49.888   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:49.888   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:49.909  5881  5881 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-08 14:31:49.918  5882  5882 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:31:49.918  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 14:31:49.918  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:31:49.918  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:31:49.918  5882  5882 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:31:49.918  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 14:31:49.921  5882  5882 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:31:49.928   971  1309 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
,09-08 14:31:49.932   971  1309 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-08 14:31:49.933   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:49.933   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:49.936  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:49.936  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:49.936 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:49.936  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
09-08 14:31:49.941  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:49.943  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:49.943  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:49.943  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:49.944   971   971 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-08 14:31:49.945  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:49.946  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-08 14:31:49.947  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:49.947  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:49.947  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:49.947  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:49.947  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:49.947  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:49.947  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:49.947  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:49.947   971  1315 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-08 14:31:49.949  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:49.950   971   971 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
09-08 14:31:49.950  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:31:49.953  5882  5882 D WiFiOffLoadUpdatePriority: remove : truetruetrue
09-08 14:31:49.954  5881  5881 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-08 14:31:49.970   971  1309 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 14:31:49.974   971  1309 D WifiStateMachine: enableVerboseLogging : level 2
09-08 14:31:49.978   971  1309 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:31:49.979   971  1309 D WifiNative-HAL: Setting external_sim to 1
09-08 14:31:49.979   971  1309 I WifiNative-HAL: startHal
09-08 14:31:49.979   971  1309 E wifi    : getStaticLongField sWifiHalHandle 0x9b5d48ec
09-08 14:31:49.980   971  1309 I WifiHAL : Initializing wifi
09-08 14:31:49.980   971  1309 I WifiHAL : Creating socket
09-08 14:31:49.982   971  1309 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-08 14:31:49.982   971  1309 D wifi    : Did set static halHandle = 0x9a004200
09-08 14:31:49.982  1861  1861 D WfdsService: Supplicant Connection state is changed : true
09-08 14:31:49.983   971  1309 D wifi    : halHandle = 0x9a004200, mVM = 0xb487c280, mCls = 0x501d8a
09-08 14:31:49.983   971  1309 E wifi    : getStaticLongField sWifiHalHandle 0x9b5d489c
09-08 14:31:49.983   971  1309 D wifi    : array field set
09-08 14:31:49.983   971  1309 I WifiNative-HAL: interface[0] = wlan0
09-08 14:31:49.983   971  1309 I WifiNative-HAL: interface[1] = p2p0
,09-08 14:31:49.984   971  1309 D wifi    : setting scan oui 0x9a0902c8
09-08 14:31:49.984   971  1309 D WifiHAL : Sending mac address OUI
09-08 14:31:49.984   971  1309 E WifiHAL : failed to set scanning mac OUI; result = -95
09-08 14:31:49.985   971  1309 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:31:49.985   971  1309 I WifiNative-HAL: startHal
09-08 14:31:49.985   971  1309 D wifi    : setting scan oui 0x9a0902c8
09-08 14:31:49.985   971  1309 D WifiHAL : Sending mac address OUI
09-08 14:31:49.985   971  1309 E WifiHAL : failed to set scanning mac OUI; result = -95
09-08 14:31:49.986   971  5941 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1711259136
09-08 14:31:49.986   971  5941 D wifi    : waitForHalEvents called, vm = 0xb487c280, obj = 0x501d8a, env = 0x90027fd0
09-08 14:31:49.986   971  5941 E wifi    : getStaticLongField sWifiHalHandle 0x9917db2c
09-08 14:31:49.988  1861  2153 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-08 14:31:49.988  1861  2153 D WfdsService: Set the WFDS Monitor: true
09-08 14:31:49.990  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:49.990   971   971 D WifiHS20: hidePasspointNotification off =false
09-08 14:31:49.992   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:31:49.992   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:31:49.992   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:49.994  1861  2153 D WfdsMonitor: WfdsMonitorThread create
,09-08 14:31:49.994  1861  2153 D WfdsMonitor: WFDS Monitor is created and started
09-08 14:31:49.994  1861  2153 D WfdsService: WiFi: Supplicant connection re-established
,09-08 14:31:49.997   971  1307 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:49.999   971  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:49.999   971  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:49.999   274  1044 D CommandListener: Setting iface cfg
09-08 14:31:49.999   274  1044 D CommandListener: Trying to bring up p2p0
09-08 14:31:50.000   971  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 14:31:50.000   971  1307 D LGWifiP2pService: P2pEnablingState
09-08 14:31:50.000   971  1307 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.000   971  1307 D LGWifiP2pService: P2p socket connection successful
09-08 14:31:50.000   971  1307 D LGWifiP2pService: P2pEnabledState
09-08 14:31:50.002  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:50.003   971  1307 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-08 14:31:50.003   971  1307 D LGWifiP2pService: before postfix = G3s-1
09-08 14:31:50.003   971  1307 D WifiServerServiceExt: postfix byte check : 5
09-08 14:31:50.004   971  1307 D LGWifiP2pService: after postfix = G3s-1
09-08 14:31:50.004  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:50.005  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:50.005  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:50.005  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
,09-08 14:31:50.008   971   971 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 14:31:50.008   971   971 D RttService: SCAN_AVAILABLE : 3
09-08 14:31:50.008   971  1332 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.008   971  1332 I WifiNative-HAL: startHal
09-08 14:31:50.008   971  1333 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.010  1861  5942 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-08 14:31:50.010   971  1332 D wifi    : getting scan capabilities on interface[0] = 0x9a0902c8
09-08 14:31:50.010   971  1307 D WifiNative-HAL: p2pGetDeviceAddress
09-08 14:31:50.010   971  1332 D WifiHAL : Creating message to get scan capablities; iface = 24
09-08 14:31:50.010   971  1332 D wifi    : failed to get capabilities : -95
09-08 14:31:50.010   971  1332 E WifiScanningService: could not get scan capabilities
09-08 14:31:50.011  1861  5942 E CtrlSupplicant: Succeed to open control connection
09-08 14:31:50.012  1861  5942 E CtrlSupplicant: Succeed to open monitor connection
09-08 14:31:50.012  1861  5942 D WfdsMonitor: Supplicant connection established
09-08 14:31:50.012  1861  2153 D WfdsService: Connected to the supplicant for wfds
09-08 14:31:50.013  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:50.012 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:50.015  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:50.015  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:50.015   971  1309 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
09-08 14:31:50.016   971  1307 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
09-08 14:31:50.016  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:31:50.017   971  1307 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
09-08 14:31:50.019  5614  5614 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:31:50.020  1861  1861 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-08 14:31:50.022   971  1309 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-08 14:31:50.026  1861  1861 D WfdsService: Update P2p Interface State: 3
09-08 14:31:50.047  5881  5881 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,09-08 14:31:50.048   971  1307 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-08 14:31:50.049   971  1307 D LGWifiP2pService: sending p2p connection changed broadcast
09-08 14:31:50.049   971  1309 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-08 14:31:50.049  5881  5881 E wpa_supplicant: disconnect_rssi_lvl: -100
09-08 14:31:50.051  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
09-08 14:31:50.051  1861  1861 D WfdsService: WifiP2pState is changed : true
09-08 14:31:50.051  1861  2153 D WfdsService: Receive the WFDS_ENABLE Method
09-08 14:31:50.051  1861  2153 D WfdsService: Set the WFDS Monitor: true
09-08 14:31:50.051  1861  2153 D WfdsService: Connected to the supplicant for wfds
09-08 14:31:50.051  1861  2153 D WfdsJNI : doCommand: WFDS_SET TRUE
09-08 14:31:50.052  5881  5881 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-08 14:31:50.052   971  1309 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
09-08 14:31:50.053  5881  5881 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
09-08 14:31:50.053  1861  2153 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
09-08 14:31:50.053  5881  5881 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
09-08 14:31:50.054   971  1307 D LGWifiP2pService: InactiveState
09-08 14:31:50.054  1861  2153 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
09-08 14:31:50.054  5881  5881 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
09-08 14:31:50.054   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.054   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.054  1861  2153 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
09-08 14:31:50.054   971  1307 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.054  1861  2153 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
09-08 14:31:50.054  1861  2153 D WfdsService: selectPreferredScanChannel [6]
09-08 14:31:50.054  1861  2153 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
09-08 14:31:50.054  1861  1861 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-08 14:31:50.055   971  1307 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.055   971  1307 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.055   971  1307 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.055   971   971 E WifiServerServiceExt: No p2p device connected
09-08 14:31:50.057  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:50.058  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:50.058  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:50.058 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:50.058  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:31:50.059   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:50.059   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:50.059   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_A,CTION [SCANNING]
09-08 14:31:50.060  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:50.061  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:50.061  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:50.061  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:50.061  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:50.061  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:50.061   971  1309 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
09-08 14:31:50.067  1861  1861 D WfdsService: isConnected: false
09-08 14:31:50.068   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.068   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.071   971  1307 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.072  1861  1861 D WfdsService: GroupInfoAvailable: mGroupInfo is null
09-08 14:31:50.073   971  1307 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.073   971  1307 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.073   971  1307 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.074  1861  2153 W WfdsService: DefaultState - msg [9441285] is not handled
09-08 14:31:50.097  5881  5881 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-08 14:31:50.099  5881  5881 I wpa_supplicant: [LGE_PATCH]scan interval[0] = 2 sec.
09-08 14:31:50.100   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.100   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.100   971  1307 D LGWifiP2pService: DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:50.101  1861  5942 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
09-08 14:31:50.108  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:50.108  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 14:31:50.109  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:50.108 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:50.109  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:31:50.109   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:50.109   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:31:50.110   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:31:50.114  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:50.114  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:50.114  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:50.114  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:50.115  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:50.115  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:50.132  5881  5881 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-08 14:31:50.139   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:50.140   971   971 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 14:31:50.149  5882  5882 D WiFiOffLoadUpdatePriority: remove1
09-08 14:31:50.149  5882  5882 V WiFiOffLoadSharedPrefsUtils: save remove
,09-08 14:31:50.160   971   971 D LocSvc_java: onReceive
09-08 14:31:50.160   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:50.160   971   971 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-08 14:31:50.180  5882  5882 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
09-08 14:31:50.181  5882  5882 D WiFiOffLoadBroadcast: S: false, R: false
09-08 14:31:50.181  1758  1758 D GONS    : GONS isTestMode: false Country: 
,09-08 14:31:50.184  5882  5882 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
09-08 14:31:50.184  5882  5882 D WiFiOffLoadUpdatePriority: connected SSID: null
09-08 14:31:50.184  5882  5882 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
09-08 14:31:50.186   971  1640 D WifiServiceImplEx: addOrUpdateNetwork pid=5882, uid=1000, packageName=android.uid.system:1000
09-08 14:31:50.192   971  1640 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
,09-08 14:31:50.194   971  1309 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
09-08 14:31:50.254  5882  5882 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
09-08 14:31:50.254  5882  5882 D WiFiOffLoadUpdatePriority: configuration updated: 0
,09-08 14:31:50.255   971  1309 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
09-08 14:31:50.266  5882  5882 D WiFiOffLoadUpdatePriority: configuration saved: true
,09-08 14:31:50.268  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:50.314   971  1901 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5949 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-08 14:31:50.446  5949  5949 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:31:50.446  5949  5949 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-08 14:31:50.457  5949  5949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:31:50.459  5949  5949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,09-08 14:31:50.463  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:50.467  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:50.480  5949  5973 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-08 14:31:50.482  5949  5973 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:31:50.489  5910  5910 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:31:50.491  5949  5972 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:31:50.493  5910  5910 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:50.493  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:31:50.563   971  1383 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5978 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-08 14:31:50.587   314   314 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 25.040ms
,09-08 14:31:50.601   971   988 I ActivityManager: Process com.google.android.apps.plus (pid 5562) has died
,09-08 14:31:50.610   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 22.177ms
09-08 14:31:50.633   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.478ms
,09-08 14:31:50.677  5978  5978 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 14:31:50.755   293   349 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-08 14:31:50.793   971  1055 D BluetoothManagerService: Message: 20
09-08 14:31:50.793   971  1055 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29143ca5:true
,09-08 14:31:50.805  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:31:50.807  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:50.855  5594  5594 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-08 14:31:50.857  5594  5594 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-08 14:31:50.868  5594  5594 V [BNRBootReceiver]: Boot Receiver Return
,09-08 14:31:50.872  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:50.877  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:50.885  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:50.891  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:50.900  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-08 14:31:50.904  5882  5882 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-08 14:31:51.001  2103  2103 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,09-08 14:31:51.009  2103  2103 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
09-08 14:31:51.012   971  1900 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6000 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:31:51.040  5978  5978 V LGMDMManager: Create singleton instance
,09-08 14:31:51.100  6000  6000 D UEI.SmartControl: Quickset Services start...
,09-08 14:31:51.105  6000  6000 I UEI.SmartControl: Manufacture = LGE
09-08 14:31:51.108  6000  6000 D UEI.SmartControl: File observer start...
09-08 14:31:51.109  6000  6000 E UEI.SmartControl: IR Port is disabled: false
09-08 14:31:51.110  6000  6000 D UEI.SmartControl: Starting file observer...
09-08 14:31:51.110  6000  6000 D UEI.SmartControl: Extracting JNI libs...
09-08 14:31:51.110  6000  6000 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-08 14:31:51.138  5978  5978 I AudioManager: getMode name:com.lge.qremote
,09-08 14:31:51.146  6000  6000 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-08 14:31:51.147  6000  6000 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-08 14:31:51.147  6000  6000 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-08 14:31:51.183  6000  6000 I UEI.SmartControl: --- Selecting new region: 2
09-08 14:31:51.183  6000  6000 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,09-08 14:31:51.187  6000  6000 D UEI.SmartControl: Platform has CIR...
,09-08 14:31:51.189  6000  6000 D UEI.SmartControl: NO CIR support, need to check package...
09-08 14:31:51.189  6000  6000 I UEI.SmartControl: Model: LG-D722 uses JNI
09-08 14:31:51.192  6000  6000 D UEI.SmartControl: QS Service created
09-08 14:31:51.213  6000  6000 E UEI.SmartControl: QS start get config
,09-08 14:31:51.233   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-08 14:31:51.234  5881  5881 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz)
09-08 14:31:51.269   971   971 D LocSvc_java: onReceive
,09-08 14:31:51.274  6000  6000 D UEI.SmartControl: Loading JNI Libs...
09-08 14:31:51.275  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-08 14:31:51.278  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:51.279  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:51.279  6000  6000 D UEI.SmartControl:  configuring local db...
09-08 14:31:51.280  5882  5882 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-08 14:31:51.282  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:51.282 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:51.283  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:31:51.284  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:51.284  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:51.284  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:51.286  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:51.286  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:51.286  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:51.286   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:51.286   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:51.286   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:31:51.287   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:51.287   971   971 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-08 14:31:51.292  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:51.299  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:51.337   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:31:51.337   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:31:51.338   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-08 14:31:51.339  5881  5881 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-08 14:31:51.350  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 14:31:51.351   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:51.351   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:51.351   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:31:51.352  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:51.353  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:51.353 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:51.353  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:31:51.355  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:51.355  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:51.355  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:51.355  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:51.355  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:51.355  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:51.357  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:51.357  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:51.358  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:51.357 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:51.358  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:31:51.358   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:51.358   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:51.358   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-08 14:31:51.359   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:51.359   971   971 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-08 14:31:51.360   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:51.360   971   971 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-08 14:31:51.361  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:51.361  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:51.361  1373  1373 I [Sys,temUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:51.361  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:51.361  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:51.361  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:51.361  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:51.369  5881  5881 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:31:51.369  5881  5881 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 14:31:51.370   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:31:51.379   971  1309 I WifiServiceExtension: setVHTCapabilityType  : false
09-08 14:31:51.380  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:51.392  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:51.398  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:51.410   971  1309 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-08 14:31:51.410   971  1309 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
09-08 14:31:51.412   971  1309 I WifiServiceExtension: setSecurityType  : 2
,09-08 14:31:51.430  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,09-08 14:31:51.433   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:51.433   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:51.433   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 14:31:51.434  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:51.433 DNS addrs= 0.0.0.0, 0.0.0.0, 
,09-08 14:31:51.434  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:51.434  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:31:51.436  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:51.436  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:51.436  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:51.436  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:51.436  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:51.436  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:51.440  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:51.441  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:51.442  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:51.442 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:51.442  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:31:51.445   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:51.445   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:51.445   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 14:31:51.445  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:51.445  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:51.445  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:51.446  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:51.446  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:51.446  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:51.446  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:51.450  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 14:31:51.462  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:51.472   971  6028 D WifiExtManager: WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@db1821b
09-08 14:31:51.472   971  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-08 14:31:51.473  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:51.475   971  1317 D ConnectivityService: Got NetworkAgent Messenger
,09-08 14:31:51.477   971  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 14:31:51.481   971  1317 D ConnectivityService: NetworkAgent connected
09-08 14:31:51.484  1861  1885 D WifiServiceExtension: isInternetCheckAvailable return false
09-08 14:31:51.485   971  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:31:51.497   971  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:31:51.506   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
09-08 14:31:51.507   971  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:51.507   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:51.507   971  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:51.507   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:51.508   274  1044 D CommandListener: Setting iface cfg
09-08 14:31:51.513   971  6030 D DhcpStateMachine: StoppedState
09-08 14:31:51.513   971  1309 E WifiStateMachine: Start Dhcp Watchdog 1
09-08 14:31:51.513   971  6030 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:51.513   971  6030 D DhcpStateMachine: WaitBeforeStartState
,09-08 14:31:51.515   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:51.515   971   971 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-08 14:31:51.524  1914  1914 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
09-08 14:31:51.525  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-54 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:51.525 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:51.527  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,09-08 14:31:51.527  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:51.527  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:51.535   971  1317 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
09-08 14:31:51.578  6000  6000 D UEI.SmartControl:  ---- Has DB8: true
09-08 14:31:51.585  6000  6000 D UEI.SmartControl: QS start statue = true Error code = 0
,09-08 14:31:51.587  6000  6000 D UEI.SmartControl: QS version = v2.7.11.1_RC1
09-08 14:31:51.587  6000  6000 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
09-08 14:31:51.591  6000  6000 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
09-08 14:31:51.620  6000  6000 W irrc_jni: IRRCPlayer_nativeInit ++ 
09-08 14:31:51.620  6000  6000 D irrcClient: IrrcClient ++ 
09-08 14:31:51.620  6000  6000 D irrcClient: getIrrcService ++ 
,09-08 14:31:51.621  6000  6000 D irrcClient: getIrrcService -- 
09-08 14:31:51.621  6000  6000 D irrcClient: IrrcClient -- 
09-08 14:31:51.621  6000  6000 W irrc_jni: IRRCPlayer_nativeInit -- 
09-08 14:31:51.628  6000  6000 D UEI.SmartControl: Services init done
,09-08 14:31:51.634   971  1309 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-08 14:31:51.634   971  1309 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:31:51.635   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16bd96e8 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 14:31:51.635   971  1307 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16bd96e8 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:51.635   971  6030 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:51.636  6000  6032 I UEI.SmartControl: Device manager: loading config....
09-08 14:31:51.636   971  1309 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:31:51.636   971  1309 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
09-08 14:31:51.636   971  6030 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-08 14:31:51.637   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:51.637   971   971 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 14:31:51.637   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:51.637   971   971 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 14:31:51.639  6000  6000 D UEI.SmartControl: QS Service init finished
09-08 14:31:51.641  6000  6000 D UEI.SmartControl: QS Service version name: 0.1.73
09-08 14:31:51.641  6000  6000 D UEI.SmartControl: QS Service version code: 1073
09-08 14:31:51.642  6000  6032 D UEI.SmartControl: Config is loaded...
09-08 14:31:51.643  6000  6000 D UEI.SmartControl: Service requested: Control
09-08 14:31:51.646  6000  6000 D UEI.SmartControl: Internal service binding...
,09-08 14:31:51.648  6000  6015 D UEI.SmartControl: -----IControl: 11
09-08 14:31:51.649  6000  6015 D UEI.SmartControl: Caller: com.lge.qremote
09-08 14:31:51.653  6000  6015 D UEI.SmartControl: ------------ IControl registerCallback...
09-08 14:31:51.654  6000  6015 I UEI.SmartControl: Registering callback...
09-08 14:31:51.656  6000  6016 D UEI.SmartControl: -----IControl: 19
09-08 14:31:51.656  6000  6016 D UEI.SmartControl: Caller: com.lge.qremote
09-08 14:31:51.657  6000  6016 I UEI.SmartControl: Registering Services Ready callback...
09-08 14:31:51.658  6000  6016 I UEI.SmartControl: Notify client services are ready...
,09-08 14:31:51.660  6000  6015 D UEI.SmartControl: -----IControl: 8
09-08 14:31:51.661  6000  6015 D UEI.SmartControl: Caller: com.lge.qremote
09-08 14:31:51.671  5978  5978 I AudioManager: getMode name:com.lge.qremote
,09-08 14:31:51.677   971  1901 I ActivityManager: Killing 5614:com.google.android.talk/u0a61 (adj 15): empty #11
,09-08 14:31:51.685  6000  6031 D UEI.SmartControl:  ----- QS SDK is ready!!!
,09-08 14:31:51.688  6000  6031 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-08 14:31:51.756   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
,09-08 14:31:51.757   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:51.757   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:51.776   971  1901 I ActivityManager: Killing 5417:com.lge.eula/1000 (adj 15): empty #12
,09-08 14:31:51.782  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:51.782  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 added. We now have 2 listener(s)
09-08 14:31:51.838   971  6030 D DhcpStateMachine: DHCPV4 request on wlan0
,09-08 14:31:51.839   971  6030 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-08 14:31:51.839   971  6030 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-08 14:31:51.855  6035  6035 I dhcpcd  : version 5.5.6 starting
,09-08 14:31:51.857  6035  6035 E dhcpcd  : get_duid: Read-only file system
09-08 14:31:51.877   971  1383 W libprocessgroup: failed to open /acct/uid_10061/pid_5614/cgroup.procs: No such file or directory
,09-08 14:31:51.879   971  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:51.880   971  1324 W libprocessgroup: failed to open /acct/uid_1000/pid_5417/cgroup.procs: No such file or directory
09-08 14:31:51.883  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-08 14:31:51.883  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:51.883  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 14:31:51.883  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:51.883  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd added. We now have 2 listener(s)
09-08 14:31:51.883  5737  5825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:51.884  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:51.889  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:51.893  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:51.893  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:51.893  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:51.893  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:51.893  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:51.893  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:51.893  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:51.893  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:51.893  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:51.894  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:51.895  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:31:51.895  5737  5825 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:51.897  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:51.900  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:51.910  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 14:31:51.913  5737  5825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:31:51.913  5737  5825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:31:51.918   971  1974 I art     : Explicit concurrent mark sweep GC freed 75306(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.650ms total 208.690ms
09-08 14:31:51.923  5978  5978 I AudioManager: getMode name:com.lge.qremote
,09-08 14:31:51.942  5737  5825 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-08 14:31:51.943  5737  5825 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 14:31:51.943  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 14:31:51.943  5737  5825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:31:51.943  5737  5825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:31:51.947  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:51.947  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:51.947  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:51.947  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:31:51.947  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 removed from the list
09-08 14:31:51.947  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:51.947  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd removed from the list
09-08 14:31:51.947  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:51.947  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:51.951  6035  6035 I dhcpcd  : wlan0: rebinding lease of 192.168.1.109
09-08 14:31:51.956  5978  5978 I AudioManager: getMode name:com.lge.qremote
,09-08 14:31:51.960  5737  5825 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-08 14:31:51.960  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:51.960  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:51.960  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:51.960  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:51.960  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:51.960  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:51.961  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:51.961  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:51.961  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 14:31:51.968  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 14:31:51.969  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 14:31:51.969  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 14:31:51.969  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 14:31:51.969  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:51.969  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:51.969  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:51.969  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:51.969  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:51.969  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:51.969  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:51.969  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:51.969  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:51.972  5737  5825 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 14:31:51.973  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:51.975  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:51.976  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:51.976  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:51.976  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:51.976  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:51.976  5737  5825 V io.jxco,re.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:51.976  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:51.976  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:51.976  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:51.977  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:51.978  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:51.978  5737  5825 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:51.979  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:51.981  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:31:51.982  5737  5825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:31:51.982  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:31:51.982  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:51.982  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:31:51.987  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 14:31:51.988   971  2043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:51.988  6035  6035 I dhcpcd  : wlan0: acknowledged 192.168.1.109 from 192.168.1.1
09-08 14:31:51.996  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:51.998  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.000  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 14:31:52.008  6035  6035 I dhcpcd  : wlan0: leased 192.168.1.109 for 172800 seconds
09-08 14:31:52.008  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.009   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
09-08 14:31:52.009   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.009   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:52.010  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:31:52.014  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.015   971  1317 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
09-08 14:31:52.015  5737  5825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-08 14:31:52.015  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:31:52.016  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:52.019  5737  5825 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:31:52.020  5737  5825 I io.jxcore.node.ConnectionHelper: start: OK
09-08 14:31:52.021  5737  5825 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-08 14:31:52.021  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-08 14:31:52.022  5737  5825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:31:52.024  5737  5825 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 14:31:52.024  5737  5825 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-08 14:31:52.024  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:31:52.024  5737  5825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:31:52.024  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:31:52.024  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:52.024  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:31:52.028  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.029  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:31:52.030  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:52.032  5737  5825 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:31:52.032  5737  5825 I io.jxcore.node.ConnectionHelper: start: OK
09-08 14:31:52.032  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.032  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.032  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:52.032  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.032  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.032  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.032  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.032  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:52.035  5737  5825 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 14:31:52.036  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:52.038  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.039  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:52.039  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:52.039  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:52.039  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:52.039  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:52.039  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:52.039  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:52.039  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:52.040  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:31:52.041  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:52.041  5737  5825 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:52.041  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:31:52.041  5737  5825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:31:52.041  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:31:52.041  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:52.041  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:31:52.043  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:52.047  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.047  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:31:52.048  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:52.050  5737  5825 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:31:52.050  5737  5825 I io.jxcore.node.ConnectionHelper: start: OK
09-08 14:31:52.050  5737  5825 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-08 14:31:52.050  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 14:31:52.050  5737  5825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:31:52.055  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.055  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.055  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:52.056  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.056  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.056  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.056  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.056  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.057  5737  5825 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 14:31:52.057  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.057  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.057  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.057  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.058  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.058  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.058  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.058  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.058  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.059  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 14:31:52.059  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.059  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.059  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.059  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.059  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.059  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.059  5737  5825 D io.jx,core.node.ConnectivityMonitor: stop
09-08 14:31:52.059  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.059  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.060  5737  5825 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 14:31:52.060  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.060  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.060  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.061  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.061  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.061  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.061  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.061  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.061  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.062  5737  5825 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 14:31:52.062  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.062  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.062  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.062  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.062  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.062  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.062  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.062  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.062  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.063  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 14:31:52.063  5737  5825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:31:52.063  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 14:31:52.063  5737  5825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:31:52.063  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 14:31:52.063  5737  5825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:31:52.063  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.063  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.063  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.063  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.063  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.063  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.063  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.063  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.064  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.064  5737  5825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:52.065  5737  5825 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 14:31:52.065  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 14:31:52.069  5737  5825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:52.070  5737  5825 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 14:31:52.070  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 14:31:52.071  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 14:31:52.071  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 14:31:52.071  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 14:31:52.071  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 14:31:52.071  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 14:31:52.071  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 14:31:52.071  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 14:31:52.071  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 14:31:52.071  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 14:31:52.071  5737  5825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 14:31:52.071  5737  5825 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:31:52.071  5737  5825 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 14:31:52.071  5737  5825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:52.071  5737  5825 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:31:52.071  5737  5825 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 14:31:52.072  5737  5825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:52.072  5737  5825 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:31:52.072  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 14:31:52.081  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 14:31:52.082  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 14:31:52.082  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 14:31:52.087  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 14:31:52.087  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 14:31:52.087  5737  5825 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 14:31:52.087  5737  5825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:52.087  5737  5825 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 14:31:52.088  5737  6053 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 762)
,09-08 14:31:52.090  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.090  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.090  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.090  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 14:31:52.091  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.091  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.091  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.091  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.091  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.091  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.094  5737  6054 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 762
09-08 14:31:52.094  5737  6054 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 762)
09-08 14:31:52.094  5737  6054 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 762)
09-08 14:31:52.094  5737  5825 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 14:31:52.094  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.094  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.094  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.094  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.094  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.094  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.094  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.094  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.095  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.096  5737  5825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 14:31:52.097  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.097  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.097  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.097  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.097  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.097  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.097  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.097  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.097  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.098  5737  5825 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 14:31:52.098  5737  5825 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 14:31:52.098  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:31:52.098  5737  5825 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 14:31:52.099  5737  5825 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 14:31:52.099  5737  5825 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 14:31:52.099  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:31:52.099  5737  5825 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 14:31:52.099  5737  5825 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 14:31:52.099  5737  5825 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 14:31:52.099  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:31:52.099  5737  5825 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 14:31:52.099  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.099  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.099  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.099  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.099  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.099  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.099  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.099  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.099  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.100  5737  5825 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 14:31:52.102  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:52.104  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.104  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:52.104  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:52.104  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:52.104  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:52.104  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:52.104  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:52.104  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:52.104  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:52.105  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.106  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:52.106  5737  5825 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:52.106  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:31:52.106  5737  5825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:31:52.106  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:31:52.107  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:52.107  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:31:52.108  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:52.112  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.112  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:31:52.113  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:52.115  5737  5825 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:31:52.115  5737  5825 I io.jxcore.node.ConnectionHelper: start: OK
09-08 14:31:52.115  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.115  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.115  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:52.115  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.115  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.115  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.115  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.115  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.118  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.118  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.118  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.118  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.118  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.118  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.118  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.118  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.118  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.120  5737  5825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 14:31:52.121  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:52.122  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 14:31:52.123  5737  5825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 14:31:52.123  5737  5825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:31:52.124  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 14:31:52.124  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:31:52.125  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.125  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:31:52.125  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:31:52.125  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:31:52.125  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.125  5737  5825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:31:52.125  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.125  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.125  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:31:52.125  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:31:52.125  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:31:52.126  5737  5737 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 14:31:52.126  5737  5737 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 14:31:52.130  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:31:52.131  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.132  5737  5825 D BluetoothLeScanner: could not find callback wrapper
09-08 14:31:52.132  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:31:52.133  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:31:52.133  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.133  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.134  5737  6059 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:31:52.134  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:31:52.134  5737  6059 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 14:31:52.134  5737  5737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:31:52.134  5737  5737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:31:52.134  5737  5737 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:31:52.134  5737  5737 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 14:31:52.134  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.135  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.135  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.135  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.136  5737  5825 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 14:31:52.136  5737  5825 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 14:31:52.136  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 14:31:52.138  5737  5825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:31:52.138  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.138  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.138  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.138  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.138  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.138  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.138  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.138  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.138  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.141   971   988 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:52.142   971  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:52.143   971  1640 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:52.144  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.144  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.144  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.144  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.144  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.144  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.144  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.144  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.144  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.145  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.145  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.145  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.146  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb743b4 not in the list
09-08 14:31:52.146  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.146  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0dbdd not in the list
09-08 14:31:52.146  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.146  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.146  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.147  5737  5825 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 14:31:52.148  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:31:52.148  5737  5825 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 14:31:52.148  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:31:52.148  5737  5825 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 14:31:52.148  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:31:52.150  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 14:31:52.150  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 14:31:52.151  5737  5825 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 14:31:52.151  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 14:31:52.151  5737  5825 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 14:31:52.151  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 14:31:52.151  5737  5825 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 14:31:52.151  5737  5825 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 14:31:52.152  5737  5825 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 14:31:52.152  5737  5825 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 14:31:52.153  5737  5825 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 14:31:52.153  5737  5825 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 14:31:52.153  5737  5825 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 14:31:52.153  5737  5825 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-08 14:31:52.156  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:52.156  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d17469b added. We now have 2 listener(s)
09-08 14:31:52.156   971  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:52.158  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-08 14:31:52.158  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:52.158  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:31:52.158  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:52.159  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14e7a38 added. We now have 2 listener(s)
09-08 14:31:52.159  5737  5825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:52.159  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:52.161  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:52.164  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.165  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:52.165  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:52.165  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:52.165  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:52.165  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:52.165  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:52.165  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:52.165  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:52.167  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:31:52.168  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:52.168  5737  5825 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:52.170  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:52.171  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.172  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.172  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.172  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:52.172  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:31:52.172  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d17469b removed from the list
09-08 14:31:52.172  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.172  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14e7a38 removed from the list
09-08 14:31:52.172  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.172  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.176  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:52.177  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a01e776 added. We now have 2 listener(s)
09-08 14:31:52.177   971  1951 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:52.180  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-08 14:31:52.180  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:52.180  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:31:52.180  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:52.180  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2299b177 added. We now have 2 listener(s)
09-08 14:31:52.180  5737  5825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:31:52.186  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:52.188  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:52.197  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:31:52.197  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:52.197  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:52.197  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:52.197  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:52.197  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:52.197  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:52.197  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:52.197  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:52.199  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.200  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:52.200  5737  5825 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:52.201  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:52.201  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:52.201  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:52.201  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:31:52.201  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a01e776 removed from the list
09-08 14:31:52.201  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:52.201  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2299b177 removed from the list
09-08 14:31:52.201  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:52.201  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:52.202  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:52.203  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:52.203  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34f5764d added. We now have 2 listener(s)
09-08 14:31:52.204   971  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:31:52.206  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-08 14:31:52.206  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:52.207  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:31:52.207  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:52.207  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@231d0502 added. We now have 2 listen,er(s)
09-08 14:31:52.207  5737  5825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:52.207  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:52.211  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:52.211  5737  6053 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-08 14:31:52.213  5737  6053 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 762)
09-08 14:31:52.213  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.214  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:52.214  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:52.214  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:52.214  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:52.214  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:52.214  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:52.214  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:52.214  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:52.215  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:31:52.216  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:52.216  5737  5825 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:52.218  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:52.221   971   990 D WifiServiceImplEx: setWifiEnabled: false pid=5737, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
09-08 14:31:52.221   971   990 D WifiService: setWifiEnabled: false pid=5737, uid=10030
,09-08 14:31:52.233   971   971 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:31:52.234   971   971 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:31:52.234   971   971 D Ulp_jni : JNI:system_update. Event-4
09-08 14:31:52.237   971  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:31:52.242   971  6030 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.242   971  6030 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:52.242   971  6030 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.243   971  6030 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-08 14:31:52.243   971  6030 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.243   971  6030 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:52.243   971  6030 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.243   971  6030 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:52.243   971  6030 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-08 14:31:52.244   971  6030 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
09-08 14:31:52.245   971  6030 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:31:52.245   971  6030 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.245   971  6030 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:52.245   971  6030 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.109
09-08 14:31:52.245   971  6030 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-08 14:31:52.245   971  6030 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:31:52.245   971  6030 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
09-08 14:31:52.245   971  6030 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-08 14:31:52.246   971  6030 D DhcpStateMachine: RunningState
09-08 14:31:52.247   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:52.247   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:52.262   971  6030 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:52.262   274  1044 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:31:52.262   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
,09-08 14:31:52.295   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-08 14:31:52.295   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-08 14:31:52.296   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 10
09-08 14:31:52.297   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
09-08 14:31:52.297   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.297   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:52.298   971  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
09-08 14:31:52.299   971  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 0
09-08 14:31:52.300   971  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 14:31:52.301   971  6028 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:52.301   971  6028 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-08 14:31:52.301   971  1317 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-08 14:31:52.302   971   971 D WifiHS20: hidePasspointNotification off =false
09-08 14:31:52.306   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:52.306  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:52.306   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:52.306   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:52.307  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 14:31:52.311  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:52.311 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:52.311  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:52.311  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:52.312  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:52.312  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:52.312  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:52.312   971  1317 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-08 14:31:52.312  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:52.312  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:52.312  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:31:52.313   971   971 D WifiHS20: hidePasspointNotification off =false
09-08 14:31:52.314  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:52.314  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:52.315   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:52.315   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:52.315   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:52.315  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:52.315 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:52.315  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:31:52.316   971   971 D WifiScanningService: SCAN_AVAILABLE : 1
09-08 14:31:52.317   971   971 D RttService: SCAN_AVAILABLE : 1
09-08 14:31:52.317   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:52.317   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:52.317  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:52.317  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:52.317  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-,08 14:31:52.317   971  1307 D LGWifiP2pService: P2pDisablingState
09-08 14:31:52.317  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:52.317   971  1307 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:52.318   971  1307 D LGWifiP2pService: p2p socket connection lost
09-08 14:31:52.318  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:52.318  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:52.318   971  1307 D LGWifiP2pService: P2pDisabledState
09-08 14:31:52.319  1861  1861 D WfdsService: WifiP2pState is changed : false
09-08 14:31:52.319  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
09-08 14:31:52.319  1861  2153 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-08 14:31:52.319  1861  2153 D WfdsJNI : doCommand: P2P_STOP_FIND
09-08 14:31:52.319  1861  2153 D WfdsService: Set the WFDS Monitor: false
09-08 14:31:52.320  1861  2153 D WfdsMonitor: WFDS Monitor is stopped
09-08 14:31:52.320  1861  2153 D WfdsService: STATE : WfdsDisabledState - enter
09-08 14:31:52.320  1861  2153 D WfdsService: WFDS: Scanner is paused
,09-08 14:31:52.321  1861  5942 D CtrlSupplicant: Received on exit socket, terminate
09-08 14:31:52.321  1861  5942 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-08 14:31:52.321  1861  5942 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-08 14:31:52.321  1861  5942 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-08 14:31:52.321  1861  2153 D WfdsDiscoveryStore: Clear Discovery Method Map: ScanAlwaysMode false
09-08 14:31:52.322  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:52.322  1861  2142 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-08 14:31:52.323   971  1332 D WifiScanningService: DefaultState got{ when=-6ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:52.324   971  1333 D RttService: EnabledState got{ when=-7ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:52.324   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.324   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:52.330   971  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 14:31:52.331   971  1307 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:52.331   971  1307 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 14:31:52.332   274  1044 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:31:52.332  5910  5910 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:31:52.332  5910  5910 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:52.332  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:52.336   971   971 D WifiHS20: hidePasspointNotification off =false
09-08 14:31:52.338  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:52.338  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:52.338   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:52.338   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:52.338   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:52.339  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:52.338 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:52.339  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:31:52.341  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:52.341  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:52.341 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:52.341  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:52.342  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:52.342  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:31:52.342  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:52.342  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:52.342  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:52.342  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:52.342   971   971 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-08 14:31:52.343   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:52.343   971   971 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,09-08 14:31:52.346  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:52.346  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:52.346  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
09-08 14:31:52.346  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-08 14:31:52.348  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.349  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:52.349  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:52.349  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:52.349  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:52.349  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:52.349  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:52.349  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:52.349  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:52.350  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.351  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:52.351  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:52.355  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:52.356  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:52.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:52.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:52.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:52.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:52.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:52.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:52.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:52.357  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:31:52.358  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:52.359  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:52.363  5910  5910 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:31:52.363  5910  5910 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:52.363  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:52.369  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:52.375  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:52.376   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-08 14:31:52.377   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 5
09-08 14:31:52.378  5881  5881 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-08 14:31:52.378  5881  5881 I wpa_supplicant: monitor socket send errors count : 1
09-08 14:31:52.378  5881  5881 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1861-2\x00 that cannot receive messages
09-08 14:31:52.378   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 10
09-08 14:31:52.379   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 7
09-08 14:31:52.380   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.380   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:52.382  5910  5910 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:31:52.382  5910  5910 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:52.382  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:31:52.391  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:52.394  5881  5881 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 14:31:52.395  5881  5881 W wpa_supplicant: USIM:  scard_deinit function
09-08 14:31:52.399  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:52.401  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:52.409   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:31:52.409   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-08 14:31:52.410   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-08 14:31:52.410   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:52.448   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-08 14:31:52.460   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 5
09-08 14:31:52.461   971  1055 D Tethering: InitialState.processMessage what=4
09-08 14:31:52.461  5881  5881 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-08 14:31:52.461   971  1055 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-08 14:31:52.462   971  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.462   971  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:52.462   971  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.463   971  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:52.464   274  1039 E BandwidthController: [LG DATA] No such appUid: 1000
09-08 14:31:52.464   274  1039 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-08 14:31:52.464   274  6072 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
09-08 14:31:52.464   274  6072 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:52.465   274  6072 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
09-08 14:31:52.465  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:31:52.465  5882  5882 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:31:52.465  5882  5882 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:31:52.465  5882  5882 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:31:52.465  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:31:52.465   971  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-08 14:31:52.466  5882  5882 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:31:52.467  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-08 14:31:52.467  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:31:52.467  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:31:52.467  5882  5882 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:31:52.467  5882  5882 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:31:52.472   971  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:52.472   971  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:52.480   971  6030 D DhcpStateMachine: StoppedState
09-08 14:31:52.480   971  6030 D DhcpStateMachine: StoppedState{ when=-149ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 14:31:52.566  1861  1861 D WfdsService: Supplicant Connection state is changed : false
09-08 14:31:52.566  1861  2153 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-08 14:31:52.566  1861  2153 D WfdsService: Set the WFDS Monitor: false
,09-08 14:31:52.566  1861  2153 D WfdsMonitor: WFDS Monitor is stopped
09-08 14:31:52.567   971  1309 D WifiOffDelayIfNotUsed: stopMonitoring
09-08 14:31:52.568  5949  5949 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:31:52.568  5949  5949 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:31:52.569  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:52.569  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:52.569 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:52.569  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:31:52.570   971   971 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-08 14:31:52.570   971  1315 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-08 14:31:52.570   971  1315 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-08 14:31:52.570  5949  5949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:31:52.572  1737  2525 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:52.573  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:52.573  5949  5949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:31:52.573  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:52.573  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:52.573  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
09-08 14:31:52.574  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-08 14:31:52.575  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:52.577  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:52.578  5949  6073 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 14:31:52.582  5949  6074 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:31:52.582  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:52.582  5949  6074 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:31:52.585  5910  5910 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-08 14:31:52.585  5910  5910 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:31:52.585  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:52.635  5737  5737 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:31:52.738   971   988 D WifiServiceImplEx: setWifiEnabled: true pid=5737, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,09-08 14:31:52.738   971   988 D WifiService: setWifiEnabled: true pid=5737, uid=10030
09-08 14:31:52.747   971   971 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:31:52.747   971  1316 D WifiController: WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 488ms
09-08 14:31:52.748   971   971 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:31:52.748   971   971 D Ulp_jni : JNI:system_update. Event-4
09-08 14:31:53.241   971  1316 D WifiController: DEFERRED_TOGGLE handled
,09-08 14:31:53.245   971  1309 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-08 14:31:53.248   971  1309 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
09-08 14:31:53.248   971  1309 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
09-08 14:31:53.248   971  1309 E WifiHW  : band=b
09-08 14:31:53.248   971  1309 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
09-08 14:31:53.249   274  1044 D SoftapController: Softap fwReload - Ok
09-08 14:31:53.250   971  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:53.251   971  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:53.251   274  1044 D CommandListener: Setting iface cfg
09-08 14:31:53.251   274  1044 D CommandListener: Trying to bring down wlan0
09-08 14:31:53.252   274  1044 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:31:53.255   971  1309 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-08 14:31:53.269  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:53.270  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:53.27 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:53.270  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,09-08 14:31:53.290  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:53.291  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:53.293  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:53.294  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:53.294  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
09-08 14:31:53.294  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-08 14:31:53.299   971   971 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-08 14:31:53.301   971  1309 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-08 14:31:53.303  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:53.319  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:53.321  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:53.333  6086  6086 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 14:31:53.398  6086  6086 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 14:31:53.399  6086  6086 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-08 14:31:54.304   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:31:54.304   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-08 14:31:54.310   971  1055 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 14:31:54.312   971  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:54.312   971  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.325  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-08 14:31:54.333   971  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:54.333   971  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.334  5882  5882 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:31:54.334  5882  5882 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:31:54.334  5882  5882 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:31:54.335  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-08 14:31:54.346  5882  5882 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-08 14:31:54.346  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 14:31:54.346  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:31:54.346  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:31:54.346  5882  5882 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:31:54.346  5882  5882 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 14:31:54.346  5882  5882 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-08 14:31:54.355  6086  6086 E wpa_supplicant: USIM:  scard_init function
09-08 14:31:54.356  6086  6086 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 14:31:54.358   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
,09-08 14:31:54.363   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
09-08 14:31:54.364   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:54.364   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.366   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-08 14:31:54.374  6086  6086 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-08 14:31:54.389   971  1309 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
09-08 14:31:54.389   971  1309 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-08 14:31:54.392   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.392   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.392   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.392   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.392   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:31:54.397  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:54.397  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.397 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:54.397  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:31:54.401  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:31:54.403  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:54.403  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:54.403  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:54.403  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:54.403  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:54.403  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:54.403  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:54.403  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:54.405  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:54.405  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:54.407  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:54.408  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:54.408  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:54.408  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:54.408  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:54.408  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:54.408  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:54.408  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:54.408  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:54.408  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:54.409  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:54.410  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:54.410  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.410  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:54.411  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-08 14:31:54.415   971   971 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-08 14:31:54.415   971   971 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
,09-08 14:31:54.418   971  1315 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,09-08 14:31:54.419  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:54.424  6086  6086 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-08 14:31:54.440   971  1309 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-08 14:31:54.440   971  1309 D WifiStateMachine: enableVerboseLogging : level 2
,09-08 14:31:54.445   971  1309 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:31:54.446   971  1309 D WifiNative-HAL: Setting external_sim to 1
09-08 14:31:54.446   971  1309 I WifiNative-HAL: startHal
09-08 14:31:54.446   971  1309 D wifi    : setting scan oui 0x9a0902c8
09-08 14:31:54.446   971  1309 D WifiHAL : Sending mac address OUI
09-08 14:31:54.446   971  1309 E WifiHAL : failed to set scanning mac OUI; result = -95
09-08 14:31:54.447   971  1309 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:31:54.447   971  1309 I WifiNative-HAL: startHal
09-08 14:31:54.447   971  1309 D wifi    : setting scan oui 0x9a0902c8
09-08 14:31:54.447   971  1309 D WifiHAL : Sending mac address OUI
09-08 14:31:54.447   971  1309 E WifiHAL : failed to set scanning mac OUI; result = -95
09-08 14:31:54.447  1861  1861 D WfdsService: Supplicant Connection state is changed : true
09-08 14:31:54.449  1861  2153 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-08 14:31:54.449  1861  2153 D WfdsService: Set the WFDS Monitor: true
09-08 14:31:54.450  1861  2153 D WfdsMonitor: WfdsMonitorThread create
09-08 14:31:54.450  1861  2153 D WfdsMonitor: WFDS Monitor is created and started
09-08 14:31:54.450  1861  2153 D WfdsService: WiFi: Supplicant connection re-established
09-08 14:31:54.450  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:54.451   971  1307 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.452   971   971 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 14:31:54.452   971   971 D RttService: SCAN_AVAILABLE : 3
09-08 14:31:54.452   971  1332 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.452   971  1332 I WifiNative-HAL: startHal
09-08 14:31:54.453   971  1333 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.453   971  1332 D wifi    : getting scan capabilities on interface[0] = 0x9a0902c8
09-08 14:31:54.453   971  1332 D WifiHAL : Creating message to get scan capablities; iface = 24
09-08 14:31:54.453   971  1332 D wifi    : failed to get capabilities : -95
09-08 14:31:54.453   971  1332 E WifiScanningService: could not get scan capabilities
09-08 14:31:54.453   971  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:54.453   971  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.454   971  1309 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
09-08 14:31:54.454   274  1044 D CommandListener: Setting iface cfg
09-08 14:31:54.454   274  1044 D CommandListener: Trying to bring up p2p0
09-08 14:31:54.454   971  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 14:31:54.454   971  1307 D LGWifiP2pService: P2pEnablingState
09-08 14:31:54.454   971  1307 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.454   971  1307 D LGWifiP2pService: P2p socket connection successful
09-08 14:31:54.454   971  1307 D LGWifiP2pService: P2pEnabledState
09-08 14:31:54.455   971  1309 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-08 14:31:54.455  6086  6086 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-08 14:31:54.456  1861  6122 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-08 14:31:54.456  1861  6122 E CtrlSupplicant: Succeed to open control connection
09-08 14:31:54.456   971  1307 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-08 14:31:54.456   971  1307 D LGWifiP2pService: before postfix = G3s-1
09-08 14:31:54.456   971  1307 D WifiServerServiceExt: postfix byte check : 5
09-08 14:31:54.457   971  1307 D LGWifiP2pService: after postfix = G3s-1
09-08 14:31:54.457  1861  6122 E CtrlSupplicant: Succeed to open monitor connection
09-08 14:31:54.457  ,1861  6122 D WfdsMonitor: Supplicant connection established
09-08 14:31:54.457  1861  2153 D WfdsService: Connected to the supplicant for wfds
09-08 14:31:54.458   971  1307 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 14:31:54.458   971  1307 D WifiNative-HAL: p2pGetDeviceAddress returning 
09-08 14:31:54.458   971  1307 E LGWifiP2pService: p2pGetDeviceAddress NULL retry=1
09-08 14:31:54.458   971  1307 D WifiNative-HAL: p2pGetDeviceAddress
09-08 14:31:54.459   971  1307 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
09-08 14:31:54.461   971  1307 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
09-08 14:31:54.463  1861  1861 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-08 14:31:54.463  1861  1861 D WfdsService: Update P2p Interface State: 3
09-08 14:31:54.465   971  1309 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-08 14:31:54.465  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:54.481  5949  5949 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:31:54.481  5949  5949 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:31:54.483  5949  5949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:31:54.485  5949  5949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,09-08 14:31:54.491  5949  6132 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:31:54.494  5949  6133 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:31:54.494  5949  6133 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:31:54.498  6086  6086 E wpa_supplicant: disconnect_rssi_lvl: -100
,09-08 14:31:54.498   971  1307 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-08 14:31:54.500   971  1309 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
09-08 14:31:54.500  6086  6086 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
09-08 14:31:54.501   971  1307 D LGWifiP2pService: sending p2p connection changed broadcast
09-08 14:31:54.501   971  1307 D LGWifiP2pService: InactiveState
09-08 14:31:54.501   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.501   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.501   971  1307 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.501   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.501   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.501   971  1307 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.501   971   971 E WifiServerServiceExt: No p2p device connected
09-08 14:31:54.502  1861  1861 D WfdsService: WifiP2pState is changed : true
09-08 14:31:54.503  1861  2153 D WfdsService: Receive the WFDS_ENABLE Method
09-08 14:31:54.503  1861  2153 D WfdsService: Set the WFDS Monitor: true
09-08 14:31:54.503  1861  2153 D WfdsService: Connected to the supplicant for wfds
09-08 14:31:54.503  1861  2153 D WfdsJNI : doCommand: WFDS_SET TRUE
09-08 14:31:54.503  6086  6086 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-08 14:31:54.503  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:54.504   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.504   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.504   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:31:54.504  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.504 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:54.504  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:31:54.504   971  1309 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
09-08 14:31:54.505  1861  1861 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-08 14:31:54.506  1861  1861 D WfdsService: isConnected: false
09-08 14:31:54.506  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
09-08 14:31:54.506  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:54.506  1861  2153 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
09-08 14:31:54.507  5594  5594 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 14:31:54.507   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.507   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.507   971  1307 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.507   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg,2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.507   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.507   971  1307 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.508  1861  1861 D WfdsService: GroupInfoAvailable: mGroupInfo is null
09-08 14:31:54.508  5594  5594 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-08 14:31:54.508  5594  5594 V [BNRBootReceiver]: Boot Receiver Return
09-08 14:31:54.510  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:54.510  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.510  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:54.510  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:54.510  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:54.510  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:54.514  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:54.519  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:54.524  6086  6086 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:31:54.525  6086  6086 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
,09-08 14:31:54.525  1861  2153 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
09-08 14:31:54.525  1861  2153 D WfdsService: selectPreferredScanChannel [6]
09-08 14:31:54.525  1861  2153 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
09-08 14:31:54.525  1861  2153 W WfdsService: DefaultState - msg [9441285] is not handled
09-08 14:31:54.526  6086  6086 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz)
,09-08 14:31:54.557  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,09-08 14:31:54.557  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.557 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:54.558  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:31:54.558   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.558   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.558   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:31:54.558  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:54.561  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:54.561  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.561  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:54.561  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:54.562  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:54.562  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:54.563   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:54.563   971   971 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 14:31:54.564  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:54.566   971   971 D LocSvc_java: onReceive
09-08 14:31:54.568  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:54.568  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:54.568   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.568   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.568   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:31:54.569  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.569 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:54.569  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,09-08 14:31:54.571  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:54.571  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.571  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:54.571  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:54.571  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:54.571  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:54.572   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:54.572   971   971 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 14:31:54.573   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:54.573   971   971 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-08 14:31:54.574  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:54.583  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-08 14:31:54.585  5882  5882 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-08 14:31:54.586  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:54.590  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:54.612   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:31:54.612   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:31:54.612   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:31:54.613  6086  6086 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 14:31:54.615   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:54.615   971   971 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-08 14:31:54.618  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 14:31:54.619   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.619   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.619   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:31:54.619  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:54.620  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.619 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:54.620  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:31:54.620  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:54.621  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:54.621  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.621  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:54.621  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:54.622  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:54.622  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:54.622  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:54.622  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:54.623   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.623   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.623   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-08 14:31:54.624  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.623 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:54.624   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:54.624   971   971 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-08 14:31:54.624  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:31:54.625  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:54.625  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.625  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=,false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:54.626  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
,09-08 14:31:54.626  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:54.626  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:54.629  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:54.637  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:54.642  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:54.644  6086  6086 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:31:54.644  6086  6086 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-08 14:31:54.645   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:31:54.647   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:54.647   971   971 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-08 14:31:54.649   971  1309 I WifiServiceExtension: setVHTCapabilityType  : false
,09-08 14:31:54.660   971  1309 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-08 14:31:54.660   971  1309 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
09-08 14:31:54.660   971  1309 I WifiServiceExtension: setSecurityType  : 2
09-08 14:31:54.669  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-08 14:31:54.670  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:54.670   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.670   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.670   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 14:31:54.672  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.672 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:54.672  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:54.672  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:31:54.674  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:54.675  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.675  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:54.675  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:54.675  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:54.675  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:54.675  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:54.675  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:54.675  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.675 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:31:54.676  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:31:54.676   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.676   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.676   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 14:31:54.679  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:54.679  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.679  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:,54.679  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:54.679  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:54.679  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:54.680  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:54.685   971  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,09-08 14:31:54.686   971  1317 D ConnectivityService: Got NetworkAgent Messenger
09-08 14:31:54.686   971  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 14:31:54.686   971  1317 D ConnectivityService: NetworkAgent connected
09-08 14:31:54.689  1861  1885 D WifiServiceExtension: isInternetCheckAvailable return false
09-08 14:31:54.689   971  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:31:54.692  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:54.696  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:54.700   971  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:31:54.709   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
09-08 14:31:54.709   971  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:54.709   971  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-08 14:31:54.710   274  1044 D CommandListener: Setting iface cfg
09-08 14:31:54.711   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:54.711   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.714   971  6139 D DhcpStateMachine: StoppedState
09-08 14:31:54.714   971  1309 E WifiStateMachine: Start Dhcp Watchdog 2
09-08 14:31:54.714   971  6139 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.714   971  6139 D DhcpStateMachine: WaitBeforeStartState
09-08 14:31:54.721  1914  1914 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
09-08 14:31:54.721  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-52 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.721 DNS addrs= 0.0.0.0, 0.0.0.0, 
,09-08 14:31:54.722  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:54.722  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.723  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:54.725   971  1317 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-08 14:31:54.757  5737  5825 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 14:31:54.808   971  1309 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-08 14:31:54.808   971  1309 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:31:54.808   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1bc0dfec target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.808   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1bc0dfec target=com.android.internal.util.StateMachine$SmHandler }
,09-08 14:31:54.808   971  1309 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:31:54.809   971  6139 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.809   971  6139 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-08 14:31:54.813   274  1044 D CommandListener: Setting iface cfg
09-08 14:31:54.813   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
09-08 14:31:54.814   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:54.814   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.815   274  1044 D CommandListener: Trying to bring up wlan0
09-08 14:31:54.816   971  1309 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-08 14:31:54.817   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:54.817   971   971 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 14:31:54.817   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:31:54.818   971   971 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 14:31:54.821   971  1317 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,09-08 14:31:54.822   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.822   971  1307 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.829   971  1317 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-08 14:31:54.830   971  1309 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 14:31:54.831   971  1317 D ConnectivityService: ignoring duplicate network state non-change
09-08 14:31:54.833  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,09-08 14:31:54.834  1861  1887 D WifiServiceExtension: isInternetCheckAvailable return false
09-08 14:31:54.836   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.836   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.836   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 14:31:54.839  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:54.839  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:54.841   971  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 14:31:54.843   971  1317 D ConnectivityService: Adding iface wlan0 to network 101
09-08 14:31:54.844   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.844   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.844   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 14:31:54.844  1861  1885 D WifiServiceExtension: isInternetCheckAvailable return false
09-08 14:31:54.846  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.845 DNS addrs= 192.168.1.1, 0.0.0.0, 
,09-08 14:31:54.848  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
09-08 14:31:54.849  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:54.850  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:54.850  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.850  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:54.850  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:54.851  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:54.851  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:54.852  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:31:54.855  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.855 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-08 14:31:54.856   971   971 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-08 14:31:54.859   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.859   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.859   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 14:31:54.862   971  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-08 14:31:54.864  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
09-08 14:31:54.866   971   971 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 14:31:54.868  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,09-08 14:31:54.876   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.876  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.875 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-08 14:31:54.876   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.876   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 14:31:54.876  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-08 14:31:54.876  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:31:54.878  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:54.878 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-08 14:31:54.878  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-08 14:31:54.880  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:31:54.880  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.880  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
09-08 14:31:54.880  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:54.880  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:54.880  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:54.881  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 14:31:54.886  1861  1861 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-08 14:31:54.887   971  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 14:31:54.888   971  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-08 14:31:54.889   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-08 14:31:54.889   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.889   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-08 14:31:54.889   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.890   971  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-08 14:31:54.890   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-08 14:31:54.890   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.891   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-08 14:31:54.891   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.891   274  1044 E Netd    : netlink response contains error (File exists)
09-08 14:31:54.892   488   488 D charger_monitor: init target 500000
09-08 14:31:54.892   971  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-08 14:31:54.893  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 14:31:54.893   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-08 14:31:54.893   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.894   971  1317 D ConnectivityService: addLocalRoutetoDefaultNetwork
,09-08 14:31:54.894   971  1317 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-08 14:31:54.894   971  1317 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-08 14:31:54.895   971  1317 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:54.895   971  1317 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.898   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
09-08 14:31:54.898   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.898   971  1317 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 14:31:54.899   971  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 14:31:54.899   971  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-08 14:31:54.899   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.899   971  1317 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-08 14:31:54.899   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-08 14:31:54.899   971  1317 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:54.899   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:54.899   971  1317 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:54.899   971  1317 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 14:31:54.899   971  1317 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.899   971  1317 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
09-08 14:31:54.900   971  1317 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.900   971  1317 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-08 14:31:54.900   971  1317 D ConnectivityService: currentScore = 0, newScore = 20
09-08 14:31:54.900   971  1317 D ConnectivityService:    accepting network in place of null
09-08 14:31:54.900   971  1317 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.900   971  1317 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
09-08 14:31:54.905  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:31:54.906  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.906   971  1317 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extr,a: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-08 14:31:54.906  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
,09-08 14:31:54.908   971  1309 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.908   971  1309 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:54.909   971  1317 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 14:31:54.911   971  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 14:31:54.912  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:54.913  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:54.913  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:54.914  1758  1758 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.914  1758  1758 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-08 14:31:54.915   971  1317 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:31:54.915  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 14:31:54.915   971  1317 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-08 14:31:54.916   971  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-08 14:31:54.917   971  1317 D ConnectivityService: validation of new default Network = false
09-08 14:31:54.918   971  1317 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-08 14:31:54.918   971  1317 D DSQN    : enableDataServiceNotify 
09-08 14:31:54.918   971  1317 D DSQN    : start dsqn bin
,09-08 14:31:54.919  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:31:54.919  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:54.919  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-08 14:31:54.920  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:31:54.920  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:31:54.920  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:31:54.921  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-08 14:31:54.921  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-08 14:31:54.921  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-08 14:31:54.921  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-08 14:31:54.923   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
09-08 14:31:54.924   971  6143 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
09-08 14:31:54.927   971  1046 W ProcessCpuTracker: Skipping unknown process pid 6142
09-08 14:31:54.939   971  1317 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,09-08 14:31:54.939   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.939   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:54.946   971  1901 I ActivityManager: Process com.android.vending (pid 4856) has died
09-08 14:31:54.949   971  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:54.949   971  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:54.949   971  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:54.949  1914  1914 W QCNEJ   : |CORE| No family connected
09-08 14:31:54.949   971  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:54.949  1914  1914 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-08 14:31:54.950   274  1039 E BandwidthController: [LG DATA] No such appUid: 1000
09-08 14:31:54.950   274  1039 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-08 14:31:54.950   274  6145 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-08 14:31:54.950   274  6145 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:54.951   274  6145 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-08 14:31:54.951   488   488 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-08 14:31:54.951   274  6145 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:31:54.952  1914  1914 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
09-08 14:31:54.954   971  1317 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:54.954   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.955   971  1317 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:54.955  5434  5865 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-08 14:31:54.956  1373  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:31:54.956  6144  6144 I DSQN    : DSQN samuel.seo ver 141203
09-08 14:31:54.957  6144  6144 E DSQN    : DSQN sock connect success to lgdatalistenerd
09-08 14:31:54.957  6144  6144 I DSQN    : created command queue thread
,09-08 14:31:54.957  6144  6144 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-08 14:31:54.957  6144  6144 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
09-08 14:31:54.959  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:54.960   971  1055 D Tethering: MasterInitialState.processMessage what=3
09-08 14:31:54.964  1914  1914 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-08 14:31:54.964  1914  1914 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-08 14:31:54.969  1861  2047 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-08 14:31:54.969  1861  2047 D LEDHandler: Battery Level Remaining: 100%
09-08 14:31:54.969  1861  2047 D LEDHandler: Battery Temp: 323, mChargingStatus=5, mChargingStop=false
,09-08 14:31:54.971  2082  3307 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-08 14:31:54.972  5594  5594 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-08 14:31:54.973   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.973   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.973   971  1316 D WifiController: battery changed pluggedType: 2
,09-08 14:31:54.978  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:54.991  1914  1914 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-08 14:31:54.991  1914  1914 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-08 14:31:54.991  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:31:54.992  1861  2047 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-08 14:31:54.992  1861  2047 D LEDHandler: Battery Level Remaining: 100%
09-08 14:31:54.992  1861  2047 D LEDHandler: Battery Temp: 324, mChargingStatus=5, mChargingStop=false
09-08 14:31:54.993  2082  3307 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-08 14:31:54.993  5594  5594 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-08 14:31:54.995   971  1316 D WifiController: battery changed pluggedType: 2
09-08 14:31:54.994   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.995   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:54.997  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:55.002  1373  1373 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:31:55.003  5910  5910 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 14:31:55.006  1373  1373 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,09-08 14:31:55.007   274  6145 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:31:55.009  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:31:55.009  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:31:55.009  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:55.009   971  1306 I System.out: propertyValue:false
09-08 14:31:55.009  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-08 14:31:55.011   971  6139 D DhcpStateMachine: DHCPV4 request on wlan0
09-08 14:31:55.011   971  6139 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-08 14:31:55.011   971  6139 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-08 14:31:55.016  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:31:55.017  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,09-08 14:31:55.017  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
09-08 14:31:55.017  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 323
09-08 14:31:55.017  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-08 14:31:55.017  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 323
09-08 14:31:55.019  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-08 14:31:55.019  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 324
09-08 14:31:55.020  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-08 14:31:55.020  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 324
09-08 14:31:55.022  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-08 14:31:55.022  6149  6149 I dhcpcd  : version 5.5.6 starting
09-08 14:31:55.023  5882  5882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:31:55.023  6149  6149 E dhcpcd  : get_duid: Read-only file system
09-08 14:31:55.027  5882  5882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:31:55.032  5910  5910 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-08 14:31:55.033  5910  5910 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:31:55.050   971  1306 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-08 14:31:55.082  6149  6149 I dhcpcd  : wlan0: rebinding lease of 192.168.1.109
,09-08 14:31:55.093  6149  6149 I dhcpcd  : wlan0: acknowledged 192.168.1.109 from 192.168.1.1
,09-08 14:31:55.096  6149  6149 I dhcpcd  : wlan0: leased 192.168.1.109 for 172800 seconds
09-08 14:31:55.413   971  6139 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:55.413   971  6139 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:55.413   971  6139 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:55.413   971  6139 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:55.414   971  6139 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:55.414   971  6139 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:55.414   971  6139 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:55.414   971  6139 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:55.414   971  6139 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-08 14:31:55.419   971  6139 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
09-08 14:31:55.420   971  6139 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:31:55.420   971  6139 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:55.420   971  6139 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:55.420   971  6139 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.109
09-08 14:31:55.420   971  6139 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-08 14:31:55.420   971  6139 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:31:55.420   971  6139 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-08 14:31:55.420   971  6139 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-08 14:31:55.424   971  6143 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
09-08 14:31:55.425   971  6143 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:55.425   971  6143 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:55.425   971  6143 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
09-08 14:31:55.425   971  6143 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:55.426   274  1039 E BandwidthController: [LG DATA] No such appUid: 1000
09-08 14:31:55.426   274  1039 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-08 14:31:55.427   971  6139 D DhcpStateMachine: RunningState
09-08 14:31:55.436   274  6185 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
09-08 14:31:55.436   274  6185 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:55.437   274  6185 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
,09-08 14:31:55.440   274  6185 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:31:55.484   274  6185 D libc-netbsd: res_queryN name = xxxxx succeed
,09-08 14:31:55.489   971  6143 I System.out: propertyValue:false
09-08 14:31:55.489   971  6143 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
09-08 14:31:55.497   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-08 14:31:55.512   971  6138 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:55.512   971  6138 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-08 14:31:55.545  6144  6147 I DSQN    : first global connection report this to start monitoring at DSQM.
09-08 14:31:55.545  6144  6147 I DSQN    : restart monitoring
,09-08 14:31:55.549   274  1043 D LGDataListener: argv[0]=dsqncommand
09-08 14:31:55.549   274  1043 D LGDataListener: argv[1]=wlan0
09-08 14:31:55.549   274  1043 D LGDataListener: argv[2]=1
09-08 14:31:55.549   274  1043 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-08 14:31:55.551   971  1053 D DSQN    : DSQM DsqnNotification wlan0  1
09-08 14:31:55.551   971  1053 D DSQN    : start to monitor internet connection
09-08 14:31:55.552  6144  6187 I DSQN    : dsqn report finish
09-08 14:31:55.634   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:31:55 GMT], X-Android-Received-Millis=[1473337915634], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473337915553]}
09-08 14:31:55.635   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-08 14:31:55.640  1861  1887 D WifiServiceExtension: isInternetCheckAvailable return false
09-08 14:31:55.640   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
09-08 14:31:55.640   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 14:31:55.641   971  1317 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-08 14:31:55.641   971  1317 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-08 14:31:55.641   971  1317 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:55.641   971  1317 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:55.641   971  1317 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 14:31:55.641   971  1317 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:55.642   971  1317 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
09-08 14:31:55.642   971  1317 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-08 14:31:55.642   971  1317 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-08 14:31:55.642   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:55.642   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:55.643   971  1317 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:55.644  1373  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:31:55.645   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:55.645   971  1317 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:55.646  5434  5865 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:31:55.647   971  1317 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:55.649   971  1309 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:55.649   971  1309 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-08 14:31:55.653  1758  1758 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:55.653  1758  1758 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-08 14:31:55.654   971  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 14:31:55.657   971   971 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
09-08 14:31:55.675   971  1309 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
,09-08 14:31:55.679  1373  1373 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:31:55.680  1373  1373 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-08 14:31:55.687  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:31:55.687  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:55.687  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
,09-08 14:31:55.691  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:31:55.691  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:55.691  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
09-08 14:31:55.760   293   349 I ThermalEngine: Sensor:pa_therm0:34000 mC
,09-08 14:31:55.873  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:31:55.873  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:55.873  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,09-08 14:31:55.967   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
,09-08 14:31:55.972   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:55.972   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:55.986   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,09-08 14:31:55.990   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:55.990   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:55.997   971  1317 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-08 14:31:55.997   971  1317 D ConnectivityService: identical MTU - not setting
09-08 14:31:55.998   971  1317 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 14:31:55.998   971  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 14:31:55.998   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:55.998   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:31:55.999   971  1317 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-08 14:31:56.002  1373  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 14:31:56.004   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:56.005   971  1317 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:56.007  5434  5865 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 14:31:56.013   971  1317 D ConnectivityService: Wi-Fi IP changed. Lp difference / No Route difference
09-08 14:31:56.013   971  1317 D DSQN    : enableDataServiceNotify 
09-08 14:31:56.013   971  1317 D DSQN    : start dsqn bin
,09-08 14:31:56.017  1914  1914 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
09-08 14:31:56.021  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:56.02 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-08 14:31:56.031   971  1317 D DSQN    : dsqn is running restart
,09-08 14:31:56.053  6188  6188 I DSQN    : DSQN samuel.seo ver 141203
,09-08 14:31:56.056  6188  6188 E DSQN    : DSQN sock connect success to lgdatalistenerd
09-08 14:31:56.057  6188  6188 I DSQN    : created command queue thread
09-08 14:31:56.057  6188  6188 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-08 14:31:56.057  6188  6188 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
09-08 14:31:56.666  6000  6033 D UEI.SmartControl: Internal timer expired: 1
,09-08 14:31:57.319   971  1307 D LGWifiP2pService: InactiveState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:57.319   971  1307 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:57.319   971  1307 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 14:31:57.737  1914  1914 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,09-08 14:31:57.740  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:31:57.74 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-08 14:31:57.743  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:31:57.743  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:31:57.743  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:31:57.858   971  1312 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-08 14:31:57.917   971  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:57.931  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
,09-08 14:31:57.944  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:31:57.949  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:57.949  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:57.949  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:57.949  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:57.949  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:57.949  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:57.949  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:57.949  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:57.953  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:57.954  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:57.960  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:31:57.965  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:57.965  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:57.965  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:31:57.965  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:57.965  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:57.965  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:57.965  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:57.965  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:57.967  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:31:57.967  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:57.974   971   971 D LocSvc_java: onReceive
09-08 14:31:57.974   971   971 D LocSvc_java: got connectivity action
,09-08 14:31:57.987   971  1743 D AlarmManagerService: Setting time of day to sec=1473337918
,09-08 14:31:58.215   971  1743 W AlarmManagerService: Unable to set rtc to 1473337918: Invalid argument
09-08 14:31:58.233   971   971 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
09-08 14:31:58.233   971   971 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,09-08 14:31:58.239   971   971 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 14:31:58.239   971   971 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 14:31:58.239   971   971 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 14:31:58.239   971   971 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
09-08 14:31:58.255   971  6199 D LocSvc_java: NTP server returned: 1473337915278 (Thu Sep 08 14:31:55 GMT+02:00 2016) reference: 142363 certainty: 14 system time offset: -2976
09-08 14:31:58.255   971  1045 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:58.260   971  6199 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
09-08 14:31:58.262   971  1046 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6200 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:31:58.312   971  1046 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=6216 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-08 14:31:58.340  1373  1373 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
,09-08 14:31:58.343  1373  1373 I LgeClockWidgetControlView: time changed, timezoneChanged : false
09-08 14:31:58.346  2820  2820 D WeatherService: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:31:58
09-08 14:31:58.347  2820  2820 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
09-08 14:31:58.349  2820  2820 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:31:58.349  2820  2820 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
09-08 14:31:58.349  2820  2820 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
09-08 14:31:58.350  2820  2820 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
09-08 14:31:58.351  2820  2820 D WeatherTheme: 2 : Fixed theme : optimus
09-08 14:31:58.353  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
,09-08 14:31:58.381  2820  2820 D WeatherReflect: 2 : Map key string is -2
09-08 14:31:58.384  2820  2820 D lim     : 2 : time = 14:31
,09-08 14:31:58.386  2820  2820 I WeatherReflect: Model Name : LG-D722
09-08 14:31:58.386  2820  2820 D WeatherTheme: 2 : exactly same view!
09-08 14:31:58.386  2820  2820 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
09-08 14:31:58.386  2820  2820 D WeatherService: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:31:58
09-08 14:31:58.418   971  1045 I ActivityManager: Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6245 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
09-08 14:31:58.419   971  1974 W ActivityManager: getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,09-08 14:31:58.437   971  1045 I NotificationManager: android: cancelAsUser(-1597574061) by android
,09-08 14:31:58.452  6216  6216 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:31:58.452  6216  6216 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 14:31:58.453  6216  6216 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-08 14:31:58.457  1737  1737 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
09-08 14:31:58.467  1953  1953 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=8 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
,09-08 14:31:58.486  1953  1953 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 8
09-08 14:31:58.491  6245  6245 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:31:58.491  6245  6245 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 14:31:58.491  6245  6245 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-08 14:31:58.500  1953  1953 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 8
,09-08 14:31:58.507  1953  1953 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-08 14:31:58.508   971  1045 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:58.530   971  1058 I PowerManagerService: ALS enabled for SRE
09-08 14:31:58.530   971  1058 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (25641 ms ago)
,09-08 14:31:58.549   971  1045 E GpsLocationProvider: No APN found to select.
,09-08 14:31:58.569   971  6265 D LgeGpsConstants: Can't find 'ext_gps.conf'!!
,09-08 14:31:58.604   971  6265 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:58.604   971  6265 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:58.604   971  6265 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:58.604   971  6265 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,09-08 14:31:58.608   971  1351 D qdlights: set_light_backlight: 252
09-08 14:31:58.608   274  1039 E BandwidthController: [LG DATA] No such appUid: 1000
09-08 14:31:58.608   274  1039 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-08 14:31:58.608   274  6266 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-08 14:31:58.608   274  6266 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:58.609   274  6266 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-08 14:31:58.609   274  6266 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:31:58.609   971  1351 D qdlights: set_light_backlight: 242
09-08 14:31:58.623   971  1351 D qdlights: set_light_backlight: 239
,09-08 14:31:58.640   971  1351 D qdlights: set_light_backlight: 235
,09-08 14:31:58.657   971  1351 D qdlights: set_light_backlight: 232
,09-08 14:31:58.665  5434  6268 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,09-08 14:31:58.666   274  6266 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:31:58.667   971  6265 I System.out: propertyValue:false
09-08 14:31:58.674   971  1351 D qdlights: set_light_backlight: 229
,09-08 14:31:58.690   971  1351 D qdlights: set_light_backlight: 225
,09-08 14:31:58.708   971  1351 D qdlights: set_light_backlight: 222
,09-08 14:31:58.723   971  1351 D qdlights: set_light_backlight: 219
09-08 14:31:58.725   971  6265 D LgeGpsLocationProvider: NTP server: europe.pool.ntp.org
09-08 14:31:58.725   971  6265 D LgeGpsLocationProvider: NTP server returned: 1473337918742 (Thu Sep 08 14:31:58 GMT+02:00 2016) reference: 145824 certainty: 28 system time offset: 17
,09-08 14:31:58.743   971  1351 D qdlights: set_light_backlight: 215
,09-08 14:31:58.757   971  1351 D qdlights: set_light_backlight: 212
,09-08 14:31:58.765   971  1045 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 36557, reason: UserStart, SyncResult: databaseError: true stats []
09-08 14:31:58.766   971  1045 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 177946, reason: UserStart
09-08 14:31:58.766   971  1045 I NotificationManager: android: cancelAsUser(716319171) by android
09-08 14:31:58.773   971  1351 D qdlights: set_light_backlight: 209
,09-08 14:31:58.790   971  1351 D qdlights: set_light_backlight: 205
,09-08 14:31:58.803  6216  6216 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-08 14:31:58.807   971  1351 D qdlights: set_light_backlight: 202
,09-08 14:31:58.824   971  1351 D qdlights: set_light_backlight: 199
,09-08 14:31:58.842   971  1351 D qdlights: set_light_backlight: 195
,09-08 14:31:58.850  6216  6216 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
09-08 14:31:58.857   971  1351 D qdlights: set_light_backlight: 192
,09-08 14:31:58.873   971  1351 D qdlights: set_light_backlight: 189
,09-08 14:31:58.890   971  1351 D qdlights: set_light_backlight: 185
,09-08 14:31:58.904  6245  6245 I AppConfig: Total System Memory = 906309632
09-08 14:31:58.907   971  1351 D qdlights: set_light_backlight: 182
,09-08 14:31:58.912  6245  6245 I GalleryUtils: Application Heap = 96 MB
09-08 14:31:58.917  6245  6245 I AppConfig: App Tier : NOT_DEF
09-08 14:31:58.923   971  1351 D qdlights: set_light_backlight: 179
,09-08 14:31:58.928  6200  6200 I MusicStore: Database version: 120
09-08 14:31:58.930  6245  6245 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-08 14:31:58.940   971  1351 D qdlights: set_light_backlight: 175
,09-08 14:31:58.953  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-08 14:31:58.956  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-08 14:31:58.957   971  1351 D qdlights: set_light_backlight: 172
09-08 14:31:58.960  5434  6281 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-08 14:31:58.960  5434  6281 D SchedPeriodicTask: Scheduled AdAttestation task.
09-08 14:31:58.969  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-08 14:31:58.974   971  1351 D qdlights: set_light_backlight: 169
09-08 14:31:58.981   971  1045 I NotificationManager: android: cancelAsUser(-1597574061) by android
,09-08 14:31:58.990   971  1351 D qdlights: set_light_backlight: 165
,09-08 14:31:59.007   971  1351 D qdlights: set_light_backlight: 162
,09-08 14:31:59.012   971  1045 I NotificationManager: android: cancelAsUser(353845882) by android
09-08 14:31:59.025   971  1351 D qdlights: set_light_backlight: 159
,09-08 14:31:59.033   971  1045 I NotificationManager: android: cancelAsUser(-1597574061) by android
09-08 14:31:59.040   971  1351 D qdlights: set_light_backlight: 155
,09-08 14:31:59.046  5434  6278 W InstanceID/Rpc: Found 10006
09-08 14:31:59.057   971  1351 D qdlights: set_light_backlight: 152
,09-08 14:31:59.074   971  1351 D qdlights: set_light_backlight: 149
,09-08 14:31:59.088  5434  6264 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,09-08 14:31:59.090   971  1351 D qdlights: set_light_backlight: 145
09-08 14:31:59.093   279  1610 V AudioFlinger: 2103 died, releasing its sessions
09-08 14:31:59.093   279  1610 V AudioFlinger:  pid 1758 @ 0
09-08 14:31:59.093   279  1610 V AudioFlinger:  pid 3073 @ 1
09-08 14:31:59.093   279  1610 V AudioFlinger:  pid 3073 @ 2
09-08 14:31:59.098   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:31:59.098   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-08 14:31:59.098   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:31:59.099  6200  6200 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,09-08 14:31:59.108   971  1351 D qdlights: set_light_backlight: 142
09-08 14:31:59.123   971  1351 D qdlights: set_light_backlight: 139
,09-08 14:31:59.140   971  1351 D qdlights: set_light_backlight: 135
09-08 14:31:59.149   971  1901 I ActivityManager: Process com.lge.music (pid 2103) has died
,09-08 14:31:59.157   971  1351 D qdlights: set_light_backlight: 132
09-08 14:31:59.173   971  1351 D qdlights: set_light_backlight: 129
,09-08 14:31:59.190   971  1351 D qdlights: set_light_backlight: 125
,09-08 14:31:59.207   971  1351 D qdlights: set_light_backlight: 122
09-08 14:31:59.222   971  1974 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6291 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,09-08 14:31:59.223   971  1351 D qdlights: set_light_backlight: 119
09-08 14:31:59.256   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:31:59.256   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-08 14:31:59.256   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:31:59.258   971  1351 D qdlights: set_light_backlight: 112
,09-08 14:31:59.261  6200  6200 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-08 14:31:59.265   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:31:59.265   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,09-08 14:31:59.265   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:31:59.266  6200  6200 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-08 14:31:59.271   971  1045 I NotificationManager: android: cancelAsUser(-591465577) by android
09-08 14:31:59.273   971  1351 D qdlights: set_light_backlight: 109
,09-08 14:31:59.291   971  1351 D qdlights: set_light_backlight: 105
,09-08 14:31:59.299   971  1312 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:59.299   971  1312 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:59.300   971  1312 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:59.300   971  1312 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:59.300   274  1039 E BandwidthController: [LG DATA] No such appUid: 1000
09-08 14:31:59.300   274  1039 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-08 14:31:59.301   274  6310 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-08 14:31:59.301   274  6310 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:59.301   274  6310 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-08 14:31:59.301   274  6310 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:31:59.307   971  1351 D qdlights: set_light_backlight: 102
,09-08 14:31:59.323   971  1351 D qdlights: set_light_backlight: 99
,09-08 14:31:59.327   971  1045 I NotificationManager: android: cancelAsUser(353845882) by android
09-08 14:31:59.340   971  1351 D qdlights: set_light_backlight: 95
,09-08 14:31:59.343   274  6310 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:31:59.345   971  1312 I System.out: propertyValue:false
,09-08 14:31:59.348   971  1313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:59.348   971  1313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:31:59.349   971  1313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:31:59.349   971  1313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:59.349   274  1039 E BandwidthController: [LG DATA] No such appUid: 1000
09-08 14:31:59.349   274  1039 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-08 14:31:59.350   274  6315 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-08 14:31:59.350   274  6315 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:31:59.351   274  6315 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-08 14:31:59.351   274  6315 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:31:59.351   274  6315 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:31:59.351   971  1313 I System.out: propertyValue:false
09-08 14:31:59.357   971  1351 D qdlights: set_light_backlight: 92
,09-08 14:31:59.362  6200  6200 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-08 14:31:59.364  6200  6200 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-08 14:31:59.373   971  1351 D qdlights: set_light_backlight: 89
,09-08 14:31:59.383  6188  6189 I DSQN    : first global connection report this to start monitoring at DSQM.
09-08 14:31:59.383  6188  6189 I DSQN    : restart monitoring
09-08 14:31:59.383   274  1043 D LGDataListener: argv[0]=dsqncommand
09-08 14:31:59.383   274  1043 D LGDataListener: argv[1]=wlan0
09-08 14:31:59.383   274  1043 D LGDataListener: argv[2]=1
09-08 14:31:59.383   274  1043 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-08 14:31:59.383  6188  6316 I DSQN    : dsqn report finish
09-08 14:31:59.384   971  1053 D DSQN    : DSQM DsqnNotification wlan0  1
09-08 14:31:59.384   971  1053 D DSQN    : start to monitor internet connection
09-08 14:31:59.391   971  1351 D qdlights: set_light_backlight: 85
,09-08 14:31:59.407   971  1351 D qdlights: set_light_backlight: 82
,09-08 14:31:59.408   971  1313 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-08 14:31:59.424   971  1351 D qdlights: set_light_backlight: 79
,09-08 14:31:59.440   971  1351 D qdlights: set_light_backlight: 75
,09-08 14:31:59.457   971  1351 D qdlights: set_light_backlight: 72
,09-08 14:31:59.459  6200  6200 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
09-08 14:31:59.473   971  1351 D qdlights: set_light_backlight: 69
,09-08 14:31:59.490   971  1351 D qdlights: set_light_backlight: 65
,09-08 14:31:59.496   971  1974 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6318 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
09-08 14:31:59.507   971  1351 D qdlights: set_light_backlight: 62
09-08 14:31:59.527   971  1351 D qdlights: set_light_backlight: 59
09-08 14:31:59.528  6291  6327 D ALBootInit: ====action==>android.intent.action.TIME_SET
,09-08 14:31:59.533  6291  6327 D ALBootInit: Alarm ALBootInit: TIME_SET
09-08 14:31:59.537  6291  6327 D Alarms  : [setNextAlert] start
09-08 14:31:59.541   971  1351 D qdlights: set_light_backlight: 55
09-08 14:31:59.557   971  1351 D qdlights: set_light_backlight: 52
,09-08 14:31:59.569  6291  6327 D Alarms  : [setNextAlert] (1)
,09-08 14:31:59.572  6291  6327 D Alarms  :  minTime  = 0
09-08 14:31:59.574   971  1351 D qdlights: set_light_backlight: 49
09-08 14:31:59.582  6291  6327 D Alarms  :  -- OK multi -- 0
,09-08 14:31:59.583  6291  6327 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
09-08 14:31:59.583  6291  6327 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
09-08 14:31:59.586  6200  6200 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-08 14:31:59.586  6200  6200 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@243f7074: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-08 14:31:59.587  6200  6200 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-08 14:31:59.587  6200  6200 D AndroidMusic: GMSCore installation verified
09-08 14:31:59.590   971  1351 D qdlights: set_light_backlight: 45
09-08 14:31:59.593  6318  6318 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-08 14:31:59.593  6318  6318 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-08 14:31:59.604  6291  6327 I CommonUtil: BUILD Operator: OPEN
09-08 14:31:59.607   971  1351 D qdlights: set_light_backlight: 42
09-08 14:31:59.607  6200  6200 I ConfigStore: Config Database version: 1
,09-08 14:31:59.609  6291  6327 D Alarms  : broadcastToWidgetProvider : false
09-08 14:31:59.613  6291  6327 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
09-08 14:31:59.623   971  1351 D qdlights: set_light_backlight: 39
,09-08 14:31:59.640   971  1351 D qdlights: set_light_backlight: 35
09-08 14:31:59.643  6318  6318 I MultiDex: VM with version 2.1.0 has multidex support
09-08 14:31:59.643  6318  6318 I MultiDex: install
09-08 14:31:59.643  6318  6318 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-08 14:31:59.657   971  1351 D qdlights: set_light_backlight: 32
09-08 14:31:59.673   971  1351 D qdlights: set_light_backlight: 29
,09-08 14:31:59.679   971  2043 I ActivityManager: Process com.lge.lgdmsclient (pid 5949) has died
09-08 14:31:59.682   971  1951 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
09-08 14:31:59.686  6291  6291 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
,09-08 14:31:59.688  6291  6291 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@33117216
09-08 14:31:59.690   971  1351 D qdlights: set_light_backlight: 25
09-08 14:31:59.693  6291  6291 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@33117216
,09-08 14:31:59.705  6291  6291 D QuickCoverProvider: onReceiver
09-08 14:31:59.707   971  1351 D qdlights: set_light_backlight: 22
09-08 14:31:59.713  6318  6318 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
09-08 14:31:59.752   971  1324 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6340 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:31:59.753   971  1351 D qdlights: set_light_backlight: 15
,09-08 14:31:59.775   971  1351 D qdlights: set_light_backlight: 10
,09-08 14:31:59.779   971  1045 I NotificationManager: android: cancelAsUser(-591465577) by android
09-08 14:31:59.787  6318  6318 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-08 14:31:59.788  6318  6318 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@25a3e5a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-08 14:31:59.790  6318  6318 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-08 14:31:59.793  6318  6318 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
,09-08 14:31:59.794  6318  6318 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
,09-08 14:31:59.810  6318  6318 D ChimeraCfgMgr: Reading stored module config
,09-08 14:31:59.849  5453  5468 I art     : Explicit concurrent mark sweep GC freed 1550(67KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 790us total 40.170ms
09-08 14:31:59.857  6340  6340 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:31:59.957  6318  6358 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-08 14:32:00.014   971   988 I art     : Explicit concurrent mark sweep GC freed 106834(5MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 1.850ms total 178.924ms
,09-08 14:32:00.029   971  2043 I ActivityManager: Process com.lge.bnr (pid 5594) has died
,09-08 14:32:00.030   971  1285 D PowerManagerServiceEx: acquireWakeLockInternal: lock=304840138, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=971
09-08 14:32:00.032  6340  6340 D CalendarApplication: CalendarApplication.onCreate()
09-08 14:32:00.035   971  1869 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:00.035   971  1869 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@15fb9d0c mBinding = false
,09-08 14:32:00.047   971  1055 D BluetoothManagerService: Message: 2
,09-08 14:32:00.049   971   971 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:32:00.049   971   971 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:32:00.049   971   971 D Ulp_jni : JNI:system_update. Event-4
09-08 14:32:00.049  6340  6340 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
09-08 14:32:00.049  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:00.050   971  1055 D BluetoothManagerService: Sending off request.
09-08 14:32:00.050  6340  6340 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2d7e68b5, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@13b7eb4a, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@343beabb, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@6aa1bd8, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@bf9db31, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@33117216, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@22347797, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@22911d84, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@6dff96d, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2aa99a2, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@12bef633, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@8c48df0, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@168fbf69, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1bbcadee, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@68c28f, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@217c991c, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@5be925, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1fc9bafa, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1738f8ab, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3e482b08, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1206f2a1, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@14688cc6, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@328c7487, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@38b8efb4, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@18ff17dd, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2fd0af52, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1cb1d223, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@fcf5320, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@115a54d9, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@22266e9e, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2c456d7f, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3026814c, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@8926595, lg_preferences_week_start_day=com.android.calendar.adaptatio,n.PreferenceKey$KeyData@2786d6aa, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1b4d629b, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@12e06638, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3000c611, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2ed3b376, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@34158d77, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1f51ade4, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1b1ab24d, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@213f9102,
09-08 14:32:00.056  2082  3270 D BluetoothAdapterService(579935620): disable() called...
09-08 14:32:00.058  6340  6340 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
09-08 14:32:00.063  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:00.064  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:00.064  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:00.065  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:00.065  6340  6340 D Config  : [init]
09-08 14:32:00.065  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:00.065  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:00.065  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:00.065  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:00.065  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34f5764d removed from the list
09-08 14:32:00.065  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:00.065  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@231d0502 removed from the list
09-08 14:32:00.065  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:00.065  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:00.065  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:00.066  6340  6340 I Config  : LGCalendar ver.4.40.17
09-08 14:32:00.066  2082  2215 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-08 14:32:00.066  6340  6340 I Config  : start check model
09-08 14:32:00.066  6340  6340 I Config  : start check native_ca
09-08 14:32:00.066  2082  2215 D BluetoothAdapterProperties: Setting state to 13
09-08 14:32:00.066  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:32:00.066  2082  2215 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 14:32:00.066  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f0a5850 added. We now have 2 listener(s)
09-08 14:32:00.066   971  1869 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:00.067  2082  2215 D BluetoothAdapterService(579935620): updateAdapterState() - Broadc,asting state to 1 receivers.
09-08 14:32:00.067  6340  6340 I Config  : Config Operator=OPEN, Country=EU
09-08 14:32:00.067  6340  6340 D Config  : [setDefaultValuesToPref]
09-08 14:32:00.067  6340  6340 D Config  : [parseProfiles]
09-08 14:32:00.069  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-08 14:32:00.069  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:32:00.069  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:32:00.069  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:32:00.069  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c302a49 added. We now have 2 listener(s)
09-08 14:32:00.069  5737  5825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:32:00.073  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:32:00.075  6340  6340 D ProfilesParser: [debug_displayParseInfos] profile.country = null
09-08 14:32:00.075  6340  6340 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
09-08 14:32:00.075  6340  6340 D Config  : [updateProfiletoCountryInfo]
09-08 14:32:00.076  6340  6340 D GeneralPreference: [checkAndMigrateOldPreference]
09-08 14:32:00.081  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:00.081  2082  2215 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 14:32:00.092  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:00.092  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:32:00.092  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:00.092  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:00.092  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:00.092  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:00.092  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.092  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:00.092  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:00.094  2082  2215 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-08 14:32:00.094  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:00.094  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.095  5737  5825 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:32:00.095  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:00.095  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:00.095  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:00.095  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:00.095  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f0a5850 removed from the list
09-08 14:32:00.095  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:00.095  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c302a49 removed from the list
09-08 14:32:00.100  2082  2244 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
09-08 14:32:00.100  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.104  6340  6340 E AgendaWidgetManager: [updateWidgets] 
09-08 14:32:00.104  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.104  2082  2244 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:32:00.106  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:00.106  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:00.106  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:00.106  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:00.106  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:00.106  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:00.106  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.106  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:00.106  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:00.107  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:00.107  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.109  2082  2215 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-08 14:32:00.109  2082  2215 I bt-btif : BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
09-08 14:32:00.109  2082  2215 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1,, vhci_init:1
09-08 14:32:00.110  2082  2215 D bt-btif : btsock_ctrl_hci_cleanup(L202): poll handle:4
09-08 14:32:00.111  2082  2215 I bt-btif : BTA_JvDeleteRecord
09-08 14:32:00.111  2082  2215 I bt-btif : BTA_JvRfcommStopServer
09-08 14:32:00.111  2082  2215 I bt-btif : BTA_JvDeleteRecord
09-08 14:32:00.111  2082  2215 I bt-btif : BTA_JvRfcommStopServer
09-08 14:32:00.111  2082  3485 W bt-btif : invalid rfc slot id: 1
09-08 14:32:00.112  2082  2215 D IOP_DB_BT: db_close: nbr users 0
09-08 14:32:00.112  2082  2215 D IOP_DB_BT: db_close: free database
09-08 14:32:00.113  2082  2215 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L300): in, key:Adapter, value:BluezMigrationDone
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L343): out, key:Adapter, value:BluezMigrationDone
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L300): in, key:Adapter, value:Address
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L343): out, key:Adapter, value:Address
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L344): out, value:f8:95:c7:87:85:54
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L300): in, key:Adapter, value:Name
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L343): out, key:Adapter, value:Name
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L344): out, value:G3s-1
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
09-08 14:32:00.113  2082  2215 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:��8�\�婓��n�ScanMode
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:Adapter, value:ScanMode
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:Adapter, value:ScanMode
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:x
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:s!WE�(E��00:0F:F6
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:BMW,Audi,Parrot,Car
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:00:0F:F6
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
09-08 14:32:00.114  2082  2215 D btif_config_util: enum_config(L344): out, value:�
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:HTC Desire 820
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
09-08 14:32:00.115  2082  3365 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:$
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:Galaxy S6-1
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
09-08 14:32:00.115  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L344): out, value:�
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
09-08 14:32:00.116  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L344): out, value:A5-1
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
09-08 14:32:00.118  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.118  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:00.118  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:00.117  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L344): out, value:#
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
09-08 14:32:00.118  2082  2215 D btif_config_util: enum_config(L344): out, value:Nexus 6
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.119  2082  2215 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
09-08 14:32:00.120  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
09-08 14:32:00.120  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:32:00.120  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@113f586f added. We now have 2 listener(s)
09-08 14:32:00.120   971  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:00.121  2082  2244 E bt-btif : btif_hf_upstreams_evt: wrong handle = 1280 
09-08 14:32:00.120  2082  2215 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
09-08 14:32:00.121  2082  3512 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L344): out, value:�
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L344): out, value:XT1072
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
,09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.121  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L344): out, value:a
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L344): out, value:S5-1
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
09-08 14:32:00.122  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
09-08 14:32:00.123  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L344): out, value:	a
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L344): out, value:G4-1
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
09-08 14:32:00.123  2082  2215 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:a
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy S5)
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:�
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy A5)
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.124  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:�
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy A3)
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
09-08 14:32:00.125  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L344): out, value:A
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L344): out, value:Thali Test's G2
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.126  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
09-08 14:32:00.127  2082  3365 W bt-obex : Ignore event 10 in state 1
09-08 14:32:00.127  2082  2244 I bt-btif : HAL bt_op_callbacks->ops_state_cb
09-08 14:32:00.127  2082  2244 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:3
09-08 14:32:00.127  2082  3365 W bt-obex : Ignore event 10 in state 1
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L344): out, value:	a
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L344): out, value:Note3-1
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.128  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
09-08 14:32:00.128  2082  2244 D OppService: onOpsStateChange() :3
09-08 14:32:00.129  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
09-08 14:32:00.129  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
09-08 14:32:00.129  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.129  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
09-08 14:32:00.129  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
09-08 14:32:00.129  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
09-08 14:32:00.129  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
09-08 14:32:00.129  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
09-08 14:32:00.129  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
09-08 14:32:00.129  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
09-08 14:32:00.129  2082  2082 D OppService: Recieved MESSAGE_OPS_DISABLE
09-08 14:32:00.129  2082  3365 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-08 14:32:00.129  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L344): out, value:�
09-08 14:32:00.130   971  1055 D BluetoothManagerService: Message: 60
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L344): out, value:A3-1
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
09-08 14:32:00.130  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
09-08 14:32:00.131  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.131  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
09-08 14:32:00.131  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
09-08 14:32:00.131  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
09-08 14:32:00.131  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Manufacturer, value type:int
09-08 14:32:00.132  2082  2215 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
09-08 14:32:00.133  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.133  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-08 14:32:00.133  2082  2215 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
09-08 14:32:00.133  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
09-08 14:32:00.133  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:32:00.133  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:32:00.133  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:32:00.133  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c4a97c added. We now have 2 listener(s)
09-08 14:32:00.133  5737  5825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
09-08 14:32:00.134   971  1055 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-08 14:32:00.134   971  1055 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L344): out, value:�
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L344): out, value:XT1039
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
09-08 14:32:00.134  2082  2215 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L344): out, value:	a
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
09-08 14:32:00.135  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L344): out, value:Nexus 5
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:JustWorks, value type:int
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.136  2082  2215 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L344): out, value:�
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L344): out, value:HTC One_M8
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.137  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L344): out, value:"
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L344): out, value:Note4-1
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.138  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L344): out, value:
,09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.139  2082  2215 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:Manufacturer
09-08 14:32:00.140  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Manufacturer, value type:int
09-08 14:32:00.140  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
09-08 14:32:00.141  2082  2215 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
09-08 14:32:00.141  2082  2215 D btif_config_util: enum_config(L344): out, value:�
09-08 14:32:00.141  1861  1861 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:00.141  2082  2215 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
09-08 14:32:00.141  2082  2215 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
09-08 14:32:00.141  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
09-08 14:32:00.142  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:JustWorks, value type:int
09-08 14:32:00.143  2082  2215 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
09-08 14:32:00.143  2082  2215 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
09-08 14:32:00.143  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 00006675-7475-7265-6469-616c62756d70 
09-08 14:32:00.143  2082  2215 D btif_config_util: enum_config(L300): in, key:58:3f:54:73:64:c0, value:Manufacturer
09-08 14:32:00.144  2082  2215 D btif_config_util: enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
09-08 14:32:00.144  2082  2215 D btif_config_util: enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
09-08 14:32:00.144  2082  2082 D BluetoothMapService: STATE_TURNING_OFF
09-08 14:32:00.144  2082  2215 D btif_config_util: enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevType
09-08 14:32:00.148  2082  2215 D btif_config_util: enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
09-08 14:32:00.148  2082  2215 D btif_config_util: enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
09-08 14:32:00.149  2082  2215 D btif_config_util: enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
09-08 14:32:00.149  2082  2215 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
09-08 14:32:00.149  2082  2215 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:f3, value:Name
09-08 14:32:00.149  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:Name, value type:string
09-08 14:32:00.149  2082  2215 D btif_config_util: enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
09-08 14:32:00.149  2082  2215 D btif_config_util: enum_config(L344): out, value:T\���K�`�D�`�D�
09-08 14:32:00.149  2082  2215 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
09-08 14:32:00.150  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
09-08 14:32:00.150  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.150  2082  2215 D btif_config_util: enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
09-08 14:32:00.150  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Name, value type:string
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L344): out, value:ALE-L21
09-08 14:32:00.151  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevClass
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L344): out, value:Z
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
09-08 14:32:00.151  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
09-08 14:32:00.151  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L344): out, value:`��
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevType, value type:int
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevType
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevType
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevClass, value type:int
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevClass
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevType
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevType
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L344): out, value:
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:9e, value:Name
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:Name, value type:string
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:9e, value:Name
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L344): out, value:4g�
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevClass, value type:int
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:9e, value:DevClass
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:9e, value:DevType
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:Name
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L344): out, value:4g�������v��
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevClass, value type:int
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
09-08 14:32:00.155  2082  2215 D btif_config_util: enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevType
09-08 14:32:00.156  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:00.156  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:32:00.156  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:00.156  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:00.156  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:00.156  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:00.156  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.156  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:00.156  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:00.156  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:00.156  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.157  5737  5825 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:32:00.159  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.160  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.164   971  1383 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:00.164   971  1383 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@15fb9d0c mBinding = false
09-08 14:32:00.165   971  1055 D BluetoothManagerService: Message: 2
09-08 14:32:00.165   971  1055 D BluetoothManagerService: Sending off request.
09-08 14:32:00.167  2082  3511 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-08 14:32:00.167  2082  3511 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 14:32:00.167  2082  3511 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-08 14:32:00.167  2082  3511 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-08 14:32:00.167  2082  3511 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-08 14:32:00.167  2082  3511 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-08 14:32:00.167  2082  3511 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-08 14:32:00.167  2082  3511 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-08 14:32:00.172  2082  2082 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 14:32:00.172  2082  2082 V BluetoothMapService: MAP Service closeService out
09-08 14:32:00.172  2082  2102 D BluetoothAdapterService(579935620): disable() called...
09-08 14:32:00.175  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:00.175  2082  2102 D BluetoothAdapterService: disable() : BT State is not STATE_ON. Can't disable BT
09-08 14:32:00.175   971  1055 E BluetoothManagerService: IBluetooth.disable() returned false
09-08 14:32:00.205  6340  6368 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
09-08 14:32:00.207  6318  6318 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-08 14:32:00.208  6318  6318 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-08 14:32:00.229  6340  6368 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,09-08 14:32:00.267  1737  1737 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=2f481dec-86a2-45ef-99eb-b4f9a74cff97
,09-08 14:32:00.284  6340  6368 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,09-08 14:32:00.290  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
09-08 14:32:00.295  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
09-08 14:32:00.302  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,09-08 14:32:00.307  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-08 14:32:00.307  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-08 14:32:00.308  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
09-08 14:32:00.308  6200  6200 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
09-08 14:32:00.310  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
09-08 14:32:00.311  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-08 14:32:00.311  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-08 14:32:00.312  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-08 14:32:00.312  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
09-08 14:32:00.312  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-08 14:32:00.316  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
09-08 14:32:00.320  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,09-08 14:32:00.326  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
09-08 14:32:00.329  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
09-08 14:32:00.334  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,09-08 14:32:00.337  6200  6200 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
09-08 14:32:00.342  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
09-08 14:32:00.350  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,09-08 14:32:00.353  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
09-08 14:32:00.357  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
09-08 14:32:00.362  6340  6368 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
09-08 14:32:00.362  6340  6368 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
09-08 14:32:00.363  6200  6200 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-08 14:32:00.367  6340  6368 I AlertUtils: set default noti to content://media/internal/audio/media/38
,09-08 14:32:00.386  6340  6368 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
09-08 14:32:00.411  6318  6334 I art     : CheckpointMarkThreadRoots callback created = 0xb042d380
,09-08 14:32:00.446  6200  6230 I art     : CheckpointMarkThreadRoots callback created = 0xb042d410
09-08 14:32:00.450  6318  6334 I art     : CheckpointMarkThreadRoots callback created = 0xb042d370
,09-08 14:32:00.474  6200  6200 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-08 14:32:00.508  6318  6334 I art     : Background partial concurrent mark sweep GC freed 1553(253KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 5.718ms total 96.941ms
,09-08 14:32:00.518   279  1610 D WVCdm   : Instantiating CDM.
09-08 14:32:00.518  6200  6230 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3e0
09-08 14:32:00.519   279  1295 I WVCdm   : CdmEngine::OpenSession
09-08 14:32:00.519   279  1295 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
09-08 14:32:00.533  6216  6216 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-08 14:32:00.538  6200  6230 W art     : Suspending all threads took: 6.412ms
09-08 14:32:00.562  6200  6200 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,09-08 14:32:00.580  6200  6200 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 14:32:00.593   279  1295 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
09-08 14:32:00.594   279  1295 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
09-08 14:32:00.594   279  1295 W WVCdm   : L1 library not specified. Falling Back to L3
09-08 14:32:00.597  1737  2482 W GCoreFlp: No location to return for getLastLocation()
,09-08 14:32:00.621  6340  6385 W HolidayIntentService: onHandleIntent
,09-08 14:32:00.623  6340  6340 D MonthWidgetProvider: [onReceive]
09-08 14:32:00.624  6340  6340 D CalendarWidgetProvider: [onReceive]
09-08 14:32:00.624  6340  6340 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
09-08 14:32:00.624  6340  6385 D HolidayDataLoader: readJsonAsset : holiday.json
09-08 14:32:00.626  6340  6340 D CalendarTypeController: [onUpdateAndInitCalendarTime]
09-08 14:32:00.671   971  1901 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6386 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-08 14:32:00.691   279  1295 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-08 14:32:00.696   279  1608 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-08 14:32:00.696   279  1608 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-08 14:32:00.696   279  1608 I WVCdm   : CdmEngine::GenerateKeyRequest
09-08 14:32:00.699  6340  6340 D WeekWidgetProvider: [onReceive]
09-08 14:32:00.699  6340  6340 D CalendarWidgetProvider: [onReceive]
09-08 14:32:00.699  6340  6340 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
09-08 14:32:00.701  6340  6340 D CalendarTypeController: [onUpdateAndInitCalendarTime]
,09-08 14:32:00.701   279  1608 D WVCdm   : PrepareKeyRequest: nonce=1302389228
09-08 14:32:00.701  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:00.702  6340  6385 E HolidayIntentService: onHandleIntent:holiday data empty
09-08 14:32:00.706   971  1640 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:00.707   971  1640 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@15fb9d0c mBinding = false
,09-08 14:32:00.720   971  1055 D BluetoothManagerService: Message: 1
09-08 14:32:00.720   971  1055 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@15fb9d0c
09-08 14:32:00.720   971   971 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:32:00.721   971   971 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:32:00.721   971   971 D Ulp_jni : JNI:system_update. Event-4
,09-08 14:32:00.724  2820  2820 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:32:0
09-08 14:32:00.729  2820  2820 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:32:00.729  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:00.729  2082  3270 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-08 14:32:00.730   971  1055 E BluetoothManagerService: IBluetooth.enable() returned false
09-08 14:32:00.731  2820  2820 D Weather_cast: 2 : set auto-update time : 9/8 17:32
09-08 14:32:00.740  2820  2820 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:32:0
09-08 14:32:00.740  2820  2820 D WeatherService: 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
,09-08 14:32:00.766  6216  6216 I HubEmail: JNI_OnLoad()
09-08 14:32:00.766  6216  6216 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:32:00.766  6216  6216 I HubEmail: registerNatives()
09-08 14:32:00.766  6216  6216 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:32:00.766  6216  6216 I HubEmail: registerNativeMethods()
09-08 14:32:00.766  6216  6216 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:32:00.767  6216  6216 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-08 14:32:00.799   971  1951 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6407 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
09-08 14:32:00.800   971   988 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
09-08 14:32:00.801  2820  2820 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
09-08 14:32:00.802  6216  6406 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:32:00.850  2820  2820 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
09-08 14:32:00.850  2820  2820 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,09-08 14:32:00.855  6318  6336 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:00.855  6318  6336 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:00.856  6318  6336 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:00.856  6318  6336 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:00.856   274  1039 E BandwidthController: [LG DATA] No such appUid: 10006
09-08 14:32:00.856   274  1039 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-08 14:32:00.858   274  6419 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-08 14:32:00.858   274  6419 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:00.860   274  6419 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-08 14:32:00.860   274  6419 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:00.885  6386  6386 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:00.886  6386  6386 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-08 14:32:00.891  6386  6386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:32:00.906   274  6419 D libc-netbsd: res_queryN name = xxxxx succeed
,09-08 14:32:00.908  6318  6336 I System.out: propertyValue:false
09-08 14:32:00.915  1737  2342 I art     : Explicit concurrent mark sweep GC freed 49225(2MB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 14MB/24MB, paused 2.341ms total 216.926ms
09-08 14:32:00.939   971  1900 I ActivityManager: Process com.android.settings (pid 5882) has died
,09-08 14:32:00.945  6386  6386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:32:00.974  6386  6430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:00.976  6386  6430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:32:00.977  6318  6336 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:00.977  6318  6336 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-08 14:32:00.982  6386  6428 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:32:00.985  6386  6428 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 14:32:00.987   293   349 I ThermalEngine: Sensor:pa_therm0:35000 mC
09-08 14:32:00.992  6407  6407 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1473337920992
09-08 14:32:00.992  6407  6407 D         : TimeServiceNative: User Time to be set is 1473337920992
09-08 14:32:00.992  6407  6407 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
09-08 14:32:00.992  6407  6407 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
09-08 14:32:00.992  6407  6407 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1473337920992
,09-08 14:32:00.993  6407  6407 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-08 14:32:00.994   354  1051 D QC-time-services: Daemon: Connection accepted:time_genoff
09-08 14:32:00.995   354  6434 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1473337920992
09-08 14:32:00.995   354  6434 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1473337920992, operation = 0
09-08 14:32:00.995   354  6434 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/20/71 16:32:21
09-08 14:32:00.995   354  6434 D QC-time-services: Daemon:Value read from RTC seconds = 33237141000
09-08 14:32:00.995   354  6434 D QC-time-services: Daemon:new time 1473337920992 
09-08 14:32:00.995   354  6434 D QC-time-services: Daemon: delta 1440100779992 genoff 1440100779992 
09-08 14:32:00.995   354  6434 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100779992 to memory
09-08 14:32:00.995   354  6434 D QC-time-services: Daemon:Opening File: /data/time/ats_2
09-08 14:32:00.995   354  6434 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
09-08 14:32:01.001   354  6434 D QC-time-services: Updating the TOD offset
09-08 14:32:01.001   354  6434 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100779992 to memory
09-08 14:32:01.001   354  6434 D QC-time-services: Daemon:Opening File: /data/time/ats_1
09-08 14:32:01.001   354  6434 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
09-08 14:32:01.005   354  6434 E QC-time-services: Daemon:Update to modem bit set
09-08 14:32:01.005   354  6434 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
09-08 14:32:01.005   354  6434 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124135979992
09-08 14:32:01.005  6407  6407 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
09-08 14:32:01.006   971  2043 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6435 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-08 14:32:01.009   354  1049 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
09-08 14:32:01.009   354  1051 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
09-08 14:32:01.011  6200  6280 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
09-08 14:32:01.013  6386  6428 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 14:32:01.036  6386  6386 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,09-08 14:32:01.036  6386  6386 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-08 14:32:01.037  6386  6386 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 14:32:01.039  6386  6386 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 14:32:01.046  6386  6386 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,09-08 14:32:01.086  5434  6304 D UdcContextInitService: registered all accounts: true
09-08 14:32:01.113   971  1324 I ActivityManager: Killing 6000:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,09-08 14:32:01.123  2082  3388 W bt_userial: select_read return size <=0:0, exiting userial_read_thread
09-08 14:32:01.124  2082  3367 D bt_hwcfg: hw_epilog_process
09-08 14:32:01.124  2082  2244 I bt_userial_vendor: device fd = 70 close
09-08 14:32:01.125  2082  3365 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 14:32:01.125  2082  3365 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:32:01.125  2082  3365 W bt-btif : ag scb idx 1 not allocated
09-08 14:32:01.125  2082  3365 E bt-btif : BTA AG is already disabled, ignoring ...
09-08 14:32:01.125  2082  3365 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:32:01.125  2082  3365 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:32:01.125  2082  3365 W bt-btif : ag scb idx 1 not allocated
09-08 14:32:01.125  2082  3365 E bt-btif : BTA AG is already disabled, ignoring ...
09-08 14:32:01.125  2082  3365 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-08 14:32:01.125  2082  3365 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-08 14:32:01.141  2082  2244 E bt_vendor: [BTUI] Proto is enabled. Set Proto disable!!
,09-08 14:32:01.186  6435  6435 I AppUp4:AppBoxCP: onCreate
,09-08 14:32:01.189  6435  6435 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-08 14:32:01.198  6435  6435 I AppUp4:DB:  setFingerPrint start
,09-08 14:32:01.199  6435  6435 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
09-08 14:32:01.205  6435  6435 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-08 14:32:01.205  6435  6435 I AppUp4:DB:  SDK version = 21
09-08 14:32:01.205  6435  6435 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-08 14:32:01.245  2082  2244 I GKI_LINUX: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,09-08 14:32:01.373  1737  2465 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-08 14:32:01.429   971  1951 I ActivityManager: Process com.lge.qremote (pid 5978) has died
,09-08 14:32:01.429   243   243 E lowmemorykiller: Error opening /proc/6000/oom_score_adj; errno=2
09-08 14:32:01.442   971  1951 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
09-08 14:32:01.442   971  1951 W ActivityManager: android.os.DeadObjectException
09-08 14:32:01.442   971  1951 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
,09-08 14:32:01.442   971  1951 W ActivityManager: Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
09-08 14:32:01.442   971  1951 W ActivityManager: android.os.DeadObjectException
09-08 14:32:01.442   971  1951 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
09-08 14:32:01.442   971  1951 W ActivityManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
09-08 14:32:01.444   971  6413 W libprocessgroup: failed to open /acct/uid_10089/pid_6000/cgroup.procs: No such file or directory
09-08 14:32:01.454  2082  3365 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-08 14:32:01.454  2082  2244 I GKI_LINUX: GKI_destroy_task(): task [BTU] terminated
09-08 14:32:01.455  2082  2244 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
09-08 14:32:01.455  2082  2215 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-08 14:32:01.457  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.457  2082  2215 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-08 14:32:01.457  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.458  2082  2215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 14:32:01.463  6435  6435 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: Unable to read settings
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:32:01.469  2082  2215 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 14:32:01.469  2082  2215 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-08 14:32:01.469  2082  2215 D BluetoothAdapterService(579935620): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,09-08 14:32:01.473  6435  6435 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 14:32:01.473  6435  6435 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:01.474  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.474  2082  2215 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-08 14:32:01.474  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.474  2082  2215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-08 14:32:01.475  2082  2215 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-08 14:32:01.475  2082  2215 D BluetoothAdapterService(579935620): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
09-08 14:32:01.475  6435  6435 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 14:32:01.475  6435  6435 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 14:32:01.477  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.477  2082  2215 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-08 14:32:01.477  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.477  2082  2215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 14:32:01.477  2082  2215 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-08 14:32:01.478  2082  2215 D BluetoothAdapterService(579935620): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
09-08 14:32:01.479  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.479  2082  2215 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-08 14:32:01.479  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.479  2082  2215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-08 14:32:01.479  2082  2215 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-08 14:32:01.479  2082  2215 D BluetoothAdapterService(579935620): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
09-08 14:32:01.480  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.480  2082  2215 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-08 14:32:01.480  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.480  2082  2082 D HeadsetService: Received stop request...Stopping profile...
09-08 14:32:01.480  2082  2215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 14:32:01.482  2082  2215 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-08 14:32:01.482  2082  2215 D BluetoothAdapterService(579935620): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
09-08 14:32:01.484  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.484  2082  2215 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-08 14:32:01.484  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.484  2082  2215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-08 14:32:01.486  2082  2082 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-08 14:32:01.486  2082  2215 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-08 14:32:01.486  2082  2215 D BluetoothAdapterService(579935620): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
09-08 14:32:01.486  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.487  2082  2215 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-08 14:32:01.487  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.487  2082  2215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 14:32:01.487  2082  2215 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-08 14:32:01.488  2082  2215 D BluetoothAdapterService(579935620): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
09-08 14:32:01.488  2082  2082 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 14:32:01.489  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.489  2082  2215 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-08 14:32:01.489  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.489  2082  3307 D HeadsetStateMachine: Exit Disconnected: -1
09-08 14:32:01.489  2082  2215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 14:32:01.490  2082  2082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22911d84
09-08 14:32:01.490  2082  2215 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-08 14:32:01.490  2082  2215 D BluetoothAdapterService(579935620): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
09-08 14:32:01.491  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.491  2082  2215 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
09-08 14:32:01.491  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.491  2082  2215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
09-08 14:32:01.491  2082  2215 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
09-08 14:32:01.492  2082  2215 D BluetoothAdapterService(579935620): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
09-08 14:32:01.494  2082  2082 D A2dpService: Received stop request...Stopping profile...
09-08 14:32:01.494  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.494  2082  2215 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
09-08 14:32:01.494  2082  2215 D BluetoothAdapterService: getQuietmodeRadioCount = 0
09-08 14:32:01.494  2082  2215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.494   971   971 D BluetoothHeadset: Proxy object disconnected
,09-08 14:32:01.494  2082  2215 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
09-08 14:32:01.495  2082  2215 D BluetoothAdapterService(579935620): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
09-08 14:32:01.495  1758  1758 D BluetoothHeadset: Proxy object disconnected
09-08 14:32:01.496  2082  2215 D BluetoothAdapterState: Stopping profile services that were post enabled
09-08 14:32:01.496  6435  6435 I AppUp4:CustModeStarterReceiver: onReceive
09-08 14:32:01.496  6435  6435 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:01.496   971   971 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-08 14:32:01.497  2082  3332 D A2dpStateMachine: Exit Disconnected: -1
09-08 14:32:01.501  2082  2082 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-08 14:32:01.501  2082  2082 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 14:32:01.501  2082  2082 D LGBluetoothPowerControlManager: [BTUI] terminate
09-08 14:32:01.502  1758  1758 D BluetoothHeadset: Proxy object disconnected
09-08 14:32:01.503  1758  1758 D BluetoothHeadset: Proxy object disconnected
09-08 14:32:01.504   971  1055 D BluetoothManagerService: Message: 31
09-08 14:32:01.505  2082  2082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22911d84
09-08 14:32:01.506   971   971 D BluetoothA2dp: Proxy object disconnected
09-08 14:32:01.506   971   971 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-08 14:32:01.507  2082  2082 D HidService: Received stop request...Stopping profile...
09-08 14:32:01.507  2082  2082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22911d84
09-08 14:32:01.508  2082  2082 D HealthService: Received stop request...Stopping profile...
09-08 14:32:01.509  2082  2082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22911d84
09-08 14:32:01.510  2082  2082 D PanService: Received stop request...Stopping profile...
,09-08 14:32:01.513  2082  2082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22911d84
09-08 14:32:01.513  6435  6435 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bf9db31
09-08 14:32:01.513  6435  6435 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 14:32:01.515  2082  2082 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 14:32:01.515  2082  2082 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 14:32:01.515  2082  2082 D BtGatt.GattService: stop()
09-08 14:32:01.516  2082  2082 D BtGatt.AdvertiseManager: advertise clients cleared
09-08 14:32:01.517  2082  2082 D LGBluetoothGattAdapter: [BTUI] LGBluetoothGattAdapter cleanup
09-08 14:32:01.517  2082  2082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22911d84
09-08 14:32:01.518  2082  2082 D BluetoothMapService: Received stop request...Stopping profile...
09-08 14:32:01.520  2082  2082 D BluetoothMapService: stop()
09-08 14:32:01.520  2082  2082 D BluetoothMapEmailAppObserver: deinitObservers()
09-08 14:32:01.521  2082  2082 D BluetoothMapEmailAppObserver: removeReceiver()
09-08 14:32:01.521  2082  2082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22911d84
09-08 14:32:01.522  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - Message: 1
09-08 14:32:01.522  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-08 14:32:01.522  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-08 14:32:01.522  2082  2082 D BluetoothAdapterState: isTurningOnRadio()=false
09-08 14:32:01.522  2082  2082 D BluetoothAdapterState: isTurningOffRadio()=false
09-08 14:32:01.522  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-08 14:32:01.522  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-08 14:32:01.524  2082  2082 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
,09-08 14:32:01.524  2082  2082 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.524  2082  2082 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.524  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.525  2082  2082 D SapService: Received stop request...Stopping profile...
09-08 14:32:01.525  2082  2082 D SapService: Stopping Bluetooth SapService
09-08 14:32:01.525  2082  2082 D LGBluetoothSapAdapter: [BTUI] LGBluetoothSapAdapter cleanup
09-08 14:32:01.525  2082  2082 D LGBluetoothSapManager: [BTUI] terminateSapManager
09-08 14:32:01.526  6435  6435 D AppUp4:CustFacade: isSimDevice : true
09-08 14:32:01.528  2082  2082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22911d84
09-08 14:32:01.531  6435  6435 D AppUp4:CustModeStarterReceiver: begin check event
09-08 14:32:01.531  6435  6435 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-08 14:32:01.531  2082  2082 D HeadsetStateMachine: Unbinding service...
09-08 14:32:01.532  6435  6435 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-08 14:32:01.532  2082  2082 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 14:32:01.532  2082  2082 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 14:32:01.532  1758  1758 D LgeBluetoothSimManager: [BTUI] SAP_DISABLE_EVT
09-08 14:32:01.532  2082  2082 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-08 14:32:01.532  2082  2082 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-08 14:32:01.533  2082  2082 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 14:32:01.533  2082  2082 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 14:32:01.533  2082  2082 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-08 14:32:01.533  2082  2082 D **BluetoothFTPService: Received stop request...Stopping profile...
09-08 14:32:01.534  2082  2082 D **BluetoothFTPService: Stopping Bluetooth FTP Service
09-08 14:32:01.534  6435  6457 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-08 14:32:01.534  6435  6457 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-08 14:32:01.534  6435  6457 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-08 14:32:01.534  2082  2082 V BluetoothFTPServiceJni: closeFtpServerNative
09-08 14:32:01.534  2082  2082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22911d84
09-08 14:32:01.535  2082  2082 D **OppService: Received stop request...Stopping profile...
09-08 14:32:01.535  2082  2082 D OppService: Stopping Bluetooth OppService
09-08 14:32:01.536  2082  2082 D OppService: cleanup OPP Service
09-08 14:32:01.536  2082  2082 W BluetoothOPPServiceJni: Cleaning up Bluetooth Opp Interface...
09-08 14:32:01.536  2082  2082 W BluetoothOPPServiceJni: Cleaning up Bluetooth OPP callback object
,09-08 14:32:01.537  2082  2082 D OppService: remove callbacks and handler
09-08 14:32:01.537  2082  2082 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-08 14:32:01.537  2082  2082 D OppService: cleanup done
09-08 14:32:01.537  2082  2082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22911d84
09-08 14:32:01.538  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - Message: 1
09-08 14:32:01.538  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-08 14:32:01.538  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-08 14:32:01.538  2082  2082 D BluetoothAdapterState: isTurningOnRadio()=false
09-08 14:32:01.538  2082  2082 D BluetoothAdapterState: isTurningOffRadio()=false
09-08 14:32:01.538  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-08 14:32:01.538  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-08 14:32:01.538  2082  2082 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-08 14:32:01.538  2082  2082 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.538  2082  2082 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.538  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.539  2082  2082 I BluetoothA2dpServiceJni: cleanupNative
09-08 14:32:01.539  2082  2082 I GKI_LINUX: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
09-08 14:32:01.539  2082  3459 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-08 14:32:01.540  2082  2082 I GKI_LINUX: GKI_destroy_task(): task [A2DP-MEDIA] terminated
09-08 14:32:01.545  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - Message: 1
09-08 14:32:01.545  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-08 14:32:01.545  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-08 14:32:01.545  2082  2082 D BluetoothAdapterState: isTurningOnRadio()=false
09-08 14:32:01.545  2082  2082 D BluetoothAdapterState: isTurningOffRadio()=false
09-08 14:32:01.545  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-08 14:32:01.545  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-08 14:32:01.545  2082  2082 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-08 14:32:01.545  2082  2082 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.545  2082  2082 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.545  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,09-08 14:32:01.549  2082  2082 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 14:32:01.549  2082  2082 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 14:32:01.549  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - Message: 1
09-08 14:32:01.549  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-08 14:32:01.549  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-08 14:32:01.549  2082  2082 D BluetoothAdapterState: isTurningOnRadio()=false
09-08 14:32:01.549  2082  2082 D BluetoothAdapterState: isTurningOffRadio()=false
09-08 14:32:01.549  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-08 14:32:01.549  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-08 14:32:01.549  2082  2082 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-08 14:32:01.549  2082  2082 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.550  2082  2082 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.550  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.550  2082  2082 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 14:32:01.550  2082  2082 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 14:32:01.550  2082  2082 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 14:32:01.550  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - Message: 1
09-08 14:32:01.550  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-08 14:32:01.551  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-08 14:32:01.551  2082  2082 D BluetoothAdapterState: isTurningOnRadio()=false
09-08 14:32:01.551  2082  2082 D BluetoothAdapterState: isTurningOffRadio()=false
09-08 14:32:01.551  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-08 14:32:01.551  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-08 14:32:01.551  2082  2082 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-08 14:32:01.551  2082  2082 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.551  2082  2082 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.551  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.552  2082  2082 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 14:32:01.552  2082  2082 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-08 14:32:01.553  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - Message: 1
09-08 14:32:01.553  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-08 14:32:01.553  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
09-08 14:32:01.553  2082  2082 D BluetoothAdapterState: isTurningOnRadio()=false
09-08 14:32:01.553  2082  2082 D BluetoothAdapterState: isTurningOffRadio()=false
09-08 14:32:01.553  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-08 14:32:01.553  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-08 14:32:01.553  2082  2082 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-08 14:32:01.553  2082  2082 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.553  2082  2082 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.553  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,09-08 14:32:01.553  2082  2082 V BluetoothMapService: Handler(): got msg=4
09-08 14:32:01.553  2082  2082 D BluetoothMapService: MAP Service closeService in
09-08 14:32:01.553  2082  2082 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 14:32:01.553  2082  2082 V BluetoothMapService: MAP Service closeService out
09-08 14:32:01.553  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - Message: 1
09-08 14:32:01.553  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-08 14:32:01.553  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-08 14:32:01.553  2082  2082 D BluetoothAdapterState: isTurningOnRadio()=false
09-08 14:32:01.553  2082  2082 D BluetoothAdapterState: isTurningOffRadio()=false
09-08 14:32:01.553  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-08 14:32:01.553  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-08 14:32:01.554  2082  2082 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-08 14:32:01.554  2082  2082 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.554  2082  2082 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.554  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.554  2082  2082 D BluetoothMapService: cleanup()
09-08 14:32:01.554  2082  2082 D BluetoothMapService: MAP Service closeService in
09-08 14:32:01.554  2082  2082 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-08 14:32:01.554  2082  2082 V BluetoothMapService: MAP Service closeService out
09-08 14:32:01.555  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - Message: 1
09-08 14:32:01.555  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-08 14:32:01.555  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-08 14:32:01.555  2082  2082 D BluetoothAdapterState: isTurningOnRadio()=false
09-08 14:32:01.555  2082  2082 D BluetoothAdapterState: isTurningOffRadio()=false
09-08 14:32:01.555  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-08 14:32:01.555  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-08 14:32:01.555  2082  2082 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-08 14:32:01.555  2082  2082 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.555  2082  2082 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.555  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.555  2082  2082 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
09-08 14:32:01.555  2082  2082 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
09-08 14:32:01.557  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - Message: 1
09-08 14:32:01.557  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-08 14:32:01.557  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
0,9-08 14:32:01.557  2082  2082 D BluetoothAdapterState: isTurningOnRadio()=false
09-08 14:32:01.557  2082  2082 D BluetoothAdapterState: isTurningOffRadio()=false
09-08 14:32:01.557  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-08 14:32:01.557  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-08 14:32:01.557  2082  2082 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-08 14:32:01.557  2082  2082 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.557  2082  2082 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.557  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
09-08 14:32:01.557  2082  2082 D BluetoothFTPService: cleanup FTP Service
09-08 14:32:01.557  2082  2082 V BluetoothFTPServiceJni: closeFtpServerNative
09-08 14:32:01.557  2082  2082 V BluetoothFTPServiceJni: cleanupNative
09-08 14:32:01.557  2082  2082 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP Server Interface...
09-08 14:32:01.557  2082  2082 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP callback object
09-08 14:32:01.558  2082  2082 D BluetoothFTPService: BluetoothFtpBinder.cleanup()
09-08 14:32:01.558  2082  2082 D BluetoothFTPService: cleanup done
09-08 14:32:01.558  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - Message: 1
09-08 14:32:01.558  2082  2082 D BluetoothAdapterService(579935620): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
09-08 14:32:01.558  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
09-08 14:32:01.558  2082  2082 D BluetoothAdapterState: isTurningOnRadio()=false
09-08 14:32:01.558  2082  2082 D BluetoothAdapterState: isTurningOffRadio()=false
09-08 14:32:01.558  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
09-08 14:32:01.559  2082  2082 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
09-08 14:32:01.559  2082  2082 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
09-08 14:32:01.559  2082  2082 D BluetoothAdapterService(579935620): onProfileServiceStateChange() - All profile services stopped...
09-08 14:32:01.560  2082  2215 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-08 14:32:01.560  2082  2215 D BluetoothAdapterProperties: Setting state to 10
09-08 14:32:01.560  2082  2215 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-08 14:32:01.560  2082  2215 D BluetoothAdapterService(579935620): updateAdapterState() - Broadcasting state to 1 receivers.
09-08 14:32:01.560  2082  2082 D OppService: cleanup OPP Service
09-08 14:32:01.560  2082  2082 D OppService: remove callbacks and handler
09-08 14:32:01.560  2082  2082 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-08 14:32:01.560  2082  2082 D OppService: cleanup done
09-08 14:32:01.561   971  1055 D BluetoothManagerService: Message: 60
09-08 14:32:01.561   971  1055 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-08 14:32:01.561   971  1055 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 5 receivers.
09-08 14:32:01.562  2082  2215 I BluetoothAdapterState: Entering OffState
09-08 14:32:01.563   971  1055 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 14:32:01.565  5434  6304 I GAv4-SVC: Google Analytics 9.4.52 is starting up.
09-08 14:32:01.567  1758  1787 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 14:32:01.572  1737  2342 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
09-08 14:32:01.573  1758  2335 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:32:01.574   971  1055 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:32:01.574  1758  1788 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:32:01.574   971  1055 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-08 14:32:01.578  1861  1861 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:01.578  1861  2063 D LGBluetoothAPIService: Message: 2
09-08 14:32:01.581  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:01.582  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:32:01.585  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:01.586  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:01.586  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:01.587  2082  2100 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:01.589  1861  2063 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@17b1e03 mBinding = false
09-08 14:32:01.591  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
09-08 14:32:01.591  1373  1373 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
09-08 14:32:01.593  1861  2063 D LGBluetoothAPIService: Sending unbind request.
09-08 14:32:01.619  3073  3073 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-08 14:32:01.622  3073  3073 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:01.624  3073  3073 I LgeMiscReceiver: networkInfo.isConnected() = true
09-08 14:32:01.631  3073  3073 D PhoneState: setPdpRejectCasuse : false
09-08 14:32:01.641  1737  2342 W ctxmgr  : [WorkManager]Long workInfo: label=RegisterContextListener, startTime=2016-09-08 14:32:00.617+0200, stopTime=2016-09-08 14:32:01.639+0200, duration=1022ms
,09-08 14:32:01.659   971  1640 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6468 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
09-08 14:32:01.672   314   314 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 21.313ms
,09-08 14:32:01.693   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.705ms
,09-08 14:32:01.714   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.382ms
,09-08 14:32:01.739   971  2043 I ActivityManager: Process com.lge.clock (pid 6291) has died
,09-08 14:32:01.741  2082  2082 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-08 14:32:01.741  2082  2082 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-08 14:32:01.742  2082  2082 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-08 14:32:01.743   971  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1fb2982 type 2 when 148842 com.google.android.gms} when 148842
09-08 14:32:01.800   971  1640 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6485 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,09-08 14:32:01.873  6489  6489 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-08 14:32:01.899   971  1932 I ActivityManager: Process com.android.gallery3d (pid 6245) has died
,09-08 14:32:01.992  6489  6489 I dex2oat : dex2oat took 116.456ms (threads: 4)
,09-08 14:32:02.001  6468  6468 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
09-08 14:32:02.007  6468  6468 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
09-08 14:32:02.012  6318  6336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:02.012  6318  6336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:02.012  6318  6336 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:02.012  6318  6336 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:02.012  6318  6336 I Adreno-EGL: Remote Branch: 
09-08 14:32:02.012  6318  6336 I Adreno-EGL: Local Patches: 
09-08 14:32:02.012  6318  6336 I Adreno-EGL: Reconstruct Branch: 
,09-08 14:32:02.025   243   243 E lowmemorykiller: Error writing /proc/6200/oom_score_adj; errno=22
09-08 14:32:02.026  1373  1373 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
09-08 14:32:02.026  1373  1373 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
,09-08 14:32:02.029  1334  1334 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
09-08 14:32:02.030  1373  1373 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
09-08 14:32:02.043  6468  6468 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
09-08 14:32:02.045  6468  6468 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
,09-08 14:32:02.121  6485  6485 D PhoneMonitor: Register our PhoneStateListener
,09-08 14:32:02.129   971  2043 I ActivityManager: Process com.google.android.music:main (pid 6200) has died
09-08 14:32:02.132  6468  6468 V [BNRBootReceiver]: Boot Receiver Return
09-08 14:32:02.132  6468  6468 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-08 14:32:02.138  2820  2820 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:32:2
,09-08 14:32:02.140  2820  2820 D WeatherService: 2 : TimeTick Intent And Screen On
09-08 14:32:02.140  2820  2820 D WeatherService: 2 : SDK version : 21
09-08 14:32:02.141   971  1951 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
09-08 14:32:02.141  2820  2820 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
09-08 14:32:02.142  2820  2820 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
09-08 14:32:02.142  2820  2820 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
09-08 14:32:02.142  2820  2820 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
09-08 14:32:02.143  2820  2820 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:32:02.143  2820  2820 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
09-08 14:32:02.143  2820  2820 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
09-08 14:32:02.144  2820  2820 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
09-08 14:32:02.144  2820  2820 D WeatherTheme: 2 : Fixed theme : optimus
09-08 14:32:02.146  2820  2820 D WeatherReflect: 2 : Map key string is -2
09-08 14:32:02.148  2820  2820 D lim     : 2 : time = 14:32
09-08 14:32:02.148  2820  2820 I WeatherReflect: Model Name : LG-D722
,09-08 14:32:02.149  2820  2820 D WeatherTheme: 2 : Different view - status_min_formatted : 31 != 32
09-08 14:32:02.149  2820  2820 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
09-08 14:32:02.150  2820  2820 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,09-08 14:32:02.153  2820  2820 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-08 14:32:02.153  2820  2820 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-08 14:32:02.153  2820  2820 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-08 14:32:02.153  2820  2820 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
09-08 14:32:02.156  6318  6336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:02.156  6318  6336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:02.156  6318  6336 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:02.156  6318  6336 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:02.156  6318  6336 I Adreno-EGL: Remote Branch: 
09-08 14:32:02.156  6318  6336 I Adreno-EGL: Local Patches: 
09-08 14:32:02.156  6318  6336 I Adreno-EGL: Reconstruct Branch: 
09-08 14:32:02.183  2820  2820 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
09-08 14:32:02.183  2820  2820 D Weather4x2_optimus: widgetType = 1, orientation = 1
09-08 14:32:02.183  2820  2820 D Weather4x2_optimus: forecast size is 0
09-08 14:32:02.184  2820  2820 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-08 14:32:02.184  2820  2820 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-08 14:32:02.184  2820  2820 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-08 14:32:02.184  2820  2820 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-08 14:32:02.184  2820  2820 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-08 14:32:02.184  2820  2820 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-08 14:32:02.184  2820  2820 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-08 14:32:02.184  2820  2820 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-08 14:32:02.184  2820  2820 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-08 14:32:02.184  2820  2820 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
09-08 14:32:02.184  2820  2820 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
,09-08 14:32:02.184  2820  2820 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-08 14:32:02.184  2820  2820 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-08 14:32:02.184  2820  2820 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-08 14:32:02.184  2820  2820 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
09-08 14:32:02.187  2820  2820 D Theme_WeatherAncestor_optimus: url is : null
09-08 14:32:02.189  2820  2820 D Theme   : strTheme: com.lge.launcher2.theme.optimus
09-08 14:32:02.189  2820  2820 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
09-08 14:32:02.190  2820  2820 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
09-08 14:32:02.190  2820  2820 D WeatherAncestor: 2 : update view, appWidgetId: 2
09-08 14:32:02.192  2820  2820 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:32:2
09-08 14:32:02.228  6485  6485 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-08 14:32:02.231  6485  6485 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 14:32:02.242   971  1383 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6519 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-08 14:32:02.335  2616  2616 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:02.380  6519  6519 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:02.380  6519  6519 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-08 14:32:02.380  6519  6519 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 14:32:02.381  6519  6519 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 14:32:02.381  6519  6519 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 14:32:02.385  2616  2616 V DownloadManager: DownloadService onCreate
09-08 14:32:02.391  2616  6536 I DownloadManager: in removeSpuriousFiles
09-08 14:32:02.393  2616  2616 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
09-08 14:32:02.396  2616  6536 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-08 14:32:02.401  2616  6536 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1f51ade4 on behalf of 2616
,09-08 14:32:02.408   971   990 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6540 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-08 14:32:02.410  6485  6485 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-08 14:32:02.411  2616  6536 I DownloadManager: in trimDatabase
09-08 14:32:02.411  2616  6536 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-08 14:32:02.416  6485  6485 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-08 14:32:02.418  1953  1953 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
09-08 14:32:02.420  6485  6485 D TelephonyAutoProfiling: [parse] Load xml
09-08 14:32:02.426  6485  6485 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-08 14:32:02.426  6485  6485 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,09-08 14:32:02.469  2616  2616 V DownloadManager: DownloadService onStartCommand
09-08 14:32:02.469  2616  6536 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2fcb8a13 on behalf of 2616
,09-08 14:32:02.477  2616  6537 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-08 14:32:02.498  6519  6519 I IndexDatabaseHelper: Using schema version: 115
,09-08 14:32:02.502  6519  6519 I IndexDatabaseHelper: Index is fine
09-08 14:32:02.503  2616  6537 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3b6dc450 on behalf of 2616
09-08 14:32:02.508  6485  6485 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-08 14:32:02.556  6318  6336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:02.556  6318  6336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:02.556  6318  6336 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:02.556  6318  6336 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:02.556  6318  6336 I Adreno-EGL: Remote Branch: 
09-08 14:32:02.556  6318  6336 I Adreno-EGL: Local Patches: 
09-08 14:32:02.556  6318  6336 I Adreno-EGL: Reconstruct Branch: 
09-08 14:32:02.565  1953  1953 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,09-08 14:32:02.616  6540  6540 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
09-08 14:32:02.617  6540  6540 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,09-08 14:32:02.700   971  1640 I art     : Explicit concurrent mark sweep GC freed 21925(1053KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.172ms total 160.148ms
,09-08 14:32:02.706  6540  6540 V DrmService: Service onCreate
,09-08 14:32:02.706  6540  6540 D DrmService: Received new request = 2
09-08 14:32:02.712  2820  2820 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:2
09-08 14:32:02.714  2820  2820 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-08 14:32:02.718  2820  2820 D WeatherAncestor: connectivity changed - connection : true
09-08 14:32:02.719  2820  2820 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 14:32:02.719  2820  2820 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:2
09-08 14:32:02.719  2820  2820 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:02.723   971  1640 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
09-08 14:32:02.723  2820  2820 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
09-08 14:32:02.724  2820  2820 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,09-08 14:32:02.724  2820  2820 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
09-08 14:32:02.731  2616  2616 V DownloadManager: DownloadService onDestroy
,09-08 14:32:02.742  1737  6557 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:02.742  1737  6557 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:02.744  1737  6557 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:02.744  1737  6557 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:02.745   274  1039 E BandwidthController: [LG DATA] No such appUid: 10006
09-08 14:32:02.745   274  1039 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-08 14:32:02.749   274  6558 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-08 14:32:02.749   274  6558 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:02.749   274  6558 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-08 14:32:02.749   274  6558 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,09-08 14:32:02.772  5453  6513 I art     : Explicit concurrent mark sweep GC freed 2464(97KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.457ms total 30.961ms
,09-08 14:32:02.790  6540  6559 I DrmSntpClient: Start Sync process
,09-08 14:32:02.792  6540  6559 D DrmSntpClient: Server : 0
09-08 14:32:02.797  6540  6559 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:02.797  6540  6559 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:02.797  6540  6559 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:02.797  6540  6559 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:02.797   274  1039 E BandwidthController: [LG DATA] No such appUid: 10051
09-08 14:32:02.797   274  1039 D DnsProxyListener: App 10051 tries DNS query. Accept family:0 protocol:0
09-08 14:32:02.798   274  6561 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-08 14:32:02.798   274  6561 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:02.798   274  6561 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-08 14:32:02.798   274  6561 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:02.802   274  6558 D libc-netbsd: res_queryN name = xxxxx succeed
,09-08 14:32:02.803  1737  6557 I System.out: propertyValue:false
09-08 14:32:02.839   971  6413 I ActivityManager: Process com.lge.email (pid 6216) has died
,09-08 14:32:02.839  6519  6519 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-08 14:32:02.845   274  6561 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:02.847  2082  2082 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 14:32:02.847  2082  2082 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:02.847  2082  2082 V BluetoothPbapReceiver: ***********state = 13
09-08 14:32:02.848  2082  2082 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-08 14:32:02.849  2082  2082 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:02.850  2082  2082 V BluetoothPbapService: state: 13
09-08 14:32:02.850  2082  2082 V BluetoothPbapService: Pbap Service closeService in
09-08 14:32:02.851  2082  2082 V BluetoothPbapService: successfully stopped pbap service
09-08 14:32:02.851  2082  2082 V BluetoothPbapService: Pbap Service closeService out
09-08 14:32:02.851  2082  2082 V BluetoothPbapService: Pbap Service onDestroy
09-08 14:32:02.851  2082  2082 V BluetoothPbapService: Pbap Service closeService in
,09-08 14:32:02.851  2082  2082 V BluetoothPbapService: Pbap Service closeService out
09-08 14:32:02.851  2082  2082 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-08 14:32:02.853  6540  6559 I System.out: propertyValue:false
09-08 14:32:02.860   971  1055 D BluetoothManagerService: Message: 20
09-08 14:32:02.860   971  1055 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19aaac83:true
09-08 14:32:02.874  2082  6370 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:02.878   971  1055 D BluetoothManagerService: Message: 30
,09-08 14:32:02.883   971  1055 D BluetoothManagerService: Message: 30
09-08 14:32:02.886  6519  6519 D LocalBluetoothProfileManager: Adding local MAP profile
09-08 14:32:02.888  6519  6519 D BluetoothMap: Create BluetoothMap proxy object
09-08 14:32:02.889   971  1055 D BluetoothManagerService: Message: 30
09-08 14:32:02.894   971  1055 D BluetoothManagerService: Message: 30
09-08 14:32:02.896  6519  6519 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-08 14:32:02.897  6540  6559 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
09-08 14:32:02.898  6519  6519 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-08 14:32:02.900   285   285 V ILGDrmService: eDRM_SetDRMTime +++
09-08 14:32:02.904  1737  6557 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:02.904  1737  6557 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:02.908   285   285 I LGDRM   : [DRM] SET TIME : YR=2016, MON=9, DAY=8
09-08 14:32:02.908   285   285 I LGDRM   : [DRM] SET TIME : HR=12, MIN=32, SEC=1
09-08 14:32:02.930  6519  6519 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-08 14:32:02.936   285   285 V ILGDrmService: eDRM_SetDRMTime ---
09-08 14:32:02.936  6540  6559 I DrmSntpClient: Synched
09-08 14:32:02.937  6519  6519 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,09-08 14:32:02.938  6540  6540 D DrmService: Completed !! request = 2
09-08 14:32:02.938  6540  6540 D DrmService: Request count = 0
09-08 14:32:02.940  6540  6540 V DrmService: Service onDestroy
09-08 14:32:02.951  6519  6519 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:32:02.965  6519  6519 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-08 14:32:02.969  6519  6519 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-08 14:32:02.970  6519  6519 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
09-08 14:32:02.970  6519  6519 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
09-08 14:32:02.971  6519  6519 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
09-08 14:32:02.971  6519  6519 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
09-08 14:32:02.971  6519  6519 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
09-08 14:32:02.972  6519  6519 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
09-08 14:32:02.975  6519  6519 D BluetoothPermissionRequest: onReceive
09-08 14:32:02.976  6519  6519 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-08 14:32:02.977  6519  6519 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
,09-08 14:32:02.977  6519  6519 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
09-08 14:32:02.977  6519  6519 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
09-08 14:32:02.978  6519  6519 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
09-08 14:32:02.978  6519  6519 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
09-08 14:32:02.979  6519  6519 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
09-08 14:32:02.991  2082  2082 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-08 14:32:02.991  2082  2082 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-08 14:32:02.991  2082  2082 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
09-08 14:32:02.991  2082  2082 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-08 14:32:02.992  2082  2082 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
,09-08 14:32:02.999  2082  2082 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 14:32:03.002  2082  2082 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:03.013  1737  6557 I GCM     : GCM config loaded
,09-08 14:32:03.018  5434  5434 I art     : Explicit concurrent mark sweep GC freed 27052(1963KB) AllocSpace objects, 30(480KB) LOS objects, 24% free, 14MB/19MB, paused 1.147ms total 171.775ms
,09-08 14:32:03.078   971  1869 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6571 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-08 14:32:03.139   971  1324 I ActivityManager: Process com.android.calendar (pid 6340) has died
,09-08 14:32:03.177  1737  6313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:03.177  1737  6313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:03.179  1737  6313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:03.179  1737  6313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:03.179   274  1039 E BandwidthController: [LG DATA] No such appUid: 10006
09-08 14:32:03.179   274  1039 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-08 14:32:03.180   274  6590 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-08 14:32:03.180   274  6590 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:03.180   274  6590 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
,09-08 14:32:03.180   274  6590 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:03.189  6571  6571 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 14:32:03.214  5434  6592 I CheckinService: Disabling old GoogleServicesFramework version
,09-08 14:32:03.221  1737  1737 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-08 14:32:03.227  1737  1737 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 14:32:03.228   274  6590 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:03.231  1737  6313 I System.out: propertyValue:false
09-08 14:32:03.233  6519  6519 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-08 14:32:03.237  2082  2082 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-08 14:32:03.237  2082  2082 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:03.237  2082  2082 V BluetoothPbapReceiver: ***********state = 10
09-08 14:32:03.239  6519  6519 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:32:03.244  6519  6519 D BluetoothPermissionRequest: onReceive
09-08 14:32:03.247  6519  6519 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-08 14:32:03.248  6519  6519 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-08 14:32:03.248  6519  6519 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-08 14:32:03.256  2082  2082 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-08 14:32:03.258  2082  2082 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:32:03.265  6571  6571 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
09-08 14:32:03.271  1737  1737 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-08 14:32:03.277  1737  6597 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-08 14:32:03.278  1737  1737 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-08 14:32:03.286  5434  6598 I iu.SyncManager: SYNC; picasa accounts
,09-08 14:32:03.290  1737  6313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:03.290  1737  6313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:03.327  5434  5434 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-08 14:32:03.330  5434  5434 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-08 14:32:03.331  5434  6593 I CheckinChimeraService: Checking schedule, now: 1473337923330 next: 1473337323146
09-08 14:32:03.337  5434  6593 I CheckinChimeraService: active receiver: enabled
09-08 14:32:03.339  5434  6593 I CheckinChimeraService: Preparing to send checkin request
,09-08 14:32:03.340  5434  6593 I EventLogChimeraService: Accumulating logs since 1473337405381
09-08 14:32:03.347  5434  6598 I iu.UploadsManager: num queued entries: 0
09-08 14:32:03.348  5434  6598 I iu.UploadsManager: num updated entries: 0
09-08 14:32:03.355  5434  6598 I iu.SyncManager: NEXT; no task
,09-08 14:32:03.401   279   279 I WVCdm   : CdmEngine::CloseSession
,09-08 14:32:03.406   279   279 I WVCdm   : L3 Terminate.
09-08 14:32:03.431   971  2043 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6602 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-08 14:32:03.515  5434  5508 D edo     : Opening database auth.proximity.permit_store...
,09-08 14:32:03.518  1737  6597 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-08 14:32:03.551  1737  2342 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
09-08 14:32:03.555  1737  2342 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-08 14:32:03.563  1737  2342 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-08 14:32:01.949+0200, stopTime=2016-09-08 14:32:03.562+0200, duration=1613ms
09-08 14:32:03.583  1737  6620 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:03.583  1737  6620 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:03.583  1737  6620 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:03.583  1737  6620 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:03.583   274  1039 E BandwidthController: [LG DATA] No such appUid: 10006
09-08 14:32:03.583   274  1039 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-08 14:32:03.584   274  6624 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-08 14:32:03.584   274  6624 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:03.584   274  6624 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-08 14:32:03.584   274  6624 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:03.584   274  6624 D libc-netbsd: res_queryN name = xxxxx succeed
,09-08 14:32:03.588  1737  6620 I System.out: propertyValue:false
,09-08 14:32:03.642  6602  6602 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-08 14:32:03.729  5434  6593 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,09-08 14:32:03.737  5434  6593 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-08 14:32:03.964   279  1610 I WVCdm   : CdmEngine::OpenSession
09-08 14:32:03.964   279  1610 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,09-08 14:32:03.995   279  1610 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-08 14:32:03.996   279  1610 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
09-08 14:32:03.996   279  1610 W WVCdm   : L1 library not specified. Falling Back to L3
09-08 14:32:04.059  1737  2342 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-08 14:32:04.070  6602  6640 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-08 14:32:04.070  6602  6640 I Babel_SMS: MmsConfig.loadMmsSettings
09-08 14:32:04.079  6602  6640 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-08 14:32:04.079  6602  6640 I Babel_SMS: MmsConfig.loadFromDatabase
,09-08 14:32:04.096   279  1610 I WVCdm   : CdmEngine::QueryKeyControlInfo
09-08 14:32:04.097   279  1325 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-08 14:32:04.097   279  1325 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,09-08 14:32:04.097   279  1325 I WVCdm   : CdmEngine::GenerateKeyRequest
09-08 14:32:04.104  6602  6640 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-08 14:32:04.104  6602  6640 I Babel_SMS: MmsConfig.loadFromResources
09-08 14:32:04.106  6602  6640 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-08 14:32:04.107  6602  6640 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-08 14:32:04.111   279  1325 D WVCdm   : PrepareKeyRequest: nonce=841908402
09-08 14:32:04.139   279  1608 I WVCdm   : CdmEngine::OpenSession
,09-08 14:32:04.187  6602  6602 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-08 14:32:04.187  6602  6602 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-08 14:32:04.187  6602  6602 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-08 14:32:04.187  6602  6602 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-08 14:32:04.187  6602  6602 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-08 14:32:04.187  6602  6602 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-08 14:32:04.187  6602  6602 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-08 14:32:04.187  6602  6602 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-08 14:32:04.187  6602  6602 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-08 14:32:04.187  6602  6602 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-08 14:32:04.188  6602  6602 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-08 14:32:04.188  6602  6602 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-08 14:32:04.188  6602  6602 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-08 14:32:04.188  6602  6602 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-08 14:32:04.188  6602  6602 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-08 14:32:04.188  6602  6602 D SensorManager: found sensor: Motion Accel, handle=46
,09-08 14:32:04.217  6602  6616 W art     : Suspending all threads took: 5.703ms
,09-08 14:32:04.240  6602  6616 I art     : CheckpointMarkThreadRoots callback created = 0xb042d4d0
,09-08 14:32:04.262  6602  6602 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:32:04.264  6602  6602 I Babel_Crash: startup - clean
09-08 14:32:04.281  6602  6653 I Babel   : deleted: false for 0
,09-08 14:32:04.295  1737  6652 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-08 14:32:04.295  1737  6643 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
09-08 14:32:04.300  6602  6616 I art     : CheckpointMarkThreadRoots callback created = 0xb042d4c0
09-08 14:32:04.339  1737  6652 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-08 14:32:04.341  1737  6643 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
09-08 14:32:04.375  6602  6602 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,09-08 14:32:04.381  6602  6602 W AudioCapabilities: Unsupported mime audio/adpcm
09-08 14:32:04.389  6602  6602 W AudioCapabilities: Unsupported mime audio/g726
09-08 14:32:04.391  6602  6602 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-08 14:32:04.393  6602  6602 W AudioCapabilities: Unsupported mime audio/wma-voice
,09-08 14:32:04.394  6602  6602 W VideoCapabilities: Unsupported mime video/mjpg
,09-08 14:32:04.397   971  1951 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6655 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:32:04.469  1737  6652 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-08 14:32:04.471  1737  6643 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
09-08 14:32:04.472  1737  6643 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
09-08 14:32:04.474  6602  6602 W VideoCapabilities: Unsupported mime video/theora
,09-08 14:32:04.507  1737  6643 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
09-08 14:32:04.568  6602  6602 W AudioCapabilities: Unsupported mime audio/evrc
,09-08 14:32:04.583  6602  6602 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 14:32:04.599  6602  6602 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:32:04.619   971  1951 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 14:32:04.637  6602  6602 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-08 14:32:04.641  6602  6602 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 14:32:04.643  6602  6602 W AudioCapabilities: Unsupported mime audio/evrc
09-08 14:32:04.663  6602  6602 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-08 14:32:04.701  6602  6602 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 14:32:04.720  6602  6602 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:32:04.722  6602  6602 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:04.725  6602  6602 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:04.731  6602  6602 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:32:04.739  6602  6602 I vclib   : onServiceConnected
09-08 14:32:04.739  6602  6602 W Babel   : Attempted to change video mute state without an active call.
09-08 14:32:04.754  6602  6602 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,09-08 14:32:04.756  6602  6674 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:04.757  6602  6674 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:04.759  6602  6674 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:04.759  6602  6674 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:04.759   274  1039 E BandwidthController: [LG DATA] No such appUid: 10061
09-08 14:32:04.759   274  1039 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
09-08 14:32:04.759   274  6676 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-08 14:32:04.759   274  6676 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:04.760   274  6676 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
,09-08 14:32:04.761   274  6676 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:04.761   274  6676 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:04.762  6602  6674 I System.out: propertyValue:false
09-08 14:32:04.769  1737  6643 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:04.769  1737  6643 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:04.769  1737  6643 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:04.770  1737  6643 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:04.770   274  1039 E BandwidthController: [LG DATA] No such appUid: 10006
09-08 14:32:04.770   274  1039 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-08 14:32:04.770   274  6677 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-08 14:32:04.770   274  6677 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:04.770   274  6677 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-08 14:32:04.771   274  6677 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,09-08 14:32:04.802   274  6677 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:04.804  1737  6643 I System.out: propertyValue:false
,09-08 14:32:04.811   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:04.811   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 14:32:04.811   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:04.812  6655  6681 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 14:32:04.815   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:04.815   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 14:32:04.815   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:04.816  6655  6681 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 14:32:04.816  6602  6674 I Babel   : connection state changed from UNKNOWN to CONNECTED
,09-08 14:32:04.822   971  1959 I ActivityManager: Killing 5910:com.lge.sync/1000 (adj 15): empty #11
,09-08 14:32:04.831   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:04.831   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 14:32:04.831   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:04.836  6655  6682 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-08 14:32:04.839   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:04.839   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 14:32:04.839   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:04.840  6655  6682 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 14:32:04.842  6655  6655 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 14:32:04.842  6655  6655 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 14:32:04.842  6655  6655 I GAv4    :   adb logcat -s GAv4
09-08 14:32:04.949   971  1324 W libprocessgroup: failed to open /acct/uid_1000/pid_5910/cgroup.procs: No such file or directory
,09-08 14:32:04.954  6655  6655 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-08 14:32:04.982  6655  6655 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:32:04.987  6655  6684 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-08 14:32:05.078   971  1919 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 14:32:05.181   971  1003 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-08 14:32:05.181   971  1003 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-08 14:32:05.181   971  1003 D sensors_hal_Time: tsOffsetIs: Apps: 152292113389; DSPS: 5081891; Offset : -2806641937
,09-08 14:32:05.271  6655  6655 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,09-08 14:32:05.310   971  1959 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 14:32:05.332  6655  6655 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2442-2443)
09-08 14:32:05.333  6655  6655 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 14:32:05.340  6655  6655 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {386ef20a}
09-08 14:32:05.341  6655  6655 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:32:05.341  6655  6655 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 14:32:05.356  6655  6655 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 14:32:05.357  6655  6655 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 14:32:05.359  6655  6655 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 14:32:05.378  6655  6655 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 14:32:05.383  6655  6655 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 14:32:05.383  6655  6655 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 14:32:05.384  6655  6655 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:05.384  6655  6655 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:05.384  6655  6655 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:05.384  6655  6655 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:05.384  6655  6655 I Adreno-EGL: Remote Branch: 
09-08 14:32:05.384  6655  6655 I Adreno-EGL: Local Patches: 
09-08 14:32:05.384  6655  6655 I Adreno-EGL: Reconstruct Branch: 
09-08 14:32:05.447   279  1295 V AudioPolicyService: registerClient() client 0xb57f30e0, uid 10079
,09-08 14:32:05.451  6655  6717 W AudioManagerAndroid: Requires BLUETOOTH permission
09-08 14:32:05.459  6655  6655 I NSApplication: Starting up...
09-08 14:32:05.526   971   990 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6722 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:05.529   971   990 I ActivityManager: Killing 6407:com.qualcomm.timeservice/1000 (adj 15): empty #11
09-08 14:32:05.531   971  1058 I PowerManagerService: ALS enabled for SRE
09-08 14:32:05.531   971  1058 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32642 ms ago)
09-08 14:32:05.533   971  1058 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-08 14:32:05.551   971  1058 I PowerManagerService: ALS enabled for SRE
09-08 14:32:05.552   971  1058 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (32663 ms ago)
09-08 14:32:05.561   971  1058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,09-08 14:32:05.590   971  1932 W libprocessgroup: failed to open /acct/uid_1000/pid_6407/cgroup.procs: No such file or directory
,09-08 14:32:05.594   971  1058 I PowerManagerService: Sleeping (uid 1000)...
09-08 14:32:05.595   971  1058 D LPWGController: [updateScreenState] screen on = false
,09-08 14:32:05.601   971  1058 D LPWGController: disable proximity sensor
09-08 14:32:05.601   971  1058 D LPWGController: enable proximity sensor
09-08 14:32:05.610   971  1058 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2a1f8552] by com.android.server.power.ProximitySensorListener.enable():120
,09-08 14:32:05.617   971  1058 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
09-08 14:32:05.617   971  1058 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
09-08 14:32:05.617   971  1058 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
09-08 14:32:05.617   971  1058 I sensors_hal_Ctx: activate: handle is 48, enable
09-08 14:32:05.618   971  1058 V sensors_hal_Ctx: activate sensors is 1400000000000
09-08 14:32:05.618   971  1058 D sensors_hal_Thresh: enable: handle=48
09-08 14:32:05.618   971  1058 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
09-08 14:32:05.618   971  1058 D sensors_hal_Util: waitForResponse: timeout=1000
09-08 14:32:05.623   971  1004 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
09-08 14:32:05.623   971  1004 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
09-08 14:32:05.623   971  1058 D sensors_hal_Thresh: enable: Received response: 0
,09-08 14:32:05.627   971  1058 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (32738 ms ago)
09-08 14:32:05.633   971  6413 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 14:32:05.659   971  1058 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:05.659   971  1058 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:05.659   971  1058 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:05.659   971  1058 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:05.659   971  1058 I Adreno-EGL: Remote Branch: 
09-08 14:32:05.659   971  1058 I Adreno-EGL: Local Patches: 
09-08 14:32:05.659   971  1058 I Adreno-EGL: Reconstruct Branch: 
,09-08 14:32:05.694   246  1297 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1118 us)
,09-08 14:32:05.735  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:05.815  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:05.815  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:05.815  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:05.816  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:05.816  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@113f586f removed from the list
09-08 14:32:05.816  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:05.816  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c4a97c removed from the list
09-08 14:32:05.816  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:05.816  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:05.849   971  1900 I ActivityManager: Process com.lge.appbox.client (pid 6435) has died
,09-08 14:32:05.851   436   957 I Sensors : sns_pwr.c(273):acquiring wakelock
09-08 14:32:05.852   971  1004 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
09-08 14:32:05.858   971  1004 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
09-08 14:32:05.858   971  1004 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
09-08 14:32:05.858   971  1004 D sensors_hal_Thresh: processInd: handle 48, count=1
09-08 14:32:05.858   971  1004 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
09-08 14:32:05.858   971  1004 I sensors_hal_Thresh: processInd : proximity state changed - FAR
09-08 14:32:05.858   971  1047 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
,09-08 14:32:05.858   971  1047 D sensors_hal_Ctx: poll: count: 256
09-08 14:32:05.858   971  1047 I sensors_hal_Ctx: poll: released wakelock sensor_ind
09-08 14:32:05.858   971  1047 D sensors_hal_Util: waitForResponse: timeout=0
09-08 14:32:05.879  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:32:05.881  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf2325a added. We now have 2 listener(s)
,09-08 14:32:05.881   971  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:05.884   971  1058 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
09-08 14:32:05.884   971  1058 I LPWGController: current mode = 1  value = 1 1
09-08 14:32:05.885  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-08 14:32:05.885  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:32:05.885   971  1058 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
09-08 14:32:05.885  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:32:05.885  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:32:05.885  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d130c8b added. We now have 2 listener(s)
09-08 14:32:05.886  5737  5825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:32:05.886  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:32:05.888  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:05.889  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:05.889  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:32:05.889  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:05.889  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:05.889  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:05.889  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:05.889  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:05.889  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:05.889  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:05.890  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:05.890  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:05.890  5737  5825 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:32:05.893   971   988 D WifiServiceImplEx: setWifiEnabled: false pid=5737, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
09-08 14:32:05.893   971   988 D WifiService: setWifiEnabled: false pid=5737, uid=10030
09-08 14:32:05.894  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:05.896  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:05.906   971   971 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:32:05.906   971   971 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:32:05.906   971   971 D Ulp_jni : JNI:system_update. Event-4
,09-08 14:32:05.920   971  1309 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 14:32:05.920   971  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:32:05.938   971  1974 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 14:32:05.942   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:05.942   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:05.943   274  1044 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:32:05.944   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
09-08 14:32:05.945   971  6139 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:05.958   971  1058 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
09-08 14:32:05.958  1737  6588 V NativeCrypto: Read error: ssl=0xb049f400: I/O error during system call, Connection timed out
,09-08 14:32:05.964  1737  6588 V NativeCrypto: SSL shutdown failed: ssl=0xb049f400: I/O error during system call, Broken pipe
09-08 14:32:05.964  1737  6622 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:05.970  1737  6622 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:05.974   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 10
09-08 14:32:05.974   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
09-08 14:32:05.974   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-08 14:32:05.974   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:05.976   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:05.977   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:05.980  1737  6588 E GCM     : Wifi connection closed with errorCode 20
09-08 14:32:05.981  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:05.982   971   971 D WifiHS20: hidePasspointNotification off =false
09-08 14:32:05.983   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:05.983   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:05.983   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:32:05.983   971   971 D WifiHS20: hidePasspointNotification off =false
09-08 14:32:05.983   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:05.983   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:05.983   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:32:05.986  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:05.986   971  1919 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10006
09-08 14:32:05.988  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:05.987 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:05.988  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:32:05.988  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,09-08 14:32:05.988  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:05.988  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:05.988 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:05.988  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:32:05.992   293   349 I ThermalEngine: Sensor:pa_therm0:35000 mC
09-08 14:32:05.995   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:05.995   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-7ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:05.996   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-08 14:32:05.997   971   971 D WifiScanningService: SCAN_AVAILABLE : 1
09-08 14:32:05.998   971  1332 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:05.998   971  1307 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:05.998   971  1307 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 14:32:06.001  1861  1885 D WifiServiceExtension: isInternetCheckAvailable return false
09-08 14:32:06.001   971   971 D RttService: SCAN_AVAILABLE : 1
09-08 14:32:06.002   971  1333 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:06.002   971  1307 D LGWifiP2pService: P2pDisablingState
09-08 14:32:06.002   971  1307 D LGWifiP2pService: P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:06.002   971  1307 D LGWifiP2pService: p2p socket connection lost
09-08 14:32:06.002   971  1307 D LGWifiP2pService: P2pDisabledState
09-08 14:32:06.004  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:06.004   971  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 14:32:06.004   971  1317 D ConnectivityService: ignoring duplicate network state non-change
09-08 14:32:06.004   971  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-08 14:32:06.004  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:06.005   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:06.005   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:06.006  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:06.006  1861  1861 D WfdsService: WifiP2pState is changed : false
09-08 14:32:06.006  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:06.006  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:06.006  1861  2153 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-08 14:32:06.007  1861  2153 D WfdsJNI : doCommand: P2P_STOP_FIND
09-08 14:32:06.007  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:06.009   971  1307 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:06.009   971  1307 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:06.010  1861  2153 D WfdsService: Set the WFDS Monitor: false
09-08 14:32:06.012  1861  2153 D WfdsMonitor: WFDS Monitor is stopped
09-08 14:32:06.012  1861  6122 D CtrlSupplicant: Received on exit socket, terminate
09-08 14:32:06.012  1861  6122 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-08 14:32:06.012  1861  2153 D WfdsService: STATE : WfdsDisabledState - enter
09-08 14:32:06.012  1861  2153 D WfdsService: WFDS: Scanner is paused
09-08 14:32:06.013  1861  2153 D WfdsDiscoveryStore: Clear Discovery Method Map: ScanAlwaysMode false
,09-08 14:32:06.013  1861  6122 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-08 14:32:06.013  1861  6122 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-08 14:32:06.014  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:06.014  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:06.014  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:06.014  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:06.016  1861  2142 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-08 14:32:06.017  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:06.017  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:06.019  1737  6622 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:06.019  1737  6622 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:06.026  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
,09-08 14:32:06.056  1737  6643 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:06.056  1737  6643 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-08 14:32:06.082   274  1039 E BandwidthController: [LG DATA] No such appUid: 10006
09-08 14:32:06.082   274  1039 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-08 14:32:06.082   274  1044 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:32:06.083   274  6755 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
09-08 14:32:06.084   274  6755 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:06.084   274  6755 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
09-08 14:32:06.085   971  1053 D DSQN    : DNS error code is not timeout ignore
09-08 14:32:06.085   971  1317 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-08 14:32:06.086   971  1317 D DSQN    : disableDataServiceNotify
09-08 14:32:06.086   971  1317 D DSQN    : stop dsqn bin
09-08 14:32:06.086  1737  1737 E ctxmgr  : [BaseServerTask]Server task (WriteInterestRecordTask) got error response.
09-08 14:32:06.088   971   971 D WifiHS20: hidePasspointNotification off =false
09-08 14:32:06.089  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:06.089  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:06.089 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:06.089  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:32:06.089   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:06.089   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:06.089   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:32:06.090  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:06.092  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:06.092  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:06.092  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:06.093  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:06.093  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:06.093  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:06.094  1737  2342 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = -1
09-08 14:32:06.096   971  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-08 14:32:06.097   971   971 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-08 14:32:06.098  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:06.099  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:06.098 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:06.099  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:32:06.099   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:06.099   971   971 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-08 14:32:06.103  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:06.103  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:06.103  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:06.103  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-08 14:32:06.104  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:06.104  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:06.104  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:06.104  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:06.104  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:32:06.104  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:06.104  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:06.104  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:06.104  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:06.105  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:06.105  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:32:06.108  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:32:06.108  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:06.108  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:06.108  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:06.108  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:32:06.108  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:06.108  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:06.108  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:06.108  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:06.112  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:06.112  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:32:06.112   971  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-08 14:32:06.112   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:06.113   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:06.113   971  1317 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:06.113   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:06.113   971  1317 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:06.114   971  1317 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-08 14:32:06.114   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:06.114   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:06.114   971  6138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-08 14:32:06.114  5434  5865 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 14:32:06.114  1373  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 14:32:06.120   971  1317 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-08 14:32:06.120   971  1317 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 14:32:06.120   971  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTI,VITY_CHANGE_IMMEDIATE
,09-08 14:32:06.124  1914  1914 W QCNEJ   : |CORE| No family connected
09-08 14:32:06.125   971  1306 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 14:32:06.126   971  1055 D Tethering: MasterInitialState.processMessage what=3
09-08 14:32:06.127   971  1317 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:06.127   971  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 14:32:06.129   971  1317 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:06.129   971  1317 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:06.129   971  1317 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:06.129   971  1317 D NetworkManagementService: Removing idletimer
09-08 14:32:06.130   971  1317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:06.130  1758  1758 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:06.130   971  1309 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:06.130  1758  1758 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-08 14:32:06.131   971  1309 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:06.131   971  1306 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-08 14:32:06.131  1914  1914 W QCNEJ   : |CORE| No family connected
09-08 14:32:06.132  1914  1914 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-08 14:32:06.132   971  1055 D Tethering: MasterInitialState.processMessage what=3
09-08 14:32:06.132  1914  1914 I QCNEJ   : |CORE| sendDefaultNwMsg: default = -1
,09-08 14:32:06.157   971  6139 D DhcpStateMachine: StoppedState
09-08 14:32:06.157   971  6139 D DhcpStateMachine: StoppedState{ when=-145ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 14:32:06.157  1373  1373 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:32:06.160  1373  1373 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-08 14:32:06.162  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:06.162  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:06.162  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:06.164  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:06.164  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:06.164  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:06.217   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-08 14:32:06.218   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 5
,09-08 14:32:06.220  6086  6086 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-08 14:32:06.220  6086  6086 I wpa_supplicant: monitor socket send errors count : 1
09-08 14:32:06.220  6086  6086 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1861-4\x00 that cannot receive messages
09-08 14:32:06.221   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 10
09-08 14:32:06.221   971  1900 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6757 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-08 14:32:06.221   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 7
09-08 14:32:06.222   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:06.222   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:06.233  6086  6086 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 14:32:06.234  6086  6086 W wpa_supplicant: USIM:  scard_deinit function
09-08 14:32:06.251   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:06.251   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:32:06.251   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:06.251   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,09-08 14:32:06.293  1373  1373 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-08 14:32:06.294  1373  1373 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-08 14:32:06.297  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:06.297  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:06.297  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:06.300  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:06.300  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:06.300  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:06.303   971  1351 D qdlights: set_light_backlight: 0
09-08 14:32:06.311   971  1058 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,09-08 14:32:06.313   971  1058 I sensors_hal_Ctx: activate: handle is 46, disable
09-08 14:32:06.313   971  1058 V sensors_hal_Ctx: activate sensors is 1000000000000
,09-08 14:32:06.313   971  1058 D sensors_hal_LP2: enable: handle=46
09-08 14:32:06.313   971  1058 D sensors_hal_LP2: enable: Disabling sensor handle=46
09-08 14:32:06.313   971  1058 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
09-08 14:32:06.314  1737  6643 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/172.217.16.202 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
09-08 14:32:06.318   246   246 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
09-08 14:32:06.318   246   246 D qdhwcomposer: hwc_blank: Blanking display: 0
09-08 14:32:06.319   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:32:06.322   971  1056 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
09-08 14:32:06.322   971   971 V ActivityManager: Display changed displayId=0
09-08 14:32:06.330   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 5
09-08 14:32:06.332  6086  6086 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-08 14:32:06.334   971  1055 D Tethering: InitialState.processMessage what=4
,09-08 14:32:06.335   971  1055 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 14:32:06.347   971  1309 D WifiOffDelayIfNotUsed: stopMonitoring
09-08 14:32:06.348  1861  1861 D WfdsService: Supplicant Connection state is changed : false
09-08 14:32:06.348  1861  2153 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-08 14:32:06.348  1861  2153 D WfdsService: Set the WFDS Monitor: false
09-08 14:32:06.348  1861  2153 D WfdsMonitor: WFDS Monitor is stopped
09-08 14:32:06.349  6602  6602 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:32:06.352  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:06.352  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:06.352 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:06.353  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:32:06.354  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:06.354  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:06.354  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:06.354  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-08 14:32:06.355   971   971 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-08 14:32:06.355   971  1315 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-08 14:32:06.355   971  1315 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-08 14:32:06.356  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:06.356  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:06.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:06.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:06.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:32:06.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:06.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:06.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:06.356  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:32:06.358  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:06.358  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:06.358  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:06.358  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:06.358  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:32:06.358  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:06.358  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:06.358  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:06.358  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:32:06.359  1737  2525 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider,.Settings.Global, returning read-only value.
,09-08 14:32:06.370  1758  1758 D DSDPConnection: Display #0 changed.
,09-08 14:32:06.389   971  1032 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
09-08 14:32:06.389   971  1032 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,09-08 14:32:06.434  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:06.434   971  1901 D WifiServiceImplEx: setWifiEnabled: true pid=5737, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,09-08 14:32:06.435   971  1901 D WifiService: setWifiEnabled: true pid=5737, uid=10030
09-08 14:32:06.451   971  1316 D WifiController: WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 455ms
,09-08 14:32:06.451   971   971 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-08 14:32:06.451   971   971 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-08 14:32:06.451   971   971 D Ulp_jni : JNI:system_update. Event-4
09-08 14:32:06.487   279  1295 I WVCdm   : CdmEngine::CloseSession
,09-08 14:32:06.526   246   246 D qdhwcomposer: hwc_blank: Done blanking display: 0
09-08 14:32:06.526   971  1351 D SurfaceControl: Excessive delay in setPowerMode(): 208ms
,09-08 14:32:06.527   246   689 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-08 14:32:06.527   971  1351 I QCOM PowerHAL: Got set_interactive hint
09-08 14:32:06.539  1373  1998 D KeyguardViewMediator: onScreenTurnedOff(3)
,09-08 14:32:06.547  5737  5737 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-08 14:32:06.547  5737  5737 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
09-08 14:32:06.550  1334  1350 D SmartCoverViewMediator: onScreenTurnedOff(3)
09-08 14:32:06.560  1373  1998 D KeyguardViewMediator: notifyScreenOffLocked
09-08 14:32:06.560   971   971 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
,09-08 14:32:06.560  1334  1350 D SmartCoverViewMediator: notifyScreenOffLocked
09-08 14:32:06.561  1334  1334 D SmartCoverViewMediator: handleNotifyScreenOFF
09-08 14:32:06.566   279  1608 I WVCdm   : CdmEngine::QueryKeyControlInfo
09-08 14:32:06.567   279  1325 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-08 14:32:06.567   279  1325 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-08 14:32:06.567   279  1325 I WVCdm   : CdmEngine::GenerateKeyRequest
09-08 14:32:06.569   279  1295 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 971
09-08 14:32:06.572   279  1295 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-08 14:32:06.572   279  1295 V voice   : voice_set_parameters: enter: screen_state=on
,09-08 14:32:06.574   279  1295 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
09-08 14:32:06.574   279  1295 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-08 14:32:06.574   279  1295 V voice   : voice_set_parameters: exit with code(0)
09-08 14:32:06.574   279  1295 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
09-08 14:32:06.574   279  1295 V msm8974_platform: platform_set_parameters: enter: screen_state=on
09-08 14:32:06.575   279  1295 V msm8974_platform: platform_set_parameters: exit with code(0)
09-08 14:32:06.575   279  1295 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-08 14:32:06.575   279  1295 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
09-08 14:32:06.575   279  1295 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-08 14:32:06.575   279  1295 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-08 14:32:06.578   279  1325 D WVCdm   : PrepareKeyRequest: nonce=3710909232
09-08 14:32:06.581  5737  5737 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@217c991c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c2dd981, 16908290=android.view.AbsSavedState$1@c2dd981}, android:focusedViewId=100}]}]
09-08 14:32:06.581  5737  5737 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-08 14:32:06.582  5737  5737 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 14:32:06.582  5737  5737 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-08 14:32:06.596  1373  1998 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
,09-08 14:32:06.596  1373  1373 D KeyguardViewMediator: handleNotifyScreenOff
09-08 14:32:06.610  1373  1373 D ScreenTurnOffBySensor: unregisterProximitySensor
,09-08 14:32:06.614   971  1640 I art     : Explicit concurrent mark sweep GC freed 40221(1929KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 6.240ms total 202.236ms
09-08 14:32:06.616  1373  1373 D StatusBarWindowView: onScreenTurnedOff why = 3
09-08 14:32:06.619  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-08 14:32:06.619  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
09-08 14:32:06.620   971  1045 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
09-08 14:32:06.658   971  1901 D SplitWindow: check instance of lgWin Window{198ea74c u0 SearchPanel}
,09-08 14:32:06.667  1914  1914 I QCNEJ   : |CORE| sendScreenState: state:true
09-08 14:32:06.671  6757  6757 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:06.676   971  1919 D InputDispatcher: Window went away: Window{80e3a72 u0 SearchPanel}
09-08 14:32:06.677  1861  2047 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
09-08 14:32:06.679  1861  2047 D LEDService: stopPatternFlashing()
,09-08 14:32:06.680  1861  2047 D qdlights: set_light_notifications: 0,0,0,0,3
09-08 14:32:06.681  1373  1373 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
09-08 14:32:06.681  1861  2047 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-08 14:32:06.681  1861  2047 D qdlights: set_light_notifications: 0,0,0,0,3
09-08 14:32:06.683  1861  2047 I LEDService: updateLightsLocked : turn off led
09-08 14:32:06.683  1861  2047 D qdlights: set_light_notifications: 0,0,0,0,3
09-08 14:32:06.684  1861  2047 D LEDHandler: RESTART MSG
09-08 14:32:06.701  1373  1373 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,09-08 14:32:06.710  1861  1861 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
09-08 14:32:06.711  1861  1861 D Cliptray Service: lockStatus = 0
09-08 14:32:06.716  1839  1839 D LNfcService: action : android.intent.action.SCREEN_ON
,09-08 14:32:06.722  1839  6779 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
09-08 14:32:06.722  1839  6779 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
09-08 14:32:06.722  1839  6779 D LNfcService: isRequireNfcCRouting() return true
09-08 14:32:06.727   971   971 D Ulp_jni : JNI:system_update. Event-0
,09-08 14:32:06.729  1839  6779 D LNfcService: isHCERoutingtoHost() return : true
09-08 14:32:06.729  1839  6779 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-08 14:32:06.729  1839  6779 D NfcService: mEnableLPD: true
09-08 14:32:06.729  1839  6779 D NfcService: mEnableReader: false
09-08 14:32:06.729  1839  6779 D NfcService: mEnableHostRouting: true
09-08 14:32:06.729  1839  6779 D NfcService: newParams.techmask= mTechMask: default
09-08 14:32:06.729  1839  6779 D NfcService: mEnableLPD: true
09-08 14:32:06.729  1839  6779 D NfcService: mEnableReader: false
09-08 14:32:06.729  1839  6779 D NfcService: mEnableHostRouting: true
09-08 14:32:06.729  1839  6779 D NfcService: screenState= 3
09-08 14:32:06.729  1839  6779 D NfcService: Discovery configuration equal, not updating.
,09-08 14:32:06.748  1758  1758 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
09-08 14:32:06.766  2820  2820 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:32:6
,09-08 14:32:06.768  2820  2820 D WeatherService: 2 : ACTION screen on
09-08 14:32:06.772  2820  2820 D WeatherService: 2 : shouldTimeTickRegistered : false
09-08 14:32:06.778  2820  2820 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 14:32:06.778  2820  2820 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:32:6
,09-08 14:32:06.789  3909  3909 D AppCleanupService: android.intent.action.SCREEN_ON
,09-08 14:32:06.809   279  1608 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 971
09-08 14:32:06.809   279  1608 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-08 14:32:06.809   279  1608 V voice   : voice_set_parameters: enter: screen_state=off
09-08 14:32:06.809   279  1608 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
09-08 14:32:06.809   279  1608 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-08 14:32:06.809   279  1608 V voice   : voice_set_parameters: exit with code(0)
09-08 14:32:06.809   279  1608 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
09-08 14:32:06.809   279  1608 V msm8974_platform: platform_set_parameters: enter: screen_state=off
09-08 14:32:06.809   279  1608 V msm8974_platform: platform_set_parameters: exit with code(0)
09-08 14:32:06.809   279  1608 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-08 14:32:06.809   279  1608 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-08 14:32:06.809   279  1608 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-08 14:32:06.811   971  1316 D WifiController: CMD_SCREEN_OFF 
09-08 14:32:06.811   971  1316 D WifiController: shouldWifiStayAwake TRUE
09-08 14:32:06.816  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
09-08 14:32:06.817   971  1045 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,09-08 14:32:06.845  1914  1914 I QCNEJ   : |CORE| sendScreenState: state:false
,09-08 14:32:06.847  1861  2047 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
09-08 14:32:06.848  1861  2047 D LEDService: stopPatternFlashing()
09-08 14:32:06.848  1861  2047 D qdlights: set_light_notifications: 0,0,0,0,3
09-08 14:32:06.848  1861  1861 D VolumeVibrator: clear
09-08 14:32:06.850  1861  2047 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-08 14:32:06.850  1861  2047 D qdlights: set_light_notifications: 0,0,0,0,3
09-08 14:32:06.850  1861  1861 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
09-08 14:32:06.851  1839  1839 D LNfcService: action : android.intent.action.SCREEN_OFF
09-08 14:32:06.853  1861  2047 I LEDService: updateLightsLocked : turn on led
09-08 14:32:06.853  1861  2047 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
09-08 14:32:06.853  1839  2179 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
09-08 14:32:06.853  1861  2047 E LEDService: Can't handle this request of patternId:0
09-08 14:32:06.853  1861  2047 D LEDHandler: RESTART MSG
09-08 14:32:06.878  1953  1953 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,09-08 14:32:06.896  1758  1758 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,09-08 14:32:06.903  2820  2820 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:32:6
09-08 14:32:06.903  2820  2820 D WeatherService: 2 : ACTION screen off
09-08 14:32:06.905  2820  2820 D WeatherService: 2 : TimeTick Receiver Unregister
09-08 14:32:06.905  2820  2820 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:32:6
09-08 14:32:06.911   971  1316 D WifiController: DEFERRED_TOGGLE handled
,09-08 14:32:06.914   971  1309 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-08 14:32:06.915  3909  3909 D AppCleanupService: android.intent.action.SCREEN_OFF
09-08 14:32:06.916   971  1309 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
09-08 14:32:06.916   971  1309 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
09-08 14:32:06.916   971  1309 E WifiHW  : band=b
09-08 14:32:06.916   971  1309 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
09-08 14:32:06.918   274  1044 D SoftapController: Softap fwReload - Ok
09-08 14:32:06.919   971  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:06.919   971  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:06.919   274  1044 D CommandListener: Setting iface cfg
09-08 14:32:06.919   274  1044 D CommandListener: Trying to bring down wlan0
09-08 14:32:06.920  3909  6785 D AppCleanupService: AppUsageStatsSaveTask
09-08 14:32:06.920   274  1044 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:32:06.922   971  1309 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-08 14:32:06.926   971  1309 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-08 14:32:06.930  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:32:06.930  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:06.93 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:06.931  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:32:06.931   971   971 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-08 14:32:06.933  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:06.934  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:06.935  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:06.936  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:06.936  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:06.936  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-08 14:32:06.966  6786  6786 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 14:32:07.026  6786  6786 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 14:32:07.026  6786  6786 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-08 14:32:07.079  1839  2610 E NxpNfcJni: getReconnectState = 0x0
,09-08 14:32:07.082  1839  2179 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-08 14:32:07.082  1839  2179 D LCardEmulationManager: getDefaultRoute
09-08 14:32:07.082  1839  2179 D LNfcService: isRequireNfcCRouting() return true
09-08 14:32:07.082  1839  2179 D LNfcService: isHCERoutingtoHost() return : true
09-08 14:32:07.082  1839  2179 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-08 14:32:07.082  1839  2179 D NfcService: mEnableLPD: true
09-08 14:32:07.082  1839  2179 D NfcService: mEnableReader: false
09-08 14:32:07.082  1839  2179 D NfcService: mEnableHostRouting: true
09-08 14:32:07.082  1839  2179 D NfcService: newParams.techmask= mTechMask: 0
09-08 14:32:07.082  1839  2179 D NfcService: mEnableLPD: true
09-08 14:32:07.082  1839  2179 D NfcService: mEnableReader: false
09-08 14:32:07.082  1839  2179 D NfcService: mEnableHostRouting: true
09-08 14:32:07.082  1839  2179 D NfcService: screenState= 1
09-08 14:32:07.138  1839  2610 E NxpNfcJni: getReconnectState = 0x0
,09-08 14:32:07.272   971  1869 I ActivityManager: Killing 6386:com.lge.lgdmsclient/1000 (adj 15): empty #11
,09-08 14:32:07.352   436   443 I Sensors : sns_pwr.c(301):releasing wakelock
,09-08 14:32:07.360   971  1901 W libprocessgroup: failed to open /acct/uid_1000/pid_6386/cgroup.procs: No such file or directory
09-08 14:32:07.420   971  2043 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6800 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,09-08 14:32:07.439   971  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{21a4ec38 type 2 when 154503 com.google.android.gms} when 154503
,09-08 14:32:07.625  6800  6800 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,09-08 14:32:07.627   971  1919 I ActivityManager: Killing 6468:com.lge.bnr/1000 (adj 15): empty #11
,09-08 14:32:07.715   971  6413 W libprocessgroup: failed to open /acct/uid_1000/pid_6468/cgroup.procs: No such file or directory
,09-08 14:32:07.718  2820  2820 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:32:7
,09-08 14:32:07.720  2820  2820 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:32:07.721  2820  2820 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
09-08 14:32:07.721  2820  2820 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:32:7
09-08 14:32:07.721  2820  2820 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
09-08 14:32:07.722  2820  2820 D WeatherService: 2 : shouldTimeTickRegistered : false
09-08 14:32:07.727  1737  6817 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:07.727  1737  6817 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:07.728  1737  6817 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:07.728  1737  6817 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:07.728   274  1039 E BandwidthController: [LG DATA] No such appUid: 10006
09-08 14:32:07.728   274  1039 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-08 14:32:07.728   274  6818 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
09-08 14:32:07.728   274  6818 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:07.729   274  6818 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
,09-08 14:32:07.730   971  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-08 14:32:07.731  1953  1953 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
09-08 14:32:07.736  1737  6819 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:07.736  1737  6819 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:07.736  1737  6819 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:07.736  1737  6819 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:07.736   274  1039 E BandwidthController: [LG DATA] No such appUid: 10006
09-08 14:32:07.736   274  1039 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-08 14:32:07.737   274  6820 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
09-08 14:32:07.737   274  6820 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:07.737   274  6820 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
09-08 14:32:07.737   971  1053 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-08 14:32:07.762  1953  2536 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
09-08 14:32:07.763  1953  2536 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
09-08 14:32:07.763  1953  2536 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,09-08 14:32:07.778  1953  2536 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,09-08 14:32:07.781   971  1324 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6824 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
09-08 14:32:07.782  1953  2536 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
,09-08 14:32:07.908  6824  6824 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
,09-08 14:32:07.916   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:32:07.917   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:32:07.919   971  1055 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 14:32:07.920  6824  6824 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
,09-08 14:32:07.924  1373  1373 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
09-08 14:32:07.924  1373  1373 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
09-08 14:32:07.924  1373  1373 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
09-08 14:32:07.924  1334  1334 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
09-08 14:32:07.930  6824  6824 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
09-08 14:32:07.930  6824  6824 V [BNRBootReceiver]: Boot Receiver Return
09-08 14:32:07.931  6824  6824 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-08 14:32:07.993   971  1640 I ActivityManager: Killing 6485:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,09-08 14:32:08.011  6786  6786 E wpa_supplicant: USIM:  scard_init function
09-08 14:32:08.011  6786  6786 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 14:32:08.013   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-08 14:32:08.015   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
09-08 14:32:08.015   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:08.015   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.016   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
09-08 14:32:08.060   971  1959 W libprocessgroup: failed to open /acct/uid_10038/pid_6485/cgroup.procs: No such file or directory
,09-08 14:32:08.098  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:08.102  6786  6786 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-08 14:32:08.122  6786  6786 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-08 14:32:08.123   971  1309 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
09-08 14:32:08.123   971  1309 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-08 14:32:08.125   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.125   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.126   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.126   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.126   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-08 14:32:08.131   971   971 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-08 14:32:08.131  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:08.131   971   971 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
09-08 14:32:08.131  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.131 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:08.131  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:32:08.131   971  1315 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-08 14:32:08.135  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:08.135  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:08.135  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:08.135  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:08.135  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:08.135  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:08.135  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:08.135  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:08.135  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:32:08.136  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:08.137  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:32:08.138  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:08.138  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.138  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.138  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
09-08 14:32:08.141  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:08.141  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:08.141  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:08.141  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:08.141  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:08.141  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:08.141  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:08.141  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:08.141  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:32:08.141  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:08.141  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:32:08.151   971  1309 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-08 14:32:08.153   243   243 E lowmemorykiller: Error writing /proc/6655/oom_score_adj; errno=22
,09-08 14:32:08.156   971  1309 D WifiStateMachine: enableVerboseLogging : level 2
09-08 14:32:08.161  1861  1861 D WfdsService: Supplicant Connection state is changed : true
,09-08 14:32:08.161  1861  2153 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
,09-08 14:32:08.161  1861  2153 D WfdsService: Set the WFDS Monitor: true,
09-08 14:32:08.161  1861  2153 D WfdsMonitor: WfdsMonitorThread create
09-08 14:32:08.161  1861  2153 D WfdsMonitor: WFDS Monitor is created and started
,09-08 14:32:08.161  1861  2153 D WfdsService: WiFi: Supplicant connection re-established
09-08 14:32:08.162   971  1309 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:32:08.162   971  1309 D WifiNative-HAL: Setting external_sim to 1
09-08 14:32:08.162   971  1309 I WifiNative-HAL: startHal
09-08 14:32:08.163  6602  6602 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.163   971  1309 D wifi    : setting scan oui 0x9a0902c8
09-08 14:32:08.163   971  1309 D WifiHAL : Sending mac address OUI
09-08 14:32:08.164   971  1309 E WifiHAL : failed to set scanning mac OUI; result = -95
09-08 14:32:08.164   971  1309 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:32:08.164   971  1309 I WifiNative-HAL: startHal
09-08 14:32:08.164   971  1309 D wifi    : setting scan oui 0x9a0902c8
09-08 14:32:08.164   971  1309 D WifiHAL : Sending mac address OUI
09-08 14:32:08.164   971  1309 E WifiHAL : failed to set scanning mac OUI; result = -95
09-08 14:32:08.175   971  1307 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.176   971   971 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 14:32:08.176   971   971 D RttService: SCAN_AVAILABLE : 3
09-08 14:32:08.177   971  1333 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.177   971  1332 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.177   971  1332 I WifiNative-HAL: startHal
09-08 14:32:08.177   971  1332 D wifi    : getting scan capabilities on interface[0] = 0x9a0902c8
09-08 14:32:08.177   971  1332 D WifiHAL : Creating message to get scan capablities; iface = 24
09-08 14:32:08.177   971  1332 D wifi    : failed to get capabilities : -95
09-08 14:32:08.177   971  1332 E WifiScanningService: could not get scan capabilities
09-08 14:32:08.179   971  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:08.179   971  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.179   274  1044 D CommandListener: Setting iface cfg
09-08 14:32:08.179   274  1044 D CommandListener: Trying to bring up p2p0
09-08 14:32:08.179   971  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 14:32:08.180   971  1307 D LGWifiP2pService: P2pEnablingState
09-08 14:32:08.180   971  1307 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.180   971  1307 D LGWifiP2pService: P2p socket connection successful
09-08 14:32:08.180   971  1307 D LGWifiP2pService: P2pEnabledState
09-08 14:32:08.180   971  1307 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-08 14:32:08.181   971  1307 D LGWifiP2pService: before postfix = G3s-1
09-08 14:32:08.181   971  1307 D WifiServerServiceExt: postfix byte check : 5
09-08 14:32:08.181   971  1307 D LGWifiP2pService: after postfix = G3s-1
09-08 14:32:08.182   971  1307 D WifiNative-HAL: p2pGetDeviceAddress
09-08 14:32:08.182   971  1307 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
09-08 14:32:08.183  1861  1861 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,09-08 14:32:08.184  1861  1861 D WfdsService: Update P2p Interface State: 3
09-08 14:32:08.184   971  1307 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
09-08 14:32:08.192   971  1309 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
09-08 14:32:08.192  5453  5469 I art     : Explicit concurrent mark sweep GC freed 2807(112KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.140ms total 37.516ms
09-08 14:32:08.192  1861  6846 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-08 14:32:08.193  1861  6846 E CtrlSupplicant: Succeed to open control connection
09-08 14:32:08.193  1861  6846 E CtrlSupplicant: Succeed to open monitor connection
09-08 14:32:08.194   971  1309 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-08 14:32:08.199   243   243 E lowmemorykiller: Error writing /proc/6655/oom_score_adj; errno=22
,09-08 14:32:08.219  6786  6786 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-08 14:32:08.219  1861  6846 D WfdsMonitor: Supplicant connection established
09-08 14:32:08.219  1861  2153 D WfdsService: Connected to the supplicant for wfds
09-08 14:32:08.219   971  1307 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,09-08 14:32:08.220   971  1309 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-08 14:32:08.220  6786  6786 E wpa_supplicant: disconnect_rssi_lvl: -100
09-08 14:32:08.221   971  1309 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
09-08 14:32:08.222  6786  6786 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
09-08 14:32:08.223   971  1309 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
09-08 14:32:08.231   971  1307 D LGWifiP2pService: sending p2p connection changed broadcast
,09-08 14:32:08.232  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
09-08 14:32:08.232  1861  1861 D WfdsService: WifiP2pState is changed : true
09-08 14:32:08.232  1861  2153 D WfdsService: Receive the WFDS_ENABLE Method
09-08 14:32:08.232  1861  2153 D WfdsService: Set the WFDS Monitor: true
09-08 14:32:08.232   971  1307 D LGWifiP2pService: InactiveState
09-08 14:32:08.232  1861  2153 D WfdsService: Connected to the supplicant for wfds
09-08 14:32:08.232  1861  2153 D WfdsJNI : doCommand: WFDS_SET TRUE
09-08 14:32:08.232   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.232   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.232   971  1307 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.232   971  1307 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.232   971  1307 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.233   971  1307 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.233  1861  1861 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-08 14:32:08.233   971   971 E WifiServerServiceExt: No p2p device connected
09-08 14:32:08.237  1861  1861 D WfdsService: isConnected: false
09-08 14:32:08.238   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.238   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.238   971  1307 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.239   971  1307 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.239   971  1307 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.239   971  1307 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.240  1861  1861 D WfdsService: GroupInfoAvailable: mGroupInfo is null
09-08 14:32:08.242  6786  6786 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-08 14:32:08.243  6786  6786 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-08 14:32:08.244  6786  6786 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz)
09-08 14:32:08.244  1861  2153 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
09-08 14:32:08.245  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 14:32:08.274  6786  6786 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
,09-08 14:32:08.274  1861  2153 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
09-08 14:32:08.274  1861  2153 D WfdsService: selectPreferredScanChannel [6]
09-08 14:32:08.274  1861  2153 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
09-08 14:32:08.274  1861  2153 W WfdsService: DefaultState - msg [9441285] is not handled
09-08 14:32:08.333   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:32:08.333   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:32:08.333   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:32:08.335  6786  6786 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 14:32:08.361  6786  6786 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:32:08.362  6786  6786 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-08 14:32:08.362   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-08 14:32:08.457  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:08.457  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:32:08.457  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:08.457  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:08.457  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:08.457  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf2325a removed from the list
09-08 14:32:08.457  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:08.457  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d130c8b removed from the list
09-08 14:32:08.457  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:08.457  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:08.479   971  6413 I ActivityManager: Process com.google.android.apps.magazines (pid 6655) has died
,09-08 14:32:08.485  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:08.485   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.485   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.485   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:32:08.486  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:08.486  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.486 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:08.486  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:32:08.491   971   971 D LocSvc_java: onReceive
,09-08 14:32:08.495  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:08.495  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.495  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.495  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:08.495  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:08.495  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:08.495  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:08.496  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:08.496   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.496   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.496   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-08 14:32:08.496  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.496 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:08.496   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.496   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.496   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:32:08.496  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-08 14:32:08.496  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:08.497  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.497 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:08.497  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:32:08.500  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:08.500  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.500  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.500  1373  1373 I [SystemUI]Quick,SettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:08.500  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:08.500  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:08.500  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:08.502   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.502   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.502   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-08 14:32:08.502  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,09-08 14:32:08.504  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.504 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:08.504  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:32:08.504   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.504  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:08.504   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.504   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-08 14:32:08.505  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.505 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:08.505  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:32:08.508  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:08.509  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.509  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.509  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:08.509  5737  6851 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-08 14:32:08.509  5737  6851 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-08 14:32:08.510  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:08.510  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:08.510  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:08.514  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,09-08 14:32:08.514  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.515  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.515  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:08.515  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:08.515  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:08.515  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:08.517   971  1309 I WifiServiceExtension: setVHTCapabilityType  : false
09-08 14:32:08.524  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:08.529  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,09-08 14:32:08.530  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,09-08 14:32:08.530  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:08.531  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:08.531  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:08.558   971  1383 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6855 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-08 14:32:08.562   971  1309 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-08 14:32:08.562   971  1309 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
09-08 14:32:08.562   971  1309 I WifiServiceExtension: setSecurityType  : 2
09-08 14:32:08.580   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.580   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.580   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 14:32:08.581   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.581   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.581   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-08 14:32:08.585   314   314 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 24.287ms
,09-08 14:32:08.591  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:08.592  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:08.593  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.593 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:08.593  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:32:08.593  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:08.594  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:08.594  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.594 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:08.594  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.594  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
09-08 14:32:08.594  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.595  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:08.595  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:08.595  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:08.595  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:08.598  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:08.598  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.598  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.598  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:08.598  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:08.598  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
,09-08 14:32:08.603   971  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-08 14:32:08.603   971  1317 D ConnectivityService: Got NetworkAgent Messenger
09-08 14:32:08.604   971  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 14:32:08.604   971  1317 D ConnectivityService: NetworkAgent connected
09-08 14:32:08.606  1861  1887 D WifiServiceExtension: isInternetCheckAvailable return false
09-08 14:32:08.606   971  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:32:08.610   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 337us total 23.763ms
09-08 14:32:08.615   971  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:32:08.623   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
09-08 14:32:08.629   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:08.629   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.630   971  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:08.630   971  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.630   274  1044 D CommandListener: Setting iface cfg
09-08 14:32:08.635   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 24.721ms
,09-08 14:32:08.640   971  1309 E WifiStateMachine: Start Dhcp Watchdog 3
09-08 14:32:08.642   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:08.642   971   971 D WifiServerServiceExt: setSupplicantStateSCANNING
09-08 14:32:08.643   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:08.643   971   971 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-08 14:32:08.644   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:08.644   971   971 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-08 14:32:08.645   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:08.645   971   971 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-08 14:32:08.646   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:08.646   971   971 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-08 14:32:08.648   971  6874 D DhcpStateMachine: StoppedState
09-08 14:32:08.649   971  6874 D DhcpStateMachine: StoppedState{ when=-9ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.649   971  6874 D DhcpStateMachine: WaitBeforeStartState
,09-08 14:32:08.652  1914  1914 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
09-08 14:32:08.653  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-52 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.652 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-08 14:32:08.654  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:08.654  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.654  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.656   971  1317 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-08 14:32:08.657   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:08.657   971   971 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 14:32:08.658   971   971 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-08 14:32:08.658   971   971 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-08 14:32:08.671  5434  6843 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,09-08 14:32:08.707  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-08 14:32:08.713  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:32:08.713  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:32:08.751   971  1309 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-08 14:32:08.751   971  1309 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:32:08.751   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14f470e5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.751   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14f470e5 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.751   971  1309 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:32:08.751   971  6874 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.751   971  6874 D DhcpStateMachine: DHCP Start wake lock is acquired.
,09-08 14:32:08.752   274  1044 D CommandListener: Setting iface cfg
09-08 14:32:08.753   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
09-08 14:32:08.755   274  1044 D CommandListener: Trying to bring up wlan0
09-08 14:32:08.757   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:08.757   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.758   971  1309 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-08 14:32:08.760   971  1317 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-08 14:32:08.761   971  1307 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 14:32:08.761   971  1307 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.765   971  6413 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6878 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-08 14:32:08.774   971  1309 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 14:32:08.774   971  1317 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-08 14:32:08.774   971  1317 D ConnectivityService: ignoring duplicate network state non-change
09-08 14:32:08.776   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.777   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.777   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 14:32:08.777   971  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 14:32:08.778   971  1317 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 14:32:08.779   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.779   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.779   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-08 14:32:08.782   971   971 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 14:32:08.782   971  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-08 14:32:08.784   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.784   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.784   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 14:32:08.784   971   971 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-08 14:32:08.786   971   971 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.786   971   971 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:08.786   971   971 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-08 14:32:08.798   971  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 14:32:08.798   971  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 14:32:08.799   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-08 14:32:08.799   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.800   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-08 14:32:08.800   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.801   971  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-08 14:32:08.802   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-08 14:32:08.802   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.802  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:08.803   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-08 14:32:08.803   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.804  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:08.805   279  1610 I WVCdm   : CdmEngine::CloseSession
09-08 14:32:08.806   274  1044 E Netd    : netlink response contains error (File exists)
09-08 14:32:08.806   971  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-08 14:32:08.807   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-08 14:32:08.807   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.807  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.807 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-08 14:32:08.807  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
09-08 14:32:08.807  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:08.808  1861  1885 D WifiServiceExtension: isInternetCheckAvailable return false
09-08 14:32:08.809  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:08.809   971  1317 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-08 14:32:08.809  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.809  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.809  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.808 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-08 14:32:08.809  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:08.809   971  1317 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-08 14:32:08.809  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.1,68.1.109 ipV6Addr=
09-08 14:32:08.809  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:08.809   971  1317 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-08 14:32:08.809   971  1317 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:08.809   971  1317 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.809  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:08.809  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:08.810   274  1044 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
09-08 14:32:08.810   274  1044 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:08.810  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.81 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-08 14:32:08.810  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-08 14:32:08.810  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-08 14:32:08.810  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-08 14:32:08.811   971  1317 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 14:32:08.811   971  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 14:32:08.811   971  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-08 14:32:08.811  1861  1887 D WifiServiceExtension: isInternetCheckAvailable return false
,09-08 14:32:08.811   971  1317 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-08 14:32:08.811   971  1317 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:08.811   971  6861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.811   971  6861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-08 14:32:08.811   971  1317 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:08.811   971  1317 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 14:32:08.811   971  6861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:08.811   971  1317 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:08.814   971  1317 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
09-08 14:32:08.814   971  1317 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:08.814   971  1317 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-08 14:32:08.814   971  1317 D ConnectivityService: currentScore = 0, newScore = 20
09-08 14:32:08.814   971  1317 D ConnectivityService:    accepting network in place of null
09-08 14:32:08.814   971  1317 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:08.815   971  1309 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:08.815   971  1309 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:08.815   279  1610 I WVCdm   : L3 Terminate.
09-08 14:32:08.817  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:08.812 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-08 14:32:08.817  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
09-08 14:32:08.820  1758  1758 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:08.820  1758  1758 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-08 14:32:08.821   971  1317 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBan,dwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-08 14:32:08.821   971  1317 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-08 14:32:08.821   971  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 14:32:08.821   971  1317 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:08.821   971  1317 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-08 14:32:08.821   971  1055 D Tethering: MasterInitialState.processMessage what=3
09-08 14:32:08.822   971  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-08 14:32:08.823   971  1317 D ConnectivityService: validation of new default Network = false
09-08 14:32:08.823   971  1317 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-08 14:32:08.823   971  1317 D DSQN    : enableDataServiceNotify 
09-08 14:32:08.823   971  1317 D DSQN    : start dsqn bin
09-08 14:32:08.824  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-08 14:32:08.824  1914  1914 W QCNEJ   : |CORE| No family connected
09-08 14:32:08.824  1914  1914 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-08 14:32:08.824  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.824  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.825  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:08.825  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:08.825  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:08.825  1914  1914 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
,09-08 14:32:08.826  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 14:32:08.830   971  6861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
09-08 14:32:08.831  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:32:08.831  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.831  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.832   971  6895 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
09-08 14:32:08.832  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:08.833  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:08.833  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:08.833  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-08 14:32:08.838  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,09-08 14:32:08.839  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.839  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.839  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-08 14:32:08.841   971  1306 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-08 14:32:08.842  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-08 14:32:08.842  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
09-08 14:32:08.843   971  1317 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-08 14:32:08.843   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:08.843   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:08.843   971  1317 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:08.844   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:08.844  1373  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:32:08.844   971  1317 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:08.845  5434  5865 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:32:08.853  6899  6899 I DSQN    : DSQN samuel.seo ver 141203
09-08 14:32:08.853  6899  6899 E DSQN    : DSQN sock connect success to lgdatalistenerd
09-08 14:32:08.854  6899  6899 I DSQN    : created command queue thread
09-08 14:32:08.854  6899  6899 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-08 14:32:08.854  6899  6899 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
,09-08 14:32:08.867  1373  1373 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-08 14:32:08.868  1373  1373 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-08 14:32:08.869  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:32:08.869  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.869  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.871  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:32:08.871  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:08.871  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:08.896  6878  6878 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 14:32:08.917  6318  6336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:08.917  6318  6336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:08.917  6318  6336 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:08.917  6318  6336 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:08.917  6318  6336 I Adreno-EGL: Remote Branch: 
09-08 14:32:08.917  6318  6336 I Adreno-EGL: Local Patches: 
09-08 14:32:08.917  6318  6336 I Adreno-EGL: Reconstruct Branch: 
,09-08 14:32:08.956   971  6874 D DhcpStateMachine: DHCPV4 request on wlan0
09-08 14:32:08.957   971  6874 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,09-08 14:32:08.957   971  6874 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-08 14:32:08.968  6903  6903 I dhcpcd  : version 5.5.6 starting
,09-08 14:32:08.970  6903  6903 E dhcpcd  : get_duid: Read-only file system
09-08 14:32:08.972   971  1055 D BluetoothManagerService: Message: 20
09-08 14:32:08.972   971  1055 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a0abe47:true
09-08 14:32:08.979  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:08.979  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
,09-08 14:32:08.991  6318  6336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:08.991  6318  6336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:08.991  6318  6336 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:08.991  6318  6336 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:08.991  6318  6336 I Adreno-EGL: Remote Branch: 
09-08 14:32:08.991  6318  6336 I Adreno-EGL: Local Patches: 
09-08 14:32:08.991  6318  6336 I Adreno-EGL: Reconstruct Branch: 
09-08 14:32:09.007  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:09.011  5737  6911 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.011  5737  6911 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.012  5737  6911 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.012  5737  6911 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:09.013   274  1039 E BandwidthController: [LG DATA] No such appUid: 10030
09-08 14:32:09.013   274  1039 D DnsProxyListener: App 10030 tries DNS query. Accept family:0 protocol:0
09-08 14:32:09.013   274  6913 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-08 14:32:09.013   274  6913 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:09.013   274  6913 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-08 14:32:09.013   274  6913 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.013  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.014  5737  6911 I System.out: propertyValue:false
09-08 14:32:09.017  5737  6911 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-08 14:32:09.018  5737  6911 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:32:09.018  5737  6851 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-08 14:32:09.018  5737  6851 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-08 14:32:09.020  5737  6911 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:09.021  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:32:09.021  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:32:09.021  5737  6851 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:09.021  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:32:09.022  5737  6851 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:09.023  5737  6851 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 14:32:09.027  5737  6911 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:09.027  5737  6915 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 823, name: OutgoingSocketThread/Sender)
09-08 14:32:09.029  5737  6916 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 824, name: OutgoingSocketThread/Receiver)
09-08 14:32:09.029  5737  6911 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 14:32:09.031  5737  6916 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 824, thread name: OutgoingSocketThread/Receiver)
09-08 14:32:09.031  5737  6916 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 14:32:09.031  5737  6916 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 824, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 14:32:09.031  5737  6918 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 822, name: IncomingSocketThread/Sender)
,09-08 14:32:09.034  5737  6919 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 825, name: IncomingSocketThread/Receiver)
09-08 14:32:09.035  5737  6919 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 825, thread name: IncomingSocketThread/Receiver)
09-08 14:32:09.035  5737  6919 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 14:32:09.035  5737  6919 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 825, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 14:32:09.037  6903  6903 I dhcpcd  : wlan0: rebinding lease of 192.168.1.109
09-08 14:32:09.040  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:09.044  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.047  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-08 14:32:09.047  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-08 14:32:09.048  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:32:09.053  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:09.057  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.059  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:32:09.066  6903  6903 I dhcpcd  : wlan0: acknowledged 192.168.1.109 from 192.168.1.1
,09-08 14:32:09.074  6519  6519 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-08 14:32:09.074  6519  6519 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-08 14:32:09.075  6519  6519 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-08 14:32:09.075  6519  6519 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-08 14:32:09.077  6519  6519 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-08 14:32:09.081  6318  6336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:09.081  6318  6336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:09.081  6318  6336 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:09.081  6318  6336 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:09.081  6318  6336 I Adreno-EGL: Remote Branch: 
09-08 14:32:09.081  6318  6336 I Adreno-EGL: Local Patches: 
09-08 14:32:09.081  6318  6336 I Adreno-EGL: Reconstruct Branch: 
09-08 14:32:09.097  6519  6519 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,09-08 14:32:09.097  6519  6519 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-08 14:32:09.097  6519  6519 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-08 14:32:09.098  6519  6519 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-08 14:32:09.098  6519  6519 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-08 14:32:09.098  6519  6519 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-08 14:32:09.099  6519  6519 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-08 14:32:09.099  6903  6903 I dhcpcd  : wlan0: leased 192.168.1.109 for 172800 seconds
09-08 14:32:09.127   971  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:09.147   971  6413 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6927 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-08 14:32:09.150   971  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:09.151   971  1045 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:09.152   971  1045 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:09.152   971  1045 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:09.152   971  1045 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:09.154   971   971 D LocSvc_java: onReceive
09-08 14:32:09.154   971   971 D LocSvc_java: got connectivity action
09-08 14:32:09.154   971   971 D LocSvc_java: broadcast - no network connections
09-08 14:32:09.154   971   971 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-08 14:32:09.154   971   971 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 14:32:09.155   971   971 D LocSvc_java: onReceive
09-08 14:32:09.155   971   971 D LocSvc_java: got connectivity action
09-08 14:32:09.155   971   971 D LocSvc_java: broadcast - no network connections
09-08 14:32:09.155   971   971 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
09-08 14:32:09.155   971   971 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-08 14:32:09.155   971   971 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 14:32:09.155   971   971 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 14:32:09.155   971   971 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 14:32:09.155   971   971 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 14:32:09.155   971   971 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 14:32:09.155   971   971 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-08 14:32:09.208  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
,09-08 14:32:09.214  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:09.214  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:09.214  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:09.214  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:09.214  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:09.214  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:09.214  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:09.214  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:09.214  5737  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:09.214  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
09-08 14:32:09.217  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:09.217  5737  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:09.221  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:09.324  6927  6927 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:32:09.324  6927  6927 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-08 14:32:09.327  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:32:09.329  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:32:09.332   971  6895 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
09-08 14:32:09.332   971  6895 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.332   971  6895 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.332   971  6895 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=102; mark=0
09-08 14:32:09.333   971  6895 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:09.333  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:09.333   274  1039 E BandwidthController: [LG DATA] No such appUid: 1000
09-08 14:32:09.333   274  1039 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-08 14:32:09.333   274  6960 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=983142
09-08 14:32:09.333   274  6960 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:09.334   274  6960 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-08 14:32:09.334   274  6960 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:09.337  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.340  6855  6855 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-08 14:32:09.340  6855  6855 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-08 14:32:09.340  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:32:09.343  6927  6961 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:32:09.345  6927  6961 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:32:09.349  6927  6959 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:32:09.351  6927  6959 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 14:32:09.352  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:32:09.359  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.359   971  6874 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.359   971  6874 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.359   971  6874 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.359   971  6874 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.360   971  6874 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.360   971  6874 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.360   971  6874 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.360   971  6874 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.360   971  6874 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-08 14:32:09.360  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-08 14:32:09.361   971  6874 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
09-08 14:32:09.362   971  6874 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-08 14:32:09.362   971  6874 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.362   971  6874 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.362   971  6874 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.109
09-08 14:32:09.362   971  6874 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-08 14:32:09.362   971  6874 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-08 14:32:09.362   971  6874 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-08 14:32:09.362   971  6874 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-08 14:32:09.362   971  6874 D DhcpStateMachine: RunningState
09-08 14:32:09.367  6927  6959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-08 14:32:09.370  6927  6927 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-08 14:32:09.373  6927  6927 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-08 14:32:09.373  6927  6927 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 14:32:09.374   971   971 D PowerManagerServiceEx: releaseWakeLockInternal: lock=304840138 [*alarm*], flags=0x0
09-08 14:32:09.375   274  6960 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:09.375  6927  6927 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 14:32:09.376   971  6895 I System.out: propertyValue:false
09-08 14:32:09.376   971  6895 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
09-08 14:32:09.376  1737  6966 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.376  1737  6966 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.377  1737  6966 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.377  1737  6966 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:09.377   971  6861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-08 14:32:09.377   274  1039 E BandwidthController: [LG DATA] No such appUid: 10006
09-08 14:32:09.377   274  1039 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-08 14:32:09.377   274  6967 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-08 14:32:09.377   274  6967 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:09.378   274  6967 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-08 14:32:09.378   274  6967 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:09.379  6927  6927 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
09-08 14:32:09.379   971  6861 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.380   971  6861 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-08 14:32:09.387   971   988 I ActivityManager: Killing 6540:com.lge.drmservice/u0a51 (adj 15): empty #11
,09-08 14:32:09.447  6899  6901 I DSQN    : first global connection report this to start monitoring at DSQM.
09-08 14:32:09.447  6899  6901 I DSQN    : restart monitoring
09-08 14:32:09.448  6899  6969 I DSQN    : dsqn report finish
09-08 14:32:09.448   274  1043 D LGDataListener: argv[0]=dsqncommand
09-08 14:32:09.448   274  1043 D LGDataListener: argv[1]=wlan0
09-08 14:32:09.448   274  1043 D LGDataListener: argv[2]=1
09-08 14:32:09.448   274  1043 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-08 14:32:09.449   971  1053 D DSQN    : DSQM DsqnNotification wlan0  1
,09-08 14:32:09.449   971  1053 D DSQN    : start to monitor internet connection
09-08 14:32:09.455   274  6967 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:09.455  1737  6966 I System.out: propertyValue:false
09-08 14:32:09.480   971  6861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:32:09 GMT], X-Android-Received-Millis=[1473337929479], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473337929447]}
09-08 14:32:09.480   971  6861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-08 14:32:09.480   971  1951 W libprocessgroup: failed to open /acct/uid_10051/pid_6540/cgroup.procs: No such file or directory
09-08 14:32:09.481  1953  1953 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
09-08 14:32:09.482  1953  4345 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,09-08 14:32:09.483  1861  1885 D WifiServiceExtension: isInternetCheckAvailable return false
09-08 14:32:09.483  1953  4345 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
09-08 14:32:09.483  1953  4345 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
09-08 14:32:09.483   971  6861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
09-08 14:32:09.483   971  6861 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-08 14:32:09.483   971  1317 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-08 14:32:09.483   971  1317 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-08 14:32:09.483   971  1317 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:09.483   971  1317 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:09.484   971  1317 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-08 14:32:09.484   971  1317 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:09.484   971  1317 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
09-08 14:32:09.484   971  1317 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-08 14:32:09.484   971  1317 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-08 14:32:09.484   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:09.484   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:09.484  1953  4345 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
09-08 14:32:09.484  1953  4345 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
09-08 14:32:09.484   971  1317 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:09.484  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:09.484   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:09.485   971   971 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
09-08 14:32:09.485  1373  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:32:09.485   971  1317 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:09.486   971  1317 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:09.486   971  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 14:32:09.486   971  1309 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
09-08 14:32:09.486   971  1309 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:09.487   971  1309, D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:09.487  5434  5865 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:32:09.487  1758  1758 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:09.487  1758  1758 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
09-08 14:32:09.493  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.496  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:32:09.510  6927  6927 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:32:09.511  6927  6927 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:32:09.511  1373  1373 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-08 14:32:09.512  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:32:09.512  1373  1373 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-08 14:32:09.514  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:32:09.514  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:09.514  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:09.516  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-08 14:32:09.516  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:09.516  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-08 14:32:09.517  5737  5825 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-08 14:32:09.518  5737  5825 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 14:32:09.520  5737  5825 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@217c991c Bundle[{}]
09-08 14:32:09.521  5737  5825 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 14:32:09.521  5737  5825 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-08 14:32:09.521  5737  5825 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 14:32:09.522  5737  5825 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 14:32:09.522  5737  5825 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 14:32:09.523  5737  5825 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-08 14:32:09.527  1737  6966 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.527  1737  6966 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.530  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,09-08 14:32:09.534  5737  6971 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-08 14:32:09.534  5737  6971 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-08 14:32:09.536  6824  6824 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 14:32:09.537  6927  6973 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:32:09.538  5737  6974 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.538  5737  6974 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.539   274  1037 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
09-08 14:32:09.539   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-08 14:32:09.540   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.541  5737  6974 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-08 14:32:09.541  5737  6971 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-08 14:32:09.541  5737  6971 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:32:09.541  5737  6971 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:09.541  5737  6974 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:32:09.541  5737  6974 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:09.541  6927  6975 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-08 14:32:09.541  5737  6974 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:09.541  5737  6971 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:32:09.541  6927  6975 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:32:09.541  5737  6971 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 14:32:09.541  5737  6974 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 14:32:09.543  6927  6973 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 14:32:09.543  5737  6977 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 836, name: OutgoingSocketThread/Sender)
09-08 14:32:09.544  6824  6824 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-08 14:32:09.545  5737  6980 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 838, name: IncomingSocketThread/Receiver)
09-08 14:32:09.545  5737  6980 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 838, thread name: IncomingSocketThread/Receiver)
09-08 14:32:09.545  5737  6980 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 14:32:09.545  5737  6980 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 838, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 14:32:09.547  5737  6978 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 837, name: IncomingSocketThread/Sender)
09-08 14:32:09.548  5737  6979 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 839, name: OutgoingSocketThread/Receiver)
09-08 14:32:09.548  5737  6979 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 839, thread name: OutgoingSocketThread/Receiver)
09-08 14:32:09.548  5737  6979 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 14:32:09.548  5737  6979 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 839, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 14:32:09.552  6927  6973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 14:32:09.555  6927  6927 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-08 14:32:09.555  6927  6927 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-08 14:32:09.555  6927  6927 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 14:32:09.557  6927  6927 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 14:32:09.560  6927  6927 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,09-08 14:32:09.599  6824  6824 V [BNRBootReceiver]: Boot Receiver Return
,09-08 14:32:09.602  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:09.608  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.618  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-08 14:32:09.622  6519  6519 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-08 14:32:09.622  5434  6593 I CheckinUtil: Classify the device as Phone.
09-08 14:32:09.624  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:09.627  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.638  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:09.644  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 14:32:09.652  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:09.658  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 14:32:09.666  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:09.671  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.678  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:09.683  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.693  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:09.697  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.706  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:09.710  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-08 14:32:09.728  5434  6593 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.729  5434  6593 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.729  5434  6593 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:09.729  5434  6593 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:09.730  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:09.730   274  1039 E BandwidthController: [LG DATA] No such appUid: 10006
09-08 14:32:09.730   274  1039 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-08 14:32:09.730   274  6986 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-08 14:32:09.730   274  6986 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:09.730   274  6986 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-08 14:32:09.731   274  6986 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,09-08 14:32:09.735  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.744  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-08 14:32:09.749  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.754  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 14:32:09.756  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:32:09.762  6519  6519 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-08 14:32:09.766  6519  6519 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-08 14:32:09.766   274  6986 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:09.766  5434  6593 I System.out: propertyValue:false
09-08 14:32:09.771  6855  6855 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-08 14:32:09.771  6855  6855 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-08 14:32:09.848   971  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 14:32:09.852  5434  6593 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-08 14:32:09.852  5434  6593 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:09.862   971  1324 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6988 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:09.878  6878  6878 V LGMDMManager: Create singleton instance
,09-08 14:32:09.926  5434  6593 I CheckinTask: Sending checkin request (11457 bytes)
,09-08 14:32:09.945  6878  6878 I AudioManager: getMode name:com.lge.qremote
,09-08 14:32:09.962  6988  6988 D UEI.SmartControl: Quickset Services start...
09-08 14:32:09.964  6988  6988 I UEI.SmartControl: Manufacture = LGE
09-08 14:32:09.966  6988  6988 D UEI.SmartControl: File observer start...
09-08 14:32:09.967  6988  6988 E UEI.SmartControl: IR Port is disabled: false
,09-08 14:32:09.968  6988  6988 D UEI.SmartControl: Starting file observer...
09-08 14:32:09.968  6988  6988 D UEI.SmartControl: Extracting JNI libs...
09-08 14:32:09.969  6988  6988 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-08 14:32:10.017   971  1383 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7010 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:10.049   971  1951 I ActivityManager: Process com.google.android.apps.plus (pid 6757) has died
,09-08 14:32:10.199   274  1037 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,09-08 14:32:10.199   971  1053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:10.200   971  1053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:10.206   971  1317 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-08 14:32:10.206   971  1317 D ConnectivityService: identical MTU - not setting
09-08 14:32:10.207   971  1317 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-08 14:32:10.207   971  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 14:32:10.207   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:10.207   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:10.208   971  1317 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-08 14:32:10.208   971  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-08 14:32:10.209  1373  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 14:32:10.210   971  1317 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:10.210   971  1317 D ConnectivityService: Wi-Fi IP changed. Lp difference / No Route difference
09-08 14:32:10.210   971  1317 D DSQN    : enableDataServiceNotify 
09-08 14:32:10.210   971  1317 D DSQN    : start dsqn bin
09-08 14:32:10.211  5434  5865 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 14:32:10.212  1914  1914 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
,09-08 14:32:10.214  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:10.213 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-08 14:32:10.230   971  1317 D DSQN    : dsqn is running restart
,09-08 14:32:10.254  7027  7027 I DSQN    : DSQN samuel.seo ver 141203
09-08 14:32:10.254  7027  7027 E DSQN    : DSQN sock connect success to lgdatalistenerd
09-08 14:32:10.254  7027  7027 I DSQN    : created command queue thread
09-08 14:32:10.254  7027  7027 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
09-08 14:32:10.254  7027  7027 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
,09-08 14:32:10.255  6988  6988 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-08 14:32:10.256  6988  6988 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-08 14:32:10.256  6988  6988 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-08 14:32:10.289   971  1951 I ActivityManager: Process com.android.chrome (pid 6722) has died
,09-08 14:32:10.293  6988  6988 I UEI.SmartControl: --- Selecting new region: 2
09-08 14:32:10.293  6988  6988 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
09-08 14:32:10.299  6988  6988 D UEI.SmartControl: Platform has CIR...
09-08 14:32:10.301  6988  6988 D UEI.SmartControl: NO CIR support, need to check package...
09-08 14:32:10.303  6988  6988 I UEI.SmartControl: Model: LG-D722 uses JNI
,09-08 14:32:10.307  6988  6988 D UEI.SmartControl: QS Service created
09-08 14:32:10.314  7010  7010 I MusicStore: Database version: 120
09-08 14:32:10.335  6988  6988 E UEI.SmartControl: QS start get config
,09-08 14:32:10.365  5434  6593 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
09-08 14:32:10.367  5434  6593 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
09-08 14:32:10.394  6988  6988 D UEI.SmartControl: Loading JNI Libs...
,09-08 14:32:10.397  6988  6988 D UEI.SmartControl:  configuring local db...
09-08 14:32:10.405   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-08 14:32:10.405   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-08 14:32:10.405   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:10.409  7010  7010 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,09-08 14:32:10.547   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:10.547   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-08 14:32:10.547   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:10.547  7010  7010 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,09-08 14:32:10.550   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:10.550   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-08 14:32:10.550   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:10.551  7010  7010 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-08 14:32:10.566   971  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{332828 type 2 when 157665 com.google.android.gms} when 157665
,09-08 14:32:10.573  5434  6593 I CheckinUtil: Classify the device as Phone.
,09-08 14:32:10.589  7010  7010 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-08 14:32:10.589  7010  7010 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 14:32:10.600  5434  6593 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
09-08 14:32:10.612  5434  6593 I CheckinChimeraService: Checking schedule, now: 1473337930612 next: 1473865179600
09-08 14:32:10.612  5434  6593 I CheckinChimeraService: active receiver: disabled
,09-08 14:32:10.650  5434  7046 I CheckinChimeraService: Checking schedule, now: 1473337930649 next: 1473865179600
09-08 14:32:10.650  5434  7046 I CheckinChimeraService: active receiver: disabled
,09-08 14:32:10.668  5434  5434 D CheckinChimeraService: Recording last checkin time for package unspecified as 1473337930668
,09-08 14:32:10.680  7010  7010 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-08 14:32:10.695  6988  6988 D UEI.SmartControl:  ---- Has DB8: true
09-08 14:32:10.703  6988  6988 D UEI.SmartControl: QS start statue = true Error code = 0
,09-08 14:32:10.703  6988  6988 D UEI.SmartControl: QS version = v2.7.11.1_RC1
09-08 14:32:10.704  6988  6988 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
09-08 14:32:10.710  6988  6988 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
09-08 14:32:10.731  6988  6988 W irrc_jni: IRRCPlayer_nativeInit ++ 
,09-08 14:32:10.732  6988  6988 D irrcClient: IrrcClient ++ 
09-08 14:32:10.732  6988  6988 D irrcClient: getIrrcService ++ 
09-08 14:32:10.732  6988  6988 D irrcClient: getIrrcService -- 
09-08 14:32:10.732  6988  6988 D irrcClient: IrrcClient -- 
09-08 14:32:10.732  6988  6988 W irrc_jni: IRRCPlayer_nativeInit -- 
09-08 14:32:10.738  6988  6988 D UEI.SmartControl: Services init done
09-08 14:32:10.741  6988  7048 I UEI.SmartControl: Device manager: loading config....
09-08 14:32:10.741  6988  6988 D UEI.SmartControl: QS Service init finished
09-08 14:32:10.745  6988  6988 D UEI.SmartControl: QS Service version name: 0.1.73
09-08 14:32:10.746  6988  6988 D UEI.SmartControl: QS Service version code: 1073
09-08 14:32:10.747  6988  6988 D UEI.SmartControl: Service requested: Control
09-08 14:32:10.750  6988  7048 D UEI.SmartControl: Config is loaded...
,09-08 14:32:10.779  7010  7010 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-08 14:32:10.780  7010  7010 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@243f7074: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-08 14:32:10.781  7010  7010 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-08 14:32:10.781  7010  7010 D AndroidMusic: GMSCore installation verified
09-08 14:32:10.786  7010  7010 I ConfigStore: Config Database version: 1
09-08 14:32:10.789  6988  7047 D UEI.SmartControl:  ----- QS SDK is ready!!!
09-08 14:32:10.790  6988  7047 I UEI.SmartControl: Notify AllClients services are ready: 0
09-08 14:32:10.791  6988  6988 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-08 14:32:10.793  6988  6988 D UEI.SmartControl: Internal service binding...
09-08 14:32:10.794  6988  7003 D UEI.SmartControl: -----IControl: 11
,09-08 14:32:10.795  6988  7003 D UEI.SmartControl: Caller: com.lge.qremote
09-08 14:32:10.795  6988  7003 D UEI.SmartControl: ------------ IControl registerCallback...
09-08 14:32:10.796  6988  7003 I UEI.SmartControl: Registering callback...
09-08 14:32:10.797  6988  7004 D UEI.SmartControl: -----IControl: 19
09-08 14:32:10.798  6988  7004 D UEI.SmartControl: Caller: com.lge.qremote
09-08 14:32:10.799  6988  7004 I UEI.SmartControl: Registering Services Ready callback...
09-08 14:32:10.799  6988  7004 I UEI.SmartControl: Notify client services are ready...
09-08 14:32:10.801  6988  7003 D UEI.SmartControl: -----IControl: 8
09-08 14:32:10.802  6988  7003 D UEI.SmartControl: Caller: com.lge.qremote
09-08 14:32:10.806   971  1919 I ActivityManager: Killing 6571:com.lge.settings.easy/1000 (adj 15): empty #11
,09-08 14:32:10.839   971  1324 W libprocessgroup: failed to open /acct/uid_1000/pid_6571/cgroup.procs: No such file or directory
,09-08 14:32:10.919  7010  7024 I art     : CheckpointMarkThreadRoots callback created = 0xb042d400
,09-08 14:32:10.920  7010  7010 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
09-08 14:32:10.929  7010  7010 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
09-08 14:32:10.940  7010  7010 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-08 14:32:10.945  7010  7024 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3e0
09-08 14:32:10.985   971  1932 I ActivityManager: Killing 6800:com.lge.clock/u0a10 (adj 15): empty #11
,09-08 14:32:10.996   293   349 I ThermalEngine: Sensor:pa_therm0:35000 mC
,09-08 14:32:11.000   971  1901 W libprocessgroup: failed to open /acct/uid_10010/pid_6800/cgroup.procs: No such file or directory
09-08 14:32:11.005   971  1307 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:11.005   971  1307 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:11.005   971  1307 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:11.007  7010  7010 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-08 14:32:11.050   971  1640 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7057 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-08 14:32:11.074  7010  7010 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,09-08 14:32:11.084  7010  7010 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 14:32:11.117   971  1324 I ActivityManager: Killing 6602:com.google.android.talk/u0a61 (adj 15): empty #11
,09-08 14:32:11.144  7057  7057 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:11.145  7057  7057 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 14:32:11.145  7057  7057 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 14:32:11.161   971  6413 W libprocessgroup: failed to open /acct/uid_10061/pid_6602/cgroup.procs: No such file or directory
,09-08 14:32:11.165  7010  7032 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,09-08 14:32:11.275  7057  7057 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-08 14:32:11.291  7057  7057 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,09-08 14:32:11.471  7057  7057 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-08 14:32:11.488  6927  6927 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:11.488  6927  6927 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-08 14:32:11.490  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:32:11.493  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:32:11.499  6927  7083 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-08 14:32:11.502  6927  7084 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:11.502  6927  7083 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 14:32:11.502  6927  7084 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-08 14:32:11.513  7057  7057 I HubEmail: JNI_OnLoad()
09-08 14:32:11.513  7057  7057 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:32:11.513  7057  7057 I HubEmail: registerNatives()
09-08 14:32:11.513  7057  7057 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:32:11.513  7057  7057 I HubEmail: registerNativeMethods()
09-08 14:32:11.513  7057  7057 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:32:11.513  7057  7057 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-08 14:32:11.539   971  1869 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7086 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-08 14:32:11.543  6927  7083 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 14:32:11.549  7057  7085 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:11.721   971  1901 I art     : Explicit concurrent mark sweep GC freed 96461(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 2.382ms total 172.498ms
,09-08 14:32:11.727  6927  6927 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-08 14:32:11.728  6927  6927 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-08 14:32:11.728  6927  6927 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 14:32:11.728   971  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{23bf85 type 2 when 158689 com.android.systemui} when 158689
09-08 14:32:11.730  6927  6927 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 14:32:11.732  1914  1914 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
09-08 14:32:11.732  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-09-08 14:32:11.732 DNS addrs= 192.168.1.1, 0.0.0.0, 
09-08 14:32:11.735  6927  6927 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,09-08 14:32:11.747  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,09-08 14:32:11.747  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-08 14:32:11.747  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,09-08 14:32:11.750   971  1324 I ActivityManager: Killing 6824:com.lge.bnr/1000 (adj 15): empty #11
09-08 14:32:11.779   971  1869 W libprocessgroup: failed to open /acct/uid_1000/pid_6824/cgroup.procs: No such file or directory
,09-08 14:32:11.784   971  1312 V WifiInternetCheck: Single check msg out of sync, ignoring.
09-08 14:32:11.799  7086  7086 I AppUp4:AppBoxCP: onCreate
,09-08 14:32:11.802  7086  7086 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-08 14:32:11.810  7086  7086 I AppUp4:DB:  setFingerPrint start
09-08 14:32:11.811  7086  7086 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,09-08 14:32:11.819  7086  7086 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-08 14:32:11.819  7086  7086 I AppUp4:DB:  SDK version = 21
09-08 14:32:11.819  7086  7086 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-08 14:32:11.820  7086  7086 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-08 14:32:11.822  7086  7086 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 14:32:11.823   971  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:11.824   971  1045 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:11.824   971  1045 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 14:32:11.826   971   971 D LocSvc_java: onReceive
09-08 14:32:11.826   971   971 D LocSvc_java: got connectivity action
09-08 14:32:11.826   971   971 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
09-08 14:32:11.826   971   971 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-08 14:32:11.826   971   971 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-08 14:32:11.826   971   971 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-08 14:32:11.826   971   971 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-08 14:32:11.828  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
09-08 14:32:11.842  7010  7010 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-08 14:32:11.845  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:11.848  7086  7086 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:11.851  7086  7086 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 14:32:11.851  7086  7086 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 14:32:11.860  7086  7086 I AppUp4:CustModeStarterReceiver: onReceive
09-08 14:32:11.860  7086  7086 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:11.865  7086  7086 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bf9db31
09-08 14:32:11.865  7086  7086 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 14:32:11.873  7086  7086 D AppUp4:CustFacade: isSimDevice : true
09-08 14:32:11.874  7086  7086 D AppUp4:CustModeStarterReceiver: begin check event
09-08 14:32:11.875  7086  7086 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,09-08 14:32:11.881  7086  7086 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,09-08 14:32:11.881  7086  7104 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,09-08 14:32:11.881  7086  7104 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-08 14:32:11.882  7086  7104 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-08 14:32:11.883   971  1959 I ActivityManager: Killing 6519:com.android.settings/1000 (adj 15): empty #11
09-08 14:32:11.980   971  1951 W libprocessgroup: failed to open /acct/uid_1000/pid_6519/cgroup.procs: No such file or directory
,09-08 14:32:11.992  3073  3073 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 14:32:11.992  3073  3073 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:11.992  3073  3073 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 14:32:12.036   971  1640 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7111 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,09-08 14:32:12.149  7111  7111 D PhoneMonitor: Register our PhoneStateListener
,09-08 14:32:12.163  7111  7111 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-08 14:32:12.164  7111  7111 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-08 14:32:12.167   971   988 I ActivityManager: Killing 6855:com.lge.sync/1000 (adj 15): empty #11
09-08 14:32:12.183   971  1900 W libprocessgroup: failed to open /acct/uid_1000/pid_6855/cgroup.procs: No such file or directory
,09-08 14:32:12.200  2616  2616 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:12.207  2616  2616 V DownloadManager: DownloadService onCreate
09-08 14:32:12.210  2616  7134 I DownloadManager: in removeSpuriousFiles
09-08 14:32:12.212  2616  2616 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
,09-08 14:32:12.219  2616  7134 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-08 14:32:12.220  2616  7134 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1699bb4e on behalf of 2616
09-08 14:32:12.224  2616  7134 I DownloadManager: in trimDatabase
09-08 14:32:12.224  2616  7134 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,09-08 14:32:12.225  7111  7111 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-08 14:32:12.226  2616  7134 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@36f2d57c on behalf of 2616
09-08 14:32:12.228  7111  7111 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-08 14:32:12.231  7111  7111 D TelephonyAutoProfiling: [parse] Load xml
09-08 14:32:12.235  7111  7111 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-08 14:32:12.236  7111  7111 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
09-08 14:32:12.243  7111  7111 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-08 14:32:12.251   971  1640 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7138 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-08 14:32:12.253  5434  7133 I CheckinChimeraService: Checking schedule, now: 1473337932252 next: 1473337960600
09-08 14:32:12.253  5434  7133 I CheckinChimeraService: active receiver: disabled
09-08 14:32:12.253  2616  2616 V DownloadManager: DownloadService onStartCommand
09-08 14:32:12.261  2616  7135 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-08 14:32:12.265  2616  7135 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@25a3e5a on behalf of 2616
,09-08 14:32:12.323  2616  2616 V DownloadManager: DownloadService onDestroy
,09-08 14:32:12.346   971  1932 I ActivityManager: Killing 6878:com.lge.qremote/u0a106 (adj 15): empty #11
,09-08 14:32:12.420  2820  2820 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:12
09-08 14:32:12.420   971  1919 W libprocessgroup: failed to open /acct/uid_10106/pid_6878/cgroup.procs: No such file or directory
,09-08 14:32:12.423  2820  2820 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:32:12.423  2820  2820 D WeatherAncestor: connectivity changed - connection : true
09-08 14:32:12.423  2820  2820 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 14:32:12.423  2820  2820 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:12
09-08 14:32:12.423  2820  2820 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:12.424  2820  2820 D WeatherService: 2 : shouldTimeTickRegistered : false
09-08 14:32:12.441  5434  7166 I CheckinChimeraService: Checking schedule, now: 1473337932441 next: 1473337930600
,09-08 14:32:12.441  5434  7166 I CheckinChimeraService: active receiver: enabled
09-08 14:32:12.460  5434  7166 I CheckinChimeraService: Preparing to send checkin request
09-08 14:32:12.460  5434  7166 I EventLogChimeraService: Accumulating logs since 1473337923622
,09-08 14:32:12.501   971   990 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7167 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-08 14:32:12.545  5737  5825 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 848)
,09-08 14:32:12.546  5737  5825 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-08 14:32:12.546  5737  5825 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 849)
09-08 14:32:12.552  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:32:12.552  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22911a26 added. We now have 2 listener(s)
09-08 14:32:12.552   971  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-08 14:32:12.555  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-08 14:32:12.555  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:32:12.555  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:32:12.555  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:32:12.555  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d23e667 added. We now have 2 listener(s)
09-08 14:32:12.556  5737  5825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:32:12.556  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:32:12.558  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:12.560  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:12.560  5737  5825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:32:12.560  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:12.560  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-08 14:32:12.560  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:12.560  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:32:12.560  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:12.560  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:12.560  5737  5825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:12.560  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:32:12.560  5737  5825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:12.561  5737  5825 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:32:12.561  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:32:12.563  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:32:12.563  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:12.563  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:12.563  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:12.563  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:12.564  5737  5825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22911a26 removed from the list
09-08 14:32:12.564  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:12.564  5737  5825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d23e667 removed from the list
09-08 14:32:12.565  5737  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:12.565  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:12.565  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:12.566  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:32:12.566  5737  5825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:32:12.566  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:32:12.566  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:12.566  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:32:12.572  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-08 14:32:12.573  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-08 14:32:12.573  5737  5825 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:32:12.574  5737  5737 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-08 14:32:12.593  5434  7166 I art     : Explicit concurrent mark sweep GC freed 22612(1539KB) AllocSpace objects, 26(419KB) LOS objects, 24% free, 15MB/20MB, paused 1.120ms total 122.095ms
09-08 14:32:12.621  5434  7166 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,09-08 14:32:12.623  5434  7166 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-08 14:32:12.665  7167  7167 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-08 14:32:12.789   279   279 I WVCdm   : CdmEngine::OpenSession
,09-08 14:32:12.789   279   279 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
09-08 14:32:12.821   279   279 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
09-08 14:32:12.822   279   279 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
09-08 14:32:12.822   279   279 W WVCdm   : L1 library not specified. Falling Back to L3
,09-08 14:32:12.887   279   279 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-08 14:32:12.887   279  1325 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-08 14:32:12.887   279  1325 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-08 14:32:12.887   279  1325 I WVCdm   : CdmEngine::GenerateKeyRequest
09-08 14:32:12.893   279  1325 D WVCdm   : PrepareKeyRequest: nonce=3130163194
09-08 14:32:12.954  7167  7194 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-08 14:32:12.954  7167  7194 I Babel_SMS: MmsConfig.loadMmsSettings
,09-08 14:32:12.958  7167  7194 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-08 14:32:12.958  7167  7194 I Babel_SMS: MmsConfig.loadFromDatabase
09-08 14:32:12.958   279  1295 I WVCdm   : CdmEngine::OpenSession
09-08 14:32:12.989   971  1312 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-08 14:32:12.989   971  1312 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:12.989   971  1312 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:12.989   971  1312 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:12.989   274  1039 E BandwidthController: [LG DATA] No such appUid: 1000
09-08 14:32:12.989   274  1039 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-08 14:32:12.989   274  7198 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-08 14:32:12.990   274  7198 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:12.990   274  7198 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-08 14:32:12.990   274  7198 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:13.025  7167  7194 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-08 14:32:13.025  7167  7194 I Babel_SMS: MmsConfig.loadFromResources
09-08 14:32:13.027  7167  7194 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-08 14:32:13.028  7167  7194 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,09-08 14:32:13.029   274  7198 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:13.030   971  1312 I System.out: propertyValue:false
09-08 14:32:13.032   971  1313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:13.032   971  1313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:13.032   971  1313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:13.032   971  1313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:13.033   274  1039 E BandwidthController: [LG DATA] No such appUid: 1000
09-08 14:32:13.033   274  1039 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
09-08 14:32:13.033   274  7201 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-08 14:32:13.033   274  7201 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:13.034   274  7201 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-08 14:32:13.034   274  7201 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:13.034   274  7201 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:13.034   971  1313 I System.out: propertyValue:false
09-08 14:32:13.056  7027  7028 I DSQN    : first global connection report this to start monitoring at DSQM.
,09-08 14:32:13.056  7027  7028 I DSQN    : restart monitoring
09-08 14:32:13.056  7027  7202 I DSQN    : dsqn report finish
09-08 14:32:13.056   274  1043 D LGDataListener: argv[0]=dsqncommand
09-08 14:32:13.056   274  1043 D LGDataListener: argv[1]=wlan0
09-08 14:32:13.056   274  1043 D LGDataListener: argv[2]=1
09-08 14:32:13.056   274  1043 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-08 14:32:13.057   971  1053 D DSQN    : DSQM DsqnNotification wlan0  1
09-08 14:32:13.057   971  1053 D DSQN    : start to monitor internet connection
,09-08 14:32:13.075  5737  5737 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:32:13.076  7167  7181 I art     : CheckpointMarkThreadRoots callback created = 0xb042d880
09-08 14:32:13.082   971  1313 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
09-08 14:32:13.106  7167  7181 I art     : CheckpointMarkThreadRoots callback created = 0xaae47db0
,09-08 14:32:13.112  7167  7167 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-08 14:32:13.112  7167  7167 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-08 14:32:13.112  7167  7167 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-08 14:32:13.112  7167  7167 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-08 14:32:13.113  7167  7167 D SensorManager: found sensor: Motion Accel, handle=46
09-08 14:32:13.146  7167  7167 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:32:13.149  7167  7167 I Babel_Crash: startup - clean
09-08 14:32:13.159  7167  7203 I Babel   : deleted: false for 0
09-08 14:32:13.253   971  1324 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7205 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:13.297  7167  7167 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,09-08 14:32:13.329  7167  7167 W AudioCapabilities: Unsupported mime audio/adpcm
09-08 14:32:13.332  7167  7167 W AudioCapabilities: Unsupported mime audio/g726
,09-08 14:32:13.333  7167  7167 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-08 14:32:13.334  7167  7167 W AudioCapabilities: Unsupported mime audio/wma-voice
09-08 14:32:13.335  7167  7167 W VideoCapabilities: Unsupported mime video/mjpg
09-08 14:32:13.344  7167  7167 W VideoCapabilities: Unsupported mime video/theora
,09-08 14:32:13.393  7167  7167 W AudioCapabilities: Unsupported mime audio/evrc
,09-08 14:32:13.394  7167  7167 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 14:32:13.396  7167  7167 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:13.410  7167  7167 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-08 14:32:13.411  7167  7167 W AudioCapabilities: Unsupported mime audio/qcelp
,09-08 14:32:13.413  7167  7167 W AudioCapabilities: Unsupported mime audio/evrc
09-08 14:32:13.424  7167  7167 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-08 14:32:13.439  7167  7167 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 14:32:13.454  7167  7167 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:13.455  7167  7167 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:32:13.459  7167  7167 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:13.467  7167  7167 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:13.482  7167  7167 I vclib   : onServiceConnected
,09-08 14:32:13.486  7167  7167 W Babel   : Attempted to change video mute state without an active call.
09-08 14:32:13.502  7167  7167 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,09-08 14:32:13.515  7167  7224 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:13.515  7167  7224 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:13.516  7167  7224 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:13.516  7167  7224 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,09-08 14:32:13.526   274  1039 E BandwidthController: [LG DATA] No such appUid: 10061
09-08 14:32:13.526   274  1039 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
09-08 14:32:13.526   274  7227 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-08 14:32:13.526   274  7227 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:13.527   274  7227 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-08 14:32:13.527   274  7227 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:13.527   274  7227 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:13.528  7167  7224 I System.out: propertyValue:false
,09-08 14:32:13.569   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:13.569   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 14:32:13.569   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 14:32:13.573  7205  7230 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 14:32:13.584   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:13.584   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 14:32:13.584   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 14:32:13.593  7167  7224 I Babel   : connection state changed from UNKNOWN to CONNECTED
09-08 14:32:13.605  7205  7230 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-08 14:32:13.619  7205  7205 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 14:32:13.619  7205  7205 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 14:32:13.619  7205  7205 I GAv4    :   adb logcat -s GAv4
,09-08 14:32:13.657   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:13.658   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 14:32:13.658   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:13.658  7205  7231 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-08 14:32:13.660   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:13.660   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 14:32:13.660   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:13.661  7205  7231 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 14:32:13.694  5434  5445 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-08 14:32:13.719  7205  7205 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:32:13.746  7205  7205 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:32:13.751  7205  7233 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:32:14.007  7205  7205 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,09-08 14:32:14.057  7205  7205 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1165-1168)
,09-08 14:32:14.058  7205  7205 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:32:14.066  7205  7205 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {386ef20a}
09-08 14:32:14.067  7205  7205 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:32:14.067  7205  7205 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 14:32:14.080  7205  7205 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 14:32:14.081  7205  7205 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 14:32:14.082  7205  7205 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 14:32:14.101  7205  7205 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 14:32:14.107  7205  7205 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 14:32:14.107  7205  7205 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 14:32:14.108  7205  7205 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:14.108  7205  7205 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:14.108  7205  7205 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:14.108  7205  7205 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:14.108  7205  7205 I Adreno-EGL: Remote Branch: 
09-08 14:32:14.108  7205  7205 I Adreno-EGL: Local Patches: 
09-08 14:32:14.108  7205  7205 I Adreno-EGL: Reconstruct Branch: 
09-08 14:32:14.186  7205  7205 I NSApplication: Starting up...
,09-08 14:32:14.189   279  1610 V AudioPolicyService: registerClient() client 0xb57f3020, uid 10079
09-08 14:32:14.199  7205  7264 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 14:32:14.241   971  1324 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7269 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:32:14.266   314   314 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 22.318ms
,09-08 14:32:14.291   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 24.360ms
,09-08 14:32:14.313   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.368ms
,09-08 14:32:14.509   971   988 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7288 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-08 14:32:14.509   971   988 I ActivityManager: Killing 6988:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,09-08 14:32:14.789   971  1901 W libprocessgroup: failed to open /acct/uid_10089/pid_6988/cgroup.procs: No such file or directory
,09-08 14:32:14.839  7288  7288 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:32:14.998   279  1610 I WVCdm   : CdmEngine::CloseSession
,09-08 14:32:15.068   279  1295 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-08 14:32:15.069   279  1325 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-08 14:32:15.069   279  1325 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-08 14:32:15.069   279  1325 I WVCdm   : CdmEngine::GenerateKeyRequest
09-08 14:32:15.079   279  1325 D WVCdm   : PrepareKeyRequest: nonce=1950394459
,09-08 14:32:15.317   971  1869 I ActivityManager: Killing 7010:com.google.android.music:main/u0a81 (adj 15): empty #11
,09-08 14:32:15.400   971  6413 W libprocessgroup: failed to open /acct/uid_10081/pid_7010/cgroup.procs: No such file or directory
,09-08 14:32:15.476   971  2043 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7333 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:15.573  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 14:32:15.573  5737  5825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 14:32:15.609  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:15.609  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:15.609  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:15.609  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22911a26 not in the list
09-08 14:32:15.609  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:15.609  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:32:15.609  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:32:15.609  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:32:15.610  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:32:15.615  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:15.616  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:32:15.616  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d23e667 not in the list
09-08 14:32:15.616  5737  5737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:32:15.616  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:15.616  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:15.616  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:15.616  5737  5737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:32:15.616  5737  5737 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:32:15.626  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 14:32:15.632  5737  5825 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-08 14:32:15.634  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-08 14:32:15.635  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:32:15.635  5737  5825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 14:32:15.635  5737  5825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 14:32:15.635  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:15.636  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-08 14:32:15.637  5737  5825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-08 14:32:15.637  5737  5737 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-08 14:32:15.647  5737  5825 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
09-08 14:32:15.647  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 14:32:15.647  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:15.647  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 14:32:15.649  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-08 14:32:15.650  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-08 14:32:15.650  5737  5825 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:32:15.653  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:15.654  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:32:15.654  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:15.654  5737  5825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-08 14:32:15.654  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22911a26 not in the list
09-08 14:32:15.654  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:15.654  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:32:15.654  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:32:15.654  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:32:15.654  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:32:15.654  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:15.654  5737  5737 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-08 14:32:15.654  5737  5737 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 14:32:15.655  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:32:15.655  5737  5737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:32:15.655  5737  5737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:32:15.655  5737  5737 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:32:15.655  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d23e667 not in the list
09-08 14:32:15.655  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:15.655  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:15.655  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:15.656  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:32:15.656  5737  5825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:32:15.656  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start adve,rtiser: false
09-08 14:32:15.656  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:15.656  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:32:15.659  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-08 14:32:15.659  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-08 14:32:15.659  5737  5825 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-08 14:32:15.659  5737  5737 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-08 14:32:15.718  7333  7333 I MusicStore: Database version: 120
,09-08 14:32:15.763   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-08 14:32:15.763   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-08 14:32:15.763   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:15.763  7333  7333 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-08 14:32:15.897   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-08 14:32:15.897   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-08 14:32:15.897   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:15.897  7333  7333 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,09-08 14:32:15.900   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:15.900   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-08 14:32:15.900   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:15.901  7333  7333 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-08 14:32:15.944  7333  7333 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-08 14:32:15.944  7333  7333 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 14:32:16.001   293   349 I ThermalEngine: Sensor:pa_therm0:35000 mC
,09-08 14:32:16.020  7333  7333 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-08 14:32:16.109  7333  7333 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-08 14:32:16.109  7333  7333 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@243f7074: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-08 14:32:16.110  7333  7333 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-08 14:32:16.110  7333  7333 D AndroidMusic: GMSCore installation verified
09-08 14:32:16.116  7333  7333 I ConfigStore: Config Database version: 1
,09-08 14:32:16.160  5737  5737 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:32:16.228  7333  7333 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-08 14:32:16.237  7333  7333 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-08 14:32:16.245  7333  7347 I art     : CheckpointMarkThreadRoots callback created = 0xb042d400
,09-08 14:32:16.252  7333  7333 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-08 14:32:16.271  7333  7347 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3e0
,09-08 14:32:16.300  7333  7333 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-08 14:32:16.309  6927  6927 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:16.310  6927  6927 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:32:16.311  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:32:16.316  6927  6927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,09-08 14:32:16.318  7057  7368 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:16.320  7086  7086 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 14:32:16.320  7086  7086 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:16.320  7086  7086 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 14:32:16.320  7086  7086 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 14:32:16.330  6927  7369 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 14:32:16.332  7086  7086 I AppUp4:CustModeStarterReceiver: onReceive
09-08 14:32:16.332  7086  7086 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:16.332  7086  7086 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bf9db31
09-08 14:32:16.332  7086  7086 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 14:32:16.334  6927  7370 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:16.335  6927  7370 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:32:16.333  7086  7086 D AppUp4:CustFacade: isSimDevice : true
09-08 14:32:16.336  7086  7086 D AppUp4:CustModeStarterReceiver: begin check event
09-08 14:32:16.337  7086  7086 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-08 14:32:16.339  3073  3073 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 14:32:16.340  3073  3073 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:16.340  3073  3073 I LgeMiscReceiver: networkInfo.isConnected() = false
09-08 14:32:16.342  7111  7111 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-08 14:32:16.342  7111  7111 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 14:32:16.344  6927  7369 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 14:32:16.349  2616  2616 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:16.352  2616  2616 V DownloadManager: DownloadService onCreate
09-08 14:32:16.355  2820  2820 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:16
09-08 14:32:16.355  2616  7375 I DownloadManager: in removeSpuriousFiles
09-08 14:32:16.356  2616  7375 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-08 14:32:16.358  2616  7375 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3d55cd68 on behalf of 2616
09-08 14:32:16.360  2820  2820 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:32:16.360  2820  2820 D WeatherAncestor: connectivity changed - connection : true
09-08 14:32:16.360  2820  2820 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 14:32:16.360  2616  7375 I DownloadManager: in trimDatabase
09-08 14:32:16.360  2820  2820 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:16
09-08 14:32:16.360  2616  7375 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-08 14:32:16.361  2616  7375 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@88e5581 on behalf of 2616
09-08 14:32:16.362  2820  2820 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:16.363  2820  2820 D WeatherService: 2 : shouldTimeTickRegistered : false
09-08 14:32:16.366  6927  7369 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 14:32:16.368  7333  7333 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,09-08 14:32:16.369  6927  6927 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
09-08 14:32:16.370  6927  6927 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-08 14:32:16.370  6927  6927 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 14:32:16.371  2616  2616 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
,09-08 14:32:16.372  6927  6927 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-08 14:32:16.384  6927  6927 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
09-08 14:32:16.386  7333  7333 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
09-08 14:32:16.394  2616  2616 V DownloadManager: DownloadService onStartCommand
,09-08 14:32:16.394  2616  7376 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-08 14:32:16.398  2616  7376 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3a6e5814 on behalf of 2616
09-08 14:32:16.430   971  1901 I ActivityManager: Killing 7167:com.google.android.talk/u0a61 (adj 15): empty #11
,09-08 14:32:16.525   971  1324 I art     : Explicit concurrent mark sweep GC freed 26732(1333KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.107ms total 154.913ms
,09-08 14:32:16.559   971  1932 W libprocessgroup: failed to open /acct/uid_10061/pid_7167/cgroup.procs: No such file or directory
,09-08 14:32:16.565  2616  2616 V DownloadManager: DownloadService onDestroy
09-08 14:32:16.572  7333  7357 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,09-08 14:32:16.616   971  1919 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7381 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-08 14:32:16.774  7381  7381 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-08 14:32:16.837   971  1285 V AlarmManager: RTC_WAKEUP set : Alarm{542c114 type 0 when 1473337936834 com.google.android.googlequicksearchbox} when 1473337936834
,09-08 14:32:16.987  7381  7410 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-08 14:32:16.987  7381  7410 I Babel_SMS: MmsConfig.loadMmsSettings
,09-08 14:32:16.990  7381  7410 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-08 14:32:16.990  7381  7410 I Babel_SMS: MmsConfig.loadFromDatabase
,09-08 14:32:17.037  7381  7410 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-08 14:32:17.038  7381  7410 I Babel_SMS: MmsConfig.loadFromResources
09-08 14:32:17.039  7381  7410 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-08 14:32:17.039  7381  7410 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-08 14:32:17.056  7381  7381 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-08 14:32:17.057  7381  7381 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-08 14:32:17.057  7381  7381 D SensorManager: found sensor: Motion Accel, handle=46
,09-08 14:32:17.089  7381  7381 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:17.092  7381  7381 I Babel_Crash: startup - clean
,09-08 14:32:17.118  7381  7398 I art     : CheckpointMarkThreadRoots callback created = 0xaaf3e500
,09-08 14:32:17.142  7381  7419 I Babel   : deleted: false for 0
,09-08 14:32:17.165   279  1608 I WVCdm   : CdmEngine::CloseSession
,09-08 14:32:17.170   279  1608 I WVCdm   : L3 Terminate.
09-08 14:32:17.170  7381  7398 I art     : CheckpointMarkThreadRoots callback created = 0xaaf3e4f0
09-08 14:32:17.207  7381  7381 W AudioCapabilities: Unsupported mime audio/x-lg-flac
09-08 14:32:17.219  7381  7381 W AudioCapabilities: Unsupported mime audio/adpcm
09-08 14:32:17.221  7381  7381 W AudioCapabilities: Unsupported mime audio/g726
,09-08 14:32:17.222  7381  7381 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-08 14:32:17.223  7381  7381 W AudioCapabilities: Unsupported mime audio/wma-voice
09-08 14:32:17.225  7381  7381 W VideoCapabilities: Unsupported mime video/mjpg
09-08 14:32:17.227  7381  7381 W VideoCapabilities: Unsupported mime video/theora
09-08 14:32:17.232  6318  6336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:17.232  6318  6336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:17.232  6318  6336 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:17.232  6318  6336 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:17.232  6318  6336 I Adreno-EGL: Remote Branch: 
09-08 14:32:17.232  6318  6336 I Adreno-EGL: Local Patches: 
09-08 14:32:17.232  6318  6336 I Adreno-EGL: Reconstruct Branch: 
09-08 14:32:17.256  7381  7381 W AudioCapabilities: Unsupported mime audio/evrc
09-08 14:32:17.257  7381  7381 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 14:32:17.258  7381  7381 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:32:17.265  7381  7381 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-08 14:32:17.266  7381  7381 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 14:32:17.267  7381  7381 W AudioCapabilities: Unsupported mime audio/evrc
09-08 14:32:17.277  7381  7381 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-08 14:32:17.295  7381  7381 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-08 14:32:17.298  6318  6336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:17.298  6318  6336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:17.298  6318  6336 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:17.298  6318  6336 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:17.298  6318  6336 I Adreno-EGL: Remote Branch: 
09-08 14:32:17.298  6318  6336 I Adreno-EGL: Local Patches: 
09-08 14:32:17.298  6318  6336 I Adreno-EGL: Reconstruct Branch: 
09-08 14:32:17.303  7381  7381 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:17.305  7381  7381 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:32:17.309  7381  7381 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:17.314  7381  7381 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:17.338  7381  7422 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:17.338  7381  7422 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:17.339  7381  7422 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:17.339  7381  7422 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:17.339   274  1039 E BandwidthController: [LG DATA] No such appUid: 10061
09-08 14:32:17.339   274  1039 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
09-08 14:32:17.339   274  7424 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-08 14:32:17.339   274  7424 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,09-08 14:32:17.340   274  7424 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-08 14:32:17.340   274  7424 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:17.340   274  7424 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:17.341  7381  7422 I System.out: propertyValue:false
,09-08 14:32:17.353  6318  6336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-08 14:32:17.353  6318  6336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-08 14:32:17.353  6318  6336 I Adreno-EGL: Build Date: 03/02/15 Mon
09-08 14:32:17.353  6318  6336 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-08 14:32:17.353  6318  6336 I Adreno-EGL: Remote Branch: 
09-08 14:32:17.353  6318  6336 I Adreno-EGL: Local Patches: 
09-08 14:32:17.353  6318  6336 I Adreno-EGL: Reconstruct Branch: 
09-08 14:32:17.415  7381  7381 I vclib   : onServiceConnected
09-08 14:32:17.416  7381  7381 W Babel   : Attempted to change video mute state without an active call.
,09-08 14:32:17.434  7381  7381 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,09-08 14:32:17.453  7381  7422 I Babel   : connection state changed from UNKNOWN to CONNECTED
,09-08 14:32:17.479  7111  7111 V SetupWizard: Connected to Gservices successfully
,09-08 14:32:17.485   971  2043 I ActivityManager: Killing 7333:com.google.android.music:main/u0a81 (adj 15): empty #11
09-08 14:32:17.650   971  1974 W libprocessgroup: failed to open /acct/uid_10081/pid_7333/cgroup.procs: No such file or directory
,09-08 14:32:17.691  5434  5434 D GCM     : COMPAT: Enabling multi user even though supportsMultipleUsers=false
,09-08 14:32:17.703  5434  5434 D GCM     : COMPAT: Multi user ser=0 current=0
,09-08 14:32:17.813   971   988 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7433 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-08 14:32:17.822  1737  7439 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-08 14:32:17.831  5434  7166 I CheckinUtil: Classify the device as Phone.
,09-08 14:32:17.886  5434  7166 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:17.886  5434  7166 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:17.886  5434  7166 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:17.886  5434  7166 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:17.887   274  1039 E BandwidthController: [LG DATA] No such appUid: 10006
09-08 14:32:17.887   274  1039 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
09-08 14:32:17.887   274  7453 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-08 14:32:17.887   274  7453 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:17.888   274  7453 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-08 14:32:17.888   274  7453 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:17.889   274  7453 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:17.889  5434  7166 I System.out: propertyValue:false
09-08 14:32:17.899  7433  7433 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-08 14:32:17.968   971  1055 D BluetoothManagerService: Message: 20
,09-08 14:32:17.970   971  1055 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1192e56b:true
09-08 14:32:17.974  5434  7166 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:17.975  5434  7166 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:17.977  2082  2102 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:17.978  2082  3270 D BluetoothAdapterService(579935620): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1fc9bafa
09-08 14:32:18.041  5434  7166 I CheckinTask: Sending checkin request (11436 bytes)
,09-08 14:32:18.069   971  1640 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7455 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:18.090  7433  7433 V LGMDMManager: Create singleton instance
,09-08 14:32:18.169  7455  7455 D UEI.SmartControl: Quickset Services start...
09-08 14:32:18.172  7455  7455 I UEI.SmartControl: Manufacture = LGE
,09-08 14:32:18.179  7455  7455 D UEI.SmartControl: File observer start...
09-08 14:32:18.180  7455  7455 E UEI.SmartControl: IR Port is disabled: false
09-08 14:32:18.181  7455  7455 D UEI.SmartControl: Starting file observer...
09-08 14:32:18.181  7455  7455 D UEI.SmartControl: Extracting JNI libs...
09-08 14:32:18.182  7455  7455 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-08 14:32:18.188  7433  7433 I AudioManager: getMode name:com.lge.qremote
09-08 14:32:18.204  1373  1373 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,09-08 14:32:18.236  1758  1787 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-08 14:32:18.241  1758  1787 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-08 14:32:18.242  1758  1787 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-08 14:32:18.248  1758  1787 V TelecomServiceImpl: getCallState : 0
,09-08 14:32:18.250  1758  1788 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-08 14:32:18.250  1758  1788 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-08 14:32:18.250  1758  1788 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-08 14:32:18.253  1373  1373 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
09-08 14:32:18.255  1373  1373 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
09-08 14:32:18.304   971  1640 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7480 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:18.389  7455  7455 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-08 14:32:18.391  7455  7455 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-08 14:32:18.391  7455  7455 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-08 14:32:18.446  7455  7455 I UEI.SmartControl: --- Selecting new region: 2
09-08 14:32:18.446  7455  7455 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,09-08 14:32:18.451  7455  7455 D UEI.SmartControl: Platform has CIR...
09-08 14:32:18.452  7455  7455 D UEI.SmartControl: NO CIR support, need to check package...
09-08 14:32:18.453  7455  7455 I UEI.SmartControl: Model: LG-D722 uses JNI
09-08 14:32:18.456  7455  7455 D UEI.SmartControl: QS Service created
09-08 14:32:18.479  7455  7455 E UEI.SmartControl: QS start get config
,09-08 14:32:18.480  7480  7480 I MusicStore: Database version: 120
09-08 14:32:18.526  7455  7455 D UEI.SmartControl: Loading JNI Libs...
09-08 14:32:18.528  7455  7455 D UEI.SmartControl:  configuring local db...
,09-08 14:32:18.533   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:18.533   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-08 14:32:18.533   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:18.533  7480  7480 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-08 14:32:18.646   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:18.646   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-08 14:32:18.646   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 14:32:18.647  7480  7480 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-08 14:32:18.649   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:18.649   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
09-08 14:32:18.649   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:18.650  7480  7480 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
09-08 14:32:18.660  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:18.660  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:18.660  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:18.660  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22911a26 not in the list
09-08 14:32:18.660  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:18.660  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:32:18.660  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:32:18.660  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 14:32:18.663  5737  5825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:32:18.676  5434  7166 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,09-08 14:32:18.709   971  1640 I ActivityManager: Process com.lge.email (pid 7057) has died
,09-08 14:32:18.712  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:18.713  5434  7166 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
09-08 14:32:18.713  5737  5825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:32:18.713  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d23e667 not in the list
09-08 14:32:18.713  5737  5737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:32:18.713  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:18.713  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:18.713  5737  5737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:32:18.713  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:18.713  5737  5737 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:32:18.714  5737  5825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:18.714  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:18.715  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:18.715  5737  5825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22911a26 not in the list
09-08 14:32:18.715  5737  5825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:18.715  5737  5825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d23e667 not in the list
09-08 14:32:18.715  5737  5825 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:18.715  5737  5825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:18.715  5737  5825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:18.716  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 14:32:18.717  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 14:32:18.717  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 14:32:18.717  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:32:18.717  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 14:32:18.717  5737  5825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discove,ry: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 14:32:18.736  5737  7504 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
,09-08 14:32:18.748  7480  7480 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-08 14:32:18.749  7480  7480 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 14:32:18.766  7455  7455 D UEI.SmartControl:  ---- Has DB8: true
,09-08 14:32:18.775  7455  7455 D UEI.SmartControl: QS start statue = true Error code = 0
09-08 14:32:18.775  7455  7455 D UEI.SmartControl: QS version = v2.7.11.1_RC1
09-08 14:32:18.776  7455  7455 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
09-08 14:32:18.780  7455  7455 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,09-08 14:32:18.791  7455  7455 W irrc_jni: IRRCPlayer_nativeInit ++ 
09-08 14:32:18.791  7455  7455 D irrcClient: IrrcClient ++ 
09-08 14:32:18.791  7455  7455 D irrcClient: getIrrcService ++ 
09-08 14:32:18.791  7455  7455 D irrcClient: getIrrcService -- 
09-08 14:32:18.791  7455  7455 D irrcClient: IrrcClient -- 
09-08 14:32:18.791  7455  7455 W irrc_jni: IRRCPlayer_nativeInit -- 
09-08 14:32:18.799  7455  7455 D UEI.SmartControl: Services init done
,09-08 14:32:18.802  7455  7506 I UEI.SmartControl: Device manager: loading config....
09-08 14:32:18.806  7455  7455 D UEI.SmartControl: QS Service init finished
09-08 14:32:18.809  7455  7455 D UEI.SmartControl: QS Service version name: 0.1.73
09-08 14:32:18.810  7455  7506 D UEI.SmartControl: Config is loaded...
09-08 14:32:18.810  7455  7455 D UEI.SmartControl: QS Service version code: 1073
09-08 14:32:18.813  7455  7455 D UEI.SmartControl: Service requested: Control
,09-08 14:32:18.815  7455  7455 D UEI.SmartControl: Internal service binding...
09-08 14:32:18.816  7455  7470 D UEI.SmartControl: -----IControl: 11
09-08 14:32:18.818  7455  7470 D UEI.SmartControl: Caller: com.lge.qremote
09-08 14:32:18.819  7455  7470 D UEI.SmartControl: ------------ IControl registerCallback...
09-08 14:32:18.820  7455  7470 I UEI.SmartControl: Registering callback...
09-08 14:32:18.821  7455  7470 D UEI.SmartControl: -----IControl: 19
09-08 14:32:18.822  7455  7470 D UEI.SmartControl: Caller: com.lge.qremote
09-08 14:32:18.823  7455  7470 I UEI.SmartControl: Registering Services Ready callback...
09-08 14:32:18.823  7455  7470 I UEI.SmartControl: Notify client services are ready...
09-08 14:32:18.825  7455  7471 D UEI.SmartControl: -----IControl: 8
09-08 14:32:18.826  7455  7471 D UEI.SmartControl: Caller: com.lge.qremote
,09-08 14:32:18.839  7480  7480 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-08 14:32:18.859  7455  7505 D UEI.SmartControl:  ----- QS SDK is ready!!!
09-08 14:32:18.860  7455  7505 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-08 14:32:18.909  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-08 14:32:18.910  1737  1737 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-08 14:32:18.916  7480  7480 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-08 14:32:18.917  7480  7480 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@243f7074: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-08 14:32:18.917  7480  7480 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-08 14:32:18.918  7480  7480 D AndroidMusic: GMSCore installation verified
09-08 14:32:18.923  7480  7480 I ConfigStore: Config Database version: 1
,09-08 14:32:18.955  5434  7166 I CheckinUtil: Classify the device as Phone.
,09-08 14:32:19.008  7480  7480 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-08 14:32:19.013  7480  7480 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
09-08 14:32:19.020  7480  7480 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-08 14:32:19.031  7480  7494 I art     : CheckpointMarkThreadRoots callback created = 0xb042d400
09-08 14:32:19.059   971  1974 I ActivityManager: Killing 7086:com.lge.appbox.client/u0a11 (adj 15): empty #11
09-08 14:32:19.059  7480  7494 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3e0
,09-08 14:32:19.068  1737  1755 I art     : Explicit concurrent mark sweep GC freed 60093(3MB) AllocSpace objects, 37(613KB) LOS objects, 40% free, 15MB/25MB, paused 1.623ms total 105.278ms
09-08 14:32:19.099   971  2043 W libprocessgroup: failed to open /acct/uid_10011/pid_7086/cgroup.procs: No such file or directory
,09-08 14:32:19.107  7480  7480 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-08 14:32:19.149   971  6413 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7519 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-08 14:32:19.163  5434  7166 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
09-08 14:32:19.171  5434  7166 I CheckinChimeraService: Checking schedule, now: 1473337939171 next: 1473865188163
09-08 14:32:19.171  5434  7166 I CheckinChimeraService: active receiver: disabled
09-08 14:32:19.172  7480  7480 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
09-08 14:32:19.176  7480  7480 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 14:32:19.214  5737  5737 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:32:19.240  5434  7538 I CheckinChimeraService: Checking schedule, now: 1473337939240 next: 1473865188163
,09-08 14:32:19.240  5434  7538 I CheckinChimeraService: active receiver: disabled
,09-08 14:32:19.250  7519  7519 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:19.250  7519  7519 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-08 14:32:19.251  7519  7519 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-08 14:32:19.252   971   988 I ActivityManager: Killing 7138:com.lge.drmservice/u0a51 (adj 15): empty #11
09-08 14:32:19.260  5434  5434 D CheckinChimeraService: Recording last checkin time for package unspecified as 1473337939260
,09-08 14:32:19.345   971  2043 W libprocessgroup: failed to open /acct/uid_10051/pid_7138/cgroup.procs: No such file or directory
,09-08 14:32:19.350  7480  7499 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
09-08 14:32:19.351  7519  7519 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-08 14:32:19.357   971  1932 I ActivityManager: Killing 7205:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
09-08 14:32:19.366  7519  7519 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,09-08 14:32:19.464   971  1932 I ActivityManager: Killing 6927:com.lge.lgdmsclient/1000 (adj 15): empty #12
,09-08 14:32:19.527   971  1919 W libprocessgroup: failed to open /acct/uid_10079/pid_7205/cgroup.procs: No such file or directory
,09-08 14:32:19.530   971  1640 W libprocessgroup: failed to open /acct/uid_1000/pid_6927/cgroup.procs: No such file or directory
,09-08 14:32:19.637  7519  7519 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-08 14:32:19.696   971  1869 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7546 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,09-08 14:32:19.718  7519  7519 I HubEmail: JNI_OnLoad()
09-08 14:32:19.718  7519  7519 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:32:19.718  7519  7519 I HubEmail: registerNatives()
09-08 14:32:19.718  7519  7519 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,09-08 14:32:19.718  7519  7519 I HubEmail: registerNativeMethods()
09-08 14:32:19.718  7519  7519 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-08 14:32:19.718  7519  7519 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-08 14:32:19.726   971  1951 I ActivityManager: Killing 7269:com.android.chrome/u0a48 (adj 15): empty #11
,09-08 14:32:19.753   971  1869 W libprocessgroup: failed to open /acct/uid_10048/pid_7269/cgroup.procs: No such file or directory
09-08 14:32:19.755  7519  7562 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:19.799  7546  7546 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:19.800  7546  7546 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-08 14:32:19.802  7546  7546 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:32:19.805  7546  7546 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
09-08 14:32:19.812  7546  7565 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:19.813  7546  7565 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-08 14:32:19.822  7546  7564 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-08 14:32:19.826  7546  7564 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-08 14:32:19.845   971  1932 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7570 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-08 14:32:19.851  7546  7564 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
09-08 14:32:19.934  7546  7546 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,09-08 14:32:19.935  7546  7546 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
09-08 14:32:19.935  7546  7546 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-08 14:32:19.938  7546  7546 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-08 14:32:19.944  7546  7546 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
09-08 14:32:19.946   971  1640 I ActivityManager: Killing 7288:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,09-08 14:32:20.001   971  1932 W libprocessgroup: failed to open /acct/uid_10086/pid_7288/cgroup.procs: No such file or directory
09-08 14:32:20.027  7570  7570 I AppUp4:AppBoxCP: onCreate
09-08 14:32:20.028  7570  7570 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-08 14:32:20.038  7570  7570 I AppUp4:DB:  setFingerPrint start
09-08 14:32:20.038  7570  7570 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
09-08 14:32:20.045  7570  7570 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
09-08 14:32:20.045  7570  7570 I AppUp4:DB:  SDK version = 21
09-08 14:32:20.045  7570  7570 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-08 14:32:20.046  7570  7570 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-08 14:32:20.048  7570  7570 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-08 14:32:20.048  7570  7570 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:20.049  7570  7570 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-08 14:32:20.049  7570  7570 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-08 14:32:20.054  7570  7570 I AppUp4:CustModeStarterReceiver: onReceive
09-08 14:32:20.054  7570  7570 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:20.057  7570  7570 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bf9db31
,09-08 14:32:20.057  7570  7570 D AppUp4:CustFacade: isCustomizationCompleted : false
09-08 14:32:20.063  7570  7570 D AppUp4:CustFacade: isSimDevice : true
09-08 14:32:20.064  7570  7570 D AppUp4:CustModeStarterReceiver: begin check event
09-08 14:32:20.065  7570  7570 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-08 14:32:20.065  7570  7570 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-08 14:32:20.066  7570  7587 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-08 14:32:20.066  7570  7587 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-08 14:32:20.066  7570  7587 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-08 14:32:20.068   971  1869 I ActivityManager: Killing 7381:com.google.android.talk/u0a61 (adj 15): empty #11
09-08 14:32:20.097   971  1324 W libprocessgroup: failed to open /acct/uid_10061/pid_7381/cgroup.procs: No such file or directory
,09-08 14:32:20.100  3073  3073 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-08 14:32:20.101  3073  3073 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:20.101  3073  3073 I LgeMiscReceiver: networkInfo.isConnected() = true
09-08 14:32:20.103  3073  3073 D PhoneState: setPdpRejectCasuse : false
09-08 14:32:20.105  7111  7111 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-08 14:32:20.105  7111  7111 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-08 14:32:20.108  2616  2616 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-08 14:32:20.110  2616  2616 V DownloadManager: DownloadService onCreate
,09-08 14:32:20.112  2616  7589 I DownloadManager: in removeSpuriousFiles
,09-08 14:32:20.114  2616  7589 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-08 14:32:20.114  2616  2616 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
09-08 14:32:20.116  2616  7589 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@10c23eb2 on behalf of 2616
09-08 14:32:20.119  2616  7589 I DownloadManager: in trimDatabase
09-08 14:32:20.119  2616  7589 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-08 14:32:20.120  2616  7589 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1de2e180 on behalf of 2616
09-08 14:32:20.166   971  1383 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7592 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-08 14:32:20.168  2616  2616 V DownloadManager: DownloadService onStartCommand
,09-08 14:32:20.171  2616  7590 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-08 14:32:20.173  2616  7590 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@49193fe on behalf of 2616
,09-08 14:32:20.423   971  6413 I art     : Explicit concurrent mark sweep GC freed 19821(933KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.260ms total 200.636ms
,09-08 14:32:20.429  2616  2616 V DownloadManager: DownloadService onDestroy
09-08 14:32:20.467   971  6413 I ActivityManager: Killing 7433:com.lge.qremote/u0a106 (adj 15): empty #11
,09-08 14:32:20.565   971  2043 W libprocessgroup: failed to open /acct/uid_10106/pid_7433/cgroup.procs: No such file or directory
,09-08 14:32:20.571  2820  2820 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:20
09-08 14:32:20.574  2820  2820 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-08 14:32:20.574  2820  2820 D WeatherAncestor: connectivity changed - connection : true
09-08 14:32:20.574  2820  2820 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-08 14:32:20.574  2820  2820 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:20
09-08 14:32:20.590  2820  2820 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:20.595  2820  2820 D WeatherService: 2 : shouldTimeTickRegistered : false
09-08 14:32:20.656   971  1869 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7616 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-08 14:32:20.721   314   314 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 799us total 57.894ms
,09-08 14:32:20.739  5737  5825 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 867
09-08 14:32:20.739  5737  5825 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 867, name: My test thread name)
,09-08 14:32:20.771   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 402us total 44.955ms
,09-08 14:32:20.781  5737  7504 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 187 and the total number of bytes written 187
09-08 14:32:20.784  1914  1914 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
09-08 14:32:20.795  1373  1373 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-08 14:32:20.804   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 422us total 31.163ms
09-08 14:32:20.807  5737  7638 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: My test thread name)
09-08 14:32:20.807  5737  7638 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 868, thread name: My test thread name)
09-08 14:32:20.807  5737  7638 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 868, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-08 14:32:20.811  5737  5825 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:32:20.821  1373  1373 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-08 14:32:20.831   971  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 14:32:20.851  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
09-08 14:32:20.851  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
09-08 14:32:20.851  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-08 14:32:20.851  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
09-08 14:32:20.851  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-08 14:32:20.851  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
09-08 14:32:20.852  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-08 14:32:20.852  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
09-08 14:32:20.852  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-08 14:32:20.852  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
09-08 14:32:20.852  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
09-08 14:32:20.852  1373  1373 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
09-08 14:32:20.852  1373  1373 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-08 14:32:20.858  7616  7616 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 14:32:20.861  5737  7651 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 872, name: My test thread name)
09-08 14:32:20.873  1953  1953 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-08 14:32:20.876  5737  7651 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 872, thread name: My test thread name): Test exception.
09-08 14:32:20.876  5737  7651 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 872, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-08 14:32:20.892  1953  1953 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-08 14:32:20.898  5737  5825 E com.test.thalitest.ThaliTestRunner: testIsBluetoothEnabled(io.jxcore.node.ConnectivityMonitorTest)
09-08 14:32:20.898  5737  5825 E com.test.thalitest.ThaliTestRunner: Returns proper state of BT when switched on
09-08 14:32:20.898  5737  5825 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-08 14:32:20.898  5737  5825 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-08 14:32:20.900  1953  1953 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: Returns proper state of BT when switched on
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testIsBluetoothEnabled(ConnectivityMonitorTest.java:268)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-08 14:32:20,.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:57)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: testExecuteStopOperation(io.jxcore.node.StartStopOperationHandlerTest)
09-08 14:32:20.910  5737  5825 E com.test.thalitest.T,haliTestRunner: mDiscoveryManager1 state should be NOT_STARTED
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner: Expected: is <NOT_STARTED>
09-08 14:32:20.910  5737  5825 E com.test.thalitest.ThaliTestRunner:      but: was <WAITING_FOR_SERVICES_TO_BE_ENABLED>
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: mDiscoveryManager1 state should be NOT_STARTED
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: Expected: is <NOT_STARTED>
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner:      but: was <WAITING_FOR_SERVICES_TO_BE_ENABLED>
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandlerTest.testExecuteStopOperation(StartStopOperationHandlerTest.java:234)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:57)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-08 14:32:20.922  5737  5825 E com.test.thalitest.ThaliTestRunner: testCheckCurrentOperationStatus(io.jxcore.node.StartStopOperationHandlerTest)
09-08 14:32:20.934  1953  1953 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-08 14:32:20.940  5737  5825 I jxcore-log: Failed to execute UT.
09-08 14:32:20.940  5737  5825 I jxcore-log: 
09-08 14:32:20.941  5737  5825 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-08 14:32:20.941  5737  5825 I jxcore-log: 
--------- beginning of crash
09-08 14:32:20.945  5737  5825 E AndroidRuntime: FATAL EXCEPTION: Thread-664
09-08 14:32:20.945  5737  5825 E AndroidRuntime: Process: com.test.thalitest, PID: 5737
09-08 14:32:20.945  5737  5825 E AndroidRuntime: java.lang.NullPointerException: println needs a message
09-08 14:32:20.945  5737  5825 E AndroidRuntime: 	at android.util.Log.println_native(Native Method)
09-08 14:32:20.945  5737  5825 E AndroidRuntime: 	at android.util.Log.e(Log.java:232)
09-08 14:32:20.945  5737  5825 E AndroidRuntime: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:61)
09-08 14:32:20.945  5737  5825 E AndroidRuntime: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-08 14:32:20.945  5737  5825 E AndroidRuntime: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-08 14:32:20.945  5737  5825 E AndroidRuntime: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-08 14:32:20.945  5737  5825 E AndroidRuntime: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-08 14:32:20.945  5737  5825 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:32:20.945  5737  5825 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:32:20.945  5737  5825 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:32:20.945  5737  5825 E AndroidRuntime: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,09-08 14:32:20.994   971   990 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,09-08 14:32:20.999   971   990 D InputDispatcher: Focus left window: Window{1336113f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-08 14:32:21.004   971   990 I ActivityManager: Killing 7455:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
09-08 14:32:21.006   293   349 I ThermalEngine: Sensor:pa_therm0:35000 mC
09-08 14:32:21.034   971   971 D administrator: Handling package changes for user 0
,09-08 14:32:21.263   971  6413 W libprocessgroup: failed to open /acct/uid_10089/pid_7455/cgroup.procs: No such file or directory
,09-08 14:32:21.285  5737  5737 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 14:32:21.285  5737  5737 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
09-08 14:32:21.285  5737  5737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:21.285  5737  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:21.285  5737  5737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:21.285  5737  5737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:21.285  5737  5737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b1ab24d removed from the list
09-08 14:32:21.285  5737  5737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:21.285  5737  5737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b6dc450 removed from the list
09-08 14:32:21.285  5737  5737 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:21.285  5737  5737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,09-08 14:32:21.299  7616  7630 I art     : CheckpointMarkThreadRoots callback created = 0xb042d380
,09-08 14:32:21.307  1758  1758 D DSDPConnection: Display #0 changed.
,09-08 14:32:21.334  5737  5825 I Process : Sending signal. PID: 5737 SIG: 9
09-08 14:32:21.338  7616  7630 I art     : CheckpointMarkThreadRoots callback created = 0xb042d360
,09-08 14:32:21.345  1953  1953 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
09-08 14:32:21.372  1953  1953 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,09-08 14:32:21.381  1953  1953 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
09-08 14:32:21.389  1953  2058 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-08 14:32:21.390   971  1951 I WindowState: WIN DEATH: Window{1336113f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-08 14:32:21.396   971  1951 D InputDispatcher: Window went away: Window{1336113f u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 14:32:21.401  7616  7663 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-08 14:32:21.401  7616  7663 I Babel_SMS: MmsConfig.loadMmsSettings
,09-08 14:32:21.514   971  1045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:32:21.533   971   971 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-08 14:32:21.534   971   971 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-08 14:32:21.534   971   971 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-08 14:32:21.574  7654  7654 D AndroidRuntime: 
09-08 14:32:21.574  7654  7654 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-08 14:32:21.593  7654  7654 D AndroidRuntime: CheckJNI is OFF
,09-08 14:32:21.629   971  1959 I ActivityManager: Process com.test.thalitest (pid 5737) has died
,09-08 14:32:21.655  1953  1953 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-08 14:32:21.656  1953  1953 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
09-08 14:32:21.657  1953  1953 I Activity: Activity.onPostResume() called 
09-08 14:32:21.661   971   971 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,09-08 14:32:21.680  7616  7663 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
09-08 14:32:21.681  7616  7663 I Babel_SMS: MmsConfig.loadFromDatabase
,09-08 14:32:21.684  1953  1953 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,09-08 14:32:21.701   971   971 V ActivityManager: Display changed displayId=0
09-08 14:32:21.701  7616  7663 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-08 14:32:21.701  7616  7663 I Babel_SMS: MmsConfig.loadFromResources
09-08 14:32:21.702  1953  7666 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
09-08 14:32:21.705  7616  7663 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-08 14:32:21.705   971   971 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
09-08 14:32:21.706   971   971 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2c61a0c0
09-08 14:32:21.706  7616  7663 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
09-08 14:32:21.721  7616  7616 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
09-08 14:32:21.723  7616  7616 D SensorManager: found sensor: Motion Accel, handle=46
,09-08 14:32:21.739   971  1054 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
,09-08 14:32:21.743   971  1932 D InputDispatcher: Focus entered window: Window{3582038e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-08 14:32:21.755   971  1054 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,09-08 14:32:21.759  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
09-08 14:32:21.759  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
09-08 14:32:21.759  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
09-08 14:32:21.759  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-08 14:32:21.761   971  1054 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-08 14:32:21.761   971  1054 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-08 14:32:21.761   971  1054 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-08 14:32:21.763   971  1054 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ac048f0,  pkg=WindowManager.LayoutParams
09-08 14:32:21.763   971  1054 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-08 14:32:21.771  1953  1953 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,09-08 14:32:21.779  7616  7616 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:32:21.782  7616  7616 I Babel_Crash: startup - clean
09-08 14:32:21.788  1953  1953 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,09-08 14:32:21.791  1953  1953 I PhoneWindow: [setNavigationBarColor] color=0x 0
09-08 14:32:21.809   971  1900 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,09-08 14:32:21.816   971  1900 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5737 uid 10030
09-08 14:32:21.833  7616  7668 I Babel   : deleted: false for 0
,09-08 14:32:21.886  1953  1953 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
,09-08 14:32:21.904  1953  1953 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-08 14:32:21.927   971  1869 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7680 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:32:21.930   971  1045 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-08 14:32:21.944  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,09-08 14:32:21.946  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-08 14:32:21.947  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-08 14:32:21.952  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-08 14:32:21.953   971  1056 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{fa49164 u0 com.lge.launcher2/.Launcher t258} time:169064
09-08 14:32:21.963  7616  7616 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,09-08 14:32:21.972  7616  7616 W AudioCapabilities: Unsupported mime audio/adpcm
09-08 14:32:21.974  7616  7616 W AudioCapabilities: Unsupported mime audio/g726
09-08 14:32:21.975  7616  7616 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-08 14:32:21.976  7616  7616 W AudioCapabilities: Unsupported mime audio/wma-voice
09-08 14:32:21.977  7616  7616 W VideoCapabilities: Unsupported mime video/mjpg
,09-08 14:32:21.982  7616  7616 W VideoCapabilities: Unsupported mime video/theora
09-08 14:32:21.999  1953  1953 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-08 14:32:22.011  7616  7616 W AudioCapabilities: Unsupported mime audio/evrc
09-08 14:32:22.012  7616  7616 W AudioCapabilities: Unsupported mime audio/qcelp
,09-08 14:32:22.015  7616  7616 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:22.022  7616  7616 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-08 14:32:22.023  7616  7616 W AudioCapabilities: Unsupported mime audio/qcelp
09-08 14:32:22.024  7616  7616 W AudioCapabilities: Unsupported mime audio/evrc
09-08 14:32:22.037  7616  7616 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-08 14:32:22.037  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-08 14:32:22.038  1953  1953 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
09-08 14:32:22.039  1953  1953 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-08 14:32:22.056  7654  7654 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-08 14:32:22.080  7616  7616 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 14:32:22.081  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
09-08 14:32:22.085  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
09-08 14:32:22.086  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
09-08 14:32:22.087  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
09-08 14:32:22.088  7616  7616 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:22.090  7616  7616 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:22.092  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
09-08 14:32:22.094  7616  7616 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:32:22.103  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
09-08 14:32:22.104  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
09-08 14:32:22.105   971  1046 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
09-08 14:32:22.108  7616  7616 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 14:32:22.108  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
09-08 14:32:22.109  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
09-08 14:32:22.109  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
09-08 14:32:22.120  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,09-08 14:32:22.126  7616  7616 I vclib   : onServiceConnected
09-08 14:32:22.127  7616  7616 W Babel   : Attempted to change video mute state without an active call.
09-08 14:32:22.131  1953  1953 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,09-08 14:32:22.290   971  1061 W PackageSettings: Skipping PackageSetting{2fa5e00 com.example.hello/10317} due to missing metadata
,09-08 14:32:22.324  7616  7616 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
09-08 14:32:22.330  7616  7700 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:22.330  7616  7700 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-08 14:32:22.330  7616  7700 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-08 14:32:22.331  7616  7700 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,09-08 14:32:22.337   274  1039 E BandwidthController: [LG DATA] No such appUid: 10061
09-08 14:32:22.337   274  1039 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
09-08 14:32:22.338   274  7703 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=102; mark=917606
09-08 14:32:22.338   274  7703 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-08 14:32:22.338   274  7703 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=102
09-08 14:32:22.338   274  7703 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-08 14:32:22.339  1737  1737 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
09-08 14:32:22.339   274  7703 D libc-netbsd: res_queryN name = xxxxx succeed
09-08 14:32:22.339  7616  7700 I System.out: propertyValue:false
09-08 14:32:22.344   971  1061 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,09-08 14:32:22.408  7616  7700 I Babel   : connection state changed from UNKNOWN to CONNECTED
,09-08 14:32:22.422  2036  2036 I art     : Explicit concurrent mark sweep GC freed 3580(291KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/20MB, paused 1.838ms total 75.356ms
,09-08 14:32:22.424  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-08 14:32:22.426  3411  3411 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-08 14:32:22.426  3411  3411 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-08 14:32:22.426  3411  3411 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-08 14:32:22.426  3411  3411 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
09-08 14:32:22.426  3411  3411 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:32:22.426  3411  3411 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:32:22.426  3411  3411 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-08 14:32:22.426  3411  3411 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-08 14:32:22.426  3411  3411 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:32:22.426  3411  3411 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:32:22.426  3411  3411 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-08 14:32:22.426  3411  3411 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-08 14:32:22.430   971  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-08 14:32:22.434  1914  1914 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,09-08 14:32:22.441   971   971 D administrator: Handling package changes for user 0
,09-08 14:32:22.456  1373  1373 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-08 14:32:22.477  1953  1953 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,09-08 14:32:22.488  1737  2465 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 14:32:22.502  5434  5434 I art     : Explicit concurrent mark sweep GC freed 9899(659KB) AllocSpace objects, 6(99KB) LOS objects, 25% free, 15MB/20MB, paused 1.184ms total 134.507ms
,09-08 14:32:22.503   971   971 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-08 14:32:22.503   971   971 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-08 14:32:22.506   971   971 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-08 14:32:22.515   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:22.515   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 14:32:22.515   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 14:32:22.523  1373  1373 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-08 14:32:22.524  7680  7710 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 14:32:22.525   971  1352 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
09-08 14:32:22.526  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-08 14:32:22.553   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:22.553   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 14:32:22.553   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:22.555  7680  7710 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-08 14:32:22.560  7680  7680 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 14:32:22.560  7680  7680 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 14:32:22.560  7680  7680 I GAv4    :   adb logcat -s GAv4
09-08 14:32:22.574   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:22.574   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-08 14:32:22.574   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:22.575  7680  7711 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-08 14:32:22.577  1953  1953 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-08 14:32:22.577  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
09-08 14:32:22.578  1953  1953 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
09-08 14:32:22.578  1953  1953 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-08 14:32:22.581   245   371 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-08 14:32:22.581   245   371 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-08 14:32:22.581   245   371 W Vold    : Returning OperationFailed - no handler for errno 0
09-08 14:32:22.583  7680  7711 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-08 14:32:22.591  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-08 14:32:22.592  1953  1953 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
09-08 14:32:22.592  1953  1953 I Choreographer: Skipped 41 frames!  The application may be doing too much work on its main thread.
09-08 14:32:22.593  1953  1953 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-08 14:32:22.597   971  1974 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7713 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
09-08 14:32:22.605  1636  1636 E b       : Unable to connect to the editor to retrieve text... will retry later
,09-08 14:32:22.610  1953  2110 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-08 14:32:22.610  1953  2110 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-08 14:32:22.621  1953  1953 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-08 14:32:22.621  1953  1953 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-08 14:32:22.621  1953  1953 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,09-08 14:32:22.624  1953  1953 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-08 14:32:22.626  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-08 14:32:22.629  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
09-08 14:32:22.630  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-08 14:32:22.632  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
,09-08 14:32:22.634  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
09-08 14:32:22.637  7680  7680 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-08 14:32:22.643  1953  1953 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-08 14:32:22.644  1953  1953 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,09-08 14:32:22.688  7680  7680 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-08 14:32:22.713  7680  7731 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:32:22.724  7713  7713 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
09-08 14:32:22.726  1953  1953 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,09-08 14:32:22.752  1953  1953 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,09-08 14:32:22.752  1953  1953 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-08 14:32:22.755  1953  1953 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
09-08 14:32:22.772  1373  1513 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-08 14:32:22.773  1373  1513 D KeyguardModel: createShortcutInfo...
,09-08 14:32:22.775  1373  1513 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-08 14:32:22.775  1373  1513 D KeyguardModel: createShortcutInfo...
09-08 14:32:22.782  1373  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:32:22.784  1373  1513 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-08 14:32:22.790  1373  1513 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-08 14:32:22.790  1373  1513 D KeyguardModel: createShortcutInfo...
09-08 14:32:22.791  1953  1953 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@243f7074 time:169902
,09-08 14:32:22.794  1373  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:32:22.795  1373  1513 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-08 14:32:22.797  1373  1513 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-08 14:32:22.797  1373  1513 D KeyguardModel: createShortcutInfo...
09-08 14:32:22.799  1373  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:32:22.799  1373  1513 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-08 14:32:22.801  1373  1513 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-08 14:32:22.801  1373  1513 D KeyguardModel: createShortcutInfo...
09-08 14:32:22.809   971  1951 I ActivityManager: Killing 7480:com.google.android.music:main/u0a81 (adj 15): empty #11
,09-08 14:32:22.815   971  1061 I art     : Explicit concurrent mark sweep GC freed 32064(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 4.348ms total 414.019ms
09-08 14:32:22.871  1953  1953 I art     : Explicit concurrent mark sweep GC freed 29793(1625KB) AllocSpace objects, 18(2MB) LOS objects, 39% free, 15MB/25MB, paused 1.368ms total 76.095ms
,09-08 14:32:22.889  1953  1953 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,09-08 14:32:22.909  7654  7654 D AndroidRuntime: Shutting down VM
,09-08 14:32:22.919  1373  1373 D KeyguardModel: handleShortcutListChanged...
09-08 14:32:22.924   971  1869 W libprocessgroup: failed to open /acct/uid_10081/pid_7480/cgroup.procs: No such file or directory
,09-08 14:32:22.931  1373  1513 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-08 14:32:22.931  1373  1513 D KeyguardModel: createShortcutInfo...
09-08 14:32:22.934  1373  1513 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-08 14:32:22.934  1373  1513 D KeyguardModel: createShortcutInfo...
09-08 14:32:22.935  1373  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-08 14:32:22.935  1373  1513 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-08 14:32:22.938  1373  1513 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-08 14:32:22.938  1373  1513 D KeyguardModel: createShortcutInfo...
09-08 14:32:22.940  1373  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:32:22.940  1373  1513 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-08 14:32:22.944  1373  1513 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,09-08 14:32:22.945  1373  1513 D KeyguardModel: createShortcutInfo...
09-08 14:32:22.947  1373  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:32:22.947  1373  1513 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-08 14:32:22.949  1373  1513 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-08 14:32:22.949  1373  1513 D KeyguardModel: createShortcutInfo...
09-08 14:32:22.954  1373  1373 D KeyguardModel: handleShortcutListChanged...
,09-08 14:32:22.976  1839  1839 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-08 14:32:22.976  1839  1839 D LCardEmulationManager: getDefaultRoute
,09-08 14:32:23.023   971  1045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:32:23.065   971  1045 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-08 14:32:23.067  1953  1953 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-08 14:32:23.077   971  1045 D LocationProviderProxy: applying state to connected service
09-08 14:32:23.138  7680  7680 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,09-08 14:32:23.179   971  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7746 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-08 14:32:23.337  5434  6592 I CheckinService: Done disabling old GoogleServicesFramework version
,09-08 14:32:23.354  7680  7680 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 463-465)
,09-08 14:32:23.354  7680  7680 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 14:32:23.363  7680  7680 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {386ef20a}
09-08 14:32:23.364  7680  7680 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:32:23.365  7680  7680 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 14:32:23.378  7680  7680 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 14:32:23.379  7680  7680 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 14:32:23.380  7680  7680 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 14:32:23.400  1953  2177 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-08 14:32:23.400  1953  2177 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..

```
