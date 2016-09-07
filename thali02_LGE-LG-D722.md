#### Test 83627337140e0c5_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
09-07 09:06:22.813   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 132713409068; DSPS: 4447017; Offset : -3000390617
,09-07 09:06:23.787   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
09-07 09:06:23.808  6398  6398 D AndroidRuntime: 
09-07 09:06:23.808  6398  6398 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 09:06:23.812  6398  6398 D AndroidRuntime: CheckJNI is OFF
09-07 09:06:24.037  6398  6398 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 09:06:24.056   861  1894 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 09:06:24.112   861  1894 D ActivityManager: setTaskToReturnTo : TaskRecord{178a08f #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 09:06:24.114   861  1894 D ActivityManager: setTaskToReturnTo : TaskRecord{178a08f #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 09:06:24.138   861  1894 D WindowStateEx: AppWindowTokenEx init.. 
09-07 09:06:24.164   861  1032 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-07 09:06:24.173   861  1894 D InputDispatcher: Focus left window: Window{2e61cf88 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-07 09:06:24.175  6398  6398 D AndroidRuntime: Shutting down VM
09-07 09:06:24.183   861  1032 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-07 09:06:24.183  1877  1877 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
09-07 09:06:24.197   861  1032 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-07 09:06:24.197   861  1032 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-07 09:06:24.221   861  1032 D SplitWindow: check instance of lgWin Window{dfa1287 u0 Starting com.test.thalitest}
09-07 09:06:24.267   861  1060 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6418 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 09:06:24.284  1877  1877 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
09-07 09:06:24.350  1877  1877 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
09-07 09:06:24.350  1946  1946 I HotwordDetector: Closing mic
09-07 09:06:24.355  1946  2342 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1ccf5167
09-07 09:06:24.355  1946  2342 V AudioRecord: stop()
09-07 09:06:24.355  1946  2342 D AudioRecord: AudioRecord->stop()
09-07 09:06:24.355   282   282 V AudioFlinger: RecordHandle::stop()
09-07 09:06:24.355   282   282 V AudioFlinger: RecordThread::stop
09-07 09:06:24.355   282   282 V AudioFlinger: Record stopped OK
09-07 09:06:24.356   282   282 V AudioPolicyManager: stopInput() input 17
09-07 09:06:24.357   282   282 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
09-07 09:06:24.357   282   282 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
09-07 09:06:24.358   282  1063 V AudioPolicyService: AudioCommandThread() waking up
09-07 09:06:24.358   282  1063 V AudioPolicyService: AudioCommandThread() processing release audio patch
09-07 09:06:24.358   282  1063 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
09-07 09:06:24.359   282  1063 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
09-07 09:06:24.359   282  1063 V AudioFlinger: ThreadBase::setParameters() routing=0
09-07 09:06:24.359   282  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-07 09:06:24.361   282  2582 V AudioFlinger: processConfigEvents_l() remaining events 1
09-07 09:06:24.361   282  2582 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3a0f000
09-07 09:06:24.366   282  2582 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
09-07 09:06:24.371   861  1854 I WindowStateAnimator: Starting window displayed
09-07 09:06:24.379   861  1028 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
09-07 09:06:24.383   861  1028 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :win == null
,09-07 09:06:24.390   861  1028 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-07 09:06:24.390   861  1028 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-07 09:06:24.390   861  1028 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-07 09:06:24.391  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
09-07 09:06:24.391   861  1028 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@213041d7,  pkg=WindowManager.LayoutParams
09-07 09:06:24.391   861  1028 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-07 09:06:24.395  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
09-07 09:06:24.395  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
09-07 09:06:24.395  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-07 09:06:24.407   282  2582 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
09-07 09:06:24.407   282  2582 V audio_hw_primary: disable_audio_route: enter: usecase(7)
09-07 09:06:24.407   282  2582 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
09-07 09:06:24.407   282  2582 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 09:06:24.409   282  2582 V audio_hw_primary: disable_audio_route: exit
09-07 09:06:24.409   282  2582 E audio_hw_primary: disable_snd_device: enter 144
09-07 09:06:24.409   282  2582 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
09-07 09:06:24.409   282  2582 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
09-07 09:06:24.414   282  2582 V audio_hw_primary: stop_input_stream: exit: status(0)
09-07 09:06:24.414   282  2582 V audio_hw_primary: in_standby: exit:  status(0)
09-07 09:06:24.414   282  2582 V AudioFlinger: RecordThread: loop stopping
09-07 09:06:24.414   282  1063 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 09:06:24.415   282   282 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
09-07 09:06:24.415   282   282 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
09-07 09:06:24.415   282   282 V AudioPolicyService: AudioCommandThread() adding update audio patch list
09-07 09:06:24.415   282   282 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
09-07 09:06:24.415   282  1064 V AudioPolicyService: AudioCommandThread() waking up
09-07 09:06:24.415   282  1064 V AudioPolicyService: AudioCommandThread() processing update audio patch list
09-07 09:06:24.415   282  1064 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 09:06:24.418   282   282 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
09-07 09:06:24.418   282   282 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
09-07 09:06:24.418   282  1063 V AudioPolicyService: AudioCommandThread() waking up
09-07 09:06:24.418   282  1063 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
09-07 09:06:24.418   282  1063 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
09-07 09:06:24.418   282  1063 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
09-07 09:06:24.418   282  1063 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
09-07 09:06:24.418   282  2582 V AudioFlinger: RecordThread: loop starting
09-07 09:06:24.418   282  2582 V AudioFlinger: processConfigEvents_l() remaining events 1
09-07 09:06:24.418   282  2582 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
09-07 09:06:24.418   282  2582 V audio_hw_primary: in_set_parameters: exit: status(0)
09-07 09:06:24.418   282  2582 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3a0f000
09-07 09:06:24.418   282  2582 V AudioFlinger: RecordThread: loop stopping
09-07 09:06:24.419   282  1063 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 09:06:24.426  1946  2342 V AudioRecord: stop()
09-07 09:06:24.426  1946  2342 V AudioRecord: stop()
09-07 09:06:24.426  1946  2342 V AudioRecord: stop()
09-07 09:06:24.427   282  1322 V AudioFlinger: RecordHandle::stop()
09-07 09:06:24.427   282  1322 V AudioFlinger: RecordThread::stop
09-07 09:06:24.427   282  1322 V AudioPolicyManager: releaseInput() 17
09-07 09:06:24.427   282  1322 V AudioPolicyManager: closeInput(17)
09-07 09:06:24.427   282  1322 V AudioFlinger: closeInput() 17
09-07 09:06:24.427   282  1322 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 09:06:24.428   282  1322 V AudioFlinger: ThreadBase::exit
09-07 09:06:24.428   282  2582 V AudioFlinger: RecordThread: loop starting
09-07 09:06:24.428  3146  3161 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 09:06:24.428   282  2582 V AudioFlinger: RecordThread 0xb3a0f000 exiting
09-07 09:06:24.428   861  2205 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 09:06:24.429  1373  1399 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 09:06:24.429   282  1322 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546e1a0)
09-07 09:06:24.429   282  1322 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
09-07 09:06:24.429   282  1322 V audio_hw_primary: in_standby: exit:  status(0)
09-07 09:06:24.429  1749  2639 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 09:06:24.429   282  1322 V AudioPolicyService: AudioCommandThread() adding update audio port list
09-07 09:06:24.429   282  1322 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
09-07 09:06:24.429   282  1322 V AudioPolicyManager: releaseInput() exit
09-07 09:06:24.429   282  1064 V AudioPolicyService: AudioCommandThread() waking up
09-07 09:06:24.429   282  1064 V AudioPolicyService: AudioCommandThread() processing update audio port list
09-07 09:06:24.429   282  1322 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
09-07 09:06:24.430   282  1322 V AudioFlinger: removeClient_l() pid 1946, calling pid 282
09-07 09:06:24.430  2876  3928 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 09:06:24.430   282  1064 V AudioPolicyService: AudioCommandThread() going to sleep
09-07 09:06:24.430  1946  2336 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 09:06:24.430   282  1323 V AudioFlinger: releasing 16 from 1946 for -1
09-07 09:06:24.430   282  1323 V AudioFlinger:  decremented refcount to 0
09-07 09:06:24.430   282  1323 V AudioFlinger: purging stale effects
09-07 09:06:24.431  2009  3373 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
09-07 09:06:24.432  1946  2346 I HotwordRecognitionRnr: Stopping hotword detection.
09-07 09:06:24.442  1946  2577 I HotwordRecognitionRnr: Hotword detection finished
09-07 09:06:24.517  6418  6418 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-07 09:06:24.623  6418  6418 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
09-07 09:06:24.675  6418  6418 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4573-4576)
09-07 09:06:24.676  6418  6418 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 09:06:24.707  6418  6418 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {16149993}
09-07 09:06:24.708  6418  6418 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 09:06:24.709  6418  6418 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 09:06:24.724  6418  6418 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 09:06:24.725  6418  6418 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 09:06:24.726  6418  6418 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 09:06:24.748  6418  6418 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-07 09:06:24.754  6418  6418 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 09:06:24.754  6418  6418 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 09:06:24.755  6418  6418 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 09:06:24.755  6418  6418 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 09:06:24.755  6418  6418 I Adreno-EGL: Build Date: 03/02/15 Mon
09-07 09:06:24.755  6418  6418 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-07 09:06:24.755  6418  6418 I Adreno-EGL: Remote Branch: 
09-07 09:06:24.755  6418  6418 I Adreno-EGL: Local Patches: 
09-07 09:06:24.755  6418  6418 I Adreno-EGL: Reconstruct Branch: 
09-07 09:06:24.822   282   282 V AudioPolicyService: registerClient() client 0xb3a68f20, uid 10030
09-07 09:06:24.847   861  1029 D BluetoothManagerService: Message: 20
09-07 09:06:24.847   861  1029 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@171e8976:true
09-07 09:06:24.863  2009  3373 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:25.064  6418  6418 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 09:06:25.078  6418  6418 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-07 09:06:25.088  6418  6418 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-07 09:06:25.092  6418  6418 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-07 09:06:25.092  6418  6418 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-07 09:06:25.109  6418  6418 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
09-07 09:06:25.119  6418  6418 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 09:06:25.119  6418  6418 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 09:06:25.190  6418  6418 I Activity: Activity.onPostResume() called 
,09-07 09:06:25.205  6418  6479 D OpenGLRenderer: Render dirty regions requested: true
09-07 09:06:25.206  6418  6479 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 09:06:25.217  6418  6479 D OpenGLRenderer: Enabling debug mode 0
09-07 09:06:25.236  6418  6418 D Atlas   : Validating map...
,09-07 09:06:25.242   861  1060 D SplitWindow: check instance of lgWin Window{191a3c26 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 09:06:25.259  6418  6463 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 09:06:25.294   861  1060 D InputDispatcher: Focus entered window: Window{191a3c26 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 09:06:25.354   861  2160 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,09-07 09:06:25.363   861  1032 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s142ms
09-07 09:06:25.363   861  1032 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ee21f1c u0 com.test.thalitest/.MainActivity t259} time:135264
09-07 09:06:25.384  6418  6418 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f06c5f5 time:135284
,09-07 09:06:25.505  6418  6418 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6418
,09-07 09:06:25.701  6418  6418 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 09:06:26.181  6418  6482 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635611904
,09-07 09:06:26.213  6418  6482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 09:06:26.213  6418  6482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 09:06:26.213  6418  6482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 09:06:26.213  6418  6482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 09:06:26.213  6418  6482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-07 09:06:26.214  6418  6482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ffbae2e added. We now have 1 listener(s)
,09-07 09:06:26.222   861  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 09:06:26.225  6418  6482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
09-07 09:06:26.226  6418  6482 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
,09-07 09:06:26.228  6418  6482 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 09:06:26.228  6418  6482 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 09:06:26.235  6418  6482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4561665 added. We now have 1 listener(s)
09-07 09:06:26.236  6418  6482 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:06:26.247  6418  6482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 09:06:26.247  6418  6482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 09:06:26.247  6418  6482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 09:06:26.247  6418  6482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 09:06:26.247  6418  6482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 09:06:26.253  6418  6482 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:26.253   861  1827 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 09:06:26.254  6418  6482 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
09-07 09:06:26.267  2009  2046 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
,09-07 09:06:26.279  6418  6482 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 09:06:26.279  6418  6482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:26.279  6418  6482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:26.279  6418  6482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:06:26.279  6418  6482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:26.279  6418  6482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:26.279  6418  6482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:26.279  6418  6482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:26.279  6418  6482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:06:26.280  6418  6482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 09:06:26.280  6418  6482 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 09:06:26.282  6418  6482 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 09:06:26.345  6418  6418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:06:26.349  6418  6418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:26.352  6418  6418 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-07 09:06:26.437  6418  6432 I art     : CheckpointMarkThreadRoots callback created = 0x98a1dc30
,09-07 09:06:26.474  6418  6432 I art     : CheckpointMarkThreadRoots callback created = 0x98a1dbf0
,09-07 09:06:27.092  6418  6509 W jxcore-log: Initializing JXcore engine
,09-07 09:06:27.093  6418  6509 W jxcore-log: JXcore engine is ready
09-07 09:06:27.233  6509  6509 W Thread-754: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7906]" dev="sockfs" ino=7906 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-07 09:06:27.233  6509  6509 W Thread-754: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-07 09:06:27.233  6509  6509 W Thread-754: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6387]" dev="sockfs" ino=6387 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-07 09:06:27.233  6509  6509 W Thread-754: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-07 09:06:27.233  6509  6509 W Thread-754: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-07 09:06:27.233  6509  6509 W Thread-754: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30284]" dev="sockfs" ino=30284 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-07 09:06:27.262  6418  6509 W jxcore-log: Starting JXcore engine
,09-07 09:06:27.403  6418  6509 W jxcore-log: Platform android
09-07 09:06:27.403  6418  6509 W jxcore-log: 
,09-07 09:06:27.404  6418  6509 W jxcore-log: Process ARCH arm
09-07 09:06:27.404  6418  6509 W jxcore-log: 
09-07 09:06:27.682  6418  6509 I jxcore-log: JXcore Cordova bridge is ready!
09-07 09:06:27.682  6418  6509 I jxcore-log: 
09-07 09:06:27.683  6418  6509 W jxcore-log: JXcore engine is started
,09-07 09:06:27.688  6418  6482 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-07 09:06:27.690  6418  6418 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-07 09:06:28.696  2876  2876 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,09-07 09:06:28.704  2876  2876 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
09-07 09:06:28.791   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:06:29.420   861  1286 V AlarmManager: RTC_WAKEUP set : Alarm{1cde0ef1 type 0 when 1473231989413 com.google.android.googlequicksearchbox} when 1473231989413
,09-07 09:06:29.689  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,09-07 09:06:29.689  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 09:06:29.689  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
09-07 09:06:32.580   861  1876 I ActivityManager: Process com.google.android.apps.docs (pid 6126) has died
,09-07 09:06:33.698  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 09:06:33.698  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 09:06:33.698  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-07 09:06:33.796   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:06:35.700  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 09:06:35.700  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 09:06:35.700  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-07 09:06:36.071   861  1055 I PowerManagerService: ALS enabled for SRE
09-07 09:06:36.072   861  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (25972 ms ago)
,09-07 09:06:36.096   861  1350 D qdlights: set_light_backlight: 254
,09-07 09:06:36.110   861  1350 D qdlights: set_light_backlight: 250
,09-07 09:06:36.126   861  1350 D qdlights: set_light_backlight: 247
,09-07 09:06:36.143   861  1350 D qdlights: set_light_backlight: 244
,09-07 09:06:36.160   861  1350 D qdlights: set_light_backlight: 240
,09-07 09:06:36.177   861  1350 D qdlights: set_light_backlight: 237
,09-07 09:06:36.193   861  1350 D qdlights: set_light_backlight: 234
,09-07 09:06:36.210   861  1350 D qdlights: set_light_backlight: 230
,09-07 09:06:36.226   861  1350 D qdlights: set_light_backlight: 227
,09-07 09:06:36.243   861  1350 D qdlights: set_light_backlight: 224
,09-07 09:06:36.260   861  1350 D qdlights: set_light_backlight: 220
,09-07 09:06:36.277   861  1350 D qdlights: set_light_backlight: 217
,09-07 09:06:36.293   861  1350 D qdlights: set_light_backlight: 214
,09-07 09:06:36.310   861  1350 D qdlights: set_light_backlight: 210
,09-07 09:06:36.326   861  1350 D qdlights: set_light_backlight: 207
,09-07 09:06:36.343   861  1350 D qdlights: set_light_backlight: 204
,09-07 09:06:36.360   861  1350 D qdlights: set_light_backlight: 200
,09-07 09:06:36.377   861  1350 D qdlights: set_light_backlight: 197
,09-07 09:06:36.393   861  1350 D qdlights: set_light_backlight: 194
,09-07 09:06:36.410   861  1350 D qdlights: set_light_backlight: 190
,09-07 09:06:36.427   861  1350 D qdlights: set_light_backlight: 187
,09-07 09:06:36.443   861  1350 D qdlights: set_light_backlight: 184
,09-07 09:06:36.460   861  1350 D qdlights: set_light_backlight: 180
,09-07 09:06:36.477   861  1350 D qdlights: set_light_backlight: 177
09-07 09:06:36.493   861  1350 D qdlights: set_light_backlight: 174
,09-07 09:06:36.510   861  1350 D qdlights: set_light_backlight: 170
,09-07 09:06:36.526   861  1350 D qdlights: set_light_backlight: 167
,09-07 09:06:36.543   861  1350 D qdlights: set_light_backlight: 164
,09-07 09:06:36.560   861  1350 D qdlights: set_light_backlight: 160
,09-07 09:06:36.577   861  1350 D qdlights: set_light_backlight: 157
,09-07 09:06:36.593   861  1350 D qdlights: set_light_backlight: 154
,09-07 09:06:36.610   861  1350 D qdlights: set_light_backlight: 150
,09-07 09:06:36.627   861  1350 D qdlights: set_light_backlight: 147
,09-07 09:06:36.643   861  1350 D qdlights: set_light_backlight: 144
,09-07 09:06:36.660   861  1350 D qdlights: set_light_backlight: 140
,09-07 09:06:36.677   861  1350 D qdlights: set_light_backlight: 137
,09-07 09:06:36.697   861  1350 D qdlights: set_light_backlight: 134
,09-07 09:06:36.710   861  1350 D qdlights: set_light_backlight: 130
,09-07 09:06:36.727   861  1350 D qdlights: set_light_backlight: 127
,09-07 09:06:36.743   861  1350 D qdlights: set_light_backlight: 124
,09-07 09:06:36.760   861  1350 D qdlights: set_light_backlight: 120
,09-07 09:06:36.776   861  1350 D qdlights: set_light_backlight: 117
,09-07 09:06:36.793   861  1350 D qdlights: set_light_backlight: 114
,09-07 09:06:36.810   861  1350 D qdlights: set_light_backlight: 110
,09-07 09:06:36.826   861  1350 D qdlights: set_light_backlight: 107
,09-07 09:06:36.843   861  1350 D qdlights: set_light_backlight: 104
,09-07 09:06:36.860   861  1350 D qdlights: set_light_backlight: 100
,09-07 09:06:36.877   861  1350 D qdlights: set_light_backlight: 97
,09-07 09:06:36.894   861  1350 D qdlights: set_light_backlight: 94
,09-07 09:06:36.910   861  1350 D qdlights: set_light_backlight: 90
,09-07 09:06:36.926   861  1350 D qdlights: set_light_backlight: 87
,09-07 09:06:36.943   861  1350 D qdlights: set_light_backlight: 84
,09-07 09:06:36.960   861  1350 D qdlights: set_light_backlight: 80
,09-07 09:06:36.977   861  1350 D qdlights: set_light_backlight: 77
,09-07 09:06:36.997   861  1350 D qdlights: set_light_backlight: 74
,09-07 09:06:37.010   861  1350 D qdlights: set_light_backlight: 70
,09-07 09:06:37.026   861  1350 D qdlights: set_light_backlight: 67
,09-07 09:06:37.043   861  1350 D qdlights: set_light_backlight: 64
,09-07 09:06:37.060   861  1350 D qdlights: set_light_backlight: 60
,09-07 09:06:37.077   861  1350 D qdlights: set_light_backlight: 57
,09-07 09:06:37.093   861  1350 D qdlights: set_light_backlight: 54
,09-07 09:06:37.110   861  1350 D qdlights: set_light_backlight: 50
,09-07 09:06:37.127   861  1350 D qdlights: set_light_backlight: 47
,09-07 09:06:37.143   861  1350 D qdlights: set_light_backlight: 44
,09-07 09:06:37.160   861  1350 D qdlights: set_light_backlight: 40
,09-07 09:06:37.177   861  1350 D qdlights: set_light_backlight: 37
,09-07 09:06:37.193   861  1350 D qdlights: set_light_backlight: 34
,09-07 09:06:37.210   861  1350 D qdlights: set_light_backlight: 30
,09-07 09:06:37.227   861  1350 D qdlights: set_light_backlight: 27
,09-07 09:06:37.243   861  1350 D qdlights: set_light_backlight: 24
,09-07 09:06:37.260   861  1350 D qdlights: set_light_backlight: 20
,09-07 09:06:37.277   861  1350 D qdlights: set_light_backlight: 17
,09-07 09:06:37.293   861  1350 D qdlights: set_light_backlight: 14
,09-07 09:06:37.311   861  1350 D qdlights: set_light_backlight: 10
,09-07 09:06:38.801   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:06:39.708  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 09:06:39.708  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 09:06:39.708  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-07 09:06:40.709  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 09:06:40.709  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 09:06:40.709  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,09-07 09:06:42.813   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:06:42.813   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:06:42.813   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 152714255414; DSPS: 5102405; Offset : -3000396966
,09-07 09:06:43.075   861  1055 I PowerManagerService: ALS enabled for SRE
,09-07 09:06:43.075   861  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32976 ms ago)
09-07 09:06:43.078   861  1055 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
09-07 09:06:43.087   861  1055 I PowerManagerService: ALS enabled for SRE
09-07 09:06:43.087   861  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (32988 ms ago)
09-07 09:06:43.093   861  1055 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,09-07 09:06:43.098   861  1055 I PowerManagerService: Sleeping (uid 1000)...
09-07 09:06:43.098   861  1055 D LPWGController: [updateScreenState] screen on = false
09-07 09:06:43.103   861  1055 D LPWGController: disable proximity sensor
09-07 09:06:43.103   861  1055 D LPWGController: enable proximity sensor
09-07 09:06:43.115   861  1055 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1233a92d] by com.android.server.power.ProximitySensorListener.enable():120
,09-07 09:06:43.121   861  1055 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
09-07 09:06:43.121   861  1055 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
09-07 09:06:43.121   861  1055 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
09-07 09:06:43.121   861  1055 I sensors_hal_Ctx: activate: handle is 48, enable
09-07 09:06:43.121   861  1055 V sensors_hal_Ctx: activate sensors is 1400000000000
09-07 09:06:43.121   861  1055 D sensors_hal_Thresh: enable: handle=48
09-07 09:06:43.121   861  1055 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
09-07 09:06:43.122   861  1055 D sensors_hal_Util: waitForResponse: timeout=1000
09-07 09:06:43.126   861  1025 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
09-07 09:06:43.126   861  1025 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
,09-07 09:06:43.127   861  1055 D sensors_hal_Thresh: enable: Received response: 0
09-07 09:06:43.128   861  1055 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33028 ms ago)
09-07 09:06:43.153   861  1055 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 09:06:43.153   861  1055 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 09:06:43.153   861  1055 I Adreno-EGL: Build Date: 03/02/15 Mon
09-07 09:06:43.153   861  1055 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-07 09:06:43.153   861  1055 I Adreno-EGL: Remote Branch: 
09-07 09:06:43.153   861  1055 I Adreno-EGL: Local Patches: 
09-07 09:06:43.153   861  1055 I Adreno-EGL: Reconstruct Branch: 
,09-07 09:06:43.180   245  1902 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1174 us)
,09-07 09:06:43.353  6418  6509 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 09:06:43.353  6418  6509 I jxcore-log: 
,09-07 09:06:43.354   415  1014 I Sensors : sns_pwr.c(273):acquiring wakelock
09-07 09:06:43.355   861  1025 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
09-07 09:06:43.355   861  1025 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
09-07 09:06:43.356   861  1025 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
09-07 09:06:43.356   861  1025 D sensors_hal_Thresh: processInd: handle 48, count=1
09-07 09:06:43.356   861  1025 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
09-07 09:06:43.356   861  1025 I sensors_hal_Thresh: processInd : proximity state changed - FAR
09-07 09:06:43.356   861  1057 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
09-07 09:06:43.356   861  1057 D sensors_hal_Ctx: poll: count: 256
09-07 09:06:43.356   861  1057 I sensors_hal_Ctx: poll: released wakelock sensor_ind
09-07 09:06:43.356   861  1057 D sensors_hal_Util: waitForResponse: timeout=0
09-07 09:06:43.357   861  1055 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
09-07 09:06:43.357   861  1055 I LPWGController: current mode = 1  value = 1 1
09-07 09:06:43.358   861  1055 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
09-07 09:06:43.362  6418  6509 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 09:06:43.362  6418  6509 I jxcore-log: 
09-07 09:06:43.367  2009  2046 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
,09-07 09:06:43.368  6418  6509 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:43.368  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:43.368  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:06:43.368  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:43.368  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:43.368  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:43.368  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:43.368  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:06:43.371  2009  2046 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:43.372  6418  6509 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:43.375  6418  6509 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 09:06:43.375  6418  6509 I jxcore-log: 
09-07 09:06:43.382  6418  6509 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 09:06:43.382  6418  6509 I jxcore-log: 
,09-07 09:06:43.462   861  1055 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,09-07 09:06:43.715   861  1350 D qdlights: set_light_backlight: 0
09-07 09:06:43.715  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
09-07 09:06:43.716  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-07 09:06:43.716  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,09-07 09:06:43.735   861  1055 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,09-07 09:06:43.737   861  1055 I sensors_hal_Ctx: activate: handle is 46, disable
09-07 09:06:43.737   861  1055 V sensors_hal_Ctx: activate sensors is 1000000000000
09-07 09:06:43.737   861  1055 D sensors_hal_LP2: enable: handle=46
09-07 09:06:43.737   861  1055 D sensors_hal_LP2: enable: Disabling sensor handle=46
09-07 09:06:43.738   861  1055 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
09-07 09:06:43.741   245   245 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
09-07 09:06:43.741   245   245 D qdhwcomposer: hwc_blank: Blanking display: 0
09-07 09:06:43.745   861  1032 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
09-07 09:06:43.746   861   861 V ActivityManager: Display changed displayId=0
,09-07 09:06:43.794  1749  1749 D DSDPConnection: Display #0 changed.
,09-07 09:06:43.805   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:06:43.810   861  1052 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
09-07 09:06:43.810   861  1052 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
09-07 09:06:43.928   245   245 D qdhwcomposer: hwc_blank: Done blanking display: 0
09-07 09:06:43.929   861  1350 D SurfaceControl: Excessive delay in setPowerMode(): 187ms
,09-07 09:06:43.931   245   689 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-07 09:06:43.931   861  1350 I QCOM PowerHAL: Got set_interactive hint
,09-07 09:06:43.942  6418  6418 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-07 09:06:43.942  6418  6418 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
09-07 09:06:43.946  1373  1600 D KeyguardViewMediator: onScreenTurnedOff(3)
09-07 09:06:43.949  6418  6418 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b58a101 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@39c285c9, 16908290=android.view.AbsSavedState$1@39c285c9}, android:focusedViewId=100}]}]
09-07 09:06:43.949  6418  6418 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-07 09:06:43.949  6418  6418 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 09:06:43.949  6418  6418 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-07 09:06:43.963  1333  1348 D SmartCoverViewMediator: onScreenTurnedOff(3)
,09-07 09:06:43.964   861   861 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
09-07 09:06:43.979  1333  1348 D SmartCoverViewMediator: notifyScreenOffLocked
,09-07 09:06:43.980  1373  1600 D KeyguardViewMediator: notifyScreenOffLocked
09-07 09:06:43.981  1333  1333 D SmartCoverViewMediator: handleNotifyScreenOFF
09-07 09:06:43.988   861  1308 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
09-07 09:06:43.989   282  1300 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 861
09-07 09:06:43.990   282  1300 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-07 09:06:43.990   282  1300 V voice   : voice_set_parameters: enter: screen_state=on
09-07 09:06:43.992   282  1300 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
09-07 09:06:43.992   282  1300 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 09:06:43.992   282  1300 V voice   : voice_set_parameters: exit with code(0)
09-07 09:06:43.992   282  1300 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
09-07 09:06:43.992   282  1300 V msm8974_platform: platform_set_parameters: enter: screen_state=on
09-07 09:06:43.992   282  1300 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 09:06:43.992   282  1300 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 09:06:43.993   282  1300 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
09-07 09:06:43.993   282  1300 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-07 09:06:43.993   282  1300 V audio_hw_primary: adev_set_parameters: exit with code(0)
,09-07 09:06:44.005  1373  1600 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
09-07 09:06:44.005  1373  1373 D KeyguardViewMediator: handleNotifyScreenOff
09-07 09:06:44.017  1373  1373 D ScreenTurnOffBySensor: unregisterProximitySensor
,09-07 09:06:44.024  1373  1373 D StatusBarWindowView: onScreenTurnedOff why = 3
,09-07 09:06:44.026  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:06:44.338   861   905 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,09-07 09:06:44.343  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
09-07 09:06:44.346  1839  1839 I QCNEJ   : |CORE| sendScreenState: state:true
09-07 09:06:44.350  1803  1989 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,09-07 09:06:44.353  1803  1989 D LEDService: stopPatternFlashing()
09-07 09:06:44.354  1803  1989 D qdlights: set_light_notifications: 0,0,0,0,3
09-07 09:06:44.358  1803  1989 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-07 09:06:44.358  1803  1989 D qdlights: set_light_notifications: 0,0,0,0,3
09-07 09:06:44.359  1803  1989 I LEDService: updateLightsLocked : turn off led
09-07 09:06:44.359  1803  1989 D qdlights: set_light_notifications: 0,0,0,0,3
09-07 09:06:44.363  1803  1989 D LEDHandler: RESTART MSG
09-07 09:06:44.388   861   889 D SplitWindow: check instance of lgWin Window{10c0d0b0 u0 SearchPanel}
,09-07 09:06:44.388  6418  6509 I jxcore-log: Unit Test app is loaded
09-07 09:06:44.388  6418  6509 I jxcore-log: 
09-07 09:06:44.397  1803  1803 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
09-07 09:06:44.399  1803  1803 D Cliptray Service: lockStatus = 0
09-07 09:06:44.400  6418  6509 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:06:44.400  6418  6509 I jxcore-log: 
09-07 09:06:44.402  6418  6418 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 09:06:44.414   861  1894 D InputDispatcher: Window went away: Window{28b1900b u0 SearchPanel}
,09-07 09:06:44.417  1373  1373 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
09-07 09:06:44.420  6418  6509 D executeNativeTests: Running unit tests
09-07 09:06:44.436  1373  1373 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,09-07 09:06:44.441  1785  1785 D LNfcService: action : android.intent.action.SCREEN_ON
09-07 09:06:44.448  1785  6580 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
09-07 09:06:44.448  1785  6580 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
09-07 09:06:44.448  1785  6580 D LNfcService: isRequireNfcCRouting() return true
09-07 09:06:44.448  1785  6580 D LNfcService: isHCERoutingtoHost() return : true
09-07 09:06:44.453   861   861 D Ulp_jni : JNI:system_update. Event-0
,09-07 09:06:44.458  1785  6580 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-07 09:06:44.458  1785  6580 D NfcService: mEnableLPD: true
09-07 09:06:44.458  1785  6580 D NfcService: mEnableReader: false
09-07 09:06:44.458  1785  6580 D NfcService: mEnableHostRouting: true
09-07 09:06:44.458  1785  6580 D NfcService: newParams.techmask= mTechMask: default
09-07 09:06:44.458  1785  6580 D NfcService: mEnableLPD: true
09-07 09:06:44.458  1785  6580 D NfcService: mEnableReader: false
09-07 09:06:44.458  1785  6580 D NfcService: mEnableHostRouting: true
09-07 09:06:44.458  1785  6580 D NfcService: screenState= 3
09-07 09:06:44.458  1785  6580 D NfcService: Discovery configuration equal, not updating.
,09-07 09:06:44.472  1749  1749 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
09-07 09:06:44.491   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:06:44.491   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:06:44.492   861   861 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,09-07 09:06:44.495  2859  2859 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:6:44
09-07 09:06:44.497  2859  2859 D WeatherService: 2 : ACTION screen on
09-07 09:06:44.498  2859  2859 D WeatherService: 2 : shouldTimeTickRegistered : false
09-07 09:06:44.502  2859  2859 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-07 09:06:44.502  2859  2859 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:6:44
09-07 09:06:44.512  3969  3969 D AppCleanupService: android.intent.action.SCREEN_ON
,09-07 09:06:44.535   282  1322 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 861
09-07 09:06:44.536   282  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-07 09:06:44.536   282  1322 V voice   : voice_set_parameters: enter: screen_state=off
09-07 09:06:44.536   282  1322 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
09-07 09:06:44.536   282  1322 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-07 09:06:44.536   282  1322 V voice   : voice_set_parameters: exit with code(0)
09-07 09:06:44.536   282  1322 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
09-07 09:06:44.536   282  1322 V msm8974_platform: platform_set_parameters: enter: screen_state=off
09-07 09:06:44.536   282  1322 V msm8974_platform: platform_set_parameters: exit with code(0)
09-07 09:06:44.536   282  1322 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-07 09:06:44.536   282  1322 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
09-07 09:06:44.536   282  1322 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-07 09:06:44.537   861  1313 D WifiController: CMD_SCREEN_OFF 
09-07 09:06:44.538   861  1313 D WifiController: shouldWifiStayAwake TRUE
09-07 09:06:44.538   861   905 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
09-07 09:06:44.543  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,09-07 09:06:44.555  1839  1839 I QCNEJ   : |CORE| sendScreenState: state:false
,09-07 09:06:44.559  1803  1989 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
09-07 09:06:44.559  1803  1989 D LEDService: stopPatternFlashing()
09-07 09:06:44.559  1803  1989 D qdlights: set_light_notifications: 0,0,0,0,3
09-07 09:06:44.563  1803  1803 D VolumeVibrator: clear
09-07 09:06:44.565  1803  1989 I LEDService: getCurrentHighestLGLedRecord : size = 1
09-07 09:06:44.565  1803  1989 D qdlights: set_light_notifications: 0,0,0,0,3
09-07 09:06:44.567  1803  1803 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
09-07 09:06:44.568  1803  1989 I LEDService: updateLightsLocked : turn on led
09-07 09:06:44.568  1803  1989 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
09-07 09:06:44.568  1803  1989 E LEDService: Can't handle this request of patternId:0
09-07 09:06:44.568  1803  1989 D LEDHandler: RESTART MSG
,09-07 09:06:44.569  1785  1785 D LNfcService: action : android.intent.action.SCREEN_OFF
09-07 09:06:44.572  1785  2241 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
09-07 09:06:44.585  1877  1877 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
09-07 09:06:44.597  1749  1749 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,09-07 09:06:44.602   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:06:44.603   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:06:44.603   861   861 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
09-07 09:06:44.604  2859  2859 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:6:44
09-07 09:06:44.604  2859  2859 D WeatherService: 2 : ACTION screen off
09-07 09:06:44.605  2859  2859 D WeatherService: 2 : TimeTick Receiver Unregister
09-07 09:06:44.606  2859  2859 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:6:44
09-07 09:06:44.608  3969  3969 D AppCleanupService: android.intent.action.SCREEN_OFF
09-07 09:06:44.611  3969  6583 D AppCleanupService: AppUsageStatsSaveTask
,09-07 09:06:44.646  6418  6509 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 09:06:44.646  6418  6509 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e added. We now have 2 listener(s)
09-07 09:06:44.647   861  1894 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 09:06:44.649  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-07 09:06:44.649  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 09:06:44.649  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 09:06:44.649  6418  6509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:06:44.649  6418  6509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df added. We now have 2 listener(s)
09-07 09:06:44.649  6418  6509 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:06:44.650  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 09:06:44.652  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:44.654  2009  2047 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:44.656  6418  6509 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:44.656  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:44.656  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:06:44.656  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:44.656  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:44.656  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:44.656  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:44.656  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:06:44.656  2009  2047 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:44.657  6418  6509 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:44.657  6418  6509 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:06:44.660  6418  6418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:44.661  2009  2046 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
,09-07 09:06:44.663  6418  6418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:44.667  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 09:06:44.668  6418  6509 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:06:44.668  6418  6509 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:06:44.673  1785  2681 E NxpNfcJni: getReconnectState = 0x0
09-07 09:06:44.675  6418  6509 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 09:06:44.675  6418  6509 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 09:06:44.675  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 09:06:44.676  1785  2241 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-07 09:06:44.676  1785  2241 D LCardEmulationManager: getDefaultRoute
09-07 09:06:44.676  1785  2241 D LNfcService: isRequireNfcCRouting() return true
09-07 09:06:44.677  6418  6509 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:06:44.677  6418  6509 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:06:44.677  1785  2241 D LNfcService: isHCERoutingtoHost() return : true
09-07 09:06:44.677  1785  2241 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
09-07 09:06:44.677  1785  2241 D NfcService: mEnableLPD: true
09-07 09:06:44.677  1785  2241 D NfcService: mEnableReader: false
09-07 09:06:44.677  1785  2241 D NfcService: mEnableHostRouting: true
09-07 09:06:44.677  1785  2241 D NfcService: newParams.techmask= mTechMask: 0
09-07 09:06:44.677  1785  2241 D NfcService: mEnableLPD: true
09-07 09:06:44.677  1785  2241 D NfcService: mEnableReader: false
09-07 09:06:44.677  1785  2241 D NfcService: mEnableHostRouting: true
09-07 09:06:44.677  1785  2241 D NfcService: screenState= 1
09-07 09:06:44.681  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:44.681  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:44.681  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:06:44.681  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 09:06:44.681  6418  6509 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e removed from the list
09-07 09:06:44.681  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:44.681  6418  6509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df removed from the list
09-07 09:06:44.681  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:44.682  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:44.695  6418  6509 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 09:06:44.695  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:44.695  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:44.695  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:44.696  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:44.696  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:44.696  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in ,the list
09-07 09:06:44.696  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:44.696  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:44.696  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 09:06:44.703  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 09:06:44.704  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 09:06:44.704  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 09:06:44.704  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 09:06:44.704  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 09:06:44.704  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:44.704  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:44.704  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:44.704  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:44.704  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:44.704  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list
09-07 09:06:44.704  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:44.704  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:44.704  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:44.705  6418  6509 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:06:44.706  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:44.708  2009  2047 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:44.708  6418  6509 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:44.708  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:44.708  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:06:44.708  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:44.708  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:44.708  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:44.708  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:44.708  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:06:44.709  2009  2047 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:44.710  6418  6509 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:44.710  6418  6509 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:06:44.712  6418  6509 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:06:44.712  6418  6418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:44.712  6418  6509 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:06:44.712  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:06:44.712  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:44.712  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:06:44.714  6418  6418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:44.719  6418  6509 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 09:06:44.720   861  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 09:06:44.730  2009  2047 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:44.731  1785  2681 E NxpNfcJni: getReconnectState = 0x0
,09-07 09:06:44.732  2009  2046 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:44.733  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 09:06:44.738  2009  2047 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:44.739  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 09:06:44.740  2009  3373 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:44.741  6418  6509 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 09:06:44.743  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:06:44.743  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:06:44.746  6418  6509 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 09:06:44.747  6418  6509 I io.jxcore.node.ConnectionHelper: start: OK
09-07 09:06:44.854   415   431 I Sensors : sns_pwr.c(301):releasing wakelock
,09-07 09:06:47.748  6418  6509 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-07 09:06:47.749  6418  6509 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-07 09:06:47.749  6418  6509 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 09:06:48.810   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:06:48.997   861  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{7eac586 type 2 when 158895 com.android.systemui} when 158895
,09-07 09:06:48.999  1373  1373 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,09-07 09:06:49.014  1749  2341 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-07 09:06:49.018  1749  2341 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-07 09:06:49.018  1749  2341 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-07 09:06:49.022  1749  2341 V TelecomServiceImpl: getCallState : 0
09-07 09:06:49.023  1749  2639 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
09-07 09:06:49.023  1749  2639 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-07 09:06:49.023  1749  2639 D PhoneUtils: getPhoneCount() sPhoneCount = 1
09-07 09:06:49.024  1373  1373 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
,09-07 09:06:49.026  1373  1373 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
09-07 09:06:50.752  6418  6509 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:06:50.752  6418  6509 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-07 09:06:50.752  6418  6509 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:06:50.753  6418  6509 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:06:50.753  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:06:50.753  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:50.753  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 09:06:50.760  2009  3373 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:50.761  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:06:50.761  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:06:50.763  6418  6509 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 09:06:50.763  6418  6509 I io.jxcore.node.ConnectionHelper: start: OK
09-07 09:06:53.765  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:53.765  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:53.765  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:06:53.765  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:53.765  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:53.765  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list
09-07 09:06:53.765  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:53.765  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:53.770  6418  6509 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:06:53.773  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:53.776  2009  3373 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:53.777  6418  6509 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:53.777  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:53.777  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:06:53.777  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:53.777  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:53.777  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:53.777  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:53.777  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:06:53.778  2009  3373 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
,09-07 09:06:53.781  6418  6509 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:53.781  6418  6509 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:06:53.783  6418  6418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:53.785  6418  6418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:53.785  6418  6509 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:06:53.785  6418  6509 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:06:53.786  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:06:53.786  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:53.786  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:06:53.790  2009  3373 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
,09-07 09:06:53.794  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:06:53.794  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:06:53.796  6418  6509 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 09:06:53.796  6418  6509 I io.jxcore.node.ConnectionHelper: start: OK
09-07 09:06:53.816   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:06:56.797  6418  6509 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-07 09:06:56.797  6418  6509 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 09:06:56.797  6418  6509 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 09:06:58.822   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:06:59.808  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:59.808  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.808  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:06:59.808  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:59.808  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:59.808  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list
09-07 09:06:59.808  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:59.808  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:59.813  6418  6509 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 09:06:59.813  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:59.813  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.813  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.813  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:59.813  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:59.814  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list
09-07 09:06:59.814  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:59.814  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.814  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.815  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 09:06:59.815  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:59.815  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.815  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.815  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:59.815  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:59.815  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list
09-07 09:06:59.816  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:59.816  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.816  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.816  6418  6509 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 09:06:59.817  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:59.817  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.817  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.817  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:59.817  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:59.817  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list
09-07 09:06:59.817  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:59.817  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetooth,Manager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.817  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.818  6418  6509 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 09:06:59.818  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:59.818  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.818  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.818  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:59.818  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:59.818  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list
,09-07 09:06:59.818  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:59.818  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.818  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:59.821  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 09:06:59.830  6418  6509 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:06:59.830  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 09:06:59.830  6418  6509 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:06:59.831  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 09:06:59.831  6418  6509 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:06:59.832  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:59.832  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.832  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.832  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:59.832  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:59.832  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list
09-07 09:06:59.832  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:59.832  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.832  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.836  6418  6509 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 09:06:59.840  6418  6509 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 09:06:59.840  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 09:06:59.847  6418  6509 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:06:59.847  6418  6509 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 09:06:59.847  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 09:06:59.847  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 09:06:59.847  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:22,10:2210]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 09:06:59.848  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 09:06:59.849  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 09:06:59.849  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 09:06:59.849  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 09:06:59.849  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 09:06:59.850  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-07 09:06:59.850  6418  6509 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-07 09:06:59.862  6418  6509 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:06:59.864  6418  6509 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 09:06:59.864  6418  6509 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:06:59.864  6418  6509 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:06:59.864  6418  6509 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 09:06:59.864  6418  6509 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:06:59.864  6418  6509 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:06:59.864  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-07 09:06:59.881  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 09:06:59.882  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 09:06:59.883  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-07 09:06:59.887  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 09:06:59.887  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 09:06:59.887  6418  6509 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 09:06:59.888  6418  6509 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:06:59.888  6418  6509 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 09:06:59.888  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:59.888  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.888  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.888  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 09:06:59.890  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:59.890  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:59.890  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list
09-07 09:06:59.890  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:59.890  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.890  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.891  6418  6509 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 09:06:59.891  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:59.891  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.891  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.891  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:59.891  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:59.891  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list
09-07 09:06:59.891  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:59.892  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.892  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.893  6418  6509 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 09:06:59.893  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:59.893  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.893  6418  6509 D, org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.893  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:59.893  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:59.893  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list
09-07 09:06:59.893  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:06:59.893  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:59.893  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:59.894  6418  6509 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 09:06:59.895  6418  6509 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 09:06:59.895  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-07 09:06:59.895  6418  6509 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 09:06:59.895  6418  6509 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 09:06:59.895  6418  6509 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-07 09:06:59.895  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 09:06:59.895  6418  6509 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 09:06:59.895  6418  6509 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-07 09:06:59.895  6418  6509 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 09:06:59.895  6418  6509 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 09:06:59.895  6418  6509 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection,
,09-07 09:06:59.896  6418  6509 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:59.896  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:06:59.896  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:59.896  6418  6509 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c19d7e not in the list
09-07 09:06:59.896  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-07 09:06:59.896  6418  6509 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ae0a2df not in the list,
09-07 09:06:59.896  6418  6509 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:59.896  6418  6509 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:06:59.896  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-07 09:06:59.897  6418  6509 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:06:59.903  6418  6601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 851)
,09-07 09:06:59.918  6418  6602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 851,
,09-07 09:06:59.927  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:59.935  2009  2047 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
,09-07 09:06:59.940  6418  6509 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:59.940  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:59.940  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:06:59.940  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:59.940  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:59.940  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:59.940  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:59.940  6418  6509 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:06:59.941  2009  2047 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
09-07 09:06:59.942  6418  6509 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:59.942  6418  6509 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:06:59.944  6418  6418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:59.946  6418  6418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:59.946  6418  6509 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:06:59.946  6418  6509 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:06:59.946  6418  6509 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:06:59.946  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:59.946  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:06:59.956  2009  2047 D BluetoothAdapterService(465011145): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30b2b9e7
,09-07 09:06:59.960  6418  6509 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:06:59.961  6418  6509 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:06:59.966  6418  6509 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 09:06:59.966  6418  6509 I io.jxcore.node.ConnectionHelper: start: OK
09-07 09:07:00.044  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:07:00.044  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-07 09:07:00.049  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
09-07 09:07:00.051  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:07:00.051  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:07:00.052  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:07:00.053  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:07:00.122  6418  6601 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-07 09:07:00.122  6418  6601 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:07:00.152  2009  3373 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 09:07:00.155  2009  3373 I bt-btif : BTA_JvStartDiscovery
09-07 09:07:00.160  2009  3373 D LGBluetoothServiceAdapter: [BTUI] connectSocket FD=87 mFd=85
09-07 09:07:02.465  3611  4177 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 09:07:02.815   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:07:02.815   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:07:02.815   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 172715829561; DSPS: 5757817; Offset : -3000409941
,09-07 09:07:03.827   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:07:05.304  2009  3427 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-07 09:07:05.304  2009  3427 E bt-btif : DISCOVERY_COMP_EVT slot id:3, failed to find channle,                                       status:1, scn:0
,09-07 09:07:05.307  2009  3556 W bt-btif : invalid rfc slot id: 3
09-07 09:07:05.309  6418  6601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 851)
09-07 09:07:08.840   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:07:13.845   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:07:14.618   861  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=754922622, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,09-07 09:07:14.621   861  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1ab59c36 type 2 when 184516 com.google.android.gms} when 184516
09-07 09:07:14.666   861   861 D PowerManagerServiceEx: releaseWakeLockInternal: lock=754922622 [*alarm*], flags=0x0
,09-07 09:07:17.372   479   479 D charger_monitor: init target 500000
,09-07 09:07:17.377   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:07:17.382  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:07:17.382  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:07:17.382  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:07:17.382  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:07:17.383  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:07:17.423  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:07:17.427  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:07:17.428  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:07:17.429  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:07:17.429  1803  1989 D LEDHandler: Battery Temp: 275, mChargingStatus=5, mChargingStop=false
09-07 09:07:17.429  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
09-07 09:07:17.430  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:07:17.430  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
09-07 09:07:17.431  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:07:17.435  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:07:17.440   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:07:17.440   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:07:17.443   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:07:17.445  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:07:18.850   292   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:07:22.817   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:07:22.817   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:07:22.818   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 192718185375; DSPS: 6413254; Offset : -3000403799
,09-07 09:07:23.856   292   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:07:28.862   292   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:07:33.682  1732  4234 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 09:07:33.868   292   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:07:38.874   292   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:07:42.820   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:07:42.820   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:07:42.820   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 212720554996; DSPS: 7068691; Offset : -3000383900
,09-07 09:07:43.880   292   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:07:48.886   292   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:07:52.343   479   479 D charger_monitor: init target 500000
,09-07 09:07:52.348   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:07:52.352  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:07:52.352  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:07:52.352  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:07:52.352  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:07:52.355  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:07:52.405  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:07:52.408  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:07:52.408  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:07:52.410  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:07:52.410  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:07:52.410  1803  1989 D LEDHandler: Battery Temp: 273, mChargingStatus=5, mChargingStop=false
09-07 09:07:52.411  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
09-07 09:07:52.411  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:07:52.411  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
09-07 09:07:52.413  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:07:52.417   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:07:52.417   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:07:52.420   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:07:52.422  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:07:52.463  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:07:52.466  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
09-07 09:07:52.466  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:07:52.467  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
09-07 09:07:52.468  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:07:52.468  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:07:52.469  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:07:52.469  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:07:52.470  1803  1989 D LEDHandler: Battery Temp: 274, mChargingStatus=5, mChargingStop=false
09-07 09:07:52.472  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:07:52.475   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:07:52.476   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:07:52.478   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:07:52.479  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:07:53.892   292   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:07:55.804   861  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3cb02737 type 2 when 215005 android} when 215005
,09-07 09:07:58.898   292   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:08:00.042  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:08:00.042  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:08:00.042  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:08:00.046  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:08:00.046  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:08:00.047  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:08:00.048  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:08:02.822   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:08:02.822   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:08:02.822   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 232722859337; DSPS: 7724130; Offset : -3000490656
,09-07 09:08:03.904   292   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:08:08.910   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:08:13.916   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:08:17.523  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:08:17.530   479   479 D charger_monitor: init target 500000
09-07 09:08:17.533  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:08:17.533  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:08:17.533  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:08:17.533  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:08:17.535   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:08:17.594  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:08:17.597  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:08:17.597  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:08:17.599  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:08:17.599  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:08:17.599  1803  1989 D LEDHandler: Battery Temp: 272, mChargingStatus=5, mChargingStop=false
09-07 09:08:17.604   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:08:17.604   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:08:17.605   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:08:17.605  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
09-07 09:08:17.605  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:08:17.605  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
09-07 09:08:17.607  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:08:17.611  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:08:17.824   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:08:17.824   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:08:17.824   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 247725131577; DSPS: 8215721; Offset : -3000385008
,09-07 09:08:18.922   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:08:23.929   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:08:28.935   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:08:32.826   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:08:32.826   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:08:32.826   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 262727125683; DSPS: 8707309; Offset : -3000466124
,09-07 09:08:33.941   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:08:38.946   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:08:43.952   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:08:47.829   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:08:47.829   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,09-07 09:08:47.831   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 277729365839; DSPS: 9198903; Offset : -3000484451
09-07 09:08:48.958   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:08:53.964   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:08:58.969   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:00.077  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:09:00.077  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:09:00.077  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:09:00.081  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:09:00.081  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:09:00.082  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:09:00.083  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:09:00.961   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:09:00.961   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:09:00.961   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 290861649456; DSPS: 9629209; Offset : -3000097572
,09-07 09:09:03.974   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:08.980   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:13.986   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:15.967   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:09:15.967   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:09:15.967   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 305868179759; DSPS: 10120943; Offset : -3000098032
,09-07 09:09:17.688   479   479 D charger_monitor: init target 500000
,09-07 09:09:17.693   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:09:17.693  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:09:17.694  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:09:17.694  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:09:17.694  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:09:17.694  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:09:17.737  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:09:17.741  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:09:17.741  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:09:17.742  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:09:17.742  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:09:17.742  1803  1989 D LEDHandler: Battery Temp: 270, mChargingStatus=5, mChargingStop=false
09-07 09:09:17.748   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:09:17.748   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:09:17.748   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:09:17.749  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
09-07 09:09:17.749  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:09:17.749  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
09-07 09:09:17.752  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:09:17.754  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:09:18.992   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:23.998   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:29.004   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:32.852   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:09:32.852   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:09:32.852   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 322752891023; DSPS: 10674229; Offset : -3000335367
,09-07 09:09:34.011   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:39.017   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:44.023   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:49.028   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:52.327   861  3192 I LocationManagerService: remove 7fb6c8b
,09-07 09:09:52.331   861  3192 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
09-07 09:09:52.331   861  3192 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 09:09:52.334   861  3192 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
09-07 09:09:52.334   861  3192 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
09-07 09:09:52.334   861  3192 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,09-07 09:09:52.854   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:09:52.855   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:09:52.855   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 342755283004; DSPS: 11329668; Offset : -3000354380
,09-07 09:09:54.035   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:09:59.041   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:10:00.076  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:10:00.076  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:10:00.077  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:10:00.081  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:10:00.081  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:10:00.081  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:10:00.082  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:10:04.047   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:10:09.053   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:10:12.857   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:10:12.857   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:10:12.857   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 362757360217; DSPS: 11985101; Offset : -3000506798
,09-07 09:10:14.059   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:10:17.858   479   479 D charger_monitor: init target 500000
,09-07 09:10:17.863   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:10:17.873  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:10:17.873  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:10:17.873  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:10:17.873  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:10:17.876  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:10:17.913  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:10:17.916  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:10:17.916  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:10:17.917  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:10:17.917  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:10:17.917  1803  1989 D LEDHandler: Battery Temp: 269, mChargingStatus=5, mChargingStop=false
09-07 09:10:17.918  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
09-07 09:10:17.918  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:10:17.918  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
09-07 09:10:17.921  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:10:17.925   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:10:17.925   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:10:17.928   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:10:17.929  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:10:19.066   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:10:24.072   292   356 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:10:25.733   861  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=754922622, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,09-07 09:10:25.736   861  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{e7da4a4 type 2 when 375631 android} when 375631
09-07 09:10:25.761   861   861 D PowerManagerServiceEx: releaseWakeLockInternal: lock=754922622 [*alarm*], flags=0x0
,09-07 09:10:29.077   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:10:31.954  5631  5675 I PlayCommon: [652] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-07 09:10:31.967  1732  1732 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 09:10:31.980  1732  1732 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 09:10:31.983  1732  1732 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-07 09:10:32.030   861  1859 I NotificationManager: android: cancelAsUser(2) by android
,09-07 09:10:32.037  5631  5675 I PlayCommon: [652] com.google.android.play.a.l.a(927): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
09-07 09:10:32.043  5631  5675 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 09:10:32.043  5631  5675 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-07 09:10:32.048  5631  5675 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 09:10:32.048  5631  5675 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 09:10:32.050   278   923 E BandwidthController: [LG DATA] No such appUid: 10036
09-07 09:10:32.050   278   923 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
09-07 09:10:32.050   278  6668 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
09-07 09:10:32.050   278  6668 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 09:10:32.051   278  6668 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=101
09-07 09:10:32.051   278  6668 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-07 09:10:32.052   278  6668 D libc-netbsd: res_queryN name = xxxxx succeed
09-07 09:10:32.053  5631  5675 I System.out: propertyValue:false
09-07 09:10:32.274  5631  5675 I PlayCommon: [652] com.google.android.play.a.l.a(1002): Successfully uploaded logs.
,09-07 09:10:34.083   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:10:35.369   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:10:35.369   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:10:35.369   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 385269565470; DSPS: 12722777; Offset : -3000384840
,09-07 09:10:37.753  5631  5874 I PlayCommon: [670] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-07 09:10:37.753  5631  5874 I PlayCommon: [670] com.google.android.play.a.l.e(789): No file ready to send
,09-07 09:10:39.089   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:10:44.095   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:10:49.102   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:10:54.108   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:10:55.371   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:10:55.371   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:10:55.371   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 405271854579; DSPS: 13378212; Offset : -3000384471
,09-07 09:10:59.114   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:11:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:11:00.040  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:11:00.044  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:11:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:11:00.046  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:11:00.046  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:11:04.120   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:09.126   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:14.132   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:15.373   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:11:15.374   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:11:15.374   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 425274310481; DSPS: 14033654; Offset : -3000430906
,09-07 09:11:18.008   479   479 D charger_monitor: init target 500000
,09-07 09:11:18.013   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:11:18.015  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:11:18.015  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:11:18.015  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:11:18.016  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:11:18.016  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:11:18.061  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:11:18.061  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,09-07 09:11:18.065  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:11:18.066  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:11:18.066  1803  1989 D LEDHandler: Battery Temp: 266, mChargingStatus=5, mChargingStop=false
09-07 09:11:18.066  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:11:18.072   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:11:18.072   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:11:18.073   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:11:18.073  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
09-07 09:11:18.073  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:11:18.073  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
09-07 09:11:18.076  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:11:18.079  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:11:19.139   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:24.145   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:29.151   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:34.157   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:35.376   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:11:35.376   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:11:35.376   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 445276559337; DSPS: 14689085; Offset : -3000348851
,09-07 09:11:39.163   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:43.661  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:11:43.664  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:11:43.664  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:11:43.664  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:11:43.664  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:11:43.696   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:11:43.734  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:11:43.737  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:11:43.737  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:11:43.741  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:11:43.741  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:11:43.748   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:11:43.832  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:11:43.835  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:11:43.835  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:11:43.836  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:11:43.836  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:11:43.836  1803  1989 D LEDHandler: Battery Temp: 268, mChargingStatus=5, mChargingStop=false
09-07 09:11:43.838  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
09-07 09:11:43.838  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:11:43.838  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
09-07 09:11:43.840  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:11:43.844   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:11:43.844   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:11:43.847   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:11:43.848  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:11:43.887  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:11:43.890  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
09-07 09:11:43.891  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:11:43.891  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:11:43.892  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:11:43.892  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:11:43.892  1803  1989 D LEDHandler: Battery Temp: 268, mChargingStatus=5, mChargingStop=false
09-07 09:11:43.894  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:11:43.894  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
09-07 09:11:43.896  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:11:43.900   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:11:43.900   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:11:43.903   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:11:43.904  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:11:44.169   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:45.709  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:11:45.709  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:11:45.709  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:11:45.709  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:11:45.713  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:11:45.717   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:11:45.764  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:11:45.767  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:11:45.767  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:11:45.768  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:11:45.768  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:11:45.768  1803  1989 D LEDHandler: Battery Temp: 268, mChargingStatus=5, mChargingStop=false
09-07 09:11:45.770  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
09-07 09:11:45.770  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:11:45.770  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
09-07 09:11:45.772  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:11:45.776   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:11:45.776   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:11:45.780   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:11:45.780  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:11:49.175   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:54.182   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:11:55.378   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:11:55.378   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:11:55.378   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 465278880378; DSPS: 15344522; Offset : -3000377532
,09-07 09:11:59.188   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:00.049  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-07 09:12:00.051  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:12:00.051  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
09-07 09:12:00.053  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:12:00.053  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:12:00.054  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:12:00.055  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:12:04.194   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:09.200   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:14.206   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:15.381   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:12:15.381   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:12:15.381   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 485281596490; DSPS: 15999971; Offset : -3000377564
,09-07 09:12:18.179   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:12:18.181  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:12:18.182  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:12:18.182  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:12:18.182  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:12:18.182  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:12:18.224  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:12:18.227  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:12:18.227  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:12:18.229  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:12:18.229  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:12:18.230  1803  1989 D LEDHandler: Battery Temp: 266, mChargingStatus=5, mChargingStop=false
09-07 09:12:18.234   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:12:18.234   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:12:18.235   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:12:18.235  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
09-07 09:12:18.235  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:12:18.236  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
09-07 09:12:18.239  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:12:18.241  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:12:19.213   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:24.219   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:29.230   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:34.236   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:35.383   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:12:35.383   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:12:35.383   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 505283854449; DSPS: 16655405; Offset : -3000377880
,09-07 09:12:39.242   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:44.248   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:49.255   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:54.261   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:12:55.385   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:12:55.385   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:12:55.385   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 525286161748; DSPS: 17310841; Offset : -3000389889
,09-07 09:12:59.266   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:00.073  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:13:00.073  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:13:00.073  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:13:00.077  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:13:00.077  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:13:00.078  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:13:00.078  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:13:04.272   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:09.278   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:14.284   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:15.388   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:13:15.388   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:13:15.388   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 545288446610; DSPS: 17966276; Offset : -3000393820
,09-07 09:13:18.340  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:13:18.344   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:13:18.344  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:13:18.344  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:13:18.345  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:13:18.345  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:13:18.386  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:13:18.390  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:13:18.390  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:13:18.391  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:13:18.391  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:13:18.391  1803  1989 D LEDHandler: Battery Temp: 265, mChargingStatus=5, mChargingStop=false
09-07 09:13:18.397   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:13:18.397   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:13:18.397   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:13:18.398  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
09-07 09:13:18.398  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:13:18.398  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
09-07 09:13:18.401  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:13:18.404  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:13:19.290   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:24.296   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:29.303   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:34.309   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:35.390   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:13:35.390   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:13:35.390   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 565290730865; DSPS: 18621713; Offset : -3000459600
,09-07 09:13:39.315   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:44.321   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:49.327   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:54.333   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:13:55.392   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:13:55.392   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:13:55.392   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 585293064457; DSPS: 19277152; Offset : -3000536767
,09-07 09:13:59.340   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:00.075  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:14:00.075  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:14:00.075  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:14:00.080  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:14:00.080  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:14:00.081  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:14:00.081  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:14:04.346   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:09.352   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:09.464   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:14:09.464   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:14:09.464   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 599364875999; DSPS: 19738254; Offset : -3000441586
,09-07 09:14:14.358   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:18.492   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:14:18.494  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:14:18.495  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:14:18.495  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:14:18.495  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:14:18.495  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:14:18.536  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:14:18.540  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:14:18.540  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:14:18.540  1803  1989 D LEDHandler: Battery Temp: 265, mChargingStatus=5, mChargingStop=false
09-07 09:14:18.541  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:14:18.541  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:14:18.546   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:14:18.546   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:14:18.547   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:14:18.547  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
09-07 09:14:18.547  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:14:18.548  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
09-07 09:14:18.550  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:14:18.553  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:14:19.364   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:24.371   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:24.466   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:14:24.466   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:14:24.467   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 614367212447; DSPS: 20229849; Offset : -3000393748
,09-07 09:14:29.377   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:34.383   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:39.389   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:44.395   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:44.469   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:14:44.469   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:14:44.469   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 634369493829; DSPS: 20885283; Offset : -3000370928
,09-07 09:14:49.401   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:54.407   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:59.414   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:14:59.471   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:14:59.471   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:14:59.471   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 649371757626; DSPS: 21376878; Offset : -3000396027
,09-07 09:15:00.075  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:15:00.075  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:15:00.075  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:15:00.080  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:15:00.080  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:15:00.081  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:15:00.082  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:15:04.420   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:15:09.426   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:15:14.432   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:15:16.975   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:15:16.975   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:15:16.975   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 666875656699; DSPS: 21950440; Offset : -3000220047
,09-07 09:15:18.652   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:15:18.654  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:15:18.655  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:15:18.655  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:15:18.655  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:15:18.655  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:15:18.696  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:15:18.700  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:15:18.700  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:15:18.701  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:15:18.701  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:15:18.701  1803  1989 D LEDHandler: Battery Temp: 263, mChargingStatus=5, mChargingStop=false
09-07 09:15:18.707   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:15:18.707   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:15:18.707   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:15:18.708  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
09-07 09:15:18.708  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:15:18.708  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
09-07 09:15:18.710  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:15:18.713  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:15:19.438   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:15:24.445   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:15:29.451   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:15:34.457   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:15:37.855  5631  5874 I PlayCommon: [670] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-07 09:15:37.855  5631  5874 I PlayCommon: [670] com.google.android.play.a.l.e(789): No file ready to send
,09-07 09:15:39.463   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:15:39.479   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:15:39.479   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:15:39.479   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 689379768578; DSPS: 22687860; Offset : -3000380186
,09-07 09:15:44.469   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:15:49.475   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:15:54.481   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:15:59.481   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:15:59.481   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:15:59.481   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 709381558609; DSPS: 23343279; Offset : -3000391005
,09-07 09:15:59.486   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
09-07 09:16:00.075  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:16:00.075  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:16:00.076  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:16:00.080  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:16:00.080  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:16:00.081  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:16:00.082  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:16:04.498   292   356 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:16:09.504   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:16:14.510   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:16:18.803  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:16:18.813  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:16:18.813  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:16:18.814  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:16:18.814  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:16:18.815   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:16:19.483   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:16:19.483   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:16:19.483   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 729383845891; DSPS: 23998714; Offset : -3000392671
,09-07 09:16:19.516   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:16:24.522   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:16:29.528   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:16:34.485   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:16:34.485   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:16:34.485   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 744386111549; DSPS: 24490319; Offset : -3000721032
,09-07 09:16:34.534   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:16:39.541   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:16:44.547   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:16:49.492   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:16:49.492   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:16:49.492   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 759392807003; DSPS: 24982053; Offset : -3000556209
,09-07 09:16:49.553   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:16:54.559   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:16:59.566   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:00.076  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:17:00.076  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:17:00.076  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:17:00.081  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:17:00.081  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:17:00.082  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:17:00.082  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:17:04.572   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:09.578   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:10.748   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:17:10.748   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:17:10.748   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 780648646665; DSPS: 25678559; Offset : -3000392895
,09-07 09:17:14.584   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:18.963  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:17:18.965  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:17:18.965  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:17:18.965  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:17:18.965  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:17:18.975   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:17:19.016  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:17:19.020  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:17:19.020  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:17:19.021  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:17:19.021  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:17:19.021  1803  1989 D LEDHandler: Battery Temp: 262, mChargingStatus=5, mChargingStop=false
09-07 09:17:19.026   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:17:19.026   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:17:19.027   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:17:19.027  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 262
09-07 09:17:19.027  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:17:19.028  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 262
09-07 09:17:19.030  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:17:19.033  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:17:19.590   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:24.596   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:29.603   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:30.750   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:17:30.750   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:17:30.750   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 800650953222; DSPS: 26333995; Offset : -3000405675
,09-07 09:17:32.279  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,09-07 09:17:32.290  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:17:32.290  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:17:32.290  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:17:32.291   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:17:32.294  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:17:32.348  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 261
,09-07 09:17:32.351  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:17:32.352  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 261
09-07 09:17:32.354  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:17:32.354  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:17:32.356  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:17:32.356  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:17:32.356  1803  1989 D LEDHandler: Battery Temp: 261, mChargingStatus=5, mChargingStop=false
09-07 09:17:32.360  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:17:32.364  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:17:32.368   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:17:32.368   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:17:32.369   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:17:32.369  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:17:34.609   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:39.615   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:44.621   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:49.627   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:50.752   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:17:50.752   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:17:50.753   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 820653224156; DSPS: 26989429; Offset : -3000392912
,09-07 09:17:54.634   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:17:59.639   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:00.062  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:18:00.062  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:18:00.062  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:18:00.066  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:18:00.066  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:18:00.067  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:18:00.067  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:18:04.645   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:05.755   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:18:05.755   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:18:05.755   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 835655631683; DSPS: 27481027; Offset : -3000365860
,09-07 09:18:09.652   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:14.658   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:19.130  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:18:19.132   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:18:19.139  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:18:19.139  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:18:19.139  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:18:19.139  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:18:19.664   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:24.670   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:25.757   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:18:25.757   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:18:25.757   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 855657944344; DSPS: 28136464; Offset : -3000402922
,09-07 09:18:29.676   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:34.682   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:39.689   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:40.760   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:18:40.760   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:18:40.760   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 870660523038; DSPS: 28628068; Offset : -3000387444
,09-07 09:18:44.695   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:49.701   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:54.707   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:18:59.713   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:00.075  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:19:00.075  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:19:00.075  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:19:00.080  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:19:00.080  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:19:00.081  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:19:00.082  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:19:00.762   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:19:00.762   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:19:00.762   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 890662887801; DSPS: 29283503; Offset : -3000311865
,09-07 09:19:04.719   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:09.725   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:14.731   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:19.283  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:19:19.293  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:19:19.293  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:19:19.293  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:19:19.293  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:19:19.295   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:19:19.340  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:19:19.341  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,09-07 09:19:19.344  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:19:19.344  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:19:19.344  1803  1989 D LEDHandler: Battery Temp: 260, mChargingStatus=5, mChargingStop=false
09-07 09:19:19.345  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:19:19.349   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:19:19.349   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:19:19.350   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:19:19.350  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 260
09-07 09:19:19.350  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:19:19.350  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 260
09-07 09:19:19.352  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:19:19.356  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:19:19.738   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:20.764   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:19:20.764   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:19:20.764   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 910665166008; DSPS: 29938940; Offset : -3000383433
,09-07 09:19:24.744   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:29.750   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:34.756   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:39.762   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:40.767   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:19:40.767   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:19:40.767   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 930667428092; DSPS: 30594374; Offset : -3000379832
,09-07 09:19:44.768   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:49.774   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:54.780   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:19:59.786   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:00.075  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:20:00.075  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:20:00.075  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:20:00.080  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:20:00.080  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:20:00.081  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:20:00.082  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:20:00.769   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:20:00.769   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:20:00.770   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 950669837567; DSPS: 31249811; Offset : -3000319950
,09-07 09:20:04.792   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:09.799   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:14.805   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:15.771   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:20:15.771   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:20:15.771   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 965672113348; DSPS: 31741406; Offset : -3000333144
,09-07 09:20:19.452   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:20:19.454  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:20:19.455  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:20:19.455  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:20:19.455  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:20:19.460  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:20:19.496  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:20:19.501  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:20:19.501  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:20:19.502  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:20:19.502  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:20:19.502  1803  1989 D LEDHandler: Battery Temp: 260, mChargingStatus=5, mChargingStop=false
09-07 09:20:19.507   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:20:19.507   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:20:19.507   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:20:19.508  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 260
09-07 09:20:19.508  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:20:19.508  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 260
09-07 09:20:19.511  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:20:19.514  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:20:19.811   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:24.817   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:29.823   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:34.830   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:35.774   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:20:35.774   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:20:35.774   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 985674359902; DSPS: 32396842; Offset : -3000405926
,09-07 09:20:37.957  5631  5874 I PlayCommon: [670] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-07 09:20:37.957  5631  5874 I PlayCommon: [670] com.google.android.play.a.l.e(789): No file ready to send
,09-07 09:20:39.836   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:44.842   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:49.848   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:54.855   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:20:55.776   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:20:55.776   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:20:55.776   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1005676560069; DSPS: 33052275; Offset : -3000433567
,09-07 09:20:59.861   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:00.075  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:21:00.075  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:21:00.075  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:21:00.080  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:21:00.080  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:21:00.080  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:21:00.081  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:21:04.867   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:09.873   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:14.879   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:15.778   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:21:15.778   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:21:15.778   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1025678839964; DSPS: 33707708; Offset : -3000383382
,09-07 09:21:19.610  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:21:19.613  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:21:19.614  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:21:19.614  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:21:19.614  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:21:19.614   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:21:19.660  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:21:19.663  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:21:19.663  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:21:19.664  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:21:19.665  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:21:19.665  1803  1989 D LEDHandler: Battery Temp: 259, mChargingStatus=5, mChargingStop=false
09-07 09:21:19.670   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:21:19.670   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:21:19.670   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:21:19.671  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 259
09-07 09:21:19.671  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:21:19.671  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 259
09-07 09:21:19.673  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:21:19.677  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:21:19.885   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:24.899   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:29.904   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:34.911   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:35.781   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:21:35.781   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:21:35.781   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1045681705152; DSPS: 34363166; Offset : -3000506989
,09-07 09:21:39.917   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:44.923   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:48.912   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:21:48.912   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:21:48.912   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1058813166476; DSPS: 34793457; Offset : -3000484875
,09-07 09:21:49.929   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:54.936   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:21:55.192   861  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=754922622, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,09-07 09:21:55.195   861  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{16b3964b type 2 when 1065090 com.android.bluetooth} when 1065090
09-07 09:21:55.330  2009  3427 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
09-07 09:21:55.330  2009  3427 W bt-smp  : Plain text(LSB ~ MSB) = 1a b3 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 09:21:55.330  2009  3427 W bt-smp  : Encrypted text(LSB ~ MSB) = a7 3a 45 c8 6d cf 80 cd fb a1 17 7b 1c 1a d0 43 
09-07 09:21:55.330  2009  3427 W bt-btm  : Stopping oneshot timer
,09-07 09:21:55.408   861   887 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6768 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,09-07 09:21:55.626  6768  6768 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,09-07 09:21:55.648  6768  6768 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@15c4a4f7
,09-07 09:21:55.650   861   861 D PowerManagerServiceEx: releaseWakeLockInternal: lock=754922622 [*alarm*], flags=0x0
09-07 09:21:59.940   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:22:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:22:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:22:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:22:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:22:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:22:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:22:03.915   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:22:03.915   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:22:03.915   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1073815474904; DSPS: 35285049; Offset : -3000373634
,09-07 09:22:04.946   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:09.952   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:14.958   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:18.917   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:22:18.917   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:22:18.917   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1088817410515; DSPS: 35776636; Offset : -3000482753
,09-07 09:22:19.769  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:22:19.769  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:22:19.769  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:22:19.769  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:22:19.774  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:22:19.774   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:22:19.965   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:24.971   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:29.977   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:34.984   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:36.420   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:22:36.420   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:22:36.420   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1106320664466; DSPS: 36350179; Offset : -3000372035
,09-07 09:22:39.990   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:44.996   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:50.002   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:55.008   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:22:56.424   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:22:56.424   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:22:56.424   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1126324581512; DSPS: 37005669; Offset : -3000422144
,09-07 09:23:00.014   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:00.074  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:23:00.074  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:23:00.074  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:23:00.078  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:23:00.078  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:23:00.080  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:23:00.080  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:23:05.020   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:10.026   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:15.033   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:16.426   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:23:16.426   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:23:16.426   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1146326735410; DSPS: 37661098; Offset : -3000374116
,09-07 09:23:19.923  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:23:19.933  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:23:19.933  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:23:19.933  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:23:19.933  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:23:19.935   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:23:20.039   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:25.045   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:30.051   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:35.057   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:36.428   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:23:36.428   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:23:36.428   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1166328870557; DSPS: 38316529; Offset : -3000405690
,09-07 09:23:40.063   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:45.069   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:50.075   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:55.081   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:23:56.432   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:23:56.432   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:23:56.432   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1186332771120; DSPS: 38972012; Offset : -3000258608
,09-07 09:24:00.073  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:24:00.073  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:24:00.073  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:24:00.078  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:24:00.078  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:24:00.079  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:24:00.080  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:24:00.086   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:24:05.092   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:24:10.098   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:24:10.504   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:24:10.504   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:24:10.504   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1200404722622; DSPS: 39433125; Offset : -3000359419
,09-07 09:24:15.104   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:24:20.083  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:24:20.093  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:24:20.093  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:24:20.093  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:24:20.093  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:24:20.095   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:24:20.114   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:24:20.154  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:24:20.162  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:24:20.163  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:24:20.164  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:24:20.164  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:24:20.164  1803  1989 D LEDHandler: Battery Temp: 258, mChargingStatus=5, mChargingStop=false
09-07 09:24:20.167   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:24:20.168   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:24:20.170   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:24:20.173  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:24:20.208  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 258
09-07 09:24:20.208  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:24:20.209  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 258
,09-07 09:24:20.214  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:24:25.120   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:24:25.506   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:24:25.506   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:24:25.506   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1215407015540; DSPS: 39924721; Offset : -3000385785
,09-07 09:24:30.127   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:24:34.586   861   905 I UsageStatsService: User[0] Flushing usage stats to disk
,09-07 09:24:35.133   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:24:40.139   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:24:45.144   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:24:45.509   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:24:45.509   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:24:45.509   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1235409344340; DSPS: 40580158; Offset : -3000406708
,09-07 09:24:50.151   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:24:55.156   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:00.074  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:25:00.074  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:25:00.074  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:25:00.078  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:25:00.078  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:25:00.080  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:25:00.081  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:25:00.167   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:05.173   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:05.511   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:25:05.511   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:25:05.511   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1255411549196; DSPS: 41235590; Offset : -3000399196
,09-07 09:25:10.179   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:15.185   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:20.195   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:20.257  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:25:20.259   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:25:20.260  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:25:20.261  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:25:20.261  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:25:20.261  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:25:20.303  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:25:20.308  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:25:20.308  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:25:20.309  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:25:20.309  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:25:20.309  1803  1989 D LEDHandler: Battery Temp: 258, mChargingStatus=5, mChargingStop=false
09-07 09:25:20.314   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:25:20.314   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:25:20.315   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:25:20.315  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 258
09-07 09:25:20.315  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:25:20.315  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 258
09-07 09:25:20.319  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:25:20.321  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:25:25.201   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:25.513   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:25:25.513   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:25:25.513   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1275413701373; DSPS: 41891021; Offset : -3000413767
,09-07 09:25:30.207   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:32.380  5631  5675 I PlayCommon: [652] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-07 09:25:32.380  5631  5675 I PlayCommon: [652] com.google.android.play.a.l.e(789): No file ready to send
,09-07 09:25:35.213   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:38.058  5631  5874 I PlayCommon: [670] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-07 09:25:38.058  5631  5874 I PlayCommon: [670] com.google.android.play.a.l.e(789): No file ready to send
,09-07 09:25:40.220   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:45.226   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:45.515   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:25:45.515   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:25:45.515   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1295416016182; DSPS: 42546457; Offset : -3000418268
,09-07 09:25:50.232   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:25:55.239   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:00.073  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:26:00.073  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:26:00.073  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:26:00.077  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:26:00.077  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:26:00.078  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:26:00.079  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:26:00.245   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:00.517   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:26:00.517   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:26:00.518   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1310418230917; DSPS: 43038049; Offset : -3000400826
,09-07 09:26:05.251   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:10.257   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:14.590   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:26:14.590   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:26:14.590   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1324489950705; DSPS: 43499154; Offset : -3000488767
,09-07 09:26:15.263   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:20.270   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:20.403  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:26:20.413  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:26:20.413  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:26:20.413  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:26:20.413  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:26:20.415   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:26:20.460  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:26:20.463  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:26:20.463  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:26:20.464  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:26:20.464  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:26:20.464  1803  1989 D LEDHandler: Battery Temp: 257, mChargingStatus=5, mChargingStop=false
09-07 09:26:20.470   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:26:20.470   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:26:20.470   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:26:20.471  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 257
09-07 09:26:20.471  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:26:20.471  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 257
09-07 09:26:20.473  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:26:20.477  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:26:25.275   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:30.282   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:35.287   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:35.845   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:26:35.845   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:26:35.845   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1345745865298; DSPS: 44195670; Offset : -3000557678
,09-07 09:26:40.293   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:45.299   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:50.306   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:26:50.847   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:26:50.847   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:26:50.847   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1360748088938; DSPS: 44687256; Offset : -3000346452
,09-07 09:26:55.312   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:00.073  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:27:00.073  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:27:00.073  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:27:00.077  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:27:00.077  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:27:00.078  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:27:00.079  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:27:00.318   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:05.324   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:05.850   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:27:05.850   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:27:05.850   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1375750529878; DSPS: 45178859; Offset : -3000438237
,09-07 09:27:10.330   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:15.336   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:20.342   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:20.563  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:27:20.572  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:27:20.573  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:27:20.573  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:27:20.573  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:27:20.575   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:27:20.852   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:27:20.852   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:27:20.852   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1390752772560; DSPS: 45670451; Offset : -3000393108
,09-07 09:27:25.348   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:30.355   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:35.361   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:40.367   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:40.854   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:27:40.854   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:27:40.854   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1410755093081; DSPS: 46325887; Offset : -3000391741
,09-07 09:27:45.373   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:50.379   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:27:55.385   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:00.072  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:28:00.072  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:28:00.073  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:28:00.077  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:28:00.077  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:28:00.078  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:28:00.078  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:28:00.392   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:00.856   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:28:00.857   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:28:00.857   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1430757283835; DSPS: 46981318; Offset : -3000367630
,09-07 09:28:05.398   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:10.404   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:15.410   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:15.859   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:28:15.859   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:28:15.859   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1445759361937; DSPS: 47472907; Offset : -3000395293
,09-07 09:28:20.417   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:20.723  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:28:20.733  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:28:20.733  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:28:20.733  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:28:20.733  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:28:20.735   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:28:25.423   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:30.429   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:35.435   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:35.861   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:28:35.861   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:28:35.861   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1465761563634; DSPS: 48128344; Offset : -3000543449
,09-07 09:28:40.441   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:45.447   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:50.453   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:55.459   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:28:58.365   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:28:58.365   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:28:58.365   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1488265381508; DSPS: 48865745; Offset : -3000418333
,09-07 09:29:00.073  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:29:00.074  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:29:00.074  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:29:00.078  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:29:00.078  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:29:00.079  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:29:00.080  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:29:00.466   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:29:05.472   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:29:10.478   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:29:15.484   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:29:18.367   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:29:18.367   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:29:18.367   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1508267538392; DSPS: 49521174; Offset : -3000367006
,09-07 09:29:20.490   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:29:20.883  1803  1803 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:29:20.893  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:29:20.893  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:29:20.893  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:29:20.893  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:29:20.895   479   479 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:29:20.952  2009  3367 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:29:20.956  1839  1839 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:29:20.956  1839  1839 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:29:20.957  1803  1989 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:29:20.957  1803  1989 D LEDHandler: Battery Level Remaining: 100%
09-07 09:29:20.957  1803  1989 D LEDHandler: Battery Temp: 256, mChargingStatus=5, mChargingStop=false
09-07 09:29:20.962   861   861 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:29:20.963   861   861 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:29:20.963   861  1313 D WifiController: battery changed pluggedType: 2
09-07 09:29:20.963  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 256
09-07 09:29:20.964  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:29:20.964  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 256
09-07 09:29:20.966  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:29:20.970  6179  6179 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-07 09:29:25.496   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:29:30.502   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:29:35.508   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:29:38.369   861  1023 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:29:38.369   861  1023 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:29:38.369   861  1023 D sensors_hal_Time: tsOffsetIs: Apps: 1528269610972; DSPS: 50176603; Offset : -3000400060
,09-07 09:29:40.515   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:29:45.521   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:29:50.527   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
,TIME-OUT KILL (timeout was 1400000ms),09-07 09:29:55.532   292   356 I ThermalEngine: Sensor:pa_therm0:26000 mC
09-07 09:29:55.961  6873  6873 D AndroidRuntime: 
09-07 09:29:55.961  6873  6873 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 09:29:55.974  6873  6873 D AndroidRuntime: CheckJNI is OFF
09-07 09:29:56.318  6873  6873 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-07 09:29:56.364   861   907 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
09-07 09:29:56.368   861   907 I ActivityManager: Killing 6418:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
09-07 09:29:56.425   861  1773 I WindowState: WIN DEATH: Window{191a3c26 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 09:29:56.447   861  1773 D InputDispatcher: Focus left window: Window{191a3c26 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 09:29:56.448   861  1773 D InputDispatcher: Window went away: Window{191a3c26 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 09:29:56.466   861  1061 W PackageSettings: Skipping PackageSetting{26f34d55 com.example.hello/10317} due to missing metadata
09-07 09:29:56.495   861   907 I ActivityManager:   Force finishing activity ActivityRecord{1ee21f1c u0 com.test.thalitest/.MainActivity t259}
09-07 09:29:56.525   861   861 V ActivityManager: Display changed displayId=0
09-07 09:29:56.530  1749  1749 D DSDPConnection: Display #0 changed.
09-07 09:29:56.549   861  1060 W ActivityManager: Spurious death for ProcessRecord{2b440828 6418:com.test.thalitest/u0a30}, curProc for 6418: null
09-07 09:29:56.551   861  1061 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
09-07 09:29:56.553   861  1061 I ActivityManager:   Force finishing activity ActivityRecord{1ee21f1c u0 com.test.thalitest/.MainActivity t259 f}
09-07 09:29:56.553   861  1061 W ActivityManager: Duplicate finish request for ActivityRecord{1ee21f1c u0 com.test.thalitest/.MainActivity t259 f}
09-07 09:29:56.635  1946  1946 I art     : Explicit concurrent mark sweep GC freed 3097(271KB) AllocSpace objects, 2(47KB) LOS objects, 39% free, 12MB/20MB, paused 2.246ms total 77.232ms
09-07 09:29:56.646  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-07 09:29:56.657  1732  2496 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 09:29:56.662   861  1288 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 09:29:56.663  1839  1839 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
09-07 09:29:56.664  3473  3473 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-07 09:29:56.665  3473  3473 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-07 09:29:56.665  3473  3473 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-07 09:29:56.665  3473  3473 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
09-07 09:29:56.665  3473  3473 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 09:29:56.665  3473  3473 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 09:29:56.665  3473  3473 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 09:29:56.665  3473  3473 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-07 09:29:56.665  3473  3473 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:29:56.665  3473  3473 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 09:29:56.665  3473  3473 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-07 09:29:56.665  3473  3473 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-07 09:29:56.697  3611  3611 I art     : Explicit concurrent mark sweep GC freed 17468(1081KB) AllocSpace objects, 6(96KB) LOS objects, 25% free, 16MB/21MB, paused 1.100ms total 124.780ms
09-07 09:29:56.712   861   907 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6903 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-07 09:29:56.720  1877  1877 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
09-07 09:29:56.743  1373  1373 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-07 09:29:56.752  1877  1877 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
09-07 09:29:56.808  1373  1516 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 09:29:56.808  1373  1516 D KeyguardModel: createShortcutInfo...
09-07 09:29:56.811  1877  1877 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-07 09:29:56.813  1877  1877 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
09-07 09:29:56.813  1877  1877 I Activity: Activity.onPostResume() called 
09-07 09:29:56.814  1373  1516 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 09:29:56.814  1373  1516 D KeyguardModel: createShortcutInfo...
09-07 09:29:56.817  1373  1516 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:29:56.819  1877  1877 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
09-07 09:29:56.823  1373  1516 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 09:29:56.826  1373  1373 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-07 09:29:56.826  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-07 09:29:56.828  1373  1516 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 09:29:56.828  1373  1516 D KeyguardModel: createShortcutInfo...
09-07 09:29:56.833  1373  1516 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:29:56.833  1373  1516 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 09:29:56.835  1373  1516 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 09:29:56.835  1373  1516 D KeyguardModel: createShortcutInfo...
09-07 09:29:56.838  1877  6921 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
09-07 09:29:56.840  1373  1516 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:29:56.840  1373  1516 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 09:29:56.842   861  1028 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
09-07 09:29:56.843   861  1028 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
09-07 09:29:56.843  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
09-07 09:29:56.843   861  1028 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-07 09:29:56.843   861  1028 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-07 09:29:56.843   861  1028 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-07 09:29:56.843  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
09-07 09:29:56.843  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
09-07 09:29:56.843  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-07 09:29:56.843   861  1028 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@213041d7,  pkg=WindowManager.LayoutParams
09-07 09:29:56.843   861  1028 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-07 09:29:56.844  1373  1516 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 09:29:56.845  1373  1516 D KeyguardModel: createShortcutInfo...
09-07 09:29:56.848   861   889 D InputDispatcher: Focus entered window: Window{2e61cf88 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-07 09:29:56.855  1373  1373 D KeyguardModel: handleShortcutListChanged...
09-07 09:29:56.865  1373  1516 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 09:29:56.865  1373  1516 D KeyguardModel: createShortcutInfo...
09-07 09:29:56.867  6903  6903 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 09:29:56.867  6903  6903 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 09:29:56.869  6903  6903 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 09:29:56.870  1373  1516 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 09:29:56.870  1373  1516 D KeyguardModel: createShortcutInfo...
09-07 09:29:56.872   861   861 I art     : Explicit concurrent mark sweep GC freed 61300(3MB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 3.336ms total 253.423ms
09-07 09:29:56.872  1373  1516 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:29:56.872  1373  1516 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 09:29:56.873   861  1061 I art     : WaitForGcToComplete blocked for 139.864ms for cause Explicit
09-07 09:29:56.880  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 09:29:56.881  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 09:29:56.882  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
09-07 09:29:56.899  1877  1877 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
09-07 09:29:56.900  1877  1877 I PhoneWindow: [setNavigationBarColor] color=0x 0
09-07 09:29:56.908   861  1795 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
09-07 09:29:56.912   861  1795 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6418 uid 10030
09-07 09:29:56.918  1373  1516 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 09:29:56.918  1373  1516 D KeyguardModel: createShortcutInfo...
09-07 09:29:56.920  1373  1516 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:29:56.920  1373  1516 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 09:29:56.921  1373  1516 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 09:29:56.921  1373  1516 D KeyguardModel: createShortcutInfo...
09-07 09:29:56.923  1373  1516 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:29:56.923  1373  1516 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 09:29:56.924  1373  1516 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 09:29:56.924  1373  1516 D KeyguardModel: createShortcutInfo...
09-07 09:29:56.934  1373  1373 D KeyguardModel: handleShortcutListChanged...
09-07 09:29:56.950   861   861 D administrator: Handling package changes for user 0
09-07 09:29:56.990  1877  1877 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
09-07 09:29:56.994  1946  1946 I HotwordDetector: Closing mic
09-07 09:29:56.999  1877  1877 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
09-07 09:29:57.010   861  1032 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{25284703 u0 com.lge.launcher2/.Launcher t258} time:1546911
09-07 09:29:57.010  1877  1877 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@63e443e time:1546911
09-07 09:29:57.017  1946  2346 I HotwordRecognitionRnr: Stopping hotword detection.
09-07 09:29:57.029  1614  1614 E b       : Unable to connect to the editor to retrieve text... will retry later
09-07 09:29:57.076  1877  1877 I art     : Explicit concurrent mark sweep GC freed 3971(212KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.988ms total 65.121ms
09-07 09:29:57.076  1877  1877 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
09-07 09:29:57.215   861  1061 I art     : Explicit concurrent mark sweep GC freed 10409(1005KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.241ms total 330.415ms
09-07 09:29:57.235  6903  6903 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-07 09:29:57.241   861   861 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-07 09:29:57.241   861   861 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 09:29:57.243   861   861 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 09:29:57.247   861  1351 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
09-07 09:29:57.259  6903  6903 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
09-07 09:29:57.316  6873  6873 D AndroidRuntime: Shutting down VM
09-07 09:29:57.346  1785  1785 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-07 09:29:57.346  1785  1785 D LCardEmulationManager: getDefaultRoute
09-07 09:29:57.494  6903  6903 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
09-07 09:29:57.548   861  2205 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6930 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-07 09:29:57.548   861  2205 I ActivityManager: Killing 6104:com.lge.eula/1000 (adj 15): empty #11
09-07 09:29:57.586   861   905 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 09:29:57.643   861  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6949 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-07 09:29:57.643   861  1876 W libprocessgroup: failed to open /acct/uid_1000/pid_6104/cgroup.procs: No such file or directory
09-07 09:29:57.714  6930  6930 I AppUp4:AppBoxCP: onCreate
09-07 09:29:57.722  6930  6930 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-07 09:29:57.740  6930  6930 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-07 09:29:57.741  6930  6930 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-07 09:29:57.741  6930  6930 E AndroidRuntime: FATAL EXCEPTION: main
09-07 09:29:57.741  6930  6930 E AndroidRuntime: Process: com.lge.appbox.client, PID: 6930
09-07 09:29:57.741  6930  6930 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
09-07 09:29:57.741  6930  6930 E AndroidRuntime: 	... 11 more

```
