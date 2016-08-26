#### Test 8286536244f8192_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-26 14:59:46.839   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 114441216990; DSPS: 3841912; Offset : -2814295637
,08-26 14:59:47.503  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 14:59:47.503  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 14:59:47.503  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-26 14:59:47.563  6218  6218 D AndroidRuntime: 
08-26 14:59:47.563  6218  6218 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 14:59:47.571  6218  6218 D AndroidRuntime: CheckJNI is OFF
08-26 14:59:47.901  6218  6218 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 14:59:47.921   834  1832 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 14:59:47.977   834  1832 D ActivityManager: setTaskToReturnTo : TaskRecord{1a14f1b8 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 14:59:47.980   834  1832 D ActivityManager: setTaskToReturnTo : TaskRecord{1a14f1b8 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 14:59:48.005   834  1832 D WindowStateEx: AppWindowTokenEx init.. 
08-26 14:59:48.017   834  1035 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 14:59:48.038   834  1035 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 14:59:48.053  1880  1880 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-26 14:59:48.056   834  1832 D InputDispatcher: Focus left window: Window{c7728be u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-26 14:59:48.057  6218  6218 D AndroidRuntime: Shutting down VM
08-26 14:59:48.065   834  1035 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 14:59:48.065   834  1035 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-26 14:59:48.086   834  1035 D SplitWindow: check instance of lgWin Window{1c383fd0 u0 Starting com.test.thalitest}
08-26 14:59:48.138   834  2133 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6238 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 14:59:48.150  1880  1880 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-26 14:59:48.212  1948  1948 I HotwordDetector: Closing mic
08-26 14:59:48.215  1880  1880 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-26 14:59:48.218  1948  2402 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2b0b2cf8
08-26 14:59:48.218  1948  2402 V AudioRecord: stop()
08-26 14:59:48.218  1948  2402 D AudioRecord: AudioRecord->stop()
08-26 14:59:48.218   287   287 V AudioFlinger: RecordHandle::stop()
08-26 14:59:48.218   287   287 V AudioFlinger: RecordThread::stop
08-26 14:59:48.225   287   287 V AudioFlinger: Record stopped OK
08-26 14:59:48.227   287   287 V AudioPolicyManager: stopInput() input 17
08-26 14:59:48.227   287   287 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-26 14:59:48.228   287   287 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-26 14:59:48.228   287  1061 V AudioPolicyService: AudioCommandThread() waking up
08-26 14:59:48.228   287  1061 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-26 14:59:48.228   287  1061 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
08-26 14:59:48.228   287  1061 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-26 14:59:48.228   287  1061 V AudioFlinger: ThreadBase::setParameters() routing=0
08-26 14:59:48.228   287  1061 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-26 14:59:48.229   834  1859 I WindowStateAnimator: Starting window displayed
08-26 14:59:48.230   287  2468 V AudioFlinger: processConfigEvents_l() remaining events 1
08-26 14:59:48.230   287  2468 V AudioFlinger: processConfigEvents_l() DONE thread 0xb4393000
08-26 14:59:48.234   287  2468 D audio_hw_primary: in_standby: enter: stream (0xb40365c0) usecase(7: audio-record)
08-26 14:59:48.240   834  1033 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-26 14:59:48.240   834  1033 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
,08-26 14:59:48.242   834  1033 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-26 14:59:48.243   834  1033 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-26 14:59:48.243   834  1033 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 14:59:48.245  1371  1371 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-26 14:59:48.247   834  1033 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1de71418,  pkg=WindowManager.LayoutParams
08-26 14:59:48.247   834  1033 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-26 14:59:48.249  1371  1371 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-26 14:59:48.249  1371  1371 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-26 14:59:48.249  1371  1371 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-26 14:59:48.289   287  2468 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-26 14:59:48.289   287  2468 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-26 14:59:48.289   287  2468 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-26 14:59:48.290   287  2468 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 14:59:48.295   287  2468 V audio_hw_primary: disable_audio_route: exit
08-26 14:59:48.295   287  2468 E audio_hw_primary: disable_snd_device: enter 144
08-26 14:59:48.295   287  2468 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-26 14:59:48.295   287  2468 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-26 14:59:48.298   287  2468 V audio_hw_primary: stop_input_stream: exit: status(0)
08-26 14:59:48.298   287  2468 V audio_hw_primary: in_standby: exit:  status(0)
08-26 14:59:48.298   287  2468 V AudioFlinger: RecordThread: loop stopping
08-26 14:59:48.299   287   287 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-26 14:59:48.299   287  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 14:59:48.299   287   287 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
08-26 14:59:48.299   287   287 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-26 14:59:48.299   287   287 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-26 14:59:48.299   287  1062 V AudioPolicyService: AudioCommandThread() waking up
08-26 14:59:48.299   287  1062 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-26 14:59:48.300   287  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 14:59:48.302   287   287 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
08-26 14:59:48.302   287   287 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-26 14:59:48.302   287  1061 V AudioPolicyService: AudioCommandThread() waking up
08-26 14:59:48.302   287  1061 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
08-26 14:59:48.302   287  1061 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 287
08-26 14:59:48.302   287  1061 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-26 14:59:48.302   287  1061 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-26 14:59:48.302   287  2468 V AudioFlinger: RecordThread: loop starting
08-26 14:59:48.302   287  2468 V AudioFlinger: processConfigEvents_l() remaining events 1
08-26 14:59:48.302   287  2468 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-26 14:59:48.302   287  2468 V audio_hw_primary: in_set_parameters: exit: status(0)
08-26 14:59:48.302   287  2468 V AudioFlinger: processConfigEvents_l() DONE thread 0xb4393000
08-26 14:59:48.302   287  2468 V AudioFlinger: RecordThread: loop stopping
08-26 14:59:48.303   287  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 14:59:48.310  1948  2402 V AudioRecord: stop()
08-26 14:59:48.311  1948  2402 V AudioRecord: stop()
08-26 14:59:48.311  1948  2402 V AudioRecord: stop()
08-26 14:59:48.314   287   287 V AudioFlinger: releasing 16 from 1948 for -1
08-26 14:59:48.314   287   287 V AudioFlinger:  decremented refcount to 0
08-26 14:59:48.314   287   287 V AudioFlinger: purging stale effects
08-26 14:59:48.314   287   287 V AudioFlinger: RecordHandle::stop()
08-26 14:59:48.314   287   287 V AudioFlinger: RecordThread::stop
08-26 14:59:48.314   287   287 V AudioPolicyManager: releaseInput() 17
08-26 14:59:48.314   287   287 V AudioPolicyManager: closeInput(17)
08-26 14:59:48.314   287   287 V AudioFlinger: closeInput() 17
08-26 14:59:48.314   287   287 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-26 14:59:48.314   834  1788 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-26 14:59:48.314   287   287 V AudioFlinger: ThreadBase::exit
08-26 14:59:48.314  1371  2465 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-26 14:59:48.315   287  2468 V AudioFlinger: RecordThread: loop starting
08-26 14:59:48.315  1754  1769 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-26 14:59:48.315  2020  2073 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-26 14:59:48.315  1948  1977 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-26 14:59:48.315   287  2468 V AudioFlinger: RecordThread 0xb4393000 exiting
08-26 14:59:48.315  2831  2848 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-26 14:59:48.315  3178  3194 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-26 14:59:48.315   287   287 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb40365c0)
08-26 14:59:48.315   287   287 D audio_hw_primary: in_standby: enter: stream (0xb40365c0) usecase(7: audio-record)
08-26 14:59:48.315   287   287 V audio_hw_primary: in_standby: exit:  status(0)
08-26 14:59:48.315   287   287 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-26 14:59:48.315   287   287 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-26 14:59:48.316   287  1062 V AudioPolicyService: AudioCommandThread() waking up
08-26 14:59:48.316   287  1062 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-26 14:59:48.316   287  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 14:59:48.316   287   287 V AudioPolicyManager: releaseInput() exit
08-26 14:59:48.316   287   287 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-26 14:59:48.316   287   287 V AudioFlinger: removeClient_l() pid 1948, calling pid 287
08-26 14:59:48.318  1948  2408 I HotwordRecognitionRnr: Stopping hotword detection.
08-26 14:59:48.327  1948  2463 I HotwordRecognitionRnr: Hotword detection finished
08-26 14:59:48.386  6238  6238 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 14:59:48.496  6238  6238 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-26 14:59:48.548  6238  6238 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6147-6151)
08-26 14:59:48.548  6238  6238 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 14:59:48.596  6238  6238 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {39ca963a}
08-26 14:59:48.598  6238  6238 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 14:59:48.599  6238  6238 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 14:59:48.615  6238  6238 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 14:59:48.616  6238  6238 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 14:59:48.618  6238  6238 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 14:59:48.642  6238  6238 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-26 14:59:48.648  6238  6238 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 14:59:48.648  6238  6238 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 14:59:48.649  6238  6238 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 14:59:48.649  6238  6238 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 14:59:48.649  6238  6238 I Adreno-EGL: Build Date: 03/02/15 Mon
08-26 14:59:48.649  6238  6238 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-26 14:59:48.649  6238  6238 I Adreno-EGL: Remote Branch: 
08-26 14:59:48.649  6238  6238 I Adreno-EGL: Local Patches: 
08-26 14:59:48.649  6238  6238 I Adreno-EGL: Reconstruct Branch: 
08-26 14:59:48.732   287  1609 V AudioPolicyService: registerClient() client 0xb57e9760, uid 10030
08-26 14:59:48.747   834  1034 D BluetoothManagerService: Message: 20
08-26 14:59:48.747   834  1034 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2dbdb783:true
08-26 14:59:48.750  2020  2076 D BluetoothAdapterService(721852488): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@332c65de
08-26 14:59:48.958  6238  6238 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 14:59:48.976  6238  6238 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 14:59:48.986  6238  6238 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 14:59:48.994  6238  6238 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 14:59:48.994  6238  6238 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-26 14:59:49.012  6238  6238 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-26 14:59:49.023  6238  6238 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 14:59:49.023  6238  6238 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 14:59:49.089  6238  6238 I Activity: Activity.onPostResume() called 
08-26 14:59:49.099  6238  6296 D OpenGLRenderer: Render dirty regions requested: true
08-26 14:59:49.099  6238  6296 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 14:59:49.106  6238  6296 D OpenGLRenderer: Enabling debug mode 0
08-26 14:59:49.123  6238  6238 D Atlas   : Validating map...
08-26 14:59:49.128   834  1859 D SplitWindow: check instance of lgWin Window{1dcb8773 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 14:59:49.138  6238  6280 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 14:59:49.171   834  1788 D InputDispatcher: Focus entered window: Window{1dcb8773 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 14:59:49.233   834  1832 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-26 14:59:49.241   834  1035 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s139ms
08-26 14:59:49.241   834  1035 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{28e12b91 u0 com.test.thalitest/.MainActivity t259} time:116844
08-26 14:59:49.257  6238  6238 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@374c7f24 time:116859
,08-26 14:59:49.419  6238  6238 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6238
,08-26 14:59:49.506  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 14:59:49.506  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-26 14:59:49.506  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-26 14:59:49.584  6238  6238 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 14:59:50.093  6238  6299 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635611904
,08-26 14:59:50.115  6238  6299 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 14:59:50.115  6238  6299 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 14:59:50.115  6238  6299 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 14:59:50.115  6238  6299 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 14:59:50.115  6238  6299 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 14:59:50.115  6238  6299 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@254379c1 added. We now have 1 listener(s)
08-26 14:59:50.125   834  1788 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:59:50.131  6238  6299 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-26 14:59:50.134  6238  6299 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-26 14:59:50.135  6238  6299 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:59:50.135  6238  6299 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 14:59:50.151  6238  6299 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ff954 added. We now have 1 listener(s)
08-26 14:59:50.151  6238  6299 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:59:50.163  6238  6299 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 14:59:50.163  6238  6299 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 14:59:50.163  6238  6299 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 14:59:50.163  6238  6299 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 14:59:50.163  6238  6299 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 14:59:50.168  6238  6299 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:59:50.168   834   852 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 14:59:50.170  6238  6299 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-26 14:59:50.180  2020  2057 D BluetoothAdapterService(721852488): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@332c65de
,08-26 14:59:50.183  6238  6299 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 14:59:50.183  6238  6299 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:59:50.183  6238  6299 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:59:50.183  6238  6299 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 14:59:50.183  6238  6299 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:59:50.183  6238  6299 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:59:50.183  6238  6299 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:59:50.183  6238  6299 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:59:50.183  6238  6299 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:59:50.183  6238  6299 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 14:59:50.183  6238  6299 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:59:50.185  6238  6299 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 14:59:50.283  6238  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:59:50.288  6238  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:59:50.291  6238  6238 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-26 14:59:50.346  6238  6252 I art     : CheckpointMarkThreadRoots callback created = 0x99e56380
,08-26 14:59:50.385  6238  6252 I art     : CheckpointMarkThreadRoots callback created = 0x99e56340
,08-26 14:59:51.007   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-26 14:59:51.027  6238  6320 W jxcore-log: Initializing JXcore engine
,08-26 14:59:51.028  6238  6320 W jxcore-log: JXcore engine is ready
08-26 14:59:51.166  6320  6320 W Thread-755: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8743]" dev="sockfs" ino=8743 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-26 14:59:51.166  6320  6320 W Thread-755: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 14:59:51.166  6320  6320 W Thread-755: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7423]" dev="sockfs" ino=7423 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-26 14:59:51.166  6320  6320 W Thread-755: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-26 14:59:51.166  6320  6320 W Thread-755: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-26 14:59:51.166  6320  6320 W Thread-755: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[27647]" dev="sockfs" ino=27647 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-26 14:59:51.194  6238  6320 W jxcore-log: Starting JXcore engine
,08-26 14:59:51.345  6238  6320 W jxcore-log: Platform android
08-26 14:59:51.345  6238  6320 W jxcore-log: 
,08-26 14:59:51.345  6238  6320 W jxcore-log: Process ARCH arm
08-26 14:59:51.345  6238  6320 W jxcore-log: 
08-26 14:59:51.509  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 14:59:51.509  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 14:59:51.510  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-26 14:59:51.684  6238  6320 I jxcore-log: JXcore Cordova bridge is ready!
08-26 14:59:51.684  6238  6320 I jxcore-log: 
08-26 14:59:51.685  6238  6320 W jxcore-log: JXcore engine is started
,08-26 14:59:51.689  6238  6299 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 14:59:51.696  6238  6238 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 14:59:52.416   834  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{15bcd92 type 2 when 120000 com.google.android.gms} when 120000
,08-26 14:59:52.510  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 14:59:52.510  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 14:59:52.511  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-26 14:59:53.307   834  1288 V AlarmManager: RTC_WAKEUP set : Alarm{16913b60 type 0 when 1472216393298 com.google.android.googlequicksearchbox} when 1472216393298
,08-26 14:59:53.511  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 14:59:53.511  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 14:59:53.511  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-26 14:59:53.875  2831  2831 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19944
,08-26 14:59:54.514  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 14:59:54.514  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 14:59:54.514  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-26 14:59:56.012   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-26 14:59:57.519  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 14:59:57.519  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 14:59:57.519  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-26 14:59:58.552  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 14:59:58.552  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-26 14:59:58.552  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-26 14:59:59.494  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 14:59:59.494  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 14:59:59.495  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 14:59:59.495  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-26 14:59:59.497  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 14:59:59.498   491   491 D charger_monitor: init target 500000
08-26 14:59:59.530  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 313
08-26 14:59:59.530  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 14:59:59.530  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 313
08-26 14:59:59.532   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:59:59.532   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:59:59.533   834  1315 D WifiController: battery changed pluggedType: 2
08-26 14:59:59.535  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 14:59:59.535  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 14:59:59.536  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 14:59:59.536  1806  1973 D LEDHandler: Battery Temp: 313, mChargingStatus=5, mChargingStop=false
08-26 14:59:59.537  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 14:59:59.541  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 14:59:59.543  6056  6056 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-26 14:59:59.550   491   491 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 14:59:59.581  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 14:59:59.584  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 14:59:59.585  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 14:59:59.585  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-26 15:00:00.000   834  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=113159564, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
,08-26 15:00:00.013  2810  2810 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:0:0
08-26 15:00:00.014  2810  2810 D WeatherService: 2 : TimeTick Intent And Screen On
08-26 15:00:00.014  2810  2810 D WeatherService: 2 : SDK version : 21
08-26 15:00:00.015   834  1903 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
08-26 15:00:00.015  2810  2810 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
08-26 15:00:00.016  2810  2810 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
08-26 15:00:00.016  2810  2810 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
08-26 15:00:00.016  2810  2810 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
08-26 15:00:00.018  2810  2810 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 15:00:00.018  2810  2810 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
08-26 15:00:00.018  2810  2810 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
08-26 15:00:00.019  2810  2810 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
08-26 15:00:00.019  2810  2810 D WeatherTheme: 2 : Fixed theme : optimus
08-26 15:00:00.026  2810  2810 D WeatherReflect: 2 : Map key string is -2
,08-26 15:00:00.034  2810  2810 D lim     : 2 : time = 15:00
08-26 15:00:00.036  2810  2810 I WeatherReflect: Model Name : LG-D722
08-26 15:00:00.036  2810  2810 D WeatherTheme: 2 : Different view - status_hour_formatted : 14 != 15
08-26 15:00:00.036  2810  2810 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
08-26 15:00:00.037  2810  2810 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
08-26 15:00:00.038  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:00:00.038  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:00:00.039  2810  2810 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-26 15:00:00.039  2810  2810 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-26 15:00:00.039  2810  2810 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-26 15:00:00.039  2810  2810 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
08-26 15:00:00.042  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
08-26 15:00:00.044  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:00:00.046  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
,08-26 15:00:00.051  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:00:00.052  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:00:00.093  2810  2810 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
08-26 15:00:00.093  2810  2810 D Weather4x2_optimus: widgetType = 1, orientation = 1
08-26 15:00:00.093  2810  2810 D Weather4x2_optimus: forecast size is 0
08-26 15:00:00.093  2810  2810 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-26 15:00:00.093  2810  2810 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-26 15:00:00.093  2810  2810 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-26 15:00:00.094  2810  2810 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-26 15:00:00.094  2810  2810 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-26 15:00:00.094  2810  2810 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-26 15:00:00.094  2810  2810 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-26 15:00:00.094  2810  2810 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-26 15:00:00.094  2810  2810 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-26 15:00:00.094  2810  2810 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
08-26 15:00:00.094  2810  2810 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
08-26 15:00:00.094  2810  2810 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-26 15:00:00.094  2810  2810 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-26 15:00:00.094  2810  2810 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-26 15:00:00.094  2810  2810 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
,08-26 15:00:00.098  2810  2810 D Theme_WeatherAncestor_optimus: url is : null
08-26 15:00:00.100  2810  2810 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-26 15:00:00.100  2810  2810 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-26 15:00:00.100  2810  2810 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-26 15:00:00.101  2810  2810 D WeatherAncestor: 2 : update view, appWidgetId: 2
08-26 15:00:00.106  2810  2810 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:0:0
08-26 15:00:00.118   834   834 D PowerManagerServiceEx: releaseWakeLockInternal: lock=113159564 [*alarm*], flags=0x0
,08-26 15:00:00.252  1880  1880 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,08-26 15:00:00.334  1880  1880 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-26 15:00:00.554  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:00.554  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-26 15:00:00.554  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-26 15:00:01.017   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-26 15:00:01.555  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-26 15:00:01.556  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:01.556  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-26 15:00:01.687   834   969 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6390 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-26 15:00:01.935  6390  6390 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
08-26 15:00:01.944  6390  6390 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@96a552e
08-26 15:00:01.945   834  1832 I ActivityManager: Killing 6056:com.lge.bnr/1000 (adj 15): empty #11
,08-26 15:00:02.028   834  1812 W libprocessgroup: failed to open /acct/uid_1000/pid_6056/cgroup.procs: No such file or directory
,08-26 15:00:02.559  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:02.559  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:02.559  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-26 15:00:03.560  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:03.560  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:03.560  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-26 15:00:04.563  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:04.563  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:04.563  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-26 15:00:06.021   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-26 15:00:06.566  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:06.566  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:06.566  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-26 15:00:06.839   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:00:06.839   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:00:06.840   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 134442115890; DSPS: 4497301; Offset : -2814283727
,08-26 15:00:07.568  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:07.568  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:07.568  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-26 15:00:08.563   834  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3e58bcd5 type 2 when 136154 com.google.android.gms} when 136154
,08-26 15:00:08.570  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:08.571  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:08.571  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-26 15:00:08.588  1735  1735 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-26 15:00:08.811  1735  1735 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:00:08.819  3366  6410 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-26 15:00:08.819  3366  6410 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-26 15:00:09.054   834   852 I art     : Explicit concurrent mark sweep GC freed 49392(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.469ms total 170.470ms
,08-26 15:00:09.407   834  1788 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6432 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,08-26 15:00:09.510  6432  6432 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 15:00:09.510  6432  6432 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 15:00:09.566  6432  6432 I MultiDex: VM with version 2.1.0 has multidex support
08-26 15:00:09.567  6432  6432 I MultiDex: install
08-26 15:00:09.567  6432  6432 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 15:00:09.627  6432  6432 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 15:00:09.702  6432  6432 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-26 15:00:09.703  6432  6432 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d642b3e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-26 15:00:09.704  6432  6432 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 15:00:09.717  6432  6432 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
,08-26 15:00:09.720  6432  6432 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
08-26 15:00:09.732  6432  6432 D ChimeraCfgMgr: Reading stored module config
,08-26 15:00:09.866  6432  6446 W art     : Suspending all threads took: 9.929ms
,08-26 15:00:09.875  6432  6432 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-26 15:00:09.875  6432  6432 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-26 15:00:09.888  6432  6446 I art     : Background sticky concurrent mark sweep GC freed 20346(1026KB) AllocSpace objects, 3(133KB) LOS objects, 5% free, 10MB/11MB, paused 16.349ms total 113.250ms
,08-26 15:00:09.911  1735  2634 I art     : Explicit concurrent mark sweep GC freed 59003(3MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 14MB/24MB, paused 3.123ms total 165.199ms
,08-26 15:00:09.992  6432  6456 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-26 15:00:09.997  1735  1735 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=7d1fe571-ae8f-466e-b7dd-faecbebebd62
08-26 15:00:10.015  1735  1735 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:00:10.018  1735  1735 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-26 15:00:10.046  6432  6446 I art     : CheckpointMarkThreadRoots callback created = 0xaaf43760
,08-26 15:00:10.081  6432  6446 I art     : CheckpointMarkThreadRoots callback created = 0xaaf43750
,08-26 15:00:10.092   287  1353 D WVCdm   : Instantiating CDM.
,08-26 15:00:10.094   287   287 I WVCdm   : CdmEngine::OpenSession
08-26 15:00:10.095   287   287 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
08-26 15:00:10.160   287   287 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
08-26 15:00:10.160   287   287 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
08-26 15:00:10.160   287   287 W WVCdm   : L1 library not specified. Falling Back to L3
,08-26 15:00:10.203  6432  6447 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:10.203  6432  6447 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-26 15:00:10.204  6432  6447 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,08-26 15:00:10.204  6432  6447 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-26 15:00:10.204   281  1053 E BandwidthController: [LG DATA] No such appUid: 10006
08-26 15:00:10.205   281  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-26 15:00:10.207   281  6467 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-26 15:00:10.207   281  6467 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-26 15:00:10.208   281  6467 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-26 15:00:10.208   281  6467 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-26 15:00:10.222  1735  2414 W GCoreFlp: No location to return for getLastLocation()
,08-26 15:00:10.251   281  6467 D libc-netbsd: res_queryN name = xxxxx succeed
08-26 15:00:10.253  6432  6447 I System.out: propertyValue:false
,08-26 15:00:10.263   287   287 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-26 15:00:10.264   287  1609 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-26 15:00:10.264   287  1609 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-26 15:00:10.264   287  1609 I WVCdm   : CdmEngine::GenerateKeyRequest
08-26 15:00:10.272   287  1609 D WVCdm   : PrepareKeyRequest: nonce=3875134386
,08-26 15:00:10.286  3366  6423 D UdcContextInitService: registered all accounts: true
08-26 15:00:10.294  1735  2401 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 15:00:10.312  1735  2374 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-26 15:00:10.336  6432  6447 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:10.336  6432  6447 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-26 15:00:10.575  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:10.575  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-26 15:00:10.575  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,08-26 15:00:10.733   834  1859 I ActivityManager: Process com.google.android.talk (pid 6113) has died
,08-26 15:00:11.026   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-26 15:00:11.419  6477  6477 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 15:00:11.521  6477  6477 I dex2oat : dex2oat took 101.944ms (threads: 4)
,08-26 15:00:11.538  6432  6447 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 15:00:11.538  6432  6447 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 15:00:11.538  6432  6447 I Adreno-EGL: Build Date: 03/02/15 Mon
08-26 15:00:11.538  6432  6447 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-26 15:00:11.538  6432  6447 I Adreno-EGL: Remote Branch: 
08-26 15:00:11.538  6432  6447 I Adreno-EGL: Local Patches: 
08-26 15:00:11.538  6432  6447 I Adreno-EGL: Reconstruct Branch: 
,08-26 15:00:11.650  6432  6447 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 15:00:11.650  6432  6447 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 15:00:11.650  6432  6447 I Adreno-EGL: Build Date: 03/02/15 Mon
08-26 15:00:11.650  6432  6447 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-26 15:00:11.650  6432  6447 I Adreno-EGL: Remote Branch: 
08-26 15:00:11.650  6432  6447 I Adreno-EGL: Local Patches: 
08-26 15:00:11.650  6432  6447 I Adreno-EGL: Reconstruct Branch: 
,08-26 15:00:11.706  6432  6447 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 15:00:11.706  6432  6447 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 15:00:11.706  6432  6447 I Adreno-EGL: Build Date: 03/02/15 Mon
08-26 15:00:11.706  6432  6447 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-26 15:00:11.706  6432  6447 I Adreno-EGL: Remote Branch: 
08-26 15:00:11.706  6432  6447 I Adreno-EGL: Local Patches: 
08-26 15:00:11.706  6432  6447 I Adreno-EGL: Reconstruct Branch: 
,08-26 15:00:11.863  1735  6425 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:11.863  1735  6425 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-26 15:00:11.863  1735  6425 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:11.863  1735  6425 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-26 15:00:11.864   281  1053 E BandwidthController: [LG DATA] No such appUid: 10006
08-26 15:00:11.864   281  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,08-26 15:00:11.865   281  6485 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-26 15:00:11.865   281  6485 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-26 15:00:11.866   281  6485 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-26 15:00:11.866   281  6485 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-26 15:00:11.866   281  6485 D libc-netbsd: res_queryN name = xxxxx succeed
08-26 15:00:11.866  1735  6425 I System.out: propertyValue:false
08-26 15:00:11.932  1735  6425 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:11.932  1735  6425 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-26 15:00:12.137  1735  2374 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 15:00:12.146  1735  2374 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-26 15:00:12.153  1735  2374 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-26 15:00:10.434+0200, stopTime=2016-08-26 15:00:12.148+0200, duration=1714ms
08-26 15:00:12.197  1735  6493 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:12.197  1735  6493 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-26 15:00:12.198  1735  6493 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:12.198  1735  6493 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-26 15:00:12.198   281  1053 E BandwidthController: [LG DATA] No such appUid: 10006
08-26 15:00:12.198   281  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-26 15:00:12.198   281  6500 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-26 15:00:12.198   281  6500 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-26 15:00:12.199   281  6500 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-26 15:00:12.199   281  6500 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-26 15:00:12.199   281  6500 D libc-netbsd: res_queryN name = xxxxx succeed
,08-26 15:00:12.201  1735  6493 I System.out: propertyValue:false
,08-26 15:00:12.286  4098  5070 I art     : Explicit concurrent mark sweep GC freed 1349(45KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.247ms total 32.689ms
,08-26 15:00:12.451   287  1353 I WVCdm   : CdmEngine::CloseSession
08-26 15:00:12.455   287  1353 I WVCdm   : L3 Terminate.
,08-26 15:00:12.623  1735  2374 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-26 15:00:12.774  1735  6508 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 15:00:12.775  1735  6506 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-26 15:00:12.805  1735  6508 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-26 15:00:12.807  1735  6506 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 15:00:12.846  1735  6508 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 15:00:12.848  1735  6506 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-26 15:00:12.848  1735  6506 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
08-26 15:00:12.865  1735  6506 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 15:00:12.909   834  1812 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:12.995  1735  6506 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:12.995  1735  6506 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-26 15:00:12.995  1735  6506 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:12.995  1735  6506 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-26 15:00:12.996   281  1053 E BandwidthController: [LG DATA] No such appUid: 10006
08-26 15:00:12.996   281  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-26 15:00:12.996   281  6509 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-26 15:00:12.996   281  6509 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-26 15:00:12.996   281  6509 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,08-26 15:00:12.997   281  6509 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-26 15:00:12.997   281  6509 D libc-netbsd: res_queryN name = xxxxx succeed
08-26 15:00:12.998  1735  6506 I System.out: propertyValue:false
08-26 15:00:13.336   834  1859 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:13.629   834  1874 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:13.872  2831  2831 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-26 15:00:13.889  2831  2831 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-26 15:00:13.931   834  1635 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:14.181   834  1286 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:14.267  1735  6506 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:14.267  1735  6506 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-26 15:00:14.268  1735  6506 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:14.268  1735  6506 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-26 15:00:14.269   281  1053 E BandwidthController: [LG DATA] No such appUid: 10006
08-26 15:00:14.269   281  1053 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-26 15:00:14.272   281  6515 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-26 15:00:14.272   281  6515 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-26 15:00:14.272   281  6515 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-26 15:00:14.272   281  6515 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-26 15:00:14.273   281  6515 D libc-netbsd: res_queryN name = xxxxx succeed
,08-26 15:00:14.273  1735  6506 I System.out: propertyValue:false
08-26 15:00:14.323  1735  6506 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-26 15:00:14.323  1735  6506 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-26 15:00:14.538   834  1874 I NotificationManager: android: cancelAsUser(2) by android
,08-26 15:00:14.561  1735  6506 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,08-26 15:00:14.583  1735  2374 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-26 15:00:14.778   834   852 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:14.987   834  1788 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:15.599  6238  6320 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 15:00:15.599  6238  6320 I jxcore-log: 
,08-26 15:00:15.603  6238  6320 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 15:00:15.603  6238  6320 I jxcore-log: 
08-26 15:00:15.608  2020  2076 D BluetoothAdapterService(721852488): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@332c65de
08-26 15:00:15.609  6238  6320 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:00:15.609  6238  6320 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:00:15.609  6238  6320 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 15:00:15.609  6238  6320 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:00:15.609  6238  6320 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:00:15.609  6238  6320 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:00:15.609  6238  6320 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:00:15.609  6238  6320 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:00:15.635  2020  2076 D BluetoothAdapterService(721852488): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@332c65de
,08-26 15:00:15.639  6238  6320 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:00:15.643  6238  6320 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 15:00:15.643  6238  6320 I jxcore-log: 
08-26 15:00:15.646  6238  6320 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 15:00:15.646  6238  6320 I jxcore-log: 
08-26 15:00:16.030   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-26 15:00:16.225  6238  6320 I jxcore-log: Running unit tests
08-26 15:00:16.225  6238  6320 I jxcore-log: 
,08-26 15:00:16.226  6238  6320 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-26 15:00:16.226  6238  6320 I jxcore-log: Failed to execute UT.
08-26 15:00:16.226  6238  6320 I jxcore-log: 
08-26 15:00:16.228  6238  6320 I jxcore-log: Unit Test app is loaded
08-26 15:00:16.228  6238  6320 I jxcore-log: 
08-26 15:00:16.242  6238  6320 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:00:16.242  6238  6320 I jxcore-log: 
,08-26 15:00:16.249  6238  6320 I jxcore-log: My device name is: LGE-LG-D722
08-26 15:00:16.249  6238  6320 I jxcore-log: 
08-26 15:00:16.252  6238  6320 I jxcore-log: WARN testUtils: myNameCallback not set!
08-26 15:00:16.252  6238  6320 I jxcore-log: 
08-26 15:00:16.260  6238  6238 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-26 15:00:16.584  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:16.585  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:16.585  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-26 15:00:17.037  6238  6320 W jxcore-log: !!! js_ReportOverRecursed called !!!
,08-26 15:00:17.092  6517  6320 W google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----
,08-26 15:00:17.094  6517  6320 W google-breakpad: O A arm 04 armv7l 3.4.0+ #1 SMP PREEMPT Thu Aug 20 12:20:45 KST 2015
08-26 15:00:17.094  6517  6320 W google-breakpad: S 0 9A368028 9A368000 00008000
08-26 15:00:17.133  6517  6320 W google-breakpad: S 9A368000 5C80369A20490698000000002080369AE0ED46B0000000006C1760987080369A741760985C80369A07000000000000000000000090B8E0E66042D69585FFFFFFE01D1197E0ED46B0E080369A8C80369A6480369A85FFFFFF8480369A202E25985C86AA95E01D1197E0ED46B05081369A8C80369AE080369A741760986042D695AC80369A58D746985C86AA95000000000000000082FFFFFFE080369A5081369AD080369AE0ED46B01481369A1C6B3F98E4D85F9850DC5F9858DB7598220000005C86AA9554DA3B9500000000E480369A6042D69585FFFFFFE0ED46B0000000006042D69585FFFFFF9881369A6882369A18C176986081369A00000000010000005081369A4081369A22000000E0ED46B0A482369A2894429878CB389500000000E0ED46B03081369A020000007881369A30BD61969881369A30D1DB9588FFFFFF0000000082FFFFFF00000000000100000000000082FFFFFFE0ED46B00000000000000000E0ED46B001000000C882369AD882369A0100000078CB389507000000
08-26 15:00:17.134  6517  6320 W google-breakpad: S 9A368180 0700000001000000D040D69500000000E0ED46B00000000000000000060000003CC176983CC176980600000018C1769800000000FFFFFFFF0000000088CB389522000000D840D6950700000000000000010000001800109750526A9481FFFFFF0482369AE0AA2F9807000000D040D695E0ED46B000000000100010971082369A4482369AE8EC2F980000000000000000000000000CD4BA9C7882369A0100000000000000B0D5DB95E01B1197D040D69500000000FFFFFFFF50526A9481FFFFFFE082369AB0D4BA9C3883369A5482369AA082369A000000000000000078D4BA9C4003000001000000FFFFFFFF81FFFFFFD040D69585FFFFFF1000109785FFFFFFB082369A6049069788FFFFFF881CBD9C00000000FFFFFFFFC0526A9481FFFFFFE082369A387F3D9B00000000B482369A8C893D9B0000000000000000881CBD9C42020000010000006049069788FFFFFF00EA029788FFFFFFD040D69585FFFFFF3C83369AC0526A94881CBD9C01050000D040D69585FFFFFF00EA029788FFFFFF
08-26 15:00:17.135  6517  6320 W google-breakpad: S 9A368300 6049069788FFFFFF0000000082FFFFFF000000002831269A40020000000000005000000030BD0297F0D9119785FFFFFF6C83369A8483369A000000006083369A8C893D9B8201000080860697010000000000000082FFFFFFD040D69585FFFFFF0C84369AC08D0A952CCCBB9C010A0000D040D69585FFFFFF0000000082FFFFFF8086069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007109785FFFFFFF0D9119785FFFFFF82FFFFFF58187F98F0FB1197EC7A249AA000000030BD02970000000083FFFFFFE87B249A02000000000000003884369A8C893D9B02020000C04C069702000000A0C6059788FFFFFFD040D69585FFFFFFE0A85B9688FFFFFFAC84369A80390296BCBC249A81060000F0D9119785FFFFFFD040D69585FFFFFFA0C6059788FFFFFFC04C069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:17.136  6517  6320 W google-breakpad: S 9A368480 C10300009084369A0000000083FFFFFF68000000107C7F95D840D6950100000030000000107C7F9500000000D084369A8C893D9B8201000020A66196010000000000000082FFFFFFD040D69585FFFFFF5485369A70320296FCB4249A81070000D040D69585FFFFFF0000000082FFFFFF20A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF7085369A6885369A6085369AD485369A78000000107C7F95000000001686B39358DB7598E0ED46B0000000007885369A8C893D9B8201000060A66196010000000000000082FFFFFFD040D69585FFFFFFE485369A98280296DCAA249A01060000D040D69585FFFFFF0000000082FFFFFF60A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000F085369A0886369A0400000060000000107C7F95E018029681FFFFFF7486369AF83F3D9B000000000886369A8C893D9B8201000080A66196010000000000000082FFFFFF
08-26 15:00:17.137  6517  6320 W google-breakpad: S 9A368600 D040D69585FFFFFF7486369A98220296E0A1249A01060000D040D69585FFFFFF0000000082FFFFFF80A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000050D5DB9500000000201EAF946000000080D5DB9504000000E87B249A8486369A78041298040000009886369A8C893D9B82010000A0A66196010000000000000082FFFFFF50D5DB9588FFFFFF1487369A90170296F498249A0107000050D5DB9588FFFFFF0000000082FFFFFFA0A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013119785FFFFFFD040D69585FFFFFF000000000887369A0487369A88FFFFFF7000000020D5D,B959032D19584E124980000000000000000040000003887369A8C893D9B8201000020A761960100000070B3D09688FFFFFF90D1DB9588FFFFFF9487369A602CF8936092249A0105000090D1DB9588FFFFFF70B3D09688FFFFFF20A7619688FFFFFFC0D3119785FFFFFF9032D19501000000C487369ADC87369A5000000040707F95
,08-26 15:00:17.137  6517  6320 W google-breakpad: S 9A368780 02000000706F8096B487369AC803129800000000C887369ADC8DBE9C8202000080776F96030000000000000082FFFFFF90D1DB9588FFFFFF0000000081FFFFFF9032D19588FFFFFF6488369AD0169695E852B89C010900009032D19588FFFFFF0000000081FFFFFF90D1DB9588FFFFFF0000000082FFFFFF80776F9688FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF7092C19488FFFFFF0000000082FFFFFF0900000081FFFFFF9032D19588FFFFFFE032D195000000009488369AC0D602979000000020C00297E87B249A020000007023F89381FFFFFF000000008888369A8C893D9B82010000B0020397010000009032D19588FFFFFF80776F9688FFFFFF0C89369A2828F893D08B249A8107000080776F9688FFFFFF9032D19588FFFFFFB002039788FFFFFFE032D19588FFFFFFC0D6029788FFFFFFC0D0029788FFFFFF0000000082FFFFFFE032D19588FFFFFF0000000082FFFFFF3089369A387F3D9B00000000F488369A7800000040707F95000000002482249A
08-26 15:00:17.138  6517  6320 W google-breakpad: S 9A368900 4203000003000000000000003889369A8C893D9B02020000A0776F96020000007069779388FFFFFF30BD619688FFFFFF9032D19588FFFFFFA489369A781DF893F086249A010600009032D19588FFFFFF30BD619688FFFFFF7069779388FFFFFFA0776F9688FFFFFF0000000082FFFFFF0000000082FFFFFF6889369AA03504970042D695401111976000000040707F9585FFFFFFDC76269A85FFFFFFA489369A0000000000370497E881269A800B0000E0776F96020000000037049788FFFFFF30BD619688FFFFFF908CD19588FFFFFF1042D69585FFFFFF4032D19588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFB0D2DB95908CD195A0350497207DD1958A00000060D4DB951042D6954032D195908CD195A03504970042D69580181097807DD1950900000080A85B96D0B00297D0B00297908CD19588FFFFFF0900000040111197090000000037049730BD619660D1DB9580A85B9688FFFFFF0000000064FDB59C08FFB59C000400008036049701000000
08-26 15:00:17.140  6517  6320 W google-breakpad: S 9A368A80 0037049788FFFFFF30BD619688FFFFFF0000000082FFFFFFF02A7F9830BD619630D1DB9500D1DB950000000087FFFFFFA00F0397D0D0DB9500D1DB9560A85B96E0DDBA9C80020000C0360497020000000000000082FFFFFFA00F039788FFFFFFD0D0DB9588FFFFFF208B369AD0D0DB9570D0DB95A0D0DB95FC00BB9C80020000003704970000000070D0DB9588FFFFFFC028D7958A00000007000000D028D795E0ED46B040B00297107DD1950037049720B83C9B03020000603F07970100000040B0029788FFFFFF107DD19585FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0ED46B0080EF3B6F88C369A0100000081FFFFFF508C369ABC8C369A14C41798603F07970000000000000000208C369AD48B369A38B73C9B58DB7598E0ED46B000B446B03C9D369A000000000000000000000000010000002494369AE0ED46B00001000000000000
08-26 15:00:17.141  6517  6320 W google-breakpad: S 9A368C00 B0FFBA9C00000000603F0797B090369A020000000100000000000000000000000100000081FFFFFF00000000000000008890369AF6FFFFFFECED46B001000000E0ED46B0508C369A000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000F88C369AE0ED46B0783B7F9800820A970000000070CB3895BC8C369A46804C6100000000E0ED46B0F88C369AC08C369A603F079700820A970000000070CB3895E48C369A2C653598000000000000000000000000080EF3B601000000E0ED46B0B890369AF08C369A6C90369A2466359852CC2795FBCD2795B890369A01000000E80C75980100000000820A97F08C369A0000000000CE27950200000002000000010000000000000080BA74985C0000000600000000000000289C369A00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:17.141  6517  6320 W google-breakpad: S 9A368D80 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C4279500000000000000000100000002000000C0A75B9600830A97E52847B0000000000000000046804C6100000000080EF3B600000000E0ED46B0C8BA2798888E369A0492369AA86635980000000000000000A892369A0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000,000000000000000000000000000000000000000000000000000000000
08-26 15:00:17.142  6517  6320 W google-breakpad: S 9A368F00 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000046804C61080EF3B6A890369AE0ED46B05891369AB890369A70CB38951491369AE46A359800000000000000000000000040B00297
08-26 15:00:17.143  6517  6320 W google-breakpad: S 9A369080 B890369A01000000989D369AF6FFFFFFECED46B008E70000E0ED46B0A890369A0300000008000000603F079788FFFFFF40B0029788FFFFFF107DD19585FFFFFFFFFFFFFF008041B00000000008000000000000006B27F1B600000000000000000800000067E3F0B60000000046804C6100000000E0ED46B06891369A5891369A6091369A5491369A82FFFFFF68CB38954491369A3855259868CB38956091369A40B0029788FFFFFFA491369AD891369AB892369A010000007091369A00000000A491369A20EB46986091369A00000000408DC0B440B00297603F079788FFFFFF0000000082FFFFFF0100000068CB38950000000082FFFFFFE0ED46B0000000006C176098D891369AC891369A806C4CB0186F4CB0E0ED46B0B892369A6C1760981492369AB8FA3D98D891369A4F000000DC2F34950C86AA95000000000086AA952892369A2C92369A40B0029788FFFFFFE0ED46B000000000107DD19585FFFFFFE0ED46B0000000002892369A187061982D86AA954892369AB892369A3892369A
08-26 15:00:17.144  6517  6320 W google-breakpad: S 9A369200 E0ED46B02C92369A22000000806C4CB07C92369AEC6A3F98E4D85F9850DC5F9858DB7598220000000C86AA9524DA3B95000000004C92369A2200000000000000D093369A000000006492369A1435FD970093369AD093369A18C17698C892369A0000000001000000B892369AA892369A22000000E0ED46B00C94369A2894429858CB389500000000E0ED46B09892369A02000000E092369AE0BC61960093369AB04BD19588FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0ED46B0010000003094369A4094369A0100000058CB3895070000000700000001000000B07BD19500000000E0ED46B00000000000000000060000003CC176983CC176980600000018C1769800000000FFFFFFFF0000000060CB389522000000B87BD1950700000000000000010000001800109750526A9481FFFFFF6C93369AE0AA2F9807000000B07BD195E0ED46B000000000100010977893369AAC93369AE8EC2F980000000000000000000000000CD4BA9C
08-26 15:00:17.145  6517  6320 W google-breakpad: S 9A369380 E093369A010000000000000040D0DB95E01B1197B07BD19500000000FFFFFFFF50526A9481FFFFFF4894369AB0D4BA9CA094369ABC93369A0894369A000000000000000078D4BA9C4003000001000000FFFFFFFF81FFFFFFB07BD19585FFFFFF1000109785FFFFFF1894369A6049069788FFFFFF881CBD9C00000000FFFFFFFFC0526A9481FFFFFF4894369A387F3D9B000000001C94369A8C893D9B0000000000000000881CBD9C42020000010000006049069788FFFFFF00EA029788FFFFFFB07BD19585FFFFFFA494369AC0526A94881CBD9C01050000B07BD19585FFFFFF00EA029788FFFFFF6049069788FFFFFF0000000082FFFFFF000000002831269A40020000000000005000000030BD0297F0D9119785FFFFFFD494369AEC94369A00000000C894369A8C893D9B8201000080860697010000000000000082FFFFFFB07BD19585FFFFFF7495369AC08D0A952CCCBB9C010A0000B07BD19585FFFFFF0000000082FFFFFF8086069788FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:17.145  6517  6320 W google-breakpad: S 9A369500 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007109785FFFFFFF0D9119785FFFFFF82FFFFFF58187F98F0FB1197EC7A249AA000000030BD02970000000083FFFFFFE87B249A0200000000000000A095369A8C893D9B02020000C04C069702000000A0C6059788FFFFFFB07BD19585FFFFFF40A85B9688FFFFFF1496369A80390296BCBC249A81060000F0D9119785FFFFFFB07BD19585FFFFFFA0C6059788FFFFFFC04C069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000F895369A0000000083FFFFFF68000000107C7F95B87BD1950100000030000000107C7F95000000003896369A8C893D9B8201000020A66196010000000000000082FFFFFFB07BD19585FFFFFFBC96369A70320296FCB4249A8107,0000B07BD19585FFFFFF0000000082FFFFFF20A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:17.146  6517  6320 W google-breakpad: S 9A369680 0000000082FFFFFF0000000082FFFFFFD896369AD096369AC896369A3C97369A78000000107C7F95000000001686B39358DB7598E0ED46B000000000E096369A8C893D9B8201000060A66196010000000000000082FFFFFFB07BD19585FFFFFF4C97369A98280296DCAA249A01060000B07BD19585FFFFFF0000000082FFFFFF60A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000005897369A7097369A0400000060000000107C7F95E018029681FFFFFFDC97369AF83F3D9B000000007097369A8C893D9B8201000080A66196010000000000000082FFFFFFB07BD19585FFFFFFDC97369A98220296E0A1249A01060000B07BD19585FFFFFF0000000082FFFFFF80A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000D04FD19500000000201EAF946000000010D0DB9504000000E87B249AEC97369A78041298040000000098369A8C893D9B82010000A0A66196010000000000000082FFFFFFD04FD19588FFFFFF
08-26 15:00:17.147  6517  6320 W google-breakpad: S 9A369800 7C98369A90170296F498249A01070000D04FD19588FFFFFF0000000082FFFFFFA0A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013119785FFFFFFB07BD19585FFFFFF000000007098369A6C98369A88FFFFFF70000000A04FD195F08BD19584E12498000000000000000004000000A098369A8C893D9B8201000020A761960100000070B3D09688FFFFFF104CD19588FFFFFFFC98369A602CF8936092249A01050000104CD19588FFFFFF70B3D09688FFFFFF20A7619688FFFFFFC0D3119785FFFFFFF08BD195010000002C99369A4499369A5000000040707F9502000000706F80961C99369AC8031298000000003099369ADC8DBE9C8202000080776F96030000000000000082FFFFFF104CD19588FFFFFF0000000081FFFFFFF08BD19588FFFFFFCC99369AD0169695E852B89C01090000F08BD19588FFFFFF0000000081FFFFFF104CD19588FFFFFF0000000082FFFFFF80776F9688FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF
08-26 15:00:17.148  6517  6320 W google-breakpad: S 9A369980 0092C19488FFFFFF0000000082FFFFFF0900000081FFFFFFF08BD19588FFFFFF408CD19500000000FC99369AC0D602979000000020C00297E87B249A020000007023F89381FFFFFF00000000F099369A8C893D9B82010000B002039701000000F08BD19588FFFFFF80776F9688FFFFFF749A369A2828F893D08B249A8107000080776F9688FFFFFFF08BD19588FFFFFFB002039788FFFFFF408CD19588FFFFFFC0D6029788FFFFFFC0D0029788FFFFFF0000000082FFFFFF408CD19588FFFFFF0000000082FFFFFF989A369A387F3D9B000000005C9A369A7800000040707F95000000002482249A420300000300000000000000A09A369A8C893D9B02020000A0776F96020000007069779388FFFFFFE0BC619688FFFFFFF08BD19588FFFFFF0C9B369A781DF893F086249A01060000F08BD19588FFFFFFE0BC619688FFFFFF7069779388FFFFFFA0776F9688FFFFFF0000000082FFFFFF0000000082FFFFFFD09A369AA0350497E07CD195401111976000000040707F9585FFFFFFDC76269A
,08-26 15:00:17.149  6517  6320 W google-breakpad: S 9A369B00 85FFFFFF0C9B369A0000000000370497E881269A800B0000E0776F96020000000037049788FFFFFFE0BC619688FFFFFF0086D19588FFFFFFF07CD19585FFFFFFA08BD19588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF304DD1950086D195A0350497C028D7958A000000E04ED195F07CD195A08BD1950086D195A0350497E07CD195801810972029D79509000000E0A75B96D0B00297D0B002970086D19588FFFFFF09000000401111970900000000370497E0BC6196E04BD195E0A75B9688FFFFFF0000000064FDB59C08FFB59C0004000080360497010000000037049788FFFFFFE0BC619688FFFFFF0000000082FFFFFFF02A7F98E0BC6196B04BD195804BD1950000000087FFFFFFA00F0397504BD195804BD195C0A75B96E0DDBA9C80020000C0360497020000000000000082FFFFFFA00F039788FFFFFF504BD19588FFFFFF889C369A504BD195F04AD195204BD195FC00BB9C800200000037049700000000F04AD19588FFFFFF1085DD958A000000,
08-26 15:00:17.149  6517  6320 W google-breakpad: S 9A369C80 070000002085DD95E0ED46B040B00297B028D7950037049720B83C9B03020000603F07970100000040B0029788FFFFFFB028D79585FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0ED46B0080EF3B6609E369A0100000081FFFFFFB89D369A249E369A14C41798603F07970000000000000000889D369A3C9D369A38B73C9B58DB7598E0ED46B000B446B0A4AE369A000000000000000000000000010000008CA5369AE0ED46B00001000000000000B0FFBA9C00000000603F079718A2369A020000000100000000000000000000000100000081FFFFFF0000000000000000F0A1369AF6FFFFFFECED46B001000000E0ED46B0B89D369A000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000609E369AE0ED46B0783B7F9800820A970000000050CB3895249E369A46804C61
08-26 15:00:17.150  6517  6320 W google-breakpad: S 9A369E00 00000000E0ED46B0609E369A289E369A603F079700820A970000000050CB38954C9E369A2C653598000000000000000000000000080EF3B601000000E0ED46B020A2369A589E369AD4A1369A2466359852CC2795FBCD279520A2369A01000000E80C75980100000000820A97589E369A0000000000CE27950200000002000000010000000000000080BA74985C000000060000000000000090AD369A000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:17.151  6517  6320 W google-breakpad: S 9A369F80 0000000000000000000000000000000000000000000000000000000000C427950000000000000000010000000200000020A75B9600830A97E52847B0000000000000000046804C6100000000080EF3B600000000E0ED46B0C8BA2798F09F369A6CA3369AA8663598000000000000000010A4369A00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:17.152  6517  6320 W google-breakpad: S 9A36A100 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000046804C61080EF3B610A2369AE0ED46B0C0A2369A20A2369A50CB38957CA2369AE46A359800000000000000000000000040B0029720A2369A0100000000AF369AF6FFFFFFECED46B0E8E60000E0ED46B010A2369A0300000008000000603F079788FFFFFF40B0029788FFFFFFB028D79585FFFFFFFFFFFFFF008041B00000000008000000000000006B27F1B600000000000000000800000067E3F0B60000000046804C6100000000E0ED46B0D0A2369AC0A2369AC8A2369ABCA2369A82FFFFFF48CB3895ACA2369A38552598
,08-26 15:00:17.153  6517  6320 W google-breakpad: S 9A36A280 48CB3895C8A2369A40B0029788FFFFFF0CA3369A40A3369A20A4369A01000000D8A2369A000000000CA3369A20EB4698C8A2369A000000000000000040B00297603F079788FFFFFF0000000082FFFFFF0100000048CB38950000000082FFFFFFE0ED46B0000000006C17609840A3369A30A3369A806C4CB0186F4CB0E0ED46B020A4369A6C1760987CA3369AB8FA3D9840A3369A4F000000DC2F3495BC85AA9500000000B085AA9590A3369A94A3369A40B0029788FFFFFFE0ED46B000000000B028D79585FFFFFFE0ED46B00000000090A3369A18706198DD85AA95B0A3369A20A4369AA0A3369AE0ED46B094A3369A22000000806C4CB0E4A3369AEC6A3F98E4D85F9850DC5F9858DB759822000000BC85AA95F4D93B9500000000B4A3369A220000000000000038A5369A00000000CCA3369A1435FD9768A4369A38A5369A18C1769830A4369A000000000100000020A4369A10A4369A22000000E0ED46B074A5369A2894429838CB389500000000E0ED46B000A4369A0200000048A4369A
08-26 15:00:17.153  6517  6320 W google-breakpad: S 9A36A400 90BC619668A4369A4046D19588FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0ED46B00100000098A5369AA8A5369A0100000038CB38950700000007000000010000005027D79500000000E0ED46B00000000000000000060000003CC176983CC176980600000018C1769800000000FFFFFFFF0000000040CB3895220000005827D7950700000000000000010000001800109750526A9481FFFFFFD4A4369AE0AA2F98070000005027D795E0ED46B00000000010001097E0A4369A14A5369AE8EC2F980000000000000000000000000CD4BA9C48A5369A0100000000000000C04AD195E01B11975027D79500000000FFFFFFFF50526A9481FFFFFFB0A5369AB0D4BA9C08A6369A24A5369A70A5369A000000000000000078D4BA9C4003000001000000FFFFFFFF81FFFFFF5027D79585FFFFFF1000109785FFFFFF80A5369A6049069788FFFFFF881CBD9C00000000FFFFFFFFC0526A9481FFFFFFB0A5369A387F3D9B0000000084A5369A
08-26 15:00:17.154  6517  6320 W google-breakpad: S 9A36A580 8C893D9B0000000000000000881CBD9C42020000010000006049069788FFFFFF00EA029788FFFFFF5027D79585FFFFFF0CA6369AC0526A94881CBD9C010500005027D79585FFFFFF00EA029788FFFFFF6049069788FFFFFF0000000082FFFFFF000000002831269A40020000000000005000000030BD0297F0D9119785FFFFFF3CA6369A54A6369A0000000030A6369A8C893D9B8201000080860697010000000000000082FFFFFF5027D79585FFFFFFDCA6369AC08D0A952CCCBB9C010A00005027D79585FFFFFF0000000082FFFFFF8086069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007109785FFFFFFF0D9119785FFFFFF82FFFFFF58187F98F0FB1197EC7A249AA000000030BD02970000000083FFFFFFE87B249A020000000000000008A7369A8C893D9B02020000C04C069702000000A0C6059788FFFFFF5027D79585FFFFFF
08-26 15:00:17.155  6517  6320 W google-breakpad: S 9A36A700 A0A75B9688FFFFFF7CA7369A80390296BCBC249A81060000F0D9119785FFFFFF5027D79585FFFFFFA0C6059788FFFFFFC04C069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000060A7369A0000000083FFFFFF68000000107C7F955827D7950100000030000000107C7F9500000000A0A7369A8C893D9B8201000020A66196010000000000000082FFFFFF5027D79585FFFFFF24A8369A70320296FCB4249A810700005027D79585FFFFFF0000000082FFFFFF20A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF40A8369A38A8369A30A8369AA4A8369A78000000107C7F95000000001686B39358DB7598E0ED46B00000000048A8369A8C893D9B8201000060A66196010000000000000082FFFFFF5027D79585FFFFFFB4A8369A98280296DCAA249A010600005027D79585FFFFFF0000000082FFFFFF60A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:17.156  6517  6320 W google-breakpad: S 9A36A880 0000000082FFFFFF00000000C0A8369AD8A8369A0400000060000000107C7F95E018029681FFFFFF44A9369AF83F3D9B00000000D8A8369A8C893D9B8201000080A66196010000000000000082FFFFFF5027D79585FFFFFF44A9369A98220296E0A1249A010600005027D79585FFFFFF0000000082FFFFFF80A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000604AD19500000000201EAF9460000000904AD19504000000E87B249A54A9369A780412980400000068A9369A8C893D9B82010000A0A66196010000000000000082FFFFFF604AD19588FFFFFFE4A9369A90170296F498249A01070000604AD19588FFFFFF0000000082FFFFFFA0A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013119785FFFFFF5027D79585FFFFFF00000000D8A9369AD4A9369A88FFFFFF70000000304AD1956085D19584E1249800000000000000000400000,008AA369A8C893D9B8201000020A761960100000070B3D09688FFFFFF
08-26 15:00:17.157  6517  6320 W google-breakpad: S 9A36AA00 A046D19588FFFFFF64AA369A602CF8936092249A01050000A046D19588FFFFFF70B3D09688FFFFFF20A7619688FFFFFFC0D3119785FFFFFF6085D1950100000094AA369AACAA369A5000000040707F9502000000706F809684AA369AC80312980000000098AA369ADC8DBE9C8202000080776F96030000000000000082FFFFFFA046D19588FFFFFF0000000081FFFFFF6085D19588FFFFFF34AB369AD0169695E852B89C010900006085D19588FFFFFF0000000081FFFFFFA046D19588FFFFFF0000000082FFFFFF80776F9688FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF9091C19488FFFFFF0000000082FFFFFF0900000081FFFFFF6085D19588FFFFFFB085D1950000000064AB369AC0D602979000000020C00297E87B249A020000007023F89381FFFFFF0000000058AB369A8C893D9B82010000B0020397010000006085D19588FFFFFF80776F9688FFFFFFDCAB369A2828F893D08B249A8107000080776F9688FFFFFF6085D19588FFFFFFB002039788FFFFFF
08-26 15:00:17.158  6517  6320 W google-breakpad: S 9A36AB80 B085D19588FFFFFFC0D6029788FFFFFFC0D0029788FFFFFF0000000082FFFFFFB085D19588FFFFFF0000000082FFFFFF00AC369A387F3D9B00000000C4AB369A7800000040707F95000000002482249A42030000030000000000000008AC369A8C893D9B02020000A0776F96020000007069779388FFFFFF90BC619688FFFFFF6085D19588FFFFFF74AC369A781DF893F086249A010600006085D19588FFFFFF90BC619688FFFFFF7069779388FFFFFFA0776F9688FFFFFF0000000082FFFFFF0000000082FFFFFF38AC369AA03504978028D795401111976000000040707F9585FFFFFFDC76269A85FFFFFF74AC369A0000000000370497E881269A800B0000E0776F96020000000037049788FFFFFF90BC619688FFFFFF603FD69588FFFFFF9028D79585FFFFFF1085D19588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFC047D195603FD695A03504971085DD958A0000007049D1959028D7951085D195603FD695A03504978028D795801810977085DD95
08-26 15:00:17.158  6517  6320 W google-breakpad: S 9A36AD00 0900000040A75B96D0B00297D0B00297603FD69588FFFFFF0900000040111197090000000037049790BC61967046D19540A75B9688FFFFFF0000000064FDB59C08FFB59C0004000080360497010000000037049788FFFFFF90BC619688FFFFFF0000000082FFFFFFF02A7F9890BC61964046D1951046D1950000000087FFFFFFA00F0397E045D1951046D19520A75B96E0DDBA9C80020000C0360497020000000000000082FFFFFFA00F039788FFFFFFE045D19588FFFFFFF0AD369AE045D1958045D195B045D195FC00BB9C8002000000370497000000008045D19588FFFFFF1012D8958A000000070000002012D895E0ED46B040B002970085DD950037049720B83C9B03020000603F07970100000040B0029788FFFFFF0085DD9585FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0ED46B0080EF3B6C8AF369A0100000081FFFFFF20AF369A
08-26 15:00:17.159  6517  6320 W google-breakpad: S 9A36AE80 8CAF369A14C41798603F07970000000000000000F0AE369AA4AE369A38B73C9B58DB7598E0ED46B000B446B00CC0369A00000000000000000000000001000000F4B6369AE0ED46B00001369A00000000B0FFBA9C00000000603F079780B3369A020000000100000014AF369A000000000100000081FFFFFF00B1369A0000000558B3369AF6FFFFFFECED46B001000000E0ED46B020AF369A000000000800000044AF369A14A43B980000800020000000C8B1369AF87B0A97000010000000000094AF369A01000000C8AF369AE0ED46B0783B7F9800820A970000000030CB38958CAF369A46804C6100000000E0ED46B0C8AF369A90AF369A603F079700820A970000000030CB3895B4AF369A2C65359800000000B4083D9802000000080EF3B601000000E0ED46B088B3369AC0AF369A3CB3369A24663598CCAF369A0C093D9888B3369A01000000E80C75980100000000820A97C0AF369A00000000009B3B980200000038000000C4900D962C9A3B9811B0369A38000000C0B3369A11B1369A
08-26 15:00:17.160  6517  6320 W google-breakpad: S 9A36B000 3C000000000000E0080EF3B6C8B1369A60B0369AF87B0A9740BC61960000000094900D96F0B73B98D8900D963CB0369A010000004CB0369A4CB0369AFFFFFF00010000005CB0369A08000000DC900D96B0900D964CC8249A58C8249A20803B9830C8249AF0FFFFFFFFFFFFFF00000000C8B1369A446FF2692400000060C8249AC8B1369AA4B0369A10000000A4B0369A74B1369AC8B0369A74B1369AA8B0369AC4B0369AE0061B98EC8FF3B658C8249A74B1369A74B1369AEC8FF3B6F8B0369AECB0369A48081B98F4B0369A00000000784D7692E0B3369A01000000784D7692E0ED46B0C8B1369A01000000784D7692E0ED46B040BC619640BC6196000000001CB1369ACD5BEDB6C0B2369A2CC30798F8B8369AC8B1369A2CB1369A246B169800000000080EF3B6B4BC369A5C3D1B9800407692BCC060980D0000007CC42E93030000000000,00000000000000AB1B980040769264C360981895269AC8B1369A010000000040769280B1369AF87B0A9740BC619628CB739841B002970881269A
08-26 15:00:17.161  6517  6320 W google-breakpad: S 9A36B180 10000000280000001C0000002C00000000000000784D76920D0000007CC42E9303000000000000000D000000CC7A3B980200000001000000C8B1369A000000000000000000000000D8B1369A0000000000000000000000000000000000000000F0B1369A000000000000000000000000000000000000000008B2369A000000000000000000000000000000000000000020B2369A00000000000000000000000030B2369A00000000010000000000000040B2369A000000000000000000000000080000000000000058B2369A00000000080000000000000068B2369A00000000080000000000000078B2369A00000000080000000000000088B2369A00000000000000000000000098B2369A000000000000000005000000A8B2369A000000000000000002000000020000000000000018CB38950100000001000000000000000000000000000000D8B2369A0000000000000000000000002000000000000000F0B2369A00000000200000000000000001B3369A0000000008B3369A05000000
08-26 15:00:17.162  6517  6320 W google-breakpad: S 9A36B300 010000000500000018B3369A0200000001000000D000000028B3369A46804C61080EF3B678B3369AE0ED46B028B4369A88B3369A30CB3895E4B3369AE46A359850B3369A000000000100000040B0029788B3369A0100000068C0369AF6FFFFFFECED46B0C8E60000E0ED46B078B3369A0300000008000000603F079788FFFFFF40B0029788FFFFFF0085DD9585FFFFFFFFFFFFFF008041B00000000008000000000000006B27F1B600000000000000000800000067E3F0B601940D9646804C61702A7398E0ED46B038B4369A28B4369A30B4369A24B4369A82FFFFFF28CB389514B4369A3855259828CB389530B4369A40B0029788FFFFFF74B4369AA8B4369A88B5369A0100000040B4369A0000000074B4369A20EB469830B4369A08000000408DC0B440B00297603F079788FFFFFF0000000082FFFFFF0100000028CB38950000000082FFFFFFE0ED46B0000000006C176098A8B4369A98B4369A806C4CB0186F4CB0E0ED46B088B5369A6C176098E4B4369AB8FA3D98A8B4369A4F000000
08-26 15:00:17.162  6517  6320 W google-breakpad: S 9A36B480 DC2F34956C85AA95000000006085AA95F8B4369AFCB4369A40B0029788FFFFFFE0ED46B0000000000085DD9585FFFFFFE0ED46B000000000F8B4369A187061988D85AA9518B5369A88B5369A08B5369AE0ED46B0FCB4369A22000000806C4CB04CB5369AEC6A3F98E4D85F9850DC5F9858DB7598220000006C85AA95C4D93B95000000001CB5369A2200000000000000A0B6369A0000000034B5369A1435FD97D0B5369AA0B6369A18C1769898B5369A000000000100000088B5369A78B5369A22000000E0ED46B0DCB6369A2894429818CB389500000000E0ED46B068B5369A02000000B0B5369A40BC6196D0B5369AD040D19588FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0ED46B00100000000B7369A10B7369A0100000018CB3895070000000700000001000000A083DD9500000000E0ED46B00000000000000000060000003CC176983CC176980600000018C1769800000000FFFFFFFF0000000020CB389522000000A883DD95
08-26 15:00:17.163  6517  6320 W google-breakpad: S 9A36B600 0700000000000000010000001800109750526A9481FFFFFF3CB6369AE0AA2F9807000000A083DD95E0ED46B0000000001000109748B6369A7CB6369AE8EC2F98D08DC0B400000000000000000CD4BA9CB0B6369A01000000980780925045D195E01B1197A083DD9500000000FFFFFFFF50526A9481FFFFFF18B7369AB0D4BA9C70B7369A8CB6369AD8B6369A000000000000000078D4BA9C4003000001000000FFFFFFFF81FFFFFFA083DD9585FFFFFF1000109785FFFFFFF0B6369A6049069788FFFFFF881CBD9C00000000FFFFFFFFC0526A9481FFFFFF18B7369A387F3D9B00000000ECB6369A8C893D9B0000000000000000881CBD9C42020000010000006049069788FFFFFF00EA029788FFFFFFA083DD9585FFFFFF74B7369AC0526A94881CBD9C01050000A083DD9585FFFFFF00EA029788FFFFFF6049069788FFFFFF0000000082FFFFFF000000002831269A40020000000000005000000030BD0297F0D9119785FFFFFFA4B7369ABCB7369A0000000098B7369A8C893D9B82010000
08-26 15:00:17.164  6517  6320 W google-breakpad: S 9A36B780 80860697010000000000000082FFFFFFA083DD9585FFFFFF44B8369AC08D0A952CCCBB9C010A0000A083DD9585FFFFFF0000000082FFFFFF8086069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007109785FFFFFFF0D9119785FFFFFF82FFFFFF58187F98F0FB1197EC7A249AA000000030BD02970000000083FFFFFFE87B249A020000000000000070B8369A8C893D9B02020000C04C069702000000A0C6059788FFFFFFA083DD9585FFFFFF00A75B9688FFFFFFE4B8369A80390296BCBC249A81060000F0D9119785FFFFFFA083DD9585FFFFFFA0C6059788FFFFFFC04C069788FFFFFF0000000082FFFFFF0,000000082FFFFFF0000000082FFFFFFC1030000C8B8369A0000000083FFFFFF68000000107C7F95A883DD950100000030000000107C7F950000000008B9369A8C893D9B8201000020A66196010000000000000082FFFFFF
08-26 15:00:17.165  6517  6320 W google-breakpad: S 9A36B900 A083DD9585FFFFFF8CB9369A70320296FCB4249A81070000A083DD9585FFFFFF0000000082FFFFFF20A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFA8B9369AA0B9369A98B9369A0CBA369A78000000107C7F95000000001686B39358DB7598E0ED46B000000000B0B9369A8C893D9B8201000060A66196010000000000000082FFFFFFA083DD9585FFFFFF1CBA369A98280296DCAA249A01060000A083DD9585FFFFFF0000000082FFFFFF60A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000028BA369A40BA369A0400000060000000107C7F95E018029681FFFFFFACBA369AF83F3D9B0000000040BA369A8C893D9B8201000080A66196010000000000000082FFFFFFA083DD9585FFFFFFACBA369A98220296E0A1249A01060000A083DD9585FFFFFF0000000082FFFFFF80A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:17.166  6517  6320 W google-breakpad: S 9A36BA80 00000000F044D19500000000201EAF94600000002045D19504000000E87B249ABCBA369A7804129804000000D0BA369A8C893D9B82010000A0A66196010000000000000082FFFFFFF044D19588FFFFFF4CBB369A90170296F498249A01070000F044D19588FFFFFF0000000082FFFFFFA0A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013119785FFFFFFA083DD9585FFFFFF0000000040BB369A3CBB369A88FFFFFF70000000C044D195C03ED69584E1249800000000000000000400000070BB369A8C893D9B8201000020A761960100000070B3D09688FFFFFF3041D19588FFFFFFCCBB369A602CF8936092249A010500003041D19588FFFFFF70B3D09688FFFFFF20A7619688FFFFFFC0D3119785FFFFFFC03ED69501000000FCBB369A14BC369A5000000040707F9502000000706F8096ECBB369AC80312980000000000BC369ADC8DBE9C8202000080776F96030000000000000082FFFFFF3041D19588FFFFFF0000000081FFFFFFC03ED69588FFFFFF
08-26 15:00:17.166  6517  6320 W google-breakpad: S 9A36BC00 9CBC369AD0169695E852B89C01090000C03ED69588FFFFFF0000000081FFFFFF3041D19588FFFFFF0000000082FFFFFF80776F9688FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF2091C19488FFFFFF0000000082FFFFFF0900000081FFFFFFC03ED69588FFFFFF103FD69500000000CCBC369AC0D602979000000020C00297E87B249A020000007023F89381FFFFFF00000000C0BC369A8C893D9B82010000B002039701000000C03ED69588FFFFFF80776F9688FFFFFF44BD369A2828F893D08B249A8107000080776F9688FFFFFFC03ED69588FFFFFFB002039788FFFFFF103FD69588FFFFFFC0D6029788FFFFFFC0D0029788FFFFFF0000000082FFFFFF103FD69588FFFFFF0000000082FFFFFF68BD369A387F3D9B000000002CBD369A7800000040707F95000000002482249A42030000030000000000000070BD369A8C893D9B02020000A0776F96020000007069779388FFFFFF40BC619688FFFFFFC03ED69588FFFFFFDCBD369A781DF893F086249A01060000
08-26 15:00:17.167  6517  6320 W google-breakpad: S 9A36BD80 C03ED69588FFFFFF40BC619688FFFFFF7069779388FFFFFFA0776F9688FFFFFF0000000082FFFFFF0000000082FFFFFFA0BD369AA0350497D084DD95401111976000000040707F9585FFFFFFDC76269A85FFFFFFDCBD369A0000000000370497E881269A800B0000E0776F96020000000037049788FFFFFF40BC619688FFFFFFD038D69588FFFFFFE084DD9585FFFFFF703ED69588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF5042D195D038D695A03504971012D8958A0000000044D195E084DD95703ED695D038D695A0350497D084DD95801810977012D89509000000A0A65B96D0B00297D0B00297D038D69588FFFFFF0900000040111197090000000037049740BC61960041D195A0A65B9688FFFFFF0000000064FDB59C08FFB59C0004000080360497010000000037049788FFFFFF40BC619688FFFFFF0000000082FFFFFFF02A7F9840BC6196D040D195A040D1950000000087FFFFFFA00F03977040D195A040D19580A65B96E0DDBA9C80020000
,08-26 15:00:17.168  6517  6320 W google-breakpad: S 9A36BF00 C0360497020000000000000082FFFFFFA00F039788FFFFFF7040D19588FFFFFF8CC0369A7040D1951040D1954040D195FC00BB9C8002000000370497000000001040D19588FFFFFF20C9369A4800000064BF369A30C7369A4800000040B002970012D8950037049720B83C9B03020000603F07970100000040B0029788FFFFFF0012D89585FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0ED46B0080EF3B630C1369A0100000081FFFFFF88C0369AF4C0369A14C41798603F0797000000000000000058C0369A0CC0369A38B73C9B58DB7598E0ED46B000B446B074D1369A000000000000000000000000010000005CC8369AE0ED46B00001439200000000B0FFBA9C00000000603F0797E8C4369A020000000100000070292493000000000100000081FFFFFF00AF1D9830CF2E93C0C4369AF6FFFFFFECED46B001000000E0ED46B088C0369A,
08-26 15:00:17.169  6517  6320 W google-breakpad: S 9A36C080 0000000008000000EC8FF3B600304392C02924939A010000B01F24930030439270304392180400004891BE950100000030C1369AE0ED46B0783B7F9800820A970000000000CB3895F4C0369A46804C6100000000E0ED46B030C1369AF8C0369A603F079700820A970000000000CB38951CC1369A2C65359800000000F8CF2E9300000000080EF3B601000000E0ED46B0F0C4369A28C1369AA4C4369A2466359852CC2795FBCD2795F0C4369A01000000E80C75980100000000820A9728C1369A0000000000CE27950200000002000000010000000000000080BA74985C000000060000000000000060D0369A00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:17.170  6517  6320 W google-breakpad: S 9A36C200 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C4279500000000000000000100000002000000E0A55B9600830A97E52847B0000000000000000046804C6100000000080EF3B600000000E0ED46B0C8BA2798C0C2369A3CC6369AA86635980000000000000000E0C6369A0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:17.170  6517  6320 W google-breakpad: S 9A36C380 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000038C4369AB92DF0B69807809201000000482A40B0010000007C0E8092FFFFFFFF50288092FFFFFFFF14220095FFFFFFFFC8220093FFFFFFFF0816809201000000088EC0B4FFFFFFFF088EC0B4000000000000000046804C61080EF3B6E0C4369AE0ED46B090C5369AF0C4369A00CB38954CC5369AE46A359800000000000000000000000040B00297F0C4369A01000000D0D1369AF6FFFFFFECED46B0A8E60000E0ED46B0E0C4369A0300000008000000603F079788FFFFFF40B0029788FFFFFF0012D89585FFFFFFFFFFFFFF008041B0
08-26 15:00:17.171  6517  6320 W google-breakpad: S 9A36C500 0000000008000000000000006B27F1B600000000000000000800000067E3F0B60000000046804C6100000000E0ED46B0A0C5369A90C5369A98C5369A8CC5369A82FFFFFFF8CA38957CC5369A38552598F8CA389598C5369A40B0029788FFFFFFDCC5369A10C6369AF0C6369A01000000A8C5369A00000000DCC5369A20EB469898C5369A040000400000000040B00297603F079788FFFFFF0000000082FFFFFF01000000F8CA38950000000082FFFFFFE0ED46B0000000006C17609810C6369A00C6369A806C4CB0186F4CB0E0ED46B0F0C6369A6C1760984CC6369AB8FA3D9810C6369A4F000000DC2F34951C85AA95000000001085AA9560C6369A64C6369A40B0029788FFFFFFE0ED46B0000000000012D89585FFFFFFE0ED46B00000000060C6369A187061983D85AA9580C6369AF0C6369A70C6369AE0ED46B064C6369A22000000806C4CB0B4C6369AEC6A3F98E4D85F9850DC5F9858DB7598220000001C85AA9594D93B950000000084C6369A220000000000000008C8369A00000000
,08-26 15:00:17.172  6517  6320 W google-breakpad: S 9A36C680 9CC6369A1435FD9738C7369A08C8369A18C1769800C7369A0000000001000000F0C6369AE0C6369A22000000E0ED46B044C8369A28944298E0CA38950000000038307492000000000000000018C7369A34C7369A38C7369A50C7369A000000000000000082FFFFFF00000000000100002200000000000000000000000000000000C7369AE0ED46B00100000068C8369A78C8369A01D31197E0CA3895070000000700000001000000A010D89500000020E0ED46B0E4C0369A98CC9D92060000003CC176983CC176980600000018C1769800000000FFFFFFFF00000000D0CA389522000000A810D8950700000000000000010000001800109750526A9401000000A4C7369AE0AA2F9807000000A010D895E0ED46B00000000010001097B0C7369AE4C7369AE8EC2F98B0C7369AB92DF0B6980780920CD4BA9C18C8369A0100000098078092D0FFD795E01B1197A010D89500000000FFFFFFFF50526A940100000080C8369AB0D4BA9CD8C8369AF4C7369A40C8369A000000000000000078D4BA9C
08-26 15:00:17.173  6517  6320 W google-breakpad: S 9A36C800 4003000001000000FFFFFFFF81FFFFFFA010D89585FFFFFF1000109785FFFFFFB082FF936049069788FFFFFF881CBD9C00000000FFFFFFFFC0526A940100000080C8369A387F3D9B0000000054C8369A8C893D9B0000000000000000881CBD9C42020000010000006049069788FFFFFF00EA029788FFFFFFA010D89585FFFFFFDCC8369AC0526A94881CBD9C01050000A010D89585FFFFFF00EA029788FFFFFF6049069788FFFFFF0000000082FFFFFF000000002831269A40020000000000005000000030BD0297F0D9119785FFFFFF0CC9369A24C9369A0000000000C9369A8C893D9B8201000080860697010000000000000082FFFFFFA010D89585FFFFFFACC9369AC08D0A952CCCBB9C010A0000A010D89585FFFFFF0000000082FFFFFF8086069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007109785FFFFFFF0D9119785FFFFFF
08-26 15:00:17.174  6517  6320 W google-breakpad: S 9A36C980 82FFFFFF58187F98F0FB1197EC7A249AA000000030BD02970000000083FFFFFF80FED7950302000000000000D8C9369A8C893D9B02020000C04C069702000000A0C6059788FFFFFFA010D89585FFFFFF60A65B9688FFFFFF4CCA369A80390296BCBC249A81060000F0D9119785FFFFFFA010D89585FFFFFFA0C6059788FFFFFFC04C069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000030CA369A0000000083FFFFFF68000000107C7F95A810D8950100000030000000107C7F950000000070CA369A8C893D9B8201000020A66196010000000000000082FFFFFFA010D89585FFFFFFF4CA369A70320296FCB4249A81070000A010D89585FFFFFF0000000082FFFFFF20A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF10CB369A08CB369A00CB369A74CB369A78000000107C7F95000000001686B39358DB7598E0ED46B00000000018CB369A8C893D9B82010000
08-26 15:00:17.174  6517  6320 W google-breakpad: S 9A36CB00 60A66196010000000000000082FFFFFFA010D89585FFFFFF84CB369A98280296DCAA249A01060000A010D89585FFFFFF0000000082FFFFFF60A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000090CB369AA8CB369A0400000060000000107C7F95E01802960100000014CC369AF83F3D9B00000000A8CB369A8C893D9B8201000080A66196010000000000000082FFFFFFA010D89585FFFFFF14CC369A98220296E0A1249A01060000A010D89585FFFFFF0000000082FFFFFF80A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000070FFD79500000000201EAF9460000000A0FFD7950400000080FED79524CC369A780412980400000038CC369A8C893D9B82010000A0A66196010000000000000082FFFFFF70FFD79588FFFFFFB4CC369A90170296F498249A0107000070FFD79588FFFFFF0000000082FFFFFFA0A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013119785FFFFFF
08-26 15:00:17.175  6517  6320 W google-breakpad: S 9A36CC80 A010D89585FFFFFF00000000A8CC369AA4CC369A88FFFFFF7000000040FFD7953038D69584E12498000000000000000004000000D8CC369A8C893D9B8201000020A761960100000070B3D09688FFFFFFB0FBD79588FFFFFF34CD369A602CF8936092249A01050000B0FBD79588FFFFFF70B3D09688FFFFFF20A7619688FFFFFFC0D3119785FFFFFF3038D6950100000064CD369A7CCD369A5000000040707F9503020000706F809654CD369AC80312980000000068CD369ADC8DBE9C8202000080776F96030000000000000082FFFFFFB0FBD79588FFFFFF0000000081FFFFFF3038D69588FFFFFF04CE369AD0169695E852B89C010900003038D69588FFFFFF0000000081FFFFFFB0FBD79588FFFFFF0000000082FFFFFF80776F9688FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFB090C19488FFFFFF0000000082FFFFFF0900000081FFFFFF3038D69588FFFFFF8038D6950000000034CE369,AC0D602979000000020C0029780FED795030200007023F89301000000
08-26 15:00:17.176  6517  6320 W google-breakpad: S 9A36CE00 0000000028CE369A8C893D9B82010000B0020397010000003038D69588FFFFFF80776F9688FFFFFFACCE369A2828F893D08B249A8107000080776F9688FFFFFF3038D69588FFFFFFB002039788FFFFFF8038D69588FFFFFFC0D6029788FFFFFFC0D0029788FFFFFF0000000082FFFFFF8038D69588FFFFFF0000000082FFFFFFD0CE369A387F3D9B0000000094CE369A7800000040707F95000000002482249A420300000300000000000000D8CE369A8C893D9B02020000A0776F96020000007069779388FFFFFFF0BB619688FFFFFF3038D69588FFFFFF44CF369A781DF893F086249A010600003038D69588FFFFFFF0BB619688FFFFFF7069779388FFFFFFA0776F9688FFFFFF0000000082FFFFFF0000000082FFFFFFCCA13D9B8CCF369A90CF369A000000006000000040707F9578CF369A0000000080FED795030200000000000070CF369A8C893D9B02020000E0776F96020000000037049788FFFFFFF0BB619688FFFFFF4032D69588FFFFFF0CD0369A58279396FC54BC9C01090000
08-26 15:00:17.177  6517  6320 W google-breakpad: S 9A36CF80 4032D69588FFFFFFF0BB619688FFFFFF0037049788FFFFFFE0776F9688FFFFFF0000000082FFFFFF0000000082FFFFFFE011D89585FFFFFFE037D69588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF00A65B9688FFFFFF80FED79588FFFFFF603F0797010000009000000080FBD79514D0369A04D0369A08257F9800000000040000005CD2369A08FFB59C0004000080360497010000000037049788FFFFFFF0BB619688FFFFFF0000000082FFFFFFF02A7F98F0BB619650FBD79520FBD7950000000087FFFFFFA00F0397F0FAD79520FBD795E0A55B96E0DDBA9C80020000C0360497020000000000000082FFFFFFA00F039788FFFFFFF0FAD79588FFFFFFC0D0369AF0FAD79590FAD795C0FAD795FC00BB9C80020000003704970000000090FAD79588FFFFFF107ED8958A00000007000000207ED895E0ED46B040B00297A0AFDE950037049720B83C9B03020000603F07970100000040B0029788FFFFFFA0AFDE9585FFFFFF00000000000000000000000000000000
08-26 15:00:17.178  6517  6320 W google-breakpad: S 9A36D100 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0ED46B0080EF3B698D2369A0100000081FFFFFFF0D1369A5CD2369A14C41798603F07970000000000000000C0D1369A74D1369A38B73C9B58DB7598E0ED46B000B446B0DCE2369A00000000000000000000000001000000C4D9369AE0ED46B00001000000000000B0FFBA9C00000000603F079750D6369A020000000100000000000000000000000100000081FFFFFF000000000000000028D6369AF6FFFFFFECED46B001000000E0ED46B0F0D1369A00000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000098D2369AE0ED46B0783B7F9800820A9700000000D0CA38955CD2369A46804C6100000000E0ED46B098D2369A60D2369A603F079700820A9700000000D0CA389584D2369A2C653598000000000000000000000000080EF3B601000000E0ED46B058D6369A90D2369A
08-26 15:00:17.179  6517  6320 W google-breakpad: S 9A36D280 0CD6369A2466359852CC2795FBCD279558D6369A01000000E80C75980100000000820A9790D2369A0000000000CE27950200000002000000010000000000000080BA74985C0000000600000000000000C8E1369A0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C427950000000000000000010000000200000040A55B9600830A97E52847B0000000000000000046804C61
,08-26 15:00:17.179  6517  6320 W google-breakpad: S 9A36D400 00000000080EF3B600000000E0ED46B0C8BA279828D4369AA4D7369AA8663598000000000000000048D8369A00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000,
08-26 15:00:17.180  6517  6320 W google-breakpad: S 9A36D580 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000046804C61080EF3B648D6369AE0ED46B0F8D6369A58D6369AD0CA3895B4D6369AE46A359800000000000000000000000040B0029758D6369A0100000038E3369AF6FFFFFFECED46B088E60000E0ED46B048D6369A0300000008000000603F079788FFFFFF40B0029788FFFFFFA0AFDE9585FFFFFFFFFFFFFF008041B00000000008000000000000006B27F1B600000000000000000800000067E3F0B60000000046804C6100000000E0ED46B008D7369AF8D6369A00D7369AF4D6369A82FFFFFFC8CA3895E4D6369A38552598C8CA389500D7369A40B0029788FFFFFF44D7369A78D7369A58D8369A0100000010D7369A0000000044D7369A20EB469800D7369A00000000408DC0B440B00297603F079788FFFFFF
08-26 15:00:17.181  6517  6320 W google-breakpad: S 9A36D700 0000000082FFFFFF01000000C8CA38950000000082FFFFFFE0ED46B0000000006C17609878D7369A68D7369A806C4CB0186F4CB0E0ED46B058D8369A6C176098B4D7369AB8FA3D9878D7369A4F000000DC2F3495CC84AA9500000000C084AA95C8D7369ACCD7369A40B0029788FFFFFFE0ED46B000000000A0AFDE9585FFFFFFE0ED46B000000000C8D7369A18706198ED84AA95E8D7369A58D8369AD8D7369AE0ED46B0CCD7369A22000000806C4CB01CD8369AEC6A3F98E4D85F9850DC5F9858DB759822000000CC84AA9564D93B9500000000ECD7369A220000000000000070D9369A0000000004D8369A1435FD97A0D8369A70D9369A18C1769868D8369A000000000100000058D8369A48D8369A22000000E0ED46B0ACD9369A28944298B0CA389500000000E0ED46B038D8369A0200000080D8369AA0BB6196A0D8369AE0F5D79588FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0ED46B001000000D0D9369AE0D9369A01000000
08-26 15:00:17.182  6517  6320 W google-breakpad: S 9A36D880 B0CA389507000000070000000100000040AEDE9500000000E0ED46B00000000000000000060000003CC176983CC176980600000018C1769800000000FFFFFFFF00000000B8CA38952200000048AEDE950700000000000000010000001800109750526A94010000000CD9369AE0AA2F980700000040AEDE95E0ED46B0000000001000109718D9369A4CD9369AE8EC2F98D08DC0B400000000000000000CD4BA9C80D9369A01000000E80BC09860FAD795E01B119740AEDE9500000000FFFFFFFF50526A9401000000E8D9369AB0D4BA9C40DA369A5CD9369AA8D9369A000000000000000078D4BA9C4003000001000000FFFFFFFF81FFFFFF40AEDE9585FFFFFF1000109785FFFFFFC0D9369A6049069788FFFFFF881CBD9C00000000FFFFFFFFC0526A9401000000E8D9369A387F3D9B00000000BCD9369A8C893D9B0000000000000000881CBD9C42020000010000006049069788FFFFFF00EA029788FFFFFF40AEDE9585FFFFFF44DA369AC0526A94881CBD9C0105000040AEDE9585FFFFFF
08-26 15:00:17.183  6517  6320 W google-breakpad: S 9A36DA00 00EA029788FFFFFF6049069788FFFFFF0000000082FFFFFF000000002831269A40020000000000005000000030BD0297F0D9119785FFFFFF74DA369A8CDA369A0000000068DA369A8C893D9B8201000080860697010000000000000082FFFFFF40AEDE9585FFFFFF14DB369AC08D0A952CCCBB9C010A000040AEDE9585FFFFFF0000000082FFFFFF8086069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007109785FFFFFFF0D9119785FFFFFF82FFFFFF58187F98F0FB1197EC7A249AA000000030BD02970000000083FFFFFF10F9D795030200000000000040DB369A8C893D9B02020000C04C069702000000A0C6059788FFFFFF40AEDE9585FFFFFFC0A55B9688FFFFFFB4DB369A80390296BCBC249A81060000F0D9119785FFFFFF40AEDE9585FFFFFFA0C6059788FFFFFFC04C069788FFFFFF0000000082FFFFFF0000000082FFFFFF
,08-26 15:00:17.183  6517  6320 W google-breakpad: S 9A36DB80 0000000082FFFFFFC103000098DB369A0000000083FFFFFF68000000107C7F9548AEDE950100000030000000107C7F9500000000D8DB369A8C893D9B8201000020A66196010000000000000082FFFFFF40AEDE9585FFFFFF5CDC369A70320296FCB4249A8107000040AEDE9585FFFFFF0000000082FFFFFF20A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF78DC369A70DC369A68DC369ADCDC369A78000000107C7F95000000001686B39358DB7598E0ED46B00000000080DC369A8C893D9B8201000060A66196010000000000000082FFFFFF40AEDE9585FFFFFFECDC369A98280296DCAA249A0106000040AEDE9585FFFFFF0000000082FFFFFF60A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000F8DC369A10DD369A0400000060000000107C7F95E0180296010000007CDD369AF83F3D9B0000000010DD369A8C893D9B8201000080A6619601000000
08-26 15:00:17.184  6517  6320 W google-breakpad: S 9A36DD00 0000000082FFFFFF40AEDE9585FFFFFF7CDD369A98220296E0A1249A0106000040AEDE9585FFFFFF0000000082FFFFFF80A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000000FAD79500000000201EAF946000000030FAD7950400000010F9D7958CDD369A7804129804000000A0DD369A8C893D9B82010000A0A66196010000000000000082FFFFFF00FAD79588FFFFFF1CDE369A90170296F498249A0107000000FAD79588FFFFFF0000000082FFFFFFA0A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013119785FFFFFF40AEDE9585FFFFFF0000000010DE369A0CDE369A88FFFFFF70000000D0F9D795A031D69584E1249800000000000000000400000040DE369A8C893D9B8201000020A761960100000070B3D09688FFFFFF40F6D79588FFFFFF9CDE369A602CF8936092249A0105000040F6D79588FFFFFF70B3D09688FFFFFF20A7619688FFFFFFC0D3119785FFFFFFA031D69501000000CCDE369AE4DE369A
08-26 15:00:17.185  6517  6320 W google-breakpad: S 9A36DE80 5000000040707F9503020000706F8096BCDE369AC803129800000000D0DE369ADC8DBE9C8202000080776F96030000000000000082FFFFFF40F6D79588FFFFFF0000000081FFFFFFA031D69588FFFFFF6CDF369AD0169695E852B89C01090000A031D69588FFFFFF0000000081FFFFFF40F6D79588FFFFFF0000000082FFFFFF80776F9688FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF4090C19488FFFFFF0000000082FFFFFF0900000081FFFFFFA031D69588FFFFFFF031D695000000009CDF369AC0D602979000000020C0029710F9D795030200007023F893010000000000000090DF369A8C893D9B82010000B002039701000000A031D69588FFFFFF80776F9688FFFFFF14E0369A2828F893D08B249A8107000080776F9688FFFFFFA031D69588FFFFFFB002039788FFFFFFF031D69588FFFFFFC0D6029788FFFFFFC0D0029788FFFFFF0000000082FFFFFFF031D69588FFFFFF0000000082FFFFFF38E0369A387F3D9B00000000FCDF369A7800000040707F95
08-26 15:00:17.186  6517  6320 W google-breakpad: S 9A36E000 000000002482249A42030000030000000000000040E0369A8C893D9B02020000A0776F96020000007069779388FFFFFFA0BB619688FFFFFFA031D69588FFFFFFACE0369A781DF893F086249A01060000A031D69588FFFFFFA0BB619688FFFFFF7069779388FFFFFFA0776F9688FFFFFF0000000082FFFFFF0000000082FFFFFFCCA13D9BF4E0369AF8E0369A000000006000000040707F95E0E0369A0000000010F9D7950302000000000000D8E0369A8C893D9B02020000E0776F96020000000037049788FFFFFFA0BB619688FFFFFFA02BD99588FFFFFF74E1369A58279396FC54BC9C01090000A02BD99588FFFFFFA0BB619688FFFFFF0037049788FFFFFFE0776F9688FFFFFF0000000082FFFFFF0000000082FFFFFF80AFDE9585FFFFFF5031D69588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF60A55B9688FFFFFF10F9D79588FFFFFF603F0797010000009000000010F6D7957CE1369A6CE1369A08257F980000000004000000C4E3369A08FFB59C00040000
08-26 15:00:17.187  6517  6320 W google-breakpad: S 9A36E180 80360497010000000037049788FFFFFFA0BB619688FFFFFF0000000082FFFFFFF02A7F98A0BB6196E0F5D795B0F5D7950000000087FFFFFFA00F039780F5D795B0F5D79540A55B96E0DDBA9C80020000C0360497020000000000000082FFFFFFA00F039788FFFFFF80F5D79588FFFFFF28E2369A80F5D79520F5D79550F5D795FC00BB9C80020000003704970000000020F5D79588FFFFFF20DDD5958A0000000700000030DDD595E0ED46B040B00297007ED8950037049720B83C9B03020000603F07970100000040B0029788FFFFFF007ED89585FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0ED46B0080EF3B600E4369A0100000081FFFFFF58E3369AC4E3369A14C41798603F0797000000000000000028E3369ADCE2369A38B73C9B58DB7598E0ED46B000B446B,044F4369A000000000000000000000000010000002CEB369AE0ED46B0
08-26 15:00:17.187  6517  6320 W google-breakpad: S 9A36E300 0001000000000000B0FFBA9C00000000603F0797B8E7369A020000000100000000000000000000000100000081FFFFFF000000000000000090E7369AF6FFFFFFECED46B001000000E0ED46B058E3369A00000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000000E4369AE0ED46B0783B7F9800820A9700000000A8CA3895C4E3369A46804C6100000000E0ED46B000E4369AC8E3369A603F079700820A9700000000A8CA3895ECE3369A2C653598000000000000000000000000080EF3B601000000E0ED46B0C0E7369AF8E3369A74E7369A2466359852CC2795FBCD2795C0E7369A01000000E80C75980100000000820A97F8E3369A0000000000CE27950200000002000000010000000000000080BA74985C000000060000000000000030F3369A0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:17.188  6517  6320 W google-breakpad: S 9A36E480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C4279500000000000000000100000002000000A0A45B9600830A97E52847B0000000000000000046804C6100000000080EF3B600000000E0ED46B0C8BA279890E5369A0CE9369AA86635980000000000000000B0E9369A000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:17.189  6517  6320 W google-breakpad: S 9A36E600 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000046804C61080EF3B6B0E7369AE0ED46B060E8369AC0E7369AA8CA38951CE8369AE46A35980000000000000000
08-26 15:00:17.190  6517  6320 W google-breakpad: S 9A36E780 0000000040B00297C0E7369A01000000A0F4369AF6FFFFFFECED46B068E60000E0ED46B0B0E7369A0300000008000000603F079788FFFFFF40B0029788FFFFFF007ED89585FFFFFFFFFFFFFF008041B00000000008000000000000006B27F1B600000000000000000800000067E3F0B60000000046804C6100000000E0ED46B070E8369A60E8369A68E8369A5CE8369A82FFFFFFA0CA38954CE8369A38552598A0CA389568E8369A40B0029788FFFFFFACE8369AE0E8369AC0E9369A0100000078E8369A00000000ACE8369A20EB469868E8369A000000000000000040B00297603F079788FFFFFF0000000082FFFFFF01000000A0CA38950000000082FFFFFFE0ED46B0000000006C176098E0E8369AD0E8369A806C4CB0186F4CB0E0ED46B0C0E9369A6C1760981CE9369AB8FA3D98E0E8369A4F000000DC2F34957C84AA95000000007084AA9530E9369A34E9369A40B0029788FFFFFFE0ED46B000000000007ED89585FFFFFFE0ED46B00000000030E9369A187061989D84AA9550E9369A
08-26 15:00:17.191  6517  6320 W google-breakpad: S 9A36E900 C0E9369A40E9369AE0ED46B034E9369A22000000806C4CB084E9369AEC6A3F98E4D85F9850DC5F9858DB7598220000007C84AA9534D93B950000000054E9369A2200000000000000D8EA369A000000006CE9369A1435FD9708EA369AD8EA369A18C17698D0E9369A0000000001000000C0E9369AB0E9369A22000000E0ED46B014EB369A2894429888CA389500000000E0ED46B0A0E9369A02000000E8E9369A50BB619608EA369A70F0D79588FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0ED46B00100000038EB369A48EB369A0100000088CA3895070000000700000001000000A07CD89500000000E0ED46B00000000000000000060000003CC176983CC176980600000018C1769800000000FFFFFFFF0000000098CA389522000000A87CD8950700000000000000010000001800109750526A940100000074EA369AE0AA2F9807000000A07CD895E0ED46B0000000001000109780EA369AB4EA369AE8EC2F98D08DC0B400000000
08-26 15:00:17.191  6517  6320 W google-breakpad: S 9A36EA80 000000000CD4BA9CE8EA369A01000000D40A8096F0F4D795E01B1197A07CD89500000000FFFFFFFF50526A940100000050EB369AB0D4BA9CA8EB369AC4EA369A10EB369A000000000000000078D4BA9C4003000001000000FFFFFFFF81FFFFFFA07CD89585FFFFFF1000109785FFFFFF28EB369A6049069788FFFFFF881CBD9C00000000FFFFFFFFC0526A940100000050EB369A387F3D9B0000000024EB369A8C893D9B0000000000000000881CBD9C42020000010000006049069788FFFFFF00EA029788FFFFFFA07CD89585FFFFFFACEB369AC0526A94881CBD9C01050000A07CD89585FFFFFF00EA029788FFFFFF6049069788FFFFFF0000000082FFFFFF000000002831269A40020000000000005000000030BD0297F0D9119785FFFFFFDCEB369AF4EB369A00000000D0EB369A8C893D9B8201000080860697010000000000000082FFFFFFA07CD89585FFFFFF7CEC369AC08D0A952CCCBB9C010A0000A07CD89585FFFFFF0000000082FFFFFF8086069788FFFFFF0000000082FFFFFF
08-26 15:00:17.192  6517  6320 W google-breakpad: S 9A36EC00 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007109785FFFFFFF0D9119785FFFFFF82FFFFFF58187F98F0FB1197EC7A249AA000000030BD02970000000083FFFFFFA0F3D7950302000000000000A8EC369A8C893D9B02020000C04C069702000000A0C6059788FFFFFFA07CD89585FFFFFF20A55B9688FFFFFF1CED369A80390296BCBC249A81060000F0D9119785FFFFFFA07CD89585FFFFFFA0C6059788FFFFFFC04C069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000000ED369A0000000083FFFFFF68000000107C7F95A87CD8950100000030000000107C7F950000000040ED369A8C893D9B8201000020A66196010000000000000082FFFFFFA07CD89585FFFFFFC4ED369A70320296FCB4249A81070000A07CD89585FFFFFF0000000082FFFFFF20A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:17.193  6517  6320 W google-breakpad: S 9A36ED80 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFE0ED369AD8ED369AD0ED369A44EE369A78000000107C7F95000000001686B39358DB7598E0ED46B000000000E8ED369A8C893D9B8201000060A66196010000000000000082FFFFFFA07CD89585FFFFFF54EE369A98280296DCAA249A01060000A07CD89585FFFFFF0000000082FFFFFF60A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000060EE369A78EE369A0400000060000000107C7F95E018029601000000E4EE369AF83F3D9B0000000078EE369A8C893D9B8201000080A66196010000000000000082FFFFFFA07CD89585FFFFFFE4EE369A98220296E0A1249A01060000A07CD89585FFFFFF0000000082FFFFFF80A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000090F4D79500000000201EAF9460000000C0F4D79504000000A0F3D795F4EE369A780412980400000008EF369A8C893D9B82010000A0A66196010000000000000082FFFFFF
08-26 15:00:17.194  6517  6320 W google-breakpad: S 9A36EF00 90F4D79588FFFFFF84EF369A90170296F498249A0107000090F4D79588FFFFFF0000000082FFFFFFA0A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013119785FFFFFFA07CD89585FFFFFF0000000078EF369A74EF369A88FFFFFF7000000060F4D795002BD99584E12498000000000000000004000000A8EF369A8C893D9B8201000020A761960100000070B3D09688FFFFFFD0F0D79588FFFFFF04F0369A602CF8936092249A01050000D0F0D79588FFFFFF70B3D09688FFFFFF20A7619688FFFFFFC0D3119785FFFFFF002BD9950100000034F0369A4CF0369A5000000040707F9503020000706F809624F0369AC80312980000000038F0369ADC8DBE9C8202000080776F96030000000000000082FFFFFFD0F0D79588FFFFFF0000000081FFFFFF002BD99588FFFFFFD4F0369AD0169695E852B89C01090000002BD99588FFFFFF0000000081FFFFFFD0F0D79588FFFFFF0000000082FFFFFF80776F9688FFFFFF0900000084FFFFFF0000000082FFFFFF
08-26 15:00:17.195  6517  6320 W google-breakpad: S 9A36F080 0000000081FFFFFF901F509688FFFFFF0000000082FFFFFF0900000081FFFFFF002BD99588FFFFFF502BD9950000000004F1369AC0D602979000000020C00297A0F3D795030200007023F8930100000000000000F8F0369A8C893D9B82010000B002039701000000002BD99588FFFFFF80776F9688FFFFFF7CF1369A2828F893D08B249A8107000080776F9688FFFFFF002BD99588FFFFFFB002039788FFFFFF502BD99588FFFFFFC0D6029788FFFFFFC0D0029788FFFFFF0000000082FFFFFF502BD99588FFFFFF0000000082FFFFFFA0F1369A387F3D9B0000000064F1369A7800000040707F95000000002482249A420300000300000000000000A8F1369A8C893D9B02020000A0776F96020000007069779388FFFFFF50BB619688FFFFFF002BD99588FFFFFF14F2369A781DF893F086249A01060000002BD99588FFFFFF50BB619688FFFFFF7069779388FFFFFFA0776F9688FFFFFF0000000082FFFFFF0000000082FFFFFFCCA13D9B5CF2369A60F2369A000000006000000040707F95
08-26 15:00:17.195  6517  6320 W google-breakpad: S 9A36F200 48F2369A00000000A0F3D795030200000000000040F2369A8C893D9B02020000E0776F96020000000037049788FFFFFF50BB619688FFFFFF1025D99588FFFFFFDCF2369A58279396FC54BC9C010900001025D99588FFFFFF50BB619688FFFFFF0037049788FFFFFFE0776F9688FFFFFF0000000082FFFFFF0000000082FFFFFFE07DD89585FFFFFFB02AD99588FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFC0A45B9688FFFFFFA0F3D79588FFFFFF603F07970100000090000000A0F0D795E4F2369AD4F2369A08257F9800000000040000002CF5369A08FFB59C0004000080360497010000000037049788FFFFFF50BB619688FFFFFF0000000082FFFFFFF02A7F9850BB619670F0D79540F0D7950000000087FFFFFFA00F039710F0D79540F0D795A0A45B96E0DDBA9C80020000C0360497020000000000000082FFFFFFA00F039788FFFFFF10F0D79588FFFFFF90F3369A10F0D795A03FD595D03FD595FC00BB9C800200000037049700000000A03FD59588FFFFFF
08-26 15:00:17.196  6517  6320 W google-breakpad: S 9A36F380 E00CD0958A00000007000000F00CD095E0ED46B040B0029710DDD5950037049720B83C9B03020000603F07970100000040B0029788FFFFFF10DDD59585FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0ED46B0080EF3B668F5369A0100000081FFFFFFC0F4369A2CF5369A14C41798603F0797000000000000000090F4369A44F4369A38B73C9B58DB7598E0ED46B000B446B0AC05379A0000000000000000000000000100000094FC369AE0ED46B00001000000000000B0FFBA9C00000000603F079720F9369A020000000100000000000000000000000100000081FFFFFF0000000000000000F8F8369AF6FFFFFFECED46B001000000E0ED46B0C0F4369A00000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000068F5369AE0ED46B0783B7F9800820A970000000080CA3895
08-26 15:00:17.197  6517  6320 W google-breakpad: S 9A36F500 2CF5369A46804C6100000000E0ED46B068F5369A30F5369A603F079700820A970000000080CA389554F5369A2C653598000000000000000000000000080EF3B601000000E0ED46B028F9369A60F5369ADCF8369A2466359852CC2795FBCD279528F9369A01000000E80C75980100000000820A9760F5369A0000000000CE27950200000002000000010000000000000080BA74985C00000006000000000000009804379A00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:17.198  6517  6320 W google-breakpad: S 9A36F680 00000000000000000000000000000000000000000000000000000000000000000000000000C427950000000000000000010000000200000000A45B9600830A97E52847B0000000000000000046804C6100000000080EF3B600000000E0ED46B0C8BA2798F8F6369A74FA369AA8663598000000000000000018FB369A0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:17.199  6517  6320 W google-breakpad: S 9A36F800 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000046804C61080EF3B618F9369AE0ED46B0C8F9369A28F9369A80CA389584F9369AE46A359800000000000000000000000040B0029728F9369A010000000806379AF6FFFFFFECED46B048E60000E0ED46B018F9369A0300000008000000603F079788FFFFFF40B0029788FFFFFF10DDD59585FFFFFFFFFFFFFF008041B00000000008000000000000006B27F1B600000000000000000800000067E3F0B60000000046804C6100000000E0ED46B0D8F9369AC8F9369AD0F9369AC4F9369A82FFFFFF78CA3895
08-26 15:00:17.200  6517  6320 W google-breakpad: S 9A36F980 B4F9369A3855259878CA3895D0F9369A40B0029788FFFFFF14FA369A48FA369A28FB369A01000000E0F9369A0000000014FA369A20EB4698D0F9369A00000000408DC0B440B00297603F079788FFFFFF0000000082FFFFFF0100000078CA38950000000082FFFFFFE0ED46B0000000006C17609848FA369A38FA369A806C4CB0186F4CB0E0ED46B028FB369A6C17609884FA369AB8FA3D9848FA369A4F000000DC2F34952C84AA95000000002084AA9598FA369A9CFA369A40B0029788FFFFFFE0ED46B00000000010DDD59585FFFFFFE0ED46B00000000098FA369A187061984D84AA95B8FA369A28FB369AA8FA369AE0ED46B09CFA369A22000000806C4CB0ECFA369AEC6A3F98E4D85F9850DC5F9858DB7598220000002C84AA9504D93B9500000000BCFA369A220000000000000040FC369A00000000D4FA369A1435FD9770FB369A40FC369A18C1769838FB369A000000000100000028FB369A18FB369A22000000E0ED46B07CFC369A2894429868CA389500000000E0ED46B008FB369A
08-26 15:00:17.201  6517  6320 W google-breakpad: S 9A36FB00 0200000050FB369A00BB619670FB369AF03AD59588FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0ED46B001000000A0FC369AB0FC369A0100000068CA3895070000000700000001000000B0DBD59500000000E0ED46B00000000000000000060000003CC176983CC176980600000018C1769800000000FFFFFFFF0000000070CA389522000000B8DBD5950700000000000000010000001800109750526A9401000000DCFB369AE0AA2F9807000000B0DBD595E0ED46B00000000010001097E8FB369A1CFC369AE8EC2F98D08DC0B400000000000000000CD4BA9C50FC369A01000000A42E0096703FD595E01B1197B0DBD59500000000FFFFFFFF50526A9401000000B8FC369AB0D4BA9C10FD369A2CFC369A78FC369A000000000000000078D4BA9C4003000001000000FFFFFFFF81FFFFFFB0DBD59585FFFFFF1000109785FFFFFF90FC369A6049069788FFFFFF881CBD9C00000000FFFFFFFFC0526A9401000000B8FC369A387F3D9B
08-26 15:00:17.201  6517  6320 W google-breakpad: S 9A36FC80 000000008CFC369A8C893D9B0000000000000000881CBD9C42020000010000006049069788FFFFFF00EA029788FFFFFFB0DBD59585FFFFFF14FD369AC0526A94881CBD9C01050000B0DBD59585FFFFFF00EA029788FFFFFF6049069788FFFFFF0000000082FFFFFF000000002831269A40020000000000005000000030BD0297F0D9119785FFFFFF44FD369A5CFD369A0000000038FD369A8C893D9B8201000080860697010000000000000082FFFFFFB0DBD59585FFFFFFE4FD369AC08D0A952CCCBB9C010A0000B0DBD59585FFFFFF0000000082FFFFFF8086069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007109785FFFFFFF0D9119785FFFFFF82FFFFFF58187F98F0FB1197EC7A249AA000000030BD02970000000083FFFFFF203ED595030200000000000010FE369A8C893D9B02020000C04C069702000000A0C6059788FFFFFF
08-26 15:00:17.202  6517  6320 W google-breakpad: S 9A36FE00 B0DBD59585FFFFFF80A45B9688FFFFFF84FE369A80390296BCBC249A81060000F0D9119785FFFFFFB0DBD59585FFFFFFA0C6059788FFFFFFC04C069788FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000068FE369A0000000083FFFFFF68000000107C7F95B8DBD5950100000030000000107C7F9500000000A8FE369A8C893D9B8201000020A66196010000000000000082FFFFFFB0DBD59585FFFFFF2CFF369A70320296FCB4249A81070000B0DBD59585FFFFFF0000000082FFFFFF20A6619688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF48FF369A40FF369A38FF369AACFF369A78000000107C7F95000000001686B39358DB7598E0ED46B00000000050FF369A8C893D9B8201000060A66196010000000000000082FFFFFFB0DBD59585FFFFFFBCFF369A98280296DCAA249A01060000B0DBD59585FFFFFF0000000082FFFFFF60A6619688FFFFFF0000000082FFFFFF
08-26 15:00:17.202  6517  6320 W google-breakpad: S 9A36FF80 0000000082FFFFFF0000000082FFFFFF00000000C8FF369AE0FF369A0400000060000000107C7F95E0180296010000004C00379AF83F3D9B00000000E0FF369A8C893D9B8201000080A66196010000000000000082FFFFFFB0DBD59585FFFFFF4C00379A98220296E0A1249A01060000B0DBD59585FFFFFF0000000082FFFFFF
08-26 15:00:17.203  6517  6320 W google-breakpad: C 06000040001058B0000000006480369AE080369A3880369A8C80369AE0ED46B06480369A6042D69585FFFFFF806C4CB05C80369A2080369A2880369A782925987C29259810000F200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:17.204  6517  6320 W google-breakpad: M B6F52000 00000000 00002000 8734159D8182F72B5360108998F669D60 app_process32
08-26 15:00:17.208  6517  6320 W google-breakpad: M 97D0B000 00000000 00A60000 886D6DA606BAF6E3428F775AFDA8BFB00 libjxcore.so
08-26 15:00:17.209  6517  6320 W google-breakpad: M 9D69B000 00000000 00005000 52A6412D61E6C42CA6A57FF38AD4FC0C0 gralloc.msm8226.so
08-26 15:00:17.209  6517  6320 W google-breakpad: M 9ECC8000 00000000 0000A000 92434EED1D88531F6F531210F620E1D70 libqservice.so
08-26 15:00:17.209  6517  6320 W google-breakpad: M 9EFD6000 00000000 00469000 F4AB4C6F6CCEC72B081FA92634F9DF360 libsc-a3xx.so
08-26 15:00:17.209  6517  6320 W google-breakpad: M 9F44E000 00000000 0000C000 FE1E23D2159CFD295F34996A111FBB9C0 eglsubAndroid.so
08-26 15:00:17.212  6517  6320 W google-breakpad: M A1B6C000 00000000 01AE1000 488126E5C3F082244EC0664CC97A94320 libwebviewchromium.so
08-26 15:00:17.212  6517  6320 W google-breakpad: M A7F6C000 00000000 00003000 9334D9805B275A75829ECC69380A5D2E0 libwebviewchromium_loader.so
08-26 15:00:17.213  6517  6320 W google-breakpad: M A7F6F000 00000000 00003000 8FF5949AE957364C270D0F448DAD4FE20 libjnigraphics.so
08-26 15:00:17.214  6517  6320 W google-breakpad: M A7F72000 00000000 00008000 F5D3384E9BEEEDF600C2C4D02CB7146A0 libcompiler_rt.so
,08-26 15:00:17.215  6517  6320 W google-breakpad: M A7F7A000 00000000 00010000 E4CEF5EDFBB5994F920E12960C27E0BC0 libandroid.so
08-26 15:00:17.222  6517  6320 W google-breakpad: M A7F8A000 00000000 0013B000 9C07A5706C6FD8E13025C6918642A80F0 libGLESv2_adreno.so
08-26 15:00:17.228  6517  6320 W google-breakpad: M A80C6000 00000000 00034000 CF692CC2042CC03999A6210A4668E2EF0 libGLESv1_CM_adreno.so
08-26 15:00:17.231  6517  6320 W google-breakpad: M A80FA000 00000000 00027000 E48344CD23F82BA0E7B940BC32BBBECF0 libgsl.so
08-26 15:00:17.231  6517  6320 W google-breakpad: M A8123000 00000000 00004000 EB49C798524706CBF3372BB9DFBB92C20 libadreno_utils.so
08-26 15:00:17.232  6517  6320 W google-breakpad: M A8128000 00000000 00029000 C29A639A4AEAC88466F1ACCA732D030E0 libEGL_adreno.so
08-26 15:00:17.233  6517  6320 W google-breakpad: M A958A000 00000000 00018000 AF017574A7821CB2261DD3AD8E68B8110 libjavacrypto.so
08-26 15:00:17.234  6517  6320 W google-breakpad: M A95A2000 00000000 00004000 B472CADC2448C211F1E320D88D27B5420 libemoji.so
08-26 15:00:17.235  6517  6320 W google-breakpad: M A95A6000 00000000 00009000 0D2F47D82DA4058B87D201CB8CFCC0BA0 librs_jni.so
08-26 15:00:17.236  6517  6320 W google-breakpad: M A95AF000 00000000 00006000 11185286066C9E9FCD6823AD5566C0A10 libaudioeffect_jni.so
08-26 15:00:17.236  6517  6320 W google-breakpad: M A95B5000 00000000 00004000 CDA9BA072D4DECC71C5E63467275E7EE0 libsoundpool.so
08-26 15:00:17.237  6517  6320 W google-breakpad: M A95B9000 00000000 00004000 82A278A7E21B4A314D9BE16CAA239F060 liblg_parser_qcp.so
08-26 15:00:17.238  6517  6320 W google-breakpad: M A95BD000 00000000 00006000 668D1570CE3FD1F09D9FEB0BE8EF85AC0 liblg_parser_ogm.so
08-26 15:00:17.240  6517  6320 W google-breakpad: M A95C3000 00000000 00014000 10C26557F124644418D3776ACB0060640 liblg_parser_mkv.so
08-26 15:00:17.241  6517  6320 W google-breakpad: M A95D7000 00000000 00007000 382E4730DF55A022477523CBB8FCC9710 liblg_parser_flv.so
08-26 15:00:17.242  6517  6320 W google-breakpad: M A95DE000 00000000 00004000 F4B87DC6C74B91E84FE7777B3E5906010 liblg_parser_dts.so
08-26 15:00:17.243  6517  6320 W google-breakpad: M A95E2000 00000000 0000C000 8E274BF3A141EC3CE5429E0CE1FA30CB0 liblg_parser_avi.so
08-26 15:00:17.244  6517  6320 W google-breakpad: M A95EE000 00000000 0000B000 F063E5B8FB9C577438EDFB5611B924190 liblg_parser_asf.so
08-26 15:00:17.245  6517  6320 W google-breakpad: M A95F9000 00000000 00004000 128196E62A9943A933F1E1195A96BE220 liblg_parser_ac3.so
08-26 15:00:17.247  6517  6320 W google-breakpad: M A95FD000 00000000 0000D000 1A3AE0BAE05AA19C0E70341D14A70F6F0 libLGCodecParserUtils.so
08-26 15:00:17.252  6517  6320 W google-breakpad: M A960A000 00000000 00052000 8511145F91B6E9DC0E4C3A2F73EC36F70 libLGParserOSAL.so
08-26 15:00:17.253  6517  6320 W google-breakpad: M A965C000 00000000 00004000 3FA8B89358F6F38194ED11741859BF530 libjhead_jni.so
08-26 15:00:17.255  6517  6320 W google-breakpad: M A9660000 00000000 0000E000 D791A978CC1F875366C3FDE9B33194060 libstagefright_amrnb_common.so
08-26 15:00:17.258  6517  6320 W google-breakpad: M A966E000 00000000 0001A000 F596626166534B070F7B57DA85DCA86F0 libvorbisidec.so
08-26 15:00:17.259  6517  6320 W google-breakpad: M A9688000 00000000 00009000 2C13DEB1B6771414DD42E8EFCE50D0250 libstreamingpolicy.so
08-26 15:00:17.259  6517  6320 W google-breakpad: M A9691000 00000000 00004000 9D3A1EEE172AFB35E2663261B36F7D400 libstagefright_yuv.so
08-26 15:00:17.260  6517  6320 W google-breakpad: M A9695000 00000000 00005000 21A9B2A67B28A953FC06D733BC7BDD8C0 libstagefright_timedtext_xsub.so
08-26 15:00:17.261  6517  6320 W google-breakpad: M A969A000 00000000 00006000 C2198A2C485ADBA7ED8DEB50EAE941270 libstagefright_timedtext_ccparser.so
08-26 15:00:17.264  6517  6320 W google-breakpad: M A96A0000 00000000 0001D000 C14A7473908F5EA75CA7E1D7004F41960 libstagefright_omx.so
,08-26 15:00:17.265  6517  6320 W google-breakpad: M A96BD000 00000000 00007000 741CD0CBF5589F8EDBD02FD7023550580 libstagefright_avc_common.so
08-26 15:00:17.271  6517  6320 W google-breakpad: M A96C4000 00000000 0003A000 E5C670B735242BF581AAFAC97791DAAD0 libopus.so
,08-26 15:00:17.273  6517  6320 W google-breakpad: M A96FE000 00000000 00013000 26C968C2EEFE0472C24581A7741CB1DF0 liblgetars.so
08-26 15:00:17.274  6517  6320 W google-breakpad: M A9715000 00000000 00006000 AC1D7BAE26791BE91E8BCCB199F3926F0 liblgresampler.so
08-26 15:00:17.274  6517  6320 W google-breakpad: M A971B000 00000000 00005000 3959C688C8EDD647686EDC0D8FBE83110 liblgaudioutils.so
08-26 15:00:17.282  6517  6320 W google-breakpad: M A9720000 00000000 00159000 A933B593929F3C362CB602C7CE80476B0 libstagefright.so
,08-26 15:00:17.285  6517  6320 W google-breakpad: M A9B1C000 00000000 00015000 A600837AA56318B462C907F827B457BF0 libmtp.so
,08-26 15:00:17.287  6517  6320 W google-breakpad: M A9B31000 00000000 0000B000 C23E765DA7EFD456B11A4B772CB778400 libjhead.so
08-26 15:00:17.295  6517  6320 W google-breakpad: M A9B3D000 00000000 0026B000 5F714815D0836D204C046E173AC47EC80 libWVStreamControlAPI_L3.so
,08-26 15:00:17.296  6517  6320 W google-breakpad: M AB000000 00000000 00003000 E11DA546CE9E08D1D647E8E1135DAD810 libstagefright_enc_common.so
,08-26 15:00:17.304  6517  6320 W google-breakpad: M AB003000 00000000 0002C000 FEA39E86228BE8028B0334A7E0331B200 libexif.so
08-26 15:00:17.305  6517  6320 W google-breakpad: M AB02F000 00000000 00014000 E9EE77C3D7D433365516A96B8AE34C790 libbrunch.so
08-26 15:00:17.307  6517  6320 W google-breakpad: M AB043000 00000000 0003C000 260D535C70B24A059C3DD13D265601400 libmedia_jni.so
,08-26 15:00:17.308  6517  6320 W google-breakpad: M B00DE000 00000000 00003000 9A115484806571313C641963FDAA69670 memtrack.msm8226.so
08-26 15:00:17.309  6517  6320 W google-breakpad: M B00E5000 00000000 00008000 73BEACFB34F012C578F2CBCFA3A714560 libqdutils.so
08-26 15:00:17.309  6517  6320 W google-breakpad: M B00ED000 00000000 00005000 878BE07CFBE9CD8D1D67C45CE007A7BA0 libmemalloc.so
08-26 15:00:17.310  6517  6320 W google-breakpad: M B1BFE000 00000000 00037000 EC4386CA92978B743AE8C0612A7128C50 libjavacore.so
08-26 15:00:17.310  6517  6320 W google-breakpad: M B3BFE000 00000000 00004000 F786FA54B1844430370450775E3839AD0 libwebviewchromium_plat_support.so
08-26 15:00:17.311  6517  6320 W google-breakpad: M B44F7000 00000000 00305000 3865F1A96E2B21A6EF7A30BC26CCB5FB0 libart.so
08-26 15:00:17.312  6517  6320 W google-breakpad: M B5096000 00000000 0001B000 195B37B83D4254C8B330DB89973D654E0 libdrmframework.so
08-26 15:00:17.313  6517  6320 W google-breakpad: M B50B2000 00000000 00008000 FE09F5ADF996273125BF471219C782630 libdrmframework_jni.so
08-26 15:00:17.313  6517  6320 W google-breakpad: M B5207000 00000000 00015000 4BA2AE649C0515F58E3A4F2EB156187B0 liblgalmond.so
08-26 15:00:17.313  6517  6320 W google-breakpad: M B521C000 00000000 00008000 DAEE33DE0444DFA19A5E9977EBC34B020 libbacktrace_libc++.so
08-26 15:00:17.313  6517  6320 W google-breakpad: M B5224000 00000000 00003000 6B5B53D0A10F826CC9EA2F6B88D39AF70 libcnefeatureconfig.so
08-26 15:00:17.313  6517  6320 W google-breakpad: M B5228000 00000000 00006000 5E93EF95A5A6222B4237CBEE5C5B19E20 libvendorconn.so
08-26 15:00:17.314  6517  6320 W google-breakpad: M B524E000 00000000 00004000 C88FD942703CD0910236DC719AB36EF90 libusbhost.so
08-26 15:00:17.314  6517  6320 W google-breakpad: M B5252000 00000000 0003F000 B22F42D05FF6D12B8B990F67BBF114260 libssl.so
08-26 15:00:17.315  6517  6320 W google-breakpad: M B5291000 00000000 000A5000 69EC663D7D4956711E46CB4333B4108F0 libsqlite.so
08-26 15:00:17.315  6517  6320 W google-breakpad: M B5337000 00000000 0000E000 FEEFBB918616C9664F948E273A3A03EF0 libsoundtrigger.so
08-26 15:00:17.315  6517  6320 W google-breakpad: M B5345000 00000000 00012000 1ED726B29E92DEC8EA3197FAED4636470 libpcre.so
08-26 15:00:17.315  6517  6320 W google-breakpad: M B5357000 00000000 0000E000 13E86CFFF130F842512F9D3ABB556C130 libselinux.so
08-26 15:00:17.316  6517  6320 W google-breakpad: M B5365000 00000000 00004000 4E6C8C876BA563C3C4B0B3BA562093920 libprocessgroup.so
08-26 15:00:17.320  6517  6320 W google-breakpad: M B5369000 00000000 00446000 83C530EBE395DB5C15F9E1A6BAF1B5740 libpdfium.so
08-26 15:00:17.321  6517  6320 W google-breakpad: M B57B4000 00000000 00004000 B080204D8695FBA941E35E376FBA4E8F0 libnetd_client.so
08-26 15:00:17.321  6517  6320 W google-breakpad: M B57B8000 00000000 00007000 8E6CAE05BFD7DE1B53E18F1D6A6F5BEE0 libnativehelper.so
08-26 15:00:17.321  6517  6320 W google-breakpad: M B57BF000 00000000 00004000 37054B221724BC2C01AA6EE6D46425740 libnativebridge.so
,08-26 15:00:17.323  6517  6320 W google-breakpad: M B57C3000 00000000 0000C000 34DA5C5BEFD3D3F076439D28B2EAF3600 libminikin.so
08-26 15:00:17.324  6517  6320 W google-breakpad: M B57CF000 00000000 00003000 CCA8BE0D07D24523C8D02FEE5F724EA70 libmemtrack.so
08-26 15:00:17.324  6517  6320 W google-breakpad: M B57D2000 00000000 00005000 EA3D9827398AB1CB4C13D1DAC7AFBF1C0 libpowermanager.so
08-26 15:00:17.325  6517  6320 W google-breakpad: M B57D7000 00000000 00015000 71C5EA36B4CE20563A0F4197D42051670 libstagefright_foundation.so
08-26 15:00:17.326  6517  6320 W google-breakpad: M B57EC000 00000000 0001C000 8E02720480177F53B812AD30BF3B72FE0 liblgdrm_client.so
08-26 15:00:17.328  6517  6320 W google-breakpad: M B5808000 00000000 00051000 6EBD71CB63633C219CC3F7A97D7B4D4C0 libsonivox.so
08-26 15:00:17.329  6517  6320 W google-breakpad: M B585E000 00000000 0000F000 E2DD6FCC6A85AF2204C3DD01BB5505510 libcommon_time_client.so
08-26 15:00:17.330  6517  6320 W google-breakpad: M B586D000 00000000 00009000 424F91688903AE89C61A0EB2A38B884D0 libnbaio.so
08-26 15:00:17.330  6517  6320 W google-breakpad: M B5876000 00000000 0000A000 E6B9F397F004151EE0822D0D830AED170 libmedia_ex.so
08-26 15:00:17.331  6517  6320 W google-breakpad: M B5880000 00000000 00005000 8D1366FBF8CAA032568C227712A97EBD0 libaudioparameter.so
08-26 15:00:17.332  6517  6320 W google-breakpad: M B5885000 00000000 000A9000 DF1D7256F5401E97FE39C599F9715B640 libmedia.so
08-26 15:00:17.334  6517  6320 W google-breakpad: M B592E000 00000000 00038000 197D8529D4736FFC8810A5DDA9D7156D0 libinputflinger.so
,08-26 15:00:17.335  6517  6320 W google-breakpad: M B5966000 00000000 0001A000 735B646A98ED5D627CC62B715BD4B1620 libinput.so
08-26 15:00:17.336  6517  6320 W google-breakpad: M B5980000 00000000 0000D000 3B926F72AB1625BE0AA7CC84C738C6300 libimg_utils.so
08-26 15:00:17.338  6517  6320 W google-breakpad: M B598D000 00000000 00032000 D435EDF7E2D4110BD215491B6CA7DE530 libjpeg.so
08-26 15:00:17.339  6517  6320 W google-breakpad: M B59BF000 00000000 00217000 374493F0DB82EA4D2AB745426F743D7A0 libskia.so
08-26 15:00:17.340  6517  6320 W google-breakpad: M B5BDB000 00000000 0001D000 F5BFC9B72DBB5B7BA590737EAB5185400 libRScpp.so
08-26 15:00:17.341  6517  6320 W google-breakpad: M B5BF8000 00000000 00027000 8D8D3A8173CEE8A7DAC890AC84E0C2210 libpng.so
08-26 15:00:17.343  6517  6320 W google-breakpad: M B5C20000 00000000 00059000 6560F3B8013A04F7702E4BAB5517CBE70 libft2.so
08-26 15:00:17.344  6517  6320 W google-breakpad: M B5C7A000 00000000 0003C000 506ED2DAD985E5138F4B28F7611B42A20 libbcinfo.so
08-26 15:00:17.344  6517  6320 W google-breakpad: M B5CB6000 00000000 00022000 CB37261C00D653D5DB7DFBF06FE8BC650 libbcc.so
08-26 15:00:17.344  6517  6320 W google-breakpad: M B5CF8000 00000000 0008C000 F247376FF48BF26BFB947B88BCE170710 libc++.so
08-26 15:00:17.345  6517  6320 W google-breakpad: M B5D86000 00000000 008FE000 DD4CE7B695B87B47C9E55A77C3A5DCB00 libLLVM.so
,08-26 15:00:17.346  6517  6320 W google-breakpad: M B668B000 00000000 00036000 C6BD1C78BC4C75B667669A4F7EFB95180 libRS.so
08-26 15:00:17.348  6517  6320 W google-breakpad: M B66C1000 00000000 0004B000 3C83FBB58F791A75238BD95B8B13E5DD0 libhwui.so
08-26 15:00:17.349  6517  6320 W google-breakpad: M B670C000 00000000 00107000 1944C4996C0BFD0F27EA043677EA49130 libicuuc.so
08-26 15:00:17.350  6517  6320 W google-breakpad: M B6817000 00000000 00006000 E3AE8BE37EE0B813F539936AB3929DEB0 libgabi++.so
08-26 15:00:17.351  6517  6320 W google-breakpad: M B681D000 00000000 00158000 23F1A0622B97B553871971130E2981050 libicui18n.so
08-26 15:00:17.354  6517  6320 W google-breakpad: M B6975000 00000000 00048000 CA4E26A13A874289F1CB754FE9FB7A460 libharfbuzz_ng.so
08-26 15:00:17.354  6517  6320 W google-breakpad: M B69BD000 00000000 00004000 B651006496AD564110C796F66C5EC9ED0 libwpa_client.so
08-26 15:00:17.355  6517  6320 W google-breakpad: M B69C1000 00000000 00006000 556B05513729F48DF69FD5DB6DD5CB9D0 libvolumevibratorcallback.so
08-26 15:00:17.355  6517  6320 W google-breakpad: M B69C7000 00000000 00008000 9FFBEDF3FF9D0412BDBF868A026D91830 libnetutils.so
08-26 15:00:17.356  6517  6320 W google-breakpad: M B69CF000 00000000 00004000 5E6F8FB1ABE22FE37DC1C9388C0D5E900 libatd_corelib.so
,08-26 15:00:17.356  6517  6320 W google-breakpad: M B69D4000 00000000 00004000 9418454BA0CA62D7606521089D87E7390 liblgftmitem.so
08-26 15:00:17.357  6517  6320 W google-breakpad: M B69D8000 00000000 0000D000 7B8A520D37C56AF1CC8A5DFA92D2167D0 libhardware_legacy.so
08-26 15:00:17.358  6517  6320 W google-breakpad: M B69E7000 00000000 00017000 BE487D5116BB4AF53060EBDC4CBCBED50 libexpat.so
08-26 15:00:17.358  6517  6320 W google-breakpad: M B69FE000 00000000 000F6000 08383DCE2A79CD51B656A4D77430F10F0 libcrypto.so
08-26 15:00:17.359  6517  6320 W google-breakpad: M B6AF6000 00000000 00003000 74BDE58D9533C5E7870D0EAFB9264B590 libhardware.so
08-26 15:00:17.359  6517  6320 W google-breakpad: M B6AF9000 00000000 0000C000 5AD01CC08B692452BC590DF63D5B4E600 libui.so
08-26 15:00:17.359  6517  6320 W google-breakpad: M B6B05000 00000000 00003000 2D9083CB8C22C02E1412DA13B1CA43AE0 libsync.so
08-26 15:00:17.360  6517  6320 W google-breakpad: M B6B08000 00000000 0004C000 40C0951EA1AF4EC38ECC93FCCD42FEEB0 libgui.so
08-26 15:00:17.361  6517  6320 W google-breakpad: M B6B54000 00000000 00008000 D8696C0232AD725A04A607DFFA2662E60 libcamera_metadata.so
08-26 15:00:17.362  6517  6320 W google-breakpad: M B6B5C000 00000000 00038000 CA16E558D8AD694A3AEFE3B867BE72A70 libcamera_client.so
08-26 15:00:17.362  6517  6320 W google-breakpad: M B6B94000 00000000 00006000 AC1D7BAE26791BE91E8BCCB199F3926F0 libspeexresampler.so
08-26 15:00:17.363  6517  6320 W google-breakpad: M B6B9A000 00000000 00006000 C51E7E210A0C2DA7F15A919C8BBA52D80 libaudioutils.so
08-26 15:00:17.363  6517  6320 W google-breakpad: M B6BA0000 00000000 0001A000 03AD8D1D4E22A7AE9B066E9786DBB3AE0 libz.so
08-26 15:00:17.364  6517  6320 W google-breakpad: M B6BBA000 00000000 0002D000 AF8C341C5F1A54BA6A750748ED080D760 libbinder.so
08-26 15:00:17.365  6517  6320 W google-breakpad: M B6BE7000 00000000 00026000 0C7AD2A1D846111DE3F1A3B54696FE350 libandroidfw.so
08-26 15:00:17.365  6517  6320 W google-breakpad: M B6C0D000 00000000 0000B000 E2F67EE50006FD0ED1482E1463C5CCFF0 libGLESv2.so
08-26 15:00:17.365  6517  6320 W google-breakpad: M B6C18000 00000000 00007000 EFE6ADDAF48E0BCED48FF0E60558C2F60 libGLESv1_CM.so
08-26 15:00:17.366  6517  6320 W google-breakpad: M B6C1F000 00000000 00004000 DE56AF21D1810CB9F5D59132F2B573690 libETC1.so
,08-26 15:00:17.366  6517  6320 W google-breakpad: M B6C23000 00000000 00004000 7A80CF6FADF6A3E8B908CC78ED49A6960 libunwind-ptrace.so
08-26 15:00:17.366  6517  6320 W google-breakpad: M B6C27000 00000000 0000E000 EF89B10946BDF6079AAF789F56192FDA0 libunwind.so
08-26 15:00:17.366  6517  6320 W google-breakpad: M B6C7B000 00000000 00007000 3874D35A672DF926049632908E3F44990 libgccdemangle.so
08-26 15:00:17.366  6517  6320 W google-breakpad: M B6C83000 00000000 00008000 565879110C8919C1B793CFC4047A2B9B0 libbacktrace.so
08-26 15:00:17.366  6517  6320 W google-breakpad: M B6C8D000 00000000 00016000 4999DE1B8A8F74002F98E921D65D73630 libutils.so
08-26 15:00:17.366  6517  6320 W google-breakpad: M B6CA3000 00000000 00036000 2F64392B3DB465278C2FAAA9AB95765E0 libstlport.so
08-26 15:00:17.368  6517  6320 W google-breakpad: M B6CDA000 00000000 0006C000 B2EFA1538A963AE403143D427627808B0 libGLES_trace.so
08-26 15:00:17.370  6517  6320 W google-breakpad: M B6D46000 00000000 00068000 93C54B2B4728113204066F4718CD48FE0 libEGL.so
08-26 15:00:17.371  6517  6320 W google-breakpad: M B6DB1000 00000000 000DE000 ED75B1C7941402A7B8C23AD0A51F1ECD0 libandroid_runtime.so
08-26 15:00:17.372  6517  6320 W google-breakpad: M B6E90000 00000000 0000D000 9CE14A143CF7D3AB3E49F82BB9BA4BAC0 libcutils.so
08-26 15:00:17.372  6517  6320 W google-breakpad: M B6E9D000 00000000 00004000 D1AC53E65CCF0819F62D0CBCB34992B60 libNimsWrap.so
08-26 15:00:17.372  6517  6320 W google-breakpad: M B6EA1000 00000000 00004000 DFD777ACF34CBD2037A5FC4C5DDFC1430 libstdc++.so
08-26 15:00:17.372  6517  6320 W google-breakpad: M B6EA5000 00000000 00018000 112087314C147BE2E520A4B6ABA86D970 libm.so
08-26 15:00:17.372  6517  6320 W google-breakpad: M B6EBE000 00000000 00007000 58CFB8EDDD133B5B179573415F8D2C080 liblog.so
08-26 15:00:17.372  6517  6320 W google-breakpad: M B6EC6000 00000000 0006A000 C01B6C02267EEB8261400EB2F8060FBA0 libc.so
08-26 15:00:17.372  6517  6320 W google-breakpad: M B6F3A000 00000000 00003000 D773C773634B82249E887ECBC5D28C900 libsigchain.so
08-26 15:00:17.372  6517  6320 W google-breakpad: M B6F42000 00000000 0000F000 F2B3647A0516D97165DA767190ECCC3C0 linker
08-26 15:00:17.372  6517  6320 W google-breakpad: -----END BREAKPAD MICRODUMP-----
08-26 15:00:17.391  6238  6320 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-26 15:00:17.391  6238  6320 W google-breakpad: Chrome build fingerprint:
08-26 15:00:17.391  6238  6320 W google-breakpad: 0.0.1
08-26 15:00:17.391  6238  6320 W google-breakpad: 19
08-26 15:00:17.392  6238  6320 W google-breakpad: 873fd9bc-5759-4679-9dc5-2d671bd0c1b7
08-26 15:00:17.392  6238  6320 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-26 15:00:17.392  6238  6320 E chromium: ### WebView Version 44.0.2403.90 (code 240309000)
,--------- beginning of crash
08-26 15:00:17.392  6238  6320 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x4 in tid 6320 (Thread-755)
08-26 15:00:17.533   283   283 I DEBUG   : [2016-08-26 15:00:17.531]
,08-26 15:00:17.534   283   283 I DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
08-26 15:00:17.534   283   283 I DEBUG   : Build fingerprint: 'lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys'
08-26 15:00:17.534   283   283 I DEBUG   : Revision: '6'
08-26 15:00:17.534   283   283 I DEBUG   : ABI: 'arm'
08-26 15:00:17.535   283   283 I DEBUG   : pid: 6238, tid: 6320, name: Thread-755  >>> com.test.thalitest <<<
08-26 15:00:17.535   283   283 I DEBUG   : signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4
08-26 15:00:17.556   834  1351 W NativeCrashListener: Couldn't find ProcessRecord for pid 1530015793
,08-26 15:00:17.571   283   283 I DEBUG   :     r0 b0581000  r1 00000000  r2 9a368064  r3 9a3680e0
,08-26 15:00:17.571   283   283 E DEBUG   : AM write failure (32 / Broken pipe)
08-26 15:00:17.572   283   283 I DEBUG   :     r4 9a368038  r5 9a36808c  r6 b046ede0  r7 9a368064
08-26 15:00:17.572   283   283 I DEBUG   :     r8 95d64260  r9 ffffff85  sl b04c6c80  fp 9a36805c
08-26 15:00:17.572   283   283 I DEBUG   :     ip 9a368020  sp 9a368028  lr 98252978  pc 9825297c  cpsr 200f0010
08-26 15:00:17.572   283   283 I DEBUG   : 
08-26 15:00:17.572   283   283 I DEBUG   : backtrace:
08-26 15:00:17.572   283   283 I DEBUG   :     #00 pc 0054797c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_SetPropertyById(JSContext*, JS::Handle<JSObject*>, JS::Handle<jsid>, JS::Handle<JS::Value>)+44)
08-26 15:00:17.572   283   283 I DEBUG   :     #01 pc 00547e1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_SetProperty(JSContext*, JS::Handle<JSObject*>, char const*, JS::Handle<JS::Value>)+132)
08-26 15:00:17.572   283   283 I DEBUG   :     #02 pc 00762754  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::SetProperty(char const*, JS::Handle<JS::Value>)+88)
08-26 15:00:18.547   283   283 I DEBUG   : 
08-26 15:00:18.547   283   283 I DEBUG   : Tombstone written to: /data/tombstones/tombstone_04
,08-26 15:00:18.557   834  1030 I BootReceiver: Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
08-26 15:00:18.587  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:18.588  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:18.588  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-26 15:00:18.633   834  1908 I WindowState: WIN DEATH: Window{1dcb8773 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 15:00:18.647   834  1908 D InputDispatcher: Focus left window: Window{1dcb8773 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 15:00:18.648   834  1908 D InputDispatcher: Window went away: Window{1dcb8773 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 15:00:18.816   309   309 I Zygote  : Process 6238 exited due to signal (11)
,08-26 15:00:18.844   834  1886 I ActivityManager: Process com.test.thalitest (pid 6238) has died
,08-26 15:00:18.848   834  1886 W ActivityManager: Force removing ActivityRecord{28e12b91 u0 com.test.thalitest/.MainActivity t259}: app died, no saved state
,08-26 15:00:18.906  1880  1880 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-26 15:00:18.935  3366  6519 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-26 15:00:18.968  1880  1880 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-26 15:00:18.989  1880  1880 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-26 15:00:18.991  1880  1880 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-26 15:00:18.991  1880  1880 I Activity: Activity.onPostResume() called 
08-26 15:00:19.000  2810  2810 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:0:19
,08-26 15:00:19.004  2810  2810 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 15:00:19.007  1880  6520 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-26 15:00:19.007  2810  2810 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
08-26 15:00:19.007  2810  2810 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
08-26 15:00:19.007  2810  2810 D WeatherAncestor: 2 : shouldTimeTickRegistered().........
08-26 15:00:19.012  2810  2810 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:0:19
,08-26 15:00:19.014  2810  2810 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,08-26 15:00:19.015   834  1832 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
08-26 15:00:19.015  2810  2810 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
08-26 15:00:19.016  2810  2810 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
08-26 15:00:19.016  2810  2810 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
08-26 15:00:19.016  2810  2810 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
08-26 15:00:19.016  2810  2810 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
08-26 15:00:19.018   834  1033 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-26 15:00:19.018  2810  2810 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 15:00:19.018  2810  2810 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
08-26 15:00:19.018  2810  2810 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
08-26 15:00:19.018  1371  1371 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-26 15:00:19.019  1371  1371 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-26 15:00:19.019  1371  1371 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-26 15:00:19.019  1371  1371 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-26 15:00:19.019  2810  2810 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
08-26 15:00:19.019  2810  2810 D WeatherTheme: 2 : Fixed theme : optimus
08-26 15:00:19.020   834  1033 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-26 15:00:19.021   834  1033 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-26 15:00:19.021   834  1033 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-26 15:00:19.023   834  1033 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 15:00:19.024   834  1033 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1de71418,  pkg=WindowManager.LayoutParams
08-26 15:00:19.024  2810  2810 D WeatherReflect: 2 : Map key string is -2
08-26 15:00:19.024   834  1033 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-26 15:00:19.026  2810  2810 D lim     : 2 : time = 15:00
08-26 15:00:19.026  2810  2810 I WeatherReflect: Model Name : LG-D722
08-26 15:00:19.026   834  1903 D InputDispatcher: Focus entered window: Window{c7728be u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-26 15:00:19.026  2810  2810 D WeatherTheme: 2 : exactly same view!
08-26 15:00:19.026  2810  2810 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
,08-26 15:00:19.030   834   852 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
08-26 15:00:19.031  2810  2810 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
08-26 15:00:19.031  2810  2810 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
08-26 15:00:19.031  2810  2810 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
08-26 15:00:19.047  1880  1880 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,08-26 15:00:19.048  1880  1880 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-26 15:00:19.051   834  2133 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-26 15:00:19.054   834  2133 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6238 uid 10030
08-26 15:00:19.153  1880  1880 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@23f68838 time:146756
,08-26 15:00:19.158  1948  6527 I HotwordRecognitionRnr: Starting hotword detection.
,08-26 15:00:19.161  1948  6528 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@604e671
08-26 15:00:19.166  1948  6528 V AudioRecord: set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
08-26 15:00:19.166  1948  6528 V AudioRecord: set(): mSessionId 23
,08-26 15:00:19.183   287  1609 V AudioPolicyManager: getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
08-26 15:00:19.183   287  1609 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
08-26 15:00:19.183   287  1609 V AudioPolicyManager: isPlaybackThread 0,isRecordThread 1
08-26 15:00:19.183   287  1609 D audio_hw_primary: adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb4036520)
08-26 15:00:19.183   287  1609 V audio_hw_primary: adev_open_input_stream: exit
08-26 15:00:19.183   287  1609 V AudioFlinger: openInput_l() openInputStream returned input 0xb4036520, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
,08-26 15:00:19.185   287  1609 V AudioFlinger: openInput_l() created record thread: ID 24 thread 0xb4393000
,08-26 15:00:19.185   287  1609 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-26 15:00:19.186  1371  1405 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-26 15:00:19.186   287  1609 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-26 15:00:19.186  1754  1770 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-26 15:00:19.186   834  1635 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-26 15:00:19.186  1948  1974 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-26 15:00:19.187  2020  2057 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-26 15:00:19.187  2831  2851 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-26 15:00:19.187   287  1609 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-26 15:00:19.187  3178  3390 V AudioSystem: ioConfigChanged() event 3, ioHandle 24
08-26 15:00:19.188   287  1062 V AudioPolicyService: AudioCommandThread() waking up
08-26 15:00:19.188   287  1062 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-26 15:00:19.188   287  6535 I AudioFlinger: AudioFlinger's thread 0xb4393000 ready to run
08-26 15:00:19.188   287  6535 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
08-26 15:00:19.188   287  6535 V audio_hw_primary: in_standby: exit:  status(0)
08-26 15:00:19.189   287  6535 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
08-26 15:00:19.189   287  6535 V audio_hw_primary: in_standby: exit:  status(0)
08-26 15:00:19.189   287  6535 V AudioFlinger: RecordThread: loop stopping
08-26 15:00:19.190   287  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 15:00:19.191   287  1353 V AudioFlinger: openRecord() lSessionId: 23 input 24
08-26 15:00:19.192   287  1353 V AudioFlinger: getOrphanEffectChain_l session 23 index -2
08-26 15:00:19.192   287  1609 V AudioFlinger: acquiring 23 from 1948, for -1
08-26 15:00:19.192   287  1609 V AudioFlinger:  added new entry for 23
08-26 15:00:19.195  1948  6528 V AudioRecord: start, sync event 0 trigger session 0
08-26 15:00:19.195  1948  6528 V AudioRecord: mAudioRecord->start()
08-26 15:00:19.195   287  1353 V AudioFlinger: RecordHandle::start()
08-26 15:00:19.195   287  1353 V AudioFlinger: RecordThread::start event 0, triggerSession 0
08-26 15:00:19.195   287  1353 V AudioPolicyManager: startInput() module primary->input primary(24)
08-26 15:00:19.195   287  1353 V AudioPolicyManager: getDeviceForInputSource()input source 1999, device 80000004
08-26 15:00:19.195   287  1353 V AudioPolicyManager: getNewInputDevice() selected device 80000004
08-26 15:00:19.195   287  1353 V AudioPolicyManager: DeviceVector::refreshTypes() mDeviceTypes 80000004
08-26 15:00:19.195   287  1353 V AudioPolicyManager: DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
08-26 15:00:19.195   287  1353 V AudioPolicyService: AudioCommandThread() adding create patch delay 0
08-26 15:00:19.196   287  1353 V AudioPolicyService: inserting command: 7 at index 0, num commands 0
08-26 15:00:19.196   287  1061 V AudioPolicyService: AudioCommandThread() waking up
08-26 15:00:19.196   287  1061 V AudioPolicyService: AudioCommandThread() processing create audio patch
,08-26 15:00:19.196   287  1061 V AudioFlinger::PatchPanel: createAudioPatch() num_sources 1 num_sinks 1 handle 0
08-26 15:00:19.196   287  1061 V AudioFlinger::PatchPanel: createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
08-26 15:00:19.196   287  1061 V AudioFlinger: ThreadBase::setParameters() input_source=6;routing=-2147483644
08-26 15:00:19.196   287  1061 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-26 15:00:19.196   287  6535 V AudioFlinger: RecordThread: loop starting
08-26 15:00:19.196   287  6535 V AudioFlinger: processConfigEvents_l() remaining events 1
08-26 15:00:19.196   287  6535 D audio_hw_primary: in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
08-26 15:00:19.196   287  6535 V audio_hw_primary: in_set_parameters: exit: status(0)
08-26 15:00:19.196   287  6535 V AudioFlinger: processConfigEvents_l() DONE thread 0xb4393000
08-26 15:00:19.197   287  1061 V AudioFlinger::PatchPanel: createAudioPatch() status 0
08-26 15:00:19.197   287  1061 V AudioFlinger::PatchPanel: createAudioPatch() added new patch handle 25 halHandle 0
08-26 15:00:19.197   287  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 15:00:19.197   287  1353 V AudioPolicyManager: setInputDevice() createAudioPatch returned 0 patchHandle 25
08-26 15:00:19.197   287  1353 V AudioPolicyManager: addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
08-26 15:00:19.197   287  1353 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-26 15:00:19.197   287  1353 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-26 15:00:19.197   287  1062 V AudioPolicyService: AudioCommandThread() waking up
08-26 15:00:19.197   287  1062 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-26 15:00:19.198   287  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 15:00:19.198   287  1353 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
08-26 15:00:19.198   287  1353 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-26 15:00:19.198   287  1061 V AudioPolicyService: AudioCommandThread() waking up
08-26 15:00:19.199   287  1061 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=1, io 24
08-26 15:00:19.199   287  1061 V AudioFlinger: setParameters(): io 24, keyvalue hotword_active=1, calling pid 287
08-26 15:00:19.199   287  1061 V AudioFlinger: ThreadBase::setParameters() hotword_active=1
08-26 15:00:19.199   287  1061 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-26 15:00:19.207   287  6535 V AudioFlinger: processConfigEvents_l() remaining events 1
08-26 15:00:19.207   287  6535 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=1
08-26 15:00:19.207   287  6535 V audio_hw_primary: in_set_parameters: exit: status(0)
08-26 15:00:19.207   287  6535 V AudioFlinger: processConfigEvents_l() DONE thread 0xb4393000
08-26 15:00:19.207   287  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 15:00:19.207   287  1353 V AudioPolicyManager: AudioPolicyManager::startInput() input source = 1999
08-26 15:00:19.217  1948  6528 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@604e671
,08-26 15:00:19.219   287  6535 V msm8974_platform: platform_update_usecase_from_source: input source :6
08-26 15:00:19.219   287  6535 D audio_hw_primary: start_input_stream: enter: stream(0xb4036520)usecase(7: audio-record)
08-26 15:00:19.219   287  6535 V voice   : voice_check_and_set_incall_rec_usecase: voice call not active
08-26 15:00:19.219   287  6535 V audio_hw_primary: start_input_stream: usecase(7)
08-26 15:00:19.219   287  6535 E audio_hw_primary: select_devices: enter and usecase(7)
08-26 15:00:19.219   287  6535 V msm8974_platform: platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
08-26 15:00:19.219   287  6535 V msm8974_platform: platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
08-26 15:00:19.219   287  6535 V msm8974_platform_lge: LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
08-26 15:00:19.219   287  6535 V audio_hw_lge_primary: LGE_exeption_scenario: enter and out: 0, in: 144
08-26 15:00:19.219   287  6535 D audio_hw_primary: select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
08-26 15:00:19.219   287  6535 E audio_hw_primary: enable_snd_device: enter  144
08-26 15:00:19.219   287  6535 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-26 15:00:19.219   287  6535 V audio_hw_primary: enable_snd_device: snd_device(144: lg-vr-handset-mic)
08-26 15:00:19.219   287  6535 V msm8974_platform_lge: LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
08-26 15:00:19.220   287  6535 D ACDB-LOADER: ACDB -> send_audio_cal, acdb_id = 65, path =  1
08-26 15:00:19.220   287  6535 D ACDB-LOADER: ACDB -> send_adm_topology
08-26 15:00:19.220   287  6535 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
08-26 15:00:19.221   287  6535 D ACDB-LOADER: ACDB -> send_asm_topology
08-26 15:00:19.221   287  6535 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
08-26 15:00:19.221   287  6535 D ACDB-LOADER: ACDB -> send_audtable
08-26 15:00:19.221   287  6535 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
08-26 15:00:19.221   287  6535 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_CAL
08-26 15:00:19.221   287  6535 D ACDB-LOADER: ACDB -> send_audvoltable
08-26 15:00:19.221   287  6535 D ACDB-LOADER: ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
08-26 15:00:19.221   287  6535 D         : Failed to fetch the lookup information of the device 00000041 
08-26 15:00:19.221   287  6535 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
08-26 15:00:19.221   287  6535 D ACDB-LOADER: ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
08-26 15:00:19.222   287  6535 D ACDB-LOADER: ACDB -> AUDIO_SET_AFE_CAL
08-26 15:00:19.228   287  6535 V audio_hw_primary: enable_audio_route: enter: usecase(7)
08-26 15:00:19.228   287  6535 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-26 15:00:19.228   287  6535 V audio_hw_primary: enable_audio_route: apply mixer and update path: audio-record
08-26 15:00:19.229   287  6535 V audio_hw_primary: enable_audio_route: exit
08-26 15:00:19.229   287  6535 D audio_hw_primary: select_devices: done
08-26 15:00:19.229   287  6535 V audio_hw_primary: start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,08-26 15:00:19.233   287  6535 V audio_hw_primary: start_input_stream: exit
08-26 15:00:19.337  1948  1948 I HotwordWorker: onReady
,08-26 15:00:19.404   834  1035 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{261bdfd1 u0 com.lge.launcher2/.Launcher t258} time:147006
,08-26 15:00:19.590  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:19.590  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:19.590  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-26 15:00:20.110   834  1043 I PowerManagerService: ALS enabled for SRE
08-26 15:00:20.111   834  1043 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27713 ms ago)
,08-26 15:00:20.140   834  1348 D qdlights: set_light_backlight: 254
,08-26 15:00:20.153   834  1348 D qdlights: set_light_backlight: 250
,08-26 15:00:20.170   834  1348 D qdlights: set_light_backlight: 247
,08-26 15:00:20.186   834  1348 D qdlights: set_light_backlight: 244
,08-26 15:00:20.203   834  1348 D qdlights: set_light_backlight: 240
,08-26 15:00:20.220   834  1348 D qdlights: set_light_backlight: 237
,08-26 15:00:20.236   834  1348 D qdlights: set_light_backlight: 234
,08-26 15:00:20.253   834  1348 D qdlights: set_light_backlight: 230
,08-26 15:00:20.270   834  1348 D qdlights: set_light_backlight: 227
,08-26 15:00:20.286   834  1348 D qdlights: set_light_backlight: 224
,08-26 15:00:20.303   834  1348 D qdlights: set_light_backlight: 220
,08-26 15:00:20.320   834  1348 D qdlights: set_light_backlight: 217
,08-26 15:00:20.336   834  1348 D qdlights: set_light_backlight: 214
,08-26 15:00:20.353   834  1348 D qdlights: set_light_backlight: 210
08-26 15:00:20.370   834  1348 D qdlights: set_light_backlight: 207
,08-26 15:00:20.386   834  1348 D qdlights: set_light_backlight: 204
,08-26 15:00:20.403   834  1348 D qdlights: set_light_backlight: 200
,08-26 15:00:20.420   834  1348 D qdlights: set_light_backlight: 197
,08-26 15:00:20.436   834  1348 D qdlights: set_light_backlight: 194
,08-26 15:00:20.453   834  1348 D qdlights: set_light_backlight: 190
,08-26 15:00:20.470   834  1348 D qdlights: set_light_backlight: 187
,08-26 15:00:20.486   834  1348 D qdlights: set_light_backlight: 184
,08-26 15:00:20.503   834  1348 D qdlights: set_light_backlight: 180
,08-26 15:00:20.520   834  1348 D qdlights: set_light_backlight: 177
,08-26 15:00:20.536   834  1348 D qdlights: set_light_backlight: 174
,08-26 15:00:20.553   834  1348 D qdlights: set_light_backlight: 170
,08-26 15:00:20.570   834  1348 D qdlights: set_light_backlight: 167
,08-26 15:00:20.586   834  1348 D qdlights: set_light_backlight: 164
,08-26 15:00:20.603   834  1348 D qdlights: set_light_backlight: 160
,08-26 15:00:20.620   834  1348 D qdlights: set_light_backlight: 157
,08-26 15:00:20.636   834  1348 D qdlights: set_light_backlight: 154
,08-26 15:00:20.653   834  1348 D qdlights: set_light_backlight: 150
,08-26 15:00:20.670   834  1348 D qdlights: set_light_backlight: 147
,08-26 15:00:20.686   834  1348 D qdlights: set_light_backlight: 144
,08-26 15:00:20.703   834  1348 D qdlights: set_light_backlight: 140
,08-26 15:00:20.720   834  1348 D qdlights: set_light_backlight: 137
,08-26 15:00:20.736   834  1348 D qdlights: set_light_backlight: 134
,08-26 15:00:20.753   834  1348 D qdlights: set_light_backlight: 130
,08-26 15:00:20.770   834  1348 D qdlights: set_light_backlight: 127
,08-26 15:00:20.786   834  1348 D qdlights: set_light_backlight: 124
,08-26 15:00:20.803   834  1348 D qdlights: set_light_backlight: 120
,08-26 15:00:20.820   834  1348 D qdlights: set_light_backlight: 117
,08-26 15:00:20.836   834  1348 D qdlights: set_light_backlight: 114
,08-26 15:00:20.853   834  1348 D qdlights: set_light_backlight: 110
,08-26 15:00:20.870   834  1348 D qdlights: set_light_backlight: 107
,08-26 15:00:20.886   834  1348 D qdlights: set_light_backlight: 104
,08-26 15:00:20.903   834  1348 D qdlights: set_light_backlight: 100
,08-26 15:00:20.920   834  1348 D qdlights: set_light_backlight: 97
,08-26 15:00:20.936   834  1348 D qdlights: set_light_backlight: 94
,08-26 15:00:20.953   834  1348 D qdlights: set_light_backlight: 90
,08-26 15:00:20.970   834  1348 D qdlights: set_light_backlight: 87
,08-26 15:00:20.987   834  1348 D qdlights: set_light_backlight: 84
,08-26 15:00:20.991  1880  2183 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 15:00:20.991  1880  2183 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-26 15:00:20.993  1880  2183 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-26 15:00:20.997  1880  2183 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-26 15:00:20.997  1880  2183 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-26 15:00:20.998  1880  2183 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
08-26 15:00:20.998  1880  2183 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-26 15:00:21.004   834  1348 D qdlights: set_light_backlight: 80
,08-26 15:00:21.008  1880  2286 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
08-26 15:00:21.008  1880  2286 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
08-26 15:00:21.020   834  1348 D qdlights: set_light_backlight: 77
,08-26 15:00:21.035   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-26 15:00:21.038   834  1348 D qdlights: set_light_backlight: 74
08-26 15:00:21.056   834  1348 D qdlights: set_light_backlight: 70
,08-26 15:00:21.070   834  1348 D qdlights: set_light_backlight: 67
,08-26 15:00:21.086   834  1348 D qdlights: set_light_backlight: 64
,08-26 15:00:21.103   834  1348 D qdlights: set_light_backlight: 60
,08-26 15:00:21.120   834  1348 D qdlights: set_light_backlight: 57
,08-26 15:00:21.136   834  1348 D qdlights: set_light_backlight: 54
,08-26 15:00:21.153   834  1348 D qdlights: set_light_backlight: 50
,08-26 15:00:21.170   834  1348 D qdlights: set_light_backlight: 47
,08-26 15:00:21.186   834  1348 D qdlights: set_light_backlight: 44
,08-26 15:00:21.203   834  1348 D qdlights: set_light_backlight: 40
,08-26 15:00:21.220   834  1348 D qdlights: set_light_backlight: 37
,08-26 15:00:21.236   834  1348 D qdlights: set_light_backlight: 34
,08-26 15:00:21.253   834  1348 D qdlights: set_light_backlight: 30
,08-26 15:00:21.270   834  1348 D qdlights: set_light_backlight: 27
,08-26 15:00:21.286   834  1348 D qdlights: set_light_backlight: 24
,08-26 15:00:21.303   834  1348 D qdlights: set_light_backlight: 20
,08-26 15:00:21.320   834  1348 D qdlights: set_light_backlight: 17
,08-26 15:00:21.336   834  1348 D qdlights: set_light_backlight: 14
,08-26 15:00:21.354   834  1348 D qdlights: set_light_backlight: 10
,08-26 15:00:21.597  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:21.597  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-26 15:00:21.600  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-26 15:00:22.599  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:22.599  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:22.599  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-26 15:00:24.603  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:24.603  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:24.603  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-26 15:00:25.605  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:25.605  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:25.605  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-26 15:00:26.040   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-26 15:00:26.840   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:00:26.840   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:00:26.840   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 154442869163; DSPS: 5152686; Offset : -2814291127
,08-26 15:00:27.108   834  1043 I PowerManagerService: ALS enabled for SRE
08-26 15:00:27.109   834  1043 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34711 ms ago)
08-26 15:00:27.109   834  1043 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 15:00:27.119   834  1043 I PowerManagerService: ALS enabled for SRE
08-26 15:00:27.119   834  1043 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34722 ms ago)
08-26 15:00:27.128   834  1043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,08-26 15:00:27.135   834  1043 I PowerManagerService: Sleeping (uid 1000)...
08-26 15:00:27.135   834  1043 D LPWGController: [updateScreenState] screen on = false
08-26 15:00:27.144   834  1043 D LPWGController: disable proximity sensor
,08-26 15:00:27.146   834  1043 D LPWGController: enable proximity sensor
08-26 15:00:27.162   834  1043 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2155318b] by com.android.server.power.ProximitySensorListener.enable():120
,08-26 15:00:27.171   834  1043 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
08-26 15:00:27.171   834  1043 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
08-26 15:00:27.171   834  1043 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
08-26 15:00:27.171   834  1043 I sensors_hal_Ctx: activate: handle is 48, enable
08-26 15:00:27.171   834  1043 V sensors_hal_Ctx: activate sensors is 1400000000000
08-26 15:00:27.171   834  1043 D sensors_hal_Thresh: enable: handle=48
08-26 15:00:27.171   834  1043 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
08-26 15:00:27.172   834  1043 D sensors_hal_Util: waitForResponse: timeout=1000
08-26 15:00:27.178   834   987 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
08-26 15:00:27.178   834   987 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
,08-26 15:00:27.180   834  1043 D sensors_hal_Thresh: enable: Received response: 0
08-26 15:00:27.181   834  1043 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34783 ms ago)
08-26 15:00:27.224   834  1043 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 15:00:27.224   834  1043 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 15:00:27.224   834  1043 I Adreno-EGL: Build Date: 03/02/15 Mon
08-26 15:00:27.224   834  1043 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-26 15:00:27.224   834  1043 I Adreno-EGL: Remote Branch: 
08-26 15:00:27.224   834  1043 I Adreno-EGL: Local Patches: 
08-26 15:00:27.224   834  1043 I Adreno-EGL: Reconstruct Branch: 
,08-26 15:00:27.251   247  1349 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (140 us)
,08-26 15:00:27.405   427   976 I Sensors : sns_pwr.c(273):acquiring wakelock
,08-26 15:00:27.407   834   987 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,08-26 15:00:27.408   834   987 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
08-26 15:00:27.408   834   987 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
08-26 15:00:27.408   834   987 D sensors_hal_Thresh: processInd: handle 48, count=1
08-26 15:00:27.408   834   987 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
08-26 15:00:27.408   834   987 I sensors_hal_Thresh: processInd : proximity state changed - FAR
08-26 15:00:27.409   834  1023 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
08-26 15:00:27.409   834  1023 D sensors_hal_Ctx: poll: count: 256
08-26 15:00:27.409   834  1023 I sensors_hal_Ctx: poll: released wakelock sensor_ind
08-26 15:00:27.409   834  1023 D sensors_hal_Util: waitForResponse: timeout=0
08-26 15:00:27.411   834  1043 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
08-26 15:00:27.411   834  1043 I LPWGController: current mode = 1  value = 1 1
08-26 15:00:27.412   834  1043 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
08-26 15:00:27.514   834  1043 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,08-26 15:00:27.608  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-26 15:00:27.608  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:27.609  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-26 15:00:27.772   834  1348 D qdlights: set_light_backlight: 0
,08-26 15:00:27.779   834  1043 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
08-26 15:00:27.780   834  1043 I sensors_hal_Ctx: activate: handle is 46, disable
08-26 15:00:27.780   834  1043 V sensors_hal_Ctx: activate sensors is 1000000000000
08-26 15:00:27.780   834  1043 D sensors_hal_LP2: enable: handle=46
08-26 15:00:27.780   834  1043 D sensors_hal_LP2: enable: Disabling sensor handle=46
08-26 15:00:27.780   834  1043 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
08-26 15:00:27.782   247   247 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
08-26 15:00:27.782   247   247 D qdhwcomposer: hwc_blank: Blanking display: 0
08-26 15:00:27.787   834  1035 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
08-26 15:00:27.787   834   834 V ActivityManager: Display changed displayId=0
,08-26 15:00:27.813   834  1013 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
08-26 15:00:27.813   834  1013 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,08-26 15:00:27.835  1754  1754 D DSDPConnection: Display #0 changed.
08-26 15:00:27.956   247   247 D qdhwcomposer: hwc_blank: Done blanking display: 0
08-26 15:00:27.956   834  1348 D SurfaceControl: Excessive delay in setPowerMode(): 174ms
08-26 15:00:27.957   247   692 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 15:00:27.959   834  1348 I QCOM PowerHAL: Got set_interactive hint
,08-26 15:00:27.973  1880  1880 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-26 15:00:27.974  1371  1918 D KeyguardViewMediator: onScreenTurnedOff(3)
08-26 15:00:27.983  1331  1347 D SmartCoverViewMediator: onScreenTurnedOff(3)
,08-26 15:00:27.989  1371  1918 D KeyguardViewMediator: notifyScreenOffLocked
08-26 15:00:27.997  1331  1347 D SmartCoverViewMediator: notifyScreenOffLocked
,08-26 15:00:28.000  1331  1331 D SmartCoverViewMediator: handleNotifyScreenOFF
,08-26 15:00:28.030  1880  1880 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-26 15:00:28.031  1371  1918 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
08-26 15:00:28.031  1371  1371 D KeyguardViewMediator: handleNotifyScreenOff
08-26 15:00:28.038  1948  1948 I HotwordDetector: Closing mic
,08-26 15:00:28.042  1948  2402 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@604e671
,08-26 15:00:28.042  1948  2402 V AudioRecord: stop()
08-26 15:00:28.042  1948  2402 D AudioRecord: AudioRecord->stop()
08-26 15:00:28.042   287  1353 V AudioFlinger: RecordHandle::stop()
08-26 15:00:28.042   287  1353 V AudioFlinger: RecordThread::stop
08-26 15:00:28.055   287  1353 V AudioFlinger: Record stopped OK
08-26 15:00:28.055   287  1353 V AudioPolicyManager: stopInput() input 24
,08-26 15:00:28.057   287  1353 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-26 15:00:28.057   287  1353 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-26 15:00:28.057   287  1061 V AudioPolicyService: AudioCommandThread() waking up
08-26 15:00:28.057   287  1061 V AudioPolicyService: AudioCommandThread() processing release audio patch
,08-26 15:00:28.057   287  1061 V AudioFlinger::PatchPanel: releaseAudioPatch handle 25
08-26 15:00:28.058   287  1061 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-26 15:00:28.058   287  1061 V AudioFlinger: ThreadBase::setParameters() routing=0
08-26 15:00:28.058   287  1061 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-26 15:00:28.058   287  6535 V AudioFlinger: processConfigEvents_l() remaining events 1
08-26 15:00:28.059   287  6535 V AudioFlinger: processConfigEvents_l() DONE thread 0xb4393000
08-26 15:00:28.059   287  6535 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
08-26 15:00:28.062  1371  1371 D ScreenTurnOffBySensor: unregisterProximitySensor
08-26 15:00:28.080  1371  1371 D StatusBarWindowView: onScreenTurnedOff why = 3
08-26 15:00:28.082   834   834 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
,08-26 15:00:28.085   287   287 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 834
08-26 15:00:28.093  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-26 15:00:28.094  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-26 15:00:28.094  1371  1371 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-26 15:00:28.106   834  1310 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
,08-26 15:00:28.113   287  6535 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-26 15:00:28.113   287  6535 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-26 15:00:28.113   287  6535 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-26 15:00:28.113   287  6535 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 15:00:28.115   287  6535 V audio_hw_primary: disable_audio_route: exit
08-26 15:00:28.115   287  6535 E audio_hw_primary: disable_snd_device: enter 144
08-26 15:00:28.115   287  6535 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-26 15:00:28.115   287  6535 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-26 15:00:28.126   287  6535 V audio_hw_primary: stop_input_stream: exit: status(0)
08-26 15:00:28.126   287  6535 V audio_hw_primary: in_standby: exit:  status(0)
08-26 15:00:28.127   287  6535 V AudioFlinger: RecordThread: loop stopping
08-26 15:00:28.127   287  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 15:00:28.127   287   287 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-26 15:00:28.127   287   287 V voice   : voice_set_parameters: enter: screen_state=on
08-26 15:00:28.127   287   287 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
08-26 15:00:28.127   287   287 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 15:00:28.127   287   287 V voice   : voice_set_parameters: exit with code(0)
08-26 15:00:28.127   287   287 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
08-26 15:00:28.127   287   287 V msm8974_platform: platform_set_parameters: enter: screen_state=on
08-26 15:00:28.127   287   287 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 15:00:28.128   287  1353 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-26 15:00:28.128   287  1353 V AudioPolicyManager: removeAudioPatch() handle 20 af handle 25
08-26 15:00:28.128   287  1353 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-26 15:00:28.128   287  1353 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-26 15:00:28.128   287  1353 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 24 ,delay 0
08-26 15:00:28.128   287  1353 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-26 15:00:28.128   287  1062 V AudioPolicyService: AudioCommandThread() waking up
08-26 15:00:28.128   287  1062 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-26 15:00:28.128   287   287 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 15:00:28.128   287  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 15:00:28.128   287   287 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
08-26 15:00:28.128   287   287 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-26 15:00:28.128   287   287 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 15:00:28.129   287  1061 V AudioPolicyService: AudioCommandThread() waking up
08-26 15:00:28.129   287  1061 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 24
08-26 15:00:28.129   287  1061 V AudioFlinger: setParameters(): io 24, keyvalue hotword_active=0, calling pid 287
,08-26 15:00:28.133   287  1061 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-26 15:00:28.133   287  1061 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-26 15:00:28.133   287  6535 V AudioFlinger: RecordThread: loop starting
08-26 15:00:28.134   287  6535 V AudioFlinger: processConfigEvents_l() remaining events 1
08-26 15:00:28.134   287  6535 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
08-26 15:00:28.134   287  6535 V audio_hw_primary: in_set_parameters: exit: status(0)
08-26 15:00:28.135   287  6535 V AudioFlinger: processConfigEvents_l() DONE thread 0xb4393000
08-26 15:00:28.135   287  6535 V AudioFlinger: RecordThread: loop stopping
08-26 15:00:28.135   287  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 15:00:28.138  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:00:28.138  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
08-26 15:00:28.139  1948  2402 V AudioRecord: stop()
08-26 15:00:28.140  1948  2402 V AudioRecord: stop()
08-26 15:00:28.140  1948  2402 V AudioRecord: stop()
08-26 15:00:28.141   287  1301 V AudioFlinger: releasing 23 from 1948 for -1
08-26 15:00:28.141   287  1301 V AudioFlinger:  decremented refcount to 0
08-26 15:00:28.141   287  1301 V AudioFlinger: purging stale effects
08-26 15:00:28.141   287  1301 V AudioFlinger: RecordHandle::stop()
08-26 15:00:28.141   287  1301 V AudioFlinger: RecordThread::stop
08-26 15:00:28.141   287  1301 V AudioPolicyManager: releaseInput() 24
08-26 15:00:28.141   287  1301 V AudioPolicyManager: closeInput(24)
08-26 15:00:28.141   287  1301 V AudioFlinger: closeInput() 24
08-26 15:00:28.141   287  1301 V AudioSystem: ioConfigChanged() event 4, ioHandle 24
08-26 15:00:28.141   287  1301 V AudioFlinger: ThreadBase::exit
,08-26 15:00:28.143  2020  2073 V AudioSystem: ioConfigChanged() event 4, ioHandle 24
08-26 15:00:28.143  2831  2848 V AudioSystem: ioConfigChanged() event 4, ioHandle 24
08-26 15:00:28.143  3178  3193 V AudioSystem: ioConfigChanged() event 4, ioHandle 24
08-26 15:00:28.143  1948  1974 V AudioSystem: ioConfigChanged() event 4, ioHandle 24
08-26 15:00:28.144  1948  2408 I HotwordRecognitionRnr: Stopping hotword detection.
08-26 15:00:28.145   287  6535 V AudioFlinger: RecordThread: loop starting
,08-26 15:00:28.145   834  1286 V AudioSystem: ioConfigChanged() event 4, ioHandle 24
08-26 15:00:28.145  1371  1918 V AudioSystem: ioConfigChanged() event 4, ioHandle 24
08-26 15:00:28.146  1754  1769 V AudioSystem: ioConfigChanged() event 4, ioHandle 24
08-26 15:00:28.146   287  6535 V AudioFlinger: RecordThread 0xb4393000 exiting
08-26 15:00:28.146   287  1301 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb4036520)
08-26 15:00:28.146   287  1301 D audio_hw_primary: in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
08-26 15:00:28.146   287  1301 V audio_hw_primary: in_standby: exit:  status(0)
08-26 15:00:28.146   287  1301 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-26 15:00:28.147   287  1301 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-26 15:00:28.147   287  1062 V AudioPolicyService: AudioCommandThread() waking up
08-26 15:00:28.147   287  1062 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-26 15:00:28.147   287  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 15:00:28.148   287  1301 V AudioPolicyManager: releaseInput() exit
08-26 15:00:28.148   287  1301 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-26 15:00:28.148   287  1301 V AudioFlinger: removeClient_l() pid 1948, calling pid 287
08-26 15:00:28.158  1948  6527 I HotwordRecognitionRnr: Hotword detection finished
,08-26 15:00:28.595   834   967 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,08-26 15:00:28.602  1842  1842 I QCNEJ   : |CORE| sendScreenState: state:true
08-26 15:00:28.614  1806  1973 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,08-26 15:00:28.620  1806  1973 D LEDService: stopPatternFlashing()
,08-26 15:00:28.621  1806  1973 D qdlights: set_light_notifications: 0,0,0,0,3
08-26 15:00:28.623  1806  1973 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-26 15:00:28.623  1806  1973 D qdlights: set_light_notifications: 0,0,0,0,3
08-26 15:00:28.624  1806  1973 I LEDService: updateLightsLocked : turn off led
08-26 15:00:28.624  1806  1973 D qdlights: set_light_notifications: 0,0,0,0,3
08-26 15:00:28.626  1806  1973 D LEDHandler: RESTART MSG
,08-26 15:00:28.667   834  1886 D SplitWindow: check instance of lgWin Window{39814326 u0 SearchPanel}
,08-26 15:00:28.678  1806  1806 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
08-26 15:00:28.679  1806  1806 D Cliptray Service: lockStatus = 0
,08-26 15:00:28.682  1789  1789 D LNfcService: action : android.intent.action.SCREEN_ON
08-26 15:00:28.692  1789  6588 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
08-26 15:00:28.693  1789  6588 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
08-26 15:00:28.693  1789  6588 D LNfcService: isRequireNfcCRouting() return true
08-26 15:00:28.693  1789  6588 D LNfcService: isHCERoutingtoHost() return : true
08-26 15:00:28.693  1789  6588 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-26 15:00:28.693  1789  6588 D NfcService: mEnableLPD: true
08-26 15:00:28.693  1789  6588 D NfcService: mEnableReader: false
08-26 15:00:28.693  1789  6588 D NfcService: mEnableHostRouting: true
08-26 15:00:28.693  1789  6588 D NfcService: newParams.techmask= mTechMask: default
08-26 15:00:28.693  1789  6588 D NfcService: mEnableLPD: true
08-26 15:00:28.693  1789  6588 D NfcService: mEnableReader: false
08-26 15:00:28.693  1789  6588 D NfcService: mEnableHostRouting: true
08-26 15:00:28.693  1789  6588 D NfcService: screenState= 3
08-26 15:00:28.693  1789  6588 D NfcService: Discovery configuration equal, not updating.
,08-26 15:00:28.700   834  1832 D InputDispatcher: Window went away: Window{27e3eb25 u0 SearchPanel}
08-26 15:00:28.705  1371  1371 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
08-26 15:00:28.723  1371  1371 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-26 15:00:28.746   834   834 D Ulp_jni : JNI:system_update. Event-0
,08-26 15:00:28.779  1754  1754 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
08-26 15:00:28.790   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:00:28.791   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:00:28.791   834   834 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
08-26 15:00:28.797  2810  2810 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:0:28
08-26 15:00:28.799  2810  2810 D WeatherService: 2 : ACTION screen on
08-26 15:00:28.801  2810  2810 D WeatherService: 2 : shouldTimeTickRegistered : false
08-26 15:00:28.804  2810  2810 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 15:00:28.804  2810  2810 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:0:28
,08-26 15:00:28.817  4193  4193 D AppCleanupService: android.intent.action.SCREEN_ON
,08-26 15:00:28.845   287  1609 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 834
08-26 15:00:28.845   287  1609 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-26 15:00:28.845   287  1609 V voice   : voice_set_parameters: enter: screen_state=off
08-26 15:00:28.845   287  1609 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
08-26 15:00:28.845   287  1609 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 15:00:28.845   287  1609 V voice   : voice_set_parameters: exit with code(0)
08-26 15:00:28.845   287  1609 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
08-26 15:00:28.846   287  1609 V msm8974_platform: platform_set_parameters: enter: screen_state=off
08-26 15:00:28.846   287  1609 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 15:00:28.846   287  1609 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 15:00:28.846   287  1609 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-26 15:00:28.846   287  1609 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 15:00:28.848   834  1315 D WifiController: CMD_SCREEN_OFF 
08-26 15:00:28.848   834  1315 D WifiController: shouldWifiStayAwake TRUE
08-26 15:00:28.857  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,08-26 15:00:28.906   427   441 I Sensors : sns_pwr.c(301):releasing wakelock
,08-26 15:00:29.041   834   967 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,08-26 15:00:29.054  1842  1842 I QCNEJ   : |CORE| sendScreenState: state:false
,08-26 15:00:29.056  1806  1973 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-26 15:00:29.056  1806  1973 D LEDService: stopPatternFlashing()
08-26 15:00:29.056  1806  1973 D qdlights: set_light_notifications: 0,0,0,0,3
08-26 15:00:29.059  1806  1806 D VolumeVibrator: clear
08-26 15:00:29.060  1806  1973 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-26 15:00:29.060  1806  1973 D qdlights: set_light_notifications: 0,0,0,0,3
08-26 15:00:29.061  1806  1973 I LEDService: updateLightsLocked : turn on led
08-26 15:00:29.062  1806  1973 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
08-26 15:00:29.062  1806  1973 E LEDService: Can't handle this request of patternId:0
08-26 15:00:29.062  1806  1973 D LEDHandler: RESTART MSG
08-26 15:00:29.066  1806  1806 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
08-26 15:00:29.067  1789  1789 D LNfcService: action : android.intent.action.SCREEN_OFF
,08-26 15:00:29.073  1789  2235 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
08-26 15:00:29.080  1880  1880 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,08-26 15:00:29.086   834  1363 W ActivityManager: getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
08-26 15:00:29.093  1754  1754 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,08-26 15:00:29.098   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:00:29.099   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:00:29.099   834   834 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
08-26 15:00:29.100  2810  2810 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:0:29
08-26 15:00:29.100  2810  2810 D WeatherService: 2 : ACTION screen off
08-26 15:00:29.101  2810  2810 D WeatherService: 2 : TimeTick Receiver Unregister
08-26 15:00:29.101  2810  2810 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:0:29
08-26 15:00:29.105  4193  4193 D AppCleanupService: android.intent.action.SCREEN_OFF
,08-26 15:00:29.113  4193  6591 D AppCleanupService: AppUsageStatsSaveTask
08-26 15:00:29.151  1789  2596 E NxpNfcJni: getReconnectState = 0x0
,08-26 15:00:29.156  1789  2235 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-26 15:00:29.156  1789  2235 D LCardEmulationManager: getDefaultRoute
08-26 15:00:29.156  1789  2235 D LNfcService: isRequireNfcCRouting() return true
08-26 15:00:29.157  1789  2235 D LNfcService: isHCERoutingtoHost() return : true
08-26 15:00:29.157  1789  2235 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-26 15:00:29.157  1789  2235 D NfcService: mEnableLPD: true
08-26 15:00:29.157  1789  2235 D NfcService: mEnableReader: false
08-26 15:00:29.157  1789  2235 D NfcService: mEnableHostRouting: true
08-26 15:00:29.157  1789  2235 D NfcService: newParams.techmask= mTechMask: 0
08-26 15:00:29.157  1789  2235 D NfcService: mEnableLPD: true
08-26 15:00:29.157  1789  2235 D NfcService: mEnableReader: false
08-26 15:00:29.157  1789  2235 D NfcService: mEnableHostRouting: true
08-26 15:00:29.157  1789  2235 D NfcService: screenState= 1
08-26 15:00:29.217  1789  2596 E NxpNfcJni: getReconnectState = 0x0
,08-26 15:00:31.044   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-26 15:00:33.003  1371  1371 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,08-26 15:00:33.008   834  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{33e35b67 type 2 when 160594 com.android.systemui} when 160594
,08-26 15:00:33.017  1754  1910 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-26 15:00:33.022  1754  1910 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-26 15:00:33.022  1754  1910 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-26 15:00:33.025  1754  1910 V TelecomServiceImpl: getCallState : 0
08-26 15:00:33.027  1754  1770 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
08-26 15:00:33.027  1754  1770 D PhoneUtils: getPhoneCount() sPhoneCount = 1
08-26 15:00:33.027  1754  1770 D PhoneUtils: getPhoneCount() sPhoneCount = 1
,08-26 15:00:33.031  1371  1371 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
08-26 15:00:33.031  1371  1371 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
08-26 15:00:36.050   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-26 15:00:41.057   300   355 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-26 15:00:41.842   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:00:41.842   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:00:41.842   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 169444944503; DSPS: 5644276; Offset : -2814352278
,08-26 15:00:46.063   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-26 15:00:47.751  3366  4372 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-26 15:00:51.069   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-26 15:00:56.075   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-26 15:00:59.120   834  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{36517d14 type 2 when 186706 com.google.android.gms} when 186706
,08-26 15:00:59.666  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:00:59.666  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:00:59.666  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:00:59.666  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-26 15:00:59.668   491   491 D charger_monitor: init target 500000
08-26 15:00:59.670  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-26 15:00:59.672   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:00:59.709  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:00:59.712  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:00:59.713  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:00:59.713  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:00:59.713  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:00:59.713  1806  1973 D LEDHandler: Battery Temp: 310, mChargingStatus=5, mChargingStop=false
08-26 15:00:59.714  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
08-26 15:00:59.714  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:00:59.714  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
08-26 15:00:59.715  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:00:59.718   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:00:59.718   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:00:59.718   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:01:00.049  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:01:00.049  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:01:00.049  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:01:00.052  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:01:00.052  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:01:00.053  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:01:00.054  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:01:01.081   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-26 15:01:01.844   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:01:01.844   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:01:01.844   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 189447030133; DSPS: 6299702; Offset : -2814280730
,08-26 15:01:06.087   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-26 15:01:11.094   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-26 15:01:16.100   300   355 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-26 15:01:16.388   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:01:16.388   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:01:16.388   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 203989924965; DSPS: 6776244; Offset : -2814293457
,08-26 15:01:20.103  1735  4445 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-26 15:01:21.106   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:01:26.112   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:01:31.118   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:01:31.390   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:01:31.390   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:01:31.390   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 218992265138; DSPS: 7267841; Offset : -2814303344
,08-26 15:01:34.624  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:01:34.624  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:01:34.624  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:01:34.624  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-26 15:01:34.626  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-26 15:01:34.640   491   491 D charger_monitor: init target 500000
,08-26 15:01:34.645   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:01:34.708  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:01:34.714  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:01:34.714  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:01:34.715  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:01:34.715  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:01:34.715  1806  1973 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
08-26 15:01:34.716  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
08-26 15:01:34.716  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:01:34.716  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
08-26 15:01:34.718  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:01:34.722   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:01:34.722   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:01:34.725   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:01:34.765  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:01:34.769  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 307
08-26 15:01:34.769  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:01:34.769  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 307
08-26 15:01:34.771  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:01:34.771  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:01:34.772  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:01:34.772  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:01:34.772  1806  1973 D LEDHandler: Battery Temp: 307, mChargingStatus=5, mChargingStop=false
08-26 15:01:34.782   834  1315 D WifiController: battery changed pluggedType: 2
,08-26 15:01:34.785   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:01:34.786   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:01:34.787  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:01:36.124   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:01:40.713   834  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=113159564, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
,08-26 15:01:40.716   834  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{25535680 type 2 when 206560 android} when 206560
08-26 15:01:40.750   834   834 D PowerManagerServiceEx: releaseWakeLockInternal: lock=113159564 [*alarm*], flags=0x0
,08-26 15:01:41.131   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:01:46.137   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:01:51.142   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:01:51.392   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:01:51.392   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:01:51.392   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 238994692080; DSPS: 7923291; Offset : -2814624756
,08-26 15:01:56.148   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:01:59.820  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,08-26 15:01:59.822  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:01:59.822  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:01:59.822  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:01:59.823  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-26 15:01:59.829   491   491 D charger_monitor: init target 500000
08-26 15:01:59.834   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-26 15:01:59.880  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 306
,08-26 15:01:59.883  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:01:59.884  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 306
08-26 15:01:59.886  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:01:59.886  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:01:59.888  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:01:59.888  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:01:59.888  1806  1973 D LEDHandler: Battery Temp: 306, mChargingStatus=5, mChargingStop=false
08-26 15:01:59.891  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:01:59.893  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:01:59.899   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:01:59.899   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:01:59.900   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:02:00.039  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:02:00.039  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:02:00.039  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:02:00.043  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:02:00.043  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:02:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:02:00.045  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:02:01.155   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:02:06.161   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:02:06.396   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:02:06.396   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:02:06.396   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 253999007320; DSPS: 8414941; Offset : -2814274979
,08-26 15:02:11.167   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:02:16.173   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:02:21.179   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:02:22.653   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:02:22.653   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:02:22.653   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 270255223754; DSPS: 8947625; Offset : -2814284208
,08-26 15:02:26.185   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:02:31.191   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:02:36.197   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:02:37.666   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:02:37.666   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:02:37.667   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 285269069496; DSPS: 9439599; Offset : -2814295218
,08-26 15:02:41.204   300   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-26 15:02:46.210   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:02:51.216   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:02:56.222   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:02:57.669   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:02:57.669   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:02:57.669   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 305271737823; DSPS: 10095047; Offset : -2814310641
,08-26 15:02:59.981  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:02:59.981  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:02:59.981  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:02:59.981  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-26 15:02:59.983  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-26 15:02:59.989   491   491 D charger_monitor: init target 500000
08-26 15:02:59.994   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-26 15:03:00.035  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:03:00.038  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:03:00.038  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:03:00.040  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:03:00.040  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:03:00.040  1806  1973 D LEDHandler: Battery Temp: 304, mChargingStatus=5, mChargingStop=false
08-26 15:03:00.041  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 304
08-26 15:03:00.041  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:03:00.041  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 304
08-26 15:03:00.042  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:03:00.042  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:03:00.042  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
08-26 15:03:00.047   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:03:00.047   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:03:00.050   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:03:00.051  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:03:00.051  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:03:00.052  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:03:00.054  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:03:00.054  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:03:01.229   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:03:06.235   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:03:11.241   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:03:16.247   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:03:17.671   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:03:17.671   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:03:17.672   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 325274112402; DSPS: 10750490; Offset : -2814468994
,08-26 15:03:21.253   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:03:26.260   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:03:31.266   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:03:35.448   834  3335 I LocationManagerService: remove 16b4b0d3
08-26 15:03:35.448   834  3335 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-26 15:03:35.448   834  3335 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 15:03:35.448   834  3335 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-26 15:03:35.449   834  3335 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-26 15:03:35.449   834  3335 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-26 15:03:36.272   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:03:40.176   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:03:40.176   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:03:40.176   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 347778655267; DSPS: 11487914; Offset : -2814322666
,08-26 15:03:41.278   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:03:46.284   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:03:51.290   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:03:56.296   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:00.081  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:04:00.081  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:04:00.081  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:04:00.084  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:04:00.084  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:04:00.085  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:04:00.086  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:04:00.160   491   491 D charger_monitor: init target 500000
,08-26 15:04:00.165   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:04:00.167  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-26 15:04:00.167  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:04:00.167  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:04:00.168  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:04:00.168  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:04:00.178   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:04:00.178   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:04:00.178   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 367780604643; DSPS: 12143337; Offset : -2814295872
,08-26 15:04:00.212  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:04:00.215  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:04:00.215  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:04:00.216  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:04:00.217  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:04:00.217  1806  1973 D LEDHandler: Battery Temp: 303, mChargingStatus=5, mChargingStop=false
08-26 15:04:00.221   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:04:00.221   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:04:00.222   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:04:00.222  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 303
08-26 15:04:00.222  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:04:00.222  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 303
08-26 15:04:00.224  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:04:01.302   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:06.308   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:11.315   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:16.321   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:19.003  5727  5796 I PlayCommon: [672] com.google.android.play.a.l.e(787): Preparing logs for uploading
08-26 15:04:19.004  5727  5796 I PlayCommon: [672] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:04:20.180   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:04:20.180   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:04:20.180   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 387783026299; DSPS: 12798776; Offset : -2814283047
,08-26 15:04:21.327   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:24.426  5727  6145 I PlayCommon: [690] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-26 15:04:24.427  5727  6145 I PlayCommon: [690] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:04:26.333   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:31.339   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:36.346   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:40.183   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:04:40.183   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:04:40.183   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 407785308949; DSPS: 13454211; Offset : -2814291273
,08-26 15:04:41.352   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:46.358   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:51.364   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:04:56.371   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:00.001   834  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=113159564, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
,08-26 15:05:00.029   834   834 D PowerManagerServiceEx: releaseWakeLockInternal: lock=113159564 [*alarm*], flags=0x0
,08-26 15:05:00.038  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:05:00.038  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:05:00.038  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
08-26 15:05:00.040  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:05:00.040  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:05:00.040  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:05:00.041  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:05:00.184   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:05:00.184   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:05:00.184   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 427786927976; DSPS: 14109625; Offset : -2814319412
,08-26 15:05:00.292  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:05:00.293  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:05:00.293  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:05:00.293  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-26 15:05:00.295  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-26 15:05:00.296   491   491 D charger_monitor: init target 500000
08-26 15:05:00.305   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-26 15:05:00.334  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
,08-26 15:05:00.334  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:05:00.335  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 302
08-26 15:05:00.335  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:05:00.335  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,08-26 15:05:00.335  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:05:00.335  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:05:00.335  1806  1973 D LEDHandler: Battery Temp: 302, mChargingStatus=5, mChargingStop=false
08-26 15:05:00.339  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:05:00.339   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:05:00.339   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:05:00.339   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:05:00.340  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:05:01.001   834  2133 I art     : Explicit concurrent mark sweep GC freed 44604(2MB) AllocSpace objects, 15(961KB) LOS objects, 33% free, 23MB/35MB, paused 3.465ms total 216.088ms
,08-26 15:05:01.376   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:06.382   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:11.388   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:16.394   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:20.186   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:05:20.186   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:05:20.187   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 447789080284; DSPS: 14765056; Offset : -2814334662
,08-26 15:05:21.400   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:26.406   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:31.412   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:36.419   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:40.189   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:05:40.189   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:05:40.190   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 467792084708; DSPS: 15420525; Offset : -2814654543
,08-26 15:05:41.425   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:46.431   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:51.437   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:05:54.261   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:05:54.261   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:05:54.261   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 481863569408; DSPS: 15881608; Offset : -2814308427
,08-26 15:05:56.443   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:06:00.095  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:06:00.095  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:06:00.095  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:06:00.099  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:06:00.099  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:06:00.100  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:06:00.101  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:06:00.470   491   491 D charger_monitor: init target 500000
,08-26 15:06:00.475   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:06:00.477  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-26 15:06:00.484  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:06:00.484  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:06:00.484  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:06:00.484  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-26 15:06:00.521  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:06:00.524  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:06:00.524  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:06:00.525  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:06:00.525  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:06:00.525  1806  1973 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
08-26 15:06:00.531   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:06:00.531   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:06:00.531   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:06:00.532  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
08-26 15:06:00.532  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:06:00.532  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
08-26 15:06:00.534  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:06:01.449   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:06:06.456   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:06:09.263   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:06:09.263   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:06:09.263   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 496865820278; DSPS: 16373205; Offset : -2814407412
,08-26 15:06:11.462   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:06:16.468   300   355 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-26 15:06:21.474   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:06:26.480   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:06:31.487   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:06:31.768   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:06:31.768   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:06:31.768   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 519370547070; DSPS: 17110636; Offset : -2814288747
,08-26 15:06:36.493   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:06:41.499   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:06:46.279  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:06:46.282  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:06:46.282  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:06:46.282  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:06:46.282  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:06:46.314   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-26 15:06:46.352  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:06:46.354   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:06:46.354  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:06:46.354  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:06:46.362  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:06:46.362  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:06:46.442  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:06:46.443  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,08-26 15:06:46.446  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 301
08-26 15:06:46.447  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:06:46.447  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 301
08-26 15:06:46.448  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:06:46.448  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:06:46.448  1806  1973 D LEDHandler: Battery Temp: 301, mChargingStatus=5, mChargingStop=false
08-26 15:06:46.452  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 15:06:46.456  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:06:46.460   834  1315 D WifiController: battery changed pluggedType: 2
,08-26 15:06:46.459   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:06:46.460   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:06:46.497  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:06:46.501  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:06:46.502  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 301
08-26 15:06:46.503  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:06:46.503  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:06:46.503  1806  1973 D LEDHandler: Battery Temp: 301, mChargingStatus=5, mChargingStop=false
08-26 15:06:46.503  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:06:46.504   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
08-26 15:06:46.505  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:06:46.505  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 301
08-26 15:06:46.507  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:06:46.511   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:06:46.511   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:06:46.514   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:06:48.322   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-26 15:06:48.332  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-26 15:06:48.332  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:06:48.332  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:06:48.332  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:06:48.332  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:06:48.371  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:06:48.375  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:06:48.376  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:06:48.377  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:06:48.377  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:06:48.377  1806  1973 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
08-26 15:06:48.378  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
08-26 15:06:48.378  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:06:48.378  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
08-26 15:06:48.380  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:06:48.384   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:06:48.384   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:06:48.387   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:06:51.510   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:06:51.770   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:06:51.770   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:06:51.770   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 539372939331; DSPS: 17766074; Offset : -2814276910
,08-26 15:06:56.516   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:00.046  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:07:00.046  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:07:00.046  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:07:00.050  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:07:00.050  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:07:00.051  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:07:00.052  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:07:00.629  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:07:00.631   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:07:00.632  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:07:00.632  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:07:00.633  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:07:00.633  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:07:00.673  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:07:00.673  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,08-26 15:07:00.678  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:07:00.678  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:07:00.678  1806  1973 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
08-26 15:07:00.679  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
08-26 15:07:00.679  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:07:00.680  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
08-26 15:07:00.683  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 15:07:00.687  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:07:00.690   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:07:00.690   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:07:00.690   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:07:01.522   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:06.528   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:11.535   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:11.773   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:07:11.773   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:07:11.773   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 559375175967; DSPS: 18421507; Offset : -2814265974
,08-26 15:07:16.541   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:21.547   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:26.553   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:31.559   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:31.775   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:07:31.775   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:07:31.775   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 579377389943; DSPS: 19076940; Offset : -2814281837
,08-26 15:07:36.565   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:41.572   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:46.578   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:46.777   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:07:46.777   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:07:46.777   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 594379520806; DSPS: 19568529; Offset : -2814256687
,08-26 15:07:51.584   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:07:56.591   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:00.093  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:08:00.094  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:08:00.094  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:08:00.098  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:08:00.098  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:08:00.099  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:08:00.100  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:08:00.789  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:08:00.792  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:08:00.792  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:08:00.792  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:08:00.793  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:08:00.796   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:08:00.835  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:08:00.840  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:08:00.840  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:08:00.840  1806  1973 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
08-26 15:08:00.841  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:08:00.841  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:08:00.845   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:08:00.845   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:08:00.845   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:08:00.846  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
08-26 15:08:00.846  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:08:00.846  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
08-26 15:08:00.848  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:08:01.597   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:06.603   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:06.779   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:08:06.779   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:08:06.779   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 614381755162; DSPS: 20223963; Offset : -2814278575
,08-26 15:08:11.609   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:16.615   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:21.622   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:21.781   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:08:21.782   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:08:21.782   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 629384150336; DSPS: 20715562; Offset : -2814296321
,08-26 15:08:26.628   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:31.634   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:35.853   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:08:35.853   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:08:35.853   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 643455871308; DSPS: 21176654; Offset : -2813986482
,08-26 15:08:36.640   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:41.646   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:46.652   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:48.985   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:08:48.985   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:08:48.986   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 656588108626; DSPS: 21606973; Offset : -2814042944
,08-26 15:08:51.658   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:08:56.664   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:00.094  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:09:00.094  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:09:00.094  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:09:00.098  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:09:00.098  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:09:00.100  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:09:00.100  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:09:00.949  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:09:00.952  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:09:00.952  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:09:00.952  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:09:00.953  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:09:00.956   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:09:00.995  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:09:01.000  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:09:01.000  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:09:01.001  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:09:01.001  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:09:01.001  1806  1973 D LEDHandler: Battery Temp: 299, mChargingStatus=5, mChargingStop=false
08-26 15:09:01.005   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:09:01.005   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:09:01.006   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:09:01.006  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
08-26 15:09:01.006  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:09:01.006  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
08-26 15:09:01.008  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:09:01.671   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:03.990   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:09:03.990   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:09:03.990   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 671592882701; DSPS: 22098657; Offset : -2814271642
,08-26 15:09:06.677   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:11.683   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:16.688   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:21.694   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:23.993   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:09:23.993   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:09:23.993   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 691595260371; DSPS: 22754092; Offset : -2814184821
,08-26 15:09:24.428  5727  6145 I PlayCommon: [690] com.google.android.play.a.l.e(787): Preparing logs for uploading
08-26 15:09:24.429  5727  6145 I PlayCommon: [690] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:09:26.700   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:31.706   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:36.712   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:38.995   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:09:38.995   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:09:38.995   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 706597435203; DSPS: 23245689; Offset : -2814359868
,08-26 15:09:41.729   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:46.735   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:51.741   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:09:52.127   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:09:52.127   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:09:52.128   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 719729612746; DSPS: 23676000; Offset : -2814229725
,08-26 15:09:56.747   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:00.065  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:10:00.065  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:10:00.065  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:10:00.069  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:10:00.069  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:10:00.071  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:10:00.071  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:10:01.109  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:10:01.112  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:10:01.112  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:10:01.112  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:10:01.113  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:10:01.116   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:10:01.155  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:10:01.159  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:10:01.160  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:10:01.161  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:10:01.161  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:10:01.161  1806  1973 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
08-26 15:10:01.165   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:10:01.165   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:10:01.166   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:10:01.166  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
08-26 15:10:01.166  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:10:01.166  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
08-26 15:10:01.168  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:10:01.753   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:06.759   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:07.129   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:10:07.129   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:10:07.129   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 734731953049; DSPS: 24167598; Offset : -2814269923
,08-26 15:10:11.765   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:16.771   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:21.777   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:22.132   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:10:22.132   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:10:22.132   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 749734353503; DSPS: 24659196; Offset : -2814249840
,08-26 15:10:26.783   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:31.789   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:35.888   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:10:35.888   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:10:35.888   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 763489950474; DSPS: 25109936; Offset : -2814145618
,08-26 15:10:36.795   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:41.801   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:46.807   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:51.814   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:56.820   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:10:57.930   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:10:57.930   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:10:57.931   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 785533104901; DSPS: 25832252; Offset : -2814328572
,08-26 15:11:00.093  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:11:00.093  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:11:00.093  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:11:00.097  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:11:00.097  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:11:00.099  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:11:00.100  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:11:01.269  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:11:01.272  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:11:01.272  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:11:01.273  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:11:01.274  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:11:01.276   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:11:01.315  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:11:01.319  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:11:01.319  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:11:01.320  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:11:01.321  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:11:01.321  1806  1973 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
08-26 15:11:01.325   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:11:01.325   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:11:01.326   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:11:01.326  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
08-26 15:11:01.326  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:11:01.326  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
08-26 15:11:01.329  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:11:01.826   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:11:06.832   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:11:11.838   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:11:12.933   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:11:12.933   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:11:12.933   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 800535393838; DSPS: 26323846; Offset : -2814295801
,08-26 15:11:16.845   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:11:21.851   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:11:26.863   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:11:30.436   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:11:30.436   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:11:30.436   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 818038698359; DSPS: 26897393; Offset : -2814256687
,08-26 15:11:31.869   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:11:36.875   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:11:41.882   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:11:45.438   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:11:45.438   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:11:45.438   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 833040891196; DSPS: 27388986; Offset : -2814293481
,08-26 15:11:46.888   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:11:51.894   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:11:56.900   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:00.094  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:12:00.094  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:12:00.094  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:12:00.098  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:12:00.098  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:12:00.099  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:12:00.100  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:12:01.428  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:12:01.431   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:12:01.432  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:12:01.432  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:12:01.432  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:12:01.432  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:12:01.906   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:02.942   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:12:02.942   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:12:02.942   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 850544317162; DSPS: 27962539; Offset : -2814314387
,08-26 15:12:06.912   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:11.918   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:16.924   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:21.931   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:22.944   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:12:22.944   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:12:22.944   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 870546606010; DSPS: 28617976; Offset : -2814375445
,08-26 15:12:26.937   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:31.943   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:34.588  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:12:34.590  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:12:34.590  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:12:34.591  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:12:34.591  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:12:34.601   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-26 15:12:34.659  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:12:34.663  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:12:34.663  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:12:34.664  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:12:34.664  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:12:34.664  1806  1973 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
08-26 15:12:34.665  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
08-26 15:12:34.665  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:12:34.665  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
08-26 15:12:34.667  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:12:34.671   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:12:34.671   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:12:34.675   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:12:34.715  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:12:34.719  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
08-26 15:12:34.719  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:12:34.719  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
08-26 15:12:34.720  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:12:34.720  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:12:34.721  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:12:34.722  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:12:34.722  1806  1973 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
08-26 15:12:34.727   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:12:34.727   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:12:34.734   834  1315 D WifiController: battery changed pluggedType: 2
,08-26 15:12:34.740  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:12:36.949   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:37.946   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:12:37.946   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:12:37.946   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 885549004195; DSPS: 29109568; Offset : -2814174319
,08-26 15:12:41.955   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:46.962   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:51.968   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:12:52.948   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:12:52.948   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:12:52.949   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 900551106216; DSPS: 29601162; Offset : -2814332681
,08-26 15:12:56.974   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:00.060  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:13:00.060  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:13:00.060  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:13:00.063  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:13:00.063  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:13:00.064  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:13:00.065  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:13:01.588  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:13:01.591   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:13:01.592  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:13:01.592  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:13:01.592  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:13:01.592  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:13:01.633  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:13:01.638  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:13:01.638  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:13:01.639  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:13:01.639  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:13:01.639  1806  1973 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
08-26 15:13:01.643   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:13:01.643   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:13:01.644   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:13:01.644  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
08-26 15:13:01.644  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:13:01.645  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
08-26 15:13:01.647  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:13:01.980   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:06.986   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:11.992   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:12.951   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:13:12.951   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:13:12.951   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 920553451720; DSPS: 30256596; Offset : -2814245503
,08-26 15:13:17.007   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:22.012   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:27.018   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:32.025   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:32.953   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:13:32.953   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:13:32.953   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 940555884238; DSPS: 30912036; Offset : -2814252309
,08-26 15:13:37.031   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:40.021   834  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=113159564, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
,08-26 15:13:40.023   834  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2fd704b9 type 2 when 947613 com.android.bluetooth} when 947613
08-26 15:13:40.171   834   834 D PowerManagerServiceEx: releaseWakeLockInternal: lock=113159564 [*alarm*], flags=0x0
,08-26 15:13:40.198  2020  3694 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
08-26 15:13:40.198  2020  3694 W bt-smp  : Plain text(LSB ~ MSB) = 61 76 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-26 15:13:40.200  2020  3694 W bt-smp  : Encrypted text(LSB ~ MSB) = 74 52 cf 2a c1 fb e2 1c 73 9b fa 2c 9e 47 32 0e 
08-26 15:13:40.200  2020  3694 W bt-btm  : Stopping oneshot timer
08-26 15:13:42.035   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:47.041   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:52.048   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:13:52.955   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:13:52.955   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:13:52.955   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 960557303585; DSPS: 31567444; Offset : -2814297831
,08-26 15:13:57.054   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:00.053  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:14:00.054  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:14:00.054  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:14:00.058  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:14:00.058  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:14:00.059  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:14:00.059  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:14:01.748  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:14:01.751   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:14:01.754  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:14:01.754  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:14:01.754  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:14:01.754  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:14:02.060   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:07.066   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:12.072   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:12.957   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:14:12.957   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:14:12.957   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 980559619193; DSPS: 32222880; Offset : -2814301221
,08-26 15:14:17.079   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:22.084   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:24.431  5727  6145 I PlayCommon: [690] com.google.android.play.a.l.e(787): Preparing logs for uploading
08-26 15:14:24.431  5727  6145 I PlayCommon: [690] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:14:24.896  5727  5796 I PlayCommon: [672] com.google.android.play.a.l.e(787): Preparing logs for uploading
08-26 15:14:24.896  5727  5796 I PlayCommon: [672] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:14:27.090   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:27.960   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:14:27.960   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:14:27.960   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 995562203906; DSPS: 32714485; Offset : -2814310788
,08-26 15:14:32.097   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:37.103   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:41.094   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:14:41.094   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:14:41.094   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1008696695649; DSPS: 33144875; Offset : -2814279546
,08-26 15:14:42.109   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:47.115   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:52.121   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:14:57.128   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:00.092  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:15:00.092  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:15:00.093  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:15:00.096  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:15:00.097  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:15:00.098  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:15:00.099  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:15:00.475   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:15:00.475   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:15:00.475   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1028077331823; DSPS: 33779940; Offset : -2814289020
,08-26 15:15:01.900  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:15:01.903  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:15:01.903  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:15:01.903  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:15:01.903  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:15:01.913   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-26 15:15:01.955  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:15:01.959  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:15:01.959  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:15:01.960  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:15:01.960  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:15:01.960  1806  1973 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
08-26 15:15:01.964   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:15:01.964   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:15:01.965   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:15:01.965  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
08-26 15:15:01.966  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:15:01.966  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
08-26 15:15:01.968  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:15:02.141   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:07.147   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:12.154   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:17.163   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:20.477   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:15:20.477   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:15:20.477   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1048079536345; DSPS: 34435369; Offset : -2814192373
,08-26 15:15:22.169   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:27.175   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:32.182   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:37.188   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:40.479   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:15:40.479   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:15:40.479   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1068081738282; DSPS: 35090804; Offset : -2814277172
,08-26 15:15:42.194   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:47.200   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:52.206   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:15:57.212   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:00.040  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:16:00.040  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:16:00.040  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:16:00.043  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:16:00.043  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:16:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:16:00.044  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:16:00.481   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:16:00.481   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:16:00.481   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1088084009750; DSPS: 35746239; Offset : -2814294443
,08-26 15:16:02.061  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:16:02.063  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:16:02.063  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:16:02.063  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:16:02.063  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:16:02.074   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-26 15:16:02.218   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:07.225   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:12.231   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:17.238   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:22.244   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:22.986   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:16:22.986   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:16:22.986   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1110588850069; DSPS: 36483676; Offset : -2814247519
,08-26 15:16:27.250   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:32.256   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:37.262   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:42.269   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:42.988   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:16:42.988   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:16:42.988   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1130591000500; DSPS: 37139110; Offset : -2814355363
,08-26 15:16:47.275   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:52.286   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:16:57.292   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:17:00.092  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:17:00.092  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:17:00.093  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:17:00.095  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:17:00.095  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:17:00.096  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:17:00.099  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:17:02.228  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:17:02.231   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:17:02.232  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:17:02.232  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:17:02.237  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:17:02.237  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:17:02.273  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:17:02.277  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:17:02.278  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:17:02.280  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:17:02.280  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:17:02.280  1806  1973 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
08-26 15:17:02.283   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:17:02.283   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:17:02.284   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:17:02.284  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
08-26 15:17:02.285  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:17:02.285  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
08-26 15:17:02.287  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:17:02.297   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
08-26 15:17:02.991   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:17:02.991   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:17:02.991   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1150593371572; DSPS: 37794543; Offset : -2814209991
,08-26 15:17:07.302   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:17:12.307   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:17:17.314   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:17:17.993   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:17:17.993   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:17:17.993   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1165595753333; DSPS: 38286142; Offset : -2814241227
,08-26 15:17:22.320   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:17:27.328   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:17:32.064   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:17:32.065   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:17:32.065   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1179667146304; DSPS: 38747234; Offset : -2814259363
,08-26 15:17:32.334   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:17:37.340   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:17:42.346   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:17:45.197   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:17:45.197   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:17:45.197   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1192799196370; DSPS: 39177546; Offset : -2814287318
,08-26 15:17:47.353   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:17:52.359   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:17:57.363   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:00.041  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:18:00.041  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:18:00.042  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:18:00.044  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:18:00.044  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:18:00.045  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:18:00.046  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:18:02.372   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:02.393  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:18:02.398  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:18:02.398  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:18:02.398  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:18:02.399  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:18:02.399   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:18:02.442  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:18:02.446  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:18:02.446  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:18:02.448  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:18:02.448  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:18:02.448  1806  1973 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
08-26 15:18:02.452   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:18:02.452   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:18:02.453   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:18:02.453  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
08-26 15:18:02.453  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:18:02.454  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
08-26 15:18:02.456  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:18:02.700   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:18:02.700   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:18:02.700   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1210302708568; DSPS: 39751101; Offset : -2814286725
,08-26 15:18:07.379   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:12.385   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:16.830   834   967 I UsageStatsService: User[0] Flushing usage stats to disk
,08-26 15:18:17.391   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:22.397   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:22.702   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:18:22.702   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:18:22.702   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1230304997135; DSPS: 40406536; Offset : -2814284920
,08-26 15:18:27.404   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:32.410   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:37.419   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:42.425   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:42.705   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:18:42.705   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:18:42.705   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1250307226321; DSPS: 41061967; Offset : -2814224487
,08-26 15:18:47.431   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:52.437   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:57.443   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:18:57.707   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:18:57.707   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:18:57.707   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1265309548079; DSPS: 41553560; Offset : -2814128533
,08-26 15:19:00.056  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:19:00.056  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:19:00.057  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:19:00.062  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:19:00.062  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:19:00.062  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:19:00.063  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:19:02.449   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:19:02.541  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:19:02.543  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:19:02.543  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:19:02.543  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:19:02.543  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:19:02.589   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-26 15:19:07.455   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:19:12.462   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:19:17.468   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:19:18.963   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:19:18.963   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:19:18.963   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1286565410329; DSPS: 42250077; Offset : -2814280277
,08-26 15:19:22.475   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:19:24.433  5727  6145 I PlayCommon: [690] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-26 15:19:24.434  5727  6145 I PlayCommon: [690] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:19:24.998  5727  5796 I PlayCommon: [672] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-26 15:19:24.998  5727  5796 I PlayCommon: [672] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:19:27.481   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:19:32.487   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:19:37.493   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:19:38.965   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:19:38.965   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:19:38.965   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1306567606880; DSPS: 42905503; Offset : -2814095829
,08-26 15:19:42.499   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:19:47.505   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:19:52.097   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:19:52.097   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:19:52.097   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1319699410214; DSPS: 43335812; Offset : -2814283130
,08-26 15:19:52.512   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:19:57.518   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:00.078  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:20:00.078  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:20:00.078  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:20:00.082  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:20:00.082  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:20:00.083  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:20:00.084  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:20:02.524   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:02.708  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:20:02.710   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:20:02.717  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:20:02.717  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:20:02.717  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:20:02.718  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:20:07.530   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:12.536   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:13.669   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:20:13.669   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:20:13.669   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1341271697099; DSPS: 44042686; Offset : -2814076551
,08-26 15:20:17.542   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:22.548   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:27.564   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:28.671   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:20:28.671   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:20:28.671   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1356273951704; DSPS: 44534284; Offset : -2814202395
,08-26 15:20:32.570   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:37.577   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:42.583   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:43.674   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:20:43.674   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:20:43.674   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1371276272724; DSPS: 45025886; Offset : -2814385899
,08-26 15:20:47.589   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:52.595   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:57.601   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:20:58.676   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:20:58.676   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:20:58.676   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1386278532442; DSPS: 45517475; Offset : -2814229890
,08-26 15:21:00.091  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:21:00.091  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:21:00.091  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:21:00.095  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:21:00.095  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:21:00.097  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:21:00.098  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:21:02.607   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:21:02.868  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:21:02.871   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:21:02.872  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:21:02.872  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:21:02.872  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:21:02.872  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:21:02.913  2020  3602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:21:02.918  1842  1842 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-26 15:21:02.918  1842  1842 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-26 15:21:02.919  1806  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 15:21:02.919  1806  1973 D LEDHandler: Battery Level Remaining: 100%
08-26 15:21:02.919  1806  1973 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
08-26 15:21:02.923   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:21:02.924   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:21:02.924   834  1315 D WifiController: battery changed pluggedType: 2
08-26 15:21:02.924  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
08-26 15:21:02.924  1371  1371 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 15:21:02.925  1371  1371 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
08-26 15:21:02.927  1371  1371 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-26 15:21:07.613   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:21:12.620   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:21:17.626   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:21:18.678   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:21:18.678   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:21:18.678   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1406280817395; DSPS: 46172916; Offset : -2814416755
,08-26 15:21:22.632   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:21:27.638   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:21:32.645   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:21:37.651   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:21:41.183   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:21:41.183   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:21:41.183   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1428785333284; DSPS: 46910342; Offset : -2814356537
,08-26 15:21:42.657   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:21:47.663   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:21:52.669   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:21:56.185   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:21:56.185   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:21:56.185   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1443787559618; DSPS: 47401935; Offset : -2814357856
,08-26 15:21:57.675   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:00.091  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:22:00.091  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:22:00.091  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:22:00.096  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:22:00.096  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:22:00.097  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:22:00.098  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:22:02.681   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:03.021  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:22:03.023  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:22:03.023  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:22:03.023  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:22:03.023  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:22:03.034   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-26 15:22:07.688   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:09.317   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:22:09.317   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:22:09.317   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1456919591725; DSPS: 47832243; Offset : -2814283497
,08-26 15:22:12.696   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:17.703   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:22.709   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:27.715   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:29.319   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:22:29.319   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:22:29.319   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1476921950537; DSPS: 48487678; Offset : -2814213789
,08-26 15:22:32.721   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:37.727   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:42.733   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:47.739   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:49.321   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:22:49.321   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:22:49.322   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1496924090919; DSPS: 49143109; Offset : -2814240182
,08-26 15:22:52.745   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:22:57.751   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:23:00.092  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 15:23:00.092  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 15:23:00.092  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-26 15:23:00.096  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 15:23:00.096  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:23:00.098  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-26 15:23:00.099  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:23:02.757   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:23:03.189  1806  1806 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-26 15:23:03.192  1371  1371 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-26 15:23:03.192  1371  1371 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-26 15:23:03.192  1371  1371 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-26 15:23:03.192  1371  1371 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 15:23:03.196   491   491 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-26 15:23:07.763   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:23:09.323   834   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-26 15:23:09.324   834   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-26 15:23:09.324   834   986 D sensors_hal_Time: tsOffsetIs: Apps: 1516926142135; DSPS: 49798537; Offset : -2814264188
,08-26 15:23:12.769   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-26 15:23:17.776   300   355 I ThermalEngine: Sensor:pa_therm0:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),08-26 15:23:19.847  6929  6929 D AndroidRuntime: 
08-26 15:23:19.847  6929  6929 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 15:23:19.855  6929  6929 D AndroidRuntime: CheckJNI is OFF
08-26 15:23:20.091  6929  6929 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-26 15:23:20.123   834   969 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
08-26 15:23:20.220   834  1059 W PackageSettings: Skipping PackageSetting{10b8b404 com.example.hello/10317} due to missing metadata
08-26 15:23:20.263   834  1059 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-26 15:23:20.322  1880  1880 I art     : Explicit concurrent mark sweep GC freed 8468(472KB) AllocSpace objects, 5(681KB) LOS objects, 40% free, 15MB/25MB, paused 1.306ms total 55.994ms
08-26 15:23:20.365  1880  1880 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 15:23:20.367  1371  1371 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-26 15:23:20.369  1735  2401 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 15:23:20.370  1880  1880 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 15:23:20.370  1880  1880 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-26 15:23:20.374   834  1290 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 15:23:20.379  1842  1842 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-26 15:23:20.386  3752  3752 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-26 15:23:20.386  3752  3752 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 15:23:20.386  3752  3752 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 15:23:20.386  3752  3752 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-26 15:23:20.386  3752  3752 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:23:20.386  3752  3752 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:23:20.386  3752  3752 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:23:20.386  3752  3752 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-26 15:23:20.386  3752  3752 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:23:20.387  3752  3752 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:23:20.387  3752  3752 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-26 15:23:20.387  3752  3752 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-26 15:23:20.396  1948  1948 I art     : Explicit concurrent mark sweep GC freed 4552(342KB) AllocSpace objects, 4(737KB) LOS objects, 40% free, 12MB/21MB, paused 8.232ms total 119.458ms
08-26 15:23:20.432   834   969 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6959 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-26 15:23:20.460  3366  3366 I art     : Explicit concurrent mark sweep GC freed 16567(1016KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 16MB/22MB, paused 971us total 151.975ms
08-26 15:23:20.494   834  1788 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6968 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
08-26 15:23:20.518   834   834 I art     : Explicit concurrent mark sweep GC freed 26632(1817KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 5.908ms total 195.068ms
08-26 15:23:20.520   834  1059 I art     : WaitForGcToComplete blocked for 24.089ms for cause Explicit
08-26 15:23:20.541  1371  1371 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-26 15:23:20.587  6959  6959 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:23:20.589  6959  6959 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 15:23:20.596  6959  6959 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 15:23:20.604  1371  1371 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 15:23:20.604  1371  1371 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-26 15:23:20.645   834   834 D administrator: Handling package changes for user 0
08-26 15:23:20.651  6968  6968 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-26 15:23:20.694  1371  1511 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 15:23:20.694  1371  1511 D KeyguardModel: createShortcutInfo...
08-26 15:23:20.699  1371  1511 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 15:23:20.699  1371  1511 D KeyguardModel: createShortcutInfo...
08-26 15:23:20.701  1371  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:23:20.706  1371  1511 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 15:23:20.709  1371  1511 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 15:23:20.710  1371  1511 D KeyguardModel: createShortcutInfo...
08-26 15:23:20.714  1371  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:23:20.714  1371  1511 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 15:23:20.716  1371  1511 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 15:23:20.716  1371  1511 D KeyguardModel: createShortcutInfo...
08-26 15:23:20.727  1371  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:23:20.728  1371  1511 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 15:23:20.733  1371  1511 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 15:23:20.733  1371  1511 D KeyguardModel: createShortcutInfo...
08-26 15:23:20.739  1371  1371 D KeyguardModel: handleShortcutListChanged...
08-26 15:23:20.743  1371  1511 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 15:23:20.743  1371  1511 D KeyguardModel: createShortcutInfo...
08-26 15:23:20.747  1371  1511 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 15:23:20.747  1371  1511 D KeyguardModel: createShortcutInfo...
08-26 15:23:20.749  1371  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:23:20.749  1371  1511 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 15:23:20.750  1371  1511 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 15:23:20.750  1371  1511 D KeyguardModel: createShortcutInfo...
08-26 15:23:20.752  1371  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:23:20.752  1371  1511 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 15:23:20.753  1371  1511 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 15:23:20.753  1371  1511 D KeyguardModel: createShortcutInfo...
08-26 15:23:20.755  1371  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:23:20.755  1371  1511 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 15:23:20.757  1371  1511 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 15:23:20.757  1371  1511 D KeyguardModel: createShortcutInfo...
08-26 15:23:20.765   834  1286 I ActivityManager: Killing 6094:com.android.providers.calendar/u0a14 (adj 15): empty #11
08-26 15:23:20.830   834   834 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-26 15:23:20.830   834   834 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 15:23:20.832   834   834 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 15:23:20.851  1371  1371 D KeyguardModel: handleShortcutListChanged...
08-26 15:23:20.851   834  1886 W libprocessgroup: failed to open /acct/uid_10014/pid_6094/cgroup.procs: No such file or directory
08-26 15:23:20.854   834  1350 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-26 15:23:20.866  6959  6959 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-26 15:23:20.879   834  1059 I art     : Explicit concurrent mark sweep GC freed 9111(1222KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 6.021ms total 356.364ms
08-26 15:23:20.889  6959  6959 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
08-26 15:23:20.961  6929  6929 D AndroidRuntime: Shutting down VM
08-26 15:23:21.018   834  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7000 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 15:23:21.018  1789  1789 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-26 15:23:21.018  1789  1789 D LCardEmulationManager: getDefaultRoute
08-26 15:23:21.110  6959  6959 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-26 15:23:21.146   834   852 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7020 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-26 15:23:21.147   834   852 I ActivityManager: Killing 5905:com.google.android.gms:car/u0a6 (adj 15): empty #11
08-26 15:23:21.197   834  1832 W libprocessgroup: failed to open /acct/uid_10006/pid_5905/cgroup.procs: No such file or directory
08-26 15:23:21.204   834  6967 I ActivityManager: Killing 5888:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
08-26 15:23:21.229  6073  6073 W System.err: android.os.DeadObjectException
08-26 15:23:21.246  6073  6073 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 15:23:21.246  6073  6073 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 15:23:21.247  6073  6073 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 15:23:21.247  6073  6073 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
08-26 15:23:21.247  6073  6073 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
08-26 15:23:21.247  6073  6073 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
08-26 15:23:21.247  6073  6073 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:23:21.247  6073  6073 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:23:21.248  6073  6073 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:23:21.248  6073  6073 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-26 15:23:21.248  6073  6073 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:23:21.248  6073  6073 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:23:21.248  6073  6073 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-26 15:23:21.248  6073  6073 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-26 15:23:21.248  6073  6073 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 15:23:21.249  6073  6073 W System.err: android.os.DeadObjectException
08-26 15:23:21.249  6073  6073 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 15:23:21.249  6073  6073 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 15:23:21.249  6073  6073 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 15:23:21.249  6073  6073 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
08-26 15:23:21.249  6073  6073 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
08-26 15:23:21.249  6073  6073 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
08-26 15:23:21.249  6073  6073 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:23:21.249  6073  6073 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:23:21.249  6073  6073 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:23:21.249  6073  6073 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-26 15:23:21.249  6073  6073 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:23:21.249  6073  6073 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:23:21.249  6073  6073 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-26 15:23:21.249  6073  6073 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-26 15:23:21.249  6073  6073 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 15:23:21.310   834  1886 W libprocessgroup: failed to open /acct/uid_10089/pid_5888/cgroup.procs: No such file or directory
08-26 15:23:21.310   834  1886 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
08-26 15:23:21.334  7020  7020 I AppUp4:AppBoxCP: onCreate
08-26 15:23:21.344  7020  7020 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-26 15:23:21.353  7020  7020 I AppUp4:DB:  setFingerPrint start
08-26 15:23:21.354  7020  7020 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
08-26 15:23:21.362   834  1961 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7043 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:23:21.373  7020  7020 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
08-26 15:23:21.373  7020  7020 I AppUp4:DB:  SDK version = 21
08-26 15:23:21.373  7020  7020 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-26 15:23:21.388  7020  7020 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-26 15:23:21.403  7020  7020 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: Error inserting package=com.test.thalitest
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-26 15:23:21.407  7020  7020 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-26 15:23:21.454   834  1788 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7060 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a

```
