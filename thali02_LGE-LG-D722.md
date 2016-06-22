#### Test 721454317367600_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
06-22 07:44:02.052  2094  2094 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19961
,06-22 07:44:02.840   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
06-22 07:44:02.872  5824  5824 D AndroidRuntime: 
06-22 07:44:02.872  5824  5824 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-22 07:44:02.883  5824  5824 D AndroidRuntime: CheckJNI is OFF
06-22 07:44:03.141  5824  5824 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-22 07:44:03.176   842  1383 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-22 07:44:03.267   842  1383 D ActivityManager: setTaskToReturnTo : TaskRecord{36f4245 #238 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-22 07:44:03.267   842  1383 D ActivityManager: setTaskToReturnTo : TaskRecord{36f4245 #238 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-22 07:44:03.300   842  1383 D WindowStateEx: AppWindowTokenEx init.. 
06-22 07:44:03.334   842  1383 D InputDispatcher: Focus left window: Window{3c47e311 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
06-22 07:44:03.334  5824  5824 D AndroidRuntime: Shutting down VM
06-22 07:44:03.337   842  1027 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
06-22 07:44:03.342  1945  1945 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
06-22 07:44:03.367   842  1027 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-22 07:44:03.382   842  1027 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
06-22 07:44:03.383   842  1027 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
06-22 07:44:03.393   842  1027 D SplitWindow: check instance of lgWin Window{29c074fd u0 Starting com.test.thalitest}
06-22 07:44:03.417   842  1896 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5844 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-22 07:44:03.448  1945  1945 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
06-22 07:44:03.499  1945  1945 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
06-22 07:44:03.519  2026  2026 I HotwordDetector: Closing mic
06-22 07:44:03.526   842  1932 I WindowStateAnimator: Starting window displayed
06-22 07:44:03.531  2026  2504 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@28c1c333
06-22 07:44:03.531  2026  2504 V AudioRecord: stop()
06-22 07:44:03.531  2026  2504 D AudioRecord: AudioRecord->stop()
06-22 07:44:03.532   284   284 V AudioFlinger: RecordHandle::stop()
06-22 07:44:03.532   284   284 V AudioFlinger: RecordThread::stop
06-22 07:44:03.536   842  1025 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
06-22 07:44:03.540   842  1025 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
06-22 07:44:03.543   842  1025 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
,06-22 07:44:03.543   842  1025 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
06-22 07:44:03.543   842  1025 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-22 07:44:03.548   842  1025 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2daee37,  pkg=WindowManager.LayoutParams
06-22 07:44:03.548   842  1025 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
06-22 07:44:03.549  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
06-22 07:44:03.550  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
06-22 07:44:03.550  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
06-22 07:44:03.550  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
06-22 07:44:03.550   284   284 V AudioFlinger: Record stopped OK
06-22 07:44:03.552   284   284 V AudioPolicyManager: stopInput() input 17
06-22 07:44:03.553   284   284 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
06-22 07:44:03.553   284   284 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
06-22 07:44:03.553   284  1060 V AudioPolicyService: AudioCommandThread() waking up
06-22 07:44:03.553   284  1060 V AudioPolicyService: AudioCommandThread() processing release audio patch
06-22 07:44:03.553   284  1060 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
06-22 07:44:03.554   284  1060 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
06-22 07:44:03.554   284  1060 V AudioFlinger: ThreadBase::setParameters() routing=0
06-22 07:44:03.554   284  1060 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
06-22 07:44:03.555   284  2516 V AudioFlinger: processConfigEvents_l() remaining events 1
06-22 07:44:03.555   284  2516 V AudioFlinger: processConfigEvents_l() DONE thread 0xb39dc000
06-22 07:44:03.558   284  2516 D audio_hw_primary: in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
06-22 07:44:03.603   284  2516 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
06-22 07:44:03.603   284  2516 V audio_hw_primary: disable_audio_route: enter: usecase(7)
06-22 07:44:03.603   284  2516 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
06-22 07:44:03.603   284  2516 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
06-22 07:44:03.606   284  2516 V audio_hw_primary: disable_audio_route: exit
06-22 07:44:03.606   284  2516 E audio_hw_primary: disable_snd_device: enter 144
06-22 07:44:03.606   284  2516 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
06-22 07:44:03.606   284  2516 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
06-22 07:44:03.610   284  2516 V audio_hw_primary: stop_input_stream: exit: status(0)
06-22 07:44:03.610   284  2516 V audio_hw_primary: in_standby: exit:  status(0)
06-22 07:44:03.610   284  2516 V AudioFlinger: RecordThread: loop stopping
06-22 07:44:03.610   284  1060 V AudioPolicyService: AudioCommandThread() going to sleep
06-22 07:44:03.611   284   284 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
06-22 07:44:03.611   284   284 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
06-22 07:44:03.611   284   284 V AudioPolicyService: AudioCommandThread() adding update audio patch list
06-22 07:44:03.611   284   284 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
06-22 07:44:03.611   284  1061 V AudioPolicyService: AudioCommandThread() waking up
06-22 07:44:03.611   284  1061 V AudioPolicyService: AudioCommandThread() processing update audio patch list
06-22 07:44:03.611   284  1061 V AudioPolicyService: AudioCommandThread() going to sleep
06-22 07:44:03.613   284   284 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
06-22 07:44:03.613   284   284 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
06-22 07:44:03.613   284  1060 V AudioPolicyService: AudioCommandThread() waking up
06-22 07:44:03.613   284  1060 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
06-22 07:44:03.613   284  1060 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 284
06-22 07:44:03.613   284  1060 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
06-22 07:44:03.613   284  1060 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
06-22 07:44:03.613   284  2516 V AudioFlinger: RecordThread: loop starting
06-22 07:44:03.613   284  2516 V AudioFlinger: processConfigEvents_l() remaining events 1
06-22 07:44:03.613   284  2516 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
06-22 07:44:03.613   284  2516 V audio_hw_primary: in_set_parameters: exit: status(0)
06-22 07:44:03.613   284  2516 V AudioFlinger: processConfigEvents_l() DONE thread 0xb39dc000
06-22 07:44:03.613   284  2516 V AudioFlinger: RecordThread: loop stopping
06-22 07:44:03.614   284  1060 V AudioPolicyService: AudioCommandThread() going to sleep
06-22 07:44:03.624  2026  2504 V AudioRecord: stop()
06-22 07:44:03.625  2026  2504 V AudioRecord: stop()
06-22 07:44:03.625  2026  2504 V AudioRecord: stop()
06-22 07:44:03.627   284  1604 V AudioFlinger: RecordHandle::stop()
06-22 07:44:03.627   284  1604 V AudioFlinger: RecordThread::stop
06-22 07:44:03.627   284  1604 V AudioPolicyManager: releaseInput() 17
06-22 07:44:03.627   284  1604 V AudioPolicyManager: closeInput(17)
06-22 07:44:03.627   284  1604 V AudioFlinger: closeInput() 17
06-22 07:44:03.627   284  1604 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-22 07:44:03.627   842  2033 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-22 07:44:03.627  1758  1780 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-22 07:44:03.627   284  1604 V AudioFlinger: ThreadBase::exit
06-22 07:44:03.627  2094  2113 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-22 07:44:03.627  2026  2248 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-22 07:44:03.627  3093  3108 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-22 07:44:03.627   284  2516 V AudioFlinger: RecordThread: loop starting
06-22 07:44:03.628   284  2516 V AudioFlinger: RecordThread 0xb39dc000 exiting
06-22 07:44:03.628  1374  1403 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-22 07:44:03.628   284  1604 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546e240)
06-22 07:44:03.628   284  1604 D audio_hw_primary: in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
06-22 07:44:03.628   284  1604 V audio_hw_primary: in_standby: exit:  status(0)
06-22 07:44:03.628   284  1604 V AudioPolicyService: AudioCommandThread() adding update audio port list
06-22 07:44:03.628   284  1604 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
06-22 07:44:03.628   284  1061 V AudioPolicyService: AudioCommandThread() waking up
06-22 07:44:03.628   284  1061 V AudioPolicyService: AudioCommandThread() processing update audio port list
06-22 07:44:03.628   284  1061 V AudioPolicyService: AudioCommandThread() going to sleep
06-22 07:44:03.629   284  1604 V AudioPolicyManager: releaseInput() exit
06-22 07:44:03.629   284  1604 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
06-22 07:44:03.629   284  1604 V AudioFlinger: removeClient_l() pid 2026, calling pid 284
06-22 07:44:03.630   284  1321 V AudioFlinger: releasing 16 from 2026 for -1
06-22 07:44:03.630   284  1321 V AudioFlinger:  decremented refcount to 0
06-22 07:44:03.630   284  1321 V AudioFlinger: purging stale effects
06-22 07:44:03.632  2026  2506 I HotwordRecognitionRnr: Stopping hotword detection.
06-22 07:44:03.641  5844  5844 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
06-22 07:44:03.644  2026  2508 I HotwordRecognitionRnr: Hotword detection finished
06-22 07:44:03.741  5844  5844 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
06-22 07:44:03.801  5844  5844 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9447-9449)
06-22 07:44:03.801  5844  5844 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:44:03.833  5844  5844 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3ad804b1}
06-22 07:44:03.836  5844  5844 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:44:03.845  5844  5844 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-22 07:44:03.868  5844  5844 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-22 07:44:03.870  5844  5844 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:44:03.874  5844  5844 E SysUtils: ApplicationContext is null in ApplicationStatus
06-22 07:44:03.935  5844  5879 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
06-22 07:44:03.967  5844  5844 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-22 07:44:03.981  5844  5844 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-22 07:44:03.981  5844  5844 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-22 07:44:03.983  5844  5844 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:03.983  5844  5844 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:03.983  5844  5844 I Adreno-EGL: Build Date: 03/02/15 Mon
06-22 07:44:03.983  5844  5844 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-22 07:44:03.983  5844  5844 I Adreno-EGL: Remote Branch: 
06-22 07:44:03.983  5844  5844 I Adreno-EGL: Local Patches: 
06-22 07:44:03.983  5844  5844 I Adreno-EGL: Reconstruct Branch: 
06-22 07:44:04.136   284   284 V AudioPolicyService: registerClient() client 0xb39b5a20, uid 10030
06-22 07:44:04.166   842  1026 D BluetoothManagerService: Message: 20
06-22 07:44:04.166   842  1026 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@294a7384:true
06-22 07:44:04.167  5844  5893 D BluetoothAdapter: 46562594: getState() :  mService = null. Returning STATE_OFF
06-22 07:44:04.312  5844  5844 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:44:04.324  5844  5844 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-22 07:44:04.329  5844  5844 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-22 07:44:04.334  5844  5844 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
06-22 07:44:04.334  5844  5844 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
06-22 07:44:04.347  5844  5844 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
06-22 07:44:04.355  5844  5844 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:44:04.355  5844  5844 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:44:04.408  5844  5844 I Activity: Activity.onPostResume() called 
06-22 07:44:04.418  5844  5904 D OpenGLRenderer: Render dirty regions requested: true
06-22 07:44:04.418  5844  5904 I OpenGLRenderer: Initialized EGL, version 1.4
06-22 07:44:04.424  5844  5904 D OpenGLRenderer: Enabling debug mode 0
06-22 07:44:04.455  5844  5844 D Atlas   : Validating map...
06-22 07:44:04.460   842  1893 D SplitWindow: check instance of lgWin Window{373c5b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-22 07:44:04.469  5844  5891 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
06-22 07:44:04.510   842  1893 D InputDispatcher: Focus entered window: Window{373c5b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-22 07:44:04.580   842  1820 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
06-22 07:44:04.595   842  1027 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s224ms
06-22 07:44:04.595   842  1027 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{22ee6d9a u0 com.test.thalitest/.MainActivity t238} time:120243
06-22 07:44:04.596  5844  5844 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@304d82a0 time:120244
06-22 07:44:04.722  5844  5844 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5844
,06-22 07:44:05.442  5844  5844 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-22 07:44:05.574  5844  5907 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1627225856
,06-22 07:44:05.582  5844  5907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-22 07:44:05.582  5844  5907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-22 07:44:05.582  5844  5907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-22 07:44:05.582  5844  5907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-22 07:44:05.582  5844  5907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-22 07:44:05.582  5844  5907 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2930b3cd added. We now have 1 listener(s)
06-22 07:44:05.595   842  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:05.598  5844  5907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
06-22 07:44:05.599  5844  5907 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
06-22 07:44:05.600  5844  5907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-22 07:44:05.600  5844  5907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-22 07:44:05.605  5844  5907 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1596d3d0 added. We now have 1 listener(s)
06-22 07:44:05.605  5844  5907 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-22 07:44:05.614  5844  5907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-22 07:44:05.618  5844  5907 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-22 07:44:05.633  5844  5907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-22 07:44:05.633  5844  5907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,06-22 07:44:05.637  5844  5907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-22 07:44:05.637  5844  5907 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-22 07:44:05.640  5844  5907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-22 07:44:05.640   842  1383 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:05.640  5844  5907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
06-22 07:44:05.643  5844  5907 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:05.643  5844  5907 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:44:05.643  5844  5907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:05.643  5844  5907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:44:05.643  5844  5907 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:44:05.643  5844  5907 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:44:05.643  5844  5907 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:44:05.643  5844  5907 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:44:05.643  5844  5907 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:44:05.643  5844  5907 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-22 07:44:05.643  5844  5907 D io.jxcore.node.ConnectivityMonitor: start: OK
06-22 07:44:05.644  5844  5907 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-22 07:44:05.681  5844  5844 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-22 07:44:05.896  5844  5858 I art     : CheckpointMarkThreadRoots callback created = 0x9f26b810
,06-22 07:44:05.938  5844  5858 I art     : CheckpointMarkThreadRoots callback created = 0x9f26b7e0
,06-22 07:44:06.518  5844  5929 W jxcore-log: Initializing JXcore engine
06-22 07:44:06.518  5844  5929 W jxcore-log: JXcore engine is ready
,06-22 07:44:06.593  5929  5929 W Thread-655: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8675]" dev="sockfs" ino=8675 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,06-22 07:44:06.593  5929  5929 W Thread-655: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-22 07:44:06.593  5929  5929 W Thread-655: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8823]" dev="sockfs" ino=8823 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-22 07:44:06.593  5929  5929 W Thread-655: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
06-22 07:44:06.593  5929  5929 W Thread-655: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
06-22 07:44:06.593  5929  5929 W Thread-655: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26365]" dev="sockfs" ino=26365 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-22 07:44:06.622  5844  5929 W jxcore-log: Starting JXcore engine
,06-22 07:44:06.766  5844  5929 W jxcore-log: Platform android
06-22 07:44:06.766  5844  5929 W jxcore-log: 
06-22 07:44:06.766  5844  5929 W jxcore-log: Process ARCH arm
06-22 07:44:06.766  5844  5929 W jxcore-log: 
,06-22 07:44:07.067  5844  5929 I jxcore-log: JXcore Cordova bridge is ready!
06-22 07:44:07.067  5844  5929 I jxcore-log: 
06-22 07:44:07.067  5844  5929 W jxcore-log: JXcore engine is started
,06-22 07:44:07.074  5844  5907 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-22 07:44:07.076  5844  5844 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
06-22 07:44:07.845   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:44:11.454  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,06-22 07:44:11.455  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:44:11.455  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:44:11.456  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:44:11.456  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:44:11.491  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
06-22 07:44:11.491  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,06-22 07:44:11.494  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:44:11.497  5571  5571 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-22 07:44:11.501  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:44:11.506  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,06-22 07:44:11.507   485   485 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 07:44:11.514  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:44:11.514  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:44:11.514  1852  2044 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
06-22 07:44:11.518  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-22 07:44:11.525   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:44:12.849   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:44:13.574   842  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2357b77 type 2 when 120000 com.google.android.gms} when 120000
,06-22 07:44:13.574   842  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{316e03e4 type 2 when 120784 com.google.android.gms} when 120784
06-22 07:44:13.839   842  2009 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:13.840   842  1313 D ConnectivityService: dumpNetworkRequest
,06-22 07:44:13.915  5591  5956 W DriveInitializer: Background init thread started
,06-22 07:44:13.943   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:13.943   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
06-22 07:44:13.943   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:13.949  5591  5956 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
06-22 07:44:14.080  5591  5956 W DriveInitializer: Background init thread ended
,06-22 07:44:16.602   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:44:16.602   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:44:16.602   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 132250410528; DSPS: 4424933; Offset : -2799518439
,06-22 07:44:17.854   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:44:22.053  2094  2094 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,06-22 07:44:22.060  2094  2094 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
06-22 07:44:22.859   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:44:23.414  5844  5929 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-22 07:44:23.414  5844  5929 I jxcore-log: 
,06-22 07:44:23.418  5844  5929 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-22 07:44:23.418  5844  5929 I jxcore-log: 
06-22 07:44:23.420  5844  5929 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:23.420  5844  5929 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:44:23.420  5844  5929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:23.420  5844  5929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:44:23.420  5844  5929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:44:23.420  5844  5929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:44:23.420  5844  5929 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:44:23.420  5844  5929 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:44:23.420  5844  5929 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:44:23.420  5844  5929 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:23.421  5844  5929 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-22 07:44:23.423  5844  5929 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-22 07:44:23.423  5844  5929 I jxcore-log: 
06-22 07:44:23.426  5844  5929 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-22 07:44:23.426  5844  5929 I jxcore-log: 
,06-22 07:44:23.964  5844  5929 I jxcore-log: Unit Test app is loaded
06-22 07:44:23.964  5844  5929 I jxcore-log: 
,06-22 07:44:23.974  5844  5929 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-22 07:44:23.974  5844  5929 I jxcore-log: 
06-22 07:44:23.983  5844  5844 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,06-22 07:44:23.997   842  1944 D WifiServiceImplEx: setWifiEnabled: true pid=5844, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,06-22 07:44:24.010   842  1944 D WifiService: setWifiEnabled: true pid=5844, uid=10030
,06-22 07:44:24.042   842  1820 D WifiServiceImplEx: disconnect pid=5844, uid=10030, packageName=com.test.thalitest
06-22 07:44:24.048   842  1908 D WifiServiceImplEx: reconnect pid=5844, uid=10030, packageName=com.test.thalitest
06-22 07:44:24.067   842  1306 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,06-22 07:44:24.070   842  1306 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
06-22 07:44:24.076   842  1306 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
06-22 07:44:24.076   842  1306 E WifiHW  : band=b
06-22 07:44:24.076   842  1306 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
06-22 07:44:24.078   842   842 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-22 07:44:24.085   842   842 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,06-22 07:44:24.089   279  1058 D SoftapController: Softap fwReload - Ok
06-22 07:44:24.091   842   842 D Ulp_jni : JNI:system_update. Event-4
06-22 07:44:24.092   842  1282 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:24.099   842  1282 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,06-22 07:44:24.114   842  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:24.114   842  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:24.117   279  1058 D CommandListener: Setting iface cfg
06-22 07:44:24.118   279  1058 D CommandListener: Trying to bring down wlan0
06-22 07:44:24.119   842  1026 D BluetoothManagerService: Message: 1
06-22 07:44:24.119   842  1026 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
06-22 07:44:24.119   842   842 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-22 07:44:24.119   842   842 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-22 07:44:24.119   842   842 D Ulp_jni : JNI:system_update. Event-4
06-22 07:44:24.120   279  1058 D CommandListener: Clearing all IP addresses on wlan0
06-22 07:44:24.126  5844  5929 I jxcore-log: My device name is: LGE-LG-D722
06-22 07:44:24.126  5844  5929 I jxcore-log: 
06-22 07:44:24.128  5844  5929 I jxcore-log: WARN testUtils: myNameCallback not set!
06-22 07:44:24.128  5844  5929 I jxcore-log: 
06-22 07:44:24.130  2055  2055 D BluetoothAdapterService(55213335): onBind()
,06-22 07:44:24.134   842   842 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
06-22 07:44:24.135   842  1026 D BluetoothManagerService: Message: 40
06-22 07:44:24.135   842  1026 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
06-22 07:44:24.148   842  1306 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
06-22 07:44:24.166  2055  2071 I bluedroid: config_hci_snoop_log
,06-22 07:44:24.178   842  1026 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
06-22 07:44:24.184   842  1026 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,06-22 07:44:24.212  2055  2070 V LGMDMManagerInternal: Create singleton instance
,06-22 07:44:24.225  5976  5976 I wpa_supplicant: Successfully initialized wpa_supplicant
,06-22 07:44:24.258   842  1306 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,06-22 07:44:24.267  5844  5844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-22 07:44:24.268  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,06-22 07:44:24.293  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:24.291 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-22 07:44:24.295  5976  5976 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-22 07:44:24.295  5976  5976 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
06-22 07:44:24.299  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
06-22 07:44:24.306   842   970 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5989 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
06-22 07:44:24.313   842   842 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
06-22 07:44:24.340  2055  2070 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:24.341  2055  2070 D BluetoothAdapterService(55213335): enable() - Enable called with quiet mode status =  false
,06-22 07:44:24.342  2055  2187 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
06-22 07:44:24.343  2055  2187 D BluetoothAdapterProperties: Setting state to 11
06-22 07:44:24.344  2055  2187 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
06-22 07:44:24.346  2055  2187 D BluetoothAdapterService(55213335): updateAdapterState() - Broadcasting state to 1 receivers.
06-22 07:44:24.365   842  1026 D BluetoothManagerService: Message: 60
,06-22 07:44:24.368  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:24.369   842  1026 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
06-22 07:44:24.369  2055  2187 D BluetoothAdapterService(55213335): processStart()
06-22 07:44:24.369   842  1026 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
06-22 07:44:24.376  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-22 07:44:24.379  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:24.379  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
06-22 07:44:24.380  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
06-22 07:44:24.380  1852  1852 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: Unable to read settings
06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
06-22 07:44:24.409  2055  2187 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-22 07:44:24.419  2055  2187 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
06-22 07:44:24.419  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-22 07:44:24.420  2055  2187 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
06-22 07:44:24.420  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-22 07:44:24.422  2055  2187 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
06-22 07:44:24.422  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,06-22 07:44:24.424  2055  2187 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
06-22 07:44:24.424  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-22 07:44:24.425  2055  5977 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:24.425  2055  2071 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:24.425  2055  2187 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
06-22 07:44:24.426  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-22 07:44:24.426  2055  2187 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
06-22 07:44:24.427  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-22 07:44:24.427  2055  2187 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
06-22 07:44:24.427  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-22 07:44:24.428  2055  2187 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
06-22 07:44:24.429  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
06-22 07:44:24.429  2055  2187 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
06-22 07:44:24.430  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-22 07:44:24.431  2055  2187 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
06-22 07:44:24.431  2055  2187 D BluetoothAdapterService(55213335): processStart() - Make Bond State Machine
06-22 07:44:24.432  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
,06-22 07:44:24.444  1374  1374 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
06-22 07:44:24.446  2055  2187 D BluetoothBondStateMachine: make
06-22 07:44:24.449  2055  6008 I BluetoothBondStateMachine: StableState(): Entering Off State
,06-22 07:44:24.450  2055  2187 D BluetoothAdapterService: setAdapterService() - set to: null
06-22 07:44:24.450  2055  2187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.450  2055  2187 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
06-22 07:44:24.456  2055  2187 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-22 07:44:24.457  2055  2187 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: Unable to read settings
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
06-22 07:44:24.457  2055  2187 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-22 07:44:24.457  2055  2187 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
06-22 07:44:24.458  2055  2187 D BluetoothAdapterService(55213335): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
06-22 07:44:24.471  2055  2055 D HeadsetService: Received start request. Starting profile...
06-22 07:44:24.473  1758  1758 D BluetoothHeadset: Proxy object connected
06-22 07:44:24.473   842   842 D BluetoothHeadset: Proxy object connected
06-22 07:44:24.479  2055  2055 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,06-22 07:44:24.488  2055  2187 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-22 07:44:24.488  2055  2187 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
06-22 07:44:24.488  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-22 07:44:24.488  2055  2187 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
06-22 07:44:24.488  2055  2187 D BluetoothAdapterService(55213335): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
06-22 07:44:24.489  2055  5977 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:24.495  2055  2187 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-22 07:44:24.495  2055  2187 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
06-22 07:44:24.495  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-22 07:44:24.495  2055  2187 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
06-22 07:44:24.495  2055  2187 D BluetoothAdapterService(55213335): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
06-22 07:44:24.497  1758  1758 D BluetoothHeadset: Proxy object connected
06-22 07:44:24.498  1758  1758 D BluetoothHeadset: Proxy object connected
06-22 07:44:24.501  2055  2055 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-22 07:44:24.502  2055  2055 I BluetoothHeadsetServiceJni: classInitNative: succeeds
06-22 07:44:24.504  2055  2187 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-22 07:44:24.504  2055  2187 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
06-22 07:44:24.504  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-22 07:44:24.504  2055  2187 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
06-22 07:44:24.504  2055  2187 D BluetoothAdapterService(55213335): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
06-22 07:44:24.505  2055  2055 D HeadsetStateMachine: make
06-22 07:44:24.514  2055  2187 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-22 07:44:24.514  2055  2187 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
06-22 07:44:24.515  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-22 07:44:24.515  2055  2187 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
06-22 07:44:24.515  2055  2187 D BluetoothAdapterService(55213335): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
,06-22 07:44:24.521  2055  2187 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-22 07:44:24.521  2055  2187 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
06-22 07:44:24.521  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-22 07:44:24.521  2055  2187 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
06-22 07:44:24.521  2055  2187 D BluetoothAdapterService(55213335): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
06-22 07:44:24.527  2055  2187 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-22 07:44:24.527  2055  2187 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
06-22 07:44:24.527  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-22 07:44:24.528  2055  2187 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
06-22 07:44:24.528  2055  2187 D BluetoothAdapterService(55213335): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
,06-22 07:44:24.536  2055  2187 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-22 07:44:24.536  2055  2187 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
06-22 07:44:24.536  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-22 07:44:24.536  2055  2187 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
06-22 07:44:24.536  2055  2187 D BluetoothAdapterService(55213335): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
06-22 07:44:24.541  2055  2187 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-22 07:44:24.541  2055  2187 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
06-22 07:44:24.541  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
06-22 07:44:24.541  2055  2187 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
06-22 07:44:24.541  2055  2187 D BluetoothAdapterService(55213335): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
,06-22 07:44:24.550  2055  2187 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-22 07:44:24.550  2055  2187 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
06-22 07:44:24.550  2055  2187 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-22 07:44:24.550  2055  2187 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
06-22 07:44:24.550  2055  2187 D BluetoothAdapterService(55213335): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
06-22 07:44:24.553  2055  2187 V LGMDMManager: Create singleton instance
,06-22 07:44:24.578  2055  2055 D HeadsetStateMachine: max_hf_connections = 1
,06-22 07:44:24.578  2055  2055 I bluedroid: get_profile_interface handsfree
06-22 07:44:24.582  2055  2187 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
06-22 07:44:24.583  2055  2055 I bt-btif : btif_hf_get_interface
06-22 07:44:24.583  2055  2055 I bt-btif : init
06-22 07:44:24.583  2055  2055 D bt-btif : max_hf_clients = 1
06-22 07:44:24.583  2055  2055 D bt-btif : btif_max_hf_clients = 1
06-22 07:44:24.583  2055  2055 D bt-btif : btif_enable_service: current services:0xa0662330
06-22 07:44:24.589  2055  2055 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,06-22 07:44:24.592   284  1604 V AudioPolicyService: registerClient() client 0xb39b56e0, uid 1002
06-22 07:44:24.593   284  1321 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
06-22 07:44:24.594   284  1321 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-22 07:44:24.594   284  1321 V AudioPolicyManagerEx: getOutput() returns output 2
06-22 07:44:24.595   284   284 V AudioFlinger: registerClient() client 0xb39baad8, pid 2055
06-22 07:44:24.595   284   284 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-22 07:44:24.595   284   284 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-22 07:44:24.595   284   284 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-22 07:44:24.595  2055  2055 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
06-22 07:44:24.596  2055  2055 V ToneGenerator: Create Track: 0xb4908a80
06-22 07:44:24.596   284  1292 V AudioFlinger: thread 0xb56eb000 type 0 TID 1292 waking up
06-22 07:44:24.596   284  1294 V AudioFlinger: thread 0xb5735000 type 0 TID 1294 waking up
06-22 07:44:24.596   284  1288 V AudioFlinger: thread 0xb5651000 type 0 TID 1288 waking up
06-22 07:44:24.596  2055  2055 V AudioTrack: set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
06-22 07:44:24.596  2055  2055 V AudioTrack: set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
06-22 07:44:24.596   284  1292 V AudioFlinger: processConfigEvents_l() remaining events 1
06-22 07:44:24.596   284  1292 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
06-22 07:44:24.596   284  1294 V AudioFlinger: processConfigEvents_l() remaining events 1
06-22 07:44:24.596   284  1294 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
06-22 07:44:24.597   284  1288 V AudioFlinger: processConfigEvents_l() remaining events 1
06-22 07:44:24.597   284  1288 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
06-22 07:44:24.597   284  1288 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:24.597   284  1288 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:24.597   842  1859 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:24.597   842  1859 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:24.597  1374  2326 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:24.597   284  1288 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
06-22 07:44:24.597  1374  2326 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:24.597   284  1292 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:24.598   284  1292 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:24.598  2055  2071 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:24.598  2055  2071 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
06-22 07:44:24.598   842  2194 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:24.598   842  2194 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:24.598  3093  3108 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:24.598  3093  3108 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:24.598  2026  2248 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:24.598  1374  1403 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:24.598  2026  2248 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:24.598  1374  1403 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:24.598  1758  1781 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:24.598,  2055  5977 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:24.598  1758  1781 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:24.598  2055  5977 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
06-22 07:44:24.598   284  1292 V AudioFlinger: processConfigEvents_l() DONE thread 0xb56eb000
06-22 07:44:24.598   284  1294 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-22 07:44:24.598   284  1294 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-22 07:44:24.598  2094  2114 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-22 07:44:24.598   284  1294 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5735000
06-22 07:44:24.598  2094  2114 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-22 07:44:24.598   842  1908 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-22 07:44:24.599   842  1908 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-22 07:44:24.599  2094  2114 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:24.599  2094  2114 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:24.599  3093  3109 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:24.599  3093  3109 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:24.599  2094  2114 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-22 07:44:24.599  2094  2114 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-22 07:44:24.599  3093  3109 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-22 07:44:24.599  3093  3109 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-22 07:44:24.599  2055  2070 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-22 07:44:24.599  2026  2248 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:24.599  2055  2070 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
06-22 07:44:24.599  2026  2248 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:24.599  2026  2248 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-22 07:44:24.599  2026  2248 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-22 07:44:24.599  1374  1403 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-22 07:44:24.599  1374  1403 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-22 07:44:24.599  1758  1781 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-22 07:44:24.599  1758  1781 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-22 07:44:24.599  1758  1781 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-22 07:44:24.599  1758  1781 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-22 07:44:24.599   284  1320 I AudioFlinger: isAudioPlaybackHookOn() false
06-22 07:44:24.600  2055  2055 D AudioTrack: TrackOffload: AudioTrack Offload disabled by property, returning false
06-22 07:44:24.600   284  1604 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-22 07:44:24.600   284  1604 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
06-22 07:44:24.600   284  1604 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-22 07:44:24.600   284  1604 V AudioPolicyManagerEx: getOutput() returns output 2
06-22 07:44:24.600  2055  2055 V AudioSystem: getLatency() output 2, latency 50
06-22 07:44:24.600  2055  2055 V AudioSystem: getFrameCount() output 2, frameCount 960
06-22 07:44:24.600  2055  2055 V AudioTrack: createTrack_l() output 2 afLatency 50
06-22 07:44:24.600  2055  2055 V AudioTrack: Create normal PCM 0x1 Track
06-22 07:44:24.603   284   284 V AudioFlinger: createTrack() lSessionId: 22
06-22 07:44:24.603   284   284 V AudioFlinger: AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
06-22 07:44:24.603   284   284 V AudioFlinger: sendConfigEvent_l() num events 1 event 1
06-22 07:44:24.604  2055  2055 V AudioTrack: Flags here  0x4 
06-22 07:44:24.604  2055  2055 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
06-22 07:44:24.605   284   284 V AudioFlinger: acquiring 22 from 2055, for 2055
06-22 07:44:24.605   284   284 V AudioFlinger:  added new entry for 22
06-22 07:44:24.605  2055  2055 V ToneGenerator: ToneGenerator INIT OK, time: 140253
06-22 07:44:24.605  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.608   284  1288 V AudioFlinger: processConfigEvents_l() remaining events 1
06-22 07:44:24.608   284  1288 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
06-22 07:44:24.609  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.613   842   842 D BluetoothA2dp: Proxy object connected
06-22 07:44:24.614  2055  2055 D A2dpService: Received start request. Starting profile...
06-22 07:44:24.614  2055  6009 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
06-22 07:44:24.614  2055  6009 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-22 07:44:24.615  2055  6009 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-22 07:44:24.615  2055  6009 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
06-22 07:44:24.615   284  1298 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 2055
06-22 07:44:24.616  2055  2055 I BluetoothAvrcpServiceJni: classInitNative: succeeds
06-22 07:44:24.617  2055  2055 V Avrcp   : make
06-22 07:44:24.617  2055  2055 D Avrcp   : [BTUI] Use Native AVRCP : init jni
06-22 07:44:24.617   284  1298 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
06-22 07:44:24.617  2055  2055 I bluedroid: get_profile_interface avrcp
06-22 07:44:24.617   284  1298 V voice   : voice_set_parameters: enter: bt_samplerate=8000
06-22 07:44:24.617   284  1298 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
06-22 07:44:24.617  2055  5977 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:24.617   284  1298 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-22 07:44:24.617   284  1298 V voice   : voice_set_parameters: exit with code(0)
06-22 07:44:24.617   284  1298 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
06-22 07:44:24.617   284  1298 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
06-22 07:44:24.619  2055  2055 I bt-btif : btif_rc_get_interface
06-22 07:44:24.619  2055  2055 I bt-btif : ## init ##
06-22 07:44:24.620   284  1298 V msm8974_platform: platform_set_parameters: exit with code(0)
06-22 07:44:24.620   284  1298 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-22 07:44:24.620   284  1298 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
06-22 07:44:24.620   284  1298 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-22 07:44:24.622  2055  2055 I LGBluetoothAvrcpServiceJni: classInitNative: succeeds
06-22 07:44:24.622  2055  6009 V ToneGenerator: ToneGenerator destructor
06-22 07:44:24.622  2055  6009 V ToneGenerator: stopTone
06-22 07:44:24.622  2055  6009 V ToneGenerator: Delete Track: 0xb4908a80
06-22 07:44:24.623  2055  6009 V AudioTrack: ~AudioTrack, releasing session id from 2055 on behalf of 2055
06-22 07:44:24.623   284  1320 V AudioFlinger: remove track (4099) and delete from mixer
06-22 07:44:24.623   284  1604 V AudioFlinger: releasing 22 from 2055 for 2055
06-22 07:44:24.623   284  1320 V AudioPolicyService: AudioCommandThread() adding release output 2
06-22 07:44:24.623   284  1604 V AudioFlinger:  decremented refcount to 0
06-22 07:44:24.623   284  1604 V AudioFlinger: purging stale effects
06-22 07:44:24.623   284  1320 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
06-22 07:44:24.623   284  1320 V AudioFlinger: PlaybackThread::Track destructor
06-22 07:44:24.623   284  1061 V AudioPolicyService: AudioCommandThread() waking up
06-22 07:44:24.623   284  1320 V AudioFlinger: removeClient_l() pid 2055, calling pid 284
06-22 07:44:24.623   284  1061 V AudioPolicyService: AudioCommandThread() processing release output 2
06-22 07:44:24.623   284  1061 V AudioPolicyManager: releaseOutput() 2
06-22 07:44:24.623   284  1061 V AudioPolicyService: AudioCommandThread() going to sleep
06-22 07:44:24.625  2055  2055 I LGBluetoothAvrcpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
06-22 07:44:24.625  2055  2055 I LGBluetoothAvrcpServiceJni: initNative: succeeds
,06-22 07:44:24.629  2055  2055 I BluetoothAvrcpBrcmAdapterJni: classInitBrcmNative
06-22 07:44:24.642  2055  2055 I BluetoothAvrcpBrcmAdapterJni: initBrcmNative
,06-22 07:44:24.768   842  1944 V AudioService: updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,06-22 07:44:24.768   842  1944 E AudioService: No RCC entry present to update
06-22 07:44:24.768  2055  2055 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
06-22 07:44:24.770  2055  2055 I BluetoothA2dpServiceJni: classInitNative
06-22 07:44:24.770  2055  2055 I BluetoothA2dpServiceJni: classInitNative: succeeds
06-22 07:44:24.770  2055  2055 D A2dpStateMachine: make
06-22 07:44:24.771  2055  2055 I bluedroid: get_profile_interface a2dp
06-22 07:44:24.771  2055  2055 I bt-btif : btif_av_get_src_interface
06-22 07:44:24.771  2055  2055 I bt-btif : init
06-22 07:44:24.771  2055  2055 D bt-btif : btif_enable_service: current services:0xa0662330
06-22 07:44:24.773  2055  2055 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
06-22 07:44:24.773  2055  2055 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
06-22 07:44:24.775  2055  2055 D LGBluetoothPowerControlManager: [BTUI] getInstance
06-22 07:44:24.775  2055  2055 D LGBluetoothPowerControlManager: [BTUI] init
06-22 07:44:24.777  2055  2055 D LGBluetoothPowerControlManager: [BTUI] init : getProfileProxy
06-22 07:44:24.778   842  1026 D BluetoothManagerService: Message: 30
06-22 07:44:24.781  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.781  2055  6013 D A2dpStateMachine: Enter Disconnected: -2
,06-22 07:44:24.783  2055  2055 I BluetoothHidServiceJni: classInitNative: succeeds
06-22 07:44:24.785  2055  2055 D HidService: Received start request. Starting profile...
06-22 07:44:24.785  2055  2055 I bluedroid: get_profile_interface hidhost
06-22 07:44:24.785  2055  2055 I bt-btif : btif_hh_get_interface
06-22 07:44:24.785  2055  2055 I bt-btif : init
06-22 07:44:24.785  2055  2055 D bt-btif : btif_enable_service: current services:0xa0662330
06-22 07:44:24.785  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.786  2055  2055 I BluetoothHealthServiceJni: classInitNative: succeeds
06-22 07:44:24.790  2055  2055 D HealthService: Received start request. Starting profile...
,06-22 07:44:24.792  2055  2055 I bluedroid: get_profile_interface health
06-22 07:44:24.792  2055  2055 I bt-btif : btif_hl_get_interface
06-22 07:44:24.792  2055  2055 I bt-btif : init
06-22 07:44:24.792  2055  2055 D bt-btif : Process name (droid.bluetooth)
06-22 07:44:24.792  2055  2055 D bt-btif : btif_hl_soc_thread_init
,06-22 07:44:24.794  2055  2055 D bt-btif : create_thread: entered
06-22 07:44:24.794  2055  2055 D bt-btif : create_thread: thread created successfully
06-22 07:44:24.794  2055  6015 D bt-btif : entered btif_hl_select_thread
06-22 07:44:24.794  2055  6015 D bt-btif : btif_hl_select_wakeup_init
06-22 07:44:24.794  2055  6015 D bt-btif : btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
06-22 07:44:24.794  2055  6015 D bt-btif : max_s=55 
06-22 07:44:24.794  2055  6015 D bt-btif : set curr_set = org_set 
06-22 07:44:24.794  2055  2055 I LGBluetoothHealthServiceJni: classInitNative: succeeds
06-22 07:44:24.794  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.797  2055  2055 I BluetoothPanServiceJni: classInitNative(L105): succeeds
06-22 07:44:24.800  2055  2055 D PanService: Received start request. Starting profile...
06-22 07:44:24.800  2055  2055 D BluetoothPanServiceJni: initializeNative(L110): pan
06-22 07:44:24.800  2055  2055 I bluedroid: get_profile_interface pan
06-22 07:44:24.800  2055  2055 D bt-btif : stack_initialized = 0, btpan_cb.enabled:0
06-22 07:44:24.807  2055  2055 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,06-22 07:44:24.807  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.809  2055  2055 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
06-22 07:44:24.814  2055  2055 D BtGatt.DebugUtils: handleDebugAction() action=null
06-22 07:44:24.815  2055  2055 D BtGatt.GattService: Received start request. Starting profile...
06-22 07:44:24.815  2055  2055 D BtGatt.GattService: start()
06-22 07:44:24.815  2055  2055 I bluedroid: get_profile_interface gatt
06-22 07:44:24.815  2055  2055 D BtGatt.AdvertiseManager: advertise manager created
06-22 07:44:24.821  2055  2055 I LGBluetoothGattAdapter: [BTUI] getInstance : create [LGBluetoothGattAdapter]
,06-22 07:44:24.821  2055  2055 D LGBluetoothGattAdapter: setGattService:  set to: null
06-22 07:44:24.821  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.825  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.825  2055  2055 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
06-22 07:44:24.826  2055  2055 V BluetoothMapService: BluetoothMapBinder()
06-22 07:44:24.827  2055  2055 D BluetoothMapService: Received start request. Starting profile...
06-22 07:44:24.827  2055  2055 D BluetoothMapService: start()
06-22 07:44:24.832  2055  2055 D BluetoothMapEmailSettingsLoader: Found 0 applications
06-22 07:44:24.832  2055  2055 D BluetoothMapEmailAppObserver: createReceiver()
06-22 07:44:24.834  2055  2055 D BluetoothMapEmailAppObserver: initObservers()
06-22 07:44:24.834  2055  2055 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
06-22 07:44:24.841  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.846  2055  2055 I BluetoothSAPServiceJni: classInitNative(L170): succeeds
06-22 07:44:24.849  2055  2055 D SapService: Received start request. Starting profile...
06-22 07:44:24.849  2055  2055 D BluetoothSAPServiceJni: initializeNative(L175): sap
06-22 07:44:24.850  2055  2055 I bluedroid: get_profile_interface sap
06-22 07:44:24.850  2055  2055 I bt-btif : btif_sc_get_interface
06-22 07:44:24.850  2055  2055 I bt-btif : init
06-22 07:44:24.850  2055  2055 D bt-btif : btif_enable_service: current services:0xa0662330
06-22 07:44:24.850  2055  2055 I LGBluetoothSapAdapter: [BTUI] getInstance : create [LGBluetoothSapAdapter]
06-22 07:44:24.850  2055  2055 I LGBluetoothSapAdapter: [BTUI] Create LGBluetoothSapManager Instance
,06-22 07:44:24.853  2055  2055 D LGBluetoothSapManager: [BTUI] initSapManager
06-22 07:44:24.856  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.861  1758  1758 D LgeBluetoothSimManager: [BTUI] SAP_ENABLE_EVT
06-22 07:44:24.869  2055  2055 V BluetoothFTPServiceJni: classInitNative
,06-22 07:44:24.870  2055  2055 I BluetoothFTPServiceJni: classInitNative(L271): succeeds
06-22 07:44:24.870  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.871  2055  2055 D BluetoothFTPService: BluetoothFtpBinder()
06-22 07:44:24.872  2055  2055 D **BluetoothFTPService: Received start request. Starting profile...
06-22 07:44:24.872  2055  2055 V BluetoothFTPService: FTP-Server Service start
06-22 07:44:24.874  2055  2055 D BluetoothFTPServiceJni: initFtpNativeDataNative(L275): FTP
06-22 07:44:24.874  2055  2055 I bluedroid: get_profile_interface ftp
06-22 07:44:24.874  2055  2055 I bt-btif : btif_fts_get_interface
06-22 07:44:24.874  2055  2055 I bt-btif : init
06-22 07:44:24.874  2055  2055 D bt-btif : btif_enable_service: current services:0xa0662330
06-22 07:44:24.874  2055  2055 D BluetoothFTPServiceJni: initFtpNativeDataNative(L317): FTP init done
06-22 07:44:24.874  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.875  2055  2055 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-22 07:44:24.875  2055  2055 E BluetoothOPPServiceJni: classInitNative
06-22 07:44:24.876  2055  2055 I BluetoothOPPServiceJni: classInitNative(L373): succeeds
06-22 07:44:24.876  2055  2055 V OppService: Opp initBinder
06-22 07:44:24.877  2055  2055 D **OppService: Received start request. Starting profile...
06-22 07:44:24.877  2055  2055 D OppService: Starting OppService 
06-22 07:44:24.877  2055  2055 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
06-22 07:44:24.883  2055  2055 I NotificationManager: com.android.bluetooth: cancelAll by com.android.bluetooth
,06-22 07:44:24.884  2055  2055 V BluetoothOppNotification: send message
06-22 07:44:24.893  5989  5989 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:44:24.894  5989  5989 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
06-22 07:44:24.894  5989  5989 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-22 07:44:24.896  5989  5989 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,06-22 07:44:24.897  2055  2055 D BluetoothOppPreference: Dumping Names:  
06-22 07:44:24.897  2055  2055 D BluetoothOppPreference: {}
06-22 07:44:24.897  2055  2055 D BluetoothOppPreference: Dumping Channels:  
06-22 07:44:24.897  2055  2055 D BluetoothOppPreference: {}
06-22 07:44:24.898  5989  5989 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
06-22 07:44:24.899  2055  2055 D OppService: Start()
06-22 07:44:24.899  2055  2055 W BluetoothOPPServiceJni: initOppNative
06-22 07:44:24.899  2055  2055 D BluetoothOPPServiceJni: initOppNative(L383): OPP
06-22 07:44:24.899  2055  2055 I bluedroid: get_profile_interface opp
06-22 07:44:24.899  2055  2055 I bt-btif : btif_op_get_interface
06-22 07:44:24.899  2055  2055 D BluetoothOPPServiceJni: initOppNative(L411): mOppCallbacksObj 1049850
06-22 07:44:24.899  2055  2055 D BluetoothOPPServiceJni: initOppNative(L413): calling OPP init
06-22 07:44:24.900  2055  2055 I bt-btif : btif_opp_init
06-22 07:44:24.900  2055  2055 D bt-btif : btif_enable_service: current services:0xa0662330
06-22 07:44:24.900  2055  2055 D BluetoothOPPServiceJni: initOppNative(L429): OPC and OPS init Succesful
06-22 07:44:24.901  2055  2055 D BluetoothOPPServiceJni: initOppNative(L430): mOppCallbacksObj 1049850
06-22 07:44:24.901  2055  2055 V OppService: setOppService(): set to: com.broadcom.bt.service.opp.OppService@e9a63f5
06-22 07:44:24.901  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:24.901  2055  2055 D HeadsetStateMachine: Proxy object connected
06-22 07:44:24.902  2055  2055 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
06-22 07:44:24.903  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - Message: 1
06-22 07:44:24.903  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-22 07:44:24.904  2055  2055 D BluetoothAdapterService(55213335): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
06-22 07:44:24.904  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:44:24.904  2055  6009 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-22 07:44:24.905  2055  6009 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-22 07:44:24.905  2055  2055 D BluetoothAdapterState: isTurningOnRadio()=false
06-22 07:44:24.905  2055  2055 D BluetoothAdapterState: isTurningOffRadio()=false
06-22 07:44:24.905  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-22 07:44:24.905  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-22 07:44:24.905  2055  2055 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-22 07:44:24.906  2055  6023 V OppService: pendingUpdate is :  true
06-22 07:44:24.908  2055  2055 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-22 07:44:24.908  2055  2055 D BluetoothA2dp: Proxy object connected
06-22 07:44:24.908  2055  2055 D LGBluetoothPowerControlManager: [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@2a35c018
06-22 07:44:24.908  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - Message: 1
06-22 07:44:24.908  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,06-22 07:44:24.908  2055  2055 D BluetoothAdapterService(55213335): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,06-22 07:44:24.908  2055  2055 D BluetoothAdapterState: isTurningOnRadio()=false
06-22 07:44:24.908  2055  2055 D BluetoothAdapterState: isTurningOffRadio()=false
06-22 07:44:24.908  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-22 07:44:24.908  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-22 07:44:24.908  2055  2055 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-22 07:44:24.911  2055  2055 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-22 07:44:24.911  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - Message: 1
06-22 07:44:24.911  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-22 07:44:24.911  2055  2055 D BluetoothAdapterService(55213335): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
06-22 07:44:24.911  2055  2055 D BluetoothAdapterState: isTurningOnRadio()=false
06-22 07:44:24.912  2055  2055 D BluetoothAdapterState: isTurningOffRadio()=false
06-22 07:44:24.912  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-22 07:44:24.912  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-22 07:44:24.912  2055  2055 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-22 07:44:24.913  2055  6020 V OppService: Deleted complete outbound shares, number =  0
06-22 07:44:24.914  2055  2055 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-22 07:44:24.915  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - Message: 1
06-22 07:44:24.915  2055  6023 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-22 07:44:24.915  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-22 07:44:24.915  2055  2055 D BluetoothAdapterService(55213335): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
06-22 07:44:24.915  2055  2055 D BluetoothAdapterState: isTurningOnRadio()=false
06-22 07:44:24.915  2055  2055 D BluetoothAdapterState: isTurningOffRadio()=false
06-22 07:44:24.915  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-22 07:44:24.915  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-22 07:44:24.915  2055  2055 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-22 07:44:24.917  2055  6020 V OppService: Deleted complete inbound failed shares, number = 0
06-22 07:44:24.918  2055  6020 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
06-22 07:44:24.919  2055  2055 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-22 07:44:24.919  2055  6020 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38a65056 on behalf of 
06-22 07:44:24.919  2055  2055 V PanService: [BTUI] SIM Extra State :ABSENT
06-22 07:44:24.919  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - Message: 1
06-22 07:44:24.919  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-22 07:44:24.919  2055  2055 D BluetoothAdapterService(55213335): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
06-22 07:44:24.919  2055  2055 D BluetoothAdapterState: isTu,rningOnRadio()=false
06-22 07:44:24.919  2055  2055 D BluetoothAdapterState: isTurningOffRadio()=false
06-22 07:44:24.919  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-22 07:44:24.919  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-22 07:44:24.919  2055  2055 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-22 07:44:24.920  2055  6023 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fa4a71 on behalf of 
,06-22 07:44:24.923  2055  2055 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-22 07:44:24.923  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - Message: 1
06-22 07:44:24.923  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-22 07:44:24.923  2055  2055 D BluetoothAdapterService(55213335): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
06-22 07:44:24.923  2055  2055 D BluetoothAdapterState: isTurningOnRadio()=false
06-22 07:44:24.923  2055  2055 D BluetoothAdapterState: isTurningOffRadio()=false
06-22 07:44:24.923  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-22 07:44:24.923  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-22 07:44:24.923  2055  2055 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-22 07:44:24.926  2055  2055 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-22 07:44:24.926  2055  2055 V BluetoothMapService: Handler(): got msg=1
06-22 07:44:24.926  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - Message: 1
06-22 07:44:24.926  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-22 07:44:24.926  2055  2055 D BluetoothAdapterService(55213335): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
06-22 07:44:24.926  2055  2055 D BluetoothAdapterState: isTurningOnRadio()=false
06-22 07:44:24.926  2055  2055 D BluetoothAdapterState: isTurningOffRadio()=false
06-22 07:44:24.926  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-22 07:44:24.927  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-22 07:44:24.927  2055  2055 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-22 07:44:24.929  2055  2055 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-22 07:44:24.929  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - Message: 1
06-22 07:44:24.929  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-22 07:44:24.929  2055  2055 D BluetoothAdapterService(55213335): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
06-22 07:44:24.929  2055  2055 D BluetoothAdapterState: isTurningOnRadio()=false
06-22 07:44:24.929  2055  2055 D BluetoothAdapterState: isTurningOffRadio()=false
06-22 07:44:24.929  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-22 07:44:24.929  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-22 07:44:24.930  2055  2055 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-22 07:44:24.932  2055  2055 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-22 07:44:24.932  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - Message: 1
06-22 07:44:24.932  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-22 07:44:24.932  2055  2055 D BluetoothAdapterService(55213335): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
06-22 07:44:24.932  2055  2055 D BluetoothAdapterState: isTurningOnRadio()=false
06-22 07:44:24.932  2055  2055 D BluetoothAdapterState: isTurningOffRadio()=false
06-22 07:44:24.932  2055  2055 D BluetoothAdapterState:, isQuietModeServiceTurningOn()=false
06-22 07:44:24.932  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-22 07:44:24.932  2055  6023 V BluetoothOppNotification: update too frequent, put in queue
06-22 07:44:24.932  2055  2055 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-22 07:44:24.933  2055  6023 V OppService: pendingUpdate is :  false
06-22 07:44:24.933  2055  6023 E OppService: UpdateThread is Completed
06-22 07:44:24.935  2055  2055 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-22 07:44:24.935  2055  2055 V BluetoothOppNotification: new notify threadi!
06-22 07:44:24.936  2055  2055 V BluetoothOppNotification: send delay message
06-22 07:44:24.936  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - Message: 1
06-22 07:44:24.936  2055  2055 D BluetoothAdapterService(55213335): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-22 07:44:24.936  2055  2055 D BluetoothAdapterService(55213335): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
06-22 07:44:24.936  2055  2055 D BluetoothAdapterState: isTurningOnRadio()=false
06-22 07:44:24.936  2055  2055 D BluetoothAdapterState: isTurningOffRadio()=false
06-22 07:44:24.936  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-22 07:44:24.936  2055  2055 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-22 07:44:24.936  2055  2055 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-22 07:44:24.936  2055  2055 D BluetoothAdapterService(55213335): onProfileServiceStateChange() - All profile services started.
06-22 07:44:24.936  2055  2055 V OppService: ContentObserver received notification
06-22 07:44:24.937  2055  2187 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
06-22 07:44:24.937  2055  2187 I bluedroid: enable
06-22 07:44:24.937  2055  2187 I bt-btif : BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
06-22 07:44:24.937  2055  2187 E bt-btu  : VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
06-22 07:44:24.938  2055  2055 V OppService: ContentObserver received notification
,06-22 07:44:24.939  2055  2187 I bt_hci_bdroid: init
06-22 07:44:24.939  2055  2187 I bt_vendor: init
06-22 07:44:24.940  2055  2187 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
06-22 07:44:24.940  2055  2187 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
06-22 07:44:24.941  2055  6024 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
06-22 07:44:24.941  2055  2187 I bt-btif : libbt-hci init returns 0
06-22 07:44:24.942  2055  6026 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
06-22 07:44:24.942  2055  6026 I bt-btu  : btu_task pending for preload complete event
06-22 07:44:24.942  2055  6025 V OppService: pendingUpdate is :  true
06-22 07:44:24.942  2055  6025 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-22 07:44:24.946  2055  6024 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ce98d7 on behalf of 
06-22 07:44:24.948  2055  6024 V BluetoothOppNotification: mUpdateCompleteNotification = true
06-22 07:44:24.951  2055  6025 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ed2c5c4 on behalf of 
,06-22 07:44:24.953  2055  6024 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-22 07:44:24.959  2055  6025 V OppService: pendingUpdate is :  false
06-22 07:44:24.959  2055  6025 E OppService: UpdateThread is Completed
06-22 07:44:24.993  2055  6024 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11981cad on behalf of 
06-22 07:44:24.994  2055  6024 V BluetoothOppNotification: outbound: succ-0  fail-0
,06-22 07:44:24.997  2055  6024 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
06-22 07:44:24.998  2055  6024 V BluetoothOppNotification: outbound notification was removed.
06-22 07:44:24.998  2055  6024 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
06-22 07:44:25.000  2055  6024 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@314f1be2 on behalf of 
06-22 07:44:25.002  2055  6024 V BluetoothOppNotification: inbound: succ-0  fail-0
06-22 07:44:25.006  2055  6024 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
,06-22 07:44:25.007  2055  6024 V BluetoothOppNotification: inbound notification was removed.
06-22 07:44:25.007  2055  6024 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
06-22 07:44:25.009  2055  6024 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bf9eb73 on behalf of 
06-22 07:44:25.030  2055  6028 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,06-22 07:44:25.035  2055  6028 D bt_userial_vendor: userial_vendor_open():UART is setup
06-22 07:44:25.035  2055  6028 I bt_userial_vendor: device fd = 70 open
06-22 07:44:25.046  2055  6028 D bt_hwcfg: hw_config_cback opcode:0x0c03
,06-22 07:44:25.046  2055  6028 D bt_hwcfg: hw_config_cback state=1
06-22 07:44:25.071  5989  5989 I IndexDatabaseHelper: Using schema version: 115
,06-22 07:44:25.072  2055  6028 D bt_hwcfg: hw_config_cback opcode:0x0c14
06-22 07:44:25.072  2055  6028 D bt_hwcfg: hw_config_cback state=4
06-22 07:44:25.072  2055  6028 D bt_hwcfg: Chipset Name: BCM4334B0
06-22 07:44:25.072  2055  6028 D bt_hwcfg: Chipset BCM4334B0
06-22 07:44:25.072  2055  6028 D bt_hwcfg: Target name = [BCM4334B0]
06-22 07:44:25.073  2055  6028 I bt_hwcfg: Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
06-22 07:44:25.073  5989  5989 I IndexDatabaseHelper: Index is fine
06-22 07:44:25.077  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc45
06-22 07:44:25.077  2055  6028 D bt_hwcfg: hw_config_cback state=2
06-22 07:44:25.082  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc18
06-22 07:44:25.082  2055  6028 D bt_hwcfg: hw_config_cback state=3
06-22 07:44:25.082  2055  6028 I bt_hwcfg: bt vendor lib: set UART baud 4000000
06-22 07:44:25.107  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc2e
,06-22 07:44:25.107  2055  6028 D bt_hwcfg: hw_config_cback state=5
06-22 07:44:25.158  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-22 07:44:25.158  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.159  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.159  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.161  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.161  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.162  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.162  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.163  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.163  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.164  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.164  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.164  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.165  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.165  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.165  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.166  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.166  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.168  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.168  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.169  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.169  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.170  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.170  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.171  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.171  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.173  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.173  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.174  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.174  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.175  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.175  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.176  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.176  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.177  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.177  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.178  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.178  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.179  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.179  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.180  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.180  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.181  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.181  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.182  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.182  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.183  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.183  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.184  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.184  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.185  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.185  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.186  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.186  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.187  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.187  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.188  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.188  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.189  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.189  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.190  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.190  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.191  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.191  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.192  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.192  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.193  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.193  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.196  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.196  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.197  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.197  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.199  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.199  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.200  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.200  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.202  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.202  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.202  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.202  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.203  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.203  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.204  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.204  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.205  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.205  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.207  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.207  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.208  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.208  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.208  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.208  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.209  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.209  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.210  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.210  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.211  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.211  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.212  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.212  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.212  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.212  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.213  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.213  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.214  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.214  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.215  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.215  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.216  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.216  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.217  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.217  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.218  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.218  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.219  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.219  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.220  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.220  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.221  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.221  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.225  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.225  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.226  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.226  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.227  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.227  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.228  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.228  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.230  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.230  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.231  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.231  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.232  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.232  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.232  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.232  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.233  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.233  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.234  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.234  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.235  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.235  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.236  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.236  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.236  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.236  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.237  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.237  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.238  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.238  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.239  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.239  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.241  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.241  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.242  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.242  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.243  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.243  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.244  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.244  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.245  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.245  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.246  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.246  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.246  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.246  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.247  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.247  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.247  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.248  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.248  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.249  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.249  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.250  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.251  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.251  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.253  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.253  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.254  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.254  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.256  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.256  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.256  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.256  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.258  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.258  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.259  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.259  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.259  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.259  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.260  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.260  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.260  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.260  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.261  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.261  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.262  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.262  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.264  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.264  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.265  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.265  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.266  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.266  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.267  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.267  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.268  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.269  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.269  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.269  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.270  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.270  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.271  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.271  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.272   842  1820 I ActivityManager: Process com.google.android.apps.docs (pid 5480) has died
06-22 07:44:25.272  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.272  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.274  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.274  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.276  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.276  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.277  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.277  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.279  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.279  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.283  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.283  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.284  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.284  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.285  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.285  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.286  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.286  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.287  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.287  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.288  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.288  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.289  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.289  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.290  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.290  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.291  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.291  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.293  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.293  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.294  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.294  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.295   279  1051 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-22 07:44:25.295   279  1051 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-22 07:44:25.297  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.297  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.300  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.300  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.301  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.302  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.303  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.303  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.304  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.304  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.305  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.305  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.306  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.306  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.307  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.307  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.307  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.307  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.308  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.308  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.309  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.309  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.310  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.310  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.312  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.312  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.313  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.313  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.314  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.314  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.315  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.315  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.316  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.316  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.316  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.317  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.317  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.317  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.318  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.318  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.318  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.318  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.319  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.319  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.320  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.320  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.321   842  1893 I art     : Explicit concurrent mark sweep GC freed 40777(2023KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 4.282ms total 208.774ms
06-22 07:44:25.321  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.321  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.322  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.322  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.324  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.324  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.325  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.325  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.325  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.325  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.326  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.326  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.327   842  1026 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
06-22 07:44:25.328  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.328  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.329  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.329  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.330   842  1303 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:25.330   842  1303 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:25.330  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.330  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.330  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.330  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.331  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.331  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.332  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.332  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.333  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.333  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.334  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.334  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.335  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.336  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.337   842  1303 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:25.337   842  1303 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:25.337  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.337  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.337   279  1053 E BandwidthController: [LG DATA] No such appUid: 1000
06-22 07:44:25.337   279  1053 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-22 07:44:25.338  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.338  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.338   279  6030 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
06-22 07:44:25.338   279  6030 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:25.339   279  6030 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
06-22 07:44:25.339  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.339  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.340  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.340  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.340  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.340  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.341  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.341  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.341   842  1024 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
06-22 07:44:25.342  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.342  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.342  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.342  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.343  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.343  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.344  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.344  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.344  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.344  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.345  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.345  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.345  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.345  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.346  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.346  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.347  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.347  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.347  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.347  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.348  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.348  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.348  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.348  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.349  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.349  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.350  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.350  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.350  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.350  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.350  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.350  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.351  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.351  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.351  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.351  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.352  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.352  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.353  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.353  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.353  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.353  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.354  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.354  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.354  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.354  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.355  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.355  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.355  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.355  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.356  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.356  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.357  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.357  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.358  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.358  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.359  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.359  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.359  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.360  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.361  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.361  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.362  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.362  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.363  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.363  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.364  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.364  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.364   842  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:25.364   842  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:25.365  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.365  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.366  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.366  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.366  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.366  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.367  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.367  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.368  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.368  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.369  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.369  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.370  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.370  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.371  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.371  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.372  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.372  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.373  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.373  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.373  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.373  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.374  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.374  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.375  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.375  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.376  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.376  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.376  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.377  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.377  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.377  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.378  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.378  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.378  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.379  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.379  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.379  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.380  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.381  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.381  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.381  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.382  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.382  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.383  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.383  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.384  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.384  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.386  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.386  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.386  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.387  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.387  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.387  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.388  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.388  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.390  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.390  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.390  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.390  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.391  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.391  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.392  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.392  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.393  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.393  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.394  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-22 07:44:25.394  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.398  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.398  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.398  5976  5976 E wpa_supplicant: USIM:  scard_init function
06-22 07:44:25.399  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.399  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.399  5976  5976 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-22 07:44:25.400  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.400  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.401   279  1051 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
06-22 07:44:25.401  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.401  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.401   279  1051 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
06-22 07:44:25.402  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.402  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.402   279  1051 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
06-22 07:44:25.403  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.403  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.404  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.404  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.405  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.405  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.406  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.406  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.406   842  1024 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:25.406   842  1024 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:25.407  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.407  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.408  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.408  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.409  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.409  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.411  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.411  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.411  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.411  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.412  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.412  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.412  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.412  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.413  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.413  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.414  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.414  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.415  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.415  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.416  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.416  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.417  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.417  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.417  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.417  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.418  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.418  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.420  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.420  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.420  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.420  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.421  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.421  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.422  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.422  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.423  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.423  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.424  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.424  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.425  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.425  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.426  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.426  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.427  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.427  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.428  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.428  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.428  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.428  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.429  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.429  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.430  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.430  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.431  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.431  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.431  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.431  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.432  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.432  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.433  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.433  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.433  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.433  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.434  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.434  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.435  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.435  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.436  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.436  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.437  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.437  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.438  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.438  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.439  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.439  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.440  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.440  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.441  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.441  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.441  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.441  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.442  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.442  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.443  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.443  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.443  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.443  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.444  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.444  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.445  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.445  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.446  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.446  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.446  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.447  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.448  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.448  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.449  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.449  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.449  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.449  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.449  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.449  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.450  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.450  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.451  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-22 07:44:25.451  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.452  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.452  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.452  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.452  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.453  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.453  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.454  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.454  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.455  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.455  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.456  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.456  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.457  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.457  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.457  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.457  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.457  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-22 07:44:25.458  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.459  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.459  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.460  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.460  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.461  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.461  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.462  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.462  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.463  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.463  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.464  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.464  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.465  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.465  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.466  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-22 07:44:25.466  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.467  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.467  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.468  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.468  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.469  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.469  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.470  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.470  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.471  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.471  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.472  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.472  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.473  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.473  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.474  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.474  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.474  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.474  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.474  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.475  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.475  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-22 07:44:25.475  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.475  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.475  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.476  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.476  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.476  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.476  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.477  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.477  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.477  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.477  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.478  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.478  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.479  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.479  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.479  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.479  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.480  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.480  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.481  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.481  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.482  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.482  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.482  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.482  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.483  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.483  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.483  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.483  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.483  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.483  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.484  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.484  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.484  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.484  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.484  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.484  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.485  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.485  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.485  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.485  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.486  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.486  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.486  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.486  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.486  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.486  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.487  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.487  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.487  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.487  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.487  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.488  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.488  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.488  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.488  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.488  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.489  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.489  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.489  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.489  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.490  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.490  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.490  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.490  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.491  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-22 07:44:25.491  2055  6028 D bt_hwcfg: hw_config_cback state=6
06-22 07:44:25.491  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc4e
06-22 07:44:25.491  2055  6028 D bt_hwcfg: hw_config_cback state=6
,06-22 07:44:25.503  2055  2055 V BluetoothPbapReceiver: PbapReceiver onReceive 
,06-22 07:44:25.505  2055  2055 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:25.505  2055  2055 V BluetoothPbapReceiver: ***********state = 11
,06-22 07:44:25.505  5976  5976 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
06-22 07:44:25.518  5976  5976 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,06-22 07:44:25.523   842  1306 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
06-22 07:44:25.525   842  1306 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
06-22 07:44:25.525   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:25.525   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:44:25.528   842   842 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
06-22 07:44:25.528  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
06-22 07:44:25.529  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:25.529 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-22 07:44:25.531  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
06-22 07:44:25.531  5844  5844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:25.532  5844  5844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-22 07:44:25.532  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:25.532  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:44:25.532  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-22 07:44:25.532  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:44:25.532  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:44:25.532  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:44:25.532  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:44:25.533  5844  5844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:25.533  5844  5844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,06-22 07:44:25.534   842  1311 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,06-22 07:44:25.534  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:25.534  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:25.535  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-22 07:44:25.535  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
06-22 07:44:25.537   842   842 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
06-22 07:44:25.551  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-22 07:44:25.553   842  1306 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
06-22 07:44:25.554   842  1306 D WifiStateMachine: enableVerboseLogging : level 2
06-22 07:44:25.559   842  1306 D WifiStateMachine: Setting OUI to DA-A1-19
06-22 07:44:25.559   842  1306 D WifiNative-HAL: Setting external_sim to 1
06-22 07:44:25.560   842  1306 I WifiNative-HAL: startHal
06-22 07:44:25.560   842  1306 E wifi    : getStaticLongField sWifiHalHandle 0x9b43c8ec
06-22 07:44:25.560   842  1306 I WifiHAL : Initializing wifi
06-22 07:44:25.560   842  1306 I WifiHAL : Creating socket
06-22 07:44:25.562   842  1306 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
06-22 07:44:25.562   842  1306 D wifi    : Did set static halHandle = 0xb060dd00
06-22 07:44:25.563   842  1306 D wifi    : halHandle = 0xb060dd00, mVM = 0xb487c280, mCls = 0x501d2a
06-22 07:44:25.563   842  1306 E wifi    : getStaticLongField sWifiHalHandle 0x9b43c89c
06-22 07:44:25.563   842  1306 D wifi    : array field set
06-22 07:44:25.563   842  1306 I WifiNative-HAL: interface[0] = wlan0
06-22 07:44:25.563   842  1306 I WifiNative-HAL: interface[1] = p2p0
06-22 07:44:25.564   842  1306 D wifi    : setting scan oui 0x9a0e31f0
06-22 07:44:25.564   842  1306 D WifiHAL : Sending mac address OUI
06-22 07:44:25.564   842  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
06-22 07:44:25.564   842  1306 D WifiStateMachine: Setting OUI to DA-A1-19
06-22 07:44:25.564   842  1306 I WifiNative-HAL: startHal
06-22 07:44:25.564   842  1306 D wifi    : setting scan oui 0x9a0e31f0
06-22 07:44:25.564   842  1306 D WifiHAL : Sending mac address OUI
06-22 07:44:25.564   842  1306 E WifiHAL : failed to set scanning mac OUI; result = -95
,06-22 07:44:25.566  1852  1852 D WfdsService: Supplicant Connection state is changed : true
06-22 07:44:25.567   842  6034 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1335829248
06-22 07:44:25.567   842  6034 D wifi    : waitForHalEvents called, vm = 0xb487c280, obj = 0x501d2a, env = 0xaaefc710
06-22 07:44:25.567   842  6034 E wifi    : getStaticLongField sWifiHalHandle 0x99371b2c
06-22 07:44:25.569  1852  2129 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
06-22 07:44:25.569  1852  2129 D WfdsService: Set the WFDS Monitor: true
06-22 07:44:25.571  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-22 07:44:25.571  1852  2129 D WfdsMonitor: WfdsMonitorThread create
06-22 07:44:25.572  1852  2129 D WfdsMonitor: WFDS Monitor is created and started
06-22 07:44:25.572  1852  2129 D WfdsService: WiFi: Supplicant connection re-established
06-22 07:44:25.572   842   842 D WifiHS20: hidePasspointNotification off =false
,06-22 07:44:25.576   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:25.576   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:25.576   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-22 07:44:25.579  5742  5742 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:25.580  1852  6035 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
06-22 07:44:25.581  1852  6035 E CtrlSupplicant: Succeed to open control connection
06-22 07:44:25.581  1852  6035 E CtrlSupplicant: Succeed to open monitor connection
06-22 07:44:25.581  1852  6035 D WfdsMonitor: Supplicant connection established
06-22 07:44:25.583  1852  2129 D WfdsService: Connected to the supplicant for wfds
06-22 07:44:25.584  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:25.584 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-22 07:44:25.585  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:25.586  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-22 07:44:25.586   842  1305 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.587   842   842 D WifiScanningService: SCAN_AVAILABLE : 3
06-22 07:44:25.587   842   842 D RttService: SCAN_AVAILABLE : 3
06-22 07:44:25.587   842  1327 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.587   842  1327 I WifiNative-HAL: startHal
06-22 07:44:25.588   842  1328 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.588   842  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:25.588   842  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:25.588   279  1058 D CommandListener: Setting iface cfg
06-22 07:44:25.588   279  1058 D CommandListener: Trying to bring up p2p0
06-22 07:44:25.590   842  1327 D wifi    : getting scan capabilities on interface[0] = 0x9a0e31f0
06-22 07:44:25.590   842  1327 D WifiHAL : Creating message to get scan capablities; iface = 24
06-22 07:44:25.590   842  1327 D wifi    : failed to get capabilities : -95
06-22 07:44:25.591   842  1327 E WifiScanningService: could not get scan capabilities
06-22 07:44:25.591  2055  6028 I bt_hwcfg: bt vendor lib: set UART baud 115200
06-22 07:44:25.592  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:25.592  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:25.592  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-22 07:44:25.592  2055  6028 D bt_hwcfg: Settlement delay -- 100 ms
06-22 07:44:25.592  2055  6028 I bt_hwcfg: Setting fw settlement delay to 100 
06-22 07:44:25.592  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:25.593   842  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-22 07:44:25.593   842  1305 D LGWifiP2pService: P2pEnablingState
06-22 07:44:25.593   842  1305 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.594   842  1305 D LGWifiP2pService: P2p socket connection successful
06-22 07:44:25.594   842  1305 D LGWifiP2pService: P2pEnabledState
06-22 07:44:25.596  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:25.596  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:25.597   842  1305 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
06-22 07:44:25.598   842  1305 D LGWifiP2pService: before postfix = G3s-1
06-22 07:44:25.598   842  1306 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
06-22 07:44:25.598   842  1305 D WifiServerServiceExt: postfix byte check : 5
06-22 07:44:25.598   842  1305 D LGWifiP2pService: after postfix = G3s-1
06-22 07:44:25.600   842  1305 D WifiNative-HAL: p2pGetDeviceAddress
06-22 07:44:25.600   842  1305 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
,06-22 07:44:25.602   842  1305 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
06-22 07:44:25.605  1852  1852 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
06-22 07:44:25.605   842  1306 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
06-22 07:44:25.611  1852  1852 D WfdsService: Update P2p Interface State: 3
,06-22 07:44:25.629  5976  5976 E wpa_supplicant: nWIFIDualbandAPConnection: 1
06-22 07:44:25.631   842  1306 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
06-22 07:44:25.631  5976  5976 E wpa_supplicant: disconnect_rssi_lvl: -100
06-22 07:44:25.631   842  1305 D LGWifiP2pService: sending p2p persistent groups changed broadcast
06-22 07:44:25.632   842  1305 D LGWifiP2pService: sending p2p connection changed broadcast
06-22 07:44:25.633  1852  1852 D WfdsService: WifiP2pState is changed : true
06-22 07:44:25.633  1852  2129 D WfdsService: Receive the WFDS_ENABLE Method
06-22 07:44:25.633  1852  2129 D WfdsService: Set the WFDS Monitor: true
06-22 07:44:25.633  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
06-22 07:44:25.633  1852  2129 D WfdsService: Connected to the supplicant for wfds
06-22 07:44:25.634  5989  5989 D WiFiOffLoadUpdatePriority: remove : truetruetrue
06-22 07:44:25.634  1852  2129 D WfdsJNI : doCommand: WFDS_SET TRUE
06-22 07:44:25.634  5976  5976 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
,06-22 07:44:25.637   842  1305 D LGWifiP2pService: InactiveState
06-22 07:44:25.637   842  1305 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.637   842  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.638   842  1305 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.638   842  1306 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
06-22 07:44:25.638  5976  5976 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
06-22 07:44:25.639  1852  1852 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
06-22 07:44:25.640   842  1306 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
06-22 07:44:25.642   842  1305 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.642   842  1305 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.642   842  1305 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.644   842   842 E WifiServerServiceExt: No p2p device connected
06-22 07:44:25.645  1852  2129 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
06-22 07:44:25.651   842  1305 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.651   842  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.651   842  1305 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.651   842  1305 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.651   842  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.651   842  1305 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.651  1852  1852 D WfdsService: isConnected: false
06-22 07:44:25.654  1852  1852 D WfdsService: GroupInfoAvailable: mGroupInfo is null
06-22 07:44:25.658  5976  5976 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-22 07:44:25.659  5976  5976 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
06-22 07:44:25.659  1852  2129 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
06-22 07:44:25.660  5976  5976 I wpa_supplicant: [LGE_PATCH]scan interval[0] = 2 sec.
06-22 07:44:25.660  5976  5976 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
06-22 07:44:25.660   842  1305 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.660   842  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.660   842  1305 D LGWifiP2pService: DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:25.660  1852  2129 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
06-22 07:44:25.661  1852  2129 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
06-22 07:44:25.662  1852  2129 D WfdsService: selectPreferredScanChannel [6]
06-22 07:44:25.662  1852  2129 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
,06-22 07:44:25.663  1852  6035 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
06-22 07:44:25.664  1852  2129 W WfdsService: DefaultState - msg [9441285] is not handled
06-22 07:44:25.687  5976  5976 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,06-22 07:44:25.690  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-22 07:44:25.691  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:25.691   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:25.691   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:25.691   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-22 07:44:25.693  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:25.694  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:25.694  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-22 07:44:25.694  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:25.694  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:25.694  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:25.694  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:25.694 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-22 07:44:25.694  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-22 07:44:25.697  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc45
06-22 07:44:25.697  2055  6028 D bt_hwcfg: hw_config_cback state=2
,06-22 07:44:25.702   842   842 D LocSvc_java: onReceive
06-22 07:44:25.702  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc18
06-22 07:44:25.702  2055  6028 D bt_hwcfg: hw_config_cback state=7
06-22 07:44:25.702  2055  6028 I bt_hwcfg: bt vendor lib: set UART baud 4000000
06-22 07:44:25.703  2055  6028 I bt_hwcfg: Setting local bd addr to F8:95:C7:87:85:54
06-22 07:44:25.704   842   842 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:25.704   842   842 D WifiServerServiceExt: setSupplicantStateSCANNING
06-22 07:44:25.722  5989  5989 D WiFiOffLoadUpdatePriority: remove1
06-22 07:44:25.722  5989  5989 V WiFiOffLoadSharedPrefsUtils: save remove
06-22 07:44:25.723  1758  1758 D GONS    : GONS isTestMode: false Country: 
,06-22 07:44:25.725  2055  6028 D bt_hwcfg: hw_config_cback opcode:0xfc01
06-22 07:44:25.725  2055  6028 D bt_hwcfg: hw_config_cback state=8
06-22 07:44:25.725  2055  6028 I bt_hwcfg: vendor lib fwcfg completed
06-22 07:44:25.725  2055  6028 I bt-btif : HC preload_cb 0 [0:SUCCESS 1:FAIL]
06-22 07:44:25.725  2055  6026 I bt-btu  : btu_task received preload complete event
06-22 07:44:25.734  2055  6026 I         : BTE_InitTraceLevels -- TRC_HCI,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_L2CAP,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_RFCOMM,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_OBEX,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_AVCT,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_AVDT,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_AVRC,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_AVDT_SCB,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_A2D,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_BNEP,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_BTM,2
,06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_GAP,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_PAN,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_SAP,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_SDP,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_GATT,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_SMP,2
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_BTAPP,3
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_BTIF,3
06-22 07:44:25.735  2055  6026 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,0
06-22 07:44:25.736  5989  5989 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
06-22 07:44:25.737  5989  5989 D WiFiOffLoadBroadcast: S: false, R: false
,06-22 07:44:25.740  5989  5989 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
06-22 07:44:25.740  5989  5989 D WiFiOffLoadUpdatePriority: connected SSID: null
06-22 07:44:25.740  5989  5989 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
06-22 07:44:25.742   842   859 D WifiServiceImplEx: addOrUpdateNetwork pid=5989, uid=1000, packageName=android.uid.system:1000
06-22 07:44:25.743   842   859 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
06-22 07:44:25.744   842  1306 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
06-22 07:44:25.806  5989  5989 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
,06-22 07:44:25.806  5989  5989 D WiFiOffLoadUpdatePriority: configuration updated: 0
06-22 07:44:25.808   842  1306 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
,06-22 07:44:25.818  5989  5989 D WiFiOffLoadUpdatePriority: configuration saved: true
06-22 07:44:25.865   842  1932 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6038 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,06-22 07:44:25.879  2055  6026 E bt-btif : bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,06-22 07:44:25.882  2055  6044 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
06-22 07:44:25.882  2055  2222 E bt-btif : warning : media task started media_task_refcnt 1 
06-22 07:44:25.883  2055  2222 E bt-btif : Calling BTA_HhEnable
06-22 07:44:25.883  2055  2222 E bt-btif : btif_storage_get_adapter_property service_mask:0x1201c8
06-22 07:44:25.883  2055  2222 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-22 07:44:25.883  2055  2222 D BluetoothAdapterProperties: Address is:F8:95:C7:87:85:54
06-22 07:44:25.884  2055  6026 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
06-22 07:44:25.884  2055  6026 W bt-smp  : Plain text(LSB ~ MSB) = 70 70 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-22 07:44:25.884  2055  6026 W bt-smp  : Encrypted text(LSB ~ MSB) = 7d 8b 6e ff 24 9b 00 3e 2a 5e 00 5f 76 91 46 41 
06-22 07:44:25.884  2055  6026 W bt-btm  : Stopping oneshot timer
06-22 07:44:25.892  2055  6044 D BT_PROF_AUDIO: created moving average (N=100)
06-22 07:44:25.892  2055  6044 D BT_PROF_AUDIO: reset rate average
06-22 07:44:25.892  2055  6044 W bt-btif : overflow 0, enter 0, exit 0
,06-22 07:44:25.894   842   842 D BluetoothManagerService: Bluetooth Adapter name changed to G3s-1
06-22 07:44:25.895  2055  2222 D BluetoothAdapterProperties: Name is: G3s-1
06-22 07:44:25.895   842   842 D BluetoothManagerService: Stored Bluetooth name: G3s-1
06-22 07:44:25.897  2055  2222 D BluetoothAdapterProperties: Scan Mode:20
06-22 07:44:25.897  2055  2222 D BluetoothAdapterProperties: Discoverable Timeout:120
06-22 07:44:25.899  2055  2222 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
06-22 07:44:25.899  2055  2222 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
06-22 07:44:25.899  2055  2222 E bt-btif : btif_sock_init: !radio_req && !rfc_init
06-22 07:44:25.899  2055  2222 I bt-btif : BTA_JvEnable
06-22 07:44:25.899  2055  2222 E bt-btif : btsock_vendor_hci_init: !vhci_init
06-22 07:44:25.899  5844  5844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-22 07:44:25.900  2055  2222 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
06-22 07:44:25.900  2055  2222 D bt-btif : init_hci_slots(L136): in
06-22 07:44:25.900  2055  2222 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
06-22 07:44:25.901  2055  2222 D IOP_DB_BT: db_open: db_open : handle 2691090396l, read 11046 bytes onto local cache
06-22 07:44:25.901  2055  2222 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
06-22 07:44:25.901  2055  2222 D IOP_DB_BT: db_query: result 1
06-22 07:44:25.901  2055  2222 I         : iop_db_open: iop_db_open status 0
06-22 07:44:25.901  2055  2222 E bt-btif : btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
06-22 07:44:25.901  2055  2222 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
06-22 07:44:25.901  2055  6026 I bt-btif : bta_pan_co_init
06-22 07:44:25.902  2055  2222 D bte_conf: Device ID record 1 : primary
06-22 07:44:25.902  2055  2222 D bte_conf:   vendorId            = 00c4
06-22 07:44:25.902  2055  2222 D bte_conf:   vendorIdSource      = 0001
06-22 07:44:25.902  2055  2222 D bte_conf:   product             = 13a1
06-22 07:44:25.902  2055  2222 D bte_conf:   version             = 1000
06-22 07:44:25.902  2055  2222 D bte_conf:   clientExecutableURL = 
06-22 07:44:25.902  2055  2222 D bte_conf:   serviceDescription  = 
06-22 07:44:25.902  2055  2222 D bte_conf:   documentationURL    = 
06-22 07:44:25.902  2055  2222 D bte_conf: bte_load_did_conf no section named DID2.
06-22 07:44:25.903  2055  2222 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
06-22 07:44:25.903  2055  2222 E bt-btif : btif_hf_upstreams_evt: wrong handle = 8240 
06-22 07:44:25.903  2055  2222 I bt-btif : HAL bt_op_callbacks->opc_state_cb
06-22 07:44:25.903  2055  2222 D BluetoothOPPServiceJni: opc_state_cb(L140):  opc_state_cb state:0
06-22 07:44:25.903  2055  2187 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
06-22 07:44:25.903  2055  2187 D BluetoothAdapterProperties: ScanMode =  20
06-22 07:44:25.903  2055  2187 D BluetoothAdapterProperties: State =  11
06-22 07:44:25.903  2055  2187 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
06-22 07:44:25.904  2055  2187 D BluetoothAdapterProperties: Setting state to 12
06-22 07:44:25.904  5989  5989 D BluetoothPermissionRequest: onReceive
06-22 07:44:25.904  2055  2187 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
06-22 07:44:25.904  2055  2187 D BluetoothAdapterService(55213335): updateAdapterState() - Broadcasting state to 1 receivers.
06-22 07:44:25.904  2055  2222 D OppService: onOpcStateChange()
06-22 07:44:25.904   842  1026 D BluetoothManagerService: Message: 60
06-22 07:44:25.904  2055  2222 I bt-btif : HAL bt_op_callbacks->ops_state_cb
06-22 07:44:25.904  2055  2222 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:0
06-22 07:44:25.904   842  1026 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
06-22 07:44:25.904  2055  2222 D OppService: onOpsStateChange() :0
06-22 0,7:44:25.904  2055  2222 I bt-btif : HAL bt_fts_callbacks->operation_cmpl_cb
06-22 07:44:25.904  2055  2222 D BluetoothFTPServiceJni: operation_cmpl_callback(L192):  oper:3 status:0
06-22 07:44:25.904   842  1026 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 6 receivers.
06-22 07:44:25.905  2055  2222 I BluetoothFTPService: onFtpServerEnabled: /storage
06-22 07:44:25.905  2055  2055 D OppService: Recieved MESSAGE_OPC_ENABLE
06-22 07:44:25.905  2055  2187 I BluetoothAdapterState: Entering On State
06-22 07:44:25.905  2055  2187 I BluetoothAdapterState: Entering On State from state = 11
06-22 07:44:25.906  2055  2187 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:25.906  2055  2187 D BluetoothAdapterService(55213335): isQuetModeEnabled() - Enabled = false
06-22 07:44:25.906  2055  2187 D BluetoothAdapterService(55213335): autoConnect() - Initiate auto connection on BT on...
06-22 07:44:25.906  2055  2187 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
06-22 07:44:25.906  2055  2055 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,06-22 07:44:25.906   842  1026 D BluetoothA2dp: onBluetoothStateChange: up=true
06-22 07:44:25.907  2055  2187 D LGBluetoothServiceAdapter: [BTUI] OnState
06-22 07:44:25.907  2055  2187 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3s-1
06-22 07:44:25.907  2055  2187 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3s-1
06-22 07:44:25.907  2055  2187 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:25.907  2055  2187 D BluetoothAdapterService(55213335): isQuetModeEnabled() - Enabled = false
06-22 07:44:25.907  2055  2187 D BluetoothAdapterService(55213335): autoConnect() - Initiate auto connection on BT on...
06-22 07:44:25.907  2055  2187 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
06-22 07:44:25.908  2055  2222 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
06-22 07:44:25.908  2055  2222 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-22 07:44:25.908  2055  2055 D OppService: Recieved MESSAGE_OPS_ENABLE
06-22 07:44:25.910  2055  2222 D BluetoothAdapterProperties: Scan Mode:21
06-22 07:44:25.910  2055  2222 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-22 07:44:25.910  2055  2222 D BluetoothAdapterProperties: Discoverable Timeout:120
06-22 07:44:25.910  1758  2319 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:44:25.911   842  1026 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:44:25.911  1758  1780 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:44:25.912  5989  5989 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
06-22 07:44:25.915  2055  2070 D BluetoothA2dp: onBluetoothStateChange: up=true
06-22 07:44:25.915  2055  5977 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:25.915  1758  1781 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:44:25.916  5844  5844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
06-22 07:44:25.916   842  1026 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
06-22 07:44:25.916   842  1026 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
06-22 07:44:25.921  2055  2070 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:25.922  1852  1852 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:25.922   842   842 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
06-22 07:44:25.922   842  1026 D BluetoothManagerService: Message: 40
06-22 07:44:25.922   842  1026 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,06-22 07:44:25.925  2055  2071 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:25.926  2055  2071 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:25.926  2055  6028 D bt_h4   : vendor lib postload completed
06-22 07:44:25.927  1852  2051 D LGBluetoothAPIService: Message: 1
06-22 07:44:25.928  5844  5844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-22 07:44:25.928  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:25.928  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-22 07:44:25.928  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-22 07:44:25.928  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-22 07:44:25.928  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:44:25.928  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:44:25.928  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:44:25.929  1852  2051 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
06-22 07:44:25.930  2055  2055 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:25.931  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
06-22 07:44:25.931  1374  1374 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
06-22 07:44:25.932  2055  2055 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:25.932  2055  2055 D BluetoothMapService: STATE_ON
06-22 07:44:25.932  2055  2055 V BluetoothMapService: Handler(): got msg=1
06-22 07:44:25.932  2055  2055 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
06-22 07:44:25.936  2055  2070 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:25.936  5844  5844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-22 07:44:25.948  2055  6060 D BluetoothMapMasInstance: MAS initSocket()
06-22 07:44:25.949  2055  6060 D BluetoothMapMasInstance:   masId = 00
06-22 07:44:25.949  2055  6060 D BluetoothMapMasInstance:   msgTypes = 0e
06-22 07:44:25.949  2055  6060 D BluetoothMapMasInstance:   masName = SMS/MMS
06-22 07:44:25.949  2055  6060 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,06-22 07:44:25.950  2055  2055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34a7d17
06-22 07:44:25.951  2055  2055 V BluetoothPbapService: Pbap Service onCreate
06-22 07:44:25.951  2055  2055 V BluetoothPbapService: Starting PBAP service
06-22 07:44:25.952   842   859 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:25.954  2055  2055 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:25.956  2055  2055 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
06-22 07:44:25.956  2055  2055 V BluetoothOppNotification: new notify threadi!
06-22 07:44:25.956  2055  2055 V BluetoothOppNotification: send delay message
06-22 07:44:25.956  2055  2055 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:25.958  2055  2055 V BluetoothPbapService: state: 12
06-22 07:44:25.960  2055  6063 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
06-22 07:44:25.961  2055  2055 V BluetoothPbapService: Handler(): got msg=1
06-22 07:44:25.962  2055  2055 V BluetoothPbapService: Pbap Service startRfcommSocketListener
06-22 07:44:25.965  1852  2051 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,06-22 07:44:25.967  2055  6060 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-22 07:44:25.968  2055  6060 I bt-btif : BTA_JvCreateRecordByUser
,06-22 07:44:25.968  2055  6060 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=0
06-22 07:44:25.969  2055  6026 I bt-btif : BTA_JvRfcommStartServer
06-22 07:44:25.969  2055  6060 V BluetoothMapMasInstance: Succeed to create listening socket 
06-22 07:44:25.969  2055  6060 D BluetoothMapMasInstance: Accepting socket connection...
06-22 07:44:25.970  2055  6065 V BluetoothPbapService: Pbap Service initSocket
06-22 07:44:25.970  2055  2055 D LGBluetoothAPIServer: [BTUI] onCreate()
06-22 07:44:25.970  2055  2055 D LGBluetoothAPIServer: [BTUI] onBind()
06-22 07:44:25.970   842  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:44:25.972  1852  1852 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
06-22 07:44:25.972  2055  6065 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-22 07:44:25.972  1852  2051 D LGBluetoothAPIService: Message: 100
06-22 07:44:25.972  1852  2051 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
06-22 07:44:25.973  2055  6063 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ec7142e on behalf of 
06-22 07:44:25.974  2055  6065 I bt-btif : BTA_JvCreateRecordByUser
06-22 07:44:25.974  2055  6026 I bt-btif : BTA_JvRfcommStartServer
06-22 07:44:25.974  2055  6063 V BluetoothOppNotification: mUpdateCompleteNotification = true
06-22 07:44:25.974  2055  6065 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=86 mFd=83
06-22 07:44:25.974  2055  6065 V BluetoothPbapService: Succeed to create listening socket 
06-22 07:44:25.974  2055  6065 V BluetoothPbapService: Accepting socket connection...
06-22 07:44:25.975   842  1026 D BluetoothManagerService: Message: 20
06-22 07:44:25.975   842  1026 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cf5bf79:true
06-22 07:44:25.976  2055  6063 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-22 07:44:25.981  2055  6063 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c7dcbcf on behalf of 
06-22 07:44:25.982  2055  6063 V BluetoothOppNotification: outbound: succ-0  fail-0
,06-22 07:44:25.985  2055  6063 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
06-22 07:44:25.986  2055  6063 V BluetoothOppNotification: outbound notification was removed.
06-22 07:44:25.986  2055  6063 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
06-22 07:44:25.987  2055  6063 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16c3095c on behalf of 
06-22 07:44:25.988  2055  6063 V BluetoothOppNotification: inbound: succ-0  fail-0
06-22 07:44:25.990  2055  6063 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
06-22 07:44:25.991  2055  6063 V BluetoothOppNotification: inbound notification was removed.
06-22 07:44:25.991  2055  6063 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
06-22 07:44:25.993  2055  6063 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@370d3465 on behalf of 
06-22 07:44:25.993  2055  2055 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-22 07:44:25.995  2055  2055 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,06-22 07:44:26.032   842  2009 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6067 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,06-22 07:44:26.042  6038  6038 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-22 07:44:26.063   842  2009 I ActivityManager: Killing 5446:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,06-22 07:44:26.193   842  1859 W libprocessgroup: failed to open /acct/uid_10069/pid_5446/cgroup.procs: No such file or directory
,06-22 07:44:26.214  5989  5989 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,06-22 07:44:26.216  5989  5989 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,06-22 07:44:26.216  5989  5989 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-22 07:44:26.217  5989  5989 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-22 07:44:26.218  5989  5989 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-22 07:44:26.235  6067  6067 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-22 07:44:26.240  5989  5989 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,06-22 07:44:26.240  5989  5989 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
06-22 07:44:26.240  5989  5989 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-22 07:44:26.240  5989  5989 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-22 07:44:26.240  5989  5989 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-22 07:44:26.241  5989  5989 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
06-22 07:44:26.241  5989  5989 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-22 07:44:26.244  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-22 07:44:26.252  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:26.255  6038  6038 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-22 07:44:26.263  6067  6067 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
,06-22 07:44:26.266   842   860 I ActivityManager: Killing 5463:com.lge.eula/1000 (adj 15): empty #11
06-22 07:44:26.363   842   859 W libprocessgroup: failed to open /acct/uid_1000/pid_5463/cgroup.procs: No such file or directory
,06-22 07:44:26.374  2351  2351 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
06-22 07:44:26.410   842   860 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6088 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,06-22 07:44:26.460  2351  2351 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,06-22 07:44:26.471  5989  5989 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-22 07:44:26.479  2055  2055 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-22 07:44:26.480  2055  2055 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:26.480  2055  2055 V BluetoothPbapReceiver: ***********state = 12
,06-22 07:44:26.491  2055  2071 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:26.493  5989  5989 D LocalBluetoothProfileManager: Adding local A2DP profile
,06-22 07:44:26.495   842  1026 D BluetoothManagerService: Message: 30
06-22 07:44:26.498  5989  5989 D LocalBluetoothProfileManager: Adding local HEADSET profile
06-22 07:44:26.501   842  1026 D BluetoothManagerService: Message: 30
06-22 07:44:26.508   842  1026 D BluetoothManagerService: Message: 30
,06-22 07:44:26.516   842  1026 D BluetoothManagerService: Message: 30
06-22 07:44:26.518  5989  5989 D LocalBluetoothProfileManager: Adding local MAP profile
06-22 07:44:26.521  5989  5989 D BluetoothMap: Create BluetoothMap proxy object
,06-22 07:44:26.522   842  1026 D BluetoothManagerService: Message: 30
,06-22 07:44:26.528   842  1026 D BluetoothManagerService: Message: 30
06-22 07:44:26.530  2055  2055 V BluetoothPbapService: Pbap Service onBind
06-22 07:44:26.530  5989  5989 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
06-22 07:44:26.535  5989  5989 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,06-22 07:44:26.541  5989  5989 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
06-22 07:44:26.547  5989  5989 D DockEventReceiver: finishStartingService: stopping service
,06-22 07:44:26.549  5989  5989 D BluetoothA2dp: Proxy object connected
06-22 07:44:26.550  5989  5989 D A2dpProfile: Bluetooth service connected
06-22 07:44:26.552  2055  2070 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:26.553  5989  5989 D BluetoothHeadset: Proxy object connected
06-22 07:44:26.554  5989  5989 D HeadsetProfile: Bluetooth service connected
06-22 07:44:26.554  2055  2071 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:26.556  5989  5989 D BluetoothInputDevice: Proxy object connected
06-22 07:44:26.557  5989  5989 D HidProfile: Bluetooth service connected
06-22 07:44:26.558  2055  5977 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:26.559  5989  5989 D BluetoothPan: BluetoothPAN Proxy object connected
,06-22 07:44:26.560  5989  5989 D PanProfile: Bluetooth service connected
,06-22 07:44:26.562  2055  2070 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:26.563  5989  5989 D BluetoothMap: Proxy object connected
06-22 07:44:26.564  5989  5989 D MapProfile: Bluetooth service connected
06-22 07:44:26.564  5989  5989 D BluetoothMap: getConnectedDevices()
06-22 07:44:26.565  2055  2071 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:26.565  2055  2070 V BluetoothMapService: getConnectedDevices()
06-22 07:44:26.566  5989  5989 D BluetoothPbap: Proxy object connected
06-22 07:44:26.566  5989  5989 D PbapServerProfile: Bluetooth service connected
06-22 07:44:26.568  5989  5989 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
06-22 07:44:26.568  6088  6088 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
06-22 07:44:26.569  6088  6088 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-22 07:44:26.572  5989  5989 D BluetoothPermissionRequest: onReceive
,06-22 07:44:26.574  5989  5989 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-22 07:44:26.575  5989  5989 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
06-22 07:44:26.578  6088  6088 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-22 07:44:26.580  2055  2055 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
06-22 07:44:26.582  6088  6088 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-22 07:44:26.586  2055  2055 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
06-22 07:44:26.586  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:26.593  2055  2055 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-22 07:44:26.595  2055  2055 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:44:26.596  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:26.598  6088  6112 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-22 07:44:26.601  6088  6112 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-22 07:44:26.601  2351  2351 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,06-22 07:44:26.610  6038  6038 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
06-22 07:44:26.614  2351  6116 D EasyUnlockInitService: Handling intent for initializer IntentService.
,06-22 07:44:26.615  6088  6111 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-22 07:44:26.615  2351  2351 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
06-22 07:44:26.617  6038  6038 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-22 07:44:26.617  6038  6038 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-22 07:44:26.663   842  1896 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6118 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,06-22 07:44:26.724   842  1896 I ActivityManager: Killing 5513:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,06-22 07:44:26.744  2351  2536 I art     : Explicit concurrent mark sweep GC freed 95857(5MB) AllocSpace objects, 48(892KB) LOS objects, 40% free, 15MB/25MB, paused 1.408ms total 122.190ms
,06-22 07:44:26.788   279  1051 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,06-22 07:44:26.790  5976  5976 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
06-22 07:44:26.817   842  2033 W libprocessgroup: failed to open /acct/uid_10086/pid_5513/cgroup.procs: No such file or directory
,06-22 07:44:26.827   842   842 D LocSvc_java: onReceive
06-22 07:44:26.834  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-22 07:44:26.834  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:26.834 DNS addrs= 0.0.0.0, 0.0.0.0, 
,06-22 07:44:26.834  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-22 07:44:26.835  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-22 07:44:26.835   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.835   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.835   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-22 07:44:26.836   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.836   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.836   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
06-22 07:44:26.836  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:26.836 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-22 07:44:26.836  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
06-22 07:44:26.837  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:26.838   842   842 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:26.838   842   842 D WifiServerServiceExt: setSupplicantStateASSOCIATING
06-22 07:44:26.844  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:26.844  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:26.844  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-22 07:44:26.845  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:26.845  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:26.845  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:26.845  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-22 07:44:26.851  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:26.851  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:26.851  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-22 07:44:26.851  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:26.852  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:26.852  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:26.877   279  1051 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,06-22 07:44:26.877   279  1051 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-22 07:44:26.877   279  1051 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-22 07:44:26.879  5976  5976 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
06-22 07:44:26.884  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-22 07:44:26.885   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.885   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.885  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:26.885 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-22 07:44:26.885   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
06-22 07:44:26.885  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
06-22 07:44:26.885  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:26.887  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-22 07:44:26.888  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:26.888 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-22 07:44:26.888   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.888  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
06-22 07:44:26.888   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.888   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
06-22 07:44:26.890  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:26.890  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:26.890  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-22 07:44:26.890  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:26.891  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:26.891  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:26.891  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:26.891   842   842 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:26.891   842   842 D WifiServerServiceExt: setSupplicantStateASSOCIATED
06-22 07:44:26.892   842   842 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:26.892   842   842 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,06-22 07:44:26.893  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:26.893  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:26.894  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-22 07:44:26.894  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:26.894  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:26.894  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:26.895  5591  5631 D fdn     : Opening database auth.proximity.permit_store...
06-22 07:44:26.900  6118  6118 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-22 07:44:26.904  2351  6116 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,06-22 07:44:26.906  5976  5976 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-22 07:44:26.906  5976  5976 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-22 07:44:26.908   279  1051 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-22 07:44:26.918   842  1306 I WifiServiceExtension: setVHTCapabilityType  : false
,06-22 07:44:26.939   842  1306 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
06-22 07:44:26.939   842  1306 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,06-22 07:44:26.943   842  1306 I WifiServiceExtension: setSecurityType  : 2
06-22 07:44:26.956  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-22 07:44:26.959  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-22 07:44:26.960  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:26.959 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-22 07:44:26.960  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
06-22 07:44:26.962   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.962   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.962   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
06-22 07:44:26.964   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.964   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:26.964  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-22 07:44:26.964   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
06-22 07:44:26.965  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:26.965 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-22 07:44:26.965  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
06-22 07:44:26.967  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:26.968  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:26.968  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-22 07:44:26.968  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:26.968  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:26.968  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:26.968  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-22 07:44:26.974  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,06-22 07:44:26.974  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:26.974  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-22 07:44:26.974  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:26.974  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:26.974  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:26.999   842  6135 D WifiExtManager: WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@39aa6f85
06-22 07:44:27.000   842  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
06-22 07:44:27.002   842  1313 D ConnectivityService: Got NetworkAgent Messenger
06-22 07:44:27.004   842  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
06-22 07:44:27.005   842  1313 D ConnectivityService: NetworkAgent connected
,06-22 07:44:27.017  1852  1875 D WifiServiceExtension: isInternetCheckAvailable return false
06-22 07:44:27.018   842  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-22 07:44:27.020   842  1026 D BluetoothManagerService: Message: 20
06-22 07:44:27.020   842  1026 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3eb2af94:true
06-22 07:44:27.027   842  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,06-22 07:44:27.031  2055  2070 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:27.033  2055  2071 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:27.037   279  1051 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
06-22 07:44:27.038   842  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.038   842  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.038   842  1024 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.038   842  1024 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.039   279  1058 D CommandListener: Setting iface cfg
06-22 07:44:27.044   842  6136 D DhcpStateMachine: StoppedState
,06-22 07:44:27.045   842  1306 E WifiStateMachine: Start Dhcp Watchdog 1
06-22 07:44:27.045   842  6136 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:27.045   842  6136 D DhcpStateMachine: WaitBeforeStartState
06-22 07:44:27.047   842   842 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:27.047   842   842 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,06-22 07:44:27.054  1907  1907 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
06-22 07:44:27.055  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-47 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:27.055 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-22 07:44:27.056  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:27.056  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:27.056  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
,06-22 07:44:27.063   842  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-22 07:44:27.088  5571  5571 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
06-22 07:44:27.088  5571  5571 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,06-22 07:44:27.099  5571  5571 V [BNRBootReceiver]: Boot Receiver Return
06-22 07:44:27.102  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:27.107  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:27.116  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,06-22 07:44:27.119  5989  5989 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
06-22 07:44:27.121  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
06-22 07:44:27.122  5989  5989 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
06-22 07:44:27.124  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-22 07:44:27.128  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-22 07:44:27.132   279  1051 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
06-22 07:44:27.133   842  1024 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.133   842  1024 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.142  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:27.147   842  1305 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@64c78d7 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:27.147   842  1305 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@64c78d7 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:27.147   842  6136 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,06-22 07:44:27.147  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:27.147   842  1306 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
06-22 07:44:27.147   842  1306 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-22 07:44:27.148   842  6136 D DhcpStateMachine: DHCP Start wake lock is acquired.
06-22 07:44:27.149   842  1306 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-22 07:44:27.149   842  1306 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
06-22 07:44:27.151   842   842 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-22 07:44:27.151   842   842 D WifiServerServiceExt: setSupplicantStateCOMPLETED
06-22 07:44:27.163  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:27.168  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:27.176  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:27.181  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:27.189  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:27.194  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:27.202  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:27.213  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:27.298   842  1893 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6142 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:27.311  6118  6118 V LGMDMManager: Create singleton instance
,06-22 07:44:27.323   310   310 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 25.129ms
,06-22 07:44:27.347   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.252ms
,06-22 07:44:27.352   842  6136 D DhcpStateMachine: DHCPV4 request on wlan0
06-22 07:44:27.352   842  6136 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
06-22 07:44:27.352   842  6136 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,06-22 07:44:27.371   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.624ms
06-22 07:44:27.374  6159  6159 I dhcpcd  : version 5.5.6 starting
06-22 07:44:27.376  6159  6159 E dhcpcd  : get_duid: Read-only file system
,06-22 07:44:27.400  6118  6118 I AudioManager: getMode name:com.lge.qremote
,06-22 07:44:27.408  6142  6142 D UEI.SmartControl: Quickset Services start...
,06-22 07:44:27.415  6142  6142 I UEI.SmartControl: Manufacture = LGE
,06-22 07:44:27.419  6142  6142 D UEI.SmartControl: File observer start...
06-22 07:44:27.420  6142  6142 E UEI.SmartControl: IR Port is disabled: false
06-22 07:44:27.421  6142  6142 D UEI.SmartControl: Starting file observer...
06-22 07:44:27.421  6142  6142 D UEI.SmartControl: Extracting JNI libs...
06-22 07:44:27.422  6142  6142 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
06-22 07:44:27.452  6159  6159 I dhcpcd  : wlan0: rebinding lease of 192.168.1.103
,06-22 07:44:27.502  6159  6159 I dhcpcd  : wlan0: acknowledged 192.168.1.103 from 192.168.1.1
,06-22 07:44:27.534  6142  6142 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,06-22 07:44:27.535  6142  6142 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
06-22 07:44:27.535  6142  6142 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
06-22 07:44:27.552  6159  6159 I dhcpcd  : wlan0: leased 192.168.1.103 for 172800 seconds
06-22 07:44:27.552   279  1051 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
06-22 07:44:27.554   842  1024 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.554   842  1024 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:27.557   842  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-22 07:44:27.574  6142  6142 I UEI.SmartControl: --- Selecting new region: 2
06-22 07:44:27.574  6142  6142 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,06-22 07:44:27.582  6142  6142 D UEI.SmartControl: Platform has CIR...
06-22 07:44:27.584  6142  6142 D UEI.SmartControl: NO CIR support, need to check package...
06-22 07:44:27.585  6142  6142 I UEI.SmartControl: Model: LG-D722 uses JNI
,06-22 07:44:27.588  6142  6142 D UEI.SmartControl: QS Service created
06-22 07:44:27.598   284  1292 V AudioFlinger: thread 0xb56eb000 type 0 TID 1292 going to sleep
,06-22 07:44:27.602   284  1288 V AudioFlinger: thread 0xb5651000 type 0 TID 1288 going to sleep
06-22 07:44:27.603   284  1294 V AudioFlinger: thread 0xb5735000 type 0 TID 1294 going to sleep
06-22 07:44:27.612  6142  6142 E UEI.SmartControl: QS start get config
,06-22 07:44:27.672  6142  6142 D UEI.SmartControl: Loading JNI Libs...
06-22 07:44:27.674  6142  6142 D UEI.SmartControl:  configuring local db...
,06-22 07:44:27.755   842  6136 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.755   842  6136 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.755   842  6136 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.755   842  6136 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.756   842  6136 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.756   842  6136 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.756   842  6136 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.756   842  6136 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.756   842  6136 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,06-22 07:44:27.759   842  6136 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
06-22 07:44:27.760   842  6136 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-22 07:44:27.760   842  6136 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.760   842  6136 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.760   842  6136 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.103
06-22 07:44:27.760   842  6136 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.103/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
06-22 07:44:27.760   842  6136 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-22 07:44:27.760   842  6136 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
06-22 07:44:27.761   842  6136 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
06-22 07:44:27.761   842  6136 D DhcpStateMachine: RunningState
06-22 07:44:27.762   842  1305 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:27.762   842  1305 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:27.772   842  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-22 07:44:27.772   842  1306 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
06-22 07:44:27.776   842  1313 D ConnectivityService: ignoring duplicate network state non-change
,06-22 07:44:27.779  1852  1877 D WifiServiceExtension: isInternetCheckAvailable return false
06-22 07:44:27.780  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-22 07:44:27.781   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:27.781   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:27.781   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
06-22 07:44:27.786  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-22 07:44:27.786   842  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
06-22 07:44:27.786  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-22 07:44:27.787   842  1313 D ConnectivityService: Adding iface wlan0 to network 100
06-22 07:44:27.788   842  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,06-22 07:44:27.792  1852  1875 D WifiServiceExtension: isInternetCheckAvailable return false
06-22 07:44:27.805   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:44:27.805   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:27.806   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
06-22 07:44:27.815   842   842 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
06-22 07:44:27.818  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-47 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.103 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:27.817 DNS addrs= 192.168.1.1, 0.0.0.0, 
06-22 07:44:27.818  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.103 ipV6Addr=
06-22 07:44:27.818  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,06-22 07:44:27.823  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-47 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.103 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:27.823 DNS addrs= 192.168.1.1, 0.0.0.0, 
06-22 07:44:27.823  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.103 ipV6Addr=
06-22 07:44:27.824  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:27.824  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-22 07:44:27.824  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:27.824  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-22 07:44:27.825  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:27.825  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:27.825  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:27.825  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-47 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.103 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:27.825 DNS addrs= 192.168.1.1, 0.0.0.0, 
06-22 07:44:27.825  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.103 ipV6Addr=
06-22 07:44:27.826  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-22 07:44:27.830   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:27.830   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:27.830   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
06-22 07:44:27.830   842   842 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
06-22 07:44:27.832   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:27.832   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:27.832   842   842 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
06-22 07:44:27.832  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-22 07:44:27.834  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-47 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.103 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:27.834 DNS addrs= 192.168.1.1, 0.0.0.0, 
06-22 07:44:27.834  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.103 ipV6Addr=
06-22 07:44:27.836   842  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
06-22 07:44:27.838   842  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
06-22 07:44:27.839   279  1058 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-22 07:44:27.839   279  1058 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.839   279  1058 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-22 07:44:27.839   279  1058 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.840   842  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
06-22 07:44:27.840  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-22 07:44:27.840  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:27.840  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-22 07:44:27.840  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:27.840  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:27.840  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:27.842   279  1058 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-22 07:44:27.842   279  1058 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.843  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-22 07:44:27.849   279  1058 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-22 07:44:27.849  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
06-22 07:44:27.849   279  1058 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.850   842  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
06-22 07:44:27.850   279  1058 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-22 07:44:27.850   279  1058 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.852   842  1313 D ConnectivityService: addLocalRoutetoDefaultNetwork
06-22 07:44:27.852   842  1313 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
06-22 07:44:27.852   842  1313 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
06-22 07:44:27.853   842  1313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.853   842  1313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.855   279  1058 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
06-22 07:44:27.855   279  1058 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.856  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-22 07:44:27.856  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,06-22 07:44:27.856  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
06-22 07:44:27.861  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:27.862  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:27.862  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:27.863  1374  1374 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
06-22 07:44:27.863   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
06-22 07:44:27.866   842  1313 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
06-22 07:44:27.867   842  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,06-22 07:44:27.869   842  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
06-22 07:44:27.869  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-22 07:44:27.869  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:27.869   842  6135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:27.869   842  6135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
06-22 07:44:27.869   842  6135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:44:27.870   842  1313 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-22 07:44:27.870   842  1313 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-22 07:44:27.870   842  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:27.870   842  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-22 07:44:27.870  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
06-22 07:44:27.870   842  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:27.870  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-22 07:44:27.871   842  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
06-22 07:44:27.872  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-22 07:44:27.872  1374  1374 I [SystemUI]QuickSettingsHandler: Remote
06-22 07:44:27.873   842  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:27.873   842  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
06-22 07:44:27.873   842  1313 D ConnectivityService: currentScore = 0, newScore = 20
06-22 07:44:27.873   842  1313 D ConnectivityService:    accepting network in place of null
06-22 07:44:27.873   842  1313 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:27.874   842  1306 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-22 07:44:27.874   842  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:44:27.875   842  1313 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
06-22 07:44:27.877  1758  1758 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:27.878  1758  1758 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
06-22 07:44:27.880   842  1313 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.103/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,06-22 07:44:27.881   842  1313 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
06-22 07:44:27.885   842  6135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
06-22 07:44:27.886   842  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-22 07:44:27.887   842  6191 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
06-22 07:44:27.888   842  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.888   842  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:27.889   842  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:27.889  1907  1907 W QCNEJ   : |CORE| No family connected
06-22 07:44:27.889   842  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:27.889  1907  1907 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
06-22 07:44:27.889   842  1026 D Tethering: MasterInitialState.processMessage what=3
06-22 07:44:27.889   842  1313 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:27.889   279  1053 E BandwidthController: [LG DATA] No such appUid: 1000
06-22 07:44:27.889   279  1053 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-22 07:44:27.890   279  6192 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
06-22 07:44:27.890   842  1313 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
06-22 07:44:27.890   279  6192 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:27.890   279  6192 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=0
06-22 07:44:27.890   842  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.103/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
06-22 07:44:27.891   279  6192 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:27.891   279  6192 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:27.892   842  1313 D ConnectivityService: validation of new default Network = false
06-22 07:44:27.892   842  1313 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
06-22 07:44:27.892   842  1313 D DSQN    : enableDataServiceNotify 
06-22 07:44:27.892   842  1313 D DSQN    : start dsqn bin
,06-22 07:44:27.894   842  1024 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
06-22 07:44:27.895  1907  1907 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
06-22 07:44:27.909   842  1304 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,06-22 07:44:27.921  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-22 07:44:27.927  1374  1374 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
06-22 07:44:27.930  1374  1374 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
06-22 07:44:27.932   842  1313 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-22 07:44:27.932   842  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:27.932   842  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:27.933  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-22 07:44:27.933  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:27.933  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
,06-22 07:44:27.936  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-22 07:44:27.936  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:27.936  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
06-22 07:44:27.938   842  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:27.939   842  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:27.939   842  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:27.940  5591  5955 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-22 07:44:27.942  6193  6193 I DSQN    : DSQN samuel.seo ver 141203
06-22 07:44:27.942  6193  6193 E DSQN    : DSQN sock connect success to lgdatalistenerd
06-22 07:44:27.943  6193  6193 I DSQN    : created command queue thread
06-22 07:44:27.943  6193  6193 I DSQN    : Interface wlan0 address 192.168.1.103 0xc0a80167
06-22 07:44:27.943  6193  6193 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a80167
06-22 07:44:27.943  1374  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-22 07:44:27.948  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:27.960  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-22 07:44:27.964  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-22 07:44:27.970  6038  6038 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,06-22 07:44:27.976  6038  6038 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
06-22 07:44:27.984  5989  5989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-22 07:44:27.988  5989  5989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-22 07:44:27.994  6038  6038 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
06-22 07:44:27.995  6038  6038 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
06-22 07:44:28.049  6142  6142 D UEI.SmartControl:  ---- Has DB8: true
,06-22 07:44:28.057  6142  6142 D UEI.SmartControl: QS start statue = true Error code = 0
06-22 07:44:28.058  6142  6142 D UEI.SmartControl: QS version = v2.7.11.1_RC1
06-22 07:44:28.059  6142  6142 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
06-22 07:44:28.062  6142  6142 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,06-22 07:44:28.184  6142  6142 W irrc_jni: IRRCPlayer_nativeInit ++ 
06-22 07:44:28.184  6142  6142 D irrcClient: IrrcClient ++ 
06-22 07:44:28.184  6142  6142 D irrcClient: getIrrcService ++ 
,06-22 07:44:28.185  6142  6142 D irrcClient: getIrrcService -- 
06-22 07:44:28.185  6142  6142 D irrcClient: IrrcClient -- 
06-22 07:44:28.185  6142  6142 W irrc_jni: IRRCPlayer_nativeInit -- 
06-22 07:44:28.192  6142  6142 D UEI.SmartControl: Services init done
06-22 07:44:28.193  6142  6197 I UEI.SmartControl: Device manager: loading config....
06-22 07:44:28.196  6142  6142 D UEI.SmartControl: QS Service init finished
06-22 07:44:28.198  6142  6197 D UEI.SmartControl: Config is loaded...
06-22 07:44:28.198  6142  6142 D UEI.SmartControl: QS Service version name: 0.1.73
06-22 07:44:28.198  6142  6142 D UEI.SmartControl: QS Service version code: 1073
06-22 07:44:28.199  6142  6142 D UEI.SmartControl: Service requested: Control
,06-22 07:44:28.203  6142  6142 D UEI.SmartControl: Internal service binding...
06-22 07:44:28.204  6142  6157 D UEI.SmartControl: -----IControl: 11
06-22 07:44:28.205  6142  6157 D UEI.SmartControl: Caller: com.lge.qremote
06-22 07:44:28.206  6142  6157 D UEI.SmartControl: ------------ IControl registerCallback...
06-22 07:44:28.206  6142  6157 I UEI.SmartControl: Registering callback...
06-22 07:44:28.207  6142  6158 D UEI.SmartControl: -----IControl: 19
06-22 07:44:28.208  6142  6158 D UEI.SmartControl: Caller: com.lge.qremote
06-22 07:44:28.209  6142  6158 I UEI.SmartControl: Registering Services Ready callback...
06-22 07:44:28.210  6142  6158 I UEI.SmartControl: Notify client services are ready...
06-22 07:44:28.213  6142  6157 D UEI.SmartControl: -----IControl: 8
,06-22 07:44:28.214  6142  6157 D UEI.SmartControl: Caller: com.lge.qremote
,06-22 07:44:28.219  6118  6118 I AudioManager: getMode name:com.lge.qremote
06-22 07:44:28.224   842  2596 I ActivityManager: Killing 5742:com.google.android.talk/u0a61 (adj 15): empty #11
,06-22 07:44:28.242  6142  6196 D UEI.SmartControl:  ----- QS SDK is ready!!!
06-22 07:44:28.243  6142  6196 I UEI.SmartControl: Notify AllClients services are ready: 0
,06-22 07:44:28.312   842  2033 W libprocessgroup: failed to open /acct/uid_10061/pid_5742/cgroup.procs: No such file or directory
,06-22 07:44:28.318  6118  6118 I AudioManager: getMode name:com.lge.qremote
,06-22 07:44:28.334  6118  6118 I AudioManager: getMode name:com.lge.qremote
,06-22 07:44:28.388   842  6191 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
,06-22 07:44:28.388   842  6191 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:28.388   842  6191 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:28.388   842  6191 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
06-22 07:44:28.389   842  6191 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:28.390   279  1053 E BandwidthController: [LG DATA] No such appUid: 1000
06-22 07:44:28.390   279  1053 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-22 07:44:28.390   279  6201 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
06-22 07:44:28.390   279  6201 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:28.391   279  6201 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:28.391   279  6201 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:28.503   279  6201 D libc-netbsd: res_queryN name = xxxxx succeed
,06-22 07:44:28.506   842  6191 I System.out: propertyValue:false
06-22 07:44:28.506   842  6191 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
06-22 07:44:28.511   842  6135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-22 07:44:28.543   842  6135 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:28.543   842  6135 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:28.550  6193  6194 I DSQN    : first global connection report this to start monitoring at DSQM.
06-22 07:44:28.550  6193  6194 I DSQN    : restart monitoring
06-22 07:44:28.551  6193  6209 I DSQN    : dsqn report finish
06-22 07:44:28.551   279  1057 D LGDataListener: argv[0]=dsqncommand
06-22 07:44:28.551   279  1057 D LGDataListener: argv[1]=wlan0
06-22 07:44:28.551   279  1057 D LGDataListener: argv[2]=1
06-22 07:44:28.551   279  1057 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
06-22 07:44:28.553   842  1024 D DSQN    : DSQM DsqnNotification wlan0  1
06-22 07:44:28.553   842  1024 D DSQN    : start to monitor internet connection
06-22 07:44:28.559   842  6135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 22 Jun 2016 05:44:29 GMT], X-Android-Received-Millis=[1466574268558], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1466574268550]}
06-22 07:44:28.559   842  6135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-22 07:44:28.561  1852  1875 D WifiServiceExtension: isInternetCheckAvailable return false
,06-22 07:44:28.561   842  6135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
06-22 07:44:28.562   842  6135 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
06-22 07:44:28.563   842   842 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
06-22 07:44:28.563   842  1313 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
06-22 07:44:28.563   842  1313 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-22 07:44:28.564   842  1313 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:44:28.564   842  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:28.564   842  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-22 07:44:28.564   842  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:28.564   842  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
06-22 07:44:28.564   842  1313 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
06-22 07:44:28.564   842  1313 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-22 07:44:28.564   842  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:28.564   842  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:28.564   842  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:28.565   842  1306 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
06-22 07:44:28.565  1374  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-22 07:44:28.566   842  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:28.566   842  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:28.566  5591  5955 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-22 07:44:28.566   842  1313 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:28.567   842  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
06-22 07:44:28.567   842  1306 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:28.567   842  1306 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:44:28.567  1758  1758 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:28.568  1758  1758 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
06-22 07:44:28.581  1374  1374 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,06-22 07:44:28.597  1374  1374 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
06-22 07:44:28.598  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-22 07:44:28.598  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:28.599  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
06-22 07:44:28.600  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-22 07:44:28.600  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:28.600  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
06-22 07:44:28.837  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-22 07:44:28.837  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:28.837  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,06-22 07:44:28.902   279  1051 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,06-22 07:44:28.905   842  1024 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:28.905   842  1024 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:28.908   842  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
06-22 07:44:28.908   842  1313 D ConnectivityService: identical MTU - not setting
06-22 07:44:28.908   842  1313 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
06-22 07:44:28.908   842  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
06-22 07:44:28.909   842  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:28.909   842  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:28.909   842  1313 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:44:28.909   842  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:28.910  1374  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-22 07:44:28.911   842  1313 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:44:28.911   842  1313 D ConnectivityService: Wi-Fi IP changed. Lp difference / No Route difference
06-22 07:44:28.911   842  1313 D DSQN    : enableDataServiceNotify 
06-22 07:44:28.911   842  1313 D DSQN    : start dsqn bin
06-22 07:44:28.911  5591  5955 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-22 07:44:28.914  1907  1907 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
06-22 07:44:28.917  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-47 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.103 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:28.916 DNS addrs= 192.168.1.1, 0.0.0.0, 
,06-22 07:44:28.950   842  1313 D DSQN    : dsqn is running restart
,06-22 07:44:28.980  6210  6210 I DSQN    : DSQN samuel.seo ver 141203
06-22 07:44:28.982  6210  6210 E DSQN    : DSQN sock connect success to lgdatalistenerd
06-22 07:44:28.982  6210  6210 I DSQN    : created command queue thread
06-22 07:44:28.983  6210  6210 I DSQN    : Interface wlan0 address 192.168.1.103 0xc0a80167
06-22 07:44:28.983  6210  6210 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a80167
,06-22 07:44:29.903   842  1037 I PowerManagerService: ALS enabled for SRE
,06-22 07:44:29.903   842  1037 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (25551 ms ago)
06-22 07:44:29.929   842  1347 D qdlights: set_light_backlight: 254
,06-22 07:44:29.942   842  1347 D qdlights: set_light_backlight: 251
,06-22 07:44:29.959   842  1347 D qdlights: set_light_backlight: 247
,06-22 07:44:29.976   842  1347 D qdlights: set_light_backlight: 244
,06-22 07:44:29.992   842  1347 D qdlights: set_light_backlight: 241
,06-22 07:44:30.009   842  1347 D qdlights: set_light_backlight: 237
,06-22 07:44:30.026   842  1347 D qdlights: set_light_backlight: 234
,06-22 07:44:30.042   842  1347 D qdlights: set_light_backlight: 231
,06-22 07:44:30.059   842  1347 D qdlights: set_light_backlight: 227
,06-22 07:44:30.073  1907  1907 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,06-22 07:44:30.076  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-46 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.103 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-06-22 07:44:30.076 DNS addrs= 192.168.1.1, 0.0.0.0, 
06-22 07:44:30.079  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-22 07:44:30.079  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:30.079  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
06-22 07:44:30.080   842  1347 D qdlights: set_light_backlight: 224
06-22 07:44:30.093   842  1347 D qdlights: set_light_backlight: 221
,06-22 07:44:30.109   842  1347 D qdlights: set_light_backlight: 217
,06-22 07:44:30.126   842  1347 D qdlights: set_light_backlight: 214
,06-22 07:44:30.143   842  1347 D qdlights: set_light_backlight: 211
,06-22 07:44:30.159   842  1347 D qdlights: set_light_backlight: 207
,06-22 07:44:30.176   842  1347 D qdlights: set_light_backlight: 204
,06-22 07:44:30.192   842  1347 D qdlights: set_light_backlight: 201
,06-22 07:44:30.209   842  1347 D qdlights: set_light_backlight: 197
,06-22 07:44:30.226   842  1347 D qdlights: set_light_backlight: 194
,06-22 07:44:30.243   842  1347 D qdlights: set_light_backlight: 191
,06-22 07:44:30.259   842  1347 D qdlights: set_light_backlight: 187
,06-22 07:44:30.276   842  1347 D qdlights: set_light_backlight: 184
,06-22 07:44:30.292   842  1347 D qdlights: set_light_backlight: 181
,06-22 07:44:30.309   842  1347 D qdlights: set_light_backlight: 177
,06-22 07:44:30.326   842  1347 D qdlights: set_light_backlight: 174
,06-22 07:44:30.342   842  1347 D qdlights: set_light_backlight: 171
,06-22 07:44:30.359   842  1347 D qdlights: set_light_backlight: 167
,06-22 07:44:30.376   842  1347 D qdlights: set_light_backlight: 164
,06-22 07:44:30.392   842  1347 D qdlights: set_light_backlight: 161
,06-22 07:44:30.409   842  1347 D qdlights: set_light_backlight: 157
,06-22 07:44:30.426   842  1347 D qdlights: set_light_backlight: 154
,06-22 07:44:30.442   842  1347 D qdlights: set_light_backlight: 151
,06-22 07:44:30.459   842  1347 D qdlights: set_light_backlight: 147
,06-22 07:44:30.476   842  1347 D qdlights: set_light_backlight: 144
,06-22 07:44:30.492   842  1347 D qdlights: set_light_backlight: 141
,06-22 07:44:30.509   842  1347 D qdlights: set_light_backlight: 137
,06-22 07:44:30.526   842  1347 D qdlights: set_light_backlight: 134
,06-22 07:44:30.542   842  1347 D qdlights: set_light_backlight: 131
,06-22 07:44:30.559   842  1347 D qdlights: set_light_backlight: 127
,06-22 07:44:30.576   842  1347 D qdlights: set_light_backlight: 124
,06-22 07:44:30.592   842  1347 D qdlights: set_light_backlight: 121
,06-22 07:44:30.609   842  1347 D qdlights: set_light_backlight: 117
,06-22 07:44:30.626   842  1347 D qdlights: set_light_backlight: 114
,06-22 07:44:30.642   842  1347 D qdlights: set_light_backlight: 111
,06-22 07:44:30.659   842  1347 D qdlights: set_light_backlight: 107
,06-22 07:44:30.676   842  1347 D qdlights: set_light_backlight: 104
,06-22 07:44:30.692   842  1347 D qdlights: set_light_backlight: 101
,06-22 07:44:30.709   842  1347 D qdlights: set_light_backlight: 97
,06-22 07:44:30.726   842  1347 D qdlights: set_light_backlight: 94
,06-22 07:44:30.742   842  1347 D qdlights: set_light_backlight: 91
,06-22 07:44:30.759   842  1347 D qdlights: set_light_backlight: 87
,06-22 07:44:30.776   842  1347 D qdlights: set_light_backlight: 84
,06-22 07:44:30.792   842  1347 D qdlights: set_light_backlight: 81
,06-22 07:44:30.809   842  1347 D qdlights: set_light_backlight: 77
,06-22 07:44:30.817   842  1307 V WifiInternetCheck: Single check msg out of sync, ignoring.
06-22 07:44:30.826   842  1347 D qdlights: set_light_backlight: 74
,06-22 07:44:30.838  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,06-22 07:44:30.838  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:30.838  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
06-22 07:44:30.843   842  1347 D qdlights: set_light_backlight: 71
06-22 07:44:30.859   842  1347 D qdlights: set_light_backlight: 67
,06-22 07:44:30.876   842  1347 D qdlights: set_light_backlight: 64
,06-22 07:44:30.892   842  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:30.893   842  1347 D qdlights: set_light_backlight: 61
,06-22 07:44:30.900  1374  1374 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
06-22 07:44:30.907  2055  5977 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:30.908  5844  5844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-22 07:44:30.908  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:30.908  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-22 07:44:30.908  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-22 07:44:30.908  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-22 07:44:30.908  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-22 07:44:30.908  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-22 07:44:30.908  5844  5844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-22 07:44:30.909   842  1347 D qdlights: set_light_backlight: 57
06-22 07:44:30.911   842   942 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:30.912  2055  5977 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:30.913  5844  5844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
06-22 07:44:30.933   842  1347 D qdlights: set_light_backlight: 54
,06-22 07:44:30.943   842  1347 D qdlights: set_light_backlight: 51
06-22 07:44:30.945   842   842 D LocSvc_java: onReceive
06-22 07:44:30.946   842   842 D LocSvc_java: got connectivity action
,06-22 07:44:30.950   842  1736 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:30.950   842  1736 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:30.950   842  1736 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:30.950   842  1736 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:30.950   279  1053 E BandwidthController: [LG DATA] No such appUid: 1000
06-22 07:44:30.950   279  1053 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-22 07:44:30.952   279  6215 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:30.952   279  6215 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:30.952   279  6215 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:30.953   279  6215 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:30.953   842   970 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6213 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:30.954   842   842 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
06-22 07:44:30.954   842   842 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
06-22 07:44:30.959   842  1347 D qdlights: set_light_backlight: 47
,06-22 07:44:30.957   842   942 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:44:30.962   842   842 D LocSvc_java: getAGpsConnectionInfo connType - 4
06-22 07:44:30.977   842   842 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
06-22 07:44:30.977   842   842 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
06-22 07:44:30.977   842   842 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
,06-22 07:44:30.980   842  1347 D qdlights: set_light_backlight: 44
06-22 07:44:30.988   842  6223 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:30.988   842  6223 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:30.988   842  6223 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:30.988   842  6223 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:30.989   279  1053 E BandwidthController: [LG DATA] No such appUid: 1000
06-22 07:44:30.989   279  1053 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-22 07:44:30.990   279  6229 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:30.990   279  6229 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:30.990   279  6229 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:30.991   279  6229 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-22 07:44:30.993   842  1347 D qdlights: set_light_backlight: 41
06-22 07:44:30.999   279  6215 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:30.999   279  6229 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:31.000   842  1736 I System.out: propertyValue:false
06-22 07:44:31.000   842  6223 I System.out: propertyValue:false
06-22 07:44:31.010   842  1347 D qdlights: set_light_backlight: 37
,06-22 07:44:31.015   842  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:31.015   842  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:31.026   842  1347 D qdlights: set_light_backlight: 34
,06-22 07:44:31.043   842  1347 D qdlights: set_light_backlight: 31
,06-22 07:44:31.050   842  6223 D LocSvc_java: NTP server returned: 1466574271696 (Wed Jun 22 07:44:31 GMT+02:00 2016) reference: 146675 certainty: 12 system time offset: 657
06-22 07:44:31.057   842  6223 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
,06-22 07:44:31.063   842  1347 D qdlights: set_light_backlight: 27
06-22 07:44:31.063   842  1736 D AlarmManagerService: Setting time of day to sec=1466574271
06-22 07:44:31.698   842  1736 W AlarmManagerService: Unable to set rtc to 1466574271: Invalid argument
06-22 07:44:31.710   842  1347 D qdlights: set_light_backlight: 24
,06-22 07:44:31.723  1374  1374 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
,06-22 07:44:31.727   842  1347 D qdlights: set_light_backlight: 21
06-22 07:44:31.734  2026  2026 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
06-22 07:44:31.738  2801  2801 D WeatherService: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 7:44:31
,06-22 07:44:31.739  2801  2801 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
06-22 07:44:31.746   842  1347 D qdlights: set_light_backlight: 17
06-22 07:44:31.749  1374  1374 I LgeClockWidgetControlView: time changed, timezoneChanged : false
06-22 07:44:31.757  2801  2801 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-22 07:44:31.757  2801  2801 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
06-22 07:44:31.757  2801  2801 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
06-22 07:44:31.757  2801  2801 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
06-22 07:44:31.758  2801  2801 D WeatherTheme: 2 : Fixed theme : optimus
,06-22 07:44:31.761   842  1347 D qdlights: set_light_backlight: 14
06-22 07:44:31.772  2801  2801 D WeatherReflect: 2 : Map key string is -2
,06-22 07:44:31.775   842   970 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=6244 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
06-22 07:44:31.776   842   860 W ActivityManager: getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
06-22 07:44:31.777  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:44:31.778   842  1347 D qdlights: set_light_backlight: 11
06-22 07:44:31.799   842   942 E GpsLocationProvider: No APN found to select.
,06-22 07:44:31.806  1945  1945 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=22 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
06-22 07:44:31.821  1945  1945 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 22
,06-22 07:44:31.836  2801  2801 D lim     : 2 : time = 07:44
,06-22 07:44:31.840  2801  2801 I WeatherReflect: Model Name : LG-D722
06-22 07:44:31.840  2801  2801 D WeatherTheme: 2 : exactly same view!
06-22 07:44:31.840  2801  2801 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
06-22 07:44:31.841  2801  2801 D WeatherService: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 7:44:31
06-22 07:44:31.844   842  1347 D qdlights: set_light_backlight: 10
06-22 07:44:31.857  1945  1945 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 22
,06-22 07:44:31.882  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,06-22 07:44:31.965  6244  6244 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:44:31.965  6244  6244 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-22 07:44:31.966  6244  6244 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,06-22 07:44:32.027   842   942 I ActivityManager: Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6264 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,06-22 07:44:32.048  2351  2351 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-22 07:44:32.103  2351  6279 I PhenotypeConfigurator: Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,06-22 07:44:32.157   842  6286 D LgeGpsConstants: Can't find 'ext_gps.conf'!!
06-22 07:44:32.158   842  6286 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:32.158   842  6286 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:32.158   842  6286 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:32.158   842  6286 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:32.159   279  1053 E BandwidthController: [LG DATA] No such appUid: 1000
06-22 07:44:32.159   279  1053 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-22 07:44:32.159   279  6287 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:32.159   279  6287 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:32.160   279  6287 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:32.160   279  6287 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-22 07:44:32.176  2351  2351 D WearableService: callingUid 10006, callindPid: 2351
,06-22 07:44:32.198  6264  6264 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:44:32.198  6264  6264 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-22 07:44:32.198  6264  6264 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,06-22 07:44:32.221   279  6287 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:32.221   842  6286 I System.out: propertyValue:false
,06-22 07:44:32.249  6213  6213 I MusicStore: Database version: 120
,06-22 07:44:32.253   842  6286 D LgeGpsLocationProvider: NTP server: europe.pool.ntp.org
06-22 07:44:32.254   842  6286 D LgeGpsLocationProvider: NTP server returned: 1466574272280 (Wed Jun 22 07:44:32 GMT+02:00 2016) reference: 147255 certainty: 16 system time offset: 27
,06-22 07:44:32.286   842  1859 I ActivityManager: Process com.android.vending (pid 4913) has died
,06-22 07:44:32.322  6244  6244 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,06-22 07:44:32.350  6244  6244 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,06-22 07:44:32.440   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:32.440   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-22 07:44:32.440   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:32.441  6213  6213 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-22 07:44:32.473  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-22 07:44:32.473  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:32.473  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,06-22 07:44:32.489  6264  6264 I AppConfig: Total System Memory = 906309632
,06-22 07:44:32.499  6264  6264 I GalleryUtils: Application Heap = 96 MB
06-22 07:44:32.500   842   942 I NotificationManager: android: cancelAsUser(-1816247584) by android
06-22 07:44:32.507  6264  6264 I AppConfig: App Tier : NOT_DEF
,06-22 07:44:32.516  6264  6264 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,06-22 07:44:32.610  5591  6305 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,06-22 07:44:32.612  2351  6303 I CheckinUtil: Classify the device as Phone.
06-22 07:44:32.612  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:44:32.614  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:44:32.681   842   942 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 36572, reason: UserStart, SyncResult: databaseError: true stats []
,06-22 07:44:32.698   842  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:32.698   842  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:32.698   842  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:32.698   842  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:32.698   279  1053 E BandwidthController: [LG DATA] No such appUid: 1000
06-22 07:44:32.698   279  1053 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-22 07:44:32.705   842   942 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 179199, reason: UserStart
06-22 07:44:32.706   842   942 I NotificationManager: android: cancelAsUser(716319171) by android
06-22 07:44:32.706   279  6313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:32.706   279  6313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-22 07:44:32.707   279  6313 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:32.707   279  6313 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:32.711   842  1932 I art     : Explicit concurrent mark sweep GC freed 85060(4MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 16.297ms total 256.281ms
,06-22 07:44:32.731   842   942 I NotificationManager: android: cancelAsUser(-1597574061) by android
06-22 07:44:32.735  2351  6303 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:32.735  2351  6303 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:32.735  2351  6303 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:44:32.735  2351  6303 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:32.736   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:44:32.736   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:44:32.736   279  6316 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:32.736   279  6316 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:32.737   279  6316 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:32.737   279  6316 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:32.749   279  6313 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:32.750   842  1307 I System.out: propertyValue:false
,06-22 07:44:32.755   842  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:32.755   842  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:32.756   842  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:32.756   842  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:32.757   279  1053 E BandwidthController: [LG DATA] No such appUid: 1000
06-22 07:44:32.757   279  1053 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-22 07:44:32.759   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:32.759   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-22 07:44:32.759   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:32.760  6213  6213 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-22 07:44:32.762   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:32.763   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-22 07:44:32.763   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:32.763  6213  6213 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,06-22 07:44:32.766   279  6318 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:32.766   279  6318 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:32.767   279  6318 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:32.767   279  6318 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:32.767   279  6318 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:32.769   842  1308 I System.out: propertyValue:false
,06-22 07:44:32.788  6210  6211 I DSQN    : first global connection report this to start monitoring at DSQM.
06-22 07:44:32.794  5591  6292 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
06-22 07:44:32.795   279  6316 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:32.796  2351  6303 I System.out: propertyValue:false
06-22 07:44:32.796  6210  6211 I DSQN    : restart monitoring
06-22 07:44:32.797   279  1057 D LGDataListener: argv[0]=dsqncommand
06-22 07:44:32.797   279  1057 D LGDataListener: argv[1]=wlan0
06-22 07:44:32.797   279  1057 D LGDataListener: argv[2]=1
06-22 07:44:32.797   279  1057 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
06-22 07:44:32.798   842  1024 D DSQN    : DSQM DsqnNotification wlan0  1
06-22 07:44:32.798   842  1024 D DSQN    : start to monitor internet connection
06-22 07:44:32.798  6210  6319 I DSQN    : dsqn report finish
,06-22 07:44:32.805   842  1308 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
06-22 07:44:32.846  2351  6279 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:32.846  2351  6279 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:32.859  2351  6279 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:32.859  2351  6279 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:32.859   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:44:32.859   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:44:32.859   279  6321 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:32.860   279  6321 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:32.860   279  6321 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:32.860   279  6321 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-22 07:44:32.865  6213  6213 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-22 07:44:32.865  6213  6213 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-22 07:44:32.878   842   942 I NotificationManager: android: cancelAsUser(353845882) by android
,06-22 07:44:32.889  2351  6303 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:32.889  2351  6303 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:32.900   279  6321 D libc-netbsd: res_queryN name = xxxxx succeed
,06-22 07:44:32.906  2351  6279 I System.out: propertyValue:false
06-22 07:44:32.923  6213  6213 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
06-22 07:44:32.929   842   942 I NotificationManager: android: cancelAsUser(-591465577) by android
,06-22 07:44:33.061   842  1908 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6326 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,06-22 07:44:33.089  6213  6213 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
06-22 07:44:33.089  6213  6213 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@109165c7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-22 07:44:33.090  6213  6213 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-22 07:44:33.090  6213  6213 D AndroidMusic: GMSCore installation verified
,06-22 07:44:33.131  6213  6213 I ConfigStore: Config Database version: 1
,06-22 07:44:33.175  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-22 07:44:33.175  5844  5929 I jxcore-log: 
,06-22 07:44:33.207   284   284 V AudioFlinger: 2094 died, releasing its sessions
06-22 07:44:33.207   284   284 V AudioFlinger:  pid 1758 @ 0
06-22 07:44:33.207   284   284 V AudioFlinger:  pid 3093 @ 1
06-22 07:44:33.207   284   284 V AudioFlinger:  pid 3093 @ 2
,06-22 07:44:33.257  5591  6261 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
06-22 07:44:33.258  5591  6261 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
,06-22 07:44:33.269   842  2194 I ActivityManager: Process com.lge.music (pid 2094) has died
,06-22 07:44:33.333   842   942 I NotificationManager: android: cancelAsUser(-1548111331) by android
06-22 07:44:33.338  6326  6347 D ALBootInit: ====action==>android.intent.action.TIME_SET
06-22 07:44:33.344  6326  6347 D ALBootInit: Alarm ALBootInit: TIME_SET
06-22 07:44:33.348  6326  6347 D Alarms  : [setNextAlert] start
,06-22 07:44:33.365  6326  6347 D Alarms  : [setNextAlert] (1)
,06-22 07:44:33.368  6326  6347 D Alarms  :  minTime  = 0
06-22 07:44:33.371  6326  6347 D Alarms  :  -- OK multi -- 0
06-22 07:44:33.372  6326  6347 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
06-22 07:44:33.372  6326  6347 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
,06-22 07:44:33.374  5553  6332 I art     : Explicit concurrent mark sweep GC freed 1583(67KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 1.582ms total 98.890ms
06-22 07:44:33.410  6326  6347 I CommonUtil: BUILD Operator: OPEN
06-22 07:44:33.412  6326  6347 D Alarms  : broadcastToWidgetProvider : false
,06-22 07:44:33.429  6326  6347 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
,06-22 07:44:33.439   842   942 I NotificationManager: android: cancelAsUser(353845882) by android
06-22 07:44:33.446  6213  6213 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,06-22 07:44:33.451   842  2194 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
06-22 07:44:33.455  6326  6326 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
06-22 07:44:33.457  6326  6326 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3ad804b1
06-22 07:44:33.465  6326  6326 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3ad804b1
,06-22 07:44:33.473   842   942 I NotificationManager: android: cancelAsUser(-1597574061) by android
06-22 07:44:33.473  6326  6326 D QuickCoverProvider: onReceiver
06-22 07:44:33.477  6213  6213 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,06-22 07:44:33.502  6213  6213 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
06-22 07:44:33.503   295   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-22 07:44:33.517   842  1932 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6354 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:33.619  2351  6279 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
06-22 07:44:33.633   842  1383 I ActivityManager: Killing 6088:com.lge.lgdmsclient/1000 (adj 15): empty #11
,06-22 07:44:33.659  6354  6354 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:44:33.718   842   860 W libprocessgroup: failed to open /acct/uid_1000/pid_6088/cgroup.procs: No such file or directory
,06-22 07:44:33.722  6354  6354 D CalendarApplication: CalendarApplication.onCreate()
06-22 07:44:33.726  6213  6213 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
06-22 07:44:33.735  6213  6235 I art     : CheckpointMarkThreadRoots callback created = 0xb042d400
,06-22 07:44:33.749  6354  6354 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
06-22 07:44:33.750  6354  6354 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1e2a046c, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3cc4fa35, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1e18deca, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3eb4983b, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@31e8fb58, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3ad804b1, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@314e1d96, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@34a7d17, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2f9e7504, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@13373aed, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2c67d22, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@12efd3b3, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@120fdd70, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3ad998e9, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@873496e, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3289f80f, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@38ed609c, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2529daa5, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@140e8e7a, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@25f8062b, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2cbdea88, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@17827c21, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@26e71846, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@5eeda07, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@358b2734, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3869b95d, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@366c72d2, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@17950fa3, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@304d82a0, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@168d8e59, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2d7aea1e, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1df02ff, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@f1828cc, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@237fb715, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@36678a2a, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3caad01b, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@300505b8, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1e31af91, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@19cc1ef6, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@159c52f7, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.,PreferenceKey$KeyData@36e0c564, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2930
,06-22 07:44:33.767  6354  6354 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,06-22 07:44:33.785   842   942 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6377 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:33.787  6354  6354 D Config  : [init]
,06-22 07:44:33.797   842   942 I NotificationManager: android: cancelAsUser(-591465577) by android
06-22 07:44:33.798  6244  6244 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
06-22 07:44:33.811  6213  6235 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3d0
,06-22 07:44:33.838  6354  6354 I Config  : LGCalendar ver.4.40.17
06-22 07:44:33.839  6354  6354 I Config  : start check model
06-22 07:44:33.839  6354  6354 I Config  : start check native_ca
,06-22 07:44:33.847  6354  6354 I Config  : Config Operator=OPEN, Country=EU
06-22 07:44:33.847  6354  6354 D Config  : [setDefaultValuesToPref]
06-22 07:44:33.849  6354  6354 D Config  : [parseProfiles]
06-22 07:44:33.854  6354  6354 D ProfilesParser: [debug_displayParseInfos] profile.country = null
06-22 07:44:33.854  6354  6354 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
06-22 07:44:33.854  6354  6354 D Config  : [updateProfiletoCountryInfo]
,06-22 07:44:33.856  6354  6354 D GeneralPreference: [checkAndMigrateOldPreference]
06-22 07:44:33.868  6142  6198 D UEI.SmartControl: Internal timer expired: 1
06-22 07:44:33.895  6354  6354 E AgendaWidgetManager: [updateWidgets] 
,06-22 07:44:33.961   842  2596 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6399 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,06-22 07:44:33.964  6213  6213 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
06-22 07:44:33.987  6213  6213 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-22 07:44:34.016  6244  6244 I HubEmail: JNI_OnLoad()
06-22 07:44:34.016  6244  6244 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-22 07:44:34.016  6244  6244 I HubEmail: registerNatives()
06-22 07:44:34.016  6244  6244 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-22 07:44:34.016  6244  6244 I HubEmail: registerNativeMethods()
06-22 07:44:34.016  6244  6244 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-22 07:44:34.016  6244  6244 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
06-22 07:44:34.024  6244  6414 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:44:34.034  6377  6377 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:44:34.098   842  2033 I ActivityManager: Killing 6067:com.lge.settings.easy/1000 (adj 15): empty #11
,06-22 07:44:34.115  5591  6365 W InstanceID/Rpc: Found 10006
,06-22 07:44:34.161  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-22 07:44:34.161  5844  5929 I jxcore-log: 
,06-22 07:44:34.187   842   860 W libprocessgroup: failed to open /acct/uid_1000/pid_6067/cgroup.procs: No such file or directory
,06-22 07:44:34.205  6213  6293 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,06-22 07:44:34.207  6399  6399 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:34.207  6399  6399 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-22 07:44:34.210  6399  6399 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-22 07:44:34.218  6399  6399 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,06-22 07:44:34.232  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-22 07:44:34.232  5844  5929 I jxcore-log: 
,06-22 07:44:34.246  6399  6421 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:34.247  6399  6421 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-22 07:44:34.249  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-22 07:44:34.249  5844  5929 I jxcore-log: 
,06-22 07:44:34.286  6399  6420 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,06-22 07:44:34.288   842  2596 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6426 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
06-22 07:44:34.296  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-22 07:44:34.296  5844  5929 I jxcore-log: 
06-22 07:44:34.303  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-22 07:44:34.303  5844  5929 I jxcore-log: 
06-22 07:44:34.331  6354  6398 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
,06-22 07:44:34.339  6354  6398 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
06-22 07:44:34.341  6354  6433 W HolidayIntentService: onHandleIntent
06-22 07:44:34.342  6354  6354 D MonthWidgetProvider: [onReceive]
06-22 07:44:34.342  6354  6354 D CalendarWidgetProvider: [onReceive]
06-22 07:44:34.342  6354  6433 D HolidayDataLoader: readJsonAsset : holiday.json
06-22 07:44:34.342  6354  6354 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
06-22 07:44:34.352  6354  6354 D CalendarTypeController: [onUpdateAndInitCalendarTime]
,06-22 07:44:34.358  6399  6420 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
06-22 07:44:34.422  6354  6433 E HolidayIntentService: onHandleIntent:holiday data empty
,06-22 07:44:34.426   842  1944 I ActivityManager: Process com.android.settings (pid 5989) has died
06-22 07:44:34.437  6354  6354 D WeekWidgetProvider: [onReceive]
06-22 07:44:34.437  6354  6354 D CalendarWidgetProvider: [onReceive]
06-22 07:44:34.437  6354  6354 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,06-22 07:44:34.438  6354  6354 D CalendarTypeController: [onUpdateAndInitCalendarTime]
06-22 07:44:34.450  6399  6420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,06-22 07:44:34.454  2801  2801 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 7:44:34
06-22 07:44:34.462  2801  2801 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,06-22 07:44:34.463  6399  6399 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
06-22 07:44:34.465  6399  6399 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
06-22 07:44:34.465  2801  2801 D Weather_cast: 2 : set auto-update time : 6/22 10:44
06-22 07:44:34.465  6399  6399 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
06-22 07:44:34.473  6354  6398 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
06-22 07:44:34.476  2801  2801 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 7:44:34
06-22 07:44:34.477  2801  2801 D WeatherService: 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
06-22 07:44:34.477  6399  6399 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,06-22 07:44:34.483  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
06-22 07:44:34.483  6399  6399 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
06-22 07:44:34.488  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
06-22 07:44:34.494  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,06-22 07:44:34.509  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,06-22 07:44:34.515  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
06-22 07:44:34.524   842  1932 I ActivityManager: Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6446 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:34.573   842  1820 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6452 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,06-22 07:44:34.574   842  2194 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
06-22 07:44:34.574  2801  2801 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
06-22 07:44:34.630  6426  6426 I AppUp4:AppBoxCP: onCreate
,06-22 07:44:34.634  6426  6426 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
06-22 07:44:34.643  6426  6426 I AppUp4:DB:  setFingerPrint start
06-22 07:44:34.643  6426  6426 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
06-22 07:44:34.650  6426  6426 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
06-22 07:44:34.650  6426  6426 I AppUp4:DB:  SDK version = 21
06-22 07:44:34.650  6426  6426 I AppUp4:DB:  beforefinger == newfinger no write in DB
06-22 07:44:34.667  2801  2801 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
06-22 07:44:34.667  2801  2801 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,06-22 07:44:34.673  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
06-22 07:44:34.682  6426  6426 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
06-22 07:44:34.687  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,06-22 07:44:34.696  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
06-22 07:44:34.703  6426  6426 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
06-22 07:44:34.703  6426  6426 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,06-22 07:44:34.706  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
06-22 07:44:34.712  6426  6426 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
06-22 07:44:34.716  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,06-22 07:44:34.734  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,06-22 07:44:34.744  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
06-22 07:44:34.754  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,06-22 07:44:34.759  6426  6426 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
06-22 07:44:34.764  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
06-22 07:44:34.784  6354  6398 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
06-22 07:44:34.784  6354  6398 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,06-22 07:44:34.796  6426  6426 I AppUp4:CustModeStarterReceiver: onReceive
06-22 07:44:34.796  6426  6426 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
06-22 07:44:34.796  6354  6398 I AlertUtils: set default noti to content://media/internal/audio/media/38
,06-22 07:44:34.810  6426  6426 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@31e8fb58
06-22 07:44:34.811  6426  6426 D AppUp4:CustFacade: isCustomizationCompleted : false
,06-22 07:44:34.819  6452  6452 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1466574274819
06-22 07:44:34.819  6452  6452 D         : TimeServiceNative: User Time to be set is 1466574274819
06-22 07:44:34.819  6452  6452 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
06-22 07:44:34.819  6452  6452 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
,06-22 07:44:34.820  6452  6452 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1466574274819
06-22 07:44:34.820  6452  6452 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
06-22 07:44:34.821   322  1065 D QC-time-services: Daemon: Connection accepted:time_genoff
06-22 07:44:34.822   322  6489 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1466574274819
06-22 07:44:34.822   322  6489 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1466574274819, operation = 0
06-22 07:44:34.822   322  6489 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/3/70 9:45:24
06-22 07:44:34.823   322  6489 D QC-time-services: Daemon:Value read from RTC seconds = 26473524000
06-22 07:44:34.823   322  6489 D QC-time-services: Daemon:new time 1466574274819 
06-22 07:44:34.823   322  6489 D QC-time-services: Daemon: delta 1440100750819 genoff 1440100750819 
06-22 07:44:34.823   322  6489 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100750819 to memory
06-22 07:44:34.823   322  6489 D QC-time-services: Daemon:Opening File: /data/time/ats_2
06-22 07:44:34.823   322  6489 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
06-22 07:44:34.826  6354  6398 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
06-22 07:44:34.847   322  6489 D QC-time-services: Updating the TOD offset
06-22 07:44:34.847   322  6489 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100750819 to memory
06-22 07:44:34.847   322  6489 D QC-time-services: Daemon:Opening File: /data/time/ats_1
06-22 07:44:34.847   322  6489 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,06-22 07:44:34.853   322  6489 E QC-time-services: Daemon:Update to modem bit set
06-22 07:44:34.853   322  6489 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
06-22 07:44:34.853   322  6489 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124135950819
06-22 07:44:34.854  6452  6452 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
06-22 07:44:34.857   322  1063 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
06-22 07:44:34.857   322  1065 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
06-22 07:44:34.876   842  1282 I ActivityManager: Process com.lge.qremote (pid 6118) has died
06-22 07:44:34.877   239   239 E lowmemorykiller: Error writing /proc/6142/oom_score_adj; errno=22
,06-22 07:44:34.918  6446  6490 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-22 07:44:34.919  6446  6490 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-22 07:44:35.043   842  1282 I art     : Explicit concurrent mark sweep GC freed 31137(1371KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.061ms total 157.408ms
,06-22 07:44:35.059   842  1282 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
06-22 07:44:35.059   842  1282 W ActivityManager: android.os.DeadObjectException
06-22 07:44:35.059   842  1282 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
06-22 07:44:35.059   842  1282 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
06-22 07:44:35.059   842  1282 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
06-22 07:44:35.059   842  1282 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
06-22 07:44:35.059   842  1282 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
06-22 07:44:35.059   842  1282 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
06-22 07:44:35.059   842  1282 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
06-22 07:44:35.059   842  1282 W ActivityManager: 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
06-22 07:44:35.059   842  1282 W ActivityManager: 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
06-22 07:44:35.059   842  1282 W ActivityManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
06-22 07:44:35.060   239   239 E lowmemorykiller: Error opening /proc/6142/oom_score_adj; errno=2
,06-22 07:44:35.071  5571  5571 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
06-22 07:44:35.079  5571  5571 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
,06-22 07:44:35.106   842  1383 I ActivityManager: Process com.uei.lg.quicksetsdk.lite (pid 6142) has died
,06-22 07:44:35.109  6426  6426 D AppUp4:CustFacade: isSimDevice : true
06-22 07:44:35.110  6446  6490 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
06-22 07:44:35.115  1374  1374 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
06-22 07:44:35.115  1374  1374 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
06-22 07:44:35.119  1330  1330 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
,06-22 07:44:35.121  1374  1374 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
06-22 07:44:35.127  6426  6426 D AppUp4:CustModeStarterReceiver: begin check event
06-22 07:44:35.129  6426  6426 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
06-22 07:44:35.129  6426  6426 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
06-22 07:44:35.134  6426  6484 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
06-22 07:44:35.134  6426  6484 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
06-22 07:44:35.134  6426  6484 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,06-22 07:44:35.164  5571  5571 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
,06-22 07:44:35.165  5571  5571 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
06-22 07:44:35.167  5571  5571 V [BNRBootReceiver]: Boot Receiver Return
06-22 07:44:35.169   842  1282 I ActivityManager: Killing 6038:com.lge.sync/1000 (adj 15): empty #11
06-22 07:44:35.217  6446  6490 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-22 07:44:35.217  6446  6490 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-22 07:44:35.218  3093  3093 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
06-22 07:44:35.219  3093  3093 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,06-22 07:44:35.223  3093  3093 I LgeMiscReceiver: networkInfo.isConnected() = true
06-22 07:44:35.231  3093  3093 D PhoneState: setPdpRejectCasuse : false
,06-22 07:44:35.291   842  1820 W libprocessgroup: failed to open /acct/uid_1000/pid_6038/cgroup.procs: No such file or directory
,06-22 07:44:35.366   842  1282 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6498 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,06-22 07:44:35.390   310   310 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 21.530ms
,06-22 07:44:35.413   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 347us total 22.580ms
,06-22 07:44:35.439   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 409us total 25.735ms
,06-22 07:44:35.477  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-22 07:44:35.477  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,06-22 07:44:35.477   842  2194 I ActivityManager: Process com.google.android.music:main (pid 6213) has died
,06-22 07:44:35.477  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,06-22 07:44:35.553  5591  6507 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-22 07:44:35.806  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:44:35.835  6498  6498 D PhoneMonitor: Register our PhoneStateListener
,06-22 07:44:35.891   842  1859 I NotificationManager: android: cancelAsUser(2) by android
,06-22 07:44:35.930  6446  6522 D ChimeraCfgMgr: Reading stored module config
06-22 07:44:35.932  6498  6498 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,06-22 07:44:35.933  6446  6466 I art     : CheckpointMarkThreadRoots callback created = 0xb0515ac0
,06-22 07:44:35.938  6498  6498 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
06-22 07:44:35.962  5591  5591 I art     : Explicit concurrent mark sweep GC freed 28549(2MB) AllocSpace objects, 37(592KB) LOS objects, 24% free, 14MB/19MB, paused 1.238ms total 205.010ms
,06-22 07:44:35.980  6446  6466 I art     : CheckpointMarkThreadRoots callback created = 0xaaeaa100
,06-22 07:44:35.986  2351  3053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:35.986  2351  3053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:35.988  5591  5604 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21f6359d)
06-22 07:44:35.992  2351  3053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:35.992  2351  3053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:35.993   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:44:35.993   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:44:35.996   279  6532 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:35.996   279  6532 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:35.997   279  6532 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:35.997   279  6532 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:35.998  2538  2538 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,06-22 07:44:36.012  2538  2538 V DownloadManager: DownloadService onCreate
,06-22 07:44:36.016  5591  6507 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:36.016  5591  6507 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:36.016  5591  6507 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:36.016  5591  6507 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:36.017   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:44:36.017   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:44:36.018   279  6537 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,06-22 07:44:36.018   279  6537 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:36.019   279  6537 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:36.019   279  6537 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:36.021  2538  6535 I DownloadManager: in removeSpuriousFiles
06-22 07:44:36.027  2538  2538 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
06-22 07:44:36.032  2538  6535 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
06-22 07:44:36.035  2538  6535 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@159c52f7 on behalf of 2538
,06-22 07:44:36.041   279  6532 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:36.042   279  6537 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:36.043  5591  6507 I System.out: propertyValue:false
06-22 07:44:36.044  6498  6498 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
06-22 07:44:36.046  2351  3053 I System.out: propertyValue:false
06-22 07:44:36.048  2538  6535 I DownloadManager: in trimDatabase
06-22 07:44:36.048  2538  6535 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
06-22 07:44:36.051  2538  6535 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2930b3cd on behalf of 2538
06-22 07:44:36.051  6498  6498 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,06-22 07:44:36.058   842   859 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6540 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
06-22 07:44:36.061  2538  2538 V DownloadManager: DownloadService onStartCommand
06-22 07:44:36.062  6498  6498 D TelephonyAutoProfiling: [parse] Load xml
06-22 07:44:36.072  6498  6498 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
06-22 07:44:36.072  6498  6498 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,06-22 07:44:36.096  2351  3053 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:36.096  2351  3053 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:36.115  2538  6536 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,06-22 07:44:36.124  2538  6536 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@26b92793 on behalf of 2538
,06-22 07:44:36.136  6446  6446 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
06-22 07:44:36.141  6498  6498 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
06-22 07:44:36.150  6446  6446 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:36.151  6446  6446 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:36.226  6446  6522 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,06-22 07:44:36.232  6446  6522 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk': Failed to open oat filename for reading: No such file or directory
06-22 07:44:36.234  6446  6522 D ChimeraFileApk: Classloading successful. Optimized code found.
06-22 07:44:36.244   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:36.244   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
06-22 07:44:36.244   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:36.244  6446  6446 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,06-22 07:44:36.276  6540  6540 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,06-22 07:44:36.278  6540  6540 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
06-22 07:44:36.316   842   860 I ActivityManager: Process com.lge.email (pid 6244) has died
,06-22 07:44:36.322  6446  6522 D DynamitePackage: Instantiated singleton DynamitePackage.
06-22 07:44:36.322  6446  6522 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
06-22 07:44:36.326  2538  2538 V DownloadManager: DownloadService onDestroy
06-22 07:44:36.336  6540  6540 V DrmService: Service onCreate
,06-22 07:44:36.350  6540  6540 D DrmService: Received new request = 2
,06-22 07:44:36.363  2801  2801 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:44:36
,06-22 07:44:36.367   842  1932 I NotificationManager: android: cancelAsUser(2) by android
06-22 07:44:36.375  2801  2801 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-22 07:44:36.403  2351  3053 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-22 07:44:36.412  2801  2801 D WeatherAncestor: connectivity changed - connection : true
06-22 07:44:36.418  2801  2801 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-22 07:44:36.418  2801  2801 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:44:36
06-22 07:44:36.418  2801  2801 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,06-22 07:44:36.423  6540  6574 I DrmSntpClient: Start Sync process
06-22 07:44:36.423  6540  6574 D DrmSntpClient: Server : 0
06-22 07:44:36.423  5591  6572 I CheckinService: Disabling old GoogleServicesFramework version
06-22 07:44:36.439  6540  6574 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:36.439  6540  6574 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:36.439  6540  6574 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:36.439  6540  6574 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:36.440   279  1053 E BandwidthController: [LG DATA] No such appUid: 10051
06-22 07:44:36.440   279  1053 D DnsProxyListener: App 10051 tries DNS query. Accept family:0 protocol:0
06-22 07:44:36.440   279  6577 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:36.440   279  6577 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:36.440   279  6577 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:36.441   279  6577 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-22 07:44:36.455   842  1932 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6578 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-22 07:44:36.456   842  1893 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
06-22 07:44:36.461  2801  2801 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
06-22 07:44:36.476   279  6577 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:36.479  2801  2801 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,06-22 07:44:36.479  2801  2801 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
06-22 07:44:36.481  6540  6574 I System.out: propertyValue:false
06-22 07:44:36.481  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-22 07:44:36.481  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-22 07:44:36.481  1374  1374 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
06-22 07:44:36.492  6540  6574 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
06-22 07:44:36.494   290   290 V ILGDrmService: eDRM_SetDRMTime +++
,06-22 07:44:36.501   290   290 I LGDRM   : [DRM] SET TIME : YR=2016, MON=6, DAY=22
06-22 07:44:36.501   290   290 I LGDRM   : [DRM] SET TIME : HR=5, MIN=44, SEC=35
06-22 07:44:36.514   290   290 V ILGDrmService: eDRM_SetDRMTime ---
,06-22 07:44:36.520  6540  6574 I DrmSntpClient: Synched
06-22 07:44:36.522  6540  6540 D DrmService: Completed !! request = 2
06-22 07:44:36.523  6540  6540 D DrmService: Request count = 0
06-22 07:44:36.540   842  1896 I ActivityManager: Process com.lge.clock (pid 6326) has died
,06-22 07:44:36.549  6540  6540 V DrmService: Service onDestroy
,06-22 07:44:36.612  6377  6511 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:44:36.634  6446  6446 I NotificationManager: com.google.android.youtube: cancel(2) by com.google.android.youtube
,06-22 07:44:36.693  6578  6578 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-22 07:44:36.756   842  1859 I ActivityManager: Process com.android.calendar (pid 6354) has died
,06-22 07:44:36.792   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:36.792   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
06-22 07:44:36.792   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:36.792  6446  6446 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
06-22 07:44:36.804   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:36.805   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
06-22 07:44:36.805   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:36.805  6446  6446 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
,06-22 07:44:36.807   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:36.807   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
06-22 07:44:36.807   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:36.808  6446  6446 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
06-22 07:44:36.819  6446  6446 W InstanceID/Rpc: Found 10006
,06-22 07:44:36.888   842  2009 I ActivityManager: Process com.android.gallery3d (pid 6264) has died
,06-22 07:44:36.896  5591  6576 I CheckinChimeraService: Checking schedule, now: 1466574276893 next: 1466512280449
06-22 07:44:36.896  5591  6576 I CheckinChimeraService: active receiver: enabled
06-22 07:44:36.908  5591  6576 I CheckinChimeraService: Preparing to send checkin request
06-22 07:44:36.908  5591  6576 I EventLogChimeraService: Accumulating logs since 1466572762561
,06-22 07:44:36.916  6377  6615 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:36.916  6377  6615 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
06-22 07:44:36.916   279  1053 E BandwidthController: [LG DATA] No such appUid: 10086
06-22 07:44:36.916   279  1053 D DnsProxyListener: App 10086 tries DNS query. Accept family:2 protocol:0
06-22 07:44:36.917   279  6619 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:36.917   279  6619 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
06-22 07:44:36.917   279  6619 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:36.917   279  6619 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:36.930   842   942 I NotificationManager: android: cancelAsUser(2126026182) by android
,06-22 07:44:36.991   842   942 I ActivityManager: Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6620 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:37.052   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,06-22 07:44:37.052   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
06-22 07:44:37.052   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:37.055  6446  6446 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,06-22 07:44:37.241   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:44:37.241   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:44:37.241   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 152254203801; DSPS: 5080418; Offset : -2799546191
,06-22 07:44:37.252  2351  2351 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,06-22 07:44:37.367  6446  6663 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:37.367  6446  6663 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:37.371  6446  6663 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:37.371  6446  6663 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-22 07:44:37.371   279  1053 E BandwidthController: [LG DATA] No such appUid: 10100
06-22 07:44:37.371   279  1053 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-22 07:44:37.372   279  6667 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:37.373   279  6667 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:37.373   279  6667 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:37.378   279  6667 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:37.413   279  6667 D libc-netbsd: res_queryN name = xxxxx succeed
,06-22 07:44:37.415  6446  6663 I System.out: propertyValue:false
06-22 07:44:37.416  6446  6663 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:37.416  6446  6663 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:37.491  6446  6605 I NotificationManager: com.google.android.youtube: cancel(10436) by com.google.android.youtube
,06-22 07:44:37.526   842  1037 I PowerManagerService: ALS enabled for SRE
06-22 07:44:37.527   842  1037 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32540 ms ago)
,06-22 07:44:37.534   842  1037 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,06-22 07:44:37.556   842  1037 I PowerManagerService: ALS enabled for SRE
06-22 07:44:37.556   842  1037 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (32570 ms ago)
06-22 07:44:37.572   842  1037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,06-22 07:44:37.620  6578  6679 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
06-22 07:44:37.620  6578  6679 I Babel_SMS: MmsConfig.loadMmsSettings
06-22 07:44:37.626   842  1383 I ActivityManager: Process com.lge.lgdmsclient (pid 6399) has died
,06-22 07:44:37.637   842  1282 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
06-22 07:44:37.643  6578  6679 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-22 07:44:37.643  6578  6679 I Babel_SMS: MmsConfig.loadFromDatabase
06-22 07:44:37.648   842  1037 I PowerManagerService: Sleeping (uid 1000)...
,06-22 07:44:37.661   842  1037 D LPWGController: [updateScreenState] screen on = false
,06-22 07:44:37.669   842  1037 D LPWGController: disable proximity sensor
06-22 07:44:37.669   842  1037 D LPWGController: enable proximity sensor
06-22 07:44:37.678  1758  1758 I PhoneApp: onTrimMemory: 10
,06-22 07:44:37.679  1758  1758 I PhoneApp: trim memory
06-22 07:44:37.691  6578  6679 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
06-22 07:44:37.691  6578  6679 I Babel_SMS: MmsConfig.loadFromResources
,06-22 07:44:37.696  6578  6679 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
06-22 07:44:37.697  6578  6679 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-22 07:44:37.697   842  1037 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1f12c439] by com.android.server.power.ProximitySensorListener.enable():120
06-22 07:44:37.709  2026  2026 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,06-22 07:44:37.714   842  1037 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
06-22 07:44:37.714   842  1037 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
06-22 07:44:37.714   842  1037 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
06-22 07:44:37.714   842  1037 I sensors_hal_Ctx: activate: handle is 48, enable
06-22 07:44:37.714   842  1037 V sensors_hal_Ctx: activate sensors is 1400000000000
06-22 07:44:37.714   842  1037 D sensors_hal_Thresh: enable: handle=48
06-22 07:44:37.714   842  1037 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
06-22 07:44:37.714   842  1037 D sensors_hal_Util: waitForResponse: timeout=1000
06-22 07:44:37.719  6446  6647 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:37.719  6446  6647 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:37.720  6446  6647 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:37.720  6446  6647 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:37.733   279  1053 E BandwidthController: [LG DATA] No such appUid: 10100
,06-22 07:44:37.733   279  1053 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-22 07:44:37.733   279  6684 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:37.733   279  6684 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:37.734   279  6684 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:37.735   279  6684 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:37.735   279  6684 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:37.739  6446  6648 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:37.739  6446  6648 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:37.739  6446  6648 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:37.739  6446  6648 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:37.740  6446  6647 I System.out: propertyValue:false
06-22 07:44:37.741   842   992 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
06-22 07:44:37.741   842   992 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
06-22 07:44:37.741   842  1037 D sensors_hal_Thresh: enable: Received response: 0
06-22 07:44:37.740  6446  6647 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:37.742  6446  6647 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:37.744   279  1053 E BandwidthController: [LG DATA] No such appUid: 10100
06-22 07:44:37.744   279  1053 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-22 07:44:37.745   279  6685 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,06-22 07:44:37.745   279  6685 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:37.746   279  6685 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:37.747   279  6685 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:37.747   279  6685 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:37.748  6446  6648 I System.out: propertyValue:false
06-22 07:44:37.748  6446  6648 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:37.748  6446  6648 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:37.754   842  1037 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (32768 ms ago)
06-22 07:44:37.803   842  1037 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:37.803   842  1037 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:37.803   842  1037 I Adreno-EGL: Build Date: 03/02/15 Mon
06-22 07:44:37.803   842  1037 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-22 07:44:37.803   842  1037 I Adreno-EGL: Remote Branch: 
06-22 07:44:37.803   842  1037 I Adreno-EGL: Local Patches: 
06-22 07:44:37.803   842  1037 I Adreno-EGL: Reconstruct Branch: 
,06-22 07:44:37.806   842  1944 I ActivityManager: Process com.lge.appbox.client (pid 6426) has died
06-22 07:44:37.890   242  2052 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (205 us)
,06-22 07:44:37.922  6620  6689 I Gmail   : getAccountsCursor
,06-22 07:44:37.935  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:44:37.969   420   982 I Sensors : sns_pwr.c(273):acquiring wakelock
06-22 07:44:37.969   842   992 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
06-22 07:44:37.970   842   992 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
06-22 07:44:37.970   842   992 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
06-22 07:44:37.973   842   992 D sensors_hal_Thresh: processInd: handle 48, count=1
,06-22 07:44:37.973   842   992 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
06-22 07:44:37.973   842   992 I sensors_hal_Thresh: processInd : proximity state changed - FAR
06-22 07:44:37.973   842  1034 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
06-22 07:44:37.973   842  1034 D sensors_hal_Ctx: poll: count: 256
06-22 07:44:37.973   842  1034 I sensors_hal_Ctx: poll: released wakelock sensor_ind
06-22 07:44:37.973   842  1034 D sensors_hal_Util: waitForResponse: timeout=0
06-22 07:44:37.989  6620  6620 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
06-22 07:44:38.066  6446  6647 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:38.066  6446  6647 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:38.071  6578  6594 I art     : CheckpointMarkThreadRoots callback created = 0xb042d940
06-22 07:44:38.109   842  1037 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
06-22 07:44:38.109   842  1037 I LPWGController: current mode = 1  value = 1 1
06-22 07:44:38.110   842  1037 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,06-22 07:44:38.120   842  1037 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
06-22 07:44:38.121  6377  6392 I art     : CheckpointMarkThreadRoots callback created = 0xaafae3c0
06-22 07:44:38.142   842  2009 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,06-22 07:44:38.144  6578  6578 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
06-22 07:44:38.148  6578  6578 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
06-22 07:44:38.148  6578  6578 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
06-22 07:44:38.150  6620  6698 E Gmail   : Error finding the version of the Email provider.....
06-22 07:44:38.150  6620  6698 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
06-22 07:44:38.150  6620  6698 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
06-22 07:44:38.150  6620  6698 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
06-22 07:44:38.150  6620  6698 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
06-22 07:44:38.150  6620  6698 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-22 07:44:38.150  6620  6698 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:38.150  6620  6698 E Gmail   : 	at android.os.Looper.loop(Looper.java:135)
06-22 07:44:38.150  6620  6698 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-22 07:44:38.150  6620  6698 W EmailMigration: We do not support migrating this version of the Email provider.
06-22 07:44:38.148  6578  6578 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
06-22 07:44:38.151  6578  6578 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
06-22 07:44:38.151  6578  6578 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
06-22 07:44:38.151  6578  6578 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
06-22 07:44:38.151  6578  6578 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
06-22 07:44:38.151  6578  6578 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
06-22 07:44:38.151  6578  6578 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
06-22 07:44:38.167  6578  6578 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
06-22 07:44:38.168  6578  6578 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
06-22 07:44:38.168  6578  6578 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
06-22 07:44:38.168  6578  6578 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
06-22 07:44:38.168  6578  6578 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
06-22 07:44:38.168  6578  6578 D SensorManager: found sensor: Motion Accel, handle=46
,06-22 07:44:38.177  6377  6392 I art     : CheckpointMarkThreadRoots callback created = 0xaafae390
06-22 07:44:38.179  6446  6648 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:38.179  6446  6648 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:38.187  6578  6594 I art     : CheckpointMarkThreadRoots callback created = 0xaae47db0
,06-22 07:44:38.192  6620  6700 I Gmail   : getAccountsCursor
,06-22 07:44:38.194  6620  6699 W Gmail   : Sync started for account: account:61035162
06-22 07:44:38.207  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:44:38.275  6578  6594 W art     : Suspending all threads took: 22.290ms
,06-22 07:44:38.366  5591  6576 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,06-22 07:44:38.375  6377  6377 I NotificationManager: com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
06-22 07:44:38.452   842  1896 I ActivityManager: Process com.qualcomm.timeservice (pid 6452) has died
,06-22 07:44:38.464   842  2033 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,06-22 07:44:38.468  5591  6576 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
06-22 07:44:38.480  1758  1758 I PhoneApp: onTrimMemory: 15
06-22 07:44:38.480  1758  1758 I PhoneApp: trim memory
,06-22 07:44:38.486  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:44:38.507   295   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-22 07:44:38.575   842  1037 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
06-22 07:44:38.575   842  1037 I sensors_hal_Ctx: activate: handle is 46, disable
06-22 07:44:38.575   842  1037 V sensors_hal_Ctx: activate sensors is 1000000000000
06-22 07:44:38.575   842  1037 D sensors_hal_LP2: enable: handle=46
06-22 07:44:38.575   842  1037 D sensors_hal_LP2: enable: Disabling sensor handle=46
06-22 07:44:38.575   842  1037 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,06-22 07:44:38.616   842  1347 D qdlights: set_light_backlight: 0
,06-22 07:44:38.621   842   942 I NotificationManager: android: cancelAsUser(2145784878) by android
06-22 07:44:38.625   242   242 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
06-22 07:44:38.625   242   242 D qdhwcomposer: hwc_blank: Blanking display: 0
06-22 07:44:38.630   842  1027 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,06-22 07:44:38.638   842   842 V ActivityManager: Display changed displayId=0
,06-22 07:44:38.667   842  1018 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
06-22 07:44:38.667   842  1018 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,06-22 07:44:38.792   842  1896 I art     : Explicit concurrent mark sweep GC freed 25090(1226KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.450ms total 275.563ms
,06-22 07:44:38.803  1758  1758 D DSDPConnection: Display #0 changed.
,06-22 07:44:38.818  6620  6706 I Gmail   : Observing account changes for notifications
06-22 07:44:38.822  6578  6578 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:44:38.824   842  2596 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
06-22 07:44:38.834  6578  6594 W art     : Suspending all threads took: 6.068ms
06-22 07:44:38.849   242   242 D qdhwcomposer: hwc_blank: Done blanking display: 0
,06-22 07:44:38.850   842  1347 D SurfaceControl: Excessive delay in setPowerMode(): 224ms
06-22 07:44:38.853   842  1347 I QCOM PowerHAL: Got set_interactive hint
06-22 07:44:38.853   242   684 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
06-22 07:44:38.858  6578  6578 I Babel_Crash: startup - clean
,06-22 07:44:38.886  1374  2500 D KeyguardViewMediator: onScreenTurnedOff(3)
,06-22 07:44:38.904  1330  1346 D SmartCoverViewMediator: onScreenTurnedOff(3)
,06-22 07:44:38.918  5844  5844 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,06-22 07:44:38.918  5844  5844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
06-22 07:44:38.925  6578  6713 I Babel   : deleted: false for 0
06-22 07:44:38.926  1330  1346 D SmartCoverViewMediator: notifyScreenOffLocked
06-22 07:44:38.928  1330  1330 D SmartCoverViewMediator: handleNotifyScreenOFF
06-22 07:44:38.935  1374  2500 D KeyguardViewMediator: notifyScreenOffLocked
,06-22 07:44:38.938   842   942 I NotificationManager: android: cancelAsUser(2145784878) by android
06-22 07:44:38.943   842   842 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
06-22 07:44:38.951   842  1306 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
,06-22 07:44:38.960   284   284 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 842
06-22 07:44:38.961   284   284 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
06-22 07:44:38.961   284   284 V voice   : voice_set_parameters: enter: screen_state=on
06-22 07:44:38.961   284   284 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
06-22 07:44:38.961   284   284 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-22 07:44:38.961   284   284 V voice   : voice_set_parameters: exit with code(0)
06-22 07:44:38.961   284   284 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
06-22 07:44:38.961   284   284 V msm8974_platform: platform_set_parameters: enter: screen_state=on
06-22 07:44:38.961   284   284 V msm8974_platform: platform_set_parameters: exit with code(0)
06-22 07:44:38.961   284   284 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-22 07:44:38.962   284   284 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
06-22 07:44:38.962   284   284 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
06-22 07:44:38.962   284   284 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-22 07:44:38.964  5844  5844 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@38ed609c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@343ca24, 16908290=android.view.AbsSavedState$1@343ca24}, android:focusedViewId=100}]}]
06-22 07:44:38.964  5844  5844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
06-22 07:44:38.966  5844  5844 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
06-22 07:44:38.966  5844  5844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,06-22 07:44:38.974  6620  6704 I Gmail   : notifyAccountChanged
06-22 07:44:38.978  6620  6716 I Gmail   : getAccountsCursor
06-22 07:44:38.979  1374  2500 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
06-22 07:44:38.979  1374  1374 D KeyguardViewMediator: handleNotifyScreenOff
06-22 07:44:38.993  1374  1374 D ScreenTurnOffBySensor: unregisterProximitySensor
,06-22 07:44:39.000  1374  1374 D StatusBarWindowView: onScreenTurnedOff why = 3
06-22 07:44:39.004  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:44:39.004  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
06-22 07:44:39.008  6620  6704 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,06-22 07:44:39.019  6620  6704 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,06-22 07:44:39.030  6620  6704 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
06-22 07:44:39.031  6620  6704 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
06-22 07:44:39.056   842   942 I ActivityManager: Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6717 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:39.066   842   942 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
06-22 07:44:39.111  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:44:39.153   842   860 D SplitWindow: check instance of lgWin Window{39f6dc8d u0 SearchPanel}
06-22 07:44:39.169  1907  1907 I QCNEJ   : |CORE| sendScreenState: state:true
,06-22 07:44:39.178  1852  2044 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
06-22 07:44:39.180  1852  2044 D LEDService: stopPatternFlashing()
06-22 07:44:39.182  1852  2044 D qdlights: set_light_notifications: 0,0,0,0,3
,06-22 07:44:39.184  1852  2044 I LEDService: getCurrentHighestLGLedRecord : size = 1
06-22 07:44:39.184  1852  2044 D qdlights: set_light_notifications: 0,0,0,0,3
06-22 07:44:39.186  1852  2044 I LEDService: updateLightsLocked : turn off led
06-22 07:44:39.186  1852  2044 D qdlights: set_light_notifications: 0,0,0,0,3
06-22 07:44:39.189  1852  2044 D LEDHandler: RESTART MSG
06-22 07:44:39.189   842  1893 D InputDispatcher: Window went away: Window{1bd3473e u0 SearchPanel}
06-22 07:44:39.190  6620  6699 I Gmail   : notifyAccountChanged
06-22 07:44:39.193  1374  1374 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
,06-22 07:44:39.212  1374  1374 I LgeClockWidgetControlView: time changed, timezoneChanged : false
06-22 07:44:39.223  1852  1852 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
06-22 07:44:39.226  1852  1852 D Cliptray Service: lockStatus = 0
,06-22 07:44:39.234  1821  1821 D LNfcService: action : android.intent.action.SCREEN_ON
06-22 07:44:39.234  6578  6578 W AudioCapabilities: Unsupported mime audio/x-lg-flac
06-22 07:44:39.239   842   842 D Ulp_jni : JNI:system_update. Event-0
,06-22 07:44:39.247  1821  6734 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
06-22 07:44:39.247  1821  6734 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
06-22 07:44:39.248  1821  6734 D LNfcService: isRequireNfcCRouting() return true
06-22 07:44:39.249  1821  6734 D LNfcService: isHCERoutingtoHost() return : true
06-22 07:44:39.249  1821  6734 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
06-22 07:44:39.249  1821  6734 D NfcService: mEnableLPD: true
06-22 07:44:39.249  1821  6734 D NfcService: mEnableReader: false
06-22 07:44:39.249  1821  6734 D NfcService: mEnableHostRouting: true
06-22 07:44:39.250  1821  6734 D NfcService: newParams.techmask= mTechMask: default
06-22 07:44:39.250  1821  6734 D NfcService: mEnableLPD: true
06-22 07:44:39.250  1821  6734 D NfcService: mEnableReader: false
06-22 07:44:39.250  1821  6734 D NfcService: mEnableHostRouting: true
06-22 07:44:39.250  1821  6734 D NfcService: screenState= 3
06-22 07:44:39.250  1821  6734 D NfcService: Discovery configuration equal, not updating.
06-22 07:44:39.253  6578  6578 W AudioCapabilities: Unsupported mime audio/adpcm
,06-22 07:44:39.257  6578  6578 W AudioCapabilities: Unsupported mime audio/g726
06-22 07:44:39.260  1758  1758 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
06-22 07:44:39.261  6578  6578 W AudioCapabilities: Unsupported mime audio/x-ms-wma
06-22 07:44:39.262  6578  6578 W AudioCapabilities: Unsupported mime audio/wma-voice
06-22 07:44:39.263  6578  6578 W VideoCapabilities: Unsupported mime video/mjpg
06-22 07:44:39.283  6578  6578 W VideoCapabilities: Unsupported mime video/theora
,06-22 07:44:39.301  5553  6332 I art     : Explicit concurrent mark sweep GC freed 2950(123KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 628us total 87.726ms
,06-22 07:44:39.326  6578  6578 W AudioCapabilities: Unsupported mime audio/evrc
06-22 07:44:39.327  6578  6578 W AudioCapabilities: Unsupported mime audio/qcelp
,06-22 07:44:39.329  6578  6578 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-22 07:44:39.336  6578  6578 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
06-22 07:44:39.337  6578  6578 W AudioCapabilities: Unsupported mime audio/qcelp
06-22 07:44:39.338  6578  6578 W AudioCapabilities: Unsupported mime audio/evrc
06-22 07:44:39.351  6578  6578 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,06-22 07:44:39.356   842  1859 I ActivityManager: Process com.lge.bnr (pid 5571) has died
06-22 07:44:39.374  2801  2801 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 7:44:39
06-22 07:44:39.378  2801  2801 D WeatherService: 2 : ACTION screen on
,06-22 07:44:39.382  2801  2801 D WeatherService: 2 : shouldTimeTickRegistered : false
06-22 07:44:39.389  2801  2801 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-22 07:44:39.389  2801  2801 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 7:44:39
,06-22 07:44:39.400  6578  6578 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
06-22 07:44:39.404  3873  3873 D AppCleanupService: android.intent.action.SCREEN_ON
,06-22 07:44:39.412   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:39.412   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:39.412   842   842 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
06-22 07:44:39.421  6578  6578 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:44:39.426   284   284 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 842
06-22 07:44:39.430   284   284 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
06-22 07:44:39.430   284   284 V voice   : voice_set_parameters: enter: screen_state=off
06-22 07:44:39.430   284   284 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
06-22 07:44:39.430   284   284 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-22 07:44:39.430   284   284 V voice   : voice_set_parameters: exit with code(0)
06-22 07:44:39.430   284   284 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
06-22 07:44:39.430   284   284 V msm8974_platform: platform_set_parameters: enter: screen_state=off
06-22 07:44:39.430   284   284 V msm8974_platform: platform_set_parameters: exit with code(0)
06-22 07:44:39.430   284   284 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-22 07:44:39.430   284   284 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
06-22 07:44:39.430   284   284 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-22 07:44:39.431  6578  6578 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-22 07:44:39.432   842  1312 D WifiController: CMD_SCREEN_OFF 
06-22 07:44:39.433   842  1312 D WifiController: shouldWifiStayAwake TRUE
06-22 07:44:39.439  6578  6578 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:44:39.454  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,06-22 07:44:39.462  6578  6578 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:44:39.466   842   942 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
06-22 07:44:39.469   420   432 I Sensors : sns_pwr.c(301):releasing wakelock
,06-22 07:44:39.478  6578  6578 I vclib   : onServiceConnected
06-22 07:44:39.480  6578  6578 W Babel   : Attempted to change video mute state without an active call.
06-22 07:44:39.493  6620  6689 I Gmail   : getAccountsCursor
,06-22 07:44:39.506  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:44:39.515  6578  6737 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:39.516  6578  6737 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:39.516  6578  6737 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:39.516  6578  6737 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:39.517   279  1053 E BandwidthController: [LG DATA] No such appUid: 10061
06-22 07:44:39.517   279  1053 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
06-22 07:44:39.518   279  6739 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:39.518   279  6739 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:39.519   279  6739 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-22 07:44:39.519   279  6739 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:39.519   279  6739 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:39.524  6578  6737 I System.out: propertyValue:false
06-22 07:44:39.525  6578  6578 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,06-22 07:44:39.549  6578  6737 I Babel   : connection state changed from UNKNOWN to CONNECTED
,06-22 07:44:39.686   842  1893 I ActivityManager: Process com.google.android.setupwizard (pid 6498) has died
,06-22 07:44:39.699  1758  1758 I PhoneApp: onTrimMemory: 15
06-22 07:44:39.699  1758  1758 I PhoneApp: trim memory
06-22 07:44:39.707  1907  1907 I QCNEJ   : |CORE| sendScreenState: state:false
,06-22 07:44:39.715  1852  2044 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
06-22 07:44:39.715  1852  2044 D LEDService: stopPatternFlashing()
06-22 07:44:39.715  1852  2044 D qdlights: set_light_notifications: 0,0,0,0,3
06-22 07:44:39.717  1852  2044 I LEDService: getCurrentHighestLGLedRecord : size = 1
06-22 07:44:39.717  1852  2044 D qdlights: set_light_notifications: 0,0,0,0,3
06-22 07:44:39.719  1852  2044 I LEDService: updateLightsLocked : turn on led
06-22 07:44:39.719  1852  2044 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
06-22 07:44:39.720  1852  2044 E LEDService: Can't handle this request of patternId:0
06-22 07:44:39.720  1852  2044 D LEDHandler: RESTART MSG
06-22 07:44:39.723  1852  1852 D VolumeVibrator: clear
06-22 07:44:39.725  1852  1852 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
06-22 07:44:39.725  1821  1821 D LNfcService: action : android.intent.action.SCREEN_OFF
,06-22 07:44:39.749  1821  2209 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
06-22 07:44:39.751  1945  1945 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,06-22 07:44:39.781  2026  2026 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
06-22 07:44:39.786  1758  1758 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,06-22 07:44:39.789  2026  2026 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
06-22 07:44:39.795   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:39.795   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-22 07:44:39.795   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:39.797  6717  6746 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
06-22 07:44:39.803  2801  2801 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 7:44:39
06-22 07:44:39.803  2801  2801 D WeatherService: 2 : ACTION screen off
,06-22 07:44:39.806  2801  2801 D WeatherService: 2 : TimeTick Receiver Unregister
06-22 07:44:39.807  2801  2801 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 7:44:39
06-22 07:44:39.811   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:39.812   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-22 07:44:39.812   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:39.812  3873  3873 D AppCleanupService: android.intent.action.SCREEN_OFF
06-22 07:44:39.812  6717  6746 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-22 07:44:39.814  3873  6747 D AppCleanupService: AppUsageStatsSaveTask
06-22 07:44:39.817   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:44:39.817   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:39.818   842   842 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
06-22 07:44:39.825  6620  6699 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 24086, normalSync: true
06-22 07:44:39.831   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:39.831   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-22 07:44:39.831   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:39.834  6717  6717 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
06-22 07:44:39.834  6717  6717 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
06-22 07:44:39.834  6717  6717 I GAv4    :   adb logcat -s GAv4
06-22 07:44:39.837  6717  6748 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
06-22 07:44:39.860   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:39.860   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-22 07:44:39.860   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:39.865  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-22 07:44:39.865  5844  5929 I jxcore-log: 
06-22 07:44:39.876  6717  6748 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,06-22 07:44:39.889  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-22 07:44:39.889  5844  5929 I jxcore-log: 
,06-22 07:44:39.897  1821  2626 E NxpNfcJni: getReconnectState = 0x0
06-22 07:44:39.901  1821  2209 D LCardEmulationManager: getHceAppCount hostAppNum : 0
06-22 07:44:39.901  1821  2209 D LCardEmulationManager: getDefaultRoute
06-22 07:44:39.901  1821  2209 D LNfcService: isRequireNfcCRouting() return true
06-22 07:44:39.902  1821  2209 D LNfcService: isHCERoutingtoHost() return : true
06-22 07:44:39.904  1821  2209 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
06-22 07:44:39.904  1821  2209 D NfcService: mEnableLPD: true
06-22 07:44:39.904  1821  2209 D NfcService: mEnableReader: false
06-22 07:44:39.904  1821  2209 D NfcService: mEnableHostRouting: true
06-22 07:44:39.904  1821  2209 D NfcService: newParams.techmask= mTechMask: 0
06-22 07:44:39.904  1821  2209 D NfcService: mEnableLPD: true
06-22 07:44:39.904  1821  2209 D NfcService: mEnableReader: false
06-22 07:44:39.904  1821  2209 D NfcService: mEnableHostRouting: true
06-22 07:44:39.904  1821  2209 D NfcService: screenState= 1
,06-22 07:44:39.907  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-22 07:44:39.907  5844  5929 I jxcore-log: 
06-22 07:44:39.913  6717  6717 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
06-22 07:44:39.953  6717  6717 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,06-22 07:44:39.957  1821  2626 E NxpNfcJni: getReconnectState = 0x0
06-22 07:44:39.959  6717  6750 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
06-22 07:44:40.034   842  1893 I NotificationManager: android: cancelAsUser(2) by android
,06-22 07:44:40.059  2351  2549 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-22 07:44:40.109  6620  6699 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-22 07:44:40.109  6620  6699 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-22 07:44:40.226   842  1282 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6764 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,06-22 07:44:40.250  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-22 07:44:40.250  5844  5929 I jxcore-log: 
,06-22 07:44:40.310  6620  6699 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-22 07:44:40.356   842  1383 I ActivityManager: Process com.lge.drmservice (pid 6540) has died
,06-22 07:44:40.361  1758  1758 I PhoneApp: onTrimMemory: 15
06-22 07:44:40.361  1758  1758 I PhoneApp: trim memory
06-22 07:44:40.397  6764  6764 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-22 07:44:40.397  6764  6764 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-22 07:44:40.436  6620  6699 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,06-22 07:44:40.445  6620  6699 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-22 07:44:40.450  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:44:40.453  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-22 07:44:40.453  5844  5929 I jxcore-log: 
06-22 07:44:40.473   842   860 I NotificationManager: android: cancelAsUser(2) by android
,06-22 07:44:40.480  6764  6764 I MultiDex: VM with version 2.1.0 has multidex support
06-22 07:44:40.480  6764  6764 I MultiDex: install
06-22 07:44:40.480  6764  6764 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-22 07:44:40.562  6717  6717 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
06-22 07:44:40.567  6764  6764 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-22 07:44:40.581  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:44:40.586  5591  6782 V AccountUtils: 0 accounts found with uca feature
06-22 07:44:40.587  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-22 07:44:40.587  5844  5929 I jxcore-log: 
06-22 07:44:40.588  5591  6782 I GamesSyncAdapter: Starting sync for 3a3529a
,06-22 07:44:40.600  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-22 07:44:40.600  5844  5929 I jxcore-log: 
,06-22 07:44:40.637  6764  6764 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,06-22 07:44:40.640  6764  6764 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3fd8f85: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-22 07:44:40.641  6764  6764 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-22 07:44:40.645  6764  6764 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
06-22 07:44:40.646  6764  6764 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
06-22 07:44:40.664  6764  6764 D ChimeraCfgMgr: Reading stored module config
,06-22 07:44:40.710  6620  6634 I art     : CheckpointMarkThreadRoots callback created = 0xaaf1bd80
,06-22 07:44:40.712  6717  6717 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5724-5726)
06-22 07:44:40.713  6717  6717 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:44:40.732  6620  6699 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:40.733  6620  6699 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:40.738  6620  6699 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:40.738  6620  6699 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:40.739   279  1053 E BandwidthController: [LG DATA] No such appUid: 10053
06-22 07:44:40.739   279  1053 D DnsProxyListener: App 10053 tries DNS query. Accept family:0 protocol:0
06-22 07:44:40.739   279  6791 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:40.739   279  6791 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:40.739   279  6791 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:40.740   279  6791 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:40.757  6717  6717 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e9a63f5}
,06-22 07:44:40.760  6717  6717 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:44:40.765  6717  6717 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-22 07:44:40.771  6620  6634 I art     : CheckpointMarkThreadRoots callback created = 0xb042daf0
,06-22 07:44:40.794  6717  6717 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-22 07:44:40.796   842  2033 I ActivityManager: Process com.google.android.youtube (pid 6446) has died
,06-22 07:44:40.799  6717  6717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:44:40.804  6717  6717 E SysUtils: ApplicationContext is null in ApplicationStatus
06-22 07:44:40.863  6764  6789 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,06-22 07:44:40.895  6717  6717 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,06-22 07:44:40.917  6717  6717 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-22 07:44:40.917  6717  6717 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-22 07:44:40.919  6764  6764 I art     : Rejecting re-init on previously-failed class java.lang.Class<jry>
06-22 07:44:40.920  6764  6764 I art     : Rejecting re-init on previously-failed class java.lang.Class<jry>
06-22 07:44:40.921  6717  6717 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:40.921  6717  6717 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:40.921  6717  6717 I Adreno-EGL: Build Date: 03/02/15 Mon
06-22 07:44:40.921  6717  6717 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-22 07:44:40.921  6717  6717 I Adreno-EGL: Remote Branch: 
06-22 07:44:40.921  6717  6717 I Adreno-EGL: Local Patches: 
06-22 07:44:40.921  6717  6717 I Adreno-EGL: Reconstruct Branch: 
06-22 07:44:41.011   284  1320 V AudioPolicyService: registerClient() client 0xb39b5c60, uid 10079
,06-22 07:44:41.015  6717  6806 W AudioManagerAndroid: Requires BLUETOOTH permission
06-22 07:44:41.059   279  6791 D libc-netbsd: res_queryN name = xxxxx succeed
,06-22 07:44:41.060  6620  6699 I System.out: propertyValue:false
06-22 07:44:41.061  6620  6699 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:41.061  6620  6699 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:41.062  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-22 07:44:41.062  5844  5929 I jxcore-log: 
06-22 07:44:41.096  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-22 07:44:41.096  5844  5929 I jxcore-log: 
,06-22 07:44:41.103  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-22 07:44:41.103  5844  5929 I jxcore-log: 
,06-22 07:44:41.106   842  1859 I ActivityManager: Process com.google.android.apps.plus (pid 6377) has died
06-22 07:44:41.114  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-22 07:44:41.114  5844  5929 I jxcore-log: 
,06-22 07:44:41.117  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:44:41.150  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-22 07:44:41.150  5844  5929 I jxcore-log: 
,06-22 07:44:41.165   842  1893 I ActivityManager: Start proc com.google.android.play.games.ui for service com.google.android.play.games/com.google.android.gms.games.service.PlayGamesBridgeService: pid=6807 uid=10085 gids={50085, 9997} abi=armeabi-v7a
06-22 07:44:41.186  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-22 07:44:41.186  5844  5929 I jxcore-log: 
,06-22 07:44:41.232   842  2009 I NotificationManager: android: cancelAsUser(2) by android
,06-22 07:44:41.295  6717  6717 I NSApplication: Starting up...
06-22 07:44:41.305   284  1321 D WVCdm   : Instantiating CDM.
,06-22 07:44:41.306   284  1604 I WVCdm   : CdmEngine::OpenSession
06-22 07:44:41.307   284  1604 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
06-22 07:44:41.318  5591  5658 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:44:41.318  5591  5658 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:41.318  5591  5658 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:41.318  5591  5658 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:41.328   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:44:41.328   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:44:41.329   279  6836 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:41.329   279  6836 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:41.329   279  6836 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:41.329   279  6836 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:41.329   279  6836 D libc-netbsd: res_queryN name = xxxxx succeed
,06-22 07:44:41.331  5591  5658 I System.out: propertyValue:false
06-22 07:44:41.364  6764  6780 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:41.364  6764  6780 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:41.364  6764  6780 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:41.364  6764  6780 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:41.365   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:44:41.365   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:44:41.366   279  6838 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:41.366   279  6838 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:41.366   279  6838 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:41.366   279  6838 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:41.367   279  6838 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:41.368  6764  6780 I System.out: propertyValue:false
,06-22 07:44:41.382  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-22 07:44:41.382  5844  5929 I jxcore-log: 
06-22 07:44:41.383   284  1604 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
06-22 07:44:41.384   284  1604 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
06-22 07:44:41.384   284  1604 W WVCdm   : L1 library not specified. Falling Back to L3
,06-22 07:44:41.391  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-22 07:44:41.391  5844  5929 I jxcore-log: 
06-22 07:44:41.410  6717  6839 I SyncAdapterService: Ignoring sync request for non-current account
,06-22 07:44:41.441  5844  5929 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-22 07:44:41.441  5844  5929 I jxcore-log: 
,06-22 07:44:41.449   842  1908 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6843 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:41.472   284  1604 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-22 07:44:41.476   284   284 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-22 07:44:41.476   284   284 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-22 07:44:41.477   284   284 I WVCdm   : CdmEngine::GenerateKeyRequest
06-22 07:44:41.477  2055  2070 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:41.480  5844  5929 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
06-22 07:44:41.482  5844  5929 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-22 07:44:41.482  5844  5929 I jxcore-log: 
06-22 07:44:41.487   284   284 D WVCdm   : PrepareKeyRequest: nonce=2032550045
,06-22 07:44:41.527  6764  6780 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:41.528  6764  6780 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:41.585  6764  6779 I art     : CheckpointMarkThreadRoots callback created = 0xaaf111a0
,06-22 07:44:41.636  5844  5929 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-22 07:44:41.636  5844  5929 I jxcore-log: 
06-22 07:44:41.638  5844  5929 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
06-22 07:44:41.638  5844  5929 I jxcore-log: 
06-22 07:44:41.639  5844  5929 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-22 07:44:41.639  5844  5929 I jxcore-log: 
,06-22 07:44:41.641  6807  6842 I NotificationManager: com.google.android.play.games: cancel(10436) by com.google.android.play.games
06-22 07:44:41.678  6764  6779 I art     : CheckpointMarkThreadRoots callback created = 0xaaf11190
,06-22 07:44:41.724   842  1383 I art     : Explicit concurrent mark sweep GC freed 27381(1260KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.348ms total 177.673ms
,06-22 07:44:41.769   842   942 I NotificationManager: android: cancelAsUser(-701419433) by android
06-22 07:44:41.813  5591  6782 I GamesSyncAdapter: Sync duration for 3a3529a: 1222
,06-22 07:44:41.894   842   942 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService: pid=6869 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:41.929  5591  5591 I GAv4-SVC: Google Analytics 9.0.83 is starting up.
,06-22 07:44:42.067   842  2009 I ActivityManager: Process com.google.android.talk (pid 6578) has died
,06-22 07:44:42.111  6869  6869 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:44:42.138  5591  5591 D PlayCommon: [1] DfeRequest.deliverResponse: Not delivering second response for request=[[ ] https://android.clients.google.com/fdfe/api/experiments 0xe8d195d1 NORMAL 1]
,06-22 07:44:42.182  5591  6782 E PopupManager: No content view usable to display popups. Popups will not be displayed in response to this client's calls. Use setViewForPopups() to set your content view.
,06-22 07:44:42.229  5591  6895 W GamesServiceBroker: Client connected with SDK 8487000, Services 9083236, and Games 37230036
,06-22 07:44:42.411  6620  6620 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
,06-22 07:44:42.415  5591  6894 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
06-22 07:44:42.420  6896  6896 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-22 07:44:42.501   239   239 E lowmemorykiller: Error writing /proc/6843/oom_score_adj; errno=22
,06-22 07:44:42.546  2351  2613 W Herrevad: Invalid mccmnc 
,06-22 07:44:42.555  6896  6896 I dex2oat : dex2oat took 132.010ms (threads: 4)
06-22 07:44:42.567  2351  2613 W Herrevad: Invalid mccmnc 
,06-22 07:44:42.584  6764  6780 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:42.584  6764  6780 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:42.584  6764  6780 I Adreno-EGL: Build Date: 03/02/15 Mon
06-22 07:44:42.584  6764  6780 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-22 07:44:42.584  6764  6780 I Adreno-EGL: Remote Branch: 
06-22 07:44:42.584  6764  6780 I Adreno-EGL: Local Patches: 
06-22 07:44:42.584  6764  6780 I Adreno-EGL: Reconstruct Branch: 
,06-22 07:44:42.606   842  1932 I ActivityManager: Process com.android.chrome (pid 6843) has died
,06-22 07:44:42.614  1758  1758 I PhoneApp: onTrimMemory: 15
06-22 07:44:42.614  1758  1758 I PhoneApp: trim memory
06-22 07:44:42.619  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:44:42.700  6764  6780 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:42.700  6764  6780 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:42.700  6764  6780 I Adreno-EGL: Build Date: 03/02/15 Mon
06-22 07:44:42.700  6764  6780 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-22 07:44:42.700  6764  6780 I Adreno-EGL: Remote Branch: 
06-22 07:44:42.700  6764  6780 I Adreno-EGL: Local Patches: 
06-22 07:44:42.700  6764  6780 I Adreno-EGL: Reconstruct Branch: 
,06-22 07:44:42.772  2351  3053 I art     : Explicit concurrent mark sweep GC freed 111054(6MB) AllocSpace objects, 36(599KB) LOS objects, 40% free, 14MB/24MB, paused 1.814ms total 146.406ms
,06-22 07:44:42.783  2351  2369 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3c33030f)
06-22 07:44:42.811  2351  6912 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:42.812  2351  6912 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:42.812  2351  6912 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:42.812  2351  6912 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:42.812   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:44:42.812   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:44:42.812   279  6913 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:42.813   279  6913 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-22 07:44:42.813   279  6913 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:42.813   279  6913 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-22 07:44:42.857   279  6913 D libc-netbsd: res_queryN name = xxxxx succeed
,06-22 07:44:42.858  2351  6912 I System.out: propertyValue:false
,06-22 07:44:42.930  2351  6912 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:42.930  2351  6912 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:43.008  5591  6919 I iu.SyncManager: SYNC; picasa accounts
,06-22 07:44:43.017  6869  6884 I art     : CheckpointMarkThreadRoots callback created = 0xb042df90
06-22 07:44:43.036  6869  6884 I art     : CheckpointMarkThreadRoots callback created = 0xb042df80
,06-22 07:44:43.195   842   860 E libprocessgroup: failed to kill 1 processes for processgroup 6717
,06-22 07:44:43.195   842   860 I ActivityManager: Process com.google.android.apps.magazines (pid 6717) has died
,06-22 07:44:43.227  5591  5591 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,06-22 07:44:43.235  2351  6912 I GCM     : GCM config loaded
06-22 07:44:43.238  5591  5591 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
06-22 07:44:43.257  6620  6634 W art     : Suspending all threads took: 27.471ms
,06-22 07:44:43.283  6620  6692 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,06-22 07:44:43.297   284  1604 I WVCdm   : CdmEngine::OpenSession
,06-22 07:44:43.326  5591  6919 I iu.UploadsManager: num queued entries: 0
,06-22 07:44:43.329  5591  6919 I iu.UploadsManager: num updated entries: 0
06-22 07:44:43.330  5591  6919 I iu.SyncManager: NEXT; no task
,06-22 07:44:43.428  2351  6930 I VacuumService: Vacuum at: now=1466574283428 tag=VacuumService
,06-22 07:44:43.432  5591  6929 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
06-22 07:44:43.432  5591  6929 D SchedPeriodicTask: Scheduled AdAttestation task.
06-22 07:44:43.484   842  1944 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6931 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,06-22 07:44:43.512   295   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-22 07:44:43.599  6931  6931 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-22 07:44:43.656   842  1859 I ActivityManager: Process com.google.android.play.games.ui (pid 6807) has died
,06-22 07:44:43.708   842   942 I NotificationManager: android: cancelAsUser(-1874035846) by android
,06-22 07:44:43.711  6620  6699 I art     : Explicit concurrent mark sweep GC freed 9989(365KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 10MB/14MB, paused 768us total 74.917ms
06-22 07:44:43.803   842   942 I NotificationManager: android: cancelAsUser(1500439826) by android
,06-22 07:44:43.818  6620  6699 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 24226, normalSync: true
,06-22 07:44:43.821  6620  6699 I Gmail   : lowestBackward conversation id 0
06-22 07:44:43.841   842  1026 D BluetoothManagerService: Message: 20
06-22 07:44:43.841   842  1026 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32fbb60c:true
06-22 07:44:43.841  2351  2613 V NQFileLogger: [185] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
,06-22 07:44:43.855   842   942 I ActivityManager: Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6949 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:43.890  2055  2070 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
,06-22 07:44:43.892  2055  2071 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:44:43.948   842  1820 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6967 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,06-22 07:44:43.970   310   310 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 280us total 22.221ms
,06-22 07:44:43.975   842  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{185a00d type 2 when 158976 com.android.systemui} when 158976
06-22 07:44:43.992   310   310 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.122ms
,06-22 07:44:44.015   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 21.995ms
,06-22 07:44:44.025  2351  2613 V ProcessReports: [185] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
06-22 07:44:44.086  6620  6620 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
,06-22 07:44:44.088  6620  6620 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
06-22 07:44:44.161  5591  6984 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-22 07:44:44.216   284  1320 I WVCdm   : CdmEngine::CloseSession
,06-22 07:44:44.249  6949  6949 I MusicStore: Database version: 120
,06-22 07:44:44.282  6620  6699 I Gmail   : notifyAccountChanged
,06-22 07:44:44.285  6620  6696 I Gmail   : getAccountsCursor
06-22 07:44:44.287   284  1604 I WVCdm   : CdmEngine::QueryKeyControlInfo
06-22 07:44:44.289   284   284 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-22 07:44:44.289   284   284 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-22 07:44:44.289   284   284 I WVCdm   : CdmEngine::GenerateKeyRequest
06-22 07:44:44.294   284   284 D WVCdm   : PrepareKeyRequest: nonce=795100719
06-22 07:44:44.314  6620  6699 I Gmail   : notifyAccountChanged
06-22 07:44:44.315  6967  6967 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
06-22 07:44:44.316  6620  6690 I Gmail   : getAccountsCursor
,06-22 07:44:44.318  6620  6699 W Gmail   : Sync complete for account: account:61035162
06-22 07:44:44.337  2801  2801 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 7:44:44
,06-22 07:44:44.343   842   942 I NotificationManager: android: cancelAsUser(1479798955) by android
06-22 07:44:44.347  2801  2801 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-22 07:44:44.352  2801  2801 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
,06-22 07:44:44.352  2801  2801 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 7:44:44
06-22 07:44:44.352  2801  2801 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
06-22 07:44:44.355  2801  2801 D WeatherService: 2 : shouldTimeTickRegistered : false
06-22 07:44:44.520   842  1908 I art     : Explicit concurrent mark sweep GC freed 29647(1245KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.295ms total 158.648ms
,06-22 07:44:44.531   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:44.531   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-22 07:44:44.531   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:44.532  6949  6949 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,06-22 07:44:44.623  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:44:44.638  2351  2351 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=a44c24d0-1c5e-49f7-bf66-72b7e55dd6de
,06-22 07:44:44.665   284  1320 I WVCdm   : CdmEngine::OpenSession
,06-22 07:44:44.692  1945  1945 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
06-22 07:44:44.719   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:44.719   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-22 07:44:44.719   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:44.721  6949  6949 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,06-22 07:44:44.724   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:44.724   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-22 07:44:44.724   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:44.726  6949  6949 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-22 07:44:44.745  5591  5591 I art     : Explicit concurrent mark sweep GC freed 31221(2MB) AllocSpace objects, 25(400KB) LOS objects, 24% free, 16MB/21MB, paused 1.982ms total 183.260ms
,06-22 07:44:44.772   842  1859 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6999 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,06-22 07:44:44.778  1945  2680 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
06-22 07:44:44.778  1945  2680 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
06-22 07:44:44.778  1945  2680 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,06-22 07:44:44.794  1945  2680 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
06-22 07:44:44.795  1945  2680 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
06-22 07:44:44.807  2026  2026 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,06-22 07:44:44.856   842   860 I ActivityManager: Process com.google.android.apps.plus (pid 6869) has died
,06-22 07:44:44.867  1758  1758 I PhoneApp: onTrimMemory: 15
06-22 07:44:44.868  1758  1758 I PhoneApp: trim memory
06-22 07:44:44.893  2351  2648 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-22 07:44:44.901  2351  2613 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
06-22 07:44:44.902  6949  6949 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-22 07:44:44.902  6949  6949 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-22 07:44:44.930  5553  5568 I art     : Explicit concurrent mark sweep GC freed 2599(103KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 838us total 27.291ms
,06-22 07:44:44.960  2351  2613 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
06-22 07:44:44.966  2351  2351 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-22 07:44:44.979  6949  6949 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-22 07:44:45.064  6949  6949 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
06-22 07:44:45.065  6949  6949 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@109165c7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,06-22 07:44:45.071  6949  6949 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-22 07:44:45.071  6949  6949 D AndroidMusic: GMSCore installation verified
06-22 07:44:45.080  6949  6949 I ConfigStore: Config Database version: 1
,06-22 07:44:45.118  6764  6864 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:45.118  6764  6864 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:45.118  6764  6864 I Adreno-EGL: Build Date: 03/02/15 Mon
06-22 07:44:45.118  6764  6864 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-22 07:44:45.118  6764  6864 I Adreno-EGL: Remote Branch: 
06-22 07:44:45.118  6764  6864 I Adreno-EGL: Local Patches: 
06-22 07:44:45.118  6764  6864 I Adreno-EGL: Reconstruct Branch: 
06-22 07:44:45.176  5591  6985 D UdcContextInitService: registered all accounts: true
,06-22 07:44:45.205  6764  6864 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:45.205  6764  6864 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:45.205  6764  6864 I Adreno-EGL: Build Date: 03/02/15 Mon
06-22 07:44:45.205  6764  6864 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-22 07:44:45.205  6764  6864 I Adreno-EGL: Remote Branch: 
06-22 07:44:45.205  6764  6864 I Adreno-EGL: Local Patches: 
06-22 07:44:45.205  6764  6864 I Adreno-EGL: Reconstruct Branch: 
,06-22 07:44:45.243  5591  5631 I Icing   : Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,06-22 07:44:45.272  6764  6864 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:45.272  6764  6864 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:45.272  6764  6864 I Adreno-EGL: Build Date: 03/02/15 Mon
06-22 07:44:45.272  6764  6864 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-22 07:44:45.272  6764  6864 I Adreno-EGL: Remote Branch: 
06-22 07:44:45.272  6764  6864 I Adreno-EGL: Local Patches: 
06-22 07:44:45.272  6764  6864 I Adreno-EGL: Reconstruct Branch: 
,06-22 07:44:45.356   842  1820 I ActivityManager: Process com.lge.clock (pid 6967) has died
,06-22 07:44:45.369   842   942 I NotificationManager: android: cancelAsUser(-379682945) by android
,06-22 07:44:45.378  6949  6949 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,06-22 07:44:45.418   842   942 I ActivityManager: Start proc com.lge.qmemoplus for service com.lge.qmemoplus/.network.googledrive.DriveSyncService: pid=7025 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
06-22 07:44:45.421  6999  6999 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
,06-22 07:44:45.433  6999  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
06-22 07:44:45.453  1374  1374 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
06-22 07:44:45.453  1374  1374 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
06-22 07:44:45.454  1374  1374 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
,06-22 07:44:45.458  1330  1330 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
,06-22 07:44:45.488  6999  6999 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
,06-22 07:44:45.503  6999  6999 V [BNRBootReceiver]: Boot Receiver Return
,06-22 07:44:45.507  6999  6999 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-22 07:44:45.531  6949  6949 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,06-22 07:44:45.532  6949  6963 I art     : CheckpointMarkThreadRoots callback created = 0xb042d430
06-22 07:44:45.541  5591  5631 I Icing   : Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
06-22 07:44:45.545  6949  6949 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
06-22 07:44:45.551  7025  7025 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-22 07:44:45.564  2351  6986 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:45.564  2351  6986 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:45.565  6949  6949 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
06-22 07:44:45.565  2351  6986 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:45.565  2351  6986 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:45.565   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:44:45.565   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:44:45.565   279  7046 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,06-22 07:44:45.566   279  7046 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:45.566   279  7046 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:45.566   279  7046 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:45.566   279  7046 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:45.576  6949  6963 I art     : CheckpointMarkThreadRoots callback created = 0xb042d410
,06-22 07:44:45.594  2351  6986 I System.out: propertyValue:false
06-22 07:44:45.611  6949  7047 I MusicLifecycle: Sync started
,06-22 07:44:45.637  7025  7025 E App     : [App][onCreate()] 4.40.23
,06-22 07:44:45.646  6949  6949 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
06-22 07:44:45.659  6949  6949 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,06-22 07:44:45.665  6949  6949 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
06-22 07:44:45.741  5591  7044 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,06-22 07:44:45.784  6949  6990 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,06-22 07:44:45.789  2351  6986 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:45.790  2351  6986 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:45.848   842  2596 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7055 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-22 07:44:46.037  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:44:46.054   842  1383 I NotificationManager: android: cancelAsUser(2) by android
,06-22 07:44:46.060  7025  7025 D AccountManager: setSyncFrequency
06-22 07:44:46.064  7055  7055 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-22 07:44:46.068  6949  7047 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:46.068  6949  7047 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:46.083  6949  7047 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:46.083  6949  7047 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-22 07:44:46.086   279  1053 E BandwidthController: [LG DATA] No such appUid: 10081
06-22 07:44:46.086   279  1053 D DnsProxyListener: App 10081 tries DNS query. Accept family:0 protocol:0
06-22 07:44:46.086   279  7077 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:46.086   279  7077 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:46.086   279  7077 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:46.087   279  7077 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:46.129   279  7077 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:46.129  7025  7025 D DriveSyncService: onCreate
06-22 07:44:46.130  7025  7025 D DriveSyncService: onBind
,06-22 07:44:46.133  6949  7047 I System.out: propertyValue:false
06-22 07:44:46.138  7025  7078 D DriveSyncAdapter: onPerformSync() START
06-22 07:44:46.138  7025  7078 D DriveSyncAdapter: Not added account. Stop
06-22 07:44:46.146   842   942 I NotificationManager: android: cancelAsUser(1312559638) by android
,06-22 07:44:46.220  6949  7047 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:46.220  6949  7047 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:46.343  2351  7080 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-22 07:44:46.346  2351  7080 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
06-22 07:44:46.350  2351  7080 V BaseAppContext: GmsRequestQueue started.
06-22 07:44:46.357  2351  7083 E CommitToConfigurationOperation: Malformed snapshot token: 
,06-22 07:44:46.361  2351  7075 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
06-22 07:44:46.439  2351  7083 E CommitToConfigurationOperation: Malformed snapshot token: 
06-22 07:44:46.439  2351  7075 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,06-22 07:44:46.455  7055  7093 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
06-22 07:44:46.455  7055  7093 I Babel_SMS: MmsConfig.loadMmsSettings
,06-22 07:44:46.457  7055  7093 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-22 07:44:46.457  7055  7093 I Babel_SMS: MmsConfig.loadFromDatabase
06-22 07:44:46.473  2351  7083 E CommitToConfigurationOperation: Malformed snapshot token: 
,06-22 07:44:46.485  2351  7075 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
06-22 07:44:46.485  2351  7075 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
06-22 07:44:46.490  2351  7075 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-22 07:44:46.495  7055  7093 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
06-22 07:44:46.495  7055  7093 I Babel_SMS: MmsConfig.loadFromResources
06-22 07:44:46.508  7055  7093 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,06-22 07:44:46.509  7055  7093 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-22 07:44:46.549  2351  7080 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:46.549  2351  7080 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:46.561   284  1298 I WVCdm   : CdmEngine::CloseSession
,06-22 07:44:46.626  2351  7080 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:46.626  2351  7080 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:46.647   284  1320 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-22 07:44:46.650   284  1604 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-22 07:44:46.650   284  1604 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-22 07:44:46.650   284  1604 I WVCdm   : CdmEngine::GenerateKeyRequest
06-22 07:44:46.657  7055  7070 I art     : CheckpointMarkThreadRoots callback created = 0xaaf22d70
06-22 07:44:46.660   284  1604 D WVCdm   : PrepareKeyRequest: nonce=315403967
,06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
06-22 07:44:46.668  7055  7055 D SensorManager: found sensor: Motion Accel, handle=46
06-22 07:44:46.697  7055  7070 I art     : CheckpointMarkThreadRoots callback created = 0xaaf22d60
,06-22 07:44:46.702  7055  7055 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:44:46.716  7055  7070 W art     : Suspending all threads took: 8.686ms
,06-22 07:44:46.725  2351  7075 I art     : Explicit concurrent mark sweep GC freed 70622(3MB) AllocSpace objects, 18(288KB) LOS objects, 39% free, 15MB/25MB, paused 10.350ms total 205.981ms
06-22 07:44:46.739  7055  7055 I Babel_Crash: startup - clean
,06-22 07:44:46.782  7055  7098 I Babel   : deleted: false for 0
,06-22 07:44:46.801   842  1932 I NotificationManager: android: cancelAsUser(2) by android
,06-22 07:44:46.820  6949  7047 I MusicSyncAdapter: Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
06-22 07:44:46.820  6949  7047 I MusicSyncAdapter: Periodic update
,06-22 07:44:46.829  2351  7080 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
06-22 07:44:46.851   842   860 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:46.898  6949  7064 W MusicApiClient: Activity events list is null or empty. Skip reporting.
,06-22 07:44:46.926  2351  7086 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:46.927  2351  7086 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:46.927  2351  7086 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:46.927  2351  7086 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:46.927   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:44:46.927   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:44:46.929   279  7102 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:46.929   279  7102 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:46.929   279  7102 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:46.930   279  7102 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:46.930   279  7102 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:46.930  2351  7086 I System.out: propertyValue:false
06-22 07:44:47.028  7055  7055 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,06-22 07:44:47.037  7055  7055 W AudioCapabilities: Unsupported mime audio/adpcm
06-22 07:44:47.038  7055  7055 W AudioCapabilities: Unsupported mime audio/g726
06-22 07:44:47.041  7055  7055 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,06-22 07:44:47.044  7055  7055 W AudioCapabilities: Unsupported mime audio/wma-voice
06-22 07:44:47.049  7055  7055 W VideoCapabilities: Unsupported mime video/mjpg
06-22 07:44:47.057  7055  7055 W VideoCapabilities: Unsupported mime video/theora
,06-22 07:44:47.090   842  2009 I art     : Explicit concurrent mark sweep GC freed 23964(1076KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.521ms total 182.675ms
,06-22 07:44:47.106  6949  7047 I MusicLifecycle: Sync ended
,06-22 07:44:47.114  7055  7055 W AudioCapabilities: Unsupported mime audio/evrc
06-22 07:44:47.117  7055  7055 W AudioCapabilities: Unsupported mime audio/qcelp
06-22 07:44:47.118  7055  7055 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:44:47.132  7055  7055 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,06-22 07:44:47.133  7055  7055 W AudioCapabilities: Unsupported mime audio/qcelp
06-22 07:44:47.137  7055  7055 W AudioCapabilities: Unsupported mime audio/evrc
06-22 07:44:47.146  2351  7075 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:47.146  2351  7075 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:47.147  2351  7075 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:47.147  2351  7075 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:47.147   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:44:47.147   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,06-22 07:44:47.147   279  7104 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:47.147   279  7104 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:47.148   279  7104 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:44:47.148   279  7104 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:47.151   842   942 I NotificationManager: android: cancelAsUser(-1123058983) by android
06-22 07:44:47.165  7055  7055 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,06-22 07:44:47.183   279  7104 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:47.183  2351  7075 I System.out: propertyValue:false
06-22 07:44:47.204  7055  7055 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-22 07:44:47.213  7055  7055 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-22 07:44:47.219  7055  7055 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:44:47.224  7055  7055 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:44:47.231  7055  7055 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:44:47.239   842  1944 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7107 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:47.268  7055  7055 I vclib   : onServiceConnected
,06-22 07:44:47.270  7055  7055 W Babel   : Attempted to change video mute state without an active call.
06-22 07:44:47.293  7055  7055 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,06-22 07:44:47.298  6931  6931 V LGMDMManager: Create singleton instance
,06-22 07:44:47.392  6931  6931 I AudioManager: getMode name:com.lge.qremote
,06-22 07:44:47.398  7107  7107 D UEI.SmartControl: Quickset Services start...
06-22 07:44:47.417  2351  7080 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
06-22 07:44:47.417  7107  7107 I UEI.SmartControl: Manufacture = LGE
,06-22 07:44:47.434  7107  7107 D UEI.SmartControl: File observer start...
,06-22 07:44:47.438  1374  1374 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
06-22 07:44:47.443  7107  7107 E UEI.SmartControl: IR Port is disabled: false
06-22 07:44:47.443  7107  7107 D UEI.SmartControl: Starting file observer...
06-22 07:44:47.444  7107  7107 D UEI.SmartControl: Extracting JNI libs...
06-22 07:44:47.447  7107  7107 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,06-22 07:44:47.472   842   860 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:47.488  1758  2319 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
06-22 07:44:47.500  1758  2319 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-22 07:44:47.500  1758  2319 D PhoneUtils: getPhoneCount() sPhoneCount = 1
,06-22 07:44:47.511  1758  2319 V TelecomServiceImpl: getCallState : 0
,06-22 07:44:47.512  1758  1780 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
06-22 07:44:47.512  1758  1780 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-22 07:44:47.512  1758  1780 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-22 07:44:47.518  1374  1374 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
06-22 07:44:47.519  1374  1374 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
06-22 07:44:47.545   842   942 I NotificationManager: android: cancelAsUser(-1548111331) by android
,06-22 07:44:47.560   842   942 I NotificationManager: android: cancelAsUser(1222422273) by android
06-22 07:44:47.637  1945  1945 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
06-22 07:44:47.641  1945  2098 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,06-22 07:44:47.647  1945  2098 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
06-22 07:44:47.648  1945  2098 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
06-22 07:44:47.649  1945  2098 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
06-22 07:44:47.649  1945  2098 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
06-22 07:44:47.655  2351  2613 I GCoreUlr: DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
06-22 07:44:47.681  6764  6780 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 07:44:47.681  6764  6780 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:44:47.681  6764  6780 I Adreno-EGL: Build Date: 03/02/15 Mon
06-22 07:44:47.681  6764  6780 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-22 07:44:47.681  6764  6780 I Adreno-EGL: Remote Branch: 
06-22 07:44:47.681  6764  6780 I Adreno-EGL: Local Patches: 
06-22 07:44:47.681  6764  6780 I Adreno-EGL: Reconstruct Branch: 
,06-22 07:44:47.715   842   859 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=7130 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:47.748  2351  2613 I GCoreUlr: Unbound from all location providers
,06-22 07:44:47.761   842  1859 I NotificationManager: android: cancelAsUser(2) by android
,06-22 07:44:47.809  5591  6576 I CheckinUtil: Classify the device as Phone.
06-22 07:44:47.819  2351  7075 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-22 07:44:47.890  5553  6383 I art     : Explicit concurrent mark sweep GC freed 2826(110KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 510us total 32.058ms
,06-22 07:44:47.900   842   942 I NotificationManager: android: cancelAsUser(-1816247584) by android
,06-22 07:44:48.008  7107  7107 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,06-22 07:44:48.009  7107  7107 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,06-22 07:44:48.009  7107  7107 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
06-22 07:44:48.065  7107  7107 I UEI.SmartControl: --- Selecting new region: 2
06-22 07:44:48.065  7107  7107 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
06-22 07:44:48.071  7107  7107 D UEI.SmartControl: Platform has CIR...
06-22 07:44:48.072  7107  7107 D UEI.SmartControl: NO CIR support, need to check package...
06-22 07:44:48.073  7107  7107 I UEI.SmartControl: Model: LG-D722 uses JNI
06-22 07:44:48.075  7107  7107 D UEI.SmartControl: QS Service created
,06-22 07:44:48.116   842  1893 I ActivityManager: Process com.google.android.talk (pid 7055) has died
06-22 07:44:48.119  2026  2026 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,06-22 07:44:48.127  1758  1758 I PhoneApp: onTrimMemory: 10
06-22 07:44:48.127  1758  1758 I PhoneApp: trim memory
06-22 07:44:48.150   842   942 I NotificationManager: android: cancelAsUser(898701380) by android
,06-22 07:44:48.173  7107  7107 E UEI.SmartControl: QS start get config
,06-22 07:44:48.203  2351  2351 I GCoreUlr: DispatchingService.onDestroy()
06-22 07:44:48.204  2351  2351 I GCoreUlr: Stopping handler for UlrDispSvcFast
,06-22 07:44:48.222  2351  2351 I GCoreUlr: Unbound from all location providers
,06-22 07:44:48.226  5591  7154 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
06-22 07:44:48.226  5591  6576 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:48.226  5591  6576 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:44:48.227  5591  6576 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:48.227  5591  6576 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:48.227   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:44:48.227   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:44:48.227   279  7156 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:44:48.227   279  7156 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:44:48.228   279  7156 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-22 07:44:48.228   279  7156 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:44:48.228   279  7156 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:44:48.229  5591  6576 I System.out: propertyValue:false
06-22 07:44:48.239  2351  2648 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-22 07:44:48.242  2351  2648 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-22 07:44:48.246  7107  7107 D UEI.SmartControl: Loading JNI Libs...
06-22 07:44:48.248  7107  7107 D UEI.SmartControl:  configuring local db...
,06-22 07:44:48.288   842   942 I NotificationManager: android: cancelAsUser(-591465577) by android
06-22 07:44:48.332  5591  6576 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:44:48.332  5591  6576 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:44:48.406  7130  7130 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
,06-22 07:44:48.433  5591  6576 I CheckinTask: Sending checkin request (13124 bytes)
,06-22 07:44:48.517   295   354 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-22 07:44:48.522  7107  7107 D UEI.SmartControl:  ---- Has DB8: true
06-22 07:44:48.530  7107  7107 D UEI.SmartControl: QS start statue = true Error code = 0
,06-22 07:44:48.531  7107  7107 D UEI.SmartControl: QS version = v2.7.11.1_RC1
06-22 07:44:48.531  7107  7107 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
06-22 07:44:48.535  7107  7107 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
06-22 07:44:48.566  7107  7107 W irrc_jni: IRRCPlayer_nativeInit ++ 
06-22 07:44:48.566  7107  7107 D irrcClient: IrrcClient ++ 
,06-22 07:44:48.566  7107  7107 D irrcClient: getIrrcService ++ 
06-22 07:44:48.567  7107  7107 D irrcClient: getIrrcService -- 
06-22 07:44:48.567  7107  7107 D irrcClient: IrrcClient -- 
06-22 07:44:48.567  7107  7107 W irrc_jni: IRRCPlayer_nativeInit -- 
06-22 07:44:48.574  7107  7107 D UEI.SmartControl: Services init done
06-22 07:44:48.577  7107  7166 I UEI.SmartControl: Device manager: loading config....
,06-22 07:44:48.579  7107  7107 D UEI.SmartControl: QS Service init finished
06-22 07:44:48.581  7107  7107 D UEI.SmartControl: QS Service version name: 0.1.73
06-22 07:44:48.581  7107  7107 D UEI.SmartControl: QS Service version code: 1073
06-22 07:44:48.597  7107  7107 D UEI.SmartControl: Service requested: Control
,06-22 07:44:48.601  7107  7166 D UEI.SmartControl: Config is loaded...
,06-22 07:44:48.616  7107  7165 D UEI.SmartControl:  ----- QS SDK is ready!!!
06-22 07:44:48.618  7107  7165 I UEI.SmartControl: Notify AllClients services are ready: 0
,06-22 07:44:48.646  7107  7107 D UEI.SmartControl: Request IControl service: devices are loaded...
,06-22 07:44:48.648  7107  7107 D UEI.SmartControl: Service.onTrimMemory: 10
06-22 07:44:48.648  7107  7107 E UEI.SmartControl: Setup service releasing memory...
06-22 07:44:48.651  7107  7123 D UEI.SmartControl: -----IControl: 11
06-22 07:44:48.652  7107  7123 D UEI.SmartControl: Caller: com.lge.qremote
06-22 07:44:48.654  7107  7123 D UEI.SmartControl: ------------ IControl registerCallback...
06-22 07:44:48.654  7107  7123 I UEI.SmartControl: Registering callback...
06-22 07:44:48.656  7107  7124 D UEI.SmartControl: -----IControl: 19
06-22 07:44:48.662  7107  7124 D UEI.SmartControl: Caller: com.lge.qremote
06-22 07:44:48.663  7107  7124 I UEI.SmartControl: Registering Services Ready callback...
06-22 07:44:48.664  7107  7124 I UEI.SmartControl: Notify client services are ready...
06-22 07:44:48.669  7107  7123 D UEI.SmartControl: -----IControl: 8
06-22 07:44:48.670  7107  7123 D UEI.SmartControl: Caller: com.lge.qremote
,06-22 07:44:48.681  7130  7130 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(171): No need to run daily hygiene.
06-22 07:44:48.697  7107  7107 I art     : Explicit concurrent mark sweep GC freed 10605(755KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 396us total 47.617ms
,06-22 07:44:48.699  7107  7107 D UEI.SmartControl: Internal service binding...
06-22 07:44:48.705  7130  7130 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-22 07:44:48.706  7130  7130 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-22 07:44:48.710  7130  7130 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
,06-22 07:44:48.732  7130  7130 I Finsky  : [1] com.google.android.finsky.utils.bk.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,06-22 07:44:48.765  7130  7130 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 10
06-22 07:44:48.767  2538  2559 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
06-22 07:44:48.769  2538  2559 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@8a1bfc9 on behalf of 7130
,06-22 07:44:48.777  7130  7130 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1226): Installer kick - no action, not running yet
06-22 07:44:48.780  7130  7130 I Finsky  : [1] com.google.android.finsky.j.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
06-22 07:44:48.780  7130  7130 I Finsky  : [1] com.google.android.finsky.j.j.run(214): Finished loading 1 libraries.
06-22 07:44:48.787  7130  7130 I Finsky  : [1] com.google.android.finsky.c.l.a(270): result=false type=4
,06-22 07:44:48.804   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:48.804   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-22 07:44:48.804   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:48.808  6949  7051 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-22 07:44:48.824  6931  6931 I AudioManager: getMode name:com.lge.qremote
,06-22 07:44:48.839   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:44:48.839   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
06-22 07:44:48.839   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:48.842  6949  7051 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
06-22 07:44:48.855  7130  7130 I Finsky  : [1] com.google.android.finsky.services.bc.a(1050): Restore complete with 0 success and 0 failed.
,06-22 07:44:49.017   842  1893 I ActivityManager: Process com.lge.bnr (pid 6999) has died
,06-22 07:44:49.022  7107  7107 D UEI.SmartControl: Service.onTrimMemory: 80
06-22 07:44:49.022  7107  7107 E UEI.SmartControl: Setup service releasing memory...
06-22 07:44:49.024  7130  7130 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 10
06-22 07:44:49.026  1758  1758 I PhoneApp: onTrimMemory: 10
06-22 07:44:49.026  1758  1758 I PhoneApp: trim memory
06-22 07:44:49.027  2026  2026 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
06-22 07:44:49.028  5591  6576 I CheckinResponseProcessor: From server: 5 gservices updates and 0 deletes
06-22 07:44:49.031  7130  7130 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 60
,06-22 07:44:49.073  6949  7184 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
06-22 07:44:49.073  6949  7184 I MusicLeanback: Stop autocaching.
,06-22 07:44:49.132   284  1321 I WVCdm   : CdmEngine::CloseSession
,06-22 07:44:49.136   284  1321 I WVCdm   : L3 Terminate.
06-22 07:44:49.198   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,06-22 07:44:49.198   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
06-22 07:44:49.198   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:49.199  6949  7191 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
06-22 07:44:49.213  6931  6931 I AudioManager: getMode name:com.lge.qremote
,06-22 07:44:49.214  7130  7130 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 80
06-22 07:44:49.220  2351  2351 D WearableService: callingUid 10006, callindPid: 2351
06-22 07:44:49.249  6931  6931 I AudioManager: getMode name:com.lge.qremote
,06-22 07:44:49.253  6949  6949 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
06-22 07:44:49.254  6949  7195 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
06-22 07:44:49.256  7107  7107 D UEI.SmartControl: Service.onTrimMemory: 80
06-22 07:44:49.257  7107  7107 E UEI.SmartControl: Setup service releasing memory...
,06-22 07:44:49.347   842  7196 I CertBlacklister: Certificate blacklist changed, updating...
,06-22 07:44:49.358  5553  7099 I GservicesProvider: main difference update completed
06-22 07:44:49.360  5591  6576 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,06-22 07:44:49.384   842  7196 I CertBlacklister: Certificate blacklist updated
,06-22 07:44:49.409   842   970 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=7197 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,06-22 07:44:49.427  5591  6576 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,06-22 07:44:49.603   842   860 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=7222 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,06-22 07:44:49.832  7222  7222 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-22 07:44:49.850  7222  7222 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-22 07:44:49.855  7222  7222 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
06-22 07:44:49.859  7222  7222 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
06-22 07:44:49.906   842  1383 I art     : Explicit concurrent mark sweep GC freed 28362(1241KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.164ms total 169.444ms
,06-22 07:44:49.959  2026  4277 I GservicesUpdateTask: Updating Gservices keys
,06-22 07:44:49.983  5591  7255 D GmsModuleFndr: Beginning GMS chimera module scan
,06-22 07:44:49.990  5591  7255 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
06-22 07:44:49.991  5591  7255 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
06-22 07:44:50.014  5591  7255 D ChimeraCfgMgr: Beginning module configuration check
,06-22 07:44:50.037  5591  7258 D PeriodicTasksManager: Got new setting, will re-schedule periodic tasks.
,06-22 07:44:50.068  5591  7255 D ChimeraCfgMgr: Module APKs unchanged, check complete
,06-22 07:44:50.082  5553  5642 I art     : Explicit concurrent mark sweep GC freed 11166(561KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.343ms total 43.797ms
,06-22 07:44:50.096  5591  6576 I CheckinUtil: Classify the device as Phone.
,06-22 07:44:50.100  5591  7258 D PeriodicTasksManager: Scheduling periodical signal task every 86400 seconds
06-22 07:44:50.120  5591  7258 D PeriodicTasksManager: AdAttestation signal task scheduled
,06-22 07:44:50.138  5591  5591 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,06-22 07:44:50.206  2351  7263 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,06-22 07:44:50.220  5591  6576 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,06-22 07:44:50.237  5591  6576 I CheckinChimeraService: Checking schedule, now: 1466574290237 next: 1467101539220
06-22 07:44:50.237  5591  6576 I CheckinChimeraService: active receiver: disabled
,06-22 07:44:50.327  5553  5642 I art     : Explicit concurrent mark sweep GC freed 3609(146KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 396us total 24.246ms
,06-22 07:44:50.525  5591  5591 I art     : Explicit concurrent mark sweep GC freed 10443(676KB) AllocSpace objects, 9(144KB) LOS objects, 25% free, 16MB/22MB, paused 1.277ms total 89.805ms
,06-22 07:44:50.542  5591  5604 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,06-22 07:44:50.582  5553  6301 I art     : Explicit concurrent mark sweep GC freed 2521(99KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 395us total 24.150ms
,06-22 07:44:50.593   842  2009 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:50.660  5591  7268 I CheckinChimeraService: Checking schedule, now: 1466574290660 next: 1467101539220
06-22 07:44:50.661  5591  7268 I CheckinChimeraService: active receiver: disabled
,06-22 07:44:50.689  5591  5591 D CheckinChimeraService: Recording last checkin time for package unspecified as 1466574290685
,06-22 07:44:50.700  5591  5591 D GoogleSignatureVerifier: Package manager can't find package com.google.android.apps.work.core, defaulting to false
06-22 07:44:50.769  5591  7272 I CheckinChimeraService: Checking schedule, now: 1466574290769 next: 1467101539220
,06-22 07:44:50.771  5591  7272 I CheckinChimeraService: active receiver: disabled
06-22 07:44:50.787   842   860 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:50.863  5591  5591 I DynamiteModule: Considering local module com.google.android.gms.flags:0 and remote module com.google.android.gms.flags:1
06-22 07:44:50.863  5591  5591 I DynamiteModule: Selected remote version of com.google.android.gms.flags, version >= 1
,06-22 07:44:50.909  2351  2351 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,06-22 07:44:50.922   842  2033 W ActivityManager: Unable to start service Intent { act=com.google.android.gms.measurement.REFRESH_ENABLED_STATE pkg=com.google.android.gms } U=0: not found
,06-22 07:44:50.958   842   942 I NotificationManager: android: cancelAsUser(-591465577) by android
06-22 07:44:50.985  2351  2611 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,06-22 07:44:51.004  5591  5591 D OcrModelBroadcastRcvr: com.google.gservices.intent.action.GSERVICES_CHANGED
,06-22 07:44:51.004  5591  5591 D OcrModelBroadcastRcvr: Updating OCR activity and model state
06-22 07:44:51.016  5591  5591 I CmaSystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
06-22 07:44:51.018  5591  5591 I CmaSystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
06-22 07:44:51.039  5591  7281 V PrereqChecker: Build version: 21
06-22 07:44:51.040  5591  7281 V PrereqChecker: Model: LG-D722
06-22 07:44:51.040  5591  7281 V PrereqChecker: CPU_ABI: armeabi-v7a
,06-22 07:44:51.040  5591  7281 V PrereqChecker: CPU_ABI2: armeabi
06-22 07:44:51.045  5553  5642 I art     : Explicit concurrent mark sweep GC freed 2935(116KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.859ms total 31.968ms
06-22 07:44:51.045  5591  5591 D CmaSystemUpdateService: onCreate
06-22 07:44:51.045  5591  5591 D CmaSystemUpdateService: mProcessPackageEnabled: false, mAutomaticUpdateEnabled: false
06-22 07:44:51.050  5591  7281 V PrereqChecker: Camera #0 is a rear-facing camera.
06-22 07:44:51.051  5591  7281 D CreditCardPrerequisiteChecker: All prerequisites OK.
06-22 07:44:51.051  5591  7281 I OcrModelUpdtStIntSvc: Updating ocr activity enabled=false (gservicesFlag=false, lowRamDevice=false, prereqCheck=true)
,06-22 07:44:51.053  5591  5591 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) }
,06-22 07:44:51.068  5591  7284 I SystemUpdateTask: cancelUpdate (empty URL)
06-22 07:44:51.068  5591  7284 I CmaSystemUpdateService: active receiver: disabled
,06-22 07:44:51.083  5591  7284 I NotificationManager: com.google.android.gms: cancel(2130838238) by com.google.android.gms
,06-22 07:44:51.084  5591  7284 I NotificationManager: com.google.android.gms: cancel(2130838239) by com.google.android.gms
06-22 07:44:51.114  5591  5591 D CmaSystemUpdateService: onDestroy
,06-22 07:44:51.221  2351  2611 I art     : Explicit concurrent mark sweep GC freed 106314(5MB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 17MB/29MB, paused 12.257ms total 160.905ms
,06-22 07:44:51.303  6949  7288 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
06-22 07:44:51.303  6949  7288 I MusicLeanback: Stop autocaching.
,06-22 07:44:51.369   842  1820 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7291 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,06-22 07:44:51.396  6949  6949 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-22 07:44:51.402  6949  7302 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-22 07:44:51.409  2351  2611 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,06-22 07:44:51.419  2351  2611 I GCoreUlr: Unbound from all location providers
,06-22 07:44:51.429  2351  2351 I GCoreUlr: DispatchingService.onDestroy()
06-22 07:44:51.429  2351  2351 I GCoreUlr: Stopping handler for UlrDispSvcFast
06-22 07:44:51.436  2351  2351 I GCoreUlr: Unbound from all location providers
,06-22 07:44:51.507  7291  7291 D PhoneMonitor: Register our PhoneStateListener
,06-22 07:44:51.535  7291  7291 V SetupWizard: Connected to Gservices successfully
,06-22 07:44:51.554  7291  7291 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
06-22 07:44:51.559  7291  7291 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
06-22 07:44:51.559  7291  7291 D TelephonyAutoProfiling: [parse] Load xml
06-22 07:44:51.566  7291  7291 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
06-22 07:44:51.567  7291  7291 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,06-22 07:44:51.579  7291  7291 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
06-22 07:44:51.636   842  1944 I ActivityManager: Process com.google.android.gm (pid 6620) has died
,06-22 07:44:51.666  2351  7315 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,06-22 07:44:51.679  2351  4478 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,06-22 07:44:51.742   842  1944 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:51.915   842  1859 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:51.961  5591  7319 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,06-22 07:44:51.962  5591  7319 D SchedPeriodicTask: Scheduled AdAttestation task.
06-22 07:44:52.039   842   860 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:52.195   842  2009 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:52.302   842  1908 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:52.449   842  1893 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:52.591   842  1893 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:52.704   842  1893 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:52.894   842   860 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:53.064   842  2009 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:53.223   842  1282 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:53.389   842  2596 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:53.521   295   354 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-22 07:44:53.537   842  1820 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:53.576  7107  7167 D UEI.SmartControl: Internal timer expired: 1
,06-22 07:44:53.672   842   860 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:53.780   842  1908 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:53.892   842  1893 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:54.048   842  1859 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-22 07:44:56.445  2351  7149 D PlaceInferenceEngine: Stop called when not running
,06-22 07:44:56.456  2351  2648 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-22 07:44:56.495  5591  6572 I CheckinService: Done disabling old GoogleServicesFramework version
,06-22 07:44:57.002   842   842 I art     : Explicit concurrent mark sweep GC freed 29271(1397KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 4.225ms total 221.188ms
,06-22 07:44:57.131   842  1893 I ActivityManager: Killing 7025:com.lge.qmemoplus/1000 (adj 15): empty #11
,06-22 07:44:57.162   842  1908 W libprocessgroup: failed to open /acct/uid_1000/pid_7025/cgroup.procs: No such file or directory
,06-22 07:44:57.242   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:44:57.242   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:44:57.242   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 172255158480; DSPS: 5735809; Offset : -2799537740
,06-22 07:44:58.526   295   354 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-22 07:44:59.634   842  1047 W PackageSettings: Skipping PackageSetting{3997c1ac com.example.hello/10317} due to missing metadata
,06-22 07:45:00.296  1374  1374 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,06-22 07:45:00.312  1907  1907 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,06-22 07:45:00.396   842  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-22 07:45:00.403   842   970 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7367 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
06-22 07:45:00.430  1374  1374 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,06-22 07:45:00.436  1945  1945 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
06-22 07:45:00.442  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
06-22 07:45:00.443  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,06-22 07:45:00.446  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,06-22 07:45:00.446  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
06-22 07:45:00.446  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
06-22 07:45:00.446  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
06-22 07:45:00.447  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
06-22 07:45:00.447  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
06-22 07:45:00.448  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
06-22 07:45:00.448  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
06-22 07:45:00.448  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
06-22 07:45:00.448  1374  1374 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
06-22 07:45:00.448  1374  1374 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,06-22 07:45:00.488  1945  1945 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,06-22 07:45:00.493  1945  1945 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
06-22 07:45:00.522  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,06-22 07:45:00.561  7367  7367 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-22 07:45:00.564   842   842 D administrator: Handling package changes for user 0
06-22 07:45:00.725  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:45:00.725  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-22 07:45:00.737  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
06-22 07:45:00.739  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:45:00.741  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
,06-22 07:45:00.743  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:45:00.744  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:45:00.987   842   842 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,06-22 07:45:00.990   842   842 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
06-22 07:45:00.991   842   842 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
06-22 07:45:00.996   842   942 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:45:01.006   842  2009 I ActivityManager: Process com.android.vending (pid 7130) has died
,06-22 07:45:01.015   842   842 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
06-22 07:45:01.036   842   842 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,06-22 07:45:01.037   842   842 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@15c8d332
06-22 07:45:01.079  7367  7402 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,06-22 07:45:01.083  7367  7402 I Babel_SMS: MmsConfig.loadMmsSettings
06-22 07:45:01.089  7367  7402 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-22 07:45:01.089  7367  7402 I Babel_SMS: MmsConfig.loadFromDatabase
06-22 07:45:01.112   842   942 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,06-22 07:45:01.118  7367  7402 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
06-22 07:45:01.118  7367  7402 I Babel_SMS: MmsConfig.loadFromResources
06-22 07:45:01.134  7367  7402 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
06-22 07:45:01.135  7367  7402 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,06-22 07:45:01.169  7367  7389 I art     : CheckpointMarkThreadRoots callback created = 0xb042d880
,06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
,06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
06-22 07:45:01.195  7367  7367 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
06-22 07:45:01.196  7367  7367 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
06-22 07:45:01.196  7367  7367 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
06-22 07:45:01.196  7367  7367 D SensorManager: found sensor: Motion Accel, handle=46
,06-22 07:45:01.214  7367  7389 I art     : CheckpointMarkThreadRoots callback created = 0xaae47db0
,06-22 07:45:01.219  1945  1945 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
06-22 07:45:01.238  7367  7367 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:45:01.245  7367  7367 I Babel_Crash: startup - clean
06-22 07:45:01.255  2351  2351 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,06-22 07:45:01.274  7367  7411 I Babel   : deleted: false for 0
,06-22 07:45:01.280   842   942 D LocationProviderProxy: applying state to connected service
06-22 07:45:01.370  7367  7367 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,06-22 07:45:01.374  7367  7367 W AudioCapabilities: Unsupported mime audio/adpcm
06-22 07:45:01.375  7367  7367 W AudioCapabilities: Unsupported mime audio/g726
06-22 07:45:01.375  7367  7367 W AudioCapabilities: Unsupported mime audio/x-ms-wma
06-22 07:45:01.376  7367  7367 W AudioCapabilities: Unsupported mime audio/wma-voice
06-22 07:45:01.378  7367  7367 W VideoCapabilities: Unsupported mime video/mjpg
06-22 07:45:01.389   842  1896 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7413 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,06-22 07:45:01.407  7367  7367 W VideoCapabilities: Unsupported mime video/theora
,06-22 07:45:01.448  7367  7367 W AudioCapabilities: Unsupported mime audio/evrc
06-22 07:45:01.450  7367  7367 W AudioCapabilities: Unsupported mime audio/qcelp
06-22 07:45:01.451  7367  7367 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-22 07:45:01.463  7367  7367 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
06-22 07:45:01.464  7367  7367 W AudioCapabilities: Unsupported mime audio/qcelp
,06-22 07:45:01.466  7367  7367 W AudioCapabilities: Unsupported mime audio/evrc
06-22 07:45:01.507  7367  7367 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,06-22 07:45:01.511  7413  7413 I AppUp4:AppBoxCP: onCreate
06-22 07:45:01.512  7413  7413 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
06-22 07:45:01.528  7413  7413 I AppUp4:DB:  setFingerPrint start
,06-22 07:45:01.528  7413  7413 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
06-22 07:45:01.538  7413  7413 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
06-22 07:45:01.538  7413  7413 I AppUp4:DB:  SDK version = 21
06-22 07:45:01.539  7413  7413 I AppUp4:DB:  beforefinger == newfinger no write in DB
,06-22 07:45:01.556  7367  7367 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-22 07:45:01.563  7367  7367 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-22 07:45:01.567  7367  7367 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-22 07:45:01.571  7367  7367 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:45:01.576   842  1896 I ActivityManager: Process com.lge.qremote (pid 6931) has died
06-22 07:45:01.576  7367  7367 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-22 07:45:01.578  7107  7107 D UEI.SmartControl: Service.onUnbind: IControl
06-22 07:45:01.579  7413  7413 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,06-22 07:45:01.579  7107  7107 D UEI.SmartControl: Service.onDestroy
06-22 07:45:01.581  7107  7107 D UEI.SmartControl: Shutdown IRRCPlayer... 
06-22 07:45:01.599  7107  7107 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
06-22 07:45:01.599  7107  7107 D irrcClient: ~IrrcClient ++ 
06-22 07:45:01.599  7107  7107 D irrcClient: ~IrrcClient -- 
06-22 07:45:01.599  7107  7107 W irrc_jni: IRRCPlayer_nativeFinalize -- 
06-22 07:45:01.599  7107  7107 D UEI.SmartControl: Blaster closed
06-22 07:45:01.599  7107  7107 D UEI.SmartControl: Blaster closed
06-22 07:45:01.599  7107  7107 D UEI.SmartControl: Shut down QS...
06-22 07:45:01.599  7107  7107 D UEI.SmartControl: Stopped file observer...
,06-22 07:45:01.607  7413  7413 I AppUp4:CustModeStarterReceiver: onReceive
06-22 07:45:01.607  7413  7413 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
06-22 07:45:01.610  7107  7107 I UEI.SmartControl: QS lib stop result = true
06-22 07:45:01.611  7107  7107 D UEI.SmartControl: QS shutdown complete
,06-22 07:45:01.614  7413  7413 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3cc4fa35
06-22 07:45:01.614  7413  7413 D AppUp4:CustFacade: isCustomizationCompleted : false
06-22 07:45:01.624  7413  7413 D AppUp4:CustFacade: isSimDevice : true
06-22 07:45:01.626  7413  7413 D AppUp4:CustModeStarterReceiver: begin check event
06-22 07:45:01.626  7413  7413 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,06-22 07:45:01.691   842  1932 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7434 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,06-22 07:45:01.715   310   310 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 23.925ms
,06-22 07:45:01.737   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 21.909ms
,06-22 07:45:01.760   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 334us total 22.038ms
,06-22 07:45:01.771   842  2009 I ActivityManager: Process com.uei.lg.quicksetsdk.lite (pid 7107) has died
,06-22 07:45:01.774  7367  7367 I vclib   : onServiceConnected
06-22 07:45:01.782  7367  7367 W Babel   : Attempted to change video mute state without an active call.
06-22 07:45:01.786  7367  7430 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,06-22 07:45:01.799  7434  7434 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:45:01.800  7434  7434 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-22 07:45:01.801  7434  7434 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
06-22 07:45:01.808  7367  7367 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-22 07:45:01.808  7367  7367 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-22 07:45:01.880  7367  7367 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-22 07:45:01.976   842  1951 I ActivityManager: Process com.google.android.partnersetup (pid 7197) has died
,06-22 07:45:01.986  7434  7434 I AppConfig: Total System Memory = 906309632
06-22 07:45:01.989  7434  7434 I GalleryUtils: Application Heap = 96 MB
06-22 07:45:01.992  7367  7367 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,06-22 07:45:01.998  7367  7367 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-22 07:45:01.999  7434  7434 I AppConfig: App Tier : NOT_DEF
06-22 07:45:02.006  7434  7434 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,06-22 07:45:02.018  7367  7367 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,06-22 07:45:02.088   842  1896 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7458 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,06-22 07:45:02.137   842  1284 D PowerManagerServiceEx: acquireWakeLockInternal: lock=51323580, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
06-22 07:45:02.139   842  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{236dd5d5 type 2 when 177138 android} when 177138
,06-22 07:45:02.143  7458  7458 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:45:02.144  7458  7458 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-22 07:45:02.144  7458  7458 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
06-22 07:45:02.146  7458  7458 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
06-22 07:45:02.148  7458  7458 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-22 07:45:02.285  7458  7458 I SystemConfig: BUILD Country: EU
06-22 07:45:02.285  7458  7458 I SystemConfig: BUILD Operator: OPEN
,06-22 07:45:02.420   842  1820 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7480 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,06-22 07:45:02.429  7458  7478 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
06-22 07:45:02.431  7458  7478 I SystemConfig: existFile = false
06-22 07:45:02.431  7458  7478 I SystemConfig: canReadFile = false
06-22 07:45:02.431  7458  7478 I SystemConfig: systemFeature RCS result false
06-22 07:45:02.431  7458  7478 D SystemConfig: refreshRcsSupport() :false
,06-22 07:45:02.496  7480  7480 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,06-22 07:45:02.524  7480  7480 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
06-22 07:45:02.524  7480  7480 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
06-22 07:45:02.524  7480  7480 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
06-22 07:45:02.524  7480  7480 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
06-22 07:45:02.524  7480  7480 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,06-22 07:45:02.583   842  2596 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7497 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:45:02.833  7497  7497 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
,06-22 07:45:02.987   842  1820 I ActivityManager: Process com.google.android.music:main (pid 6949) has died
,06-22 07:45:03.049  7497  7497 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(171): No need to run daily hygiene.
,06-22 07:45:03.073  7497  7497 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,06-22 07:45:03.075  7497  7497 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-22 07:45:03.080  7497  7497 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
06-22 07:45:03.099  7497  7497 I Finsky  : [1] com.google.android.finsky.utils.bk.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,06-22 07:45:03.131  2538  3677 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
,06-22 07:45:03.136  2538  3677 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@13c416ce on behalf of 7497
06-22 07:45:03.142  7497  7497 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1226): Installer kick - no action, not running yet
06-22 07:45:03.144  7497  7497 I Finsky  : [1] com.google.android.finsky.j.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
06-22 07:45:03.145  7497  7497 I Finsky  : [1] com.google.android.finsky.j.j.run(214): Finished loading 1 libraries.
,06-22 07:45:03.203   842  2194 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7538 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,06-22 07:45:03.223  7497  7497 I Finsky  : [1] com.google.android.finsky.c.l.a(270): result=false type=4
,06-22 07:45:03.247  7497  7497 I Finsky  : [1] com.google.android.finsky.services.bc.a(1050): Restore complete with 0 success and 0 failed.
06-22 07:45:03.268  7538  7538 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:45:03.531   295   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-22 07:45:03.603   842  2009 I ActivityManager: Killing 7222:com.google.android.configupdater/u0a3 (adj 15): empty #11
,06-22 07:45:03.606  2026  7579 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
06-22 07:45:03.649   842   860 W libprocessgroup: failed to open /acct/uid_10003/pid_7222/cgroup.procs: No such file or directory
,06-22 07:45:03.667  5591  7581 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,06-22 07:45:03.674  5591  7581 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoring.
06-22 07:45:03.698  2026  7579 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 90 ms] updated apps [took 90 ms] 
,06-22 07:45:03.709   842   842 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7582 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
06-22 07:45:03.722  5591  7581 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,06-22 07:45:03.776  5591  7610 E IcingInternalCorpora: Unknown Contacts update mode: MAYBE
06-22 07:45:03.776  5591  5631 I Icing   : updateResources: need to parse pru{com.google.android.gms}
06-22 07:45:03.837  7582  7582 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-22 07:45:03.866   842   859 I ActivityManager: Process com.google.android.gms.unstable (pid 6764) has died
,06-22 07:45:03.873  5591  7613 W IcingInternalCorpora: getNumBytesRead when not calculated.
06-22 07:45:03.913   842  1026 D BluetoothManagerService: Message: 20
06-22 07:45:03.913   842  1026 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a17dd4a:true
,06-22 07:45:03.926  2055  5977 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
,06-22 07:45:03.928  2055  2070 D BluetoothAdapterService(55213335): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2529daa5
06-22 07:45:03.980   842  1282 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7616 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,06-22 07:45:04.085  7616  7616 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,06-22 07:45:04.091  7616  7616 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3cc4fa35
06-22 07:45:04.091   842   842 D PowerManagerServiceEx: releaseWakeLockInternal: lock=51323580 [*alarm*], flags=0x0
06-22 07:45:04.181   842  2033 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7640 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:45:04.209  7582  7582 V LGMDMManager: Create singleton instance
,06-22 07:45:04.255  7640  7640 D UEI.SmartControl: Quickset Services start...
,06-22 07:45:04.260  7640  7640 I UEI.SmartControl: Manufacture = LGE
06-22 07:45:04.262  7640  7640 D UEI.SmartControl: File observer start...
06-22 07:45:04.263  7640  7640 E UEI.SmartControl: IR Port is disabled: false
06-22 07:45:04.264  7640  7640 D UEI.SmartControl: Starting file observer...
06-22 07:45:04.264  7640  7640 D UEI.SmartControl: Extracting JNI libs...
06-22 07:45:04.265  7640  7640 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
06-22 07:45:04.296  7582  7582 I AudioManager: getMode name:com.lge.qremote
,06-22 07:45:04.346   842  1383 I ActivityManager: Process com.android.gallery3d (pid 7434) has died
,06-22 07:45:04.425  7640  7640 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,06-22 07:45:04.426  7640  7640 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
06-22 07:45:04.427  7640  7640 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
06-22 07:45:04.465  7640  7640 I UEI.SmartControl: --- Selecting new region: 2
06-22 07:45:04.466  7640  7640 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,06-22 07:45:04.471  7640  7640 D UEI.SmartControl: Platform has CIR...
06-22 07:45:04.472  7640  7640 D UEI.SmartControl: NO CIR support, need to check package...
06-22 07:45:04.473  7640  7640 I UEI.SmartControl: Model: LG-D722 uses JNI
06-22 07:45:04.475  7640  7640 D UEI.SmartControl: QS Service created
06-22 07:45:04.477   842  1893 I ActivityManager: Process com.google.android.setupwizard (pid 7291) has died
06-22 07:45:04.499  7640  7640 E UEI.SmartControl: QS start get config
,06-22 07:45:04.539  7640  7640 D UEI.SmartControl: Loading JNI Libs...
,06-22 07:45:04.542  7640  7640 D UEI.SmartControl:  configuring local db...
06-22 07:45:04.737  7640  7640 D UEI.SmartControl:  ---- Has DB8: true
,06-22 07:45:04.745  7640  7640 D UEI.SmartControl: QS start statue = true Error code = 0
06-22 07:45:04.746  7640  7640 D UEI.SmartControl: QS version = v2.7.11.1_RC1
06-22 07:45:04.747  7640  7640 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
06-22 07:45:04.750  7640  7640 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,06-22 07:45:04.759  7640  7640 W irrc_jni: IRRCPlayer_nativeInit ++ 
06-22 07:45:04.759  7640  7640 D irrcClient: IrrcClient ++ 
06-22 07:45:04.759  7640  7640 D irrcClient: getIrrcService ++ 
06-22 07:45:04.760  7640  7640 D irrcClient: getIrrcService -- 
06-22 07:45:04.760  7640  7640 D irrcClient: IrrcClient -- 
06-22 07:45:04.760  7640  7640 W irrc_jni: IRRCPlayer_nativeInit -- 
06-22 07:45:04.765  7640  7640 D UEI.SmartControl: Services init done
06-22 07:45:04.767  7640  7659 I UEI.SmartControl: Device manager: loading config....
,06-22 07:45:04.770  7640  7640 D UEI.SmartControl: QS Service init finished
06-22 07:45:04.771  7640  7640 D UEI.SmartControl: QS Service version name: 0.1.73
06-22 07:45:04.772  7640  7640 D UEI.SmartControl: QS Service version code: 1073
06-22 07:45:04.772  7640  7659 D UEI.SmartControl: Config is loaded...
06-22 07:45:04.773  7640  7640 D UEI.SmartControl: Service requested: Control
06-22 07:45:04.775  7640  7640 D UEI.SmartControl: Internal service binding...
06-22 07:45:04.775  7640  7656 D UEI.SmartControl: -----IControl: 11
06-22 07:45:04.777  7640  7656 D UEI.SmartControl: Caller: com.lge.qremote
06-22 07:45:04.778  7640  7656 D UEI.SmartControl: ------------ IControl registerCallback...
06-22 07:45:04.778  7640  7656 I UEI.SmartControl: Registering callback...
,06-22 07:45:04.782  7640  7655 D UEI.SmartControl: -----IControl: 19
06-22 07:45:04.783  7640  7655 D UEI.SmartControl: Caller: com.lge.qremote
06-22 07:45:04.783  7640  7655 I UEI.SmartControl: Registering Services Ready callback...
06-22 07:45:04.784  7640  7655 I UEI.SmartControl: Notify client services are ready...
06-22 07:45:04.786  7640  7656 D UEI.SmartControl: -----IControl: 8
06-22 07:45:04.786  7640  7656 D UEI.SmartControl: Caller: com.lge.qremote
06-22 07:45:04.792  7582  7582 I AudioManager: getMode name:com.lge.qremote
,06-22 07:45:04.806  7640  7658 D UEI.SmartControl:  ----- QS SDK is ready!!!
,06-22 07:45:04.809  7640  7658 I UEI.SmartControl: Notify AllClients services are ready: 0
06-22 07:45:04.821  7582  7582 I AudioManager: getMode name:com.lge.qremote
,06-22 07:45:04.841  7582  7582 I AudioManager: getMode name:com.lge.qremote
,06-22 07:45:04.896   842  1944 I ActivityManager: Process com.android.contacts (pid 7458) has died
,06-22 07:45:04.966  5591  5631 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,06-22 07:45:05.133   842  2194 I art     : Explicit concurrent mark sweep GC freed 27093(1563KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.051ms total 146.462ms
,06-22 07:45:05.167  5591  5631 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,06-22 07:45:05.189  5591  5631 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,06-22 07:45:08.535   295   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-22 07:45:09.769  7640  7660 D UEI.SmartControl: Internal timer expired: 1
,06-22 07:45:09.818   842  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{24871969 type 2 when 184817 com.google.android.gms} when 184817
,06-22 07:45:09.954   842  1282 I ActivityManager: Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7671 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:45:10.234  7671  7698 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-22 07:45:10.236  7671  7698 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-22 07:45:10.315  7671  7698 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-22 07:45:10.410  7671  7698 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,06-22 07:45:10.410  7671  7698 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-22 07:45:10.530  7671  7706 D ChimeraCfgMgr: Reading stored module config
,06-22 07:45:10.549  7671  7695 I art     : CheckpointMarkThreadRoots callback created = 0xaaf32ff0
,06-22 07:45:10.587  7671  7695 I art     : CheckpointMarkThreadRoots callback created = 0xaaf32fc0
,06-22 07:45:10.641  7671  7706 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,06-22 07:45:10.642  7671  7706 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk': Failed to open oat filename for reading: No such file or directory
06-22 07:45:10.644  7671  7706 D ChimeraFileApk: Classloading successful. Optimized code found.
06-22 07:45:10.659  7671  7671 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,06-22 07:45:10.666  7671  7706 D DynamitePackage: Instantiated singleton DynamitePackage.
06-22 07:45:10.666  7671  7706 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
06-22 07:45:10.671  7671  7671 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:45:10.671  7671  7671 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:45:10.711   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:45:10.711   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
06-22 07:45:10.711   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:45:10.711  7671  7671 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,06-22 07:45:10.933  7671  7671 I NotificationManager: com.google.android.youtube: cancel(2) by com.google.android.youtube
,06-22 07:45:10.959   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:45:10.959   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
06-22 07:45:10.959   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:45:10.961  7671  7671 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
06-22 07:45:10.963   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:45:10.963   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
06-22 07:45:10.963   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:45:10.964  7671  7671 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
06-22 07:45:10.965   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:45:10.965   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
06-22 07:45:10.965   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:45:10.966  7671  7671 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
06-22 07:45:10.983  7671  7671 W InstanceID/Rpc: Found 10006
,06-22 07:45:11.033   241   298 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-22 07:45:11.033   241   298 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
06-22 07:45:11.033   241   298 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:45:11.037  7671  7671 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,06-22 07:45:11.146   842  1896 I ActivityManager: Killing 7413:com.lge.appbox.client/u0a11 (adj 15): empty #11
,06-22 07:45:11.156  7671  7741 I NotificationManager: com.google.android.youtube: cancel(10436) by com.google.android.youtube
06-22 07:45:11.257   842  2194 W libprocessgroup: failed to open /acct/uid_10011/pid_7413/cgroup.procs: No such file or directory
,06-22 07:45:11.284  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:11.284  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:45:11.285  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:11.285  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:45:11.285   279  1053 E BandwidthController: [LG DATA] No such appUid: 10100
06-22 07:45:11.285   279  1053 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-22 07:45:11.286   279  7780 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:45:11.286   279  7780 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:45:11.289   279  7780 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:45:11.289   279  7780 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:45:11.289   279  7780 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:45:11.290  7671  7776 I System.out: propertyValue:false
06-22 07:45:11.290  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:11.290  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:45:12.250  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-22 07:45:12.251  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:45:12.255  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:45:12.257  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:45:12.258  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:45:12.259   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 07:45:12.280  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
06-22 07:45:12.280  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:45:12.281  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,06-22 07:45:12.286  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:45:12.287  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:45:12.287  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:45:12.287  1852  2044 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
06-22 07:45:12.290  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
06-22 07:45:12.300  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-22 07:45:12.303   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:45:12.304   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:45:12.304   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:45:12.328  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-22 07:45:13.540   295   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-22 07:45:17.242   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:45:17.243   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:45:17.243   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 192256040347; DSPS: 6391198; Offset : -2799540491
,06-22 07:45:17.400  1330  1330 I art     : Explicit concurrent mark sweep GC freed 5009(358KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 7MB/12MB, paused 2.654ms total 97.767ms
,06-22 07:45:18.544   295   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-22 07:45:20.552  7671  7756 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:20.552  7671  7756 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:45:20.555  7671  7756 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:20.555  7671  7756 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:45:20.556   279  1053 E BandwidthController: [LG DATA] No such appUid: 10100
06-22 07:45:20.556   279  1053 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-22 07:45:20.557   279  7804 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:45:20.557   279  7804 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:45:20.557   279  7804 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:45:20.558   279  7804 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:45:20.604   279  7804 D libc-netbsd: res_queryN name = xxxxx succeed
,06-22 07:45:20.610  7671  7756 I System.out: propertyValue:false
06-22 07:45:20.610  7671  7756 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:20.610  7671  7756 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:45:20.664  7671  7756 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:20.664  7671  7756 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:45:22.554  1374  1374 I art     : Explicit concurrent mark sweep GC freed 42349(2MB) AllocSpace objects, 69(23MB) LOS objects, 40% free, 15MB/25MB, paused 3.015ms total 246.640ms
,06-22 07:45:23.549   295   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-22 07:45:27.393  1598  1598 I art     : Explicit concurrent mark sweep GC freed 2086(154KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 2.636ms total 89.843ms
,06-22 07:45:28.554   295   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-22 07:45:32.542  1758  1758 I art     : Explicit concurrent mark sweep GC freed 26755(1544KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 2.912ms total 228.261ms
,06-22 07:45:33.558   295   354 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-22 07:45:33.717   842  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{d9ff0b2 type 2 when 208715 android} when 208715
,06-22 07:45:33.976  5591  7806 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,06-22 07:45:33.998   842   942 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 179199, reason: UserStart, SyncResult: databaseError: true stats []
,06-22 07:45:34.006   842   942 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 272034, reason: UserStart
06-22 07:45:34.006   842   942 I NotificationManager: android: cancelAsUser(716319171) by android
06-22 07:45:37.243   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:45:37.243   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:45:37.243   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 212256851538; DSPS: 7046584; Offset : -2799522810
,06-22 07:45:38.563   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:45:38.839  1783  1783 I art     : Explicit concurrent mark sweep GC freed 1666(103KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 2.717ms total 83.044ms
,06-22 07:45:43.567   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:45:43.867  1821  1821 I art     : Explicit concurrent mark sweep GC freed 43075(2MB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/14MB, paused 2.972ms total 108.849ms
,06-22 07:45:45.581  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:45:45.588  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:45:45.665  2351  2611 E Auth    : [GoogleAccountDataServiceImpl] getToken() -> BAD_AUTHENTICATION. Account: <ELLIDED:-818113082>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
06-22 07:45:45.665  2351  2611 E Auth    : elc: Long live credential not available.
06-22 07:45:45.665  2351  2611 E Auth    : 	at eld.a(SourceFile:3099)
06-22 07:45:45.665  2351  2611 E Auth    : 	at ejq.a(SourceFile:397)
06-22 07:45:45.665  2351  2611 E Auth    : 	at ejp.a(SourceFile:31369)
06-22 07:45:45.665  2351  2611 E Auth    : 	at ejp.a(SourceFile:313)
06-22 07:45:45.665  2351  2611 E Auth    : 	at fla.a(SourceFile:1201)
06-22 07:45:45.665  2351  2611 E Auth    : 	at fkz.a(SourceFile:530)
06-22 07:45:45.665  2351  2611 E Auth    : 	at fkz.a(SourceFile:196)
06-22 07:45:45.665  2351  2611 E Auth    : 	at egp.a(SourceFile:284)
06-22 07:45:45.665  2351  2611 E Auth    : 	at egp.a(SourceFile:204)
06-22 07:45:45.665  2351  2611 E Auth    : 	at egu.a(SourceFile:1510)
06-22 07:45:45.665  2351  2611 E Auth    : 	at egt.a(SourceFile:920)
06-22 07:45:45.665  2351  2611 E Auth    : 	at egt.e(SourceFile:534)
06-22 07:45:45.665  2351  2611 E Auth    : 	at egt.d(SourceFile:454)
06-22 07:45:45.665  2351  2611 E Auth    : 	at egr.b(SourceFile:568)
06-22 07:45:45.665  2351  2611 E Auth    : 	at jtq.a(SourceFile:82)
06-22 07:45:45.665  2351  2611 E Auth    : 	at jsg.a(SourceFile:57)
06-22 07:45:45.665  2351  2611 E Auth    : 	at bnq.a(SourceFile:6096)
06-22 07:45:45.665  2351  2611 E Auth    : 	at bjz.run(SourceFile:52)
06-22 07:45:45.665  2351  2611 E Auth    : 	at bjx.a(SourceFile:258)
06-22 07:45:45.665  2351  2611 E Auth    : 	at bjx.handleMessage(SourceFile:251)
06-22 07:45:45.665  2351  2611 E Auth    : 	at jxi.run(SourceFile:141)
06-22 07:45:45.665  2351  2611 E Auth    : 	at jxq.run(SourceFile:438)
06-22 07:45:45.665  2351  2611 E Auth    : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-22 07:45:45.665  2351  2611 E Auth    : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-22 07:45:45.665  2351  2611 E Auth    : 	at kca.run(SourceFile:17)
06-22 07:45:45.665  2351  2611 E Auth    : 	at java.lang.Thread.run(Thread.java:818)
,06-22 07:45:45.830  2351  2611 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,06-22 07:45:45.932  2351  2611 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:45.932  2351  2611 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:45:45.933  2351  2611 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:45.933  2351  2611 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-22 07:45:45.935   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:45:45.935   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:45:45.935   279  7809 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:45:45.935   279  7809 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:45:45.940   279  7809 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:45:45.940   279  7809 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:45:45.941   279  7809 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:45:45.941  2351  2611 I System.out: propertyValue:false
06-22 07:45:46.003  2351  2611 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:46.003  2351  2611 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:45:46.187   842  1896 I NotificationManager: android: cancelAsUser(2) by android
,06-22 07:45:46.204  2351  2611 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-22 07:45:46.254  2351  2611 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=UNKNOWN).  Giving up.
,06-22 07:45:46.267  2351  7087 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:46.267  2351  7087 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:45:46.268  2351  7087 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:45:46.268  2351  7087 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:45:46.268   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:45:46.268   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:45:46.269   279  7816 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:45:46.269   279  7816 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:45:46.269   279  7816 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:45:46.269   279  7816 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:45:46.269   279  7816 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:45:46.270  2351  7087 I System.out: propertyValue:false
06-22 07:45:46.575  2351  2611 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,06-22 07:45:48.572   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:45:48.909  1852  1852 I art     : Explicit concurrent mark sweep GC freed 13235(912KB) AllocSpace objects, 2(28KB) LOS objects, 40% free, 8MB/13MB, paused 2.311ms total 145.995ms
,06-22 07:45:50.820   842  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1ea84aae type 2 when 216018 android} when 216018
,06-22 07:45:50.923   842  2194 D LocationManagerService: getAllProviders()=[passive, gps, network]
,06-22 07:45:51.127  2351  2376 I art     : Explicit concurrent mark sweep GC freed 109660(5MB) AllocSpace objects, 27(436KB) LOS objects, 40% free, 17MB/28MB, paused 3.074ms total 183.821ms
,06-22 07:45:51.257  2351  2549 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:51.257  2351  2549 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:45:51.257  2351  2549 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:51.257  2351  2549 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-22 07:45:51.261   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:45:51.261   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:45:51.261   279  7822 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:45:51.261   279  7822 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:45:51.262   279  7822 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:45:51.265   279  7822 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:45:51.265   279  7822 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:45:51.266  2351  2549 I System.out: propertyValue:false
06-22 07:45:51.342  2351  2549 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:45:51.342  2351  2549 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:45:51.509   842  1951 I NotificationManager: android: cancelAsUser(2) by android
,06-22 07:45:51.529  2351  2549 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-22 07:45:53.577   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:45:55.962  1881  1881 I art     : Explicit concurrent mark sweep GC freed 2152(126KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 2.635ms total 75.527ms
,06-22 07:45:57.244   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:45:57.244   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:45:57.244   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 232257607416; DSPS: 7701969; Offset : -2799530652
,06-22 07:45:58.581   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:46:00.052  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:46:00.052  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:46:00.052  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:46:00.057  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:46:00.057  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:46:00.058  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:46:00.059  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:46:00.987  1907  1907 I art     : Explicit concurrent mark sweep GC freed 8051(462KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/11MB, paused 2.559ms total 93.917ms
,06-22 07:46:03.586   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:46:03.734   842  1284 D PowerManagerServiceEx: acquireWakeLockInternal: lock=51323580, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,06-22 07:46:03.738   842  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{38334261 type 2 when 238735 android} when 238735
06-22 07:46:03.757   842   842 D PowerManagerServiceEx: releaseWakeLockInternal: lock=51323580 [*alarm*], flags=0x0
,06-22 07:46:08.590   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:46:08.848  1925  1925 I art     : Explicit concurrent mark sweep GC freed 119(5KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 4.894ms total 71.261ms
,06-22 07:46:12.406   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:46:12.409  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:46:12.410  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:46:12.416  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:46:12.416  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:46:12.416  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:46:12.451  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
06-22 07:46:12.452  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:46:12.452  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,06-22 07:46:12.456  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:46:12.456  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:46:12.458  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:46:12.458  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:46:12.458  1852  2044 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
06-22 07:46:12.460  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:46:12.461   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:46:12.461   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:46:12.461   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:46:12.463  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:46:13.595   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:46:17.245   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:46:17.245   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:46:17.245   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 252258364751; DSPS: 8357354; Offset : -2799535241
,06-22 07:46:17.549  1629  1629 I art     : Explicit concurrent mark sweep GC freed 624(30KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 587us total 79.772ms
,06-22 07:46:18.600   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:46:22.556  2614  2614 I art     : Explicit concurrent mark sweep GC freed 2661(181KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/11MB, paused 1.446ms total 79.743ms
,06-22 07:46:23.604   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:46:27.563  2272  2272 I art     : Explicit concurrent mark sweep GC freed 1981(124KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 2.695ms total 89.678ms
,06-22 07:46:28.609   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:46:32.591  2055  2055 I art     : Explicit concurrent mark sweep GC freed 20356(1260KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 8MB/14MB, paused 2.491ms total 118.278ms
,06-22 07:46:33.613   295   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-22 07:46:37.246   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:46:37.246   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:46:37.246   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 272259126671; DSPS: 9012739; Offset : -2799536235
,06-22 07:46:37.510  5553  5553 I art     : Explicit concurrent mark sweep GC freed 589(26KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 519us total 38.546ms
,06-22 07:46:38.618   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:46:42.556  2538  2538 I art     : Explicit concurrent mark sweep GC freed 4768(332KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 653us total 64.388ms
,06-22 07:46:43.623   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:46:47.605  2351  2351 I art     : Explicit concurrent mark sweep GC freed 40056(2MB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 15MB/25MB, paused 2.818ms total 130.668ms
,06-22 07:46:48.627   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:46:52.625  5591  5591 I art     : Explicit concurrent mark sweep GC freed 24272(1298KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/22MB, paused 1.685ms total 147.739ms
,06-22 07:46:52.930  2351  4369 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-22 07:46:53.632   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:46:57.246   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:46:57.246   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:46:57.247   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 292259890205; DSPS: 9668124; Offset : -2799535718
,06-22 07:46:57.562  1945  1945 I art     : Explicit concurrent mark sweep GC freed 6145(330KB) AllocSpace objects, 4(665KB) LOS objects, 25% free, 15MB/20MB, paused 771us total 76.218ms
,06-22 07:46:58.636   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:47:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:47:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:47:00.043  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:47:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:47:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:47:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
,06-22 07:47:02.539  1984  1984 I art     : Explicit concurrent mark sweep GC freed 198(19KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/10MB, paused 567us total 47.473ms
,06-22 07:47:03.641   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:07.613  2026  2026 I art     : Explicit concurrent mark sweep GC freed 9479(572KB) AllocSpace objects, 2(46KB) LOS objects, 24% free, 12MB/16MB, paused 4.926ms total 131.171ms
,06-22 07:47:08.645   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:12.536  2776  2776 I art     : Explicit concurrent mark sweep GC freed 688(43KB) AllocSpace objects, 2(221KB) LOS objects, 25% free, 7MB/9MB, paused 625us total 56.293ms
,06-22 07:47:12.567  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:47:12.567   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:47:12.577  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:47:12.577  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:47:12.577  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:47:12.577  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:47:12.611  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
06-22 07:47:12.611  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:47:12.611  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,06-22 07:47:12.615  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:47:12.615  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:47:12.616  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:47:12.616  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:47:12.616  1852  2044 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
06-22 07:47:12.618  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:47:12.619  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:47:12.621   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:47:12.621   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:47:12.621   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:47:13.650   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:17.247   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:47:17.247   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:47:17.247   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 312260677438; DSPS: 10323510; Offset : -2799542333
,06-22 07:47:17.695  2801  2801 I art     : Explicit concurrent mark sweep GC freed 8352(480KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 534us total 63.218ms
,06-22 07:47:18.655   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:22.683  2927  2927 I art     : Explicit concurrent mark sweep GC freed 273(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 508us total 54.353ms
,06-22 07:47:23.659   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:27.751  3093  3093 I art     : Explicit concurrent mark sweep GC freed 5578(316KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 556us total 116.475ms
,06-22 07:47:28.664   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:32.705  3380  3380 I art     : Explicit concurrent mark sweep GC freed 23518(1166KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 7MB/9MB, paused 593us total 75.164ms
,06-22 07:47:33.668   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:37.248   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:47:37.248   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:47:37.248   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 332261420555; DSPS: 10978894; Offset : -2799531195
,06-22 07:47:37.681  3873  3873 I art     : Explicit concurrent mark sweep GC freed 262(25KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 490us total 51.318ms
,06-22 07:47:38.673   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:43.678   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:46.312   842  3142 I LocationManagerService: remove df9ea89
,06-22 07:47:46.318   842  3142 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
06-22 07:47:46.318   842  3142 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-22 07:47:46.318   842  3142 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-22 07:47:46.319   842  3142 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
06-22 07:47:46.319   842  3142 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,06-22 07:47:48.682   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:51.547  5591  7053 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-22 07:47:53.687   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:47:57.249   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:47:57.249   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:47:57.249   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 352262172005; DSPS: 11634279; Offset : -2799542710
,06-22 07:47:58.691   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:00.038  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:48:00.038  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:48:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:48:00.043  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:48:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:48:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:48:00.044  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:48:03.696   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:08.175  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-22 07:48:08.178  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:48:08.178  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:48:08.179  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:48:08.180  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:48:08.202   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:48:08.237   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:48:08.245  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:48:08.246  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:48:08.246  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:48:08.246  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:48:08.246  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:48:08.321  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
06-22 07:48:08.321  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:48:08.321  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,06-22 07:48:08.325  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:48:08.326  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:48:08.326  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:48:08.326  1852  2044 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
06-22 07:48:08.327  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:48:08.329  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:48:08.330  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:48:08.332   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:48:08.332   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:48:08.333   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:48:08.701   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:10.213   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:48:10.216  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:48:10.223  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:48:10.223  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:48:10.224  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:48:10.224  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:48:10.259  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
06-22 07:48:10.259  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:48:10.259  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,06-22 07:48:10.263  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:48:10.264  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:48:10.264  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:48:10.264  1852  2044 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
06-22 07:48:10.264  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:48:10.268  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:48:10.269  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:48:10.270   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:48:10.270   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:48:10.271   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:48:12.728  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-22 07:48:12.735  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:48:12.736  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:48:12.736  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:48:12.736  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:48:12.738   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 07:48:13.705   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:17.249   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:48:17.249   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:48:17.249   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 372262852623; DSPS: 12289661; Offset : -2799534000
,06-22 07:48:18.710   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:23.715   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:28.719   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:33.724   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:37.250   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:48:37.250   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:48:37.250   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 392263637355; DSPS: 12945047; Offset : -2799542335
,06-22 07:48:38.728   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:43.733   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:48.737   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:53.742   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:48:57.251   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:48:57.251   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:48:57.251   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 412264322399; DSPS: 13600429; Offset : -2799528599
,06-22 07:48:58.746   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:49:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:49:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:49:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:49:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:49:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:49:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:49:03.751   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:08.756   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:12.886   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:49:12.889  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:49:12.890  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:49:12.896  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:49:12.896  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:49:12.896  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:49:12.931  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
06-22 07:49:12.932  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:49:12.932  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,06-22 07:49:12.936  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:49:12.936  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:49:12.937  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:49:12.937  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:49:12.937  1852  2044 D LEDHandler: Battery Temp: 289, mChargingStatus=5, mChargingStop=false
06-22 07:49:12.939  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:49:12.941  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:49:12.942   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:49:12.942   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:49:12.943   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:49:13.760   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:17.251   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:49:17.251   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:49:17.252   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 432265004840; DSPS: 14255811; Offset : -2799517362
,06-22 07:49:18.765   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:22.643   842  1284 D PowerManagerServiceEx: acquireWakeLockInternal: lock=51323580, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,06-22 07:49:22.649   842  1284 V AlarmManager: RTC_WAKEUP set : Alarm{4130186 type 0 when 1466574562641 com.google.android.gms} when 1466574562641
06-22 07:49:22.681   842   842 D PowerManagerServiceEx: releaseWakeLockInternal: lock=51323580 [*alarm*], flags=0x0
,06-22 07:49:22.741  5591  7864 I EventLogChimeraService: Aggregate from 1466574277439 (log), 1466572762561 (data)
,06-22 07:49:22.927  5591  7881 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,06-22 07:49:23.770   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:28.774   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:33.779   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:37.252   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:49:37.252   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:49:37.252   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 452265917019; DSPS: 14911201; Offset : -2799521284
,06-22 07:49:38.783   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:42.515  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:49:42.527  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:49:42.529  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:49:42.593  2351  2374 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:49:42.593  2351  2374 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:49:42.596  2351  2374 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:49:42.596  2351  2374 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:49:42.597   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:49:42.597   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:49:42.600   279  7905 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:49:42.600   279  7905 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:49:42.600   279  7905 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:49:42.601   279  7905 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:49:42.655   279  7905 D libc-netbsd: res_queryN name = xxxxx succeed
,06-22 07:49:42.659  2351  2374 I System.out: propertyValue:false
06-22 07:49:42.730  2351  2374 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:49:42.732  2351  2374 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:49:43.788   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:45.247   842  1383 I NotificationManager: android: cancelAsUser(2) by android
,06-22 07:49:45.269  2351  2374 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-22 07:49:45.278   842  2194 I NotificationManager: android: cancelAsUser(2) by android
06-22 07:49:45.311  5591  6901 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:49:45.314  5591  6901 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:49:45.315  5591  6901 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:49:45.315  5591  6901 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:49:45.315   279  1053 E BandwidthController: [LG DATA] No such appUid: 10006
06-22 07:49:45.315   279  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-22 07:49:45.316   279  7907 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:49:45.317   279  7907 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:49:45.317   279  7907 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:49:45.317   279  7907 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:49:45.370   279  7907 D libc-netbsd: res_queryN name = xxxxx succeed
,06-22 07:49:45.374  5591  6901 I System.out: propertyValue:false
06-22 07:49:45.441  5591  6901 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:49:45.441  5591  6901 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:49:48.793   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:53.797   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:49:57.253   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:49:57.253   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:49:57.253   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 472266601231; DSPS: 15566584; Offset : -2799538716
,06-22 07:49:58.802   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:50:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:50:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:50:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:50:00.045  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:50:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:50:00.047  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:50:00.048  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:50:03.060  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:50:03.071  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:50:03.072  2351  2351 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:50:03.108   842  1820 I NotificationManager: android: cancelAsUser(2) by android
,06-22 07:50:03.136  7497  7531 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:50:03.140  7497  7531 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:03.141  7497  7531 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:03.141  7497  7531 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:50:03.142   279  1053 E BandwidthController: [LG DATA] No such appUid: 10036
06-22 07:50:03.142   279  1053 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
06-22 07:50:03.143   279  7911 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:50:03.144   279  7911 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:50:03.144   279  7911 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:50:03.144   279  7911 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:50:03.145   279  7911 D libc-netbsd: res_queryN name = xxxxx succeed
06-22 07:50:03.146  7497  7531 I System.out: propertyValue:false
06-22 07:50:03.806   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:50:08.811   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:50:11.285  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:11.285  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:50:11.288  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:11.288  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:50:11.289   279  1053 E BandwidthController: [LG DATA] No such appUid: 10100
06-22 07:50:11.289   279  1053 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-22 07:50:11.290   279  7921 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-22 07:50:11.290   279  7921 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-22 07:50:11.290   279  7921 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-22 07:50:11.291   279  7921 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-22 07:50:11.335   279  7921 D libc-netbsd: res_queryN name = xxxxx succeed
,06-22 07:50:11.339  7671  7776 I System.out: propertyValue:false
06-22 07:50:11.340  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:11.340  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:11.613  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:50:11.616  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:11.617  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:11.617  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:11.770  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:11.770  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:11.771  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:11.771  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:50:11.923  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:50:11.925  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:11.926  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:11.926  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:12.073  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:50:12.075  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:12.076  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:12.076  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:12.225  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:12.225  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:50:12.228  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:12.229  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:12.378  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:50:12.380  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:12.381  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:12.381  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:12.527  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:12.527  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:50:12.530  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:12.531  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:12.677  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:12.677  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-22 07:50:12.680  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:12.681  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:12.827  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-22 07:50:12.830  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:12.830  7671  7776 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-22 07:50:12.830  7671  7776 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-22 07:50:13.059   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:50:13.065  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:50:13.065  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:50:13.065  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:50:13.065  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:50:13.071  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:50:13.104  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
06-22 07:50:13.104  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:50:13.104  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,06-22 07:50:13.109  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:50:13.109  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:50:13.109  1852  2044 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
06-22 07:50:13.110  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:50:13.110  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:50:13.112  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:50:13.115  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:50:13.116   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:50:13.116   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:50:13.120   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:50:13.815   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:50:17.254   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:50:17.254   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:50:17.254   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 492267445233; DSPS: 16221971; Offset : -2799518115
,06-22 07:50:18.820   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:50:23.825   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:50:28.829   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:50:33.834   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:50:37.255   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:50:37.255   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:50:37.255   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 512268198975; DSPS: 16877356; Offset : -2799527833
,06-22 07:50:38.838   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:50:43.843   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:50:48.847   295   354 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-22 07:50:53.852   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:50:57.255   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:50:57.255   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:50:57.256   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 532269015739; DSPS: 17532743; Offset : -2799534993
,06-22 07:50:58.856   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:00.041  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:51:00.041  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:51:00.041  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:51:00.046  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:51:00.046  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:51:00.047  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:51:00.048  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:51:03.861   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:08.866   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:13.206  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:51:13.206  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:51:13.207  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:51:13.207  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-22 07:51:13.209   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 07:51:13.210  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:51:13.251  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
06-22 07:51:13.252  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:51:13.252  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,06-22 07:51:13.255  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:51:13.256  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:51:13.256  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:51:13.256  1852  2044 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
06-22 07:51:13.257  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:51:13.259  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:51:13.260  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:51:13.262   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:51:13.262   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:51:13.262   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:51:13.870   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:17.256   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:51:17.256   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:51:17.256   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 552269701095; DSPS: 18188125; Offset : -2799520918
,06-22 07:51:18.875   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:23.879   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:28.884   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:33.888   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:37.257   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:51:37.257   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:51:37.257   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 572270616401; DSPS: 18843515; Offset : -2799521141
,06-22 07:51:38.893   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:43.898   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:48.902   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:53.907   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:51:57.258   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:51:57.258   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:51:57.258   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 592271391029; DSPS: 19498901; Offset : -2799540021
,06-22 07:51:58.911   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:52:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:52:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:52:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:52:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:52:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:52:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:52:03.916   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:08.920   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:13.366  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:52:13.366  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:52:13.366  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:52:13.366  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-22 07:52:13.369   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 07:52:13.370  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:52:13.411  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
06-22 07:52:13.411  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:52:13.412  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,06-22 07:52:13.415  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:52:13.416  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:52:13.416  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:52:13.416  1852  2044 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
06-22 07:52:13.417  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:52:13.419  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:52:13.420  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:52:13.422   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:52:13.422   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:52:13.422   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:52:13.925   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:17.259   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:52:17.259   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:52:17.259   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 612272151333; DSPS: 20154286; Offset : -2799542708
,06-22 07:52:18.930   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:23.934   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:28.939   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:33.943   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:37.259   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:52:37.259   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:52:37.259   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 632272834712; DSPS: 20809668; Offset : -2799530560
,06-22 07:52:38.948   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:43.952   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:48.957   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:53.962   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:52:57.260   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:52:57.260   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:52:57.260   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 652273595641; DSPS: 21465053; Offset : -2799533039
,06-22 07:52:58.966   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:53:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:53:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:53:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:53:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:53:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:53:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:53:03.971   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:08.975   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:13.526   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:53:13.528  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:53:13.535  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:53:13.535  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:53:13.535  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:53:13.536  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:53:13.568  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
06-22 07:53:13.568  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:53:13.568  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,06-22 07:53:13.572  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:53:13.573  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:53:13.573  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:53:13.573  1852  2044 D LEDHandler: Battery Temp: 286, mChargingStatus=5, mChargingStop=false
06-22 07:53:13.574  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:53:13.576  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:53:13.577  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:53:13.579   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:53:13.579   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:53:13.579   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:53:13.980   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:17.261   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:53:17.261   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:53:17.261   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 672274339279; DSPS: 22120437; Offset : -2799521328
,06-22 07:53:18.984   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:23.989   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:28.994   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:33.998   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:37.262   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:53:37.262   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:53:37.262   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 692275099845; DSPS: 22775822; Offset : -2799524093
,06-22 07:53:39.003   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:44.007   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:49.012   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:54.017   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:53:57.262   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:53:57.262   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:53:57.262   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 712275868483; DSPS: 23431207; Offset : -2799518211
,06-22 07:53:59.021   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:54:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:54:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:54:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:54:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:54:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:54:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:54:04.026   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:09.030   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:13.686  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:54:13.686  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:54:13.686  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:54:13.686  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-22 07:54:13.689   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 07:54:13.690  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:54:13.731  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
06-22 07:54:13.731  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:54:13.731  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,06-22 07:54:13.735  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:54:13.735  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:54:13.736  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:54:13.736  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:54:13.736  1852  2044 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
06-22 07:54:13.738  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:54:13.740  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:54:13.742   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:54:13.742   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:54:13.742   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:54:14.035   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:17.263   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:54:17.263   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:54:17.263   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 732276595246; DSPS: 24086591; Offset : -2799523610
,06-22 07:54:19.039   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:24.044   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:29.049   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:34.053   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:37.264   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:54:37.264   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:54:37.264   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 752277332894; DSPS: 24741975; Offset : -2799518644
,06-22 07:54:39.058   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:44.062   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:49.067   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:54.071   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:54:57.264   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:54:57.265   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:54:57.265   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 772278060282; DSPS: 25397359; Offset : -2799523653
,06-22 07:54:59.076   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:00.077  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:55:00.077  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:55:00.077  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:55:00.081  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:55:00.081  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:55:00.082  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:55:00.083  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:55:04.083   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:09.087   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:13.846   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:55:13.849  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:55:13.849  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:55:13.849  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:55:13.849  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:55:13.856  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:55:13.887  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
06-22 07:55:13.887  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:55:13.887  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,06-22 07:55:13.894  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:55:13.894  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:55:13.895  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:55:13.896  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:55:13.896  1852  2044 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
06-22 07:55:13.898  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:55:13.899  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-22 07:55:13.904   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:55:13.904   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:55:13.904   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:55:14.092   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:17.265   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:55:17.265   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:55:17.265   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 792278813607; DSPS: 26052744; Offset : -2799533344
,06-22 07:55:19.096   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:24.101   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:29.105   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:34.110   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:37.266   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:55:37.266   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:55:37.266   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 812279581569; DSPS: 26708129; Offset : -2799528322
,06-22 07:55:39.115   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:44.119   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:49.124   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:54.128   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:55:57.267   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:55:57.267   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:55:57.267   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 832280362656; DSPS: 27363515; Offset : -2799540641
,06-22 07:55:59.133   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:00.038  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:56:00.038  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:56:00.038  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:56:00.043  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:56:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:56:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:56:00.044  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:56:04.137   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:09.142   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:14.006   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:56:14.011  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:56:14.011  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:56:14.011  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:56:14.011  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:56:14.012  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:56:14.147   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:17.268   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:56:17.268   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:56:17.268   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 852281047388; DSPS: 28018897; Offset : -2799527268
,06-22 07:56:19.151   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:24.156   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:29.160   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:34.165   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:37.268   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:56:37.268   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:56:37.268   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 872281730661; DSPS: 28674280; Offset : -2799547385
,06-22 07:56:39.169   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:44.174   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:49.178   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:54.183   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:56:57.269   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:56:57.269   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:56:57.269   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 892282496956; DSPS: 29329665; Offset : -2799542805
,06-22 07:56:59.188   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:57:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:57:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:57:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:57:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:57:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:57:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:57:04.192   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:09.197   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:14.166   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:57:14.174  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:57:14.176  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:57:14.176  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:57:14.176  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:57:14.176  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:57:14.203   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:17.270   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:57:17.270   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:57:17.270   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 912283246323; DSPS: 29985049; Offset : -2799525834
,06-22 07:57:19.207   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:24.212   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:29.216   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:34.221   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:37.270   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:57:37.270   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:57:37.271   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 932284021211; DSPS: 30640435; Offset : -2799545861
,06-22 07:57:39.225   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:44.230   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:49.235   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:54.239   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:57:57.271   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:57:57.271   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:57:57.271   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 952284781047; DSPS: 31295819; Offset : -2799516884
,06-22 07:57:59.244   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:00.040  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:58:00.040  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:58:00.040  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:58:00.044  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:58:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:58:00.045  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:58:00.046  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:58:04.248   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:09.253   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:14.257   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:14.326   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:58:14.334  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:58:14.335  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:58:14.335  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:58:14.336  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:58:14.336  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:58:17.272   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:58:17.272   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:58:17.272   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 972285464321; DSPS: 31951202; Offset : -2799535228
,06-22 07:58:19.262   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:24.266   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:29.271   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:34.276   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:37.273   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:58:37.273   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:58:37.273   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 992286144053; DSPS: 32606584; Offset : -2799526910
,06-22 07:58:39.280   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:44.285   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:47.149  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:58:47.149  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:58:47.149  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:58:47.149  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-22 07:58:47.152  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:58:47.168   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:58:47.203  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
06-22 07:58:47.203  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:58:47.203  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,06-22 07:58:47.207  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:58:47.207  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 07:58:47.208  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:58:47.208  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:58:47.208  1852  2044 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
06-22 07:58:47.210  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:58:47.212  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:58:47.214   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:58:47.214   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:58:47.214   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:58:47.250  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,06-22 07:58:47.261  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:58:47.262  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
06-22 07:58:47.265  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 07:58:47.265  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,06-22 07:58:47.269  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 07:58:47.269  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 07:58:47.270  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 07:58:47.270  1852  2044 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
06-22 07:58:47.273   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:58:47.274   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:58:47.274   842  1312 D WifiController: battery changed pluggedType: 2
06-22 07:58:47.274  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:58:49.289   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:54.294   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:58:57.273   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:58:57.273   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:58:57.273   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1012286833941; DSPS: 33261967; Offset : -2799539134
,06-22 07:58:59.298   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:00.038  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 07:59:00.038  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 07:59:00.038  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 07:59:00.042  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 07:59:00.042  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:59:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 07:59:00.043  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 07:59:04.303   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:09.308   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:14.312   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:14.486   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 07:59:14.489  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 07:59:14.490  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 07:59:14.495  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 07:59:14.496  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 07:59:14.496  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 07:59:17.274   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:59:17.274   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:59:17.274   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1032287596642; DSPS: 33917352; Offset : -2799539268
,06-22 07:59:19.317   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:24.321   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:26.369   842  1284 D PowerManagerServiceEx: acquireWakeLockInternal: lock=51323580, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,06-22 07:59:26.375   842  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{35f1bae6 type 2 when 1041370 com.android.bluetooth} when 1041370
06-22 07:59:26.491   842   842 D PowerManagerServiceEx: releaseWakeLockInternal: lock=51323580 [*alarm*], flags=0x0
,06-22 07:59:26.519  2055  6026 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
06-22 07:59:26.519  2055  6026 W bt-smp  : Plain text(LSB ~ MSB) = 1c 03 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
,06-22 07:59:26.522  2055  6026 W bt-smp  : Encrypted text(LSB ~ MSB) = 5c c0 ee f6 29 34 d8 df 92 8a d6 a8 2e 30 64 56 
06-22 07:59:26.522  2055  6026 W bt-btm  : Stopping oneshot timer
06-22 07:59:29.326   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:34.330   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:37.275   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:59:37.275   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:59:37.275   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1052288255644; DSPS: 34572733; Offset : -2799521083
,06-22 07:59:39.335   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:44.340   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:49.344   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:54.349   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 07:59:57.276   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 07:59:57.276   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 07:59:57.276   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1072289098449; DSPS: 35228121; Offset : -2799532979
,06-22 07:59:59.353   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:00.038  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 08:00:00.038  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:00:00.038  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:00:00.042  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:00:00.042  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:00:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:00:00.043  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 08:00:04.358   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:09.363   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:14.367   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:14.659  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-22 08:00:14.661  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 08:00:14.662  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 08:00:14.662  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 08:00:14.662  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 08:00:14.669   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 08:00:17.277   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:00:17.277   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:00:17.277   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1092289854066; DSPS: 35883506; Offset : -2799540379
,06-22 08:00:19.372   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:24.376   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:29.381   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:34.385   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:37.277   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:00:37.277   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:00:37.277   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1112290924945; DSPS: 36538901; Offset : -2799537147
,06-22 08:00:39.390   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:44.395   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:49.399   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:54.404   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:00:57.278   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:00:57.278   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:00:57.278   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1132291670146; DSPS: 37194285; Offset : -2799524811
,06-22 08:00:59.408   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:00.038  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 08:01:00.038  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:01:00.038  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:01:00.042  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:01:00.042  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:01:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:01:00.044  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 08:01:04.413   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:09.417   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:14.422   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:14.806  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 08:01:14.806  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 08:01:14.806  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 08:01:14.807  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-22 08:01:14.809   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 08:01:14.810  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 08:01:14.849  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
06-22 08:01:14.849  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 08:01:14.849  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,06-22 08:01:14.853  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 08:01:14.853  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 08:01:14.854  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 08:01:14.854  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 08:01:14.854  1852  2044 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
06-22 08:01:14.856  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 08:01:14.858  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 08:01:14.859   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 08:01:14.860   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 08:01:14.860   842  1312 D WifiController: battery changed pluggedType: 2
06-22 08:01:17.279   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:01:17.279   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:01:17.279   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1152292435502; DSPS: 37849670; Offset : -2799522472
,06-22 08:01:19.427   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:24.431   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:29.436   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:34.440   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:37.280   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:01:37.280   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:01:37.280   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1172293193516; DSPS: 38505055; Offset : -2799527319
,06-22 08:01:39.445   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:44.449   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:49.454   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:54.459   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:01:57.280   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:01:57.280   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:01:57.280   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1192293908925; DSPS: 39160439; Offset : -2799544592
,06-22 08:01:59.463   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:00.038  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 08:02:00.038  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:02:00.038  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:02:00.042  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:02:00.042  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:02:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:02:00.044  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 08:02:04.468   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:09.472   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:14.477   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:14.967  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 08:02:14.967  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 08:02:14.967  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 08:02:14.967  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-22 08:02:14.969   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 08:02:14.976  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 08:02:15.012  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
06-22 08:02:15.012  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 08:02:15.012  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,06-22 08:02:15.016  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 08:02:15.017  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 08:02:15.018  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 08:02:15.019  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 08:02:15.019  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 08:02:15.020  1852  2044 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
06-22 08:02:15.021  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 08:02:15.023   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 08:02:15.023   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 08:02:15.023   842  1312 D WifiController: battery changed pluggedType: 2
06-22 08:02:17.281   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:02:17.281   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:02:17.281   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1212294592979; DSPS: 39815821; Offset : -2799531483
,06-22 08:02:19.481   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:24.486   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:29.291   842   942 I UsageStatsService: User[0] Flushing usage stats to disk
,06-22 08:02:29.491   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:34.495   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:37.282   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:02:37.282   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:02:37.282   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1232295356201; DSPS: 40471206; Offset : -2799531277
,06-22 08:02:39.500   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:44.504   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:49.509   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:54.514   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:02:57.282   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:02:57.283   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:02:57.283   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1252296088433; DSPS: 41126590; Offset : -2799531441
,06-22 08:02:59.518   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:00.038  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 08:03:00.038  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:03:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:03:00.043  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:03:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:03:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:03:00.044  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 08:03:04.523   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:09.527   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:14.532   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:15.126  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 08:03:15.126  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 08:03:15.126  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 08:03:15.126  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-22 08:03:15.129   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 08:03:15.130  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 08:03:15.168  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
06-22 08:03:15.168  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-22 08:03:15.168  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,06-22 08:03:15.171  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-22 08:03:15.171  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-22 08:03:15.172  1852  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-22 08:03:15.172  1852  2044 D LEDHandler: Battery Level Remaining: 100%
06-22 08:03:15.172  1852  2044 D LEDHandler: Battery Temp: 283, mChargingStatus=5, mChargingStop=false
06-22 08:03:15.177  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-22 08:03:15.178  2055  6009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 08:03:15.179   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 08:03:15.179   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 08:03:15.180   842  1312 D WifiController: battery changed pluggedType: 2
06-22 08:03:17.283   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:03:17.283   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:03:17.283   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1272296853737; DSPS: 41781975; Offset : -2799528948
,06-22 08:03:19.536   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:24.541   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:29.546   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:34.550   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:37.284   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:03:37.284   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:03:37.284   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1292297617688; DSPS: 42437360; Offset : -2799528404
,06-22 08:03:39.555   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:44.559   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:49.564   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:54.568   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:03:57.285   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:03:57.285   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:03:57.285   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1312298296639; DSPS: 43092742; Offset : -2799520476
,06-22 08:03:59.573   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 08:04:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:04:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:04:00.043  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:04:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:04:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:04:00.045  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 08:04:04.578   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:09.582   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:14.587   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:15.286  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 08:04:15.286  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 08:04:15.286  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 08:04:15.287  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-22 08:04:15.289   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 08:04:15.290  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 08:04:17.285   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:04:17.286   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:04:17.286   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1332299063766; DSPS: 43748128; Offset : -2799547196
,06-22 08:04:19.591   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:24.596   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:29.600   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:34.609   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:37.286   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:04:37.286   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:04:37.286   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1352299746884; DSPS: 44403510; Offset : -2799534918
,06-22 08:04:39.614   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:44.618   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:49.623   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:54.627   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:04:57.287   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:04:57.287   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:04:57.287   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1372300762085; DSPS: 45058903; Offset : -2799526511
,06-22 08:04:59.632   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:00.038  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 08:05:00.038  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:05:00.038  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:05:00.042  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:05:00.042  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:05:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:05:00.044  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 08:05:04.637   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:09.641   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:14.646   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:15.446   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-22 08:05:15.454  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 08:05:15.455  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 08:05:15.455  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 08:05:15.455  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 08:05:15.456  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 08:05:17.288   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:05:17.288   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:05:17.288   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1392301442182; DSPS: 45714285; Offset : -2799518400
,06-22 08:05:19.650   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:24.661   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:29.666   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:34.670   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:37.289   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:05:37.289   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:05:37.289   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1412302205820; DSPS: 46369670; Offset : -2799517622
,06-22 08:05:39.675   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:44.679   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:49.684   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:54.689   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:05:57.289   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:05:57.289   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:05:57.290   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1432302971489; DSPS: 47025056; Offset : -2799545410
,06-22 08:05:59.693   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:00.038  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 08:06:00.038  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:06:00.038  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:06:00.042  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:06:00.042  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:06:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:06:00.044  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 08:06:04.698   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:09.702   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:14.707   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:15.606  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 08:06:15.606  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,06-22 08:06:15.609   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 08:06:15.615  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 08:06:15.616  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 08:06:15.616  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
06-22 08:06:17.290   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:06:17.290   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:06:17.290   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1452303740388; DSPS: 47680441; Offset : -2799539633
,06-22 08:06:19.711   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:24.716   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:29.721   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:34.725   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:37.291   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:06:37.291   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:06:37.291   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1472304426630; DSPS: 48335823; Offset : -2799524517
,06-22 08:06:39.730   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:44.734   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:49.739   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:54.743   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:06:57.292   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:06:57.292   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:06:57.292   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1492305208237; DSPS: 48991209; Offset : -2799536003
,06-22 08:06:59.748   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:07:00.039  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-22 08:07:00.039  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
06-22 08:07:00.039  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,06-22 08:07:00.043  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
06-22 08:07:00.043  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:07:00.044  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
06-22 08:07:00.044  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
06-22 08:07:04.752   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:07:09.764   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:07:14.768   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:07:15.766  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-22 08:07:15.766  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-22 08:07:15.766  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-22 08:07:15.766  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-22 08:07:15.769   485   485 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-22 08:07:15.770  1852  1852 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-22 08:07:17.292   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:07:17.292   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:07:17.293   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1512305975886; DSPS: 49646594; Offset : -2799531554
,06-22 08:07:19.773   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:07:24.777   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:07:29.782   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-22 08:07:34.786   295   354 I ThermalEngine: Sensor:pa_therm0:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),06-22 08:07:36.433  8067  8067 D AndroidRuntime: 
06-22 08:07:36.433  8067  8067 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-22 08:07:36.449  8067  8067 D AndroidRuntime: CheckJNI is OFF
06-22 08:07:36.792  8067  8067 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-22 08:07:36.796   842  1383 I ActivityManager: Process com.google.android.talk (pid 7367) has died
06-22 08:07:36.858   842   970 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
06-22 08:07:36.858   842   970 I ActivityManager: Killing 5844:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
06-22 08:07:36.916   842  1383 I WindowState: WIN DEATH: Window{373c5b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-22 08:07:36.954   842  1383 D InputDispatcher: Focus left window: Window{373c5b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-22 08:07:36.954   842  1383 D InputDispatcher: Window went away: Window{373c5b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-22 08:07:36.977   842  1047 W PackageSettings: Skipping PackageSetting{3997c1ac com.example.hello/10317} due to missing metadata
06-22 08:07:37.008   842   970 I ActivityManager:   Force finishing activity ActivityRecord{22ee6d9a u0 com.test.thalitest/.MainActivity t238}
06-22 08:07:37.056   842   842 V ActivityManager: Display changed displayId=0
06-22 08:07:37.060  1758  1758 D DSDPConnection: Display #0 changed.
06-22 08:07:37.082   842  1944 W ActivityManager: Spurious death for ProcessRecord{12c2d827 5844:com.test.thalitest/u0a30}, curProc for 5844: null
06-22 08:07:37.084   842  1047 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
06-22 08:07:37.085   842  1047 I ActivityManager:   Force finishing activity ActivityRecord{22ee6d9a u0 com.test.thalitest/.MainActivity t238 f}
06-22 08:07:37.086   842  1047 W ActivityManager: Duplicate finish request for ActivityRecord{22ee6d9a u0 com.test.thalitest/.MainActivity t238 f}
06-22 08:07:37.149  2026  2026 I art     : Explicit concurrent mark sweep GC freed 515(23KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/21MB, paused 1.670ms total 60.864ms
06-22 08:07:37.167  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
06-22 08:07:37.176  3380  3380 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-22 08:07:37.185   842  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-22 08:07:37.191  2351  2648 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-22 08:07:37.197  1907  1907 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
06-22 08:07:37.203  5591  5591 I art     : Explicit concurrent mark sweep GC freed 8369(429KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 16MB/22MB, paused 1.224ms total 97.543ms
06-22 08:07:37.206  3380  3380 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
06-22 08:07:37.206  3380  3380 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
06-22 08:07:37.206  3380  3380 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
06-22 08:07:37.207  3380  3380 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 08:07:37.207  3380  3380 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 08:07:37.207  3380  3380 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-22 08:07:37.207  3380  3380 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
06-22 08:07:37.207  3380  3380 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 08:07:37.207  3380  3380 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 08:07:37.207  3380  3380 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
06-22 08:07:37.207  3380  3380 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
06-22 08:07:37.223  1758  1758 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-22 08:07:37.225   842   970 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8097 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
06-22 08:07:37.252  1945  1945 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
06-22 08:07:37.286  1374  1374 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
06-22 08:07:37.292  1374  1512 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-22 08:07:37.292  1374  1512 D KeyguardModel: createShortcutInfo...
06-22 08:07:37.294   842   990 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-22 08:07:37.294   842   990 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-22 08:07:37.294   842   990 D sensors_hal_Time: tsOffsetIs: Apps: 1532307864055; DSPS: 50302016; Offset : -2799535684
06-22 08:07:37.301  1374  1512 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-22 08:07:37.301  1374  1512 D KeyguardModel: createShortcutInfo...
06-22 08:07:37.314  1374  1512 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 08:07:37.314  1374  1512 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
06-22 08:07:37.333  1374  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-22 08:07:37.335  1374  1512 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-22 08:07:37.338  1945  1945 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
06-22 08:07:37.357  1374  1512 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-22 08:07:37.357  1374  1512 D KeyguardModel: createShortcutInfo...
06-22 08:07:37.362  1374  1512 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-22 08:07:37.364  1374  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-22 08:07:37.365  1374  1512 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-22 08:07:37.367  1374  1512 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-22 08:07:37.367  1374  1512 D KeyguardModel: createShortcutInfo...
06-22 08:07:37.370  1945  1945 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
06-22 08:07:37.373  1374  1512 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 08:07:37.373  1374  1512 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-22 08:07:37.373  1374  1512 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
06-22 08:07:37.375  1374  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-22 08:07:37.375  1374  1512 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-22 08:07:37.377  1374  1512 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-22 08:07:37.377  1374  1512 D KeyguardModel: createShortcutInfo...
06-22 08:07:37.378  1945  2048 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
06-22 08:07:37.382  1945  1945 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
06-22 08:07:37.384  1945  1945 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
06-22 08:07:37.386  1945  1945 I Activity: Activity.onPostResume() called 
06-22 08:07:37.397   842   842 I art     : Explicit concurrent mark sweep GC freed 49223(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/36MB, paused 16.159ms total 281.421ms
06-22 08:07:37.397  1374  1374 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
06-22 08:07:37.397  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
06-22 08:07:37.397   842  1047 I art     : WaitForGcToComplete blocked for 165.126ms for cause Explicit
06-22 08:07:37.399  1374  1374 D KeyguardModel: handleShortcutListChanged...
06-22 08:07:37.417  1374  1512 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-22 08:07:37.417  1374  1512 D KeyguardModel: createShortcutInfo...
06-22 08:07:37.419  1374  1512 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-22 08:07:37.420  1374  1512 D KeyguardModel: createShortcutInfo...
06-22 08:07:37.421  1945  1945 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
06-22 08:07:37.423  1374  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-22 08:07:37.423  1374  1512 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-22 08:07:37.427  1374  1512 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-22 08:07:37.427  1374  1512 D KeyguardModel: createShortcutInfo...
06-22 08:07:37.428  1374  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-22 08:07:37.429  1374  1512 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-22 08:07:37.430  1374  1512 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-22 08:07:37.430  1374  1512 D KeyguardModel: createShortcutInfo...
06-22 08:07:37.431  1374  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-22 08:07:37.431  1374  1512 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-22 08:07:37.433  1374  1512 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-22 08:07:37.433  1374  1512 D KeyguardModel: createShortcutInfo...
06-22 08:07:37.442  1374  1374 D KeyguardModel: handleShortcutListChanged...
06-22 08:07:37.442  1945  8117 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
06-22 08:07:37.464  8097  8097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 08:07:37.464  8097  8097 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-22 08:07:37.465  8097  8097 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-22 08:07:37.468   842  1025 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
06-22 08:07:37.470   842  1025 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
06-22 08:07:37.470   842  2033 D InputDispatcher: Focus entered window: Window{3c47e311 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
06-22 08:07:37.471  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
06-22 08:07:37.471  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
06-22 08:07:37.471  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
06-22 08:07:37.471  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
06-22 08:07:37.473   842  1025 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
06-22 08:07:37.473   842  1025 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
06-22 08:07:37.473   842  1025 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-22 08:07:37.473   842  1025 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2daee37,  pkg=WindowManager.LayoutParams
06-22 08:07:37.473   842  1025 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
06-22 08:07:37.474  1945  2264 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-22 08:07:37.474  1945  2264 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 08:07:37.474  1945  2264 I Adreno-EGL: Build Date: 03/02/15 Mon
06-22 08:07:37.474  1945  2264 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-22 08:07:37.474  1945  2264 I Adreno-EGL: Remote Branch: 
06-22 08:07:37.474  1945  2264 I Adreno-EGL: Local Patches: 
06-22 08:07:37.474  1945  2264 I Adreno-EGL: Reconstruct Branch: 
06-22 08:07:37.474  1945  2264 I OpenGLRenderer: Initialized EGL, version 1.4
06-22 08:07:37.525  1945  1945 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-22 08:07:37.528  1945  1945 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-22 08:07:37.528  1945  1945 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
06-22 08:07:37.535   842   842 D administrator: Handling package changes for user 0
06-22 08:07:37.540  1945  1945 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
06-22 08:07:37.551  1945  1945 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
06-22 08:07:37.552  1945  1945 I PhoneWindow: [setNavigationBarColor] color=0x 0
06-22 08:07:37.565   842  1908 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
06-22 08:07:37.569   842  1908 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5844 uid 10030
06-22 08:07:37.697  1945  1945 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
06-22 08:07:37.709  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-22 08:07:37.719   842  1027 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a9f6f50 u0 com.lge.launcher2/.Launcher t237} time:1532731
06-22 08:07:37.730  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
06-22 08:07:37.732  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
06-22 08:07:37.734  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
06-22 08:07:37.737  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
06-22 08:07:37.758   842  1047 I art     : Explicit concurrent mark sweep GC freed 15103(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.063ms total 360.185ms
06-22 08:07:37.780  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-22 08:07:37.814  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
06-22 08:07:37.814  1945  1945 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
06-22 08:07:37.815  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-22 08:07:37.827  1821  1821 D LCardEmulationManager: getHceAppCount hostAppNum : 0
06-22 08:07:37.827  1821  1821 D LCardEmulationManager: getDefaultRoute
06-22 08:07:37.836  8097  8097 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
06-22 08:07:37.862  8097  8097 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
06-22 08:07:37.864  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
06-22 08:07:37.868  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
06-22 08:07:37.868  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
06-22 08:07:37.869  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
06-22 08:07:37.873  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
06-22 08:07:37.883  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
06-22 08:07:37.884  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
06-22 08:07:37.888  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
06-22 08:07:37.889  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
06-22 08:07:37.890  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
06-22 08:07:37.893  8067  8067 D AndroidRuntime: Shutting down VM
06-22 08:07:37.899  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
06-22 08:07:37.911  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
06-22 08:07:37.929   842   842 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
06-22 08:07:37.929   842   842 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-22 08:07:37.935   842   842 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-22 08:07:37.946   842  1047 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8123 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
06-22 08:07:37.950   842  1348 D TaskPersister: removeObsoleteFile: deleting file=238_task.xml
06-22 08:07:38.068  1945  1945 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
06-22 08:07:38.093  8097  8097 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
06-22 08:07:38.153   842  2596 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8144 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
06-22 08:07:38.153   842  2596 I ActivityManager: Killing 7497:com.android.vending/u0a36 (adj 15): empty #11
06-22 08:07:38.155  1945  1945 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
06-22 08:07:38.155  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
06-22 08:07:38.156  1945  1945 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
06-22 08:07:38.156  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-22 08:07:38.185   310   310 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 32.866ms
06-22 08:07:38.212   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 551us total 26.520ms
06-22 08:07:38.237   842  1859 W libprocessgroup: failed to open /acct/uid_10036/pid_7497/cgroup.procs: No such file or directory
06-22 08:07:38.239   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 582us total 24.445ms
06-22 08:07:38.276  8144  8144 I AppUp4:AppBoxCP: onCreate
06-22 08:07:38.277  8144  8144 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
06-22 08:07:38.294  8144  8144 I AppUp4:DB:  setFingerPrint start
06-22 08:07:38.294  8144  8144 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
06-22 08:07:38.306  8144  8144 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
06-22 08:07:38.306  8144  8144 I AppUp4:DB:  SDK version = 21
06-22 08:07:38.306  8144  8144 I AppUp4:DB:  beforefinger == newfinger no write in DB
06-22 08:07:38.308  8144  8144 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
06-22 08:07:38.323  8144  8144 E SQLiteLog: (778) statement aborts at 16: [INSERT INTO exclude_apps(package) VALUES (?)] 
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: Error inserting package=com.test.thalitest
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
06-22 08:07:38.337  8144  8144 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
06-22 08:07:38.345  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
06-22 08:07:38.346  1945  1945 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
06-22 08:07:38.347  1945  1945 I Choreographer: Skipped 37 frames!  The application may be doing too much work on its main thread.
06-22 08:07:38.349  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-22 08:07:38.352  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
06-22 08:07:38.352  1945  2167 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
06-22 08:07:38.352  1945  2167 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
06-22 08:07:38.354  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
06-22 08:07:38.356  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
06-22 08:07:38.358  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
06-22 08:07:38.360  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
06-22 08:07:38.360  1629  1629 E b       : Unable to connect to the editor to retrieve text... will retry later
06-22 08:07:38.370  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-22 08:07:38.370  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-22 08:07:38.377   842  1951 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8165 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
06-22 08:07:38.378   842  1951 I ActivityManager: Killing 7538:com.google.android.apps.plus/u0a86 (adj 15): empty #11
06-22 08:07:38.383  3380  3404 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: Error inserting f004=13 f005=8165 f002=1466575658382 f003=com.android.settings f006=1000
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:708)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2588)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3413)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
06-22 08:07:38.401  3380  3404 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3522)

```
