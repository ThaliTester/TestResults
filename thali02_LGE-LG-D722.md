#### Test 83084099807e426_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-31 16:50:45.344   959   997 D sensors_hal_Time: tsOffsetIs: Apps: 114251895270; DSPS: 3842363; Offset : -3014819171
,08-31 16:50:49.364  5823  5823 D AndroidRuntime: 
08-31 16:50:49.364  5823  5823 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 16:50:49.367  5823  5823 D AndroidRuntime: CheckJNI is OFF
08-31 16:50:49.437   302   362 I ThermalEngine: Sensor:pa_therm0:33000 mC
08-31 16:50:49.617  5823  5823 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 16:50:49.639   959  1823 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 16:50:49.695   959  1823 D ActivityManager: setTaskToReturnTo : TaskRecord{255857e3 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 16:50:49.697   959  1823 D ActivityManager: setTaskToReturnTo : TaskRecord{255857e3 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 16:50:49.713   959  1823 D WindowStateEx: AppWindowTokenEx init.. 
08-31 16:50:49.724   959  1059 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-31 16:50:49.747   959  1059 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-31 16:50:49.748   959  1823 D InputDispatcher: Focus left window: Window{25e2c55 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-31 16:50:49.750  5823  5823 D AndroidRuntime: Shutting down VM
08-31 16:50:49.752  1880  1880 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-31 16:50:49.764   959  1059 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 16:50:49.764   959  1059 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-31 16:50:49.784   959  1059 D SplitWindow: check instance of lgWin Window{3e06e05b u0 Starting com.test.thalitest}
08-31 16:50:49.829   959  1879 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5843 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 16:50:49.837  1880  1880 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-31 16:50:49.858   310   310 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 329us total 30.928ms
08-31 16:50:49.879  1967  1967 I HotwordDetector: Closing mic
08-31 16:50:49.886  1967  2458 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2eabe466
08-31 16:50:49.886  1967  2458 V AudioRecord: stop()
08-31 16:50:49.886  1967  2458 D AudioRecord: AudioRecord->stop()
08-31 16:50:49.888   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 29.629ms
08-31 16:50:49.888   291   291 V AudioFlinger: RecordHandle::stop()
08-31 16:50:49.888   291   291 V AudioFlinger: RecordThread::stop
08-31 16:50:49.901   291   291 V AudioFlinger: Record stopped OK
08-31 16:50:49.903   291   291 V AudioPolicyManager: stopInput() input 17
08-31 16:50:49.904   291   291 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-31 16:50:49.904   291   291 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-31 16:50:49.907   291  1065 V AudioPolicyService: AudioCommandThread() waking up
08-31 16:50:49.907   291  1065 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-31 16:50:49.907   291  1065 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
08-31 16:50:49.908   291  1065 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-31 16:50:49.908   291  1065 V AudioFlinger: ThreadBase::setParameters() routing=0
08-31 16:50:49.910   291  2534 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
08-31 16:50:49.912   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 23.997ms
08-31 16:50:49.956   291  2534 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-31 16:50:49.956   291  2534 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-31 16:50:49.956   291  2534 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-31 16:50:49.956   291  2534 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-31 16:50:49.958   291  2534 V audio_hw_primary: disable_audio_route: exit
08-31 16:50:49.958   291  2534 E audio_hw_primary: disable_snd_device: enter 144
08-31 16:50:49.958   291  2534 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-31 16:50:49.958   291  2534 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-31 16:50:49.962  1880  1880 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,08-31 16:50:49.963   291  2534 V audio_hw_primary: stop_input_stream: exit: status(0)
08-31 16:50:49.963   291  2534 V audio_hw_primary: in_standby: exit:  status(0)
08-31 16:50:49.963   291  2534 V AudioFlinger: RecordThread: loop stopping
08-31 16:50:49.964   291  1065 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-31 16:50:49.965   291  2534 V AudioFlinger: RecordThread: loop starting
08-31 16:50:49.965   291  2534 V AudioFlinger: processConfigEvents_l() remaining events 1
08-31 16:50:49.966   291  2534 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c72000
08-31 16:50:49.966   291  2534 V AudioFlinger: RecordThread: loop stopping
08-31 16:50:49.966   291  1065 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 16:50:49.967   959   982 I WindowStateAnimator: Starting window displayed
08-31 16:50:49.967   291   291 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-31 16:50:49.967   291   291 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
08-31 16:50:49.967   291   291 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-31 16:50:49.967   291   291 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-31 16:50:49.967   291  1066 V AudioPolicyService: AudioCommandThread() waking up
08-31 16:50:49.967   291  1066 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-31 16:50:49.967   291  1066 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 16:50:49.969   291   291 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
08-31 16:50:49.969   291   291 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-31 16:50:49.970   291  1065 V AudioPolicyService: AudioCommandThread() waking up
08-31 16:50:49.970   291  1065 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
08-31 16:50:49.970   291  1065 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 291
08-31 16:50:49.970   291  1065 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-31 16:50:49.970   291  1065 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-31 16:50:49.970   291  2534 V AudioFlinger: RecordThread: loop starting
08-31 16:50:49.970   291  2534 V AudioFlinger: processConfigEvents_l() remaining events 1
08-31 16:50:49.970   291  2534 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-31 16:50:49.970   291  2534 V audio_hw_primary: in_set_parameters: exit: status(0)
08-31 16:50:49.971   291  2534 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3c72000
08-31 16:50:49.971   291  2534 V AudioFlinger: RecordThread: loop stopping
08-31 16:50:49.971   291  1065 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 16:50:49.973   959  1057 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-31 16:50:49.974   959  1057 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-31 16:50:49.978   959  1057 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-31 16:50:49.978   959  1057 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-31 16:50:49.978   959  1057 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 16:50:49.980  1967  2458 V AudioRecord: stop()
08-31 16:50:49.981  1967  2458 V AudioRecord: stop()
08-31 16:50:49.981  1967  2458 V AudioRecord: stop()
08-31 16:50:49.982   959  1057 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3303d4c5,  pkg=WindowManager.LayoutParams
08-31 16:50:49.982   959  1057 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-31 16:50:49.983  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-31 16:50:49.983   291  1296 V AudioFlinger: RecordHandle::stop()
08-31 16:50:49.983   291  1296 V AudioFlinger: RecordThread::stop
08-31 16:50:49.984   291  1296 V AudioPolicyManager: releaseInput() 17
08-31 16:50:49.984   291  1296 V AudioPolicyManager: closeInput(17)
08-31 16:50:49.984   291  1296 V AudioFlinger: closeInput() 17
08-31 16:50:49.984   291  1296 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-31 16:50:49.984   959  1350 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-31 16:50:49.984  1373  1411 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-31 16:50:49.984   291  1296 V AudioFlinger: ThreadBase::exit
08-31 16:50:49.984  1967  2000 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-31 16:50:49.984  2848  2876 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-31 16:50:49.984  3113  3128 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-31 16:50:49.984   291  2534 V AudioFlinger: RecordThread: loop starting
08-31 16:50:49.984   291  2534 V AudioFlinger: RecordThread 0xb3c72000 exiting
08-31 16:50:49.984  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-31 16:50:49.984  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-31 16:50:49.984  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-31 16:50:49.985  1753  1769 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-31 16:50:49.985   291  1296 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546e1a0)
08-31 16:50:49.985   291  1296 D audio_hw_primary: in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
08-31 16:50:49.985   291  1296 V audio_hw_primary: in_standby: exit:  status(0)
08-31 16:50:49.985   291  1296 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-31 16:50:49.985   291  1296 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-31 16:50:49.986   291  1066 V AudioPolicyService: AudioCommandThread() waking up
08-31 16:50:49.986   291  1066 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-31 16:50:49.986   291  1296 V AudioPolicyManager: releaseInput() exit
08-31 16:50:49.986   291  1296 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-31 16:50:49.986   291  1296 V AudioFlinger: removeClient_l() pid 1967, calling pid 291
08-31 16:50:49.987   291   291 V AudioFlinger: releasing 16 from 1967 for -1
08-31 16:50:49.987   291  1066 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 16:50:49.987   291   291 V AudioFlinger:  decremented refcount to 0
08-31 16:50:49.987   291   291 V AudioFlinger: purging stale effects
08-31 16:50:49.989  1967  2480 I HotwordRecognitionRnr: Stopping hotword detection.
08-31 16:50:49.997  1967  2493 I HotwordRecognitionRnr: Hotword detection finished
08-31 16:50:50.091  5843  5843 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-31 16:50:50.223  5843  5843 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-31 16:50:50.296  5843  5843 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 9192-9204)
08-31 16:50:50.296  5843  5843 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 16:50:50.329  5843  5843 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {379f843c}
08-31 16:50:50.330  5843  5843 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 16:50:50.336  5843  5843 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 16:50:50.352  5843  5843 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 16:50:50.354  5843  5843 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:50.358  5843  5843 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 16:50:50.418  5843  5878 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-31 16:50:50.449  5843  5843 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-31 16:50:50.461  5843  5843 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 16:50:50.461  5843  5843 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 16:50:50.469  5843  5843 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 16:50:50.469  5843  5843 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 16:50:50.469  5843  5843 I Adreno-EGL: Build Date: 03/02/15 Mon
08-31 16:50:50.469  5843  5843 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-31 16:50:50.469  5843  5843 I Adreno-EGL: Remote Branch: 
08-31 16:50:50.469  5843  5843 I Adreno-EGL: Local Patches: 
08-31 16:50:50.469  5843  5843 I Adreno-EGL: Reconstruct Branch: 
08-31 16:50:50.610   291  1606 V AudioPolicyService: registerClient() client 0xb551c660, uid 10030
08-31 16:50:50.640   959  1058 D BluetoothManagerService: Message: 20
08-31 16:50:50.640   959  1058 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2448cb1a:true
08-31 16:50:50.659  5843  5892 D BluetoothAdapter: 18246695: getState() :  mService = null. Returning STATE_OFF
,08-31 16:50:50.778  5843  5843 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 16:50:50.791  5843  5843 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 16:50:50.801  5843  5843 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-31 16:50:50.807  5843  5843 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 16:50:50.807  5843  5843 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-31 16:50:50.822  5843  5843 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-31 16:50:50.831  5843  5843 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:50.831  5843  5843 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:50.869  2848  2848 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19955
,08-31 16:50:50.887  5843  5843 I Activity: Activity.onPostResume() called 
,08-31 16:50:50.897  5843  5910 D OpenGLRenderer: Render dirty regions requested: true
08-31 16:50:50.897  5843  5910 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 16:50:50.904  5843  5910 D OpenGLRenderer: Enabling debug mode 0
,08-31 16:50:50.927  5843  5843 D Atlas   : Validating map...
,08-31 16:50:50.931   959  1383 D SplitWindow: check instance of lgWin Window{7a2eca u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 16:50:50.941  5843  5890 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 16:50:50.980   959  1805 D InputDispatcher: Focus entered window: Window{7a2eca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 16:50:51.052   959  1823 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-31 16:50:51.067   959  1059 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s284ms
08-31 16:50:51.067   959  1059 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2df6c5e0 u0 com.test.thalitest/.MainActivity t259} time:119975
,08-31 16:50:51.074  5843  5843 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@95cad17 time:119981
08-31 16:50:51.198  5843  5843 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5843
,08-31 16:50:51.377  5843  5843 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 16:50:51.761  5843  5913 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635597056
,08-31 16:50:51.806  5843  5913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 16:50:51.806  5843  5913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 16:50:51.806  5843  5913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 16:50:51.806  5843  5913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 16:50:51.806  5843  5913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 16:50:51.806  5843  5913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d15a88 added. We now have 1 listener(s)
,08-31 16:50:51.824   959  1860 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 16:50:51.825  5843  5913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-31 16:50:51.827  5843  5913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-31 16:50:51.828  5843  5913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 16:50:51.829  5843  5913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 16:50:51.835  5843  5913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ced0a07 added. We now have 1 listener(s)
08-31 16:50:51.836  5843  5913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 16:50:51.868  5843  5913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 16:50:51.868  5843  5913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 16:50:51.870  5843  5913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-31 16:50:51.870  5843  5913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 16:50:51.870  5843  5913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 16:50:51.876  5843  5913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 16:50:51.876   959  1805 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 16:50:51.876  5843  5913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-31 16:50:51.897  5843  5913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 16:50:51.897  5843  5913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:50:51.897  5843  5913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:51.897  5843  5913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:50:51.897  5843  5913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:50:51.897  5843  5913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:50:51.897  5843  5913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:51.897  5843  5913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:51.897  5843  5913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:50:51.898  5843  5913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 16:50:51.898  5843  5913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 16:50:51.901  5843  5913 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 16:50:52.024  5843  5843 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 16:50:52.077  5843  5861 I art     : CheckpointMarkThreadRoots callback created = 0x9eadf250
,08-31 16:50:52.110  5843  5861 I art     : CheckpointMarkThreadRoots callback created = 0x9eadf220
,08-31 16:50:52.755  5843  5935 W jxcore-log: Initializing JXcore engine
08-31 16:50:52.755  5843  5935 W jxcore-log: JXcore engine is ready
,08-31 16:50:52.832  5935  5935 W Thread-684: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6315]" dev="sockfs" ino=6315 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-31 16:50:52.832  5935  5935 W Thread-684: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 16:50:52.832  5935  5935 W Thread-684: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6469]" dev="sockfs" ino=6469 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-31 16:50:52.832  5935  5935 W Thread-684: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-31 16:50:52.832  5935  5935 W Thread-684: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-31 16:50:52.832  5935  5935 W Thread-684: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[27145]" dev="sockfs" ino=27145 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-31 16:50:52.869  5843  5935 W jxcore-log: Starting JXcore engine
,08-31 16:50:53.005  5843  5935 W jxcore-log: Platform android
08-31 16:50:53.005  5843  5935 W jxcore-log: 
08-31 16:50:53.005  5843  5935 W jxcore-log: Process ARCH arm
08-31 16:50:53.005  5843  5935 W jxcore-log: 
,08-31 16:50:53.310  5843  5935 I jxcore-log: JXcore Cordova bridge is ready!
08-31 16:50:53.310  5843  5935 I jxcore-log: 
08-31 16:50:53.310  5843  5935 W jxcore-log: JXcore engine is started
,08-31 16:50:53.317  5843  5913 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 16:50:53.318  5843  5843 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-31 16:50:54.441   302   362 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-31 16:50:58.188   489   489 D charger_monitor: init target 500000
,08-31 16:50:58.193  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-31 16:50:58.193  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-31 16:50:58.193  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-31 16:50:58.194  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-31 16:50:58.194  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-31 16:50:58.229  1806  1966 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-31 16:50:58.229  1806  1966 D LEDHandler: Battery Level Remaining: 100%
08-31 16:50:58.229  1806  1966 D LEDHandler: Battery Temp: 312, mChargingStatus=5, mChargingStop=false
,08-31 16:50:58.230  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 312
08-31 16:50:58.231  1841  1841 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-31 16:50:58.233  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-31 16:50:58.233  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 312
08-31 16:50:58.239   489   489 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-31 16:50:58.241  1841  1841 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-31 16:50:58.245   959  1315 D WifiController: battery changed pluggedType: 2
,08-31 16:50:58.262  5720  5720 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 16:50:58.322  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-31 16:50:58.342   959  1787 I ActivityManager: Process com.google.android.apps.docs (pid 5640) has died,
,08-31 16:50:59.446   302   362 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-31 16:50:59.926   959  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{426aa5 type 2 when 120000 com.google.android.gms} when 120000
,08-31 16:50:59.933   959  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3963de7a type 2 when 123461 com.google.android.gms} when 123461
08-31 16:51:00.001   959  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=969075207, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=959
,08-31 16:51:00.011  2842  2842 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:51:0
08-31 16:51:00.012  2842  2842 D WeatherService: 2 : TimeTick Intent And Screen On
08-31 16:51:00.013  2842  2842 D WeatherService: 2 : SDK version : 21
,08-31 16:51:00.015   959  2283 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
08-31 16:51:00.016  2842  2842 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
08-31 16:51:00.023  2842  2842 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
08-31 16:51:00.023  2842  2842 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
08-31 16:51:00.023  2842  2842 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
08-31 16:51:00.025  2842  2842 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 16:51:00.025  2842  2842 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
08-31 16:51:00.025  2842  2842 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
08-31 16:51:00.026  2842  2842 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
08-31 16:51:00.026  2842  2842 D WeatherTheme: 2 : Fixed theme : optimus
,08-31 16:51:00.035  2842  2842 D WeatherReflect: 2 : Map key string is -2
,08-31 16:51:00.040  2842  2842 D lim     : 2 : time = 16:51
,08-31 16:51:00.045  2842  2842 I WeatherReflect: Model Name : LG-D722
08-31 16:51:00.045  2842  2842 D WeatherTheme: 2 : Different view - status_min_formatted : 50 != 51
08-31 16:51:00.045  2842  2842 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
08-31 16:51:00.047  2842  2842 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
08-31 16:51:00.049  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-31 16:51:00.049  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-31 16:51:00.050  2842  2842 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-31 16:51:00.050  2842  2842 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-31 16:51:00.050  2842  2842 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-31 16:51:00.050  2842  2842 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
08-31 16:51:00.051  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-31 16:51:00.055  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-31 16:51:00.055  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-31 16:51:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-31 16:51:00.058  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 16:51:00.126  2842  2842 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
08-31 16:51:00.126  2842  2842 D Weather4x2_optimus: widgetType = 1, orientation = 1
08-31 16:51:00.126  2842  2842 D Weather4x2_optimus: forecast size is 0
08-31 16:51:00.126  2842  2842 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-31 16:51:00.126  2842  2842 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-31 16:51:00.127  2842  2842 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-31 16:51:00.127  2842  2842 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-31 16:51:00.127  2842  2842 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-31 16:51:00.127  2842  2842 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-31 16:51:00.127  2842  2842 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-31 16:51:00.127  2842  2842 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-31 16:51:00.127  2842  2842 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-31 16:51:00.127  2842  2842 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
08-31 16:51:00.127  2842  2842 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
08-31 16:51:00.127  2842  2842 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-31 16:51:00.127  2842  2842 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-31 16:51:00.127  2842  2842 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-31 16:51:00.128  2842  2842 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
,08-31 16:51:00.130  2842  2842 D Theme_WeatherAncestor_optimus: url is : null
08-31 16:51:00.133  2842  2842 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-31 16:51:00.134  2842  2842 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-31 16:51:00.134  2842  2842 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,08-31 16:51:00.135  2842  2842 D WeatherAncestor: 2 : update view, appWidgetId: 2
08-31 16:51:00.139  2842  2842 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:51:0
08-31 16:51:00.157   959   959 D PowerManagerServiceEx: releaseWakeLockInternal: lock=969075207 [*alarm*], flags=0x0
,08-31 16:51:00.248   959  1787 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:51:00.251   959  1316 D ConnectivityService: dumpNetworkRequest
,08-31 16:51:00.325  5513  5980 W DriveInitializer: Background init thread started
,08-31 16:51:00.354   248   286 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 16:51:00.355   248   286 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
08-31 16:51:00.355   248   286 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:00.356  5513  5980 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
08-31 16:51:00.369  1880  1880 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,08-31 16:51:00.465  5513  5980 W DriveInitializer: Background init thread ended
,08-31 16:51:00.511  1880  1880 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-31 16:51:04.451   302   362 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-31 16:51:05.345   959   997 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-31 16:51:05.345   959   997 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-31 16:51:05.345   959   997 D sensors_hal_Time: tsOffsetIs: Apps: 134252667556; DSPS: 4497748; Offset : -3014810215
,08-31 16:51:09.456   302   362 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-31 16:51:10.863  2848  2848 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-31 16:51:10.872  2848  2848 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
08-31 16:51:14.462   302   362 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-31 16:51:16.052  5843  5935 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 16:51:16.052  5843  5935 I jxcore-log: 
,08-31 16:51:16.056  5843  5935 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 16:51:16.056  5843  5935 I jxcore-log: 
08-31 16:51:16.059  5843  5935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:16.059  5843  5935 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:51:16.059  5843  5935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:16.059  5843  5935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:51:16.059  5843  5935 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:51:16.059  5843  5935 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:51:16.059  5843  5935 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:16.059  5843  5935 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:16.059  5843  5935 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:51:16.060  5843  5935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:16.061  5843  5935 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:51:16.063  5843  5935 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 16:51:16.063  5843  5935 I jxcore-log: 
,08-31 16:51:16.066  5843  5935 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 16:51:16.066  5843  5935 I jxcore-log: 
,08-31 16:51:16.633  5843  5935 I jxcore-log: Running unit tests
08-31 16:51:16.633  5843  5935 I jxcore-log: 
,08-31 16:51:16.634  5843  5935 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-31 16:51:16.634  5843  5935 I jxcore-log: Failed to execute UT.
08-31 16:51:16.634  5843  5935 I jxcore-log: 
08-31 16:51:16.637  5843  5935 I jxcore-log: Unit Test app is loaded
08-31 16:51:16.637  5843  5935 I jxcore-log: 
08-31 16:51:16.651  5843  5935 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 16:51:16.651  5843  5935 I jxcore-log: 
,08-31 16:51:16.660  5843  5843 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 16:51:16.670   959   983 D WifiServiceImplEx: setWifiEnabled: true pid=5843, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,08-31 16:51:16.688   959   983 D WifiService: setWifiEnabled: true pid=5843, uid=10030
,08-31 16:51:16.721   959   983 D WifiServiceImplEx: disconnect pid=5843, uid=10030, packageName=com.test.thalitest
08-31 16:51:16.722   959  1787 D WifiServiceImplEx: reconnect pid=5843, uid=10030, packageName=com.test.thalitest
08-31 16:51:16.743   959  1310 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-31 16:51:16.746   959  1310 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
08-31 16:51:16.752   959  1310 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
08-31 16:51:16.752   959  1310 E WifiHW  : band=b
08-31 16:51:16.752   959  1310 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
08-31 16:51:16.752   959  2065 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 16:51:16.761   959  2065 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 16:51:16.767   959   959 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 16:51:16.769   959   959 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 16:51:16.783   287  1050 D SoftapController: Softap fwReload - Ok
,08-31 16:51:16.784   959   959 D Ulp_jni : JNI:system_update. Event-4
08-31 16:51:16.790   959  1058 D BluetoothManagerService: Message: 1
08-31 16:51:16.791   959   959 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 16:51:16.791   959   959 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 16:51:16.791   959   959 D Ulp_jni : JNI:system_update. Event-4
08-31 16:51:16.791   959  1058 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-31 16:51:16.795  5843  5935 I jxcore-log: My device name is: LGE-LG-D722
08-31 16:51:16.795  5843  5935 I jxcore-log: 
08-31 16:51:16.807  2034  2034 D BluetoothAdapterService(1070426906): onBind()
,08-31 16:51:16.808   959  1310 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:16.808   959  1310 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:16.814   959   959 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 16:51:16.814   959  1058 D BluetoothManagerService: Message: 40
08-31 16:51:16.814   959  1058 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 16:51:16.817   287  1050 D CommandListener: Setting iface cfg
08-31 16:51:16.817   287  1050 D CommandListener: Trying to bring down wlan0
08-31 16:51:16.818   287  1050 D CommandListener: Clearing all IP addresses on wlan0
08-31 16:51:16.829   959  1310 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-31 16:51:16.851  2034  2056 I bluedroid: config_hci_snoop_log
,08-31 16:51:16.872   959  1058 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 16:51:16.878   959  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-31 16:51:16.909  5998  5998 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 16:51:16.917  2034  2057 V LGMDMManagerInternal: Create singleton instance
08-31 16:51:16.933   959  1310 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-31 16:51:16.942  5843  5843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:51:16.949  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:16.962  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:16.961 DNS addrs= 0.0.0.0, 0.0.0.0, 
08-31 16:51:16.962  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
,08-31 16:51:16.980  5998  5998 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 16:51:16.981  5998  5998 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-31 16:51:16.995   959  1037 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6009 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,08-31 16:51:17.001   959   959 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 16:51:17.060  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,08-31 16:51:17.069  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:17.070  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
08-31 16:51:17.070  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
08-31 16:51:17.095  2034  2057 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
,08-31 16:51:17.096  2034  2057 D BluetoothAdapterService(1070426906): enable() - Enable called with quiet mode status =  false
08-31 16:51:17.099  2034  2180 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-31 16:51:17.099  2034  2180 D BluetoothAdapterProperties: Setting state to 11
08-31 16:51:17.100  2034  2180 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 16:51:17.102  2034  2180 D BluetoothAdapterService(1070426906): updateAdapterState() - Broadcasting state to 1 receivers.
08-31 16:51:17.103   959  1058 D BluetoothManagerService: Message: 60
08-31 16:51:17.104   959  1058 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 16:51:17.106   959  1058 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-31 16:51:17.112  1806  1806 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:17.114  5843  5843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:51:17.119  2034  2180 D BluetoothAdapterService(1070426906): processStart()
08-31 16:51:17.132  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 16:51:17.132  2034  2057 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
,08-31 16:51:17.137  2034  2056 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:17.144  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
,08-31 16:51:17.154  1373  1373 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: Unable to read settings
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
08-31 16:51:17.179  2034  2180 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 16:51:17.184  2034  2180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 16:51:17.184  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 16:51:17.185  2034  2180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 16:51:17.185  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 16:51:17.185  2034  2180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 16:51:17.185  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 16:51:17.186  2034  2180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 16:51:17.186  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 16:51:17.186  2034  2180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 16:51:17.186  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 16:51:17.187  2034  2180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 16:51:17.187  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 16:51:17.188  2034  2180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 16:51:17.188  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 16:51:17.190  2034  2180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-31 16:51:17.190  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
08-31 16:51:17.191  2034  2180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
,08-31 16:51:17.191  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
08-31 16:51:17.192  2034  2180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
08-31 16:51:17.192  2034  2180 D BluetoothAdapterService(1070426906): processStart() - Make Bond State Machine
08-31 16:51:17.200  2034  2180 D BluetoothBondStateMachine: make
08-31 16:51:17.202  2034  2180 D BluetoothAdapterService: setAdapterService() - set to: null
08-31 16:51:17.202  2034  2180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
08-31 16:51:17.203  2034  2180 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 16:51:17.203  2034  6030 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 16:51:17.209  2034  2180 D BluetoothAdapterService: getQuietmodeRadioCount = 0
08-31 16:51:17.210  2034  2180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: Unable to read settings
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
08-31 16:51:17.210  2034  2180 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 16:51:17.210  2034  2180 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 16:51:17.211  2034  2180 D BluetoothAdapterService(1070426906): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
08-31 16:51:17.221  2034  2180 D BluetoothAdapterService: getQuietmodeRadioCount = 0
08-31 16:51:17.221  2034  2180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 16:51:17.221  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 16:51:17.221  2034  2180 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-31 16:51:17.222  2034  2180 D BluetoothAdapterService(1070426906): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
,08-31 16:51:17.226  2034  2180 D BluetoothAdapterService: getQuietmodeRadioCount = 0
08-31 16:51:17.226  2034  2180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 16:51:17.226  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 16:51:17.226  2034  2180 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-31 16:51:17.226  2034  2180 D BluetoothAdapterService(1070426906): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
08-31 16:51:17.232  2034  2180 D BluetoothAdapterService: getQuietmodeRadioCount = 0
08-31 16:51:17.232  2034  2180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 16:51:17.232  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 16:51:17.232  2034  2180 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-31 16:51:17.232  2034  2180 D BluetoothAdapterService(1070426906): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
08-31 16:51:17.236  2034  2034 D HeadsetService: Received start request. Starting profile...
,08-31 16:51:17.238  2034  2180 D BluetoothAdapterService: getQuietmodeRadioCount = 0
08-31 16:51:17.238  2034  2180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 16:51:17.238  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 16:51:17.238  2034  2180 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-31 16:51:17.238  2034  2180 D BluetoothAdapterService(1070426906): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
08-31 16:51:17.241  1753  1753 D BluetoothHeadset: Proxy object connected
08-31 16:51:17.243   959   959 D BluetoothHeadset: Proxy object connected
08-31 16:51:17.243  2034  2180 D BluetoothAdapterService: getQuietmodeRadioCount = 0
08-31 16:51:17.243  2034  2180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 16:51:17.243  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 16:51:17.243  2034  2180 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-31 16:51:17.243  2034  2180 D BluetoothAdapterService(1070426906): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
08-31 16:51:17.249  2034  2180 D BluetoothAdapterService: getQuietmodeRadioCount = 0
08-31 16:51:17.249  2034  2180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 16:51:17.249  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 16:51:17.249  2034  2180 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-31 16:51:17.249  2034  2180 D BluetoothAdapterService(1070426906): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
08-31 16:51:17.251  2034  2034 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 16:51:17.253  2034  2056 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:17.258  2034  2180 D BluetoothAdapterService: getQuietmodeRadioCount = 0
08-31 16:51:17.258  2034  2180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-31 16:51:17.258  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 16:51:17.258  2034  2180 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-31 16:51:17.258  2034  2180 D BluetoothAdapterService(1070426906): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
08-31 16:51:17.265  2034  2034 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 16:51:17.266  2034  2034 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 16:51:17.268  2034  2180 D BluetoothAdapterService: getQuietmodeRadioCount = 0
08-31 16:51:17.268  2034  2180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
08-31 16:51:17.268  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
08-31 16:51:17.268  2034  2034 D HeadsetStateMachine: make
08-31 16:51:17.268  2034  2180 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
08-31 16:51:17.268  2034  2180 D BluetoothAdapterService(1070426906): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
08-31 16:51:17.269  1753  1753 D BluetoothHeadset: Proxy object connected
08-31 16:51:17.273  1753  1753 D BluetoothHeadset: Proxy object connected
08-31 16:51:17.286  2034  2180 D BluetoothAdapterService: getQuietmodeRadioCount = 0
08-31 16:51:17.286  2034  2180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
08-31 16:51:17.286  2034  2180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
08-31 16:51:17.286  2034  2180 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
08-31 16:51:17.286  2034  2180 D BluetoothAdapterService(1070426906): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
,08-31 16:51:17.290  2034  2180 V LGMDMManager: Create singleton instance
08-31 16:51:17.309  2034  2180 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 16:51:17.336  2034  2034 D HeadsetStateMachine: max_hf_connections = 1
08-31 16:51:17.336  2034  2034 I bluedroid: get_profile_interface handsfree
,08-31 16:51:17.341  2034  2034 I bt-btif : btif_hf_get_interface
08-31 16:51:17.341  2034  2034 I bt-btif : init
08-31 16:51:17.341  2034  2034 D bt-btif : max_hf_clients = 1
08-31 16:51:17.341  2034  2034 D bt-btif : btif_max_hf_clients = 1
08-31 16:51:17.341  2034  2034 D bt-btif : btif_enable_service: current services:0xa0643330
08-31 16:51:17.353  2034  2034 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 16:51:17.354   291  1611 V AudioPolicyService: registerClient() client 0xb551ccc0, uid 1002
,08-31 16:51:17.355   291  1323 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 16:51:17.356   291  1323 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 16:51:17.356   291  1323 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 16:51:17.356   291  1606 V AudioFlinger: registerClient() client 0xb3c5fb08, pid 2034
08-31 16:51:17.356   291  1606 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
08-31 16:51:17.356   291  1606 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
08-31 16:51:17.356   291  1606 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
08-31 16:51:17.357  2034  2034 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 16:51:17.357   291  1290 V AudioFlinger: thread 0xb5735000 type 0 TID 1290 waking up
08-31 16:51:17.357   291  1288 V AudioFlinger: thread 0xb56eb000 type 0 TID 1288 waking up
08-31 16:51:17.357   291  1287 V AudioFlinger: thread 0xb5651000 type 0 TID 1287 waking up
08-31 16:51:17.357   291  1287 V AudioFlinger: processConfigEvents_l() remaining events 1
08-31 16:51:17.357   291  1287 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
08-31 16:51:17.357   291  1290 V AudioFlinger: processConfigEvents_l() remaining events 1
08-31 16:51:17.357   291  1288 V AudioFlinger: processConfigEvents_l() remaining events 1
08-31 16:51:17.357   291  1290 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
08-31 16:51:17.357   291  1288 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
08-31 16:51:17.360   291  1288 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:17.360   291  1288 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:17.360   959  1823 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:17.360  1373  2466 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:17.360   959  1823 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:17.360  1373  2466 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:17.361  1753  1769 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:17.361   291  1288 V AudioFlinger: processConfigEvents_l() DONE thread 0xb56eb000
08-31 16:51:17.361   291  1287 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:17.361  1967  1991 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:17.361   291  1287 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 16:51:17.361  1967  1991 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:17.361  3113  3128 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:17.361   291  1287 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
08-31 16:51:17.361   291  1290 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
08-31 16:51:17.361   291  1290 V AudioSystem: ioConfigChanged() opening already existing output! 6
08-31 16:51:17.361  2034  6007 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:17.361   291  1290 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5735000
08-31 16:51:17.361  2034  6007 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 16:51:17.361  2034  6007 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:17.361  1373  1411 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:17.361  1373  1411 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 16:51:17.361   959  2283 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:17.361   959  2283 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 16:51:17.361  1373  1411 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
08-31 16:51:17.361  1373  1411 V AudioSystem: ioConfi,gChanged() opening already existing output! 6
08-31 16:51:17.361   959  2283 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
08-31 16:51:17.361   959  2283 V AudioSystem: ioConfigChanged() opening already existing output! 6
08-31 16:51:17.361  3113  3128 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:17.361  3113  3128 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:17.361  3113  3128 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 16:51:17.361  1967  2000 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:17.361  1967  2000 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 16:51:17.361  3113  3128 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
08-31 16:51:17.361  3113  3128 V AudioSystem: ioConfigChanged() opening already existing output! 6
08-31 16:51:17.361  1967  2000 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
08-31 16:51:17.361  1967  2000 V AudioSystem: ioConfigChanged() opening already existing output! 6
08-31 16:51:17.361  1753  1769 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:17.362  1753  1769 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:17.362  1753  1769 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 16:51:17.362  1753  1769 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
08-31 16:51:17.362  1753  1769 V AudioSystem: ioConfigChanged() opening already existing output! 6
08-31 16:51:17.362  2848  3806 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 16:51:17.362  2848  3806 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 16:51:17.362  2848  3806 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 16:51:17.362  2848  3806 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 16:51:17.362  2848  3806 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
08-31 16:51:17.362  2848  3806 V AudioSystem: ioConfigChanged() opening already existing output! 6
08-31 16:51:17.367  2034  6007 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 16:51:17.367  2034  2034 V ToneGenerator: Create Track: 0xb4909480
08-31 16:51:17.367  2034  6007 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
08-31 16:51:17.367  2034  2034 V AudioTrack: set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 16:51:17.367  2034  6007 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
08-31 16:51:17.367  2034  2034 V AudioTrack: set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
08-31 16:51:17.367   291  1296 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 16:51:17.367  2034  2034 D AudioTrack: TrackOffload: AudioTrack Offload disabled by property, returning false
08-31 16:51:17.367   291  1611 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 16:51:17.367   291  1611 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 16:51:17.367   291  1611 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 16:51:17.367   291  1611 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 16:51:17.368  2034  2034 V AudioSystem: getLatency() output 2, latency 50
08-31 16:51:17.368  2034  2034 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 16:51:17.368  2034  2034 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 16:51:17.368  2034  2034 V AudioTrack: Create normal PCM 0x1 Track
08-31 16:51:17.368   291  1606 V AudioFlinger: createTrack() lSessionId: 22
08-31 16:51:17.368   291  1606 V AudioFlinger: AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
08-31 16:51:17.368   291  1606 V AudioFlinger: sendConfigEvent_l() num events 1 event 1
08-31 16:51:17.369  2034  2034 V AudioTrack: Flags here  0x4 
08-31 16:51:17.369  2034  2034 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 16:51:17.370   291  1296 V AudioFlinger: acquiring 22 from 2034, for 2034
08-31 16:51:17.370   291  1296 V AudioFlinger:  added new entry for 22
08-31 16:51:17.372  2034  2034 V ToneGenerator: ToneGenerator INIT OK, time: 146279
08-31 16:51:17.372  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
08-31 16:51:17.372   291  1287 V AudioFlinger: processConfigEvents_l() remaining events 1
08-31 16:51:17.373   291  1287 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
08-31 16:51:17.374  2034  6031 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 16:51:17.374  2034  6031 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 16:51:17.374  2034  6031 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 16:51:17.375  2034  6031 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 16:51:17.375   291  1323 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 2034
08-31 16:51:17.391   291  1323 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
,08-31 16:51:17.391   291  1323 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 16:51:17.391   291  1323 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 16:51:17.391   291  1323 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 16:51:17.391   291  1323 V voice   : voice_set_parameters: exit with code(0)
08-31 16:51:17.391   291  1323 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 16:51:17.391   291  1323 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 16:51:17.399   291  1323 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 16:51:17.399   291  1323 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 16:51:17.399   291  1323 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-31 16:51:17.399   291  1323 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 16:51:17.400  2034  6031 V ToneGenerator: ToneGenerator destructor
08-31 16:51:17.400  2034  6031 V ToneGenerator: stopTone
08-31 16:51:17.400  2034  6031 V ToneGenerator: Delete Track: 0xb4909480
08-31 16:51:17.400  2034  6031 V AudioTrack: ~AudioTrack, releasing session id from 2034 on behalf of 2034
08-31 16:51:17.400   291  1296 V AudioFlinger: releasing 22 from 2034 for 2034
08-31 16:51:17.400   291  1296 V AudioFlinger:  decremented refcount to 0
08-31 16:51:17.400   291  1296 V AudioFlinger: purging stale effects
08-31 16:51:17.400   291  1296 V AudioFlinger: remove track (4099) and delete from mixer
08-31 16:51:17.400   291  1296 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 16:51:17.400   291  1296 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 16:51:17.400   291  1296 V AudioFlinger: PlaybackThread::Track destructor
08-31 16:51:17.400   291  1066 V AudioPolicyService: AudioCommandThread() waking up
08-31 16:51:17.401   291  1296 V AudioFlinger: removeClient_l() pid 2034, calling pid 291
08-31 16:51:17.401   291  1066 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 16:51:17.401   291  1066 V AudioPolicyManager: releaseOutput() 2
08-31 16:51:17.401   291  1066 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 16:51:17.469  6009  6009 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:17.470  6009  6009 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-31 16:51:17.470  6009  6009 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 16:51:17.473  6009  6009 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-31 16:51:17.476  6009  6009 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 16:51:17.581   959  1350 I art     : Explicit concurrent mark sweep GC freed 39517(1912KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.505ms total 216.947ms
08-31 16:51:17.583  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
,08-31 16:51:17.587   959   959 D BluetoothA2dp: Proxy object connected
08-31 16:51:17.587  2034  2034 D A2dpService: Received start request. Starting profile...
08-31 16:51:17.588  2034  2034 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 16:51:17.589  2034  2034 V Avrcp   : make
08-31 16:51:17.589  2034  2034 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 16:51:17.589  2034  2034 I bluedroid: get_profile_interface avrcp
08-31 16:51:17.589  2034  2056 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:17.590  2034  2034 I bt-btif : btif_rc_get_interface
08-31 16:51:17.590  2034  2034 I bt-btif : ## init ##
08-31 16:51:17.603  2034  2034 I LGBluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 16:51:17.605  2034  2034 I LGBluetoothAvrcpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 16:51:17.605  2034  2034 I LGBluetoothAvrcpServiceJni: initNative: succeeds
,08-31 16:51:17.608  2034  2034 I BluetoothAvrcpBrcmAdapterJni: classInitBrcmNative
08-31 16:51:17.618  2034  2034 I BluetoothAvrcpBrcmAdapterJni: initBrcmNative
08-31 16:51:17.639  6009  6009 I IndexDatabaseHelper: Using schema version: 115
,08-31 16:51:17.641  6009  6009 I IndexDatabaseHelper: Index is fine
08-31 16:51:17.744   959   982 V AudioService: updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
08-31 16:51:17.744   959   982 E AudioService: No RCC entry present to update
,08-31 16:51:17.745  2034  2034 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 16:51:17.745  2034  2034 I BluetoothA2dpServiceJni: classInitNative
08-31 16:51:17.745  2034  2034 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 16:51:17.745  2034  2034 D A2dpStateMachine: make
08-31 16:51:17.749  2034  2034 I bluedroid: get_profile_interface a2dp
08-31 16:51:17.749  2034  2034 I bt-btif : btif_av_get_src_interface
08-31 16:51:17.749  2034  2034 I bt-btif : init
08-31 16:51:17.749  2034  2034 D bt-btif : btif_enable_service: current services:0xa0643330
08-31 16:51:17.751  2034  2034 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 16:51:17.751  2034  2034 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 16:51:17.752  2034  2034 D LGBluetoothPowerControlManager: [BTUI] getInstance
08-31 16:51:17.753  2034  2034 D LGBluetoothPowerControlManager: [BTUI] init
08-31 16:51:17.822   959  1383 I ActivityManager: Process com.google.android.apps.plus (pid 5694) has died
,08-31 16:51:17.825  2034  2034 D LGBluetoothPowerControlManager: [BTUI] init : getProfileProxy
08-31 16:51:17.829   959  1058 D BluetoothManagerService: Message: 30
08-31 16:51:17.831  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
08-31 16:51:17.831  2034  6039 D A2dpStateMachine: Enter Disconnected: -2
08-31 16:51:17.832  2034  2034 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 16:51:17.836  2034  2034 D HidService: Received start request. Starting profile...
08-31 16:51:17.836  2034  2034 I bluedroid: get_profile_interface hidhost
08-31 16:51:17.836  2034  2034 I bt-btif : btif_hh_get_interface
08-31 16:51:17.836  2034  2034 I bt-btif : init
08-31 16:51:17.836  2034  2034 D bt-btif : btif_enable_service: current services:0xa0643330
08-31 16:51:17.836  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
08-31 16:51:17.837  2034  2034 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 16:51:17.840  2034  2034 D HealthService: Received start request. Starting profile...
08-31 16:51:17.842  2034  2034 I bluedroid: get_profile_interface health
08-31 16:51:17.842  2034  2034 I bt-btif : btif_hl_get_interface
08-31 16:51:17.842  2034  2034 I bt-btif : init
08-31 16:51:17.842  2034  2034 D bt-btif : Process name (droid.bluetooth)
08-31 16:51:17.842  2034  2034 D bt-btif : btif_hl_soc_thread_init
08-31 16:51:17.844  2034  2034 D bt-btif : create_thread: entered
08-31 16:51:17.844  2034  2034 D bt-btif : create_thread: thread created successfully
08-31 16:51:17.844  2034  6041 D bt-btif : entered btif_hl_select_thread
08-31 16:51:17.844  2034  6041 D bt-btif : btif_hl_select_wakeup_init
08-31 16:51:17.844  2034  6041 D bt-btif : btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
08-31 16:51:17.844  2034  6041 D bt-btif : max_s=55 
08-31 16:51:17.844  2034  6041 D bt-btif : set curr_set = org_set 
08-31 16:51:17.844  2034  2034 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 16:51:17.844  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
,08-31 16:51:17.848  2034  2034 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 16:51:17.851  2034  2034 D PanService: Received start request. Starting profile...
08-31 16:51:17.852  2034  2034 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 16:51:17.852  2034  2034 I bluedroid: get_profile_interface pan
08-31 16:51:17.852  2034  2034 D bt-btif : stack_initialized = 0, btpan_cb.enabled:0
08-31 16:51:17.858  2034  2034 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 16:51:17.858  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
,08-31 16:51:17.859  2034  2034 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 16:51:17.863  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:17.865  2034  2034 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 16:51:17.865  2034  2034 D BtGatt.GattService: Received start request. Starting profile...
08-31 16:51:17.865  2034  2034 D BtGatt.GattService: start()
08-31 16:51:17.865  2034  2034 I bluedroid: get_profile_interface gatt
08-31 16:51:17.866  2034  2034 D BtGatt.AdvertiseManager: advertise manager created
08-31 16:51:17.871  2034  2034 I LGBluetoothGattAdapter: [BTUI] getInstance : create [LGBluetoothGattAdapter]
08-31 16:51:17.871  2034  2034 D LGBluetoothGattAdapter: setGattService:  set to: null
08-31 16:51:17.871  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
,08-31 16:51:17.874  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
08-31 16:51:17.874  2034  2034 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 16:51:17.875  2034  2034 V BluetoothMapService: BluetoothMapBinder()
08-31 16:51:17.877  2034  2034 D BluetoothMapService: Received start request. Starting profile...
08-31 16:51:17.877  2034  2034 D BluetoothMapService: start()
08-31 16:51:17.882  2034  2034 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 16:51:17.882  2034  2034 D BluetoothMapEmailAppObserver: createReceiver()
,08-31 16:51:17.885  2034  2034 D BluetoothMapEmailAppObserver: initObservers()
,08-31 16:51:17.885  2034  2034 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 16:51:17.893  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
,08-31 16:51:17.898  2034  2034 I BluetoothSAPServiceJni: classInitNative(L170): succeeds
08-31 16:51:17.901  2034  2034 D SapService: Received start request. Starting profile...
08-31 16:51:17.901  2034  2034 D BluetoothSAPServiceJni: initializeNative(L175): sap
08-31 16:51:17.901  2034  2034 I bluedroid: get_profile_interface sap
08-31 16:51:17.901  2034  2034 I bt-btif : btif_sc_get_interface
08-31 16:51:17.901  2034  2034 I bt-btif : init
08-31 16:51:17.901  2034  2034 D bt-btif : btif_enable_service: current services:0xa0643330
08-31 16:51:17.901  2034  2034 I LGBluetoothSapAdapter: [BTUI] getInstance : create [LGBluetoothSapAdapter]
08-31 16:51:17.901  2034  2034 I LGBluetoothSapAdapter: [BTUI] Create LGBluetoothSapManager Instance
08-31 16:51:17.903  2034  2034 D LGBluetoothSapManager: [BTUI] initSapManager
08-31 16:51:17.907  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
08-31 16:51:17.916  1753  1753 D LgeBluetoothSimManager: [BTUI] SAP_ENABLE_EVT
,08-31 16:51:17.923  2034  2034 V BluetoothFTPServiceJni: classInitNative
08-31 16:51:17.924  2034  2034 I BluetoothFTPServiceJni: classInitNative(L271): succeeds
08-31 16:51:17.924  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
08-31 16:51:17.925  2034  2034 D BluetoothFTPService: BluetoothFtpBinder()
08-31 16:51:17.926  2034  2034 D **BluetoothFTPService: Received start request. Starting profile...
08-31 16:51:17.926  2034  2034 V BluetoothFTPService: FTP-Server Service start
08-31 16:51:17.927   287  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
08-31 16:51:17.927   287  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,08-31 16:51:17.938  2034  2034 D BluetoothFTPServiceJni: initFtpNativeDataNative(L275): FTP
08-31 16:51:17.938  2034  2034 I bluedroid: get_profile_interface ftp
08-31 16:51:17.938  2034  2034 I bt-btif : btif_fts_get_interface
08-31 16:51:17.938  2034  2034 I bt-btif : init
08-31 16:51:17.938  2034  2034 D bt-btif : btif_enable_service: current services:0xa0643330
08-31 16:51:17.938  2034  2034 D BluetoothFTPServiceJni: initFtpNativeDataNative(L317): FTP init done
08-31 16:51:17.938  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
08-31 16:51:17.939  2034  2034 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 16:51:17.939  2034  2034 E BluetoothOPPServiceJni: classInitNative
08-31 16:51:17.940  2034  2034 I BluetoothOPPServiceJni: classInitNative(L373): succeeds
08-31 16:51:17.940  2034  2034 V OppService: Opp initBinder
08-31 16:51:17.942  2034  2034 D **OppService: Received start request. Starting profile...
08-31 16:51:17.942  2034  2034 D OppService: Starting OppService 
08-31 16:51:17.943  2034  2034 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 16:51:17.943  6009  6009 D WiFiOffLoadUpdatePriority: remove : truetruefalse
,08-31 16:51:17.948  6009  6009 D WiFiOffLoadUpdatePriority: remove2
08-31 16:51:17.948  6009  6009 V WiFiOffLoadSharedPrefsUtils: save wifi state
08-31 16:51:17.948  6009  6009 V WiFiOffLoadSharedPrefsUtils: save remove
08-31 16:51:17.949  2034  2034 I NotificationManager: com.android.bluetooth: cancelAll by com.android.bluetooth
08-31 16:51:17.950  6009  6009 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
08-31 16:51:17.950  2034  2034 V BluetoothOppNotification: send message
08-31 16:51:17.950  6009  6009 D WiFiOffLoadBroadcast: S: false, R: true
08-31 16:51:17.957  2034  2034 D BluetoothOppPreference: Dumping Names:  
08-31 16:51:17.957  2034  2034 D BluetoothOppPreference: {}
08-31 16:51:17.957  2034  2034 D BluetoothOppPreference: Dumping Channels:  
08-31 16:51:17.957  2034  2034 D BluetoothOppPreference: {}
08-31 16:51:17.957  2034  2034 D OppService: Start()
08-31 16:51:17.957  2034  2034 W BluetoothOPPServiceJni: initOppNative
08-31 16:51:17.957  2034  2034 D BluetoothOPPServiceJni: initOppNative(L383): OPP
08-31 16:51:17.957  2034  2034 I bluedroid: get_profile_interface opp
08-31 16:51:17.957  2034  2034 I bt-btif : btif_op_get_interface
08-31 16:51:17.957  2034  2034 D BluetoothOPPServiceJni: initOppNative(L411): mOppCallbacksObj 2098426
08-31 16:51:17.957  2034  2034 D BluetoothOPPServiceJni: initOppNative(L413): calling OPP init
08-31 16:51:17.958  2034  2034 I bt-btif : btif_opp_init
08-31 16:51:17.958  2034  2034 D bt-btif : btif_enable_service: current services:0xa0643330
08-31 16:51:17.958  2034  2034 D BluetoothOPPServiceJni: initOppNative(L429): OPC and OPS init Succesful
08-31 16:51:17.958  2034  2034 D BluetoothOPPServiceJni: initOppNative(L430): mOppCallbacksObj 2098426
08-31 16:51:17.959  2034  2034 V OppService: setOppService(): set to: com.broadcom.bt.service.opp.OppService@ce443d0
,08-31 16:51:17.959  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
08-31 16:51:17.959  2034  2034 D HeadsetStateMachine: Proxy object connected
08-31 16:51:17.960  2034  2034 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 16:51:17.961  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - Message: 1
08-31 16:51:17.961  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
08-31 16:51:17.961  2034  2034 D BluetoothAdapterService(1070426906): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 16:51:17.961  2034  2034 D BluetoothAdapterState: isTurningOnRadio()=false
08-31 16:51:17.961  2034  2034 D BluetoothAdapterState: isTurningOffRadio()=false
08-31 16:51:17.961  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
08-31 16:51:17.961  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
08-31 16:51:17.962  2034  2034 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
08-31 16:51:17.962  2034  6051 V OppService: pendingUpdate is :  true
08-31 16:51:17.964  2034  2034 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
08-31 16:51:17.965  2034  6031 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 16:51:17.965  2034  6031 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 16:51:17.965  2034  2034 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 16:51:17.965  2034  6031 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 16:51:17.966  2034  2034 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:17.966  2034  2034 V BluetoothPbapReceiver: ***********state = 11
08-31 16:51:17.971  2034  2034 D BluetoothA2dp: Proxy object connected
08-31 16:51:17.971  2034  2034 D LGBluetoothPowerControlManager: [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@2c4d9ef
,08-31 16:51:17.971  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - Message: 1
08-31 16:51:17.971  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
08-31 16:51:17.971  2034  2034 D BluetoothAdapterService(1070426906): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 16:51:17.971  2034  2034 D BluetoothAdapterState: isTurningOnRadio()=false
08-31 16:51:17.971  2034  2034 D BluetoothAdapterState: isTurningOffRadio()=false
08-31 16:51:17.971  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
08-31 16:51:17.971  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
08-31 16:51:17.971  2034  2034 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
08-31 16:51:17.972  2034  6051 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 16:51:17.973  2034  6048 V OppService: Deleted complete outbound shares, number =  0
08-31 16:51:17.974  2034  2034 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
08-31 16:51:17.974  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - Message: 1
08-31 16:51:17.974  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
08-31 16:51:17.974  2034  2034 D BluetoothAdapterService(1070426906): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 16:51:17.974  2034  2034 D BluetoothAdapterState: isTurningOnRadio()=false
08-31 16:51:17.974  2034  2034 D BluetoothAdapterState: isTurningOffRadio()=false
08-31 16:51:17.974  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
08-31 16:51:17.974  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
08-31 16:51:17.974  2034  2034 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
08-31 16:51:17.976  2034  2034 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
08-31 16:51:17.976  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - Message: 1
08-31 16:51:17.976  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
08-31 16:51:17.976  2034  2034 D BluetoothAdapterService(1070426906): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 16:51:17.977  2034  2034 D BluetoothAdapterState: isTurningOnRadio()=false
08-31 16:51:17.977  2034  2034 D BluetoothAdapterState: isTurningOffRadio()=false
08-31 16:51:17.977  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
08-31 16:51:17.977  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
08-31 16:51:17.977  2034  2034 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,08-31 16:51:17.980  2034  2034 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
08-31 16:51:17.980  2034  6048 V OppService: Deleted complete inbound failed shares, number = 0
08-31 16:51:17.981  2034  2034 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 16:51:17.981  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - Message: 1
08-31 16:51:17.981  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
08-31 16:51:17.981  2034  2034 D BluetoothAdapterService(1070426906): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-31 16:51:17.981  2034  2034 D BluetoothAdapterState: isTurningOnRadio()=false
08-31 16:51:17.981  2034  2034 D BluetoothAdapterState: isTurningOffRadio()=false
08-31 16:51:17.981  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
08-31 16:51:17.981  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
08-31 16:51:17.981  2034  2034 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
08-31 16:51:17.982  2034  6048 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 16:51:17.984  2034  2034 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
08-31 16:51:17.984  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - Message: 1
08-31 16:51:17.984  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
08-31 16:51:17.984  2034  2034 D BluetoothAdapterService(1070426906): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
,08-31 16:51:17.984  2034  2034 D BluetoothAdapterState: isTurningOnRadio()=false
08-31 16:51:17.984  2034  2034 D BluetoothAdapterState: isTurningOffRadio()=false
08-31 16:51:17.984  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
08-31 16:51:17.984  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
08-31 16:51:17.985  2034  2034 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
08-31 16:51:17.986  2034  6048 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2611ccfc on behalf of 
,08-31 16:51:17.988   959  2065 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6052 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
08-31 16:51:17.991   959  1058 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 16:51:17.994   959  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:17.994   959  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:17.996   959  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:17.996   959  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:17.997   287  1045 E BandwidthController: [LG DATA] No such appUid: 1000
08-31 16:51:17.997   287  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
08-31 16:51:17.997   287  6058 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
08-31 16:51:17.997   287  6058 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:17.998   287  6058 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
08-31 16:51:17.999   959  1056 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 16:51:18.018  5998  5998 E wpa_supplicant: USIM:  scard_init function
,08-31 16:51:18.020  5998  5998 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 16:51:18.021   287  1043 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
08-31 16:51:18.022   287  1043 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
08-31 16:51:18.023   287  1043 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
08-31 16:51:18.025   959  1056 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:18.025   959  1056 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:18.029   959  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:18.029   959  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:18.054  2034  2034 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
08-31 16:51:18.054  2034  2034 V BluetoothMapService: Handler(): got msg=1
,08-31 16:51:18.057  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - Message: 1
08-31 16:51:18.057  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
08-31 16:51:18.057  2034  2034 D BluetoothAdapterService(1070426906): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-31 16:51:18.057  2034  2034 D BluetoothAdapterState: isTurningOnRadio()=false
08-31 16:51:18.057  2034  2034 D BluetoothAdapterState: isTurningOffRadio()=false
08-31 16:51:18.057  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
08-31 16:51:18.057  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
08-31 16:51:18.057  2034  2034 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
08-31 16:51:18.058  2034  6051 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28f13f85 on behalf of 
08-31 16:51:18.059  2034  6051 V BluetoothOppNotification: update too frequent, put in queue
08-31 16:51:18.060  2034  2034 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
08-31 16:51:18.060  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - Message: 1
08-31 16:51:18.060  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
08-31 16:51:18.060  2034  2034 D BluetoothAdapterService(1070426906): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
08-31 16:51:18.060  2034  2034 D BluetoothAdapterState: isTurningOnRadio()=false
08-31 16:51:18.060  2034  2034 D BluetoothAdapterState: isTurningOffRadio()=false
08-31 16:51:18.060  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
08-31 16:51:18.060  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
08-31 16:51:18.060  2034  2034 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
08-31 16:51:18.061  2034  6051 V OppService: pendingUpdate is :  false
08-31 16:51:18.063  2034  2034 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
08-31 16:51:18.064  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - Message: 1
08-31 16:51:18.064  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
08-31 16:51:18.064  2034  2034 D BluetoothAdapterService(1070426906): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
08-31 16:51:18.064  2034  2034 D BluetoothAdapterState: isTurningOnRadio()=false
08-31 16:51:18.064  2034  2034 D BluetoothAdapterState: isTurningOffRadio()=false
08-31 16:51:18.064  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
08-31 16:51:18.064  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
08-31 16:51:18.064  2034  2034 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
08-31 16:51:18.065  2034  6051 E OppService: UpdateThread is Completed
,08-31 16:51:18.068  2034  2034 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
08-31 16:51:18.068  2034  2034 V BluetoothOppNotification: new notify threadi!
08-31 16:51:18.068  2034  2034 V BluetoothOppNotification: send delay message
08-31 16:51:18.069  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - Message: 1
08-31 16:51:18.069  2034  2034 D BluetoothAdapterService(1070426906): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
08-31 16:51:18.069  2034  2034 D BluetoothAdapterService(1070426906): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
08-31 16:51:18.069  2034  2034 D BluetoothAdapterState: isTurningOnRadio()=false
08-31 16:51:18.069  2034  2034 D BluetoothAdapterState: isTurningOffRadio()=false
08-31 16:51:18.069  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
08-31 16:51:18.069  2034  2034 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
08-31 16:51:18.069  2034  2034 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
08-31 16:51:18.069  2034  2034 D BluetoothAdapterService(1070426906): onProfileServiceStateChange() - All profile services started.
08-31 16:51:18.069  2034  2034 V OppService: ContentObserver received notification
08-31 16:51:18.069  2034  2034 V OppService: ContentObserver received notification
08-31 16:51:18.070  2034  2180 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 16:51:18.070  2034  2180 I bluedroid: enable
08-31 16:51:18.070  2034  2180 I bt-btif : BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
08-31 16:51:18.070  2034  2180 E bt-btu  : VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
08-31 16:51:18.073  2034  6067 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 16:51:18.074  2034  6069 V OppService: pendingUpdate is :  true
08-31 16:51:18.074  2034  6069 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 16:51:18.074  2034  2180 I bt_hci_bdroid: init
08-31 16:51:18.074  2034  6070 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 16:51:18.074  2034  2180 I bt_vendor: init
,08-31 16:51:18.074  2034  6070 I bt-btu  : btu_task pending for preload complete event
08-31 16:51:18.075  2034  2180 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 16:51:18.075  2034  6069 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15f0c1da on behalf of 
08-31 16:51:18.075  2034  2180 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
08-31 16:51:18.076  2034  6067 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b2f260b on behalf of 
08-31 16:51:18.077  2034  2180 I bt-btif : libbt-hci init returns 0
,08-31 16:51:18.083  2034  6067 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 16:51:18.084  2034  6069 V OppService: pendingUpdate is :  false
08-31 16:51:18.084  2034  6069 E OppService: UpdateThread is Completed
08-31 16:51:18.084  2034  6067 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 16:51:18.086  2034  6067 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@82cbce8 on behalf of 
08-31 16:51:18.086  2034  6067 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 16:51:18.087  6009  6009 D BluetoothPermissionRequest: onReceive
08-31 16:51:18.087  2034  6067 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
08-31 16:51:18.088  2034  6067 V BluetoothOppNotification: outbound notification was removed.
08-31 16:51:18.088  2034  6067 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 16:51:18.088  6009  6009 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-31 16:51:18.089  2034  6067 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@200b4f01 on behalf of 
08-31 16:51:18.090  2034  6067 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 16:51:18.091  2034  6067 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
,08-31 16:51:18.092  2034  6067 V BluetoothOppNotification: inbound notification was removed.
08-31 16:51:18.092  2034  6067 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 16:51:18.093  2034  6067 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32a921a6 on behalf of 
,08-31 16:51:18.108  5998  5998 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-31 16:51:18.122  5998  5998 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 16:51:18.122   959  1058 D BluetoothManagerService: Message: 20
,08-31 16:51:18.123   959  1058 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e3990d5:true
,08-31 16:51:18.132   959  1310 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
08-31 16:51:18.137   959  1310 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-31 16:51:18.139   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.140   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.140  2034  2034 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 16:51:18.142  2034  2034 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:18.144   959   959 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 16:51:18.145  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:18.146  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:18.145 DNS addrs= 0.0.0.0, 0.0.0.0, 
08-31 16:51:18.146  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
08-31 16:51:18.148   959   959 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
08-31 16:51:18.148  5843  5843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:18.148  5843  5843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:18.148  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:18.148  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:51:18.148  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:18.148  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:51:18.148  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:18.148  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:18.148  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:51:18.149  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:18.149  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:18.149  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
,08-31 16:51:18.150  5843  5843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:18.150  5843  5843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:51:18.154  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
08-31 16:51:18.162   959  1314 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 16:51:18.162  2034  6073 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
08-31 16:51:18.166  2034  6073 D bt_userial_vendor: userial_vendor_open():UART is setup
08-31 16:51:18.166  2034  6073 I bt_userial_vendor: device fd = 68 open
,08-31 16:51:18.178  2034  6073 D bt_hwcfg: hw_config_cback opcode:0x0c03
08-31 16:51:18.178  2034  6073 D bt_hwcfg: hw_config_cback state=1
08-31 16:51:18.184   959  1310 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 16:51:18.188   959  1350 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6079 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
08-31 16:51:18.189   959  1310 D WifiStateMachine: enableVerboseLogging : level 2
08-31 16:51:18.193   959  1310 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 16:51:18.194   959  1310 D WifiNative-HAL: Setting external_sim to 1
08-31 16:51:18.194   959  1310 I WifiNative-HAL: startHal
08-31 16:51:18.194   959  1310 E wifi    : getStaticLongField sWifiHalHandle 0x9b5258ec
08-31 16:51:18.194   959  1310 I WifiHAL : Initializing wifi
08-31 16:51:18.194   959  1310 I WifiHAL : Creating socket
08-31 16:51:18.196   959  1310 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-31 16:51:18.197   959  1310 D wifi    : Did set static halHandle = 0x9db3d900
,08-31 16:51:18.197   959  1310 D wifi    : halHandle = 0x9db3d900, mVM = 0xb487c280, mCls = 0x501b5a
08-31 16:51:18.197   959  1310 E wifi    : getStaticLongField sWifiHalHandle 0x9b52589c
08-31 16:51:18.197   959  1310 D wifi    : array field set
08-31 16:51:18.197   959  1310 I WifiNative-HAL: interface[0] = wlan0
08-31 16:51:18.197   959  1310 I WifiNative-HAL: interface[1] = p2p0
08-31 16:51:18.198   959  1310 D wifi    : setting scan oui 0x9da13628
08-31 16:51:18.199   959  1310 D WifiHAL : Sending mac address OUI
08-31 16:51:18.199   959  1310 E WifiHAL : failed to set scanning mac OUI; result = -95
08-31 16:51:18.200   959  1310 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 16:51:18.200   959  1310 I WifiNative-HAL: startHal
08-31 16:51:18.200   959  1310 D wifi    : setting scan oui 0x9da13628
08-31 16:51:18.200   959  1310 D WifiHAL : Sending mac address OUI
08-31 16:51:18.200   959  1310 E WifiHAL : failed to set scanning mac OUI; result = -95
08-31 16:51:18.201   959  6085 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1649157888
08-31 16:51:18.201   959  6085 D wifi    : waitForHalEvents called, vm = 0xb487c280, obj = 0x501b5a, env = 0xaaf214a0
08-31 16:51:18.201   959  6085 E wifi    : getStaticLongField sWifiHalHandle 0x99558b2c
08-31 16:51:18.204  2034  6073 D bt_hwcfg: hw_config_cback opcode:0x0c14
08-31 16:51:18.204  2034  6073 D bt_hwcfg: hw_config_cback state=4
08-31 16:51:18.204  2034  6073 D bt_hwcfg: Chipset Name: BCM4334B0
,08-31 16:51:18.204  2034  6073 D bt_hwcfg: Chipset BCM4334B0
08-31 16:51:18.204  2034  6073 D bt_hwcfg: Target name = [BCM4334B0]
08-31 16:51:18.205  2034  6073 I bt_hwcfg: Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
08-31 16:51:18.206   959   959 D WifiHS20: hidePasspointNotification off =false
08-31 16:51:18.209   959  1309 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.209   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.209   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.209   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 16:51:18.210  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc45
08-31 16:51:18.210  2034  6073 D bt_hwcfg: hw_config_cback state=2
,08-31 16:51:18.211   959  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:18.211   959  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:18.212   287  1050 D CommandListener: Setting iface cfg
08-31 16:51:18.212   287  1050 D CommandListener: Trying to bring up p2p0
08-31 16:51:18.212   959  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 16:51:18.213   959  1309 D LGWifiP2pService: P2pEnablingState
08-31 16:51:18.213   959  1309 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.214   959   959 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 16:51:18.214   959   959 D RttService: SCAN_AVAILABLE : 3
08-31 16:51:18.214   959  1330 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.214   959  1330 I WifiNative-HAL: startHal
08-31 16:51:18.214   959  1331 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.214   959  1330 D wifi    : getting scan capabilities on interface[0] = 0x9da13628
08-31 16:51:18.214   959  1330 D WifiHAL : Creating message to get scan capablities; iface = 24
08-31 16:51:18.215   959  1330 D wifi    : failed to get capabilities : -95
08-31 16:51:18.215   959  1330 E WifiScanningService: could not get scan capabilities
08-31 16:51:18.215  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc18
08-31 16:51:18.215  2034  6073 D bt_hwcfg: hw_config_cback state=3
08-31 16:51:18.215  2034  6073 I bt_hwcfg: bt vendor lib: set UART baud 4000000
08-31 16:51:18.217   959  1310 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
08-31 16:51:18.218   959  1310 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 16:51:18.219   959  1309 D LGWifiP2pService: P2p socket connection successful
08-31 16:51:18.219   959  1309 D LGWifiP2pService: P2pEnabledState
08-31 16:51:18.222   959  1309 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 16:51:18.222   959  1309 D LGWifiP2pService: before postfix = G3s-1
08-31 16:51:18.222   959  1309 D WifiServerServiceExt: postfix byte check : 5
,08-31 16:51:18.225  5998  5998 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 16:51:18.227   959  1310 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 16:51:18.227  5998  5998 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 16:51:18.228   959  1309 D LGWifiP2pService: after postfix = G3s-1
08-31 16:51:18.230   959  1309 D WifiNative-HAL: p2pGetDeviceAddress
08-31 16:51:18.230   959  1309 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-31 16:51:18.230   959  1309 E LGWifiP2pService: p2pGetDeviceAddress NULL retry=1
08-31 16:51:18.230   959  1309 D WifiNative-HAL: p2pGetDeviceAddress
08-31 16:51:18.231   959  1309 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
08-31 16:51:18.232   959  1310 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
08-31 16:51:18.232  5998  5998 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
08-31 16:51:18.233   959  1309 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
08-31 16:51:18.235   959  1310 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
,08-31 16:51:18.243  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc2e
08-31 16:51:18.243  2034  6073 D bt_hwcfg: hw_config_cback state=5
08-31 16:51:18.243  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:18.244  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:18.248  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:18.249  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:18.249  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
08-31 16:51:18.249  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
,08-31 16:51:18.253  5737  5737 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.255  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:18.255 DNS addrs= 0.0.0.0, 0.0.0.0, 
08-31 16:51:18.256  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
08-31 16:51:18.260  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:18.260  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
,08-31 16:51:18.264  6052  6052 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 16:51:18.265  1806  1806 D WfdsService: Supplicant Connection state is changed : true
08-31 16:51:18.266  1806  1806 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 16:51:18.266  1806  2130 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 16:51:18.266  1806  2130 D WfdsService: Set the WFDS Monitor: true
08-31 16:51:18.272  1806  2130 D WfdsMonitor: WfdsMonitorThread create
08-31 16:51:18.273  1806  2130 D WfdsMonitor: WFDS Monitor is created and started
08-31 16:51:18.273  1806  2130 D WfdsService: WiFi: Supplicant connection re-established
,08-31 16:51:18.285  1806  1806 D WfdsService: Update P2p Interface State: 3
08-31 16:51:18.286   959  1309 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 16:51:18.287  1806  6100 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-31 16:51:18.287   959  1309 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 16:51:18.288  1806  6100 E CtrlSupplicant: Succeed to open control connection
08-31 16:51:18.288  1806  6100 E CtrlSupplicant: Succeed to open monitor connection
08-31 16:51:18.290   959  1309 D LGWifiP2pService: InactiveState
08-31 16:51:18.291  1806  1806 D WfdsService: WifiP2pState is changed : true
08-31 16:51:18.292  1806  2130 D WfdsService: Receive the WFDS_ENABLE Method
08-31 16:51:18.292  1806  2130 D WfdsService: Set the WFDS Monitor: true
08-31 16:51:18.292  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
08-31 16:51:18.292  1806  2130 D WfdsService: Connected to the supplicant for wfds
08-31 16:51:18.292  1806  2130 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 16:51:18.292   959  1309 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.294   959  1309 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.295  1806  1806 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 16:51:18.295   959  1309 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.295   959  1309 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.295   959  1309 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.296   959  1309 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.297  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.297  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.298   959   959 E WifiServerServiceExt: No p2p device connected
08-31 16:51:18.298  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.299  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.300  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.300  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.302  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.302  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.304  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.304  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.305   959  1309 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.305   959  1309 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.305   959  1309 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.306  1806  1806 D WfdsService: isConnected: false
08-31 16:51:18.306  1806  1806 D WfdsService: GroupInfoAvailable: mGroupInfo is null
08-31 16:51:18.306   959  1309 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.306   959  1309 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.306   959  1309 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.306  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.306  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.307  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.307  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.308  5998  5998 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 16:51:18.308  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.308  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.309  1806  6100 D WfdsMonitor: Supplicant connection established
08-31 16:51:18.311  5998  5998 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz)
08-31 16:51:18.311  6009  6009 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 16:51:18.311  6009  6009 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 16:51:18.312  6009  6009 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 16:51:18.312  6009  6009 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 16:51:18.312  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.312  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.313  6009  6009 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 16:51:18.313  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.313  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.314  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.315  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.316  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.316  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.317  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.317  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.318  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.318  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.319  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.319  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.319  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.320  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.320  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.320  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.321  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.321  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.322  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.322  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.323  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.323  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.324  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.324  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.325  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.325  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.326  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.326  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.327  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.327  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.328  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.328  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.330  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.330  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.330  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.331  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.331  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.331  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.332  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.332  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.334  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.334  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.335  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.335  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.335  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.336  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.336  6079  6079 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 16:51:18.336  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.336  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.337  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.338  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.338  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.338  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.339  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.339  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.341  5998  5998 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 16:51:18.341  1806  2130 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
,08-31 16:51:18.342  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.342  5998  5998 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-31 16:51:18.342  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.342  1806  2130 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
08-31 16:51:18.342  5998  5998 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
08-31 16:51:18.343  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.343  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.343  1806  2130 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
08-31 16:51:18.343  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.344  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.344  1806  2130 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-31 16:51:18.344  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.344  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.344  1806  2130 D WfdsService: selectPreferredScanChannel [6]
08-31 16:51:18.344  1806  2130 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
08-31 16:51:18.344  1806  2130 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 16:51:18.344  1806  2130 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-31 16:51:18.344  1806  2130 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 16:51:18.345  5998  5998 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 16:51:18.345  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.345  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.346  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.346  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.347  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.347  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.347  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.348  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.348  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.348  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.349  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.349  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.349  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.349  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.350  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.350  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.351  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.351  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.351  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.351  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.352  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.352  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.352  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.352  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.353  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.353  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.354  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.354  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.355  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.355  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.356  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.356  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.356  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,08-31 16:51:18.357  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.357  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.357  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.358  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.358  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.359  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.359  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.360  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.360  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.361  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.361  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.362  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.362  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.362  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:18.363  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.363  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.363   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.363  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:18.363 DNS addrs= 0.0.0.0, 0.0.0.0, 
08-31 16:51:18.363   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.363   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 16:51:18.364  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:18.365  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.365  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.365  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
08-31 16:51:18.366  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.366  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.366  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.366  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.366   959   959 D LocSvc_java: onReceive
08-31 16:51:18.367  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.367  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.368  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.368  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.368  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.368  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.369  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.369  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.370  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.371  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.371  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.371  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.372  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.372  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.373  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.373  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.374  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:18.374  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.374  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.374  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:18.375   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.375   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.375   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 16:51:18.375  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.375  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.375  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.375  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.376  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.376  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.377  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.377  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.378   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.378  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.378  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.378   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.378   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 16:51:18.379  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.379  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.379  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:18.379  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:18.379 DNS addrs= 0.0.0.0, 0.0.0.0, 
08-31 16:51:18.379  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.380  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.380  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.380  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.381   959   959 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:18.381   959   959 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 16:51:18.381  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.381  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.383  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
08-31 16:51:18.383  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
08-31 16:51:18.383  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:18.383  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
08-31 16:51:18.383  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:18.386  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
08-31 16:51:18.387  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.387  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.388  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:18.388  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.388   959   959 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:18.388  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.388   959   959 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 16:51:18.389  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.389  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.389  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:18.390  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:18.390  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
08-31 16:51:18.390  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
08-31 16:51:18.390  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:18.390  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
08-31 16:51:18.390  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:18.390  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.390  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.394  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:18.394  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:18.394  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.394  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.394  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
08-31 16:51:18.394  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
08-31 16:51:18.394  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:18.394  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
08-31 16:51:18.395  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.395  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.396  1753  1753 D GONS    : GONS isTestMode: false Country: 
08-31 16:51:18.397  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.397  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.398  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.399  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.399   287  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
08-31 16:51:18.399   287  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
08-31 16:51:18.400   287  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
08-31 16:51:18.400  5998  5998 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 16:51:18.400  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.400  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.401  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.401  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.401  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.401  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.402  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.402  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.402  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.402  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.403  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.403  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.404   959   959 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:18.404   959   959 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-31 16:51:18.406  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.406  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.408  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.408  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.409  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.409  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.409  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:18.409 DNS addrs= 0.0.0.0, 0.0.0.0, 
08-31 16:51:18.409  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
08-31 16:51:18.410  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.410  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.410  6009  6009 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 16:51:18.410  6009  6009 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 16:51:18.411  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.411  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.411  6009  6009 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 16:51:18.411  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.411  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.411  6009  6009 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 16:51:18.412  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:18.412  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.412  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.412  6009  6009 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 16:51:18.413  6009  6009 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 16:51:18.413  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.413  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.414  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:18.414   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.415  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.415   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.415  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.415   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-31 16:51:18.416  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.416  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.417  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.417  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.418  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.418  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.419  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.419  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.420  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.420  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.420   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.420   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.420   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 16:51:18.420   959   959 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:18.421   959   959 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 16:51:18.421  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.421  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.421  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:18.421 DNS addrs= 0.0.0.0, 0.0.0.0, 
08-31 16:51:18.421  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
08-31 16:51:18.421  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:18.422  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:18.422  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.422  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.423  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:18.422 DNS addrs= 0.0.0.0, 0.0.0.0, 
08-31 16:51:18.423  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
08-31 16:51:18.423  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:18.423  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
08-31 16:51:18.423  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
08-31 16:51:18.424  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:18.424  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
08-31 16:51:18.424  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:18.425  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.425  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.427  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.427  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.428  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,08-31 16:51:18.428  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.428  5998  5998 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 16:51:18.428  5998  5998 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 16:51:18.430   287  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
08-31 16:51:18.431  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.431  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.433  6079  6079 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
08-31 16:51:18.433   959   959 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:18.433   959   959 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 16:51:18.434  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.434  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.435  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.435  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.436  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:18.436  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:18.436  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
08-31 16:51:18.436  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.436  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.436  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
08-31 16:51:18.436  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:18.436  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
08-31 16:51:18.437  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.437  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.438  6009  6009 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 16:51:18.438  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.438  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.439  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.439  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.440   959  1310 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 16:51:18.442  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.442  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.442  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:18.443  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.443  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.444  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.444  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.445  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.445  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.446  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.446  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.447  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.447  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.447  6009  6009 D WiFiOffLoadUpdatePriority: remove : truetruetrue
08-31 16:51:18.447  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.447  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.448  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.448  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.448  1735  1735 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-31 16:51:18.449  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.449  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.450  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.450  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.451  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.451  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.452  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.452  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.453  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.453  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.454  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.454  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.455  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.455  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.456  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.456  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.456  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.457  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.457  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.457  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.458  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.458  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.459  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.459  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.459  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.459  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.460  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.460  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.461  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.461  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.462  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.462  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.463  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.463  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.464  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.464  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.464  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.465  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.465   959  1310 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 16:51:18.465   959  1310 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
08-31 16:51:18.465  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,08-31 16:51:18.465  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.466  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.467  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.467   959  1310 I WifiServiceExtension: setSecurityType  : 2
08-31 16:51:18.467  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.468  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.468  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.468  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.469  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.469  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.470  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.470  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.471  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.471  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.472  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.472  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.473  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.473  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.474  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.474  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.475  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.475  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.476  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.476  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.476  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.476  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.476  1735  1735 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-31 16:51:18.477  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.477  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.477  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.477  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.478  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.478  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.479  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.479  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.479  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.479  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.480  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.480  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.480  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.480  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.481  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.481  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.482  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.482  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.482  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.482  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.482  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.483  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.483  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.483  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.484  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.484  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.484  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.484  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.485   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.485   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.485  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.485   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 16:51:18.485  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.485   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.485   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:18.485   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 16:51:18.486  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.486  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.486  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.486  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.486  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:18.487  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.487  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.487  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:18.487  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.487  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.488  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.488  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.488  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:18.488 DNS addrs= 0.0.0.0, 0.0.0.0, 
08-31 16:51:18.488  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
08-31 16:51:18.489  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:18.489  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.489  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.489  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.489  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.489  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:18.489 DNS addrs= 0.0.0.0, 0.0.0.0, 
08-31 16:51:18.489  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
08-31 16:51:18.490  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.490  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.490  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.490  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.491  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.491  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.492  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.492  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.492  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:18.492  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:18.492  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.492  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.492  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
08-31 16:51:18.493  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
08-31 16:51:18.493  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.493  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.493  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:18.493  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
08-31 16:51:18.493  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:18.494  2034  6073 D bt_hwcfg: hw_config_cback opcode,:0xfc4c
08-31 16:51:18.494  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.494  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.494  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.495  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.495  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.496  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.496  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.496  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.496  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.496  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:18.496  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:18.497  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
08-31 16:51:18.497  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
08-31 16:51:18.497  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:18.497  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
08-31 16:51:18.497  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.497  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.498  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.498  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.499  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.499  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.500  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.500  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.501  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.501  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.502  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.502  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.503  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.503  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.504  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.504  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.505  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.505  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.506  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.506  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.507  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.507  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.507  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.507  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.507   959  6105 D WifiExtManager: WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@68f35bc
08-31 16:51:18.508   959  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 16:51:18.508  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.508  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.508   959  1316 D ConnectivityService: Got NetworkAgent Messenger
08-31 16:51:18.508  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.508  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.509  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.509  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.509   959  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 16:51:18.510   959  1316 D ConnectivityService: NetworkAgent connected
08-31 16:51:18.510  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.510  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.511  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.511  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.512  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.512  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.513  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.513  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.513  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.513  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.514  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.514  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.515  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.515  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.516  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.516  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.517  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.517  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.518  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.518  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.519  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.519  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.519  1806  1822 D WifiServiceExtension: isInternetCheckAvailable return false
08-31 16:51:18.519   959  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 16:51:18.520  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.520  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.521  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.521  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.523  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.523  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.523  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.523  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.524  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.524  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.525  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.525  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.526  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.526  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.527  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.527  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.528  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.528  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.529  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.529  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.530  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.530  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.530   959  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 16:51:18.530  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.530  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.531  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.531  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.532  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.532  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.533  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.533  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.534  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.534  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.535  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.535  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.535  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.536  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.536  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.536  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.537  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.537  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.538  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.538  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.539  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.539  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.539  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.539  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.540  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.540  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.540   287  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
08-31 16:51:18.541   959  1056 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:18.541  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.541   959  1056 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:18.541  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.541  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.541  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.542  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.542  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.542   959  1310 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:18.542   959  1310 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:18.543   287  1050 D CommandListener: Setting iface cfg
08-31 16:51:18.543  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.543  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.544  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.544  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.545  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.545  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.546  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.546  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.547  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.547  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.548  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.548  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.548   959  1310 E WifiStateMachine: Start Dhcp Watchdog 1
08-31 16:51:18.549  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.549  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.550  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.550  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.550  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.551  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.551   959  6106 D DhcpStateMachine: StoppedState
08-31 16:51:18.551  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.551  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.552   959  6106 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.552   959  6106 D DhcpStateMachine: WaitBeforeStartState
08-31 16:51:18.552  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.552  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.553  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.553  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.554  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.554  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.556  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.556  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.557  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.557  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.558  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.558  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.559  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,08-31 16:51:18.559  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.559  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.559  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.561  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.561  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.561  1841  1841 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
08-31 16:51:18.562  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.562  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.562  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:18.561 DNS addrs= 0.0.0.0, 0.0.0.0, 
08-31 16:51:18.562  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.562  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.563  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.563  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.564  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.564  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.564  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.564  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.564  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:18.565  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:18.565  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
08-31 16:51:18.565  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.565  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.566  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.566  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.567  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.567  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.568  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.568  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.568  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.568  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.569   959  1316 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,08-31 16:51:18.569  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.569  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.570  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.570  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.571  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.571  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.572  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.572  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.572   959   959 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:18.572   959   959 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 16:51:18.573  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.573  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.574  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.574  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.575  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.575  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.575  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.575   959   959 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 16:51:18.575  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.575   959   959 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 16:51:18.576  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.576  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.577  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.577  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.579  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.579  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.580  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.580  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.581  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.581  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.582  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.582  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.583  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.583  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.583  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.583  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.584  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.584  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.584  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.584  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.585  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.585  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.586  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.586  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.587  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.587  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.588  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.588  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.589  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.589  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.590  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.590  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.590  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.591  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.591  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.591  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.592  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.592  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.592  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.592  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.593  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c,
08-31 16:51:18.593  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.594  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.594  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.595  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.595  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.596  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,08-31 16:51:18.596  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.597  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.597  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.598  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.598  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.599  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.599  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.600  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.600  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.601  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c,
08-31 16:51:18.601  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.602  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.602  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.603  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.603  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.604  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.604  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.605  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.605  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.606  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.606  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.607  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.607  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.607  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.607  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.608  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.608  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.608  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.608  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.608  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.608  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.609  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.609  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.610  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.610  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.610  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.610  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.611  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.611  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.611  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.611  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.611  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.611  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.612  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.612  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.612  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.612  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.613  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.613  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.613  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.613  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.613  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.614  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.614  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.614  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.614  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.614  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.615  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.615  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.615  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.615  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.616  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.616  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.616  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.616  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.617  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.617  2034  6073 D bt_hwcfg: hw_config_cback state=6
,08-31 16:51:18.617  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.617  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.617  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.617  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.618  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.618  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.618  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.618  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.618  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.618  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.619  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.619  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.619  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.619  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.620  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.620  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.620  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.620  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.621  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.621  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.621  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.621  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.622  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.622  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.622  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.622  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.623  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4c
08-31 16:51:18.623  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.623  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc4e
08-31 16:51:18.623  2034  6073 D bt_hwcfg: hw_config_cback state=6
08-31 16:51:18.654   959  1310 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 16:51:18.654   959  1309 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bc41db5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.654   959  1309 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bc41db5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:18.654   959  1310 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 16:51:18.654   959  6106 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 16:51:18.655   959  1310 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 16:51:18.655   959  1310 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-31 16:51:18.656   959  6106 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 16:51:18.667  6009  6009 D WiFiOffLoadUpdatePriority: remove1
08-31 16:51:18.667  6009  6009 V WiFiOffLoadSharedPrefsUtils: save remove
,08-31 16:51:18.677  6009  6009 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
08-31 16:51:18.677  6009  6009 D WiFiOffLoadBroadcast: S: false, R: false
08-31 16:51:18.684  6009  6009 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
,08-31 16:51:18.684  6009  6009 D WiFiOffLoadUpdatePriority: connected SSID: null
08-31 16:51:18.684  6009  6009 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
08-31 16:51:18.687   959  1640 D WifiServiceImplEx: addOrUpdateNetwork pid=6009, uid=1000, packageName=android.uid.system:1000
08-31 16:51:18.688   959  1640 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
08-31 16:51:18.689   959  1310 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
08-31 16:51:18.698   959  1061 I PowerManagerService: ALS enabled for SRE
08-31 16:51:18.698   959  1061 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27606 ms ago)
,08-31 16:51:18.715   959  1351 D qdlights: set_light_backlight: 253
,08-31 16:51:18.723  2034  6073 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-31 16:51:18.723  2034  6073 D bt_hwcfg: Settlement delay -- 100 ms
08-31 16:51:18.723  2034  6073 I bt_hwcfg: Setting fw settlement delay to 100 
08-31 16:51:18.730   959  1351 D qdlights: set_light_backlight: 250
,08-31 16:51:18.738   959  1310 E WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
08-31 16:51:18.746   959  1351 D qdlights: set_light_backlight: 246
,08-31 16:51:18.748  6009  6009 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
08-31 16:51:18.748  6009  6009 D WiFiOffLoadUpdatePriority: configuration updated: 0
08-31 16:51:18.749   959  1310 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
08-31 16:51:18.759  6009  6009 D WiFiOffLoadUpdatePriority: configuration saved: true
,08-31 16:51:18.762  6052  6052 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 16:51:18.763   959  1383 I ActivityManager: Killing 5479:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
08-31 16:51:18.763   959  1351 D qdlights: set_light_backlight: 243
08-31 16:51:18.779   959  1351 D qdlights: set_light_backlight: 240
,08-31 16:51:18.796   959  1351 D qdlights: set_light_backlight: 236
,08-31 16:51:18.813   959  1351 D qdlights: set_light_backlight: 233
,08-31 16:51:18.828  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc45
08-31 16:51:18.828  2034  6073 D bt_hwcfg: hw_config_cback state=2
,08-31 16:51:18.830   959  1351 D qdlights: set_light_backlight: 230
08-31 16:51:18.833  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc18
08-31 16:51:18.833  2034  6073 D bt_hwcfg: hw_config_cback state=7
08-31 16:51:18.833  2034  6073 I bt_hwcfg: bt vendor lib: set UART baud 4000000
08-31 16:51:18.833  2034  6073 I bt_hwcfg: Setting local bd addr to F8:95:C7:87:85:54
08-31 16:51:18.846   959  1351 D qdlights: set_light_backlight: 226
,08-31 16:51:18.853   959  1787 W libprocessgroup: failed to open /acct/uid_10069/pid_5479/cgroup.procs: No such file or directory
08-31 16:51:18.856  2034  6073 D bt_hwcfg: hw_config_cback opcode:0xfc01
08-31 16:51:18.856  2034  6073 D bt_hwcfg: hw_config_cback state=8
08-31 16:51:18.856  2034  6073 I bt_hwcfg: vendor lib fwcfg completed
08-31 16:51:18.856  2034  6073 I bt-btif : HC preload_cb 0 [0:SUCCESS 1:FAIL]
08-31 16:51:18.856  2034  6070 I bt-btu  : btu_task received preload complete event
08-31 16:51:18.859   959  6106 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 16:51:18.860   959  6106 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 16:51:18.860   959  6106 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_HCI,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_L2CAP,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_RFCOMM,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_OBEX,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_AVCT,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_AVDT,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_AVRC,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_AVDT_SCB,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_A2D,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_BNEP,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_BTM,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_GAP,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_PAN,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_SAP,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_SDP,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_GATT,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_SMP,2
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_BTAPP,3
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_BTIF,3
08-31 16:51:18.863  2034  6070 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,0
08-31 16:51:18.865   959  1351 D qdlights: set_light_backlight: 223
08-31 16:51:18.876  6110  6110 I dhcpcd  : version 5.5.6 starting
08-31 16:51:18.878  6110  6110 E dhcpcd  : get_duid: Read-only file system
,08-31 16:51:18.880   959  1351 D qdlights: set_light_backlight: 220
08-31 16:51:18.897   959  1351 D qdlights: set_light_backlight: 216
,08-31 16:51:18.909   959  1879 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6113 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
08-31 16:51:18.913   959  1351 D qdlights: set_light_backlight: 213
08-31 16:51:18.952   959  1351 D qdlights: set_light_backlight: 206
,08-31 16:51:18.965  6110  6110 I dhcpcd  : wlan0: rebinding lease of 192.168.1.109
,08-31 16:51:18.967   959  1351 D qdlights: set_light_backlight: 203
08-31 16:51:18.980   959  1351 D qdlights: set_light_backlight: 200
,08-31 16:51:18.996   959  1351 D qdlights: set_light_backlight: 196
,08-31 16:51:19.004  6110  6110 I dhcpcd  : wlan0: acknowledged 192.168.1.109 from 192.168.1.1
,08-31 16:51:19.013   959  1351 D qdlights: set_light_backlight: 193
,08-31 16:51:19.026  2034  6070 E bt-btif : bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,08-31 16:51:19.028  2034  6140 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 16:51:19.028  2034  2200 E bt-btif : warning : media task started media_task_refcnt 1 
08-31 16:51:19.030   959  1351 D qdlights: set_light_backlight: 190
08-31 16:51:19.030  2034  6070 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
08-31 16:51:19.030  2034  6070 W bt-smp  : Plain text(LSB ~ MSB) = 12 d4 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 16:51:19.030  2034  6070 W bt-smp  : Encrypted text(LSB ~ MSB) = d6 c1 ba 1a da a6 5d 1f 19 5d 7d b7 39 dd 8d 9f 
,08-31 16:51:19.030  2034  6070 W bt-btm  : Stopping oneshot timer
08-31 16:51:19.030  2034  6140 D BT_PROF_AUDIO: created moving average (N=100)
08-31 16:51:19.031  2034  6140 D BT_PROF_AUDIO: reset rate average
08-31 16:51:19.031  2034  6140 W bt-btif : overflow 0, enter 0, exit 0
08-31 16:51:19.031  2034  2200 E bt-btif : Calling BTA_HhEnable
08-31 16:51:19.031  2034  2200 E bt-btif : btif_storage_get_adapter_property service_mask:0x1201c8
08-31 16:51:19.031  2034  2200 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
08-31 16:51:19.031  2034  2200 D BluetoothAdapterProperties: Address is:F8:95:C7:87:85:54
08-31 16:51:19.032  6110  6110 I dhcpcd  : wlan0: leased 192.168.1.109 for 172800 seconds
08-31 16:51:19.033   287  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
08-31 16:51:19.034   959   959 D BluetoothManagerService: Bluetooth Adapter name changed to G3s-1
08-31 16:51:19.034   959   959 D BluetoothManagerService: Stored Bluetooth name: G3s-1
08-31 16:51:19.034  2034  2200 D BluetoothAdapterProperties: Name is: G3s-1
08-31 16:51:19.035   959  1056 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:19.035   959  1056 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.036  2034  2200 D BluetoothAdapterProperties: Scan Mode:20
08-31 16:51:19.037  2034  2200 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:51:19.038  2034  2200 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-31 16:51:19.038  2034  2200 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-31 16:51:19.038  5843  5843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:51:19.038  2034  2200 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 16:51:19.038  2034  2200 I bt-btif : BTA_JvEnable
08-31 16:51:19.038  2034  2200 E bt-btif : btsock_vendor_hci_init: !vhci_init
,08-31 16:51:19.038  2034  2200 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
08-31 16:51:19.039  2034  2200 D bt-btif : init_hci_slots(L136): in
08-31 16:51:19.039  2034  2200 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-31 16:51:19.040  2034  2200 D IOP_DB_BT: db_open: db_open : handle 2690963420l, read 11046 bytes onto local cache
08-31 16:51:19.040  2034  2200 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-31 16:51:19.041  2034  2200 D IOP_DB_BT: db_query: result 1
08-31 16:51:19.041  2034  2200 I         : iop_db_open: iop_db_open status 0
08-31 16:51:19.041  2034  2200 E bt-btif : btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
08-31 16:51:19.041  2034  2200 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
08-31 16:51:19.041  2034  6070 I bt-btif : bta_pan_co_init
08-31 16:51:19.041  2034  2200 D bte_conf: Device ID record 1 : primary
08-31 16:51:19.041  2034  2200 D bte_conf:   vendorId            = 00c4
08-31 16:51:19.041  2034  2200 D bte_conf:   vendorIdSource      = 0001
08-31 16:51:19.041  2034  2200 D bte_conf:   product             = 13a1
08-31 16:51:19.041  2034  2200 D bte_conf:   version             = 1000
08-31 16:51:19.041  2034  2200 D bte_conf:   clientExecutableURL = 
08-31 16:51:19.041  2034  2200 D bte_conf:   serviceDescription  = 
08-31 16:51:19.042  2034  2200 D bte_conf:   documentationURL    = 
08-31 16:51:19.042  2034  2200 D bte_conf: bte_load_did_conf no section named DID2.
08-31 16:51:19.043  2034  2200 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
08-31 16:51:19.043  2034  2200 E bt-btif : btif_hf_upstreams_evt: wrong handle = 26465 
08-31 16:51:19.043  2034  2200 I bt-btif : HAL bt_op_callbacks->opc_state_cb
08-31 16:51:19.043  2034  2200 D BluetoothOPPServiceJni: opc_state_cb(L140):  opc_state_cb state:0
08-31 16:51:19.043  2034  2180 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 16:51:19.043  2034  2200 D OppService: onOpcStateChange()
08-31 16:51:19.043  2034  2200 I bt-btif : HAL bt_op_callbacks->ops_state_cb
08-31 16:51:19.043  2034  2180 D BluetoothAdapterProperties: ScanMode =  20
08-31 16:51:19.043  2034  2200 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:0
08-31 16:51:19.043  2034  2180 D BluetoothAdapterProperties: State =  11
08-31 16:51:19.043  2034  2034 D OppService: Recieved MESSAGE_OPC_ENABLE
08-31 16:51:19.044  2034  2034 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 16:51:19.045  2034  2180 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 16:51:19.045  2034  2180 D BluetoothAdapterProperties: Setting state to 12
08-31 16:51:19.045  2034  2180 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 16:51:19.045  2034  2180 D BluetoothAdapterService(1070426906): updateAdapterState() - Broadcasting state to 1 receivers.
08-31 16:51:19.045  2034  2200 D OppService: onOpsStateChange() :0
08-31 16:51:19.045  2034  2200 I bt-btif : HAL bt_fts_callbacks->operation_cmpl_cb
08-31 16:51:19.045  2034  2200 D BluetoothFTPServiceJni: operation_cmpl_callback(L192):  oper:3 status:0
08-31 16:51:19.045   959  1058 D BluetoothManagerService: Message: 60
08-31 16:51:19.045   959  1058 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 16:51:19.046  2034  2200 I BluetoothFTPService: onFtpServerEnabled: /storage
08-31 16:51:19.046   959  1058 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 6 receivers.
08-31 16:51:19.046  2034  2034 D OppService: Recieved MESSAGE_OPS_ENABLE
08-31 16:51:19.046  2034  2200 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 16:51:19.046  2034  2200 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
08-31 16:51:19.047  2034  2180 I BluetoothAdapterState: Entering On State
08-31 16:51:19.047  2034  2180 I BluetoothAdapterState: Entering On State from state = 11
08-31 16:51:19.047  2034  2180 D BluetoothA,dapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.047  2034  2180 D BluetoothAdapterService(1070426906): isQuetModeEnabled() - Enabled = false
08-31 16:51:19.048  2034  2200 D BluetoothAdapterProperties: Scan Mode:21
08-31 16:51:19.048  2034  2180 D BluetoothAdapterService(1070426906): autoConnect() - Initiate auto connection on BT on...
08-31 16:51:19.048  2034  2200 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
08-31 16:51:19.048  2034  2180 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 16:51:19.048  2034  2200 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:51:19.048  2034  2180 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 16:51:19.048  2034  2180 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3s-1
08-31 16:51:19.048  2034  2180 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3s-1
08-31 16:51:19.049  2034  2180 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.049  2034  2180 D BluetoothAdapterService(1070426906): isQuetModeEnabled() - Enabled = false
08-31 16:51:19.049  2034  2180 D BluetoothAdapterService(1070426906): autoConnect() - Initiate auto connection on BT on...
08-31 16:51:19.049  2034  2180 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 16:51:19.049   959  1351 D qdlights: set_light_backlight: 186
08-31 16:51:19.050   959  1058 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:51:19.050  1753  1769 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:51:19.050  1753  1768 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:51:19.051   959  1058 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 16:51:19.051  1753  2337 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:51:19.051  2034  2057 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 16:51:19.052   959  1058 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,08-31 16:51:19.052   959  1058 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 16:51:19.054   959  1316 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-31 16:51:19.056  2034  6073 D bt_h4   : vendor lib postload completed
08-31 16:51:19.057  2034  2056 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.064  1806  1806 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:19.065  5843  5843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 16:51:19.066  2034  2057 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.066   959   959 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 16:51:19.067   959  1351 D qdlights: set_light_backlight: 183
,08-31 16:51:19.070  6113  6113 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 16:51:19.071  6113  6113 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 16:51:19.073  2034  2034 V BluetoothOppNotification: new notify threadi!
08-31 16:51:19.073  2034  2034 V BluetoothOppNotification: send delay message
08-31 16:51:19.074  2034  2057 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.074  2034  6150 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 16:51:19.077  1806  2016 D LGBluetoothAPIService: Message: 1
08-31 16:51:19.077  1806  2016 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 16:51:19.080  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
08-31 16:51:19.080   959  1351 D qdlights: set_light_backlight: 180
08-31 16:51:19.080  1373  1373 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
08-31 16:51:19.081   959  1058 D BluetoothManagerService: Message: 40
08-31 16:51:19.081   959  1058 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 16:51:19.085  2034  2034 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
,08-31 16:51:19.097   959  1351 D qdlights: set_light_backlight: 176
08-31 16:51:19.102  2034  2034 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:51:19.103  2034  2034 D BluetoothMapService: STATE_ON
08-31 16:51:19.108  6009  6009 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 16:51:19.108  2034  2034 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 16:51:19.108  2034  2034 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 16:51:19.110  2034  2057 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.112  1806  1806 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 16:51:19.113   959  1351 D qdlights: set_light_backlight: 173
08-31 16:51:19.115  1806  2016 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-31 16:51:19.115  5843  5843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-31 16:51:19.116  1806  2016 D LGBluetoothAPIService: Message: 100
08-31 16:51:19.116  1806  2016 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 16:51:19.119  2034  2056 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.122  2034  6150 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3084bf94 on behalf of 
08-31 16:51:19.124  6113  6113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
08-31 16:51:19.124  5843  5843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 16:51:19.127  2034  6150 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 16:51:19.130   959  1351 D qdlights: set_light_backlight: 170
08-31 16:51:19.132   287  1043 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
08-31 16:51:19.133   959  1056 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:19.133   959  1056 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.142  6113  6113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
08-31 16:51:19.144  2034  6007 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
,08-31 16:51:19.149  2034  2034 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fcd6b1a
08-31 16:51:19.150  2034  2034 V BluetoothPbapService: Pbap Service onCreate
08-31 16:51:19.150  2034  2034 V BluetoothPbapService: Starting PBAP service
08-31 16:51:19.152  5843  5843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:19.152  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:19.152  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 16:51:19.152  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:19.152  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:51:19.152  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:19.152  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:19.152  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:51:19.153   959  1351 D qdlights: set_light_backlight: 166
08-31 16:51:19.154  2034  2034 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.155  2034  2034 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 16:51:19.156  2034  2034 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:19.156  2034  2034 V BluetoothPbapService: state: 12
08-31 16:51:19.156  2034  2034 V BluetoothMapService: Handler(): got msg=1
08-31 16:51:19.157  2034  2057 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.157  2034  2034 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 16:51:19.158  2034  2034 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 16:51:19.158  5843  5843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:51:19.158  2034  2034 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:19.158  2034  2034 V BluetoothPbapReceiver: ***********state = 12
08-31 16:51:19.160  2034  2034 V BluetoothPbapService: Handler(): got msg=1
08-31 16:51:19.161  5843  5843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:51:19.162  2034  2034 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 16:51:19.163  2034  6150 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-31 16:51:19.165  2034  6159 D BluetoothMapMasInstance: MAS initSocket()
08-31 16:51:19.165  2034  6159 D BluetoothMapMasInstance:   masId = 00
08-31 16:51:19.165  2034  6159 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 16:51:19.165  2034  6159 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 16:51:19.165  2034  6159 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 16:51:19.168  2034  6160 V BluetoothPbapService: Pbap Service initSocket
08-31 16:51:19.169   959  1351 D qdlights: set_light_backlight: 163
08-31 16:51:19.170   959  1805 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 16:51:19.172  2034  6159 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:51:19.174  2034  6150 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3935b232 on behalf of 
08-31 16:51:19.175  2034  6150 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 16:51:19.176   959  1860 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 16:51:19.179  2034  6160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:51:19.179  2034  6159 I bt-btif : BTA_JvCreateRecordByUser
08-31 16:51:19.179  2034  6070 I bt-btif : BTA_JvRfcommStartServer
08-31 16:51:19.180  2034  6159 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=0
08-31 16:51:19.180  2034  6159 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 16:51:19.180  2034  6159 D BluetoothMapMasInstance: Accepting socket connection...
08-31 16:51:19.181   959  1351 D qdlights: set_light_backlight: 160
08-31 16:51:19.181  2034  6160 I bt-btif : BTA_JvCreateRecordByUser
08-31 16:51:19.182  2034  6070 I bt-btif : BTA_JvRfcommStartServer
08-31 16:51:19.182  2034  6160 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=85 mFd=83
08-31 16:51:19.182  2034  6160 V BluetoothPbapService: Succeed to create listening socket 
08-31 16:51:19.182  2034  6160 V BluetoothPbapService: Accepting socket connection...
08-31 16:51:19.183  2034  6007 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.184  6009  6009 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 16:51:19.188   959  1058 D BluetoothManagerService: Message: 30
08-31 16:51:19.190  2034  6150 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
08-31 16:51:19.192  2034  6150 V BluetoothOppNotification: outbound notification was removed.
08-31 16:51:19.192  2034  6150 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 16:51:19.194  2034  6150 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3cd44b83 on behalf of 
08-31 16:51:19.194  2034  6150 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-31 16:51:19.196  2034  6150 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
08-31 16:51:19.197   959  1351 D qdlights: set_light_backlight: 156
08-31 16:51:19.198  6009  6009 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 16:51:19.202   959  1058 D BluetoothManagerService: Message: 30
08-31 16:51:19.206  2034  6150 V BluetoothOppNotification: inbound notification was removed.
08-31 16:51:19.207  2034  6150 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 16:51:19.208  2034  6150 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fb84100 on behalf of 
08-31 16:51:19.211   959  1058 D BluetoothManagerService: Message: 30
,08-31 16:51:19.216   959  1351 D qdlights: set_light_backlight: 153
08-31 16:51:19.217  6113  6163 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 16:51:19.218   959  1058 D BluetoothManagerService: Message: 30
08-31 16:51:19.223  6113  6169 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 16:51:19.223  6113  6169 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 16:51:19.227  6009  6009 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 16:51:19.229  6009  6009 D BluetoothMap: Create BluetoothMap proxy object
08-31 16:51:19.230   959  1351 D qdlights: set_light_backlight: 150
08-31 16:51:19.230   959  1058 D BluetoothManagerService: Message: 30
08-31 16:51:19.238   959  1058 D BluetoothManagerService: Message: 30
,08-31 16:51:19.241  2034  2034 V BluetoothPbapService: Pbap Service onBind
08-31 16:51:19.242  6009  6009 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 16:51:19.246   959  1351 D qdlights: set_light_backlight: 146
08-31 16:51:19.249  6009  6009 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-31 16:51:19.252  6009  6009 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-31 16:51:19.263  6009  6009 D DockEventReceiver: finishStartingService: stopping service
08-31 16:51:19.263   959  1351 D qdlights: set_light_backlight: 143
08-31 16:51:19.267   959  6106 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:19.267   959  6106 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-31 16:51:19.268   959  6106 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:19.268   959  6106 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.268   959  6106 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:19.268   959  6106 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.268   959  6106 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:19.268   959  6106 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.268   959  6106 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-31 16:51:19.269  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 16:51:19.270   959  6106 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
08-31 16:51:19.270   959  6106 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 16:51:19.270   959  6106 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:19.271   959  6106 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.271   959  6106 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.109
08-31 16:51:19.271   959  6106 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 16:51:19.271   959  6106 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 16:51:19.271   959  6106 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-31 16:51:19.272   959  6106 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 16:51:19.273   959  1309 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:19.273   959  6106 D DhcpStateMachine: RunningState
08-31 16:51:19.273   959  1309 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:19.275  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:19.275  6009  6009 D BluetoothA2dp: Proxy object connected
08-31 16:51:19.276  6009  6009 D A2dpProfile: Bluetooth service connected
08-31 16:51:19.279  2034  2056 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.280   959  1351 D qdlights: set_light_backlight: 140
,08-31 16:51:19.280  6009  6009 D BluetoothHeadset: Proxy object connected
08-31 16:51:19.282  6009  6009 D HeadsetProfile: Bluetooth service connected
08-31 16:51:19.282   959  1316 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-31 16:51:19.282  2034  2057 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.283  6009  6009 D BluetoothInputDevice: Proxy object connected
08-31 16:51:19.284   959  1310 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 16:51:19.284  6009  6009 D HidProfile: Bluetooth service connected
08-31 16:51:19.284   959  1316 D ConnectivityService: ignoring duplicate network state non-change
08-31 16:51:19.285  2034  6007 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.286   959  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 16:51:19.287  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:19.289   959  1316 D ConnectivityService: Adding iface wlan0 to network 100
08-31 16:51:19.290   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:19.290   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:19.290   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-31 16:51:19.291   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:19.291   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:19.291   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 16:51:19.293  1806  1821 D WifiServiceExtension: isInternetCheckAvailable return false
08-31 16:51:19.294  1806  1822 D WifiServiceExtension: isInternetCheckAvailable return false
08-31 16:51:19.295  6009  6009 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 16:51:19.296   959  1351 D qdlights: set_light_backlight: 136
08-31 16:51:19.299  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 16:51:19.303  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:19.303  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:19.303  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
08-31 16:51:19.303  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
08-31 16:51:19.304  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:19.304  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
08-31 16:51:19.305  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 16:51:19.305   959   959 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 16:51:19.309  6009  6009 D PanProfile: Bluetooth service connected
08-31 16:51:19.310   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:19.310   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:19.310   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 16:51:19.311   959  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 16:51:19.313   959   959 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 16:51:19.318   959  1351 D qdlights: set_light_backlight: 133
,08-31 16:51:19.319   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:19.319   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:19.319   959   959 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 16:51:19.319  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
08-31 16:51:19.320  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:19.320  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
08-31 16:51:19.320  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
08-31 16:51:19.321  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:19.321  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
08-31 16:51:19.325  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:19.325 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-31 16:51:19.325  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
08-31 16:51:19.325  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:19.326  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 16:51:19.327  2034  2056 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.328  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:19.328 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-31 16:51:19.328  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
08-31 16:51:19.328  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:19.330  6009  6009 D BluetoothMap: Proxy object connected
08-31 16:51:19.331   959  1351 D qdlights: set_light_backlight: 130
,08-31 16:51:19.333  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-31 16:51:19.334  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:19.334  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
08-31 16:51:19.334  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:19.334 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-31 16:51:19.336  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
08-31 16:51:19.337  1841  1841 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
08-31 16:51:19.338  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
08-31 16:51:19.338  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:19.338 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-31 16:51:19.339   959  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 16:51:19.339  1841  1841 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
08-31 16:51:19.339   959  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-31 16:51:19.339  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:19.339  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
08-31 16:51:19.340   287  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
08-31 16:51:19.340   287  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.341   287  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
08-31 16:51:19.341   287  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.341  1373  1373 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 16:51:19.343  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-31 16:51:19.343  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:19.343  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
,08-31 16:51:19.343  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
08-31 16:51:19.343   959  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-31 16:51:19.344  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
08-31 16:51:19.344  1373  1373 I [SystemUI]QuickSettingsHandler: Remote
08-31 16:51:19.344   287  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
,08-31 16:51:19.344   287  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.344  6009  6009 D MapProfile: Bluetooth service connected
08-31 16:51:19.345  6009  6009 D BluetoothMap: getConnectedDevices()
08-31 16:51:19.345  2034  2057 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.346  2034  2056 V BluetoothMapService: getConnectedDevices()
08-31 16:51:19.346  6009  6009 D BluetoothPbap: Proxy object connected
08-31 16:51:19.347  6009  6009 D PbapServerProfile: Bluetooth service connected
08-31 16:51:19.349  6009  6009 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 16:51:19.350   959  1351 D qdlights: set_light_backlight: 126
08-31 16:51:19.353   287  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
08-31 16:51:19.353   287  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.354   959  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-31 16:51:19.355   287  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
08-31 16:51:19.355   287  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.358   959  1316 D ConnectivityService: addLocalRoutetoDefaultNetwork
,08-31 16:51:19.358   959  1316 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-31 16:51:19.358   959  1316 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-31 16:51:19.358   959  1316 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:19.359   959  1316 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.360  6009  6009 D BluetoothPermissionRequest: onReceive
08-31 16:51:19.362  6009  6009 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 16:51:19.362   287  1050 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
,08-31 16:51:19.362   287  1050 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.364  6009  6009 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 16:51:19.364   959  1351 D qdlights: set_light_backlight: 123
08-31 16:51:19.369  6052  6052 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 16:51:19.369   959  1316 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 16:51:19.369   959  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-31 16:51:19.370   959  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-31 16:51:19.370   959  1316 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-31 16:51:19.370   959  1316 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:51:19.370   959  1316 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:19.370   959  1316 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 16:51:19.370   959  1316 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:19.371   959  1316 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
08-31 16:51:19.371   959  1316 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:19.371   959  1316 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 16:51:19.371   959  1316 D ConnectivityService: currentScore = 0, newScore = 20
08-31 16:51:19.372   959  1316 D ConnectivityService:    accepting network in place of null
08-31 16:51:19.372   959  6105 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:19.372   959  6105 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 16:51:19.372   959  1316 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:19.372   959  6105 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 16:51:19.374  2034  2034 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-31 16:51:19.376  1753  1753 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:19.381   959  1351 D qdlights: set_light_backlight: 120
08-31 16:51:19.383   959  1316 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
08-31 16:51:19.385   959  1310 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:19.385   959  1310 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:51:19.386  1753  1753 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,08-31 16:51:19.388  2034  2034 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-31 16:51:19.394   959  1316 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 16:51:19.394   959  1316 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 16:51:19.395   959  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 16:51:19.396   959  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:19.396   959  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.396   959  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:19.397   959  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,08-31 16:51:19.399   959  1351 D qdlights: set_light_backlight: 116
08-31 16:51:19.400  1841  1841 W QCNEJ   : |CORE| No family connected
08-31 16:51:19.400  1841  1841 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
08-31 16:51:19.400   287  1045 E BandwidthController: [LG DATA] No such appUid: 1000
08-31 16:51:19.400   287  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
08-31 16:51:19.401   287  6186 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
08-31 16:51:19.401   287  6186 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:19.401   287  6186 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=0
08-31 16:51:19.402   287  6186 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-31 16:51:19.402  2034  2034 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 16:51:19.403   287  6186 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-31 16:51:19.403   959  1058 D Tethering: MasterInitialState.processMessage what=3
08-31 16:51:19.404   959  1056 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 16:51:19.405  2034  2034 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:19.408  1841  1841 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
08-31 16:51:19.411   959  6105 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
,08-31 16:51:19.412  6052  6052 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 16:51:19.412  6052  6052 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 16:51:19.413   959  1351 D qdlights: set_light_backlight: 113
08-31 16:51:19.414  1735  1735 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-31 16:51:19.415   959  1316 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:19.416   959  1316 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 16:51:19.417   959  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 16:51:19.418   959  6187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
08-31 16:51:19.419   959  1316 D ConnectivityService: validation of new default Network = false
08-31 16:51:19.419   959  1316 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 16:51:19.419   959  1316 D DSQN    : enableDataServiceNotify 
08-31 16:51:19.419   959  1316 D DSQN    : start dsqn bin
08-31 16:51:19.433   959  1351 D qdlights: set_light_backlight: 110
,08-31 16:51:19.446  6188  6188 I DSQN    : DSQN samuel.seo ver 141203
08-31 16:51:19.446  6188  6188 E DSQN    : DSQN sock connect success to lgdatalistenerd
08-31 16:51:19.446  6188  6188 I DSQN    : created command queue thread
08-31 16:51:19.447   959  1316 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-31 16:51:19.447   959  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:19.447   959  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:19.447  6188  6188 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
08-31 16:51:19.448  6188  6188 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
,08-31 16:51:19.451   959  1351 D qdlights: set_light_backlight: 106
08-31 16:51:19.454   959  1316 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:19.455   959  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:19.455   959  1316 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:19.455  1373  1733 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 16:51:19.456  5513  5979 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 16:51:19.463   959  1640 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6191 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-31 16:51:19.463   959  1351 D qdlights: set_light_backlight: 103
08-31 16:51:19.463   959  1640 I ActivityManager: Killing 5496:com.lge.eula/1000 (adj 15): empty #11
08-31 16:51:19.467   302   362 I ThermalEngine: Sensor:pa_therm0:33000 mC
08-31 16:51:19.496   959  1351 D qdlights: set_light_backlight: 96
,08-31 16:51:19.513   959  1351 D qdlights: set_light_backlight: 93
,08-31 16:51:19.529   959  1351 D qdlights: set_light_backlight: 90
,08-31 16:51:19.546   959  1351 D qdlights: set_light_backlight: 86
,08-31 16:51:19.563   959  1351 D qdlights: set_light_backlight: 83
,08-31 16:51:19.580   959  1351 D qdlights: set_light_backlight: 80
,08-31 16:51:19.596   959  1351 D qdlights: set_light_backlight: 76
,08-31 16:51:19.612   287  1043 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,08-31 16:51:19.613   959  1351 D qdlights: set_light_backlight: 73
08-31 16:51:19.614   959  1056 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:19.614   959  1056 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.614   959  1383 W libprocessgroup: failed to open /acct/uid_1000/pid_5496/cgroup.procs: No such file or directory
08-31 16:51:19.618   959  1316 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
08-31 16:51:19.619   959  1316 D ConnectivityService: identical MTU - not setting
08-31 16:51:19.619   959  1316 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 16:51:19.619   959  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-31 16:51:19.619   959  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:19.619   959  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:19.620   959  1316 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:19.620   959  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:19.620  1373  1733 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 16:51:19.621   959  1316 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:19.622  5513  5979 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 16:51:19.624   959  1316 D ConnectivityService: Wi-Fi IP changed. Lp difference / No Route difference
08-31 16:51:19.624   959  1316 D DSQN    : enableDataServiceNotify 
08-31 16:51:19.624   959  1316 D DSQN    : start dsqn bin
,08-31 16:51:19.626  1735  6208 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-31 16:51:19.629   959  1308 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-31 16:51:19.629  1735  1735 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-31 16:51:19.630  1841  1841 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
08-31 16:51:19.630   959  1351 D qdlights: set_light_backlight: 70
08-31 16:51:19.632  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:19.631 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-31 16:51:19.639   959  1316 D DSQN    : dsqn is running restart
,08-31 16:51:19.647   959  1351 D qdlights: set_light_backlight: 66
08-31 16:51:19.658  6209  6209 I DSQN    : DSQN samuel.seo ver 141203
08-31 16:51:19.659  6209  6209 E DSQN    : DSQN sock connect success to lgdatalistenerd
,08-31 16:51:19.659  6209  6209 I DSQN    : created command queue thread
08-31 16:51:19.659  6209  6209 I DSQN    : Interface wlan0 address 192.168.1.109 0xc0a8016d
08-31 16:51:19.659  6209  6209 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a8016d
08-31 16:51:19.663  1373  1373 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 16:51:19.664   959  1351 D qdlights: set_light_backlight: 63
08-31 16:51:19.666  1373  1373 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
08-31 16:51:19.671  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-31 16:51:19.672  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-31 16:51:19.672  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
08-31 16:51:19.675  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-31 16:51:19.676  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:19.676  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
08-31 16:51:19.680   959  1351 D qdlights: set_light_backlight: 60
08-31 16:51:19.689  6191  6191 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 16:51:19.695  5513  5593 D edo     : Opening database auth.proximity.permit_store...
08-31 16:51:19.696   959  1351 D qdlights: set_light_backlight: 56
08-31 16:51:19.700  1735  6208 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
08-31 16:51:19.713   959  1351 D qdlights: set_light_backlight: 53
,08-31 16:51:19.730   959  1351 D qdlights: set_light_backlight: 50
,08-31 16:51:19.747   959  1351 D qdlights: set_light_backlight: 46
,08-31 16:51:19.763   959  1351 D qdlights: set_light_backlight: 43
,08-31 16:51:19.776   959  1058 D BluetoothManagerService: Message: 20
08-31 16:51:19.776   959  1058 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@174b8668:true
,08-31 16:51:19.780   959  1351 D qdlights: set_light_backlight: 40
08-31 16:51:19.783  2034  2056 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.784  2034  2057 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:19.796   959  1351 D qdlights: set_light_backlight: 36
,08-31 16:51:19.813   959  1351 D qdlights: set_light_backlight: 33
,08-31 16:51:19.830   959  1351 D qdlights: set_light_backlight: 30
,08-31 16:51:19.833  5720  5720 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 16:51:19.833  5720  5720 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-31 16:51:19.848   959  1351 D qdlights: set_light_backlight: 26
08-31 16:51:19.851  5720  5720 V [BNRBootReceiver]: Boot Receiver Return
,08-31 16:51:19.854  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 16:51:19.857  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:19.863   959  1351 D qdlights: set_light_backlight: 23
,08-31 16:51:19.870  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-31 16:51:19.872  6009  6009 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 16:51:19.873  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:19.879  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:19.880   959  1351 D qdlights: set_light_backlight: 20
08-31 16:51:19.889  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:19.895  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:19.896   959  1351 D qdlights: set_light_backlight: 16
08-31 16:51:19.903  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:19.908  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 16:51:19.913   959  1351 D qdlights: set_light_backlight: 13
08-31 16:51:19.918  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 16:51:19.918   959  6187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
08-31 16:51:19.919   959  6187 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,08-31 16:51:19.919   959  6187 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:19.919   959  6187 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
08-31 16:51:19.919   959  6187 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:19.919   287  1045 E BandwidthController: [LG DATA] No such appUid: 1000
08-31 16:51:19.919   287  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
08-31 16:51:19.921   287  6217 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
08-31 16:51:19.921   287  6217 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:19.921   287  6217 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-31 16:51:19.921   287  6217 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-31 16:51:19.922  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:19.930   959  1351 D qdlights: set_light_backlight: 10
,08-31 16:51:19.935  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 16:51:19.939  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:19.951  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:19.957  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:19.966  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:19.970  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:19.981   287  6217 D libc-netbsd: res_queryN name = xxxxx succeed
,08-31 16:51:19.982   959  6187 I System.out: propertyValue:false
08-31 16:51:19.982   959  6187 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
08-31 16:51:19.988   959  6105 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 16:51:19.991  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:19.997  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:20.009  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:20.014   959  6105 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:20.014   959  6105 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:20.016  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:20.021  6052  6052 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 16:51:20.043  6209  6210 I DSQN    : first global connection report this to start monitoring at DSQM.
,08-31 16:51:20.043  6209  6210 I DSQN    : restart monitoring
,08-31 16:51:20.045   287  1049 D LGDataListener: argv[0]=dsqncommand
08-31 16:51:20.045   287  1049 D LGDataListener: argv[1]=wlan0
08-31 16:51:20.045   287  1049 D LGDataListener: argv[2]=1
08-31 16:51:20.045   287  1049 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-31 16:51:20.045  6209  6219 I DSQN    : dsqn report finish
08-31 16:51:20.047   959  1056 D DSQN    : DSQM DsqnNotification wlan0  1
08-31 16:51:20.047   959  1056 D DSQN    : start to monitor internet connection
08-31 16:51:20.049  6052  6052 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 16:51:20.056  6009  6009 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 16:51:20.061  6009  6009 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 16:51:20.065  6052  6052 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 16:51:20.066  6052  6052 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 16:51:20.077   959  6105 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 14:51:19 GMT], X-Android-Received-Millis=[1472655080076], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472655080043]}
,08-31 16:51:20.078   959  6105 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 16:51:20.080  1806  1822 D WifiServiceExtension: isInternetCheckAvailable return false
08-31 16:51:20.080   959  6105 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
08-31 16:51:20.080   959  6105 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 16:51:20.081   959  1316 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
08-31 16:51:20.081   959  1316 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-31 16:51:20.081   959  1316 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:51:20.081   959  1316 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:20.081   959  1316 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 16:51:20.081   959  1316 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:20.082   959  1316 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
08-31 16:51:20.082   959  1316 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
08-31 16:51:20.082   959  1316 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-31 16:51:20.082   959  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:20.082   959  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:20.082   959  1316 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 16:51:20.083   959  1316 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:20.083  1373  1733 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 16:51:20.083   959  1316 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:20.084  5513  5979 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 16:51:20.084   959   959 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
08-31 16:51:20.085   959  1316 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:20.085   959  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 16:51:20.085   959  1310 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
08-31 16:51:20.086   959  1310 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:20.086  1753  1753 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:20.087  1753  1753 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
08-31 16:51:20.087   959  1310 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps, LinkDnBandwidth>=1048576Kbps]
08-31 16:51:20.100  1373  1373 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 16:51:20.101  1373  1373 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,08-31 16:51:20.104  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-31 16:51:20.104  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:20.104  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
08-31 16:51:20.106  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-31 16:51:20.106  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:20.106  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-31 16:51:20.203   959  1787 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6221 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:20.216  6191  6191 V LGMDMManager: Create singleton instance
,08-31 16:51:20.262   959  2065 I ActivityManager: Process com.google.android.talk (pid 5737) has died
,08-31 16:51:20.289  6191  6191 I AudioManager: getMode name:com.lge.qremote
,08-31 16:51:20.302  6221  6221 D UEI.SmartControl: Quickset Services start...
,08-31 16:51:20.307  6221  6221 I UEI.SmartControl: Manufacture = LGE
08-31 16:51:20.310  6221  6221 D UEI.SmartControl: File observer start...
08-31 16:51:20.311  6221  6221 E UEI.SmartControl: IR Port is disabled: false
08-31 16:51:20.311  6221  6221 D UEI.SmartControl: Starting file observer...
08-31 16:51:20.311  6221  6221 D UEI.SmartControl: Extracting JNI libs...
08-31 16:51:20.312  6221  6221 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 16:51:20.317  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-31 16:51:20.318  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:20.318  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,08-31 16:51:20.360   291  1290 V AudioFlinger: thread 0xb5735000 type 0 TID 1290 going to sleep
,08-31 16:51:20.365   291  1288 V AudioFlinger: thread 0xb56eb000 type 0 TID 1288 going to sleep
08-31 16:51:20.365   291  1287 V AudioFlinger: thread 0xb5651000 type 0 TID 1287 going to sleep
08-31 16:51:20.388  6221  6221 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-31 16:51:20.389  6221  6221 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-31 16:51:20.389  6221  6221 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-31 16:51:20.423  6221  6221 I UEI.SmartControl: --- Selecting new region: 2
,08-31 16:51:20.423  6221  6221 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
08-31 16:51:20.429  6221  6221 D UEI.SmartControl: Platform has CIR...
08-31 16:51:20.430  6221  6221 D UEI.SmartControl: NO CIR support, need to check package...
08-31 16:51:20.431  6221  6221 I UEI.SmartControl: Model: LG-D722 uses JNI
08-31 16:51:20.433  6221  6221 D UEI.SmartControl: QS Service created
08-31 16:51:20.457  6221  6221 E UEI.SmartControl: QS start get config
,08-31 16:51:20.508  6221  6221 D UEI.SmartControl: Loading JNI Libs...
,08-31 16:51:20.510  6221  6221 D UEI.SmartControl:  configuring local db...
08-31 16:51:20.704  6221  6221 D UEI.SmartControl:  ---- Has DB8: true
,08-31 16:51:20.712  6221  6221 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 16:51:20.713  6221  6221 D UEI.SmartControl: QS version = v2.7.11.1_RC1
08-31 16:51:20.714  6221  6221 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
08-31 16:51:20.717  6221  6221 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,08-31 16:51:20.756  6221  6221 W irrc_jni: IRRCPlayer_nativeInit ++ 
08-31 16:51:20.756  6221  6221 D irrcClient: IrrcClient ++ 
08-31 16:51:20.756  6221  6221 D irrcClient: getIrrcService ++ 
,08-31 16:51:20.756  6221  6221 D irrcClient: getIrrcService -- 
08-31 16:51:20.756  6221  6221 D irrcClient: IrrcClient -- 
08-31 16:51:20.756  6221  6221 W irrc_jni: IRRCPlayer_nativeInit -- 
08-31 16:51:20.763  6221  6221 D UEI.SmartControl: Services init done
08-31 16:51:20.764  6221  6240 I UEI.SmartControl: Device manager: loading config....
08-31 16:51:20.766  6221  6221 D UEI.SmartControl: QS Service init finished
08-31 16:51:20.767  6221  6221 D UEI.SmartControl: QS Service version name: 0.1.73
08-31 16:51:20.768  6221  6221 D UEI.SmartControl: QS Service version code: 1073
08-31 16:51:20.769  6221  6221 D UEI.SmartControl: Service requested: Control
08-31 16:51:20.769  6221  6240 D UEI.SmartControl: Config is loaded...
,08-31 16:51:20.812  6221  6239 D UEI.SmartControl:  ----- QS SDK is ready!!!
08-31 16:51:20.813  6221  6239 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-31 16:51:20.816  6221  6221 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 16:51:20.818  6221  6221 D UEI.SmartControl: Internal service binding...
08-31 16:51:20.819  6221  6237 D UEI.SmartControl: -----IControl: 11
08-31 16:51:20.820  6221  6237 D UEI.SmartControl: Caller: com.lge.qremote
08-31 16:51:20.823  6221  6237 D UEI.SmartControl: ------------ IControl registerCallback...
08-31 16:51:20.823  6221  6237 I UEI.SmartControl: Registering callback...
08-31 16:51:20.824  6221  6236 D UEI.SmartControl: -----IControl: 19
08-31 16:51:20.825  6221  6236 D UEI.SmartControl: Caller: com.lge.qremote
08-31 16:51:20.826  6221  6236 I UEI.SmartControl: Registering Services Ready callback...
08-31 16:51:20.827  6221  6236 I UEI.SmartControl: Notify client services are ready...
,08-31 16:51:20.831  6221  6237 D UEI.SmartControl: -----IControl: 8
08-31 16:51:20.832  6221  6237 D UEI.SmartControl: Caller: com.lge.qremote
08-31 16:51:20.837  6191  6191 I AudioManager: getMode name:com.lge.qremote
08-31 16:51:20.880  6191  6191 I AudioManager: getMode name:com.lge.qremote
,08-31 16:51:20.915  6191  6191 I AudioManager: getMode name:com.lge.qremote
,08-31 16:51:21.320  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-31 16:51:21.320  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:21.320  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-31 16:51:21.579  1841  1841 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,08-31 16:51:21.579  1841  1841 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-31 16:51:21.579 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-31 16:51:21.581  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-31 16:51:21.581  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:21.581  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-31 16:51:22.300  5843  5935 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 16:51:22.300  5843  5935 I jxcore-log: 
,08-31 16:51:22.306   959  1311 V WifiInternetCheck: Single check msg out of sync, ignoring.
08-31 16:51:22.322  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-31 16:51:22.322  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:22.322  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-31 16:51:22.418   959  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:22.423  1373  1373 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
08-31 16:51:22.431  2034  2056 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:22.432  5843  5843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:22.432  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:22.432  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 16:51:22.432  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:22.432  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:51:22.432  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 16:51:22.432  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 16:51:22.432  5843  5843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 16:51:22.435  2034  2056 D BluetoothAdapterService(1070426906): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ff45440
08-31 16:51:22.441  5843  5843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 16:51:22.450   959  1035 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:22.485   959   959 D LocSvc_java: onReceive
08-31 16:51:22.485   959   959 D LocSvc_java: got connectivity action
,08-31 16:51:22.493   959   959 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
08-31 16:51:22.493   959   959 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 16:51:22.494   959  1741 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:22.494   959  1741 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:22.494   959  1741 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:22.494   959  1741 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:22.495   287  1045 E BandwidthController: [LG DATA] No such appUid: 1000
08-31 16:51:22.495   287  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
08-31 16:51:22.495   287  6256 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-31 16:51:22.496   287  6256 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:22.496   287  6256 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-31 16:51:22.496   287  6256 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-31 16:51:22.497   959  1037 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6250 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:22.523   959   959 D LocSvc_java: getAGpsConnectionInfo connType - 4
,08-31 16:51:22.547   959   959 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 16:51:22.548   959   959 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 16:51:22.548   959   959 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-31 16:51:22.549   959  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:22.549   959  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:22.549   959  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:22.549   959  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:22.550   959  6269 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:22.550   959  6269 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:22.550   959  6269 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:22.550   959  6269 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:22.550   287  1045 E BandwidthController: [LG DATA] No such appUid: 1000
08-31 16:51:22.550   287  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
08-31 16:51:22.551   287  6270 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-31 16:51:22.551   287  6270 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:22.551   287  6270 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-31 16:51:22.551   287  6270 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,08-31 16:51:22.552   287  1045 E BandwidthController: [LG DATA] No such appUid: 1000
08-31 16:51:22.552   287  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
08-31 16:51:22.553   287  6271 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-31 16:51:22.553   287  6271 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:22.554   287  6271 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-31 16:51:22.554   287  6271 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,08-31 16:51:22.593  1735  1735 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-31 16:51:22.657   959  1035 I ActivityManager: Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6284 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-31 16:51:22.661   959  1035 I NotificationManager: android: cancelAsUser(716319171) by android
,08-31 16:51:22.716   959  1035 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService: pid=6300 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-31 16:51:22.718   959  1035 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 16:51:22.768  6284  6284 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:22.768  6284  6284 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 16:51:22.768  6284  6284 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-31 16:51:22.830   959  1035 E GpsLocationProvider: No APN found to select.
,08-31 16:51:22.916   959  1805 I ActivityManager: Process com.android.vending (pid 5566) has died
,08-31 16:51:23.010   959  6324 D LgeGpsConstants: Can't find 'ext_gps.conf'!!
08-31 16:51:23.011   959  6324 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:23.011   959  6324 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:23.011   959  6324 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:23.011   959  6324 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:23.012   287  1045 E BandwidthController: [LG DATA] No such appUid: 1000
08-31 16:51:23.012   287  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
08-31 16:51:23.012   287  6325 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-31 16:51:23.012   287  6325 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:23.013   287  6325 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,08-31 16:51:23.013   287  6325 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-31 16:51:23.029  6300  6300 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 16:51:23.201   287  6271 D libc-netbsd: res_queryN name = xxxxx succeed
08-31 16:51:23.201   287  6256 D libc-netbsd: res_queryN name = xxxxx succeed
,08-31 16:51:23.202   287  6270 D libc-netbsd: res_queryN name = xxxxx succeed
08-31 16:51:23.202   959  1308 I System.out: propertyValue:false
08-31 16:51:23.203   287  6325 D libc-netbsd: res_queryN name = xxxxx succeed
08-31 16:51:23.203   959  6269 I System.out: propertyValue:false
08-31 16:51:23.204   959  1741 I System.out: propertyValue:false
08-31 16:51:23.204   959  6324 I System.out: propertyValue:false
08-31 16:51:23.272   959  1787 I art     : Explicit concurrent mark sweep GC freed 74260(3MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 1.966ms total 213.225ms
,08-31 16:51:23.291  6284  6284 I AppConfig: Total System Memory = 906309632
,08-31 16:51:23.296  6284  6284 I GalleryUtils: Application Heap = 96 MB
08-31 16:51:23.302  6284  6284 I AppConfig: App Tier : NOT_DEF
08-31 16:51:23.315  6284  6284 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-31 16:51:23.318  6250  6250 I MusicStore: Database version: 120
,08-31 16:51:23.325  5513  6335 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,08-31 16:51:23.329  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-31 16:51:23.329  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-31 16:51:23.329  1373  1373 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
08-31 16:51:23.384   959  1035 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 37334, reason: UserStart, SyncResult: databaseError: true stats []
,08-31 16:51:23.394   959  1035 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 182561, reason: UserStart
08-31 16:51:23.397   959  1035 I NotificationManager: android: cancelAsUser(716319171) by android
,08-31 16:51:23.430  5843  5935 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 16:51:23.430  5843  5935 I jxcore-log: 
,08-31 16:51:23.462   959  1035 I NotificationManager: android: cancelAsUser(-1597574061) by android
,08-31 16:51:23.485  5843  5935 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-31 16:51:23.485  5843  5935 I jxcore-log: 
,08-31 16:51:23.508  1735  1735 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 16:51:23.520   248   286 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 16:51:23.520   248   286 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
08-31 16:51:23.520   248   286 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 16:51:23.521  6250  6250 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
08-31 16:51:23.535  5513  6344 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-31 16:51:23.541  5513  6344 D SchedPeriodicTask: Scheduled AdAttestation task.
08-31 16:51:23.574   959  1035 I NotificationManager: android: cancelAsUser(353845882) by android
,08-31 16:51:23.604  5513  6339 W InstanceID/Rpc: Found 10006
,08-31 16:51:23.609  1735  1735 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-31 16:51:23.610  1735  1735 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-31 16:51:23.759   248   286 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 16:51:23.759   248   286 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
08-31 16:51:23.760   248   286 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:23.762  6250  6250 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
08-31 16:51:23.766   248   286 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 16:51:23.766   248   286 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
08-31 16:51:23.766   248   286 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 16:51:23.767  6250  6250 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
08-31 16:51:23.791  5513  6323 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-31 16:51:23.803   959  1741 D AlarmManagerService: Setting time of day to sec=1472655083
,08-31 16:51:23.043   959  6324 D LgeGpsLocationProvider: NTP server: europe.pool.ntp.org
08-31 16:51:23.044   959  6269 D LocSvc_java: NTP server returned: 1472655083046 (Wed Aug 31 16:51:23 GMT+02:00 2016) reference: 152706 certainty: 301 system time offset: 3
08-31 16:51:23.044   959  6324 D LgeGpsLocationProvider: NTP server returned: 1472655083068 (Wed Aug 31 16:51:23 GMT+02:00 2016) reference: 152705 certainty: 300 system time offset: 25
08-31 16:51:23.044   959  1741 W AlarmManagerService: Unable to set rtc to 1472655083: Invalid argument
08-31 16:51:23.057   959  6269 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
,08-31 16:51:23.075  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 16:51:23.075  1373  1373 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
,08-31 16:51:23.079   291  1606 V AudioFlinger: 2848 died, releasing its sessions
08-31 16:51:23.079   291  1606 V AudioFlinger:  pid 1753 @ 0
08-31 16:51:23.079   291  1606 V AudioFlinger:  pid 3113 @ 1
08-31 16:51:23.079   291  1606 V AudioFlinger:  pid 3113 @ 2
08-31 16:51:23.086  2842  2842 D WeatherService: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:51:23
08-31 16:51:23.086  2842  2842 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
08-31 16:51:23.088  2842  2842 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 16:51:23.088  2842  2842 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
08-31 16:51:23.088  2842  2842 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
,08-31 16:51:23.089  2842  2842 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
08-31 16:51:23.089  2842  2842 D WeatherTheme: 2 : Fixed theme : optimus
08-31 16:51:23.095  1373  1373 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-31 16:51:23.113  2842  2842 D WeatherReflect: 2 : Map key string is -2
,08-31 16:51:23.116  2842  2842 D lim     : 2 : time = 16:51
08-31 16:51:23.121  2842  2842 I WeatherReflect: Model Name : LG-D722
08-31 16:51:23.121  2842  2842 D WeatherTheme: 2 : exactly same view!
08-31 16:51:23.121  2842  2842 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
08-31 16:51:23.122  2842  2842 D WeatherService: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:51:23
08-31 16:51:23.131   959  1037 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=6356 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 16:51:23.132  6250  6250 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 16:51:23.133  6250  6250 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-31 16:51:23.210   959  2154 I ActivityManager: Process com.lge.music (pid 2848) has died
,08-31 16:51:23.213   959  1860 W ActivityManager: getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
08-31 16:51:23.224   959  1035 I NotificationManager: android: cancelAsUser(-591465577) by android
,08-31 16:51:23.251  1880  1880 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=31 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
,08-31 16:51:23.263   959  1311 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:23.263   959  1311 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:23.264   959  1311 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:23.264   959  1311 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:23.264   287  1045 E BandwidthController: [LG DATA] No such appUid: 1000
08-31 16:51:23.264   287  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
08-31 16:51:23.264   287  6373 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-31 16:51:23.264   287  6373 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:23.265   287  6373 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-31 16:51:23.265   287  6373 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-31 16:51:23.269  6356  6356 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:23.269  6356  6356 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 16:51:23.271  6356  6356 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-31 16:51:23.296  1880  1880 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 31
,08-31 16:51:23.321  1880  1880 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 31
,08-31 16:51:23.341  1880  1880 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,08-31 16:51:23.357   287  6373 D libc-netbsd: res_queryN name = xxxxx succeed
08-31 16:51:23.361   959  1311 I System.out: propertyValue:false
,08-31 16:51:23.369   959  1312 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:23.369   959  1312 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:23.369   959  1312 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:23.369   959  1312 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:23.370   287  1045 E BandwidthController: [LG DATA] No such appUid: 1000
08-31 16:51:23.370   287  1045 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
08-31 16:51:23.370   287  6377 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-31 16:51:23.371   287  6377 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:23.372   287  6377 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-31 16:51:23.372   287  6377 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-31 16:51:23.372   287  6377 D libc-netbsd: res_queryN name = xxxxx succeed
,08-31 16:51:23.374   959  1312 I System.out: propertyValue:false
08-31 16:51:23.427  6250  6250 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
08-31 16:51:23.430   959  2065 I ActivityManager: Process com.lge.lgdmsclient (pid 6113) has died
,08-31 16:51:23.478   959  1823 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6378 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,08-31 16:51:23.499   310   310 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 888us total 25.678ms
,08-31 16:51:23.524   310   310 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 346us total 22.494ms
,08-31 16:51:23.529  6356  6356 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-31 16:51:23.551  6356  6356 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-31 16:51:23.562   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 34.757ms
,08-31 16:51:23.602  6378  6378 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 16:51:23.602  6378  6378 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 16:51:23.646  6250  6250 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 16:51:23.651  6250  6250 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@366d558a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-31 16:51:23.656  6250  6250 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-31 16:51:23.657  6250  6250 D AndroidMusic: GMSCore installation verified
08-31 16:51:23.679  6378  6378 I MultiDex: VM with version 2.1.0 has multidex support
08-31 16:51:23.679  6378  6378 I MultiDex: install
08-31 16:51:23.679  6378  6378 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 16:51:23.694  6250  6250 I ConfigStore: Config Database version: 1
08-31 16:51:23.710   302   362 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-31 16:51:23.736   959  1312 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-31 16:51:23.738  6378  6378 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 16:51:23.817   959  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1897446e type 2 when 153479 com.google.android.gms} when 153479
,08-31 16:51:23.824  5532  5547 I art     : Explicit concurrent mark sweep GC freed 1587(68KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 5.821ms total 60.682ms
08-31 16:51:23.831  6378  6378 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-31 16:51:23.832  6378  6378 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@85ef2a0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-31 16:51:23.837  6378  6378 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-31 16:51:23.839  6378  6378 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
08-31 16:51:23.840  6378  6378 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
08-31 16:51:23.873  6378  6378 D ChimeraCfgMgr: Reading stored module config
,08-31 16:51:23.993   959  1640 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6407 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-31 16:51:24.073   959  1035 I NotificationManager: android: cancelAsUser(-1874035846) by android
,08-31 16:51:24.101  6378  6404 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-31 16:51:24.126  6378  6378 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-31 16:51:24.126  6378  6378 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-31 16:51:24.126  1735  1735 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=dec72244-a5f2-4be7-8ec7-be226c79ac9a
,08-31 16:51:24.187   959  1035 I NotificationManager: android: cancelAsUser(-1597574061) by android
,08-31 16:51:24.199   959  1035 I NotificationManager: android: cancelAsUser(-591465577) by android
,08-31 16:51:24.251  6407  6429 D ALBootInit: ====action==>android.intent.action.TIME_SET
,08-31 16:51:24.259  6407  6429 D ALBootInit: Alarm ALBootInit: TIME_SET
08-31 16:51:24.261  6407  6429 D Alarms  : [setNextAlert] start
,08-31 16:51:24.305   959  1035 I NotificationManager: android: cancelAsUser(353845882) by android
,08-31 16:51:24.329  1735  1735 I art     : Explicit concurrent mark sweep GC freed 52405(3MB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 14MB/24MB, paused 2.589ms total 146.142ms
,08-31 16:51:24.420   959  1640 I ActivityManager: Process com.lge.bnr (pid 5720) has died
,08-31 16:51:24.456   959  1860 I art     : Explicit concurrent mark sweep GC freed 29064(1339KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 6.050ms total 171.794ms
,08-31 16:51:24.461  6407  6429 D Alarms  : [setNextAlert] (1)
08-31 16:51:24.464  6407  6429 D Alarms  :  minTime  = 0
08-31 16:51:24.469  6407  6429 D Alarms  :  -- OK multi -- 0
,08-31 16:51:24.471  6407  6429 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
08-31 16:51:24.471  6407  6429 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
08-31 16:51:24.486  6250  6250 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-31 16:51:24.489  6407  6429 I CommonUtil: BUILD Operator: OPEN
08-31 16:51:24.490  6250  6278 I art     : CheckpointMarkThreadRoots callback created = 0xb042d380
08-31 16:51:24.492  6407  6429 D Alarms  : broadcastToWidgetProvider : false
08-31 16:51:24.500  6407  6429 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
,08-31 16:51:24.524  6378  6392 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3c0
,08-31 16:51:24.535   291  1606 D WVCdm   : Instantiating CDM.
08-31 16:51:24.536   291  1611 I WVCdm   : CdmEngine::OpenSession
08-31 16:51:24.536   291  1611 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
08-31 16:51:24.542   959  1823 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,08-31 16:51:24.544  6250  6278 I art     : CheckpointMarkThreadRoots callback created = 0xb042d360
08-31 16:51:24.550  6407  6407 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
08-31 16:51:24.552  6407  6407 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@379f843c
08-31 16:51:24.556  6378  6392 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3b0
,08-31 16:51:24.559  6407  6407 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@379f843c
08-31 16:51:24.561  6250  6250 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
08-31 16:51:24.566  6407  6407 D QuickCoverProvider: onReceiver
08-31 16:51:24.585   959   997 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
,08-31 16:51:24.585  6378  6392 I art     : Background partial concurrent mark sweep GC freed 1817(285KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/18MB, paused 10.233ms total 61.371ms
,08-31 16:51:24.585   959   997 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-31 16:51:24.585   959   997 D sensors_hal_Time: tsOffsetIs: Apps: 154253541872; DSPS: 5153137; Offset : -3014826508
08-31 16:51:24.609  6250  6278 W art     : Suspending all threads took: 43.750ms
,08-31 16:51:24.625   959  1383 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6435 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:24.633   291  1611 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-31 16:51:24.634   291  1611 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
08-31 16:51:24.634   291  1611 W WVCdm   : L1 library not specified. Falling Back to L3
08-31 16:51:24.648  1735  2399 W GCoreFlp: No location to return for getLastLocation()
,08-31 16:51:24.652  6250  6250 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-31 16:51:24.703  6378  6394 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:24.703  6378  6394 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:24.703  6378  6394 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:24.703  6378  6394 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:24.704   287  1045 E BandwidthController: [LG DATA] No such appUid: 10006
08-31 16:51:24.704   287  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,08-31 16:51:24.710   287  6454 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-31 16:51:24.710   287  6454 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:24.711   287  6454 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-31 16:51:24.711   287  6454 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-31 16:51:24.747  1735  2393 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 16:51:24.751  6435  6435 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:24.756  5513  6353 D UdcContextInitService: registered all accounts: true
08-31 16:51:24.756   291  1611 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-31 16:51:24.759   291  1323 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-31 16:51:24.760   291  1323 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-31 16:51:24.760   291  1323 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-31 16:51:24.768   291  1323 D WVCdm   : PrepareKeyRequest: nonce=244444620
08-31 16:51:24.779  6250  6250 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-31 16:51:24.830  6356  6356 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 16:51:24.930   959   983 I ActivityManager: Process com.lge.settings.easy (pid 6079) has died
,08-31 16:51:24.933   959  1061 I PowerManagerService: ALS enabled for SRE
08-31 16:51:24.933   959  1061 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34602 ms ago)
08-31 16:51:24.935  6435  6435 D CalendarApplication: CalendarApplication.onCreate()
08-31 16:51:24.936   959  1061 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-31 16:51:24.947   959  1061 I PowerManagerService: ALS enabled for SRE
,08-31 16:51:24.947   959  1061 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34617 ms ago)
08-31 16:51:24.950  1735  2339 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
08-31 16:51:24.961   959  1061 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,08-31 16:51:24.967  6435  6435 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
,08-31 16:51:24.968  6435  6435 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@ad31fd3, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1fc90710, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@f1f1209, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@23af9c0e, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3425e62f, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@379f843c, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@b9dc5c5, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3fcd6b1a, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3134b64b, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@bfea828, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2999f941, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@29c71ee6, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1166c27, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@18aa1ed4, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1cbe87d, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@32564372, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1373a3c3, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2ff45440, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@6338f79, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@a4124be, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1fe2b91f, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@34ea746c, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2ed4aa35, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1666ceca, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1703c83b, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@c406b58, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3632b4b1, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@388b0d96, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@95cad17, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2ffce504, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@218ceaed, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@18e26d22, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1ff503b3, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@11e54d70, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@10da48e9, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3c5e396e, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2b2280f, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@38a9d09c, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@12858aa5, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@33b87e7a, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@873362b, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyDat,a@3d15a88, l
08-31 16:51:24.968   959  1061 I PowerManagerService: Sleeping (uid 1000)...
08-31 16:51:24.970   959  1061 D LPWGController: [updateScreenState] screen on = false
08-31 16:51:24.976   959  1061 D LPWGController: disable proximity sensor
08-31 16:51:24.976   959  1061 D LPWGController: enable proximity sensor
,08-31 16:51:24.979  6435  6435 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
08-31 16:51:24.993  6435  6435 D Config  : [init]
,08-31 16:51:24.997  6435  6435 I Config  : LGCalendar ver.4.40.17
08-31 16:51:24.997  6435  6435 I Config  : start check model
08-31 16:51:24.997  6435  6435 I Config  : start check native_ca
08-31 16:51:24.998  6435  6435 I Config  : Config Operator=OPEN, Country=EU
08-31 16:51:24.998   959  1061 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@15acd606] by com.android.server.power.ProximitySensorListener.enable():120
08-31 16:51:24.999  6435  6435 D Config  : [setDefaultValuesToPref]
08-31 16:51:24.999  6435  6435 D Config  : [parseProfiles]
,08-31 16:51:25.006  6435  6435 D ProfilesParser: [debug_displayParseInfos] profile.country = null
08-31 16:51:25.006  6435  6435 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
08-31 16:51:25.006  6435  6435 D Config  : [updateProfiletoCountryInfo]
,08-31 16:51:25.008   959  1061 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
08-31 16:51:25.008   959  1061 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
08-31 16:51:25.008   959  1061 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
08-31 16:51:25.008   959  1061 I sensors_hal_Ctx: activate: handle is 48, enable
08-31 16:51:25.008   959  1061 V sensors_hal_Ctx: activate sensors is 1400000000000
08-31 16:51:25.009   959  1061 D sensors_hal_Thresh: enable: handle=48
08-31 16:51:25.009   959  1061 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
08-31 16:51:25.009   959  1061 D sensors_hal_Util: waitForResponse: timeout=1000
08-31 16:51:25.014   959   998 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
08-31 16:51:25.014   959   998 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
08-31 16:51:25.014   959  1061 D sensors_hal_Thresh: enable: Received response: 0
08-31 16:51:25.015  6435  6435 D GeneralPreference: [checkAndMigrateOldPreference]
08-31 16:51:25.016   959  1061 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34685 ms ago)
08-31 16:51:25.033   959  1879 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6462 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,08-31 16:51:25.088   959  1061 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 16:51:25.088   959  1061 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 16:51:25.088   959  1061 I Adreno-EGL: Build Date: 03/02/15 Mon
08-31 16:51:25.088   959  1061 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-31 16:51:25.088   959  1061 I Adreno-EGL: Remote Branch: 
08-31 16:51:25.088   959  1061 I Adreno-EGL: Local Patches: 
08-31 16:51:25.088   959  1061 I Adreno-EGL: Reconstruct Branch: 
,08-31 16:51:25.091  6435  6435 E AgendaWidgetManager: [updateWidgets] 
08-31 16:51:25.108  6356  6356 I HubEmail: JNI_OnLoad()
,08-31 16:51:25.108  6356  6356 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 16:51:25.109  6356  6356 I HubEmail: registerNatives()
08-31 16:51:25.109  6356  6356 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 16:51:25.109  6356  6356 I HubEmail: registerNativeMethods()
08-31 16:51:25.109  6356  6356 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 16:51:25.109  6356  6356 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-31 16:51:25.127  5513  6353 I GAv4-SVC: Google Analytics 9.4.52 is starting up.
08-31 16:51:25.128   249   273 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (153 us)
08-31 16:51:25.138  6356  6481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:25.146  6250  6250 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,08-31 16:51:25.209  6250  6250 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 16:51:25.242   420   962 I Sensors : sns_pwr.c(273):acquiring wakelock
08-31 16:51:25.242   959   998 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
08-31 16:51:25.244   959   998 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
08-31 16:51:25.244   959   998 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
08-31 16:51:25.244   959   998 D sensors_hal_Thresh: processInd: handle 48, count=1
08-31 16:51:25.244   959   998 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
08-31 16:51:25.244   959   998 I sensors_hal_Thresh: processInd : proximity state changed - FAR
08-31 16:51:25.244   959  1040 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
08-31 16:51:25.244   959  1040 D sensors_hal_Ctx: poll: count: 256
08-31 16:51:25.244   959  1040 I sensors_hal_Ctx: poll: released wakelock sensor_ind
08-31 16:51:25.244   959  1040 D sensors_hal_Util: waitForResponse: timeout=0
,08-31 16:51:25.301   959  1805 I ActivityManager: Process com.android.settings (pid 6009) has died
,08-31 16:51:25.313   959  1061 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
08-31 16:51:25.314   959  1061 I LPWGController: current mode = 1  value = 1 1
08-31 16:51:25.314   959  1061 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
08-31 16:51:25.331  6435  6477 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
,08-31 16:51:25.335  6435  6477 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
08-31 16:51:25.338  6435  6485 W HolidayIntentService: onHandleIntent
08-31 16:51:25.340  6435  6435 D MonthWidgetProvider: [onReceive]
08-31 16:51:25.340  6435  6435 D CalendarWidgetProvider: [onReceive]
08-31 16:51:25.340  6435  6435 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
08-31 16:51:25.343  6435  6435 D CalendarTypeController: [onUpdateAndInitCalendarTime]
08-31 16:51:25.343  6435  6485 D HolidayDataLoader: readJsonAsset : holiday.json
08-31 16:51:25.352   959  1061 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,08-31 16:51:25.369   287  6454 D libc-netbsd: res_queryN name = xxxxx succeed
,08-31 16:51:25.371  6378  6394 I System.out: propertyValue:false
08-31 16:51:25.390   959  1383 I ActivityManager: Process com.lge.qremote (pid 6191) has died
,08-31 16:51:25.409  6435  6435 D WeekWidgetProvider: [onReceive]
08-31 16:51:25.409  6435  6435 D CalendarWidgetProvider: [onReceive]
08-31 16:51:25.409  6435  6435 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
08-31 16:51:25.410  6435  6435 D CalendarTypeController: [onUpdateAndInitCalendarTime]
,08-31 16:51:25.423  2842  2842 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:51:25
08-31 16:51:25.428  2842  2842 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 16:51:25.431  2842  2842 D Weather_cast: 2 : set auto-update time : 8/31 19:51
,08-31 16:51:25.442  6462  6462 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:25.442  6462  6462 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 16:51:25.445  6435  6485 E HolidayIntentService: onHandleIntent:holiday data empty
08-31 16:51:25.445  6462  6462 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
08-31 16:51:25.447  2842  2842 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:51:25
,08-31 16:51:25.448  2842  2842 D WeatherService: 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
08-31 16:51:25.449  6435  6477 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
08-31 16:51:25.450  2842  2842 D WeatherService: 2 : shouldTimeTickRegistered : false
08-31 16:51:25.459  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
08-31 16:51:25.464  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,08-31 16:51:25.471  6462  6462 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
08-31 16:51:25.474  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
08-31 16:51:25.479  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
08-31 16:51:25.483  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
08-31 16:51:25.493  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,08-31 16:51:25.496   959   982 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6487 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
08-31 16:51:25.511  6462  6493 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 16:51:25.542  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,08-31 16:51:25.545  6462  6493 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-31 16:51:25.550  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
08-31 16:51:25.556  6462  6498 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:25.556  6462  6498 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 16:51:25.558  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,08-31 16:51:25.563  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
08-31 16:51:25.567  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
08-31 16:51:25.577  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,08-31 16:51:25.584   959   982 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6510 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-31 16:51:25.634  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,08-31 16:51:25.645  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
08-31 16:51:25.666  6435  6477 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
08-31 16:51:25.666  6435  6477 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,08-31 16:51:25.679  6435  6477 I AlertUtils: set default noti to content://media/internal/audio/media/38
,08-31 16:51:25.694  6435  6477 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
,08-31 16:51:25.696  6487  6487 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472655085696
08-31 16:51:25.696  6487  6487 D         : TimeServiceNative: User Time to be set is 1472655085696
08-31 16:51:25.696  6487  6487 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-31 16:51:25.696  6487  6487 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-31 16:51:25.696  6487  6487 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472655085696
08-31 16:51:25.697  6487  6487 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-31 16:51:25.698   321  1055 D QC-time-services: Daemon: Connection accepted:time_genoff
08-31 16:51:25.700   321  6531 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472655085696
08-31 16:51:25.700   321  6531 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472655085696, operation = 0
08-31 16:51:25.700   321  6531 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/12/71 18:51:49
08-31 16:51:25.701   321  6531 D QC-time-services: Daemon:Value read from RTC seconds = 32554309000
08-31 16:51:25.701   321  6531 D QC-time-services: Daemon:new time 1472655085696 
08-31 16:51:25.701   321  6531 D QC-time-services: Daemon: delta 1440100776696 genoff 1440100776696 
08-31 16:51:25.701   321  6531 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100776696 to memory
08-31 16:51:25.701   321  6531 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-31 16:51:25.701   321  6531 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-31 16:51:25.710  6250  6334 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
08-31 16:51:25.712   321  6531 D QC-time-services: Updating the TOD offset
08-31 16:51:25.712   321  6531 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100776696 to memory
08-31 16:51:25.712   321  6531 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-31 16:51:25.712   321  6531 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-31 16:51:25.715   321  6531 E QC-time-services: Daemon:Update to modem bit set
08-31 16:51:25.715   321  6531 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-31 16:51:25.715   321  6531 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124135976696
08-31 16:51:25.716  6487  6487 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-31 16:51:25.719   321  1052 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-31 16:51:25.719   321  1055 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-31 16:51:25.723   959  1351 D qdlights: set_light_backlight: 0
08-31 16:51:25.740   959  1061 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,08-31 16:51:25.753  6462  6493 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
08-31 16:51:25.755   959  1061 I sensors_hal_Ctx: activate: handle is 46, disable
08-31 16:51:25.755   959  1061 V sensors_hal_Ctx: activate sensors is 1000000000000
08-31 16:51:25.755   959  1061 D sensors_hal_LP2: enable: handle=46
08-31 16:51:25.755   959  1061 D sensors_hal_LP2: enable: Disabling sensor handle=46
08-31 16:51:25.755   959  1061 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
08-31 16:51:25.759   249   249 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
08-31 16:51:25.759   249   249 D qdhwcomposer: hwc_blank: Blanking display: 0
08-31 16:51:25.760   959  1059 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
08-31 16:51:25.760   959   959 V ActivityManager: Display changed displayId=0
,08-31 16:51:25.789  1753  1753 D DSDPConnection: Display #0 changed.
,08-31 16:51:25.801  6221  6241 D UEI.SmartControl: Internal timer expired: 1
08-31 16:51:25.808  6510  6510 I AppUp4:AppBoxCP: onCreate
,08-31 16:51:25.811  6510  6510 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-31 16:51:25.823  6510  6510 I AppUp4:DB:  setFingerPrint start
08-31 16:51:25.823  6510  6510 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,08-31 16:51:25.830   959  1640 I ActivityManager: Process com.google.android.apps.plus (pid 6300) has died
08-31 16:51:25.831   959  1028 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
08-31 16:51:25.831   959  1028 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
08-31 16:51:25.832  6510  6510 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
08-31 16:51:25.832  6510  6510 I AppUp4:DB:  SDK version = 21
08-31 16:51:25.832  6510  6510 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-31 16:51:25.835  6462  6462 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
08-31 16:51:25.841  6462  6462 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
08-31 16:51:25.841  6221  6221 D UEI.SmartControl: Service.onUnbind: IControl
08-31 16:51:25.841  6221  6221 D UEI.SmartControl: Service.onDestroy
08-31 16:51:25.846  6221  6221 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@3fcd6b1a
08-31 16:51:25.847  6221  6221 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
08-31 16:51:25.847  6221  6221 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
08-31 16:51:25.847  6221  6221 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-31 16:51:25.847  6221  6221 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-31 16:51:25.847  6221  6221 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-31 16:51:25.847  6221  6221 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
08-31 16:51:25.847  6221  6221 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
08-31 16:51:25.847  6221  6221 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
08-31 16:51:25.847  6221  6221 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:25.847  6221  6221 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 16:51:25.847  6221  6221 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-31 16:51:25.847  6221  6221 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:25.847  6221  6221 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:25.847  6221  6221 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-31 16:51:25.847  6221  6221 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-31 16:51:25.847  6221  6221 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@3fcd6b1a
08-31 16:51:25.851  6221  6221 D UEI.SmartControl: Shutdown IRRCPlayer... 
,08-31 16:51:25.852  6510  6510 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-31 16:51:25.852  6462  6462 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-31 16:51:25.854  6462  6462 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-31 16:51:25.865  6462  6462 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,08-31 16:51:25.868  6221  6221 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
08-31 16:51:25.868  6221  6221 D irrcClient: ~IrrcClient ++ 
08-31 16:51:25.868  6221  6221 D irrcClient: ~IrrcClient -- 
08-31 16:51:25.869  6221  6221 W irrc_jni: IRRCPlayer_nativeFinalize -- 
08-31 16:51:25.869  6221  6221 D UEI.SmartControl: Blaster closed
08-31 16:51:25.869  6221  6221 D UEI.SmartControl: Blaster closed
08-31 16:51:25.870  6221  6221 D UEI.SmartControl: Shut down QS...
08-31 16:51:25.870  6221  6221 D UEI.SmartControl: Stopped file observer...
08-31 16:51:25.895  6510  6510 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 16:51:25.895  6510  6510 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:25.910  6510  6510 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 16:51:25.911  6510  6510 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 16:51:25.913  6221  6221 I UEI.SmartControl: QS lib stop result = true
08-31 16:51:25.914  6221  6221 D UEI.SmartControl: QS shutdown complete
,08-31 16:51:25.923  6378  6394 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:25.923  6378  6394 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:25.925  6510  6510 I AppUp4:CustModeStarterReceiver: onReceive
08-31 16:51:25.925  6510  6510 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:25.936  6510  6510 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3425e62f
08-31 16:51:25.936  6510  6510 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-31 16:51:25.941   959  1805 I ActivityManager: Killing 6052:com.lge.sync/1000 (adj 15): empty #11
,08-31 16:51:25.953   249   249 D qdhwcomposer: hwc_blank: Done blanking display: 0
,08-31 16:51:25.953   959  1351 D SurfaceControl: Excessive delay in setPowerMode(): 194ms
08-31 16:51:25.957   249   686 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-31 16:51:25.957   959  1351 I QCOM PowerHAL: Got set_interactive hint
08-31 16:51:25.972  1373  1612 D KeyguardViewMediator: onScreenTurnedOff(3)
,08-31 16:51:25.981  1332  1349 D SmartCoverViewMediator: onScreenTurnedOff(3)
08-31 16:51:25.986  1373  1612 D KeyguardViewMediator: notifyScreenOffLocked
,08-31 16:51:25.992  1332  1349 D SmartCoverViewMediator: notifyScreenOffLocked
08-31 16:51:25.995  1332  1332 D SmartCoverViewMediator: handleNotifyScreenOFF
08-31 16:51:26.093   959   983 W libprocessgroup: failed to open /acct/uid_1000/pid_6052/cgroup.procs: No such file or directory
,08-31 16:51:26.093  6510  6510 D AppUp4:CustFacade: isSimDevice : true
08-31 16:51:26.101  5843  5843 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-31 16:51:26.103  5843  5843 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
08-31 16:51:26.105  6510  6510 D AppUp4:CustModeStarterReceiver: begin check event
,08-31 16:51:26.108  6510  6510 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-31 16:51:26.114  6510  6510 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-31 16:51:26.115  1373  1612 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
08-31 16:51:26.115  1373  1373 D KeyguardViewMediator: handleNotifyScreenOff
08-31 16:51:26.123  6510  6535 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-31 16:51:26.123  6510  6535 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-31 16:51:26.124  6510  6535 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-31 16:51:26.132  5843  5843 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1373a3c3 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1722ccc6, 16908290=android.view.AbsSavedState$1@1722ccc6}, android:focusedViewId=100}]}]
08-31 16:51:26.132  5843  5843 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-31 16:51:26.134  5843  5843 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 16:51:26.134  5843  5843 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-31 16:51:26.145  1373  1373 D ScreenTurnOffBySensor: unregisterProximitySensor
,08-31 16:51:26.157  1373  1373 D StatusBarWindowView: onScreenTurnedOff why = 3
08-31 16:51:26.208  3113  3113 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 16:51:26.208  3113  3113 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:26.222  3113  3113 I LgeMiscReceiver: networkInfo.isConnected() = true
,08-31 16:51:26.245  3113  3113 D PhoneState: setPdpRejectCasuse : false
,08-31 16:51:26.290  5513  5513 I art     : Explicit concurrent mark sweep GC freed 25640(1835KB) AllocSpace objects, 28(448KB) LOS objects, 25% free, 14MB/19MB, paused 1.053ms total 135.534ms
,08-31 16:51:26.295   959  2065 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6538 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,08-31 16:51:26.423   959  1805 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6556 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,08-31 16:51:26.434  5532  6345 I art     : Explicit concurrent mark sweep GC freed 2445(96KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 768us total 71.669ms
08-31 16:51:26.560   959  1640 I ActivityManager: Process com.lge.clock (pid 6407) has died
,08-31 16:51:26.619  5843  5935 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 16:51:26.619  5843  5935 I jxcore-log: 
08-31 16:51:26.620  6538  6538 D PhoneMonitor: Register our PhoneStateListener
,08-31 16:51:26.667  6538  6538 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-31 16:51:26.675  6538  6538 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 16:51:26.722  3138  3138 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:26.740  3138  3138 V DownloadManager: DownloadService onCreate
08-31 16:51:26.742   420   438 I Sensors : sns_pwr.c(301):releasing wakelock
,08-31 16:51:26.744  3138  6581 I DownloadManager: in removeSpuriousFiles
08-31 16:51:26.753  3138  3138 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
,08-31 16:51:26.753  3138  6581 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-31 16:51:26.756  3138  6581 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@33b87e7a on behalf of 3138
08-31 16:51:26.761  6538  6538 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-31 16:51:26.764  3138  6581 I DownloadManager: in trimDatabase
08-31 16:51:26.765  3138  6581 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-31 16:51:26.767  3138  6581 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@873362b on behalf of 3138
,08-31 16:51:26.780   959  1350 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6584 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-31 16:51:26.823  3138  3138 V DownloadManager: DownloadService onStartCommand
,08-31 16:51:26.828  6556  6556 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
08-31 16:51:26.835   959  1879 I ActivityManager: Killing 6221:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
08-31 16:51:26.838  6556  6556 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
,08-31 16:51:26.842  6538  6538 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-31 16:51:26.857  6538  6538 D TelephonyAutoProfiling: [parse] Load xml
,08-31 16:51:26.867  3138  6582 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-31 16:51:26.873  3138  6582 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2f400846 on behalf of 3138
08-31 16:51:26.873  1735  2339 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:26.873  1735  2339 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:26.873  1735  2339 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:26.874  1735  2339 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:26.874   287  1045 E BandwidthController: [LG DATA] No such appUid: 10006
08-31 16:51:26.874   287  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,08-31 16:51:26.874   287  6603 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-31 16:51:26.874   287  6603 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:26.875   287  6603 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-31 16:51:26.875   287  6603 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-31 16:51:26.877  6538  6538 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 16:51:26.878  6538  6538 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
08-31 16:51:26.886  6538  6538 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-31 16:51:27.076   959  1848 W libprocessgroup: failed to open /acct/uid_10089/pid_6221/cgroup.procs: No such file or directory
08-31 16:51:27.079  1373  1373 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-31 16:51:27.079  1373  1373 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-31 16:51:27.081  1373  1373 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
08-31 16:51:27.083  1332  1332 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
08-31 16:51:27.084  3138  3138 V DownloadManager: DownloadService onDestroy
08-31 16:51:27.088  6556  6556 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
,08-31 16:51:27.088  6556  6556 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
,08-31 16:51:27.089  6556  6556 V [BNRBootReceiver]: Boot Receiver Return
08-31 16:51:27.090  6556  6556 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 16:51:27.091   959  1848 I ActivityManager: Killing 6284:com.android.gallery3d/u0a23 (adj 15): empty #11
08-31 16:51:27.114  5843  5935 I jxcore-log: ERROR runTests: 
08-31 16:51:27.114  5843  5935 I jxcore-log: 
,08-31 16:51:27.120  5843  5935 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:51:27.120  5843  5935 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-31 16:51:27.121  5843  5935 I jxcore-log: WARN testUtils: logCallback not set!
08-31 16:51:27.121  5843  5935 I jxcore-log: 
08-31 16:51:27.127  6584  6584 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
08-31 16:51:27.128  6584  6584 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,08-31 16:51:27.137  5843  5935 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _functionName: 'loadFile',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _lineNumber: '26',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _columnNumber: '11',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 16:51:27.137  5843  5935 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _functionName: '',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _lineNumber: '38',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _columnNumber: '7',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 16:51:27.137  5843  5935 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _functionName: '',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _lineNumber: '35',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _columnNumber: '3',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 16:51:27.137  5843  5935 I jxcore-log:   { _fileName: 'module.js',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _lineNumber: '621',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _columnNumber: '8',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 16:51:27.137  5843  5935 I jxcore-log:   { _fileName: 'module.js',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _lineNumber: '651',
08-31 16:51:27.137  5843  5935 I jxcore-log:     _columnNumber: '1',
08-31 16:51:27.137  5843  5935 I jxcore-log:    
08-31 16:51:27.137  5843  5935 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 16:51:27.137  5843  5935 I jxcore-log: 
08-31 16:51:27.138  5843  5935 E jxcore-log: Error: 
08-31 16:51:27.138  5843  5935 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:51:27.138  5843  5935 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 16:51:27.138  5843  5935 E jxcore-log: 
08-31 16:51:27.140  5843  5935 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 16:51:27.140  5843  5935 I jxcore-log: 
08-31 16:51:27.141  5843  5935 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 16:51:27.141  5843  5935 I jxcore-log: 
,08-31 16:51:27.142  5843  5935 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 16:51:27.142  5843  5935 I jxcore-log: 
08-31 16:51:27.208   959   982 W libprocessgroup: failed to open /acct/uid_10023/pid_6284/cgroup.procs: No such file or directory
,08-31 16:51:27.212  2842  2842 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:51:27
08-31 16:51:27.213  6584  6584 V DrmService: Service onCreate
08-31 16:51:27.213  6584  6584 D DrmService: Received new request = 2
08-31 16:51:27.214  2842  2842 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 16:51:27.216  2842  2842 D WeatherAncestor: connectivity changed - connection : true
08-31 16:51:27.221   959   959 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
,08-31 16:51:27.225  2842  2842 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 16:51:27.226  2842  2842 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:51:27
08-31 16:51:27.226  2842  2842 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:27.227  2842  2842 D WeatherService: 2 : shouldTimeTickRegistered : false
08-31 16:51:27.230   291   291 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 959
08-31 16:51:27.230   291   291 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-31 16:51:27.230   291   291 V voice   : voice_set_parameters: enter: screen_state=on
08-31 16:51:27.230   291   291 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
08-31 16:51:27.230   291   291 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 16:51:27.230   291   291 V voice   : voice_set_parameters: exit with code(0)
08-31 16:51:27.230   291   291 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
08-31 16:51:27.231   291   291 V msm8974_platform: platform_set_parameters: enter: screen_state=on
08-31 16:51:27.231   291   291 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 16:51:27.231   291   291 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 16:51:27.231   291   291 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
08-31 16:51:27.231   291   291 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-31 16:51:27.231   291   291 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 16:51:27.233  6584  6606 I DrmSntpClient: Start Sync process
08-31 16:51:27.233  6584  6606 D DrmSntpClient: Server : 0
08-31 16:51:27.234   959  1310 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
08-31 16:51:27.237  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
,08-31 16:51:27.238   959  1035 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
08-31 16:51:27.251  1735  6607 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:27.251  6584  6606 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:27.251  6584  6606 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:27.252  6584  6606 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,08-31 16:51:27.252  6584  6606 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:27.253  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
08-31 16:51:27.253   287  1045 E BandwidthController: [LG DATA] No such appUid: 10051
08-31 16:51:27.253   287  1045 D DnsProxyListener: App 10051 tries DNS query. Accept family:0 protocol:0
08-31 16:51:27.254   287  6608 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-31 16:51:27.254  1735  6607 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:27.254   287  6608 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:27.254   287  6608 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-31 16:51:27.254   287  6608 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-31 16:51:27.256  1735  6607 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:27.256  1735  6607 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:27.256   287  1045 E BandwidthController: [LG DATA] No such appUid: 10006
08-31 16:51:27.256   287  1045 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-31 16:51:27.257   287  6609 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-31 16:51:27.257   287  6609 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:27.257   287  6609 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-31 16:51:27.259  1841  1841 I QCNEJ   : |CORE| sendScreenState: state:true
08-31 16:51:27.260   287  6609 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,08-31 16:51:27.272  1806  1966 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-31 16:51:27.279  1806  1966 D LEDService: stopPatternFlashing()
08-31 16:51:27.281  1806  1966 D qdlights: set_light_notifications: 0,0,0,0,3
08-31 16:51:27.286  1806  1966 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-31 16:51:27.287  1806  1966 D qdlights: set_light_notifications: 0,0,0,0,3
08-31 16:51:27.289  1806  1966 I LEDService: updateLightsLocked : turn off led
08-31 16:51:27.289  1806  1966 D qdlights: set_light_notifications: 0,0,0,0,3
08-31 16:51:27.292  1806  1966 D LEDHandler: RESTART MSG
,08-31 16:51:27.319   959  1640 D SplitWindow: check instance of lgWin Window{179644b5 u0 SearchPanel}
,08-31 16:51:27.326  1806  1806 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
08-31 16:51:27.327  1806  1806 D Cliptray Service: lockStatus = 0
08-31 16:51:27.422   291  1606 I WVCdm   : CdmEngine::CloseSession
,08-31 16:51:27.426   291  1606 I WVCdm   : L3 Terminate.
08-31 16:51:27.447   959  6517 I art     : Explicit concurrent mark sweep GC freed 15949(782KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.711ms total 170.097ms
,08-31 16:51:27.460   959  1640 D InputDispatcher: Window went away: Window{372e2fdc u0 SearchPanel}
,08-31 16:51:27.463  1373  1373 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
08-31 16:51:27.483  1373  1373 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-31 16:51:27.491  5513  6612 I CheckinService: Disabling old GoogleServicesFramework version
08-31 16:51:27.492  1788  1788 D LNfcService: action : android.intent.action.SCREEN_ON
08-31 16:51:27.500  1788  6613 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
08-31 16:51:27.500  1788  6613 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
08-31 16:51:27.500  1788  6613 D LNfcService: isRequireNfcCRouting() return true
,08-31 16:51:27.505  1788  6613 D LNfcService: isHCERoutingtoHost() return : true
08-31 16:51:27.506  1788  6613 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-31 16:51:27.506  1788  6613 D NfcService: mEnableLPD: true
08-31 16:51:27.506  1788  6613 D NfcService: mEnableReader: false
08-31 16:51:27.506  1788  6613 D NfcService: mEnableHostRouting: true
08-31 16:51:27.506  1788  6613 D NfcService: newParams.techmask= mTechMask: default
08-31 16:51:27.506  1788  6613 D NfcService: mEnableLPD: true
08-31 16:51:27.506  1788  6613 D NfcService: mEnableReader: false
08-31 16:51:27.506  1788  6613 D NfcService: mEnableHostRouting: true
08-31 16:51:27.506  1788  6613 D NfcService: screenState= 3
08-31 16:51:27.506  1788  6613 D NfcService: Discovery configuration equal, not updating.
08-31 16:51:27.509   959   959 D Ulp_jni : JNI:system_update. Event-0
,08-31 16:51:27.529  1753  1753 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,08-31 16:51:27.541  2842  2842 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:51:27
08-31 16:51:27.543  2842  2842 D WeatherService: 2 : ACTION screen on
,08-31 16:51:27.544  2842  2842 D WeatherService: 2 : shouldTimeTickRegistered : false
08-31 16:51:27.544  2842  2842 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 16:51:27.544  2842  2842 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:51:27
08-31 16:51:27.559  3965  3965 D AppCleanupService: android.intent.action.SCREEN_ON
,08-31 16:51:27.575   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:27.575   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 16:51:27.576   959   959 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
08-31 16:51:27.592  5513  6617 I iu.SyncManager: SYNC; picasa accounts
,08-31 16:51:27.597  5513  6615 I CheckinChimeraService: Checking schedule, now: 1472655087597 next: 1472652330526
08-31 16:51:27.600  5513  6615 I CheckinChimeraService: active receiver: enabled
08-31 16:51:27.602  5513  6615 I CheckinChimeraService: Preparing to send checkin request
08-31 16:51:27.602  5513  6615 I EventLogChimeraService: Accumulating logs since 1472653482877
08-31 16:51:27.640  5513  5513 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-31 16:51:27.645  6604  6604 D AndroidRuntime: 
08-31 16:51:27.645  6604  6604 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 16:51:27.650  5513  5513 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 16:51:27.663   291  1296 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 959
08-31 16:51:27.663  6604  6604 D AndroidRuntime: CheckJNI is OFF
08-31 16:51:27.665   291  1296 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-31 16:51:27.665   291  1296 V voice   : voice_set_parameters: enter: screen_state=off
08-31 16:51:27.665   291  1296 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
08-31 16:51:27.665   291  1296 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 16:51:27.665   291  1296 V voice   : voice_set_parameters: exit with code(0)
08-31 16:51:27.665   291  1296 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
08-31 16:51:27.665   291  1296 V msm8974_platform: platform_set_parameters: enter: screen_state=off
08-31 16:51:27.665   291  1296 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 16:51:27.665   291  1296 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 16:51:27.665   291  1296 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-31 16:51:27.665   291  1296 V audio_hw_primary: adev_set_parameters: exit with code(0)
,08-31 16:51:27.667   959  1315 D WifiController: CMD_SCREEN_OFF 
08-31 16:51:27.667   959  1315 D WifiController: shouldWifiStayAwake TRUE
08-31 16:51:27.671  5513  6617 I iu.UploadsManager: num queued entries: 0
08-31 16:51:27.672  5513  6617 I iu.UploadsManager: num updated entries: 0
08-31 16:51:27.673  5513  6617 I iu.SyncManager: NEXT; no task
08-31 16:51:27.676   959  1035 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
08-31 16:51:27.676  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,08-31 16:51:27.720   959   982 I ActivityManager: Process com.google.android.music:main (pid 6250) has died
,08-31 16:51:27.724  1841  1841 I QCNEJ   : |CORE| sendScreenState: state:false
08-31 16:51:27.725  1806  1966 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-31 16:51:27.726  1806  1806 D VolumeVibrator: clear
08-31 16:51:27.726  1806  1966 D LEDService: stopPatternFlashing()
08-31 16:51:27.726  1806  1966 D qdlights: set_light_notifications: 0,0,0,0,3
08-31 16:51:27.728  1806  1966 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-31 16:51:27.728  1806  1966 D qdlights: set_light_notifications: 0,0,0,0,3
08-31 16:51:27.730  1806  1966 I LEDService: updateLightsLocked : turn on led
08-31 16:51:27.730  1806  1966 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
08-31 16:51:27.731  1806  1966 E LEDService: Can't handle this request of patternId:0
08-31 16:51:27.731  1806  1966 D LEDHandler: RESTART MSG
08-31 16:51:27.732  1806  1806 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
08-31 16:51:27.735  1788  1788 D LNfcService: action : android.intent.action.SCREEN_OFF
,08-31 16:51:27.741  1788  2208 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
08-31 16:51:27.760  1880  1880 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,08-31 16:51:27.793   959  1823 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6621 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 16:51:27.808  1753  1753 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,08-31 16:51:27.814  2842  2842 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:51:27
08-31 16:51:27.814  2842  2842 D WeatherService: 2 : ACTION screen off
08-31 16:51:27.814  2842  2842 D WeatherService: 2 : TimeTick Receiver Unregister
08-31 16:51:27.815  2842  2842 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:51:27
08-31 16:51:27.826  3965  3965 D AppCleanupService: android.intent.action.SCREEN_OFF
,08-31 16:51:27.840  3965  6641 D AppCleanupService: AppUsageStatsSaveTask
08-31 16:51:27.843  1788  2686 E NxpNfcJni: getReconnectState = 0x0
,08-31 16:51:27.850   959   959 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:27.851   959   959 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:27.851   959   959 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
08-31 16:51:27.852  1788  2208 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-31 16:51:27.852  1788  2208 D LCardEmulationManager: getDefaultRoute
08-31 16:51:27.853  1788  2208 D LNfcService: isRequireNfcCRouting() return true
08-31 16:51:27.853  1788  2208 D LNfcService: isHCERoutingtoHost() return : true
08-31 16:51:27.853  1788  2208 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-31 16:51:27.853  1788  2208 D NfcService: mEnableLPD: true
08-31 16:51:27.853  1788  2208 D NfcService: mEnableReader: false
08-31 16:51:27.853  1788  2208 D NfcService: mEnableHostRouting: true
08-31 16:51:27.853  1788  2208 D NfcService: newParams.techmask= mTechMask: 0
08-31 16:51:27.853  1788  2208 D NfcService: mEnableLPD: true
08-31 16:51:27.853  1788  2208 D NfcService: mEnableReader: false
08-31 16:51:27.853  1788  2208 D NfcService: mEnableHostRouting: true
08-31 16:51:27.853  1788  2208 D NfcService: screenState= 1
,08-31 16:51:27.900   959  2283 I ActivityManager: Process com.lge.email (pid 6356) has died
,08-31 16:51:27.920  1788  2686 E NxpNfcJni: getReconnectState = 0x0
,08-31 16:51:27.957  6621  6621 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 16:51:28.066  5513  6615 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,08-31 16:51:28.075  5513  6615 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,08-31 16:51:28.096  6604  6604 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 16:51:28.141   959  1037 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-31 16:51:28.144   959  1037 I ActivityManager: Killing 5843:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-31 16:51:28.204   959  1383 I WindowState: WIN DEATH: Window{7a2eca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 16:51:28.207   959  1383 D InputDispatcher: Focus left window: Window{7a2eca u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 16:51:28.207   959  1383 D InputDispatcher: Window went away: Window{7a2eca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 16:51:28.245   959  1067 W PackageSettings: Skipping PackageSetting{315c6f76 com.example.hello/10317} due to missing metadata
,08-31 16:51:28.408   959  1037 I ActivityManager:   Force finishing activity ActivityRecord{2df6c5e0 u0 com.test.thalitest/.MainActivity t259}
,08-31 16:51:28.419   959   959 V ActivityManager: Display changed displayId=0
08-31 16:51:28.422  1753  1753 D DSDPConnection: Display #0 changed.
,08-31 16:51:28.430   959   982 W ActivityManager: Spurious death for ProcessRecord{15b37731 5843:com.test.thalitest/u0a30}, curProc for 5843: null
,08-31 16:51:28.451   959  1067 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-31 16:51:28.462  6621  6638 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3c0
,08-31 16:51:28.488  6621  6638 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3a0
,08-31 16:51:28.515  1880  1880 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-31 16:51:28.517  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-31 16:51:28.526  1735  2393 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 16:51:28.528  3452  3452 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-31 16:51:28.531  1841  1841 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-31 16:51:28.537  3452  3452 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-31 16:51:28.537  3452  3452 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-31 16:51:28.537  3452  3452 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-31 16:51:28.537  3452  3452 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 16:51:28.537  3452  3452 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 16:51:28.537  3452  3452 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 16:51:28.537  3452  3452 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-31 16:51:28.537  3452  3452 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:28.537  3452  3452 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:28.537  3452  3452 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-31 16:51:28.537  3452  3452 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-31 16:51:28.543  1967  1967 I art     : Explicit concurrent mark sweep GC freed 1183(87KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 11.464ms total 85.341ms
,08-31 16:51:28.554  1880  1880 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-31 16:51:28.596   959  2283 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6667 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:28.599   959  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 16:51:28.607  1880  1880 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
,08-31 16:51:28.618  1880  2023 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=4ms
08-31 16:51:28.625  6621  6674 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-31 16:51:28.625  6621  6674 I Babel_SMS: MmsConfig.loadMmsSettings
08-31 16:51:28.645  1373  1373 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-31 16:51:28.647  1880  1880 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-31 16:51:28.648  1880  1880 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-31 16:51:28.648  1880  1880 I Activity: Activity.onPostResume() called 
08-31 16:51:28.654  6621  6674 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
08-31 16:51:28.654  6621  6674 I Babel_SMS: MmsConfig.loadFromDatabase
08-31 16:51:28.668  1880  1880 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,08-31 16:51:28.678  1880  6687 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,08-31 16:51:28.711  1373  1373 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-31 16:51:28.711  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-31 16:51:28.715   302   362 I ThermalEngine: Sensor:pa_therm0:34000 mC
08-31 16:51:28.716  6621  6674 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-31 16:51:28.716  6621  6674 I Babel_SMS: MmsConfig.loadFromResources
08-31 16:51:28.718  6621  6674 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-31 16:51:28.718  6621  6674 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,08-31 16:51:28.725   959  1057 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
,08-31 16:51:28.725   959  1057 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-31 16:51:28.725  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-31 16:51:28.726  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-31 16:51:28.726  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-31 16:51:28.726  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-31 16:51:28.726   959  1057 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-31 16:51:28.726   959  1057 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-31 16:51:28.726   959  1057 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 16:51:28.726   959  1057 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3303d4c5,  pkg=WindowManager.LayoutParams
08-31 16:51:28.726   959  1057 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-31 16:51:28.727   959   983 D InputDispatcher: Focus entered window: Window{25e2c55 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-31 16:51:28.746  1880  1880 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 16:51:28.753   959   959 D administrator: Handling package changes for user 0
08-31 16:51:28.754  6667  6667 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-31 16:51:28.756  1880  1880 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 16:51:28.756  1880  1880 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-31 16:51:28.770  1880  1880 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-31 16:51:28.771  1880  1880 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-31 16:51:28.792  1373  1503 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-31 16:51:28.792  1373  1503 D KeyguardModel: createShortcutInfo...
08-31 16:51:28.794  1373  1503 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 16:51:28.795  1373  1503 D KeyguardModel: createShortcutInfo...
,08-31 16:51:28.797  1373  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:28.797  1373  1503 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-31 16:51:28.803  1373  1503 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 16:51:28.803  1373  1503 D KeyguardModel: createShortcutInfo...
08-31 16:51:28.805  1373  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:28.805  1373  1503 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 16:51:28.807  1373  1503 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 16:51:28.807  1373  1503 D KeyguardModel: createShortcutInfo...
08-31 16:51:28.809  1373  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:28.810  1373  1503 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-31 16:51:28.814  1373  1503 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 16:51:28.814  1373  1503 D KeyguardModel: createShortcutInfo...
08-31 16:51:28.824  1373  1373 D KeyguardModel: handleShortcutListChanged...
,08-31 16:51:28.828  6621  6621 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
08-31 16:51:28.828  6621  6621 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
08-31 16:51:28.828  6621  6621 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
08-31 16:51:28.829  6621  6621 D SensorManager: found sensor: Motion Accel, handle=46
08-31 16:51:28.831  1373  1503 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 16:51:28.831  1373  1503 D KeyguardModel: createShortcutInfo...
08-31 16:51:28.835  1373  1503 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 16:51:28.835  1373  1503 D KeyguardModel: createShortcutInfo...
08-31 16:51:28.837  1373  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:28.837  1373  1503 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-31 16:51:28.842  1373  1503 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 16:51:28.842  1373  1503 D KeyguardModel: createShortcutInfo...
08-31 16:51:28.844  1373  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:28.845  1373  1503 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 16:51:28.846  1373  1503 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 16:51:28.846  1373  1503 D KeyguardModel: createShortcutInfo...
08-31 16:51:28.847  1373  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:28.848  1373  1503 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 16:51:28.850  1373  1503 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 16:51:28.850  1373  1503 D KeyguardModel: createShortcutInfo...
,08-31 16:51:28.864  1373  1373 D KeyguardModel: handleShortcutListChanged...
08-31 16:51:28.921  6621  6621 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 16:51:28.927  6621  6621 I Babel_Crash: startup - clean
08-31 16:51:28.946   959  1067 I art     : Explicit concurrent mark sweep GC freed 32179(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 4.339ms total 404.776ms
,08-31 16:51:28.953   959  2154 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-31 16:51:28.955   959  2154 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5843 uid 10030
08-31 16:51:28.958  1880  1880 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,08-31 16:51:28.975  6621  6693 I Babel   : deleted: false for 0
,08-31 16:51:29.035  1880  1880 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
,08-31 16:51:29.054   959  1059 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3a8b086d u0 com.lge.launcher2/.Launcher t258} time:158723
,08-31 16:51:29.055  1880  1880 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-31 16:51:29.081  1967  1967 I HotwordDetector: Closing mic
,08-31 16:51:29.103  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,08-31 16:51:29.109  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-31 16:51:29.113  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-31 16:51:29.116  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-31 16:51:29.136  1967  2480 I HotwordRecognitionRnr: Stopping hotword detection.
,08-31 16:51:29.166  1880  1880 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,08-31 16:51:29.188   959   982 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6700 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:29.191  1788  1788 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-31 16:51:29.191  1788  1788 D LCardEmulationManager: getDefaultRoute
08-31 16:51:29.210   310   310 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 21.365ms
,08-31 16:51:29.215  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-31 16:51:29.216  1880  1880 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
08-31 16:51:29.216  1880  1880 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-31 16:51:29.225   291  1296 I WVCdm   : CdmEngine::OpenSession
08-31 16:51:29.225   291  1296 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,08-31 16:51:29.232   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 21.355ms
08-31 16:51:29.253   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.088ms
,08-31 16:51:29.255  6604  6604 D AndroidRuntime: Shutting down VM
08-31 16:51:29.266  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
08-31 16:51:29.270   959   959 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-31 16:51:29.270   959   959 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 16:51:29.272  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
08-31 16:51:29.273  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
08-31 16:51:29.273  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
08-31 16:51:29.276   959   959 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 16:51:29.277  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,08-31 16:51:29.285   291  1296 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
08-31 16:51:29.285   291  1296 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
08-31 16:51:29.285   291  1296 W WVCdm   : L1 library not specified. Falling Back to L3
08-31 16:51:29.288   959  1352 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-31 16:51:29.288  6621  6621 W AudioCapabilities: Unsupported mime audio/x-lg-flac
08-31 16:51:29.291  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
08-31 16:51:29.292  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,08-31 16:51:29.294  6621  6621 W AudioCapabilities: Unsupported mime audio/adpcm
08-31 16:51:29.295  6621  6621 W AudioCapabilities: Unsupported mime audio/g726
08-31 16:51:29.296  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
08-31 16:51:29.297  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
08-31 16:51:29.298  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
08-31 16:51:29.301  6621  6621 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-31 16:51:29.303  6621  6621 W AudioCapabilities: Unsupported mime audio/wma-voice
08-31 16:51:29.304  6621  6621 W VideoCapabilities: Unsupported mime video/mjpg
08-31 16:51:29.308  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
08-31 16:51:29.311  6621  6621 W VideoCapabilities: Unsupported mime video/theora
,08-31 16:51:29.318  1880  1880 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
08-31 16:51:29.367  6621  6621 W AudioCapabilities: Unsupported mime audio/evrc
08-31 16:51:29.371  6621  6621 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 16:51:29.373  6621  6621 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-31 16:51:29.382  6621  6621 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-31 16:51:29.384  6621  6621 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 16:51:29.386  6621  6621 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 16:51:29.413   291  1296 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-31 16:51:29.414   291  1611 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-31 16:51:29.414   291  1611 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-31 16:51:29.414   291  1611 I WVCdm   : CdmEngine::GenerateKeyRequest
08-31 16:51:29.416  6621  6621 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-31 16:51:29.440   291  1611 D WVCdm   : PrepareKeyRequest: nonce=3966684834
,08-31 16:51:29.454  1880  1880 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
08-31 16:51:29.467  6621  6621 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 16:51:29.496  6621  6621 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-31 16:51:29.498  6621  6621 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:29.508  6621  6621 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-31 16:51:29.521  6621  6621 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:29.540  6621  6621 I vclib   : onServiceConnected
08-31 16:51:29.541  6621  6621 W Babel   : Attempted to change video mute state without an active call.
08-31 16:51:29.545  1880  1880 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-31 16:51:29.545  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
08-31 16:51:29.546  1880  1880 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
08-31 16:51:29.546  1880  1880 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,08-31 16:51:29.558  6621  6621 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
08-31 16:51:29.561  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-31 16:51:29.563  1880  1880 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-31 16:51:29.563  1880  1880 I Choreographer: Skipped 30 frames!  The application may be doing too much work on its main thread.
08-31 16:51:29.567  6621  6719 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,08-31 16:51:29.569  1880  1880 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-31 16:51:29.571  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-31 16:51:29.572  6621  6719 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-31 16:51:29.572  6621  6719 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-31 16:51:29.573  6621  6719 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:29.573   287  1045 E BandwidthController: [LG DATA] No such appUid: 10061
08-31 16:51:29.573   287  1045 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
08-31 16:51:29.573   287  6721 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-31 16:51:29.573  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
08-31 16:51:29.573   287  6721 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-31 16:51:29.574   287  6721 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-31 16:51:29.574   287  6721 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-31 16:51:29.574   287  6721 D libc-netbsd: res_queryN name = xxxxx succeed
08-31 16:51:29.575  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-31 16:51:29.577  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
08-31 16:51:29.577  6621  6719 I System.out: propertyValue:false
08-31 16:51:29.578  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
,08-31 16:51:29.588  1880  1880 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-31 16:51:29.589  1880  1880 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
08-31 16:51:29.599  1631  1631 E b       : Unable to connect to the editor to retrieve text... will retry later
,08-31 16:51:29.618  1880  2443 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-31 16:51:29.618  1880  2443 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-31 16:51:29.625   959  1067 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6723 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-31 16:51:29.650  1735  2309 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/sizeCache.xml
,08-31 16:51:29.666  1880  1880 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,08-31 16:51:29.693  1880  1880 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-31 16:51:29.693  1880  1880 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-31 16:51:29.693  1880  1880 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-31 16:51:29.694  1880  1880 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume

```
