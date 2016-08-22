#### Test 79763830f325397_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-22 12:03:28.426   298   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-22 12:03:30.019  5602  5602 D AndroidRuntime: 
08-22 12:03:30.019  5602  5602 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 12:03:30.031  5602  5602 D AndroidRuntime: CheckJNI is OFF
08-22 12:03:30.318  5602  5602 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-22 12:03:30.340   962  2185 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-22 12:03:30.402   962  2185 D ActivityManager: setTaskToReturnTo : TaskRecord{2ea258d7 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-22 12:03:30.404   962  2185 D ActivityManager: setTaskToReturnTo : TaskRecord{2ea258d7 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-22 12:03:30.424   962  2185 D WindowStateEx: AppWindowTokenEx init.. 
08-22 12:03:30.442   962  1054 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-22 12:03:30.464   962  1054 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-22 12:03:30.466  1877  1877 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-22 12:03:30.483   962  2185 D InputDispatcher: Focus left window: Window{2262e8d9 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-22 12:03:30.485   962  1054 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-22 12:03:30.485   962  1054 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-22 12:03:30.486  5602  5602 D AndroidRuntime: Shutting down VM
08-22 12:03:30.509   962  1054 D SplitWindow: check instance of lgWin Window{6098bcf u0 Starting com.test.thalitest}
08-22 12:03:30.546   962   980 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5622 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-22 12:03:30.561  1877  1877 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-22 12:03:30.614  1877  1877 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-22 12:03:30.614  1935  1935 I HotwordDetector: Closing mic
08-22 12:03:30.626  1935  2558 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@28b31a83
08-22 12:03:30.627  1935  2558 V AudioRecord: stop()
08-22 12:03:30.627  1935  2558 D AudioRecord: AudioRecord->stop()
08-22 12:03:30.627   286   286 V AudioFlinger: RecordHandle::stop()
08-22 12:03:30.627   286   286 V AudioFlinger: RecordThread::stop
08-22 12:03:30.629   286   286 V AudioFlinger: Record stopped OK
08-22 12:03:30.630   962  1379 I WindowStateAnimator: Starting window displayed
08-22 12:03:30.631   286   286 V AudioPolicyManager: stopInput() input 17
08-22 12:03:30.633   286   286 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-22 12:03:30.634   286   286 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-22 12:03:30.634   286  1066 V AudioPolicyService: AudioCommandThread() waking up
08-22 12:03:30.634   286  1066 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-22 12:03:30.634   286  1066 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
08-22 12:03:30.634   286  1066 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-22 12:03:30.634   286  1066 V AudioFlinger: ThreadBase::setParameters() routing=0
08-22 12:03:30.634   286  1066 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-22 12:03:30.634   286  2579 V AudioFlinger: processConfigEvents_l() remaining events 1
08-22 12:03:30.635   286  2579 V AudioFlinger: processConfigEvents_l() DONE thread 0xb384d000
08-22 12:03:30.637   286  2579 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-22 12:03:30.638   962  1052 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-22 12:03:30.638   962  1052 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-22 12:03:30.642   962  1052 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-22 12:03:30.642   962  1052 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-22 12:03:30.643   962  1052 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-22 12:03:30.646   962  1052 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@21826981,  pkg=WindowManager.LayoutParams
08-22 12:03:30.646   962  1052 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-22 12:03:30.653  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-22 12:03:30.654  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-22 12:03:30.654  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-22 12:03:30.654  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-22 12:03:30.681   286  2579 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-22 12:03:30.681   286  2579 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-22 12:03:30.681   286  2579 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-22 12:03:30.681   286  2579 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-22 12:03:30.684   286  2579 V audio_hw_primary: disable_audio_route: exit
08-22 12:03:30.684   286  2579 E audio_hw_primary: disable_snd_device: enter 144
08-22 12:03:30.684   286  2579 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-22 12:03:30.684   286  2579 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-22 12:03:30.688   286  2579 V audio_hw_primary: stop_input_stream: exit: status(0)
08-22 12:03:30.688   286  2579 V audio_hw_primary: in_standby: exit:  status(0)
08-22 12:03:30.688   286  2579 V AudioFlinger: RecordThread: loop stopping
08-22 12:03:30.688   286  1066 V AudioPolicyService: AudioCommandThread() going to sleep
08-22 12:03:30.688   286   286 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-22 12:03:30.688   286   286 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
08-22 12:03:30.689   286   286 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-22 12:03:30.689   286   286 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-22 12:03:30.689   286  1067 V AudioPolicyService: AudioCommandThread() waking up
08-22 12:03:30.689   286  1067 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-22 12:03:30.689   286  1067 V AudioPolicyService: AudioCommandThread() going to sleep
08-22 12:03:30.690   286   286 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
08-22 12:03:30.690   286   286 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-22 12:03:30.690   286  1066 V AudioPolicyService: AudioCommandThread() waking up
08-22 12:03:30.690   286  1066 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
08-22 12:03:30.690   286  1066 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 286
08-22 12:03:30.690   286  1066 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-22 12:03:30.690   286  1066 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-22 12:03:30.690   286  2579 V AudioFlinger: RecordThread: loop starting
08-22 12:03:30.691   286  2579 V AudioFlinger: processConfigEvents_l() remaining events 1
08-22 12:03:30.691   286  2579 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-22 12:03:30.691   286  2579 V audio_hw_primary: in_set_parameters: exit: status(0)
08-22 12:03:30.691   286  2579 V AudioFlinger: processConfigEvents_l() DONE thread 0xb384d000
08-22 12:03:30.691   286  2579 V AudioFlinger: RecordThread: loop stopping
08-22 12:03:30.691   286  1066 V AudioPolicyService: AudioCommandThread() going to sleep
08-22 12:03:30.694  1935  2558 V AudioRecord: stop()
,08-22 12:03:30.697  1935  2558 V AudioRecord: stop()
08-22 12:03:30.697  1935  2558 V AudioRecord: stop()
08-22 12:03:30.701   286  1300 V AudioFlinger: RecordHandle::stop()
08-22 12:03:30.701   286  1300 V AudioFlinger: RecordThread::stop
08-22 12:03:30.701   286  1300 V AudioPolicyManager: releaseInput() 17
08-22 12:03:30.701   286  1300 V AudioPolicyManager: closeInput(17)
08-22 12:03:30.701   286  1300 V AudioFlinger: closeInput() 17
08-22 12:03:30.701   286  1300 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-22 12:03:30.701   962   981 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-22 12:03:30.701   286  1300 V AudioFlinger: ThreadBase::exit
08-22 12:03:30.701   286  2579 V AudioFlinger: RecordThread: loop starting
08-22 12:03:30.702   286  2579 V AudioFlinger: RecordThread 0xb384d000 exiting
08-22 12:03:30.702  1372  2388 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-22 12:03:30.702  3075  3090 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-22 12:03:30.702   286  1300 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dd40)
08-22 12:03:30.702   286  1300 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-22 12:03:30.702   286  1300 V audio_hw_primary: in_standby: exit:  status(0)
08-22 12:03:30.702   286  1300 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-22 12:03:30.702  1750  2630 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-22 12:03:30.702  1935  1957 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-22 12:03:30.702   286  1300 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-22 12:03:30.703   286  1300 V AudioPolicyManager: releaseInput() exit
08-22 12:03:30.703   286  1067 V AudioPolicyService: AudioCommandThread() waking up
08-22 12:03:30.703   286  1067 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-22 12:03:30.703   286  1300 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-22 12:03:30.703   286  1300 V AudioFlinger: removeClient_l() pid 1935, calling pid 286
08-22 12:03:30.703   286  1067 V AudioPolicyService: AudioCommandThread() going to sleep
08-22 12:03:30.703  2077  2096 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-22 12:03:30.703   286  1364 V AudioFlinger: releasing 16 from 1935 for -1
08-22 12:03:30.704   286  1364 V AudioFlinger:  decremented refcount to 0
08-22 12:03:30.704   286  1364 V AudioFlinger: purging stale effects
08-22 12:03:30.755  1935  2566 I HotwordRecognitionRnr: Stopping hotword detection.
08-22 12:03:30.755  1935  2574 I HotwordRecognitionRnr: Hotword detection finished
08-22 12:03:30.780  5622  5622 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-22 12:03:30.906  5622  5622 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-22 12:03:30.976  5622  5622 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 5916-5926)
08-22 12:03:30.976  5622  5622 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 12:03:31.021  5622  5622 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7581668}
08-22 12:03:31.023  5622  5622 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 12:03:31.027  5622  5622 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 12:03:31.043  5622  5622 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-22 12:03:31.046  5622  5622 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 12:03:31.051  5622  5622 E SysUtils: ApplicationContext is null in ApplicationStatus
08-22 12:03:31.120  5622  5661 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-22 12:03:31.148  5622  5622 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-22 12:03:31.157  5622  5622 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 12:03:31.157  5622  5622 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 12:03:31.162  5622  5622 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-22 12:03:31.162  5622  5622 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-22 12:03:31.162  5622  5622 I Adreno-EGL: Build Date: 03/02/15 Mon
08-22 12:03:31.162  5622  5622 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-22 12:03:31.162  5622  5622 I Adreno-EGL: Remote Branch: 
08-22 12:03:31.162  5622  5622 I Adreno-EGL: Local Patches: 
08-22 12:03:31.162  5622  5622 I Adreno-EGL: Reconstruct Branch: 
08-22 12:03:31.287   286  1300 V AudioPolicyService: registerClient() client 0xb551ca80, uid 10030
08-22 12:03:31.319   962  1053 D BluetoothManagerService: Message: 20
08-22 12:03:31.321   962  1053 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@49a4de:true
08-22 12:03:31.324  5622  5672 D BluetoothAdapter: 593309117: getState() :  mService = null. Returning STATE_OFF
08-22 12:03:31.453  5622  5622 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:31.464  5622  5622 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-22 12:03:31.471  5622  5622 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-22 12:03:31.475  5622  5622 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-22 12:03:31.475  5622  5622 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-22 12:03:31.488  5622  5622 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-22 12:03:31.497  5622  5622 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 12:03:31.497  5622  5622 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 12:03:31.552  5622  5622 I Activity: Activity.onPostResume() called 
,08-22 12:03:31.558  5622  5683 D OpenGLRenderer: Render dirty regions requested: true
08-22 12:03:31.558  5622  5683 I OpenGLRenderer: Initialized EGL, version 1.4
08-22 12:03:31.564  5622  5683 D OpenGLRenderer: Enabling debug mode 0
,08-22 12:03:31.576  5622  5622 D Atlas   : Validating map...
,08-22 12:03:31.581   962  1829 D SplitWindow: check instance of lgWin Window{3417018e u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-22 12:03:31.590  5622  5670 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-22 12:03:31.628   962  2669 D InputDispatcher: Focus entered window: Window{3417018e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-22 12:03:31.697   962  1819 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-22 12:03:31.707  5622  5622 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29b3af3 time:116658
08-22 12:03:31.713   962  1054 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s211ms
08-22 12:03:31.713   962  1054 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f7b85c4 u0 com.test.thalitest/.MainActivity t259} time:116664
,08-22 12:03:31.842  5622  5622 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5622
,08-22 12:03:32.047  5622  5622 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 12:03:32.380  5622  5686 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426119424
,08-22 12:03:32.399  5622  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 12:03:32.399  5622  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 12:03:32.399  5622  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 12:03:32.399  5622  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 12:03:32.399  5622  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-22 12:03:32.400  5622  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@287dc974 added. We now have 1 listener(s)
,08-22 12:03:32.409   962  1819 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 12:03:32.411  5622  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-22 12:03:32.413  5622  5686 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
,08-22 12:03:32.414  5622  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 12:03:32.415  5622  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-22 12:03:32.421  5622  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@588c6e3 added. We now have 1 listener(s)
08-22 12:03:32.422  5622  5686 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 12:03:32.437  5622  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 12:03:32.437  5622  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-22 12:03:32.441  5622  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-22 12:03:32.441  5622  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 12:03:32.441  5622  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-22 12:03:32.444  5622  5686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 12:03:32.444   962  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 12:03:32.444  5622  5686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-22 12:03:32.458  5622  5686 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:32.458  5622  5686 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:03:32.458  5622  5686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:03:32.458  5622  5686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 12:03:32.458  5622  5686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:03:32.458  5622  5686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:03:32.458  5622  5686 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:03:32.458  5622  5686 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:03:32.458  5622  5686 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 12:03:32.458  5622  5686 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-22 12:03:32.459  5622  5686 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 12:03:32.460  5622  5686 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 12:03:32.639  5622  5622 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 12:03:32.657  5622  5636 I art     : CheckpointMarkThreadRoots callback created = 0xb064e310
,08-22 12:03:32.691  5622  5636 I art     : CheckpointMarkThreadRoots callback created = 0xb064e2e0
,08-22 12:03:32.974  2077  2077 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19951
,08-22 12:03:33.316  5622  5701 W jxcore-log: Initializing JXcore engine
08-22 12:03:33.316  5622  5701 W jxcore-log: JXcore engine is ready
,08-22 12:03:33.404  5701  5701 W Thread-650: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7325]" dev="sockfs" ino=7325 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-22 12:03:33.414  5701  5701 W Thread-650: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-22 12:03:33.414  5701  5701 W Thread-650: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7473]" dev="sockfs" ino=7473 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-22 12:03:33.414  5701  5701 W Thread-650: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-22 12:03:33.414  5701  5701 W Thread-650: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,08-22 12:03:33.414  5701  5701 W Thread-650: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26161]" dev="sockfs" ino=26161 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-22 12:03:33.430   298   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
08-22 12:03:33.438  5622  5701 W jxcore-log: Starting JXcore engine
08-22 12:03:33.571  5622  5701 W jxcore-log: Platform android
08-22 12:03:33.571  5622  5701 W jxcore-log: 
,08-22 12:03:33.571  5622  5701 W jxcore-log: Process ARCH arm
08-22 12:03:33.571  5622  5701 W jxcore-log: 
08-22 12:03:33.841  5622  5701 I jxcore-log: JXcore Cordova bridge is ready!
08-22 12:03:33.841  5622  5701 I jxcore-log: 
08-22 12:03:33.841  5622  5701 W jxcore-log: JXcore engine is started
,08-22 12:03:33.847  5622  5686 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-22 12:03:33.849  5622  5622 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-22 12:03:38.435   298   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-22 12:03:40.712   962  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{b64faf9 type 2 when 120000 com.google.android.gms} when 120000
,08-22 12:03:40.714   962  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{340cea3e type 2 when 121019 com.google.android.gms} when 121019
,08-22 12:03:41.036   962  1285 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-22 12:03:41.038   962  1317 D ConnectivityService: dumpNetworkRequest
,08-22 12:03:41.125  3922  5736 W DriveInitializer: Background init thread started
,08-22 12:03:41.151   244   310 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-22 12:03:41.152   244   310 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
08-22 12:03:41.152   244   310 W Vold    : Returning OperationFailed - no handler for errno 0
08-22 12:03:41.152  3922  5736 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,08-22 12:03:41.199   962  1635 I ActivityManager: Process com.google.android.apps.docs (pid 5351) has died
,08-22 12:03:41.248  3922  5736 W DriveInitializer: Background init thread ended
,08-22 12:03:42.150  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,08-22 12:03:42.151  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-22 12:03:42.151  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-22 12:03:42.151  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
08-22 12:03:42.160  1802  1802 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-22 12:03:42.194  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 320
08-22 12:03:42.194  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-22 12:03:42.194  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 320
08-22 12:03:42.196  1802  1958 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
,08-22 12:03:42.196  1802  1958 D LEDHandler: Battery Level Remaining: 100%
08-22 12:03:42.196  1802  1958 D LEDHandler: Battery Temp: 320, mChargingStatus=5, mChargingStop=false
08-22 12:03:42.197  1838  1838 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-22 12:03:42.199  1838  1838 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-22 12:03:42.202  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-22 12:03:42.205   962  1316 D WifiController: battery changed pluggedType: 2
08-22 12:03:42.206  5451  5451 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-22 12:03:42.218   479   479 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-22 12:03:43.440   298   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-22 12:03:47.682   962   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-22 12:03:47.682   962   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-22 12:03:47.682   962   998 D sensors_hal_Time: tsOffsetIs: Apps: 132632697091; DSPS: 4444809; Offset : -3020242828
,08-22 12:03:48.445   298   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-22 12:03:49.358  5622  5701 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 12:03:49.358  5622  5701 I jxcore-log: 
,08-22 12:03:49.361  5622  5701 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 12:03:49.361  5622  5701 I jxcore-log: 
08-22 12:03:49.365  5622  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:49.365  5622  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:03:49.365  5622  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:03:49.365  5622  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 12:03:49.365  5622  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:03:49.365  5622  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:03:49.365  5622  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:03:49.365  5622  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:03:49.365  5622  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 12:03:49.366  5622  5701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:49.366  5622  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 12:03:49.369  5622  5701 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 12:03:49.369  5622  5701 I jxcore-log: 
,08-22 12:03:49.372  5622  5701 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 12:03:49.372  5622  5701 I jxcore-log: 
08-22 12:03:50.163  5622  5701 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-22 12:03:50.163  5622  5701 I jxcore-log: Failed to execute UT.
08-22 12:03:50.163  5622  5701 I jxcore-log: 
,08-22 12:03:50.163  5622  5701 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-22 12:03:50.163  5622  5701 I jxcore-log: 
08-22 12:03:50.173  5622  5701 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 12:03:50.173  5622  5701 I jxcore-log: 
08-22 12:03:50.184  5622  5622 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-22 12:03:50.541  5749  5749 D AndroidRuntime: 
08-22 12:03:50.541  5749  5749 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-22 12:03:50.549  5749  5749 D AndroidRuntime: CheckJNI is OFF
08-22 12:03:50.848  5749  5749 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-22 12:03:50.899   962  1034 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-22 12:03:50.903   962  1034 I ActivityManager: Killing 5622:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
,08-22 12:03:50.952   962  2185 I WindowState: WIN DEATH: Window{3417018e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-22 12:03:50.967   962  2185 D InputDispatcher: Focus left window: Window{3417018e u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-22 12:03:50.967   962  2185 D InputDispatcher: Window went away: Window{3417018e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-22 12:03:51.013   962  1034 W ActivityManager: Force removing ActivityRecord{1f7b85c4 u0 com.test.thalitest/.MainActivity t259}: app died, no saved state
08-22 12:03:51.013   962  1061 W PackageSettings: Skipping PackageSetting{18943942 com.example.hello/10317} due to missing metadata
,08-22 12:03:51.066   962   981 W ActivityManager: Spurious death for ProcessRecord{2d18333 5622:com.test.thalitest/u0a30}, curProc for 5622: null
,08-22 12:03:51.068   962  1061 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-22 12:03:51.135  1935  1935 I art     : Explicit concurrent mark sweep GC freed 1725(109KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 1.807ms total 57.950ms
,08-22 12:03:51.172  1877  1877 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-22 12:03:51.176  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-22 12:03:51.177  1838  1838 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-22 12:03:51.180  1732  2414 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-22 12:03:51.182  3361  3361 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-22 12:03:51.188   962  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-22 12:03:51.188  3361  3361 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,08-22 12:03:51.191  3361  3361 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-22 12:03:51.191  3361  3361 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-22 12:03:51.191  3361  3361 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 12:03:51.191  3361  3361 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 12:03:51.191  3361  3361 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-22 12:03:51.191  3361  3361 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-22 12:03:51.191  3361  3361 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:51.191  3361  3361 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:51.191  3361  3361 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-22 12:03:51.191  3361  3361 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-22 12:03:51.208  1877  1877 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-22 12:03:51.229   962  1034 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5773 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-22 12:03:51.239  3922  3922 I art     : Explicit concurrent mark sweep GC freed 5243(318KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 1.227ms total 155.012ms
08-22 12:03:51.278  1877  1877 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-22 12:03:51.281  1877  1877 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-22 12:03:51.281  1877  1877 I Activity: Activity.onPostResume() called 
08-22 12:03:51.282  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-22 12:03:51.283   962  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-22 12:03:51.283   962  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-22 12:03:51.284   962  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-22 12:03:51.284   962  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-22 12:03:51.285   282  1044 E BandwidthController: [LG DATA] No such appUid: 1000
08-22 12:03:51.285   282  1044 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
08-22 12:03:51.290   282  5786 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
08-22 12:03:51.291   282  5786 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-22 12:03:51.291   282  5786 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
,08-22 12:03:51.299   962  1051 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-22 12:03:51.339   962  1052 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-22 12:03:51.341  1877  5794 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-22 12:03:51.344   962  1052 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,08-22 12:03:51.377   962  1052 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-22 12:03:51.377   962  1052 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-22 12:03:51.377   962  1052 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-22 12:03:51.377   962  1052 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@21826981,  pkg=WindowManager.LayoutParams
08-22 12:03:51.377   962  1052 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,08-22 12:03:51.383   962  2669 D InputDispatcher: Focus entered window: Window{2262e8d9 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-22 12:03:51.406  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-22 12:03:51.408  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-22 12:03:51.408   962   962 I art     : Explicit concurrent mark sweep GC freed 43136(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 31.185ms total 267.800ms
08-22 12:03:51.412  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-22 12:03:51.412   962  1061 I art     : WaitForGcToComplete blocked for 177.468ms for cause Explicit
08-22 12:03:51.421  1877  1877 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,08-22 12:03:51.434  1877  1877 I PhoneWindow: [setNavigationBarColor] color=0x 0
,08-22 12:03:51.436  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-22 12:03:51.436  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-22 12:03:51.441  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-22 12:03:51.441  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-22 12:03:51.441  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-22 12:03:51.441  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-22 12:03:51.448  5773  5773 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 12:03:51.449  5773  5773 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-22 12:03:51.453  5773  5773 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-22 12:03:51.486   962  1379 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5797 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,08-22 12:03:51.509   962   962 D administrator: Handling package changes for user 0
,08-22 12:03:51.572   962  1871 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-22 12:03:51.574   962  1871 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5622 uid 10030
,08-22 12:03:51.578  5797  5797 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-22 12:03:51.637  1877  1877 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1634c896 time:136588
,08-22 12:03:51.644  1372  1505 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-22 12:03:51.644  1372  1505 D KeyguardModel: createShortcutInfo...
08-22 12:03:51.648  1372  1505 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-22 12:03:51.648  1372  1505 D KeyguardModel: createShortcutInfo...
08-22 12:03:51.650  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-22 12:03:51.650  1372  1505 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-22 12:03:51.652  1372  1505 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-22 12:03:51.652  1372  1505 D KeyguardModel: createShortcutInfo...
08-22 12:03:51.654  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 12:03:51.654  1372  1505 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-22 12:03:51.656  1372  1505 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-22 12:03:51.656  1372  1505 D KeyguardModel: createShortcutInfo...
08-22 12:03:51.658  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 12:03:51.658  1372  1505 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-22 12:03:51.663  1372  1505 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-22 12:03:51.663  1372  1505 D KeyguardModel: createShortcutInfo...
08-22 12:03:51.665  1935  5814 I HotwordRecognitionRnr: Starting hotword detection.
08-22 12:03:51.668  1372  1372 D KeyguardModel: handleShortcutListChanged...
08-22 12:03:51.670  1935  5815 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@1766bc1
,08-22 12:03:51.673  1372  1505 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-22 12:03:51.673  1372  1505 D KeyguardModel: createShortcutInfo...
08-22 12:03:51.674  1935  5815 V AudioRecord: set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
08-22 12:03:51.675  1935  5815 V AudioRecord: set(): mSessionId 22
08-22 12:03:51.677  1372  1505 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-22 12:03:51.677  1372  1505 D KeyguardModel: createShortcutInfo...
08-22 12:03:51.680  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 12:03:51.681  1372  1505 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-22 12:03:51.681   286  1300 V AudioPolicyManager: getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
08-22 12:03:51.681   286  1300 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
08-22 12:03:51.681   286  1300 V AudioPolicyManager: isPlaybackThread 0,isRecordThread 1
08-22 12:03:51.681   286  1300 D audio_hw_primary: adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546dd40)
08-22 12:03:51.681   286  1300 V audio_hw_primary: adev_open_input_stream: exit
08-22 12:03:51.681   286  1300 V AudioFlinger: openInput_l() openInputStream returned input 0xb546dd40, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
,08-22 12:03:51.682  1372  1505 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-22 12:03:51.683  1372  1505 D KeyguardModel: createShortcutInfo...
08-22 12:03:51.684  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 12:03:51.684   286  1300 V AudioFlinger: openInput_l() created record thread: ID 23 thread 0xb384d000
08-22 12:03:51.684   286  1300 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
08-22 12:03:51.684   286  5817 I AudioFlinger: AudioFlinger's thread 0xb384d000 ready to run
08-22 12:03:51.684   286  5817 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-22 12:03:51.684   286  5817 V audio_hw_primary: in_standby: exit:  status(0)
08-22 12:03:51.684  1372  1505 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-22 12:03:51.684   962  1829 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
08-22 12:03:51.685   286  1300 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-22 12:03:51.685  3075  3091 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
08-22 12:03:51.685  2077  2096 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
08-22 12:03:51.685   286  5817 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-22 12:03:51.685   286  5817 V audio_hw_primary: in_standby: exit:  status(0)
08-22 12:03:51.685   286  5817 V AudioFlinger: RecordThread: loop stopping
08-22 12:03:51.686  1372  1401 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
08-22 12:03:51.686   286  1300 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-22 12:03:51.686   286  1067 V AudioPolicyService: AudioCommandThread() waking up
08-22 12:03:51.686   286  1067 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-22 12:03:51.686   286  1067 V AudioPolicyService: AudioCommandThread() going to sleep
08-22 12:03:51.686  1750  1766 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
08-22 12:03:51.687  1935  1957 V AudioSystem: ioConfigChanged() event 3, ioHandle 23
08-22 12:03:51.687  1372  1505 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-22 12:03:51.687  1372  1505 D KeyguardModel: createShortcutInfo...
08-22 12:03:51.687   286  1364 V AudioFlinger: openRecord() lSessionId: 22 input 23
08-22 12:03:51.688   286  1364 V AudioFlinger: getOrphanEffectChain_l session 22 index -2
08-22 12:03:51.689  1372  1505 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-22 12:03:51.689  1372  1505 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-22 12:03:51.690   286  1364 V AudioFlinger: acquiring 22 from 1935, for -1
08-22 12:03:51.690   286  1364 V AudioFlinger:  added new entry for 22
08-22 12:03:51.692  1372  1505 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-22 12:03:51.692  1372  1505 D KeyguardModel: createShortcutInfo...
,08-22 12:03:51.694  1935  5815 V AudioRecord: start, sync event 0 trigger session 0
08-22 12:03:51.695  1935  5815 V AudioRecord: mAudioRecord->start()
08-22 12:03:51.695   286   286 V AudioFlinger: RecordHandle::start()
08-22 12:03:51.695   286   286 V AudioFlinger: RecordThread::start event 0, triggerSession 0
08-22 12:03:51.695   286   286 V AudioPolicyManager: startInput() module primary->input primary(23)
08-22 12:03:51.695   286   286 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
08-22 12:03:51.695   286   286 V AudioPolicyManager: getNewInputDevice() selected device 80000004
08-22 12:03:51.695   286   286 V AudioPolicyManager: DeviceVector::refreshTypes() mDeviceTypes 80000004
08-22 12:03:51.695   286   286 V AudioPolicyManager: DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
08-22 12:03:51.695   286   286 V AudioPolicyService: AudioCommandThread() adding create patch delay 0
08-22 12:03:51.695   286   286 V AudioPolicyService: inserting command: 7 at index 0, num commands 0
08-22 12:03:51.695   286  1066 V AudioPolicyService: AudioCommandThread() waking up
08-22 12:03:51.695   286  1066 V AudioPolicyService: AudioCommandThread() processing create audio patch
08-22 12:03:51.695   286  1066 V AudioFlinger::PatchPanel: createAudioPatch() num_sources 1 num_sinks 1 handle 0
08-22 12:03:51.696   286  1066 V AudioFlinger::PatchPanel: createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
08-22 12:03:51.696   286  1066 V AudioFlinger: ThreadBase::setParameters() input_source=6;routing=-2147483644
08-22 12:03:51.696   286  1066 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-22 12:03:51.696   286  5817 V AudioFlinger: RecordThread: loop starting
08-22 12:03:51.696   286  5817 V AudioFlinger: processConfigEvents_l() remaining events 1
08-22 12:03:51.697   286  5817 D audio_hw_primary: in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
08-22 12:03:51.697   286  5817 V audio_hw_primary: in_set_parameters: exit: status(0)
08-22 12:03:51.697   286  5817 V AudioFlinger: processConfigEvents_l() DONE thread 0xb384d000
08-22 12:03:51.697   286  1066 V AudioFlinger::PatchPanel: createAudioPatch() status 0
08-22 12:03:51.697   286  1066 V AudioFlinger::PatchPanel: createAudioPatch() added new patch handle 24 halHandle 0
08-22 12:03:51.697   286  1066 V AudioPolicyService: AudioCommandThread() going to sleep
08-22 12:03:51.697   286   286 V AudioPolicyManager: setInputDevice() createAudioPatch returned 0 patchHandle 24
08-22 12:03:51.698   962   962 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-22 12:03:51.698   286   286 V AudioPolicyManager: addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
08-22 12:03:51.698   286   286 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-22 12:03:51.698   286   286 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-22 12:03:51.698   286  1067 V AudioPolicyService: AudioCommandThread() waking up
08-22 12:03:51.698   286  1067 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-22 12:03:51.698   286   286 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
08-22 12:03:51.698   286   286 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-22 12:03:51.698   286  1066 V AudioPolicyService: AudioCommandThread() waking up
08-22 12:03:51.699   286  1066 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=1, io 23
08-22 12:03:51.699   286  1067 V AudioPolicyService: AudioCommandThread() going to sleep
08-22 12:03:51.699   286  1066 V AudioFlinger: setParameters(): io 23, keyvalue hotword_active=1, calling pid 286
08-22 12:03:51.699   286  1066 V AudioFlinger: ThreadBase::setParameters() hotword_active=1
08-22 12:03:51.699   286  1066 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-22 12:03:51.700   962   962 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-22 12:03:51.703   962   962 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-22 12:03:51.707   286  5817 V AudioFlinger: processConfigEvents_l() remaining events 1
08-22 12:03:51.707   286  5817 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=1
08-22 12:03:51.707   286  5817 V audio_hw_primary: in_set_parameters: exit: status(0)
08-22 12:03:51.707   286  5817 V AudioFlinger: processConfigEvents_l() DONE thread 0xb384d000
08-22 12:03:51.708   286  1066 V AudioPolicyService: AudioCommandThread() going to sleep
08-22 12:03:51.708   286   286 V AudioPolicyManager: AudioPolicyManager::startInput() input source = 1999
08-22 12:03:51.711  1372  1372 D KeyguardModel: handleShortcutListChanged...
08-22 12:03:51.716   962  1350 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-22 12:03:51.720   286  5817 V msm8974_platform: platform_update_usecase_from_source: input source :6
08-22 12:03:51.720   286  5817 D audio_hw_primary: start_input_stream: enter: stream(0xb546dd40)usecase(7: audio-record)
08-22 12:03:51.720   286  5817 V voice   : voice_check_and_set_incall_rec_usecase: voice call not active
08-22 12:03:51.720   286  5817 V audio_hw_primary: start_input_stream: usecase(7)
08-22 12:03:51.720   286  5817 E audio_hw_primary: select_devices: enter and usecase(7)
08-22 12:03:51.720   286  5817 V msm8974_platform: platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
08-22 12:03:51.720   286  5817 V msm8974_platform: platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
08-22 12:03:51.720   286  5817 V msm8974_platform_lge: LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
08-22 12:03:51.720   286  5817 V audio_hw_lge_primary: LGE_exeption_scenario: enter and out: 0, in: 144
08-22 12:03:51.720   286  5817 D audio_hw_primary: select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
08-22 12:03:51.720   286  5817 E audio_hw_primary: enable_snd_device: enter  144
08-22 12:03:51.720   286  5817 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-22 12:03:51.720   286  5817 V audio_hw_primary: enable_snd_device: snd_device(144: lg-vr-handset-mic)
08-22 12:03:51.720   286  5817 V msm8974_platform_lge: LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
08-22 12:03:51.721   286  5817 D ACDB-LOADER: ACDB -> send_audio_cal, acdb_id = 65, path =  1
08-22 12:03:51.721   286  5817 D ACDB-LOADER: ACDB -> send_adm_topology
08-22 12:03:51.721   286  5817 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
08-22 12:03:51.721  1935  5815 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@1766bc1
,08-22 12:03:51.724   286  5817 D ACDB-LOADER: ACDB -> send_asm_topology
08-22 12:03:51.724   286  5817 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
08-22 12:03:51.724   286  5817 D ACDB-LOADER: ACDB -> send_audtable
08-22 12:03:51.724   286  5817 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
08-22 12:03:51.724   286  5817 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_CAL
08-22 12:03:51.724   286  5817 D ACDB-LOADER: ACDB -> send_audvoltable
08-22 12:03:51.724   286  5817 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
08-22 12:03:51.724   286  5817 D         : Failed to fetch the lookup information of the device 00000041 
08-22 12:03:51.724   286  5817 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
08-22 12:03:51.724   286  5817 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
08-22 12:03:51.724   286  5817 D ACDB-LOADER: ACDB -> AUDIO_SET_AFE_CAL
08-22 12:03:51.730   286  5817 V audio_hw_primary: enable_audio_route: enter: usecase(7)
08-22 12:03:51.730   286  5817 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-22 12:03:51.730   286  5817 V audio_hw_primary: enable_audio_route: apply mixer and update path: audio-record
08-22 12:03:51.730   286  5817 V audio_hw_primary: enable_audio_route: exit
08-22 12:03:51.730   286  5817 D audio_hw_primary: select_devices: done
08-22 12:03:51.730   286  5817 V audio_hw_primary: start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
08-22 12:03:51.735   286  5817 V audio_hw_primary: start_input_stream: exit
08-22 12:03:51.743  1877  1877 I art     : Explicit concurrent mark sweep GC freed 4094(248KB) AllocSpace objects, 5(681KB) LOS objects, 39% free, 15MB/25MB, paused 3.536ms total 104.157ms
08-22 12:03:51.772   962  1061 I art     : Explicit concurrent mark sweep GC freed 13330(1346KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.926ms total 358.334ms
,08-22 12:03:51.841  1935  1935 I HotwordWorker: onReady
,08-22 12:03:51.845  5773  5773 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-22 12:03:51.864  5773  5773 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-22 12:03:51.894   962  1054 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{df48e5c u0 com.lge.launcher2/.Launcher t258} time:136845
,08-22 12:03:51.913  1785  1785 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-22 12:03:51.914  1785  1785 D LCardEmulationManager: getDefaultRoute
,08-22 12:03:51.916  5749  5749 D AndroidRuntime: Shutting down VM
08-22 12:03:51.963   962  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5820 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-22 12:03:51.985   962  1033 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 12:03:52.053   962  2185 I ActivityManager: Killing 5326:com.lge.eula/1000 (adj 15): empty #11
,08-22 12:03:52.080   962  1784 W libprocessgroup: failed to open /acct/uid_1000/pid_5326/cgroup.procs: No such file or directory
,08-22 12:03:52.120   962  1033 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-22 12:03:52.131  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-22 12:03:52.131  5773  5773 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-22 12:03:52.177   962  1829 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5841 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-22 12:03:52.178   962  1829 I ActivityManager: Killing 5425:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,08-22 12:03:52.210   962  1941 W libprocessgroup: failed to open /acct/uid_10086/pid_5425/cgroup.procs: No such file or directory
,08-22 12:03:52.309  5841  5841 I AppUp4:AppBoxCP: onCreate
08-22 12:03:52.310  5841  5841 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-22 12:03:52.320  5841  5841 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-22 12:03:52.320  5841  5841 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-22 12:03:52.321  5841  5841 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-22 12:03:52.323  5841  5841 E AndroidRuntime: FATAL EXCEPTION: main
08-22 12:03:52.323  5841  5841 E AndroidRuntime: Process: com.lge.appbox.client, PID: 5841
08-22 12:03:52.323  5841  5841 E AndroidRuntime: j,ava.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-22 12:03:52.323  5841  5841 E AndroidRuntime: 	... 11 more

```
