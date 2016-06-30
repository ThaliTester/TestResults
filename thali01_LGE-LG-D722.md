#### Test 72145431fdae11f_thali01_LGE-LG-D722 Logs


```
--------- beginning of main
06-30 10:35:30.457   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:35:32.914  5630  5630 D AndroidRuntime: 
06-30 10:35:32.914  5630  5630 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 10:35:32.923  5630  5630 D AndroidRuntime: CheckJNI is OFF
06-30 10:35:33.168  5630  5630 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 10:35:33.193   944  2189 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 10:35:33.249   944  2189 D ActivityManager: setTaskToReturnTo : TaskRecord{d1be8fd #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 10:35:33.251   944  2189 D ActivityManager: setTaskToReturnTo : TaskRecord{d1be8fd #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 10:35:33.265   944  2189 D WindowStateEx: AppWindowTokenEx init.. 
06-30 10:35:33.277   944  1051 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
06-30 10:35:33.294  1945  1945 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
06-30 10:35:33.296   944  2189 D InputDispatcher: Focus left window: Window{1dc2c677 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
06-30 10:35:33.297   944  1051 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-30 10:35:33.298  5630  5630 D AndroidRuntime: Shutting down VM
06-30 10:35:33.316   944  1051 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
06-30 10:35:33.316   944  1051 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
06-30 10:35:33.331   944  1051 D SplitWindow: check instance of lgWin Window{3143ab5 u0 Starting com.test.thalitest}
06-30 10:35:33.363   944   963 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5650 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 10:35:33.395  1945  1945 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
06-30 10:35:33.446  2019  2019 I HotwordDetector: Closing mic
06-30 10:35:33.455  2019  2559 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2b4deef9
06-30 10:35:33.455  2019  2559 V AudioRecord: stop()
06-30 10:35:33.455  2019  2559 D AudioRecord: AudioRecord->stop()
06-30 10:35:33.457   283   283 V AudioFlinger: RecordHandle::stop()
06-30 10:35:33.457   283   283 V AudioFlinger: RecordThread::stop
06-30 10:35:33.458  1945  1945 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
06-30 10:35:33.470   283   283 V AudioFlinger: Record stopped OK
06-30 10:35:33.471   283   283 V AudioPolicyManager: stopInput() input 17
06-30 10:35:33.471   944  1988 I WindowStateAnimator: Starting window displayed
06-30 10:35:33.472   283   283 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
06-30 10:35:33.472   283   283 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
06-30 10:35:33.472   283  1062 V AudioPolicyService: AudioCommandThread() waking up
06-30 10:35:33.472   283  1062 V AudioPolicyService: AudioCommandThread() processing release audio patch
06-30 10:35:33.472   283  1062 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
06-30 10:35:33.473   283  1062 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
06-30 10:35:33.473   283  1062 V AudioFlinger: ThreadBase::setParameters() routing=0
06-30 10:35:33.473   283  1062 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
06-30 10:35:33.475   283  2573 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 10:35:33.475   283  2573 V AudioFlinger: processConfigEvents_l() DONE thread 0xb384e000
06-30 10:35:33.477   283  2573 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
,06-30 10:35:33.479   944  1049 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
06-30 10:35:33.479   944  1049 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
06-30 10:35:33.482   944  1049 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
06-30 10:35:33.482   944  1049 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
06-30 10:35:33.482   944  1049 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 10:35:33.482   944  1049 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@77c41,  pkg=WindowManager.LayoutParams
06-30 10:35:33.482   944  1049 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
06-30 10:35:33.483  1368  1368 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
06-30 10:35:33.485  1368  1368 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
06-30 10:35:33.485  1368  1368 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
06-30 10:35:33.485  1368  1368 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
06-30 10:35:33.523   283  2573 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
06-30 10:35:33.523   283  2573 V audio_hw_primary: disable_audio_route: enter: usecase(7)
06-30 10:35:33.523   283  2573 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
06-30 10:35:33.523   283  2573 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
06-30 10:35:33.525   283  2573 V audio_hw_primary: disable_audio_route: exit
06-30 10:35:33.525   283  2573 E audio_hw_primary: disable_snd_device: enter 144
06-30 10:35:33.525   283  2573 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
06-30 10:35:33.525   283  2573 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
06-30 10:35:33.529   283  2573 V audio_hw_primary: stop_input_stream: exit: status(0)
06-30 10:35:33.529   283  2573 V audio_hw_primary: in_standby: exit:  status(0)
06-30 10:35:33.529   283  2573 V AudioFlinger: RecordThread: loop stopping
06-30 10:35:33.530   283   283 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
06-30 10:35:33.530   283  1062 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 10:35:33.530   283   283 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
06-30 10:35:33.530   283   283 V AudioPolicyService: AudioCommandThread() adding update audio patch list
06-30 10:35:33.530   283   283 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
06-30 10:35:33.530   283  1063 V AudioPolicyService: AudioCommandThread() waking up
06-30 10:35:33.530   283  1063 V AudioPolicyService: AudioCommandThread() processing update audio patch list
06-30 10:35:33.531   283  1063 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 10:35:33.531   283   283 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
06-30 10:35:33.531   283   283 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
06-30 10:35:33.532   283  1062 V AudioPolicyService: AudioCommandThread() waking up
06-30 10:35:33.532   283  1062 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
06-30 10:35:33.532   283  1062 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 283
06-30 10:35:33.532   283  1062 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
06-30 10:35:33.532   283  1062 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
06-30 10:35:33.532   283  2573 V AudioFlinger: RecordThread: loop starting
06-30 10:35:33.532   283  2573 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 10:35:33.532   283  2573 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
06-30 10:35:33.532   283  2573 V audio_hw_primary: in_set_parameters: exit: status(0)
06-30 10:35:33.532   283  2573 V AudioFlinger: processConfigEvents_l() DONE thread 0xb384e000
06-30 10:35:33.532   283  2573 V AudioFlinger: RecordThread: loop stopping
06-30 10:35:33.532   283  1062 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 10:35:33.548  2019  2559 V AudioRecord: stop()
06-30 10:35:33.549  2019  2559 V AudioRecord: stop()
06-30 10:35:33.549  2019  2559 V AudioRecord: stop()
06-30 10:35:33.550   283  1611 V AudioFlinger: RecordHandle::stop()
06-30 10:35:33.551   283  1611 V AudioFlinger: RecordThread::stop
06-30 10:35:33.551   283  1611 V AudioPolicyManager: releaseInput() 17
06-30 10:35:33.551   283  1611 V AudioPolicyManager: closeInput(17)
06-30 10:35:33.551   283  1611 V AudioFlinger: closeInput() 17
06-30 10:35:33.551   283  1611 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 10:35:33.551   944  1988 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 10:35:33.551   283  1611 V AudioFlinger: ThreadBase::exit
06-30 10:35:33.551   283  2573 V AudioFlinger: RecordThread: loop starting
06-30 10:35:33.551   283  2573 V AudioFlinger: RecordThread 0xb384e000 exiting
06-30 10:35:33.552   283  1611 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dd40)
06-30 10:35:33.552   283  1611 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
06-30 10:35:33.552   283  1611 V audio_hw_primary: in_standby: exit:  status(0)
06-30 10:35:33.552   283  1611 V AudioPolicyService: AudioCommandThread() adding update audio port list
06-30 10:35:33.552   283  1611 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
06-30 10:35:33.552  1775  2385 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 10:35:33.552   283  1063 V AudioPolicyService: AudioCommandThread() waking up
06-30 10:35:33.553  2019  2044 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 10:35:33.553   283  1063 V AudioPolicyService: AudioCommandThread() processing update audio port list
06-30 10:35:33.553   283   283 V AudioFlinger: releasing 16 from 2019 for -1
06-30 10:35:33.553   283   283 V AudioFlinger:  decremented refcount to 0
06-30 10:35:33.553   283   283 V AudioFlinger: purging stale effects
06-30 10:35:33.553   283  1063 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 10:35:33.553  3090  3106 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 10:35:33.553   283  1611 V AudioPolicyManager: releaseInput() exit
06-30 10:35:33.553  1368  1392 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 10:35:33.554  2842  2858 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 10:35:33.554   283  1611 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
06-30 10:35:33.554   283  1611 V AudioFlinger: removeClient_l() pid 2019, calling pid 283
06-30 10:35:33.559  2019  2565 I HotwordRecognitionRnr: Stopping hotword detection.
06-30 10:35:33.563  2019  2569 I HotwordRecognitionRnr: Hotword detection finished
06-30 10:35:33.589  5650  5650 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
06-30 10:35:33.684  5650  5650 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
06-30 10:35:33.746  5650  5650 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 6796-6807)
06-30 10:35:33.746  5650  5650 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:33.766  5650  5650 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {57be840}
06-30 10:35:33.767  5650  5650 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:33.771  5650  5650 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 10:35:33.786  5650  5650 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 10:35:33.788  5650  5650 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:33.792  5650  5650 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 10:35:33.847  5650  5685 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
06-30 10:35:33.870  5650  5650 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-30 10:35:33.881  5650  5650 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:35:33.881  5650  5650 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:35:33.883  5650  5650 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:35:33.883  5650  5650 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:35:33.883  5650  5650 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 10:35:33.883  5650  5650 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 10:35:33.883  5650  5650 I Adreno-EGL: Remote Branch: 
06-30 10:35:33.883  5650  5650 I Adreno-EGL: Local Patches: 
06-30 10:35:33.883  5650  5650 I Adreno-EGL: Reconstruct Branch: 
06-30 10:35:34.003   283   283 V AudioPolicyService: registerClient() client 0xb3848b20, uid 10030
06-30 10:35:34.030   944  1050 D BluetoothManagerService: Message: 20
06-30 10:35:34.030   944  1050 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2088f31c:true
06-30 10:35:34.034  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:35:34.034  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:35:34.034  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:35:34.034  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:35:34.035  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:35:34.036   486   486 D charger_monitor: init target 500000
06-30 10:35:34.041   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:35:34.053  5650  5699 D BluetoothAdapter: 96661045: getState() :  mService = null. Returning STATE_OFF
06-30 10:35:34.084  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 301
06-30 10:35:34.085  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:35:34.085  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 301
06-30 10:35:34.087  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:35:34.088  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:35:34.089  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:35:34.089  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:35:34.089  1870  2037 D LEDHandler: Battery Temp: 301, mChargingStatus=5, mChargingStop=false
06-30 10:35:34.091   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:35:34.091  5466  5466 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 10:35:34.096  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:35:34.172  5650  5650 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:34.183  5650  5650 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 10:35:34.188  5650  5650 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-30 10:35:34.192  5650  5650 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
06-30 10:35:34.193  5650  5650 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
06-30 10:35:34.204  5650  5650 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
06-30 10:35:34.211  5650  5650 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:34.211  5650  5650 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:34.268  5650  5650 I Activity: Activity.onPostResume() called 
06-30 10:35:34.274  5650  5721 D OpenGLRenderer: Render dirty regions requested: true
06-30 10:35:34.278  5650  5721 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 10:35:34.285  5650  5721 D OpenGLRenderer: Enabling debug mode 0
06-30 10:35:34.300  5650  5650 D Atlas   : Validating map...
06-30 10:35:34.305   944  2189 D SplitWindow: check instance of lgWin Window{3ffd5b4c u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 10:35:34.312  5650  5697 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
06-30 10:35:34.341   944  2189 D InputDispatcher: Focus entered window: Window{3ffd5b4c u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 10:35:34.409   944  1051 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s87ms
06-30 10:35:34.412   944  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{68d79f2 u0 com.test.thalitest/.MainActivity t241} time:127470
06-30 10:35:34.413   944  1944 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
06-30 10:35:34.431  5650  5650 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b561a2b time:127492
06-30 10:35:34.536  5650  5650 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5650
06-30 10:35:34.683  5650  5650 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:35:35.051  5650  5724 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1623014144
,06-30 10:35:35.066  5650  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:35:35.066  5650  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:35:35.066  5650  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:35:35.066  5650  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:35:35.066  5650  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 10:35:35.066  5650  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38a0d6ff added. We now have 1 listener(s)
,06-30 10:35:35.071   944  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:35.078  5650  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,06-30 10:35:35.082  5650  5724 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
06-30 10:35:35.083  5650  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 10:35:35.083  5650  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 10:35:35.088  5650  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9226e2a added. We now have 1 listener(s)
06-30 10:35:35.088  5650  5724 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 10:35:35.099  5650  5724 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:35:35.099  5650  5724 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 10:35:35.111  5650  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 10:35:35.112  5650  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,06-30 10:35:35.112  5650  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:35:35.112  5650  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 10:35:35.117  5650  5724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 10:35:35.118   944   963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:35.118  5650  5724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
06-30 10:35:35.122  5650  5724 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:35.122  5650  5724 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:35:35.122  5650  5724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:35.122  5650  5724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:35.122  5650  5724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:35.122  5650  5724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:35.122  5650  5724 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:35.122  5650  5724 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:35.122  5650  5724 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:35.122  5650  5724 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:35:35.122  5650  5724 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:35:35.123  5650  5724 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 10:35:35.333  5650  5650 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:35:35.371  5650  5664 I art     : CheckpointMarkThreadRoots callback created = 0x99d89b90
,06-30 10:35:35.402  5650  5664 I art     : CheckpointMarkThreadRoots callback created = 0x99d89b60
,06-30 10:35:35.462   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:35:35.912  5650  5748 W jxcore-log: Initializing JXcore engine
06-30 10:35:35.912  5650  5748 W jxcore-log: JXcore engine is ready
,06-30 10:35:36.001  5748  5748 W Thread-664: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7671]" dev="sockfs" ino=7671 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 10:35:36.001  5748  5748 W Thread-664: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 10:35:36.001  5748  5748 W Thread-664: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5546]" dev="sockfs" ino=5546 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 10:35:36.001  5748  5748 W Thread-664: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
06-30 10:35:36.001  5748  5748 W Thread-664: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
06-30 10:35:36.001  5748  5748 W Thread-664: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[20304]" dev="sockfs" ino=20304 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,06-30 10:35:36.030  5650  5748 W jxcore-log: Starting JXcore engine
,06-30 10:35:36.162  5650  5748 W jxcore-log: Platform android
06-30 10:35:36.162  5650  5748 W jxcore-log: 
06-30 10:35:36.162  5650  5748 W jxcore-log: Process ARCH arm
06-30 10:35:36.162  5650  5748 W jxcore-log: 
,06-30 10:35:36.502  5650  5748 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:35:36.502  5650  5748 I jxcore-log: 
06-30 10:35:36.503  5650  5748 W jxcore-log: JXcore engine is started
,06-30 10:35:36.506  5650  5724 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 10:35:36.508  5650  5650 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
06-30 10:35:39.873   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:35:39.873   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:35:39.873   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 132934542141; DSPS: 4454635; Offset : -3013789489
,06-30 10:35:40.466   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:35:44.499  2842  2842 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,06-30 10:35:44.509  2842  2842 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
06-30 10:35:45.471   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:35:50.476   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:35:52.510  5650  5748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-30 10:35:52.510  5650  5748 I jxcore-log: 
06-30 10:35:52.514  5650  5748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-30 10:35:52.514  5650  5748 I jxcore-log: 
,06-30 10:35:52.517  5650  5748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:52.517  5650  5748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:35:52.517  5650  5748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:52.517  5650  5748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:52.517  5650  5748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:52.517  5650  5748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:52.517  5650  5748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:52.517  5650  5748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:52.517  5650  5748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:52.518  5650  5748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:52.518  5650  5748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 10:35:52.521  5650  5748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-30 10:35:52.521  5650  5748 I jxcore-log: 
06-30 10:35:52.523  5650  5748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-30 10:35:52.523  5650  5748 I jxcore-log: 
06-30 10:35:53.045  5650  5748 I jxcore-log: Unit Test app is loaded
06-30 10:35:53.045  5650  5748 I jxcore-log: 
,06-30 10:35:53.060  5650  5748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 10:35:53.060  5650  5748 I jxcore-log: 
,06-30 10:35:53.063  5650  5650 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
06-30 10:35:53.081   944  1355 D WifiServiceImplEx: setWifiEnabled: true pid=5650, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,06-30 10:35:53.098   944  1355 D WifiService: setWifiEnabled: true pid=5650, uid=10030
,06-30 10:35:53.124   944  1636 D WifiServiceImplEx: disconnect pid=5650, uid=10030, packageName=com.test.thalitest
06-30 10:35:53.125   944  1375 D WifiServiceImplEx: reconnect pid=5650, uid=10030, packageName=com.test.thalitest
06-30 10:35:53.127   944  1053 I PowerManagerService: ALS enabled for SRE
06-30 10:35:53.127   944  1053 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26189 ms ago)
06-30 10:35:53.132   944  2189 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,06-30 10:35:53.137   944  2189 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,06-30 10:35:53.164   944  1050 D BluetoothManagerService: Message: 1
06-30 10:35:53.164   944  1050 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
06-30 10:35:53.169  5650  5748 I jxcore-log: My device name is: LGE-LG-D722
06-30 10:35:53.169  5650  5748 I jxcore-log: 
06-30 10:35:53.186  2052  2052 D BluetoothAdapterService(367319230): onBind()
,06-30 10:35:53.191   944  1304 I LGFTMITEM: [GET_FTM][id=6], offset=12288
06-30 10:35:53.192   944  1345 D qdlights: set_light_backlight: 253
06-30 10:35:53.193   944  1345 D qdlights: set_light_backlight: 249
06-30 10:35:53.194   944  1304 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
06-30 10:35:53.197   944  1304 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
06-30 10:35:53.197   944  1304 E WifiHW  : band=b
06-30 10:35:53.197   944  1304 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
06-30 10:35:53.197   944   944 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
06-30 10:35:53.197   944  1050 D BluetoothManagerService: Message: 40
06-30 10:35:53.197   944  1050 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
06-30 10:35:53.201   944   944 D LocationManagerService: getAllProviders()=[passive, gps, network]
,06-30 10:35:53.202   944   944 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 10:35:53.210   944  1345 D qdlights: set_light_backlight: 246
06-30 10:35:53.211   278  1047 D SoftapController: Softap fwReload - Ok
06-30 10:35:53.212   944   944 D Ulp_jni : JNI:system_update. Event-4
,06-30 10:35:53.224   944  1345 D qdlights: set_light_backlight: 243
,06-30 10:35:53.232   944  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:35:53.232   944  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:35:53.240   278  1047 D CommandListener: Setting iface cfg
06-30 10:35:53.240   278  1047 D CommandListener: Trying to bring down wlan0
06-30 10:35:53.241   944  1345 D qdlights: set_light_backlight: 239
06-30 10:35:53.241   278  1047 D CommandListener: Clearing all IP addresses on wlan0
,06-30 10:35:53.247  2052  2068 I bluedroid: config_hci_snoop_log
06-30 10:35:53.251   944  1304 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
06-30 10:35:53.257   944  1304 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,06-30 10:35:53.258   944  1345 D qdlights: set_light_backlight: 236
06-30 10:35:53.264  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 10:35:53.265  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
06-30 10:35:53.267   944  1050 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
06-30 10:35:53.271   944  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,06-30 10:35:53.279   944  1345 D qdlights: set_light_backlight: 233
06-30 10:35:53.282  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:35:53.28 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 10:35:53.282  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
06-30 10:35:53.291   944  1345 D qdlights: set_light_backlight: 229
,06-30 10:35:53.309   944  1345 D qdlights: set_light_backlight: 226
06-30 10:35:53.311   944  1019 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5791 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
06-30 10:35:53.324   944  1345 D qdlights: set_light_backlight: 223
,06-30 10:35:53.327  2052  2067 V LGMDMManagerInternal: Create singleton instance
06-30 10:35:53.332   944   944 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
06-30 10:35:53.370  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,06-30 10:35:53.377   944  1345 D qdlights: set_light_backlight: 213
06-30 10:35:53.380  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:35:53.380  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
06-30 10:35:53.380  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
06-30 10:35:53.399  5786  5786 I wpa_supplicant: Successfully initialized wpa_supplicant
,06-30 10:35:53.408   944  1345 D qdlights: set_light_backlight: 209
06-30 10:35:53.409   944  1345 D qdlights: set_light_backlight: 206
06-30 10:35:53.424   944  1345 D qdlights: set_light_backlight: 203
,06-30 10:35:53.441   944  1345 D qdlights: set_light_backlight: 199
,06-30 10:35:53.454  5786  5786 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-30 10:35:53.454  5786  5786 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
06-30 10:35:53.457   944  1345 D qdlights: set_light_backlight: 196
06-30 10:35:53.464  2052  2067 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:53.465  2052  2067 D BluetoothAdapterService(367319230): enable() - Enable called with quiet mode status =  false
06-30 10:35:53.466  2052  2153 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
06-30 10:35:53.466  2052  2153 D BluetoothAdapterProperties: Setting state to 11
06-30 10:35:53.467  2052  2153 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,06-30 10:35:53.469  2052  2153 D BluetoothAdapterService(367319230): updateAdapterState() - Broadcasting state to 1 receivers.
06-30 10:35:53.470   944  1050 D BluetoothManagerService: Message: 60
06-30 10:35:53.471   944  1050 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
06-30 10:35:53.473   944  1050 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
06-30 10:35:53.474   944  1345 D qdlights: set_light_backlight: 193
06-30 10:35:53.476  2052  2153 D BluetoothAdapterService(367319230): processStart()
06-30 10:35:53.478  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 10:35:53.491   944  1345 D qdlights: set_light_backlight: 189
,06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: Unable to read settings
06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:35:53.493  2052  2153 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:53.496  2052  2153 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
06-30 10:35:53.496  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-30 10:35:53.496  2052  2153 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
06-30 10:35:53.497  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 10:35:53.497  2052  2153 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
06-30 10:35:53.497  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 10:35:53.498  2052  2153 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
06-30 10:35:53.498  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 10:35:53.498  2052  2153 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
06-30 10:35:53.499  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-30 10:35:53.499  2052  2153 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
06-30 10:35:53.500  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 10:35:53.501  2052  2153 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
06-30 10:35:53.501  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 10:35:53.502  2052  2153 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
06-30 10:35:53.502  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
06-30 10:35:53.503  2052  2153 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
,06-30 10:35:53.504  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 10:35:53.504  2052  2153 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
06-30 10:35:53.505  2052  2153 D BluetoothAdapterService(367319230): processStart() - Make Bond State Machine
06-30 10:35:53.507   944  1345 D qdlights: set_light_backlight: 186
06-30 10:35:53.514  2052  2153 D BluetoothBondStateMachine: make
06-30 10:35:53.523  2052  2153 D BluetoothAdapterService: setAdapterService() - set to: null
06-30 10:35:53.523  2052  2153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:53.523  2052  2153 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
06-30 10:35:53.524  2052  5809 I BluetoothBondStateMachine: StableState(): Entering Off State
06-30 10:35:53.524   944  1345 D qdlights: set_light_backlight: 183
06-30 10:35:53.529  2052  2153 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 10:35:53.529  2052  2153 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
06-30 10:35:53.529  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: Unable to read settings
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:35:53.530  2052  2153 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:53.530  2052  2153 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
06-30 10:35:53.530  2052  2153 D BluetoothAdapterService(367319230): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
,06-30 10:35:53.541   944  1345 D qdlights: set_light_backlight: 179
06-30 10:35:53.557   944  1345 D qdlights: set_light_backlight: 176
,06-30 10:35:53.569   944  1879 I ActivityManager: Process com.google.android.apps.docs (pid 5353) has died
,06-30 10:35:53.574   944  1345 D qdlights: set_light_backlight: 173
06-30 10:35:53.591   944  1345 D qdlights: set_light_backlight: 169
,06-30 10:35:53.607   944  1345 D qdlights: set_light_backlight: 166
,06-30 10:35:53.624   944  1345 D qdlights: set_light_backlight: 163
,06-30 10:35:53.641   944  1345 D qdlights: set_light_backlight: 159
,06-30 10:35:53.644   944   962 I ActivityManager: Process com.google.android.apps.plus (pid 5431) has died
06-30 10:35:53.651  1870  1870 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,06-30 10:35:53.657   944  1345 D qdlights: set_light_backlight: 156
06-30 10:35:53.658  2052  2153 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 10:35:53.659  2052  2153 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
06-30 10:35:53.659  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-30 10:35:53.659  2052  2153 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
06-30 10:35:53.659  2052  2153 D BluetoothAdapterService(367319230): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
06-30 10:35:53.666  2052  2067 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
,06-30 10:35:53.668  2052  2052 D HeadsetService: Received start request. Starting profile...
06-30 10:35:53.668  2052  2068 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:53.670  1775  1775 D BluetoothHeadset: Proxy object connected
06-30 10:35:53.670   944   944 D BluetoothHeadset: Proxy object connected
06-30 10:35:53.672  2052  2067 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:53.673  2052  2153 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 10:35:53.673  2052  2153 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
06-30 10:35:53.673  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 10:35:53.673  2052  2153 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
06-30 10:35:53.673  2052  2153 D BluetoothAdapterService(367319230): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
06-30 10:35:53.674   944  1345 D qdlights: set_light_backlight: 153
06-30 10:35:53.681  2052  2153 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 10:35:53.681  2052  2153 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
06-30 10:35:53.681  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 10:35:53.681  2052  2153 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
06-30 10:35:53.681  2052  2153 D BluetoothAdapterService(367319230): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
06-30 10:35:53.681  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
,06-30 10:35:53.686  2052  2052 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
06-30 10:35:53.691   944  1345 D qdlights: set_light_backlight: 149
06-30 10:35:53.694  1368  1368 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,06-30 10:35:53.699  2052  2153 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 10:35:53.699  2052  2153 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
06-30 10:35:53.699  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 10:35:53.700  2052  2153 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
06-30 10:35:53.700  2052  2153 D BluetoothAdapterService(367319230): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
06-30 10:35:53.708   944  1345 D qdlights: set_light_backlight: 146
,06-30 10:35:53.711  2052  2153 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 10:35:53.711  2052  2153 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
06-30 10:35:53.711  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-30 10:35:53.711  2052  2153 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
06-30 10:35:53.711  2052  2153 D BluetoothAdapterService(367319230): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
06-30 10:35:53.713  1775  1775 D BluetoothHeadset: Proxy object connected
06-30 10:35:53.718  2052  2153 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 10:35:53.718  2052  2153 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
06-30 10:35:53.718  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 10:35:53.718  2052  2153 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
06-30 10:35:53.719  2052  2153 D BluetoothAdapterService(367319230): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
06-30 10:35:53.721  1775  1775 D BluetoothHeadset: Proxy object connected
,06-30 10:35:53.722  2052  2052 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,06-30 10:35:53.722  2052  2052 I BluetoothHeadsetServiceJni: classInitNative: succeeds
06-30 10:35:53.725   944  1345 D qdlights: set_light_backlight: 143
06-30 10:35:53.727  2052  2153 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 10:35:53.727  2052  2153 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
06-30 10:35:53.727  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 10:35:53.727  2052  2153 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
06-30 10:35:53.727  2052  2153 D BluetoothAdapterService(367319230): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
06-30 10:35:53.728  2052  2052 D HeadsetStateMachine: make
06-30 10:35:53.744   944  1345 D qdlights: set_light_backlight: 139
,06-30 10:35:53.749  5791  5791 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:35:53.751  5791  5791 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,06-30 10:35:53.751  5791  5791 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:35:53.754  5791  5791 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 10:35:53.756  5791  5791 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
06-30 10:35:53.747  2052  2153 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 10:35:53.758  2052  2153 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
06-30 10:35:53.759  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
06-30 10:35:53.759  2052  2153 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
06-30 10:35:53.759  2052  2153 D BluetoothAdapterService(367319230): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
06-30 10:35:53.760   944  1345 D qdlights: set_light_backlight: 136
06-30 10:35:53.779   944  1345 D qdlights: set_light_backlight: 133
,06-30 10:35:53.787  2052  2052 D HeadsetStateMachine: max_hf_connections = 1
06-30 10:35:53.788  2052  2052 I bluedroid: get_profile_interface handsfree
06-30 10:35:53.791   944  1345 D qdlights: set_light_backlight: 129
,06-30 10:35:53.791  2052  2153 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 10:35:53.791  2052  2153 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
06-30 10:35:53.791  2052  2153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 10:35:53.792  2052  2153 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
06-30 10:35:53.792  2052  2153 D BluetoothAdapterService(367319230): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
06-30 10:35:53.792  2052  2052 I bt-btif : btif_hf_get_interface
06-30 10:35:53.792  2052  2052 I bt-btif : init
06-30 10:35:53.792  2052  2052 D bt-btif : max_hf_clients = 1
06-30 10:35:53.792  2052  2052 D bt-btif : btif_max_hf_clients = 1
06-30 10:35:53.792  2052  2052 D bt-btif : btif_enable_service: current services:0xa068c330
06-30 10:35:53.797  2052  2052 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
06-30 10:35:53.799   283  1611 V AudioPolicyService: registerClient() client 0xb4027380, uid 1002
06-30 10:35:53.799   283   283 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
06-30 10:35:53.800  2052  2153 V LGMDMManager: Create singleton instance
06-30 10:35:53.800   283   283 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 10:35:53.800   283   283 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 10:35:53.801   283  1317 V AudioFlinger: registerClient() client 0xb4033958, pid 2052
06-30 10:35:53.801   283  1317 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-30 10:35:53.801   283  1317 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-30 10:35:53.801   283  1317 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-30 10:35:53.801  2052  2052 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,06-30 10:35:53.802   283  1288 V AudioFlinger: thread 0xb5735000 type 0 TID 1288 waking up
06-30 10:35:53.802   283  1288 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 10:35:53.802   283  1288 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
06-30 10:35:53.803   283  1286 V AudioFlinger: thread 0xb56eb000 type 0 TID 1286 waking up
06-30 10:35:53.803   283  1286 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 10:35:53.803   283  1286 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
06-30 10:35:53.803   283  1285 V AudioFlinger: thread 0xb5651000 type 0 TID 1285 waking up
06-30 10:35:53.803   283  1285 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 10:35:53.803   283  1285 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
06-30 10:35:53.804   283  1285 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:53.804   283  1285 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:53.804  1775  2385 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:53.804  1368  2699 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:53.804  1775  2385 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:53.804   283  1285 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
06-30 10:35:53.804  3090  3106 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:53.804  3090  3106 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:53.805   944  1344 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:53.805   944  1344 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:53.805  1368  2699 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:53.805  2052  2067 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:53.805  2052  2067 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
06-30 10:35:53.805   283  1286 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:53.805   283  1286 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:53.805  1775  1805 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:53.805  1775  1805 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:53.805   283  1286 V AudioFlinger: processConfigEvents_l() DONE thread 0xb56eb000
06-30 10:35:53.805  3090  3107 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:53.805  3090  3107 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:53.805   944  1924 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:53.805   944  1924 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:53.806  2052  2052 V ToneGenerator: Create Track: 0xb4909480
06-30 10:35:53.806  2052  2052 V AudioTrack: set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
06-30 10:35:53.806  2052  2052 V AudioTrack: set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
06-30 10:35:53.806  1368  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:53.806  1368  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:53.806   283  1288 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 10:35:53.806   283  1288 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 10:35:53.806  2842  2860 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:53.806   283  1288 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5735000
06-30 10:35:53.806   944  1935 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 10:35:53.806   944  1935 V AudioSystem: ioConfigChanged() opening already e,xisting output! 6
06-30 10:35:53.805  2019  2043 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 10:35:53.806  2019  2043 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:53.807  1368  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 10:35:53.807  1368  1392 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 10:35:53.807  1775  1801 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 10:35:53.807  1775  1801 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 10:35:53.807  2052  2068 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:53.807  2052  2068 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
06-30 10:35:53.807  2842  2860 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 10:35:53.807   944  1345 D qdlights: set_light_backlight: 126
06-30 10:35:53.808  2052  2068 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 10:35:53.808  2052  2068 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
06-30 10:35:53.808  3090  3106 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 10:35:53.808  3090  3106 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 10:35:53.809  2842  2860 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:53.809  2842  2860 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:53.809  2019  2043 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 10:35:53.809  2019  2043 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 10:35:53.810  2019  2043 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 10:35:53.810  2019  2043 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 10:35:53.810  2842  2860 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 10:35:53.810  2842  2860 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 10:35:53.810   283  1611 I AudioFlinger: isAudioPlaybackHookOn() false
06-30 10:35:53.810  2052  2052 D AudioTrack: TrackOffload: AudioTrack Offload disabled by property, returning false
06-30 10:35:53.811   283   283 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-30 10:35:53.811   283   283 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
06-30 10:35:53.811   283   283 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 10:35:53.811   283   283 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 10:35:53.812  2052  2052 V AudioSystem: getLatency() output 2, latency 50
06-30 10:35:53.812  2052  2052 V AudioSystem: getFrameCount() output 2, frameCount 960
06-30 10:35:53.812  2052  2052 V AudioTrack: createTrack_l() output 2 afLatency 50
06-30 10:35:53.812  2052  2052 V AudioTrack: Create normal PCM 0x1 Track
06-30 10:35:53.813   283  1292 V AudioFlinger: createTrack() lSessionId: 22
06-30 10:35:53.813   283  1292 V AudioFlinger: AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
06-30 10:35:53.814   283  1292 V AudioFlinger: sendConfigEvent_l() num events 1 event 1
06-30 10:35:53.814   283  1285 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 10:35:53.815  2052  2052 V AudioTrack: Flags here  0x4 
06-30 10:35:53.815   283  1285 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
06-30 10:35:53.815  2052  2052 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
06-30 10:35:53.816   283  1611 V AudioFlinger: acquiring 22 from 2052, for 2052
06-30 10:35:53.816   283  1611 V AudioFlinger:  added new entry for 22
06-30 10:35:53.816  2052  2052 V ToneGenerator: ToneGenerator INIT OK, time: 146878
06-30 10:35:53.816  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:53.820  2052  5810 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
06-30 10:35:53.820  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:53.820  2052  5810 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 10:35:53.820  2052  5810 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 10:35:53.823  2052  2052 D A2dpService: Received start request. Starting profile...
06-30 10:35:53.824   944   944 D BluetoothA2dp: Proxy object connected
06-30 10:35:53.824  2052  5810 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
06-30 10:35:53.824  2052  2052 I BluetoothAvrcpServiceJni: classInitNative: succeeds
06-30 10:35:53.825  2052  2052 V Avrcp   : make
06-30 10:35:53.825  2052  2052 D Avrcp   : [BTUI] Use Native AVRCP : init jni
06-30 10:35:53.825  2052  2052 I bluedroid: get_profile_interface avrcp
06-30 10:35:53.826  2052  2153 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
06-30 10:35:53.827   944  1345 D qdlights: set_light_backlight: 123
06-30 10:35:53.827  2052  2052 I bt-btif : btif_rc_get_interface
06-30 10:35:53.827  2052  2052 I bt-btif : ## init ##
06-30 10:35:53.829   283  1317 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 2052
06-30 10:35:53.830  2052  2052 I LGBluetoothAvrcpServiceJni: classInitNative: succeeds
06-30 10:35:53.831   283  1317 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
06-30 10:35:53.831   283  1317 V voice   : voice_set_parameters: enter: bt_samplerate=8000
06-30 10:35:53.831   283  1317 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
06-30 10:35:53.831   283  1317 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-30 10:35:53.831   283  1317 V voice   : voice_set_parameters: exit with code(0)
06-30 10:35:53.831   283  1317 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
06-30 10:35:53.831   283  1317 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
06-30 10:35:53.832  2052  2068 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:53.832  2052  2052 I LGBluetoothAvrcpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
06-30 10:35:53.832  2052  2052 I LGBluetoothAvrcpServiceJni: initNative: succeeds
06-30 10:35:53.833   283  1317 V msm8974_platform: platform_set_parameters: exit with code(0)
06-30 10:35:53.833   283  1317 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-30 10:35:53.834   283  1317 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
06-30 10:35:53.834   283  1317 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-30 10:35:53.834  2052  5810 V ToneGenerator: ToneGenerator destructor
06-30 10:35:53.834  2052  5810 V ToneGenerator: stopTone
06-30 10:35:53.834  2052  5810 V ToneGenerator: Delete Track: 0xb4909480
06-30 10:35:53.834  2052  5810 V AudioTrack: ~AudioTrack, releasing session id from 2052 on behalf of 2052
06-30 10:35:53.835   283  1292 V AudioFlinger: releasing 22 from 2052 for 2052
06-30 10:35:53.835   283  1292 V AudioFlinger:  decremented refcount to 0
06-30 10:35:53.835   283  1292 V AudioFlinger: purging stale effects
06-30 10:35:53.835   283  1292 V AudioFlinger: remove track (4099) and delete from mixer
06-30 10:35:53.835   283  1292 V AudioPolicyService: AudioCommandThread() adding release output 2
06-30 10:35:53.835   283  1292 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
06-30 10:35:53.835   283  1292 V AudioFlinger: PlaybackThread::Track destructor
06-30 10:35:53.835   283  1292 V AudioFlinger: removeClient_l() pid 2052, calling pid 283
06-30 10:35:53.835  2052  2052 I BluetoothAvrcpBrcmAdapterJni: classInitBrcmNative
06-30 10:35:53.835   283  1063 V AudioPolicyService: AudioCommandThread() waking up
06-30 10:35:53.835   283  1063 V AudioPolicyService: AudioCommandThread() processing release output 2
06-30 10:35:53.835   283  1063 V AudioPolicyManager: releaseOutput() 2
06-30 10:35:53.835   283  1063 V AudioPolicyService: AudioCommandThread() going to sleep
,06-30 10:35:53.841   944  1345 D qdlights: set_light_backlight: 119
06-30 10:35:53.843  2052  2052 I BluetoothAvrcpBrcmAdapterJni: initBrcmNative
06-30 10:35:53.857   944  1345 D qdlights: set_light_backlight: 116
06-30 10:35:53.874   944  1345 D qdlights: set_light_backlight: 113
,06-30 10:35:53.891   944  1345 D qdlights: set_light_backlight: 109
,06-30 10:35:53.907   944  1345 D qdlights: set_light_backlight: 106
,06-30 10:35:53.924   944  1345 D qdlights: set_light_backlight: 103
,06-30 10:35:53.941   944  1345 D qdlights: set_light_backlight: 99
,06-30 10:35:53.958   944  1345 D qdlights: set_light_backlight: 96
,06-30 10:35:53.974   944  1345 D qdlights: set_light_backlight: 93
,06-30 10:35:53.986   944  1935 V AudioService: updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,06-30 10:35:53.990   944  1935 E AudioService: No RCC entry present to update
06-30 10:35:53.991  2052  2052 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
06-30 10:35:53.991   944  1345 D qdlights: set_light_backlight: 89
06-30 10:35:53.992  2052  2052 I BluetoothA2dpServiceJni: classInitNative
06-30 10:35:53.992  2052  2052 I BluetoothA2dpServiceJni: classInitNative: succeeds
06-30 10:35:53.992  2052  2052 D A2dpStateMachine: make
06-30 10:35:53.994  2052  2052 I bluedroid: get_profile_interface a2dp
06-30 10:35:53.994  2052  2052 I bt-btif : btif_av_get_src_interface
06-30 10:35:53.994  2052  2052 I bt-btif : init
06-30 10:35:53.994  2052  2052 D bt-btif : btif_enable_service: current services:0xa068c330
06-30 10:35:53.996  2052  2052 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
06-30 10:35:53.996  2052  2052 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
06-30 10:35:53.998  2052  2052 D LGBluetoothPowerControlManager: [BTUI] getInstance
06-30 10:35:53.999  2052  2052 D LGBluetoothPowerControlManager: [BTUI] init
,06-30 10:35:54.002  2052  2052 D LGBluetoothPowerControlManager: [BTUI] init : getProfileProxy
06-30 10:35:54.004   944  1050 D BluetoothManagerService: Message: 30
06-30 10:35:54.006  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:54.006  2052  5818 D A2dpStateMachine: Enter Disconnected: -2
06-30 10:35:54.007   944  1345 D qdlights: set_light_backlight: 86
06-30 10:35:54.008  2052  2052 I BluetoothHidServiceJni: classInitNative: succeeds
06-30 10:35:54.012  2052  2052 D HidService: Received start request. Starting profile...
06-30 10:35:54.012  2052  2052 I bluedroid: get_profile_interface hidhost
06-30 10:35:54.012  2052  2052 I bt-btif : btif_hh_get_interface
06-30 10:35:54.012  2052  2052 I bt-btif : init
06-30 10:35:54.012  2052  2052 D bt-btif : btif_enable_service: current services:0xa068c330
06-30 10:35:54.013  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:54.013  2052  2052 I BluetoothHealthServiceJni: classInitNative: succeeds
,06-30 10:35:54.024  2052  2052 D HealthService: Received start request. Starting profile...
06-30 10:35:54.024   944  1345 D qdlights: set_light_backlight: 83
06-30 10:35:54.026  2052  2052 I bluedroid: get_profile_interface health
06-30 10:35:54.026  2052  2052 I bt-btif : btif_hl_get_interface
06-30 10:35:54.026  2052  2052 I bt-btif : init
06-30 10:35:54.026  2052  2052 D bt-btif : Process name (droid.bluetooth)
06-30 10:35:54.026  2052  2052 D bt-btif : btif_hl_soc_thread_init
,06-30 10:35:54.029  2052  2052 D bt-btif : create_thread: entered
06-30 10:35:54.029  2052  2052 D bt-btif : create_thread: thread created successfully
06-30 10:35:54.029  2052  5820 D bt-btif : entered btif_hl_select_thread
06-30 10:35:54.029  2052  5820 D bt-btif : btif_hl_select_wakeup_init
06-30 10:35:54.029  2052  5820 D bt-btif : btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
06-30 10:35:54.029  2052  5820 D bt-btif : max_s=55 
06-30 10:35:54.029  2052  5820 D bt-btif : set curr_set = org_set 
06-30 10:35:54.029  2052  2052 I LGBluetoothHealthServiceJni: classInitNative: succeeds
06-30 10:35:54.030  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:54.034  2052  2052 I BluetoothPanServiceJni: classInitNative(L105): succeeds
06-30 10:35:54.041   944  1345 D qdlights: set_light_backlight: 79
,06-30 10:35:54.044  2052  2052 D PanService: Received start request. Starting profile...
06-30 10:35:54.044  2052  2052 D BluetoothPanServiceJni: initializeNative(L110): pan
06-30 10:35:54.044  2052  2052 I bluedroid: get_profile_interface pan
06-30 10:35:54.044  2052  2052 D bt-btif : stack_initialized = 0, btpan_cb.enabled:0
06-30 10:35:54.055  2052  2052 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
06-30 10:35:54.055  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:54.057  2052  2052 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,06-30 10:35:54.062  2052  2052 D BtGatt.DebugUtils: handleDebugAction() action=null
06-30 10:35:54.063  2052  2052 D BtGatt.GattService: Received start request. Starting profile...
06-30 10:35:54.063  2052  2052 D BtGatt.GattService: start()
06-30 10:35:54.063  2052  2052 I bluedroid: get_profile_interface gatt
06-30 10:35:54.063  2052  2052 D BtGatt.AdvertiseManager: advertise manager created
06-30 10:35:54.071  2052  2052 I LGBluetoothGattAdapter: [BTUI] getInstance : create [LGBluetoothGattAdapter]
06-30 10:35:54.071  2052  2052 D LGBluetoothGattAdapter: setGattService:  set to: null
06-30 10:35:54.071  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:54.074   944  1345 D qdlights: set_light_backlight: 73
06-30 10:35:54.074  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:54.075  2052  2052 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
06-30 10:35:54.076  2052  2052 V BluetoothMapService: BluetoothMapBinder()
,06-30 10:35:54.077  2052  2052 D BluetoothMapService: Received start request. Starting profile...
06-30 10:35:54.077  2052  2052 D BluetoothMapService: start()
06-30 10:35:54.083  2052  2052 D BluetoothMapEmailSettingsLoader: Found 0 applications
06-30 10:35:54.084  2052  2052 D BluetoothMapEmailAppObserver: createReceiver()
06-30 10:35:54.085  2052  2052 D BluetoothMapEmailAppObserver: initObservers()
06-30 10:35:54.085  2052  2052 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
06-30 10:35:54.092   944  1345 D qdlights: set_light_backlight: 69
06-30 10:35:54.094  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
,06-30 10:35:54.099  2052  2052 I BluetoothSAPServiceJni: classInitNative(L170): succeeds
06-30 10:35:54.102  2052  2052 D SapService: Received start request. Starting profile...
06-30 10:35:54.102  2052  2052 D BluetoothSAPServiceJni: initializeNative(L175): sap
06-30 10:35:54.102  2052  2052 I bluedroid: get_profile_interface sap
06-30 10:35:54.102  2052  2052 I bt-btif : btif_sc_get_interface
06-30 10:35:54.102  2052  2052 I bt-btif : init
06-30 10:35:54.102  2052  2052 D bt-btif : btif_enable_service: current services:0xa068c330
06-30 10:35:54.102  2052  2052 I LGBluetoothSapAdapter: [BTUI] getInstance : create [LGBluetoothSapAdapter]
06-30 10:35:54.103  2052  2052 I LGBluetoothSapAdapter: [BTUI] Create LGBluetoothSapManager Instance
06-30 10:35:54.105  2052  2052 D LGBluetoothSapManager: [BTUI] initSapManager
06-30 10:35:54.106  5791  5791 I IndexDatabaseHelper: Using schema version: 115
06-30 10:35:54.107   944  1345 D qdlights: set_light_backlight: 66
06-30 10:35:54.109  5791  5791 I IndexDatabaseHelper: Index is fine
,06-30 10:35:54.113  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:54.124   944  1345 D qdlights: set_light_backlight: 63
,06-30 10:35:54.126  2052  2052 V BluetoothFTPServiceJni: classInitNative
06-30 10:35:54.127  2052  2052 I BluetoothFTPServiceJni: classInitNative(L271): succeeds
06-30 10:35:54.127  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:54.128  2052  2052 D BluetoothFTPService: BluetoothFtpBinder()
,06-30 10:35:54.130  2052  2052 D **BluetoothFTPService: Received start request. Starting profile...
06-30 10:35:54.130  2052  2052 V BluetoothFTPService: FTP-Server Service start
06-30 10:35:54.134  2052  2052 D BluetoothFTPServiceJni: initFtpNativeDataNative(L275): FTP
06-30 10:35:54.134  2052  2052 I bluedroid: get_profile_interface ftp
06-30 10:35:54.134  2052  2052 I bt-btif : btif_fts_get_interface
06-30 10:35:54.134  2052  2052 I bt-btif : init
06-30 10:35:54.134  2052  2052 D bt-btif : btif_enable_service: current services:0xa068c330
06-30 10:35:54.134  2052  2052 D BluetoothFTPServiceJni: initFtpNativeDataNative(L317): FTP init done
06-30 10:35:54.134  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:54.134  2052  2052 D HeadsetStateMachine: Proxy object connected
06-30 10:35:54.135  2052  2052 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
06-30 10:35:54.136  2052  2052 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 10:35:54.136  2052  2052 E BluetoothOPPServiceJni: classInitNative
06-30 10:35:54.136  2052  2052 I BluetoothOPPServiceJni: classInitNative(L373): succeeds
06-30 10:35:54.137  2052  2052 V OppService: Opp initBinder
06-30 10:35:54.138  2052  2052 D **OppService: Received start request. Starting profile...
06-30 10:35:54.138  2052  2052 D OppService: Starting OppService 
06-30 10:35:54.139  2052  2052 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
06-30 10:35:54.141   944  1345 D qdlights: set_light_backlight: 59
,06-30 10:35:54.147  2052  2052 I NotificationManager: com.android.bluetooth: cancelAll by com.android.bluetooth
06-30 10:35:54.147  2052  2052 V BluetoothOppNotification: send message
06-30 10:35:54.154  2052  2052 D BluetoothOppPreference: Dumping Names:  
06-30 10:35:54.154  2052  2052 D BluetoothOppPreference: {}
06-30 10:35:54.155  2052  2052 D BluetoothOppPreference: Dumping Channels:  
06-30 10:35:54.155  2052  2052 D BluetoothOppPreference: {}
,06-30 10:35:54.156  2052  2052 D OppService: Start()
06-30 10:35:54.156  2052  2052 W BluetoothOPPServiceJni: initOppNative
06-30 10:35:54.156  2052  2052 D BluetoothOPPServiceJni: initOppNative(L383): OPP
06-30 10:35:54.156  2052  2052 I bluedroid: get_profile_interface opp
06-30 10:35:54.156  2052  2052 I bt-btif : btif_op_get_interface
06-30 10:35:54.156  2052  2052 D BluetoothOPPServiceJni: initOppNative(L411): mOppCallbacksObj 2098430
06-30 10:35:54.156  2052  2052 D BluetoothOPPServiceJni: initOppNative(L413): calling OPP init
06-30 10:35:54.156  1775  1775 D LgeBluetoothSimManager: [BTUI] SAP_ENABLE_EVT
06-30 10:35:54.157  2052  2052 I bt-btif : btif_opp_init
06-30 10:35:54.157  2052  2052 D bt-btif : btif_enable_service: current services:0xa068c330
06-30 10:35:54.157  2052  2052 D BluetoothOPPServiceJni: initOppNative(L429): OPC and OPS init Succesful
06-30 10:35:54.157  2052  2052 D BluetoothOPPServiceJni: initOppNative(L430): mOppCallbacksObj 2098430
06-30 10:35:54.158  2052  2052 V OppService: setOppService(): set to: com.broadcom.bt.service.opp.OppService@3b6f1394
06-30 10:35:54.158  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:54.158   944  1345 D qdlights: set_light_backlight: 56
06-30 10:35:54.159  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:35:54.159  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - Message: 1
06-30 10:35:54.159  2052  5810 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-30 10:35:54.159  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 10:35:54.160  2052  2052 D BluetoothAdapterService(367319230): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
06-30 10:35:54.160  2052  5810 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-30 10:35:54.160  2052  2052 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 10:35:54.160  2052  2052 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 10:35:54.160  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 10:35:54.160  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 10:35:54.160  2052  2052 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 10:35:54.164  2052  2052 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 10:35:54.164  2052  2052 D BluetoothA2dp: Proxy object connected
06-30 10:35:54.164  2052  2052 D LGBluetoothPowerControlManager: [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@1eba9e3d
06-30 10:35:54.164  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - Message: 1
06-30 10:35:54.164  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 10:35:54.164  2052  2052 D BluetoothAdapterService(367319230): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
06-30 10:35:54.164  2052  2052 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 10:35:54.164  2052  2052 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 10:35:54.164  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 10:35:54.164  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 10:35:54.164  2052  2052 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 10:35:54.168  2052  2052 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 10:35:54.168  2052  2052 D BluetoothAdap,terService(367319230): handleMessage() - Message: 1
06-30 10:35:54.168  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 10:35:54.168  2052  2052 D BluetoothAdapterService(367319230): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
06-30 10:35:54.168  2052  2052 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 10:35:54.168  2052  2052 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 10:35:54.168  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 10:35:54.168  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 10:35:54.168  2052  2052 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,06-30 10:35:54.171  2052  2052 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 10:35:54.171  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - Message: 1
06-30 10:35:54.171  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 10:35:54.171  2052  2052 D BluetoothAdapterService(367319230): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
06-30 10:35:54.172  2052  2052 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 10:35:54.172  2052  2052 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 10:35:54.172  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 10:35:54.172  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 10:35:54.172  2052  2052 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 10:35:54.175   944  1345 D qdlights: set_light_backlight: 53
06-30 10:35:54.176  2052  2052 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 10:35:54.176  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - Message: 1
06-30 10:35:54.176  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 10:35:54.176  2052  2052 D BluetoothAdapterService(367319230): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
06-30 10:35:54.176  2052  2052 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 10:35:54.176  2052  2052 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 10:35:54.176  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 10:35:54.176  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 10:35:54.176  2052  2052 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 10:35:54.179  2052  2052 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 10:35:54.179  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - Message: 1
06-30 10:35:54.179  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 10:35:54.179  2052  2052 D BluetoothAdapterService(367319230): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
06-30 10:35:54.179  2052  2052 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 10:35:54.179  2052  2052 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 10:35:54.179  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 10:35:54.179  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 10:35:54.179  2052  2052 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 10:35:54.182  2052  2052 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 10:35:54.182  2052  2052 V BluetoothMapService: Handler(): got msg=1
06-30 10:35:54.183  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - Message: 1
06-30 10:35:54.183  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 10:35:54.183  2052  2052 D BluetoothAdapterService(367319230): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
06-30 10:35:54.183  2052  2052 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 10:35:54.183  2052  2052 D BluetoothAdapterState: isTurningOf,fRadio()=false
06-30 10:35:54.183  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 10:35:54.183  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 10:35:54.183  2052  2052 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,06-30 10:35:54.185  2052  2052 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 10:35:54.185  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - Message: 1
06-30 10:35:54.185  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 10:35:54.186  2052  2052 D BluetoothAdapterService(367319230): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
06-30 10:35:54.186  2052  2052 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 10:35:54.186  2052  2052 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 10:35:54.186  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 10:35:54.186  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 10:35:54.186  2052  2052 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 10:35:54.187  2052  5827 V OppService: Deleted complete outbound shares, number =  0
06-30 10:35:54.188  2052  2052 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 10:35:54.188  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - Message: 1
06-30 10:35:54.188  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 10:35:54.188  2052  2052 D BluetoothAdapterService(367319230): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
06-30 10:35:54.188  2052  2052 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 10:35:54.188  2052  2052 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 10:35:54.188  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 10:35:54.188  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 10:35:54.188  2052  2052 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 10:35:54.189  2052  5830 V OppService: pendingUpdate is :  true
06-30 10:35:54.190  2052  5830 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-30 10:35:54.191   944  1345 D qdlights: set_light_backlight: 49
06-30 10:35:54.192  2052  2052 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 10:35:54.192  2052  5830 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30f3d500 on behalf of 
06-30 10:35:54.192  2052  2052 V PanService: [BTUI] SIM Extra State :ABSENT
06-30 10:35:54.193  2052  2052 V BluetoothOppNotification: new notify threadi!
06-30 10:35:54.193  2052  5827 V OppService: Deleted complete inbound failed shares, number = 0
06-30 10:35:54.193  2052  5827 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
06-30 10:35:54.193  2052  2052 V BluetoothOppNotification: send delay message
06-30 10:35:54.193  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - Message: 1
06-30 10:35:54.193  2052  2052 D BluetoothAdapterService(367319230): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 10:35:54.193  2052  2052 D BluetoothAdapterService(367319230): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
06-30 10:35:54.193  2052  2052 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 10:35:54.194  2052  2052 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 10:35:54.194  2052  2052 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 10:35:54.194  2052  2052 D BluetoothAdapterState: i,sQuietModeServiceTurningOff()=false
06-30 10:35:54.194  2052  2052 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 10:35:54.194  2052  2052 D BluetoothAdapterService(367319230): onProfileServiceStateChange() - All profile services started.
06-30 10:35:54.194  2052  2052 V OppService: ContentObserver received notification
06-30 10:35:54.194  2052  2052 V OppService: ContentObserver received notification
06-30 10:35:54.194  2052  5827 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20b7e139 on behalf of 
06-30 10:35:54.194  2052  2153 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
06-30 10:35:54.194  2052  2153 I bluedroid: enable
06-30 10:35:54.194  2052  2153 I bt-btif : BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
06-30 10:35:54.194  2052  2153 E bt-btu  : VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
06-30 10:35:54.195  2052  5831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,06-30 10:35:54.198  2052  2153 I bt_hci_bdroid: init
06-30 10:35:54.198  2052  2153 I bt_vendor: init
06-30 10:35:54.198  2052  2153 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
06-30 10:35:54.199  2052  5832 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
06-30 10:35:54.199  2052  5832 I bt-btu  : btu_task pending for preload complete event
06-30 10:35:54.200  2052  2153 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
06-30 10:35:54.201  2052  2153 I bt-btif : libbt-hci init returns 0
06-30 10:35:54.209   944  1345 D qdlights: set_light_backlight: 46
06-30 10:35:54.210  2052  5831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2000737e on behalf of 
06-30 10:35:54.211  2052  5830 V OppService: pendingUpdate is :  true
06-30 10:35:54.211  2052  5830 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-30 10:35:54.212  2052  5830 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14d5c0df on behalf of 
06-30 10:35:54.213  2052  5831 V BluetoothOppNotification: mUpdateCompleteNotification = true
06-30 10:35:54.214  2052  5831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-30 10:35:54.215  2052  5830 V BluetoothOppNotification: update too frequent, put in queue
06-30 10:35:54.217  2052  5831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b41412c on behalf of 
06-30 10:35:54.217  2052  5830 V OppService: pendingUpdate is :  false
06-30 10:35:54.217  2052  5830 E OppService: UpdateThread is Completed
,06-30 10:35:54.219  2052  5831 V BluetoothOppNotification: outbound: succ-0  fail-0
06-30 10:35:54.224   944  1345 D qdlights: set_light_backlight: 43
06-30 10:35:54.225  2052  5831 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
06-30 10:35:54.228  2052  5831 V BluetoothOppNotification: outbound notification was removed.
06-30 10:35:54.229  2052  5831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,06-30 10:35:54.230  2052  5831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ac57f5 on behalf of 
06-30 10:35:54.231  2052  5831 V BluetoothOppNotification: inbound: succ-0  fail-0
06-30 10:35:54.238  2052  5831 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
06-30 10:35:54.239  2052  5831 V BluetoothOppNotification: inbound notification was removed.
06-30 10:35:54.239  2052  5831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
06-30 10:35:54.240  2052  5831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8ac498a on behalf of 
06-30 10:35:54.242   944  1345 D qdlights: set_light_backlight: 39
,06-30 10:35:54.258   944  1345 D qdlights: set_light_backlight: 36
,06-30 10:35:54.274   944  1345 D qdlights: set_light_backlight: 33
,06-30 10:35:54.287  2052  5834 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,06-30 10:35:54.291   944  1345 D qdlights: set_light_backlight: 29
06-30 10:35:54.292  2052  5834 D bt_userial_vendor: userial_vendor_open():UART is setup
06-30 10:35:54.292  2052  5834 I bt_userial_vendor: device fd = 67 open
06-30 10:35:54.303  2052  5834 D bt_hwcfg: hw_config_cback opcode:0x0c03
06-30 10:35:54.303  2052  5834 D bt_hwcfg: hw_config_cback state=1
,06-30 10:35:54.307   944  1345 D qdlights: set_light_backlight: 26
06-30 10:35:54.322  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-30 10:35:54.327   944  1345 D qdlights: set_light_backlight: 23
06-30 10:35:54.330  2052  5834 D bt_hwcfg: hw_config_cback opcode:0x0c14
06-30 10:35:54.331  2052  5834 D bt_hwcfg: hw_config_cback state=4
06-30 10:35:54.331  2052  5834 D bt_hwcfg: Chipset Name: BCM4334B0
06-30 10:35:54.331  2052  5834 D bt_hwcfg: Chipset BCM4334B0
06-30 10:35:54.331  2052  5834 D bt_hwcfg: Target name = [BCM4334B0]
06-30 10:35:54.331  2052  5834 I bt_hwcfg: Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
06-30 10:35:54.337  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc45
06-30 10:35:54.337  2052  5834 D bt_hwcfg: hw_config_cback state=2
,06-30 10:35:54.341   944  1345 D qdlights: set_light_backlight: 19
,06-30 10:35:54.343  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc18
06-30 10:35:54.343  2052  5834 D bt_hwcfg: hw_config_cback state=3
06-30 10:35:54.343  2052  5834 I bt_hwcfg: bt vendor lib: set UART baud 4000000
06-30 10:35:54.357   944  1345 D qdlights: set_light_backlight: 16
,06-30 10:35:54.376  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc2e
,06-30 10:35:54.376  2052  5834 D bt_hwcfg: hw_config_cback state=5
,06-30 10:35:54.378   944  1345 D qdlights: set_light_backlight: 13
06-30 10:35:54.385  5791  5791 D WiFiOffLoadUpdatePriority: remove : truetruefalse
,06-30 10:35:54.391  5791  5791 D WiFiOffLoadUpdatePriority: remove2
06-30 10:35:54.392  5791  5791 V WiFiOffLoadSharedPrefsUtils: save wifi state
06-30 10:35:54.392  5791  5791 V WiFiOffLoadSharedPrefsUtils: save remove
,06-30 10:35:54.392  5791  5791 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
06-30 10:35:54.392   944  1345 D qdlights: set_light_backlight: 10
06-30 10:35:54.393  5791  5791 D WiFiOffLoadBroadcast: S: false, R: true
06-30 10:35:54.429  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.429  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.430  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.430  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.431  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.431  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.432  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.432  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.433  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.433  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.434  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.435  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.436  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.436  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.437  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.437  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.438  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.438  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.439  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.439  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.439  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.440  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.441  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.441  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.443  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.443  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.444  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.444  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.446  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.446  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.447  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 10:35:54.447  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.449  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.449  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.450  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.450  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.450   944  1988 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5838 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
06-30 10:35:54.452  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 10:35:54.452  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.453  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.453  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.454  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.455  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.456  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.456  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.457  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.457  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.458  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.458  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.460  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.460  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.461  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.461  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.463  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.463  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.464  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.464  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.465  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.465  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.467  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.467  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.468  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.468  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.469  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.469  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.471  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.471  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.472  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.472  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.474  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.474  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.475  2052  2052 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 10:35:54.477  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.477  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.477  2052  2052 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:54.477  2052  2052 V BluetoothPbapReceiver: ***********state = 11
06-30 10:35:54.477   278  1040 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-30 10:35:54.479   278  1040 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-30 10:35:54.480  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.480  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.482  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.482  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.483  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.483  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.484  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.484  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.486  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.486  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.487  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.487  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.488  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.488  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.489  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.489  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.490  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.490  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.491  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.491  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.492  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.492  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.493  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.493  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.494  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.494  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.494  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.494  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.495  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.495  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.496  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.496  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.497  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.497  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.498  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.498  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.499  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.499  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.500  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.500  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.501  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.501  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.501   944  1050 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
06-30 10:35:54.502  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.502  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.503  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.503  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.504  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.504  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.505  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.505  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.506   944  1300 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:35:54.506   944  1300 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:35:54.506   944  1300 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:35:54.506   944  1300 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:35:54.507   278  1042 E BandwidthController: [LG DATA] No such appUid: 1000
06-30 10:35:54.507   278  1042 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-30 10:35:54.507  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.507  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.507   278  5853 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
06-30 10:35:54.508  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.508  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.508   278  5853 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:35:54.508  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.508  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.509   278  5853 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
06-30 10:35:54.509   944  1048 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
06-30 10:35:54.510  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.510  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.511  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.511  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.512  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.512  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.512  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.512  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.513  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.513  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.514  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.514  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.516  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.516  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.518  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.518  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.518  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.518  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.519  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.519  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.520  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.520  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.521  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.521  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.522  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.522  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.523  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.523  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.523  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.523  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.525  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.525  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.525  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.526  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.526  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 10:35:54.526  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.529  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.529  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.529  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.529  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.530  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.530  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.530  5791  5791 D BluetoothPermissionRequest: onReceive
06-30 10:35:54.531  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.531  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.532   944  1301 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:35:54.532   944  1301 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:35:54.532  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.532  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.533  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.533  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.533  5791  5791 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
06-30 10:35:54.534  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.534  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.535  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.535  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.536  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.536  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.537  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.537  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.538  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.538  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.539  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.539  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.541  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.541  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.541  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.541  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.542  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.542  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.543  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.543  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.544  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.544  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.545  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.545  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.546  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.546  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.547  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.547  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.548  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.548  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.549  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.550  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.550  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.550  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.551  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.551  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.552  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.552  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.553  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.553  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.554  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.555  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.558  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.558  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.559  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.559  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.560  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.560  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.561  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.561  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.562  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.562  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.563  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.563  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.564  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.564  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.566  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.566  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.567  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.567  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.568  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.568  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.569  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.569  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.571  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.571  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.572  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.572  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.573  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.573  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.574  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.574  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.575  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.575  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.575  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.575  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.576  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.576  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.577  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.577  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.578  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.578  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.580  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.580  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.581   944  1050 D BluetoothManagerService: Message: 20
06-30 10:35:54.581  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.581   944  1050 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e3b83c:true
06-30 10:35:54.581  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.582  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.582  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.583  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.583  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.585  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.585  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.586  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.586  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.587  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.587  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.588  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.588  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.589  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.589  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.590  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.590  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.591  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.591  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.592  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.592  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.593  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.593  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.594  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.594  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.594  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.594  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.595  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.595  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.596  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.596  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.597  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.597  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.598  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.598  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.599  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.599  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.600  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.600  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.601  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.601  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.602  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.602  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.603  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.603  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.604  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.604  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.605  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.605  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.605  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.605  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.606  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.606  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.607  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.607  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.609  2052  2052 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 10:35:54.611  2052  2052 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:54.608  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.612  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.612  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.613  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.618  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 10:35:54.618  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.619  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.619  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.621  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.621  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.622  5786  5786 E wpa_supplicant: USIM:  scard_init function
06-30 10:35:54.623  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.623  5786  5786 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-30 10:35:54.623  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.625   278  1040 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
06-30 10:35:54.625   278  1040 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
06-30 10:35:54.625   278  1040 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
06-30 10:35:54.627  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.627  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.628  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.628  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.628  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.628  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.629  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.629  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.630  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.630  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.630  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.630  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.631   944  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:35:54.631   944  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:35:54.631  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.631  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.631  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.631  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.633  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.633  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.636  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.637  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.637  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.637  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.638  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.638  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.638  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.638  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.639  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.639  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.640  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.640  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.641  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.641  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.642  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.642  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.642  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.642  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.643  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.643  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.643  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.643  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.644  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.644  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.644  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.644  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.645  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.645  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.645  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.645  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.646  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.646  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.646  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.646  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.647  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.647  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.647  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.648  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.648  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.648  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.650  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.650  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.650  5838  5838 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 10:35:54.651  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.651  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.651  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.651  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.652  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.652  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.652  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.652  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.653  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.653  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.654  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.654  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.655  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.656  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.656  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.657  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.657  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.658  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.658  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.658  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.659  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.659  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.660  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.660  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.662  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.662  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.662  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.663   944  1924 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5859 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
06-30 10:35:54.663  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.663  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.663  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.664  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.664  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.665  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.665  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.665  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.666  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.666  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.666  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.667  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.667  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.668  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.668  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.669  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.669  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.670  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.670  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.670  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.670  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.671  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.671  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.672  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.673  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.674  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.674  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.674  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.674  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.675  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.675  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.676  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.676  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.677  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.677  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.678  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.678  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.682  5786  5786 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,06-30 10:35:54.686  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.686  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.687  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.687  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.688  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.688  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.689  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.689  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.690  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.690  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.691  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.691  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.692  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.692  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.693  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.693  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.694  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 10:35:54.694  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.694  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.695  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.696  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.696  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.697  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.697  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.698  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.698  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.699  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.699  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.699  5786  5786 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
06-30 10:35:54.700  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.700  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.701  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.701  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.702  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.702  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.703  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.703  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.704  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.704  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.704  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.705  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.705  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.705  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.707  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.707  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.707  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.707  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.708  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.708  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.709  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.709  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.710  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.710  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.711  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.711  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.712  5791  5791 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 10:35:54.712  5791  5791 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 10:35:54.712  5791  5791 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 10:35:54.713  5791  5791 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 10:35:54.713  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.713  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.714  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.714  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.714  5791  5791 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-30 10:35:54.715  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.715  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.717  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.717  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.719  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.719  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.720  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.720  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.721  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.721  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.722  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.722  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.723  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.723  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.724  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.724  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.725  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.725  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.726  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.726  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.727  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.727  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.728  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.728  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.729   944  1304 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
,06-30 10:35:54.729  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.729  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.731  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.731  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.732  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.732  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.734  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.734  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.735  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.735  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.736  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.736  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.737  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.737  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.738  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.738  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.738  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.738  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.739  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.739  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.740   944  1304 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,06-30 10:35:54.740  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.741  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.744   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:54.744  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.744  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.744   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:35:54.746  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.746  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.747  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.747  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.748  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.748  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
06-30 10:35:54.748  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.748  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:35:54.748 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 10:35:54.748  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
06-30 10:35:54.749  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.749  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.749   944   944 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
06-30 10:35:54.749  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.750  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.750  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.750  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.751  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:54.751  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 10:35:54.751  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:54.751  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:54.751  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 10:35:54.751  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:54.751  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:54.751  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:54.751  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:54.751  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.751  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.751  5650  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:54.751  5650  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 10:35:54.753  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.753  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.753  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.753  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.753  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:35:54.754  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:35:54.754  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.754  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.754  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:35:54.755  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
06-30 10:35:54.755  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.755  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.755   944  1308 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
06-30 10:35:54.756  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.756  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.757  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.757  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.758  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.758  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.758   944   944 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
06-30 10:35:54.759  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.759  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.760  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.760  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.760  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.760  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.761  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.761  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.762  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.762  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.763  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.763  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.764  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.764  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.765  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.765  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.766  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.766  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.767  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.767  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.768  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.768  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.769  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.769  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.770  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.770  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.771  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.771  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.771  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.771  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.772  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.772  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.773  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.773  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.774  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.774  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.776  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.776  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.777  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.777  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.778  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.778  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.779  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.779  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.781  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.781  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.782  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.782  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.783  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.783  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.784  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.784  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.786  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.786  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.787  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.787  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.788  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.788  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.790  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.790  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.791  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.791  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.791  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.791  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.791  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.791  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.792   944  1304 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,06-30 10:35:54.792  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.792  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.792  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.793  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.793  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.793  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.794  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.794  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.794   944  1304 D WifiStateMachine: enableVerboseLogging : level 2
06-30 10:35:54.795  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.795  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.795  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.795  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.796  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.796  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.796  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.796  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.797  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 10:35:54.797  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.797  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.797  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.798  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.798  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.799  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.799  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.799   944  1304 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 10:35:54.799  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.799  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.800  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.800   944  1304 D WifiNative-HAL: Setting external_sim to 1
06-30 10:35:54.800  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.800  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.800  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.800   944  1304 I WifiNative-HAL: startHal
06-30 10:35:54.800   944  1304 E wifi    : getStaticLongField sWifiHalHandle 0x9b5368ec
06-30 10:35:54.800   944  1304 I WifiHAL : Initializing wifi
06-30 10:35:54.800   944  1304 I WifiHAL : Creating socket
06-30 10:35:54.800  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.800  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.801  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.801  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.801  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.801  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.802  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.802  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.802  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.802  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.803   944  1304 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
06-30 10:35:54.803   944  1304 D wifi    : Did set static halHandle = 0x9d926740
06-30 10:35:54.803  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.803  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.803  5493  5493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:54.804  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.804  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.804  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.804  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.805  1870  1870 D WfdsService: Supplicant Connection state is changed : true
06-30 10:35:54.805  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.805  2052  5834 D bt_hwcfg: hw_config_cback state=6
,06-30 10:35:54.806  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.806  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.806  1870  2135 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
06-30 10:35:54.807  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.807  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.807  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.807  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.808  1870  2135 D WfdsService: Set the WFDS Monitor: true
06-30 10:35:54.808  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.808  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.808   944  1304 D wifi    : halHandle = 0x9d926740, mVM = 0xb487c280, mCls = 0x500dce
06-30 10:35:54.808   944  1304 E wifi    : getStaticLongField sWifiHalHandle 0x9b53689c
06-30 10:35:54.808   944  1304 D wifi    : array field set
06-30 10:35:54.809   944  1304 I WifiNative-HAL: interface[0] = wlan0
06-30 10:35:54.809   944  1304 I WifiNative-HAL: interface[1] = p2p0
06-30 10:35:54.809  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.809  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.809  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.809  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.810   944  1304 D wifi    : setting scan oui 0x8fa3be08
06-30 10:35:54.810   944  1304 D WifiHAL : Sending mac address OUI
06-30 10:35:54.810  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.810  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.810   944  1304 E WifiHAL : failed to set scanning mac OUI; result = -95
06-30 10:35:54.810   944  1304 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 10:35:54.810   944  1304 I WifiNative-HAL: startHal
06-30 10:35:54.810   944  1304 D wifi    : setting scan oui 0x8fa3be08
06-30 10:35:54.810   944  1304 D WifiHAL : Sending mac address OUI
06-30 10:35:54.810  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.810   944  1304 E WifiHAL : failed to set scanning mac OUI; result = -95
06-30 10:35:54.810  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.811  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 10:35:54.811  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.811  5859  5859 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:35:54.811  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc4e
06-30 10:35:54.811  2052  5834 D bt_hwcfg: hw_config_cback state=6
06-30 10:35:54.815  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,06-30 10:35:54.817   944   944 D WifiHS20: hidePasspointNotification off =false
06-30 10:35:54.822  1870  2135 D WfdsMonitor: WfdsMonitorThread create
06-30 10:35:54.824   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:54.824   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:54.825  1870  2135 D WfdsMonitor: WFDS Monitor is created and started
06-30 10:35:54.825  1870  2135 D WfdsService: WiFi: Supplicant connection re-established
06-30 10:35:54.826   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 10:35:54.826   944   944 D WifiScanningService: SCAN_AVAILABLE : 3
06-30 10:35:54.826   944   944 D RttService: SCAN_AVAILABLE : 3
06-30 10:35:54.827  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:54.827   944  1302 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.828   944  1302 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:35:54.828   944  1302 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:35:54.829  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:35:54.828 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 10:35:54.829   278  1047 D CommandListener: Setting iface cfg
06-30 10:35:54.829   278  1047 D CommandListener: Trying to bring up p2p0
06-30 10:35:54.829  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 10:35:54.832   944  5879 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1651349696
06-30 10:35:54.832   944  5879 D wifi    : waitForHalEvents called, vm = 0xb487c280, obj = 0x500dce, env = 0xaaefe900
06-30 10:35:54.832   944  5879 E wifi    : getStaticLongField sWifiHalHandle 0x99471b2c
06-30 10:35:54.832   944  1324 D WifiScanningService: DefaultState got{ when=-6ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.832   944  1324 I WifiNative-HAL: startHal
06-30 10:35:54.833   944  1325 D RttService: DefaultState got{ when=-7ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.835   944  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-30 10:35:54.835   944  1302 D LGWifiP2pService: P2pEnablingState
06-30 10:35:54.835   944  1302 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.835   944  1302 D LGWifiP2pService: P2p socket connection successful
06-30 10:35:54.835   944  1302 D LGWifiP2pService: P2pEnabledState
06-30 10:35:54.836   944  1324 D wifi    : getting scan capabilities on interface[0] = 0x8fa3be08
06-30 10:35:54.836   944  1324 D WifiHAL : Creating message to get scan capablities; iface = 24
06-30 10:35:54.836   944  1324 D wifi    : failed to get capabilities : -95
06-30 10:35:54.836   944  1324 E WifiScanningService: could not get scan capabilities
06-30 10:35:54.836   944  1304 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
06-30 10:35:54.836  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:35:54.837  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:35:54.837  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:35:54.837  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:35:54.837  1870  5880 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
06-30 10:35:54.838   944  1304 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
06-30 10:35:54.838  1870  5880 E CtrlSupplicant: Succeed to open control connection
06-30 10:35:54.838  1870  5880 E CtrlSupplicant: Succeed to open monitor connection
06-30 10:35:54.839  1870  5880 D WfdsMonitor: Supplicant connection established
06-30 10:35:54.840  1870  2135 D WfdsService: Connected to the supplicant for wfds
06-30 10:35:54.840  5786  5786 E wpa_supplicant: nWIFIDualbandAPConnection: 1
06-30 10:35:54.841  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:35:54.841  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
06-30 10:35:54.842   944  1304 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
06-30 10:35:54.842  5786  5786 E wpa_supplicant: disconnect_rssi_lvl: -100
,06-30 10:35:54.845   944  1302 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
06-30 10:35:54.846   944  1302 D LGWifiP2pService: before postfix = G3s-1
06-30 10:35:54.846   944  1302 D WifiServerServiceExt: postfix byte check : 5
06-30 10:35:54.846   944  1302 D LGWifiP2pService: after postfix = G3s-1
06-30 10:35:54.847   944  1304 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
06-30 10:35:54.847  5786  5786 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
06-30 10:35:54.849   944  1302 D WifiNative-HAL: p2pGetDeviceAddress
06-30 10:35:54.849   944  1304 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
06-30 10:35:54.850   944  1302 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
06-30 10:35:54.850  5791  5791 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-30 10:35:54.851  5791  5791 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
06-30 10:35:54.851  5791  5791 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 10:35:54.851  5791  5791 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 10:35:54.851  5791  5791 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-30 10:35:54.851  5791  5791 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
06-30 10:35:54.851  5791  5791 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-30 10:35:54.854  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-30 10:35:54.855   944  1302 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
,06-30 10:35:54.858  1870  1870 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
06-30 10:35:54.862  5791  5791 D WiFiOffLoadUpdatePriority: remove : truetruetrue
06-30 10:35:54.865  1870  1870 D WfdsService: Update P2p Interface State: 3
,06-30 10:35:54.870  5859  5859 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
06-30 10:35:54.873  5786  5786 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-30 10:35:54.875  5786  5786 I wpa_supplicant: [LGE_PATCH]scan interval[0] = 2 sec.
06-30 10:35:54.876  1870  5880 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
06-30 10:35:54.877  1870  5880 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
06-30 10:35:54.893  2404  2404 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,06-30 10:35:54.911  2052  5834 I bt_hwcfg: bt vendor lib: set UART baud 115200
06-30 10:35:54.912  2052  5834 D bt_hwcfg: Settlement delay -- 100 ms
06-30 10:35:54.912  2052  5834 I bt_hwcfg: Setting fw settlement delay to 100 
,06-30 10:35:54.941   944  1302 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,06-30 10:35:54.942   944  1302 D LGWifiP2pService: sending p2p connection changed broadcast
06-30 10:35:54.943  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
06-30 10:35:54.943  1870  1870 D WfdsService: WifiP2pState is changed : true
06-30 10:35:54.944  1870  2135 D WfdsService: Receive the WFDS_ENABLE Method
06-30 10:35:54.944  1870  2135 D WfdsService: Set the WFDS Monitor: true
06-30 10:35:54.944  1870  2135 D WfdsService: Connected to the supplicant for wfds
06-30 10:35:54.944  1870  2135 D WfdsJNI : doCommand: WFDS_SET TRUE
06-30 10:35:54.944  5786  5786 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
06-30 10:35:54.945  1870  2135 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
06-30 10:35:54.949  2404  2404 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
06-30 10:35:54.951  1870  1870 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
06-30 10:35:54.951   944  1302 D LGWifiP2pService: InactiveState
06-30 10:35:54.952   944  1302 D LGWifiP2pService: InactiveState{ when=-63ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.952   944  1302 D LGWifiP2pService: P2pEnabledState{ when=-63ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.953   944  1302 D LGWifiP2pService: DefaultState{ when=-63ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.953   944  1302 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.953   944  1302 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.953   944  1302 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.953   944  1302 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.953   944  1302 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.953   944  1302 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.954   944   944 E WifiServerServiceExt: No p2p device connected
06-30 10:35:54.960  1870  1870 D WfdsService: isConnected: false
,06-30 10:35:54.962   944  1302 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.962   944  1302 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.962   944  1302 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.962   944  1302 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.962   944  1302 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.962   944  1302 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:54.964  1870  1870 D WfdsService: GroupInfoAvailable: mGroupInfo is null
06-30 10:35:54.977  5786  5786 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
,06-30 10:35:54.978  5786  5786 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
06-30 10:35:54.978  1870  2135 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
06-30 10:35:54.978  5786  5786 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
06-30 10:35:54.978  1870  2135 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
06-30 10:35:54.978  1870  2135 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
06-30 10:35:54.978  1870  2135 D WfdsService: selectPreferredScanChannel [6]
06-30 10:35:54.978  1870  2135 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
06-30 10:35:54.981  1870  2135 W WfdsService: DefaultState - msg [9441285] is not handled
06-30 10:35:54.982  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 10:35:54.982   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:54.983   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:54.983   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-30 10:35:54.983  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:35:54.982 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 10:35:54.983  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 10:35:54.983  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:54.987  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:35:54.988  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:35:54.988  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:35:54.988  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:35:54.988  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:35:54.988  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
,06-30 10:35:54.992   944   944 D LocSvc_java: onReceive
06-30 10:35:54.996   944   944 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 10:35:54.997   944   944 D WifiServerServiceExt: setSupplicantStateSCANNING
06-30 10:35:55.011  1775  1775 D GONS    : GONS isTestMode: false Country: 
,06-30 10:35:55.015  5791  5791 D WiFiOffLoadUpdatePriority: remove1
06-30 10:35:55.015  5791  5791 V WiFiOffLoadSharedPrefsUtils: save remove
06-30 10:35:55.016  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc45
06-30 10:35:55.016  2052  5834 D bt_hwcfg: hw_config_cback state=2
06-30 10:35:55.022  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc18
06-30 10:35:55.022  2052  5834 D bt_hwcfg: hw_config_cback state=7
06-30 10:35:55.022  2052  5834 I bt_hwcfg: bt vendor lib: set UART baud 4000000
06-30 10:35:55.023  2052  5834 I bt_hwcfg: Setting local bd addr to F8:95:C7:87:85:54
06-30 10:35:55.027  5791  5791 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
06-30 10:35:55.027  5791  5791 D WiFiOffLoadBroadcast: S: false, R: false
,06-30 10:35:55.040  5791  5791 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
06-30 10:35:55.041  5791  5791 D WiFiOffLoadUpdatePriority: connected SSID: null
06-30 10:35:55.041  5791  5791 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
,06-30 10:35:55.045  2052  5834 D bt_hwcfg: hw_config_cback opcode:0xfc01
06-30 10:35:55.045  2052  5834 D bt_hwcfg: hw_config_cback state=8
06-30 10:35:55.045  2052  5834 I bt_hwcfg: vendor lib fwcfg completed
06-30 10:35:55.045  2052  5834 I bt-btif : HC preload_cb 0 [0:SUCCESS 1:FAIL]
06-30 10:35:55.045  2052  5832 I bt-btu  : btu_task received preload complete event
06-30 10:35:55.051   944  1944 D WifiServiceImplEx: addOrUpdateNetwork pid=5791, uid=1000, packageName=android.uid.system:1000
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_HCI,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_L2CAP,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_RFCOMM,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_OBEX,2
,06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_AVCT,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_AVDT,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_AVRC,2
06-30 10:35:55.052   944  1944 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_AVDT_SCB,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_A2D,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_BNEP,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_BTM,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_GAP,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_PAN,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_SAP,2
06-30 10:35:55.052  2052  5832 I         : BTE_InitTraceLevels -- TRC_SDP,2
06-30 10:35:55.053  2052  5832 I         : BTE_InitTraceLevels -- TRC_GATT,2
06-30 10:35:55.053  2052  5832 I         : BTE_InitTraceLevels -- TRC_SMP,2
06-30 10:35:55.053  2052  5832 I         : BTE_InitTraceLevels -- TRC_BTAPP,3
06-30 10:35:55.053  2052  5832 I         : BTE_InitTraceLevels -- TRC_BTIF,3
06-30 10:35:55.053  2052  5832 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,0
06-30 10:35:55.054   944  1304 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
06-30 10:35:55.119  5791  5791 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
06-30 10:35:55.119  5791  5791 D WiFiOffLoadUpdatePriority: configuration updated: 0
,06-30 10:35:55.119   944  1304 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
06-30 10:35:55.129   944  1309 I art     : Explicit concurrent mark sweep GC freed 57730(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 10.157ms total 256.734ms
06-30 10:35:55.132  5791  5791 D WiFiOffLoadUpdatePriority: configuration saved: true
06-30 10:35:55.135  5838  5838 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 10:35:55.136   944  1935 I ActivityManager: Killing 5331:com.lge.eula/1000 (adj 15): empty #11
06-30 10:35:55.194  2052  2052 V BluetoothOppNotification: new notify threadi!
06-30 10:35:55.195  2052  2052 V BluetoothOppNotification: send delay message
06-30 10:35:55.196  2052  5885 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,06-30 10:35:55.197  2052  5885 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a7f8bfb on behalf of 
06-30 10:35:55.198  2052  5885 V BluetoothOppNotification: mUpdateCompleteNotification = true
06-30 10:35:55.200   944  1895 W libprocessgroup: failed to open /acct/uid_1000/pid_5331/cgroup.procs: No such file or directory
06-30 10:35:55.201  2052  5885 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-30 10:35:55.203  2052  5885 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24174418 on behalf of 
06-30 10:35:55.204  2052  5885 V BluetoothOppNotification: outbound: succ-0  fail-0
06-30 10:35:55.206  2052  5832 E bt-btif : bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
06-30 10:35:55.207  2052  5885 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
06-30 10:35:55.207  2052  5885 V BluetoothOppNotification: outbound notification was removed.
06-30 10:35:55.207  2052  5885 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,06-30 10:35:55.208  2052  5885 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37377e71 on behalf of 
,06-30 10:35:55.209  2052  5885 V BluetoothOppNotification: inbound: succ-0  fail-0
06-30 10:35:55.210  2052  5832 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
06-30 10:35:55.210  2052  5832 W bt-smp  : Plain text(LSB ~ MSB) = 20 85 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 10:35:55.210  2052  5832 W bt-smp  : Encrypted text(LSB ~ MSB) = f1 3a 99 7d 37 5f 60 da cf aa 80 da 26 48 81 45 
06-30 10:35:55.210  2052  5832 W bt-btm  : Stopping oneshot timer
06-30 10:35:55.211  2052  5886 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
06-30 10:35:55.211  2052  2158 E bt-btif : warning : media task started media_task_refcnt 1 
06-30 10:35:55.212  2052  5886 D BT_PROF_AUDIO: created moving average (N=100)
06-30 10:35:55.212  2052  5886 D BT_PROF_AUDIO: reset rate average
06-30 10:35:55.212  2052  5886 W bt-btif : overflow 0, enter 0, exit 0
06-30 10:35:55.212  2052  2158 E bt-btif : Calling BTA_HhEnable
06-30 10:35:55.213  2052  2158 E bt-btif : btif_storage_get_adapter_property service_mask:0x1201c8
06-30 10:35:55.213  2052  2158 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-30 10:35:55.213  2052  2158 D BluetoothAdapterProperties: Address is:F8:95:C7:87:85:54
06-30 10:35:55.218  2052  5885 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
06-30 10:35:55.219  2052  2158 D BluetoothAdapterProperties: Name is: G3s-1
06-30 10:35:55.219   944   944 D BluetoothManagerService: Bluetooth Adapter name changed to G3s-1
06-30 10:35:55.220   944   944 D BluetoothManagerService: Stored Bluetooth name: G3s-1
06-30 10:35:55.220  2052  5885 V BluetoothOppNotification: inbound notification was removed.
06-30 10:35:55.220  2052  5885 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,06-30 10:35:55.223  2052  5885 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@278d7456 on behalf of 
,06-30 10:35:55.265   944  1944 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5888 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
06-30 10:35:55.267  2052  2158 D BluetoothAdapterProperties: Scan Mode:20
06-30 10:35:55.267  2052  2158 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 10:35:55.269  2052  2158 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
06-30 10:35:55.269  2052  2158 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
06-30 10:35:55.269  2052  2158 E bt-btif : btif_sock_init: !radio_req && !rfc_init
06-30 10:35:55.269  2052  2158 I bt-btif : BTA_JvEnable
06-30 10:35:55.269  2052  2158 E bt-btif : btsock_vendor_hci_init: !vhci_init
06-30 10:35:55.270  2052  2158 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
06-30 10:35:55.270  2052  2158 D bt-btif : init_hci_slots(L136): in
06-30 10:35:55.270  2052  2158 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
06-30 10:35:55.271  2052  2158 D IOP_DB_BT: db_open: db_open : handle 2691262428l, read 11046 bytes onto local cache
06-30 10:35:55.271  2052  2158 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
06-30 10:35:55.271  2052  2158 D IOP_DB_BT: db_query: result 1
06-30 10:35:55.271  2052  2158 I         : iop_db_open: iop_db_open status 0
06-30 10:35:55.271  2052  2158 E bt-btif : btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
06-30 10:35:55.271  2052  2158 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
06-30 10:35:55.272  2052  5832 I bt-btif : bta_pan_co_init
06-30 10:35:55.272  2052  2158 D bte_conf: Device ID record 1 : primary
06-30 10:35:55.272  2052  2158 D bte_conf:   vendorId            = 00c4
06-30 10:35:55.272  2052  2158 D bte_conf:   vendorIdSource      = 0001
06-30 10:35:55.272  2052  2158 D bte_conf:   product             = 13a1
06-30 10:35:55.272  2052  2158 D bte_conf:   version             = 1000
06-30 10:35:55.272  2052  2158 D bte_conf:   clientExecutableURL = 
06-30 10:35:55.272  2052  2158 D bte_conf:   serviceDescription  = 
06-30 10:35:55.272  2052  2158 D bte_conf:   documentationURL    = 
06-30 10:35:55.272  2052  2158 D bte_conf: bte_load_did_conf no section named DID2.
06-30 10:35:55.273  2052  2158 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
06-30 10:35:55.274  2052  2153 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
06-30 10:35:55.274  2052  2153 D BluetoothAdapterProperties: ScanMode =  20
06-30 10:35:55.274  2052  2153 D BluetoothAdapterProperties: State =  11
06-30 10:35:55.274  2052  2153 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
06-30 10:35:55.274  2052  2153 D BluetoothAdapterProperties: Setting state to 12
06-30 10:35:55.274  2052  2153 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
06-30 10:35:55.274  2052  2153 D BluetoothAdapterService(367319230): updateAdapterState() - Broadcasting state to 1 receivers.
06-30 10:35:55.275  2052  2158 E bt-btif : btif_hf_upstreams_evt: wrong handle = 26465 
06-30 10:35:55.275  2052  2158 I bt-btif : HAL bt_op_callbacks->opc_state_cb
06-30 10:35:55.275  2052  2158 D BluetoothOPPServiceJni: opc_state_cb(L140):  opc_state_cb state:0
06-30 10:35:55.275  2052  2158 D OppService: onOpcStateChange()
06-30 10:35:55.275  2052  2052 D OppService: Recieved MESSAGE_OPC_ENABLE
06-30 10:35:55.276  2052  2052 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 10:35:55.277  2052  2158 I bt-btif : HAL bt_op_callbacks->ops_state_cb
06-30 10:35:55.277  2052  2158 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:0
06-30 10:35:55.277  2052  2158 D OppService: onOpsStateChange() :0
06-30 10:35:55.277  2052  2158 I bt-btif : HAL bt_fts_callbacks->operation_cmpl_cb
06-30 10:35:55.277  2052  2158 D BluetoothFTPService,Jni: operation_cmpl_callback(L192):  oper:3 status:0
06-30 10:35:55.277  2052  2158 I BluetoothFTPService: onFtpServerEnabled: /storage
06-30 10:35:55.277  2052  2158 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
06-30 10:35:55.277  2052  2158 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-30 10:35:55.278  2052  2052 D OppService: Recieved MESSAGE_OPS_ENABLE
,06-30 10:35:55.292   307   307 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 26.688ms,
,06-30 10:35:55.295  2052  5834 D bt_h4   : vendor lib postload completed
06-30 10:35:55.318   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 331us total 25.579ms
,06-30 10:35:55.329  2052  2153 I BluetoothAdapterState: Entering On State
06-30 10:35:55.329   944  1050 D BluetoothManagerService: Message: 60
06-30 10:35:55.329   944  1050 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
06-30 10:35:55.329  2052  2153 I BluetoothAdapterState: Entering On State from state = 11
06-30 10:35:55.329   944  1050 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 6 receivers.
06-30 10:35:55.329  2052  2158 D BluetoothAdapterProperties: Scan Mode:21
06-30 10:35:55.330  2052  2158 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-30 10:35:55.330  2052  2158 D BluetoothAdapterProperties: Discoverable Timeout:120
,06-30 10:35:55.333  2052  2153 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.334  2052  2153 D BluetoothAdapterService(367319230): isQuetModeEnabled() - Enabled = false
06-30 10:35:55.334  2052  2068 D BluetoothA2dp: onBluetoothStateChange: up=true
06-30 10:35:55.334  2052  2153 D BluetoothAdapterService(367319230): autoConnect() - Initiate auto connection on BT on...
06-30 10:35:55.334  2052  2153 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
06-30 10:35:55.335  2052  2153 D LGBluetoothServiceAdapter: [BTUI] OnState
06-30 10:35:55.335  2052  2153 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3s-1
06-30 10:35:55.335  2052  2067 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
,06-30 10:35:55.335  2052  2153 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3s-1
06-30 10:35:55.336  2052  2153 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.336  2052  2153 D BluetoothAdapterService(367319230): isQuetModeEnabled() - Enabled = false
06-30 10:35:55.336  2052  2153 D BluetoothAdapterService(367319230): autoConnect() - Initiate auto connection on BT on...
06-30 10:35:55.336  2052  2153 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
06-30 10:35:55.337  5650  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
06-30 10:35:55.337  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 10:35:55.337  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:55.337  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 10:35:55.337  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 10:35:55.337  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 10:35:55.337  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:55.337  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:55.337  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:55.339  2052  2067 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.339  1775  2385 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 10:35:55.339   944  1050 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 10:35:55.340  1775  1805 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 10:35:55.340  5650  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 10:35:55.342  1775  1801 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 10:35:55.342   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 23.344ms
06-30 10:35:55.342   944  1050 D BluetoothA2dp: onBluetoothStateChange: up=true
06-30 10:35:55.343  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 10:35:55.344   944  1050 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
06-30 10:35:55.344   944  1050 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,06-30 10:35:55.346   944   944 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
06-30 10:35:55.346   944  1050 D BluetoothManagerService: Message: 40
06-30 10:35:55.346   944  1050 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
06-30 10:35:55.347  1870  1870 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:55.348  2052  2068 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.348  2052  5901 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.352  2052  2052 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.352  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
06-30 10:35:55.352  1368  1368 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
06-30 10:35:55.354  2052  2052 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:55.354  2052  2052 D BluetoothMapService: STATE_ON
,06-30 10:35:55.364  5791  5791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-30 10:35:55.370  2052  2052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15e4d8be
06-30 10:35:55.374  1870  2048 D LGBluetoothAPIService: Message: 1
06-30 10:35:55.374  1870  2048 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,06-30 10:35:55.394  1870  2048 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,06-30 10:35:55.399  2052  2052 V BluetoothPbapService: Pbap Service onCreate
06-30 10:35:55.399  2052  2052 V BluetoothPbapService: Starting PBAP service
06-30 10:35:55.405  2052  2052 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.406  2052  2052 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
06-30 10:35:55.406  2052  2052 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,06-30 10:35:55.411  2052  2052 V BluetoothPbapService: state: 12
06-30 10:35:55.412  2052  2052 V BluetoothMapService: Handler(): got msg=1
06-30 10:35:55.412  2052  2052 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
06-30 10:35:55.413  2052  5901 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.413  2052  2052 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 10:35:55.414  2052  2052 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:55.414  2052  2052 V BluetoothPbapReceiver: ***********state = 12
06-30 10:35:55.414  2052  5911 D BluetoothMapMasInstance: MAS initSocket()
06-30 10:35:55.415  2052  5911 D BluetoothMapMasInstance:   masId = 00
06-30 10:35:55.415  2052  5911 D BluetoothMapMasInstance:   msgTypes = 0e
06-30 10:35:55.415  2052  5911 D BluetoothMapMasInstance:   masName = SMS/MMS
06-30 10:35:55.415  2052  5911 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
06-30 10:35:55.417   944  2189 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:55.417  5791  5791 D LocalBluetoothProfileManager: Adding local A2DP profile
06-30 10:35:55.418  2052  5911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 10:35:55.419  2052  5911 I bt-btif : BTA_JvCreateRecordByUser
,06-30 10:35:55.420  2052  5832 I bt-btif : BTA_JvRfcommStartServer
06-30 10:35:55.420  2052  5911 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=0
06-30 10:35:55.420  2052  5911 V BluetoothMapMasInstance: Succeed to create listening socket 
06-30 10:35:55.420  2052  5911 D BluetoothMapMasInstance: Accepting socket connection...
06-30 10:35:55.422   944  1050 D BluetoothManagerService: Message: 30
06-30 10:35:55.422  2052  2052 D LGBluetoothAPIServer: [BTUI] onCreate()
06-30 10:35:55.423  2052  2052 D LGBluetoothAPIServer: [BTUI] onBind()
06-30 10:35:55.424  2052  2052 V BluetoothPbapService: Handler(): got msg=1
06-30 10:35:55.424  1870  1870 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
06-30 10:35:55.425  1870  2048 D LGBluetoothAPIService: Message: 100
06-30 10:35:55.425  2052  2052 V BluetoothPbapService: Pbap Service startRfcommSocketListener
06-30 10:35:55.425  1870  2048 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
06-30 10:35:55.425  5791  5791 D LocalBluetoothProfileManager: Adding local HEADSET profile
06-30 10:35:55.426  2052  5912 V BluetoothPbapService: Pbap Service initSocket
06-30 10:35:55.427   944  1344 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:55.428   944  1050 D BluetoothManagerService: Message: 30
06-30 10:35:55.429  2052  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-30 10:35:55.429  2052  5912 I bt-btif : BTA_JvCreateRecordByUser
06-30 10:35:55.429  2052  5912 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=85 mFd=83
06-30 10:35:55.429  2052  5832 I bt-btif : BTA_JvRfcommStartServer
06-30 10:35:55.430  2052  5912 V BluetoothPbapService: Succeed to create listening socket 
06-30 10:35:55.430  2052  5912 V BluetoothPbapService: Accepting socket connection...
06-30 10:35:55.434   944  1050 D BluetoothManagerService: Message: 30
,06-30 10:35:55.439   944  1050 D BluetoothManagerService: Message: 30
06-30 10:35:55.443  5791  5791 D LocalBluetoothProfileManager: Adding local MAP profile
06-30 10:35:55.447  5791  5791 D BluetoothMap: Create BluetoothMap proxy object
,06-30 10:35:55.448   944  1050 D BluetoothManagerService: Message: 30
,06-30 10:35:55.453   944  1050 D BluetoothManagerService: Message: 30
06-30 10:35:55.455  2052  2052 V BluetoothPbapService: Pbap Service onBind
06-30 10:35:55.456  5791  5791 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
06-30 10:35:55.462  5791  5791 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,06-30 10:35:55.467  5791  5791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
06-30 10:35:55.477  5791  5791 D DockEventReceiver: finishStartingService: stopping service
,06-30 10:35:55.480  5791  5791 D BluetoothA2dp: Proxy object connected
06-30 10:35:55.481   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
06-30 10:35:55.481  5791  5791 D A2dpProfile: Bluetooth service connected
06-30 10:35:55.486  2052  2067 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.487  5791  5791 D BluetoothHeadset: Proxy object connected
06-30 10:35:55.488  5791  5791 D HeadsetProfile: Bluetooth service connected
06-30 10:35:55.494  2052  5901 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.496  5791  5791 D BluetoothInputDevice: Proxy object connected
,06-30 10:35:55.498  5791  5791 D HidProfile: Bluetooth service connected
,06-30 10:35:55.498  2052  2068 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.500  5791  5791 D BluetoothPan: BluetoothPAN Proxy object connected
06-30 10:35:55.501  5791  5791 D PanProfile: Bluetooth service connected
06-30 10:35:55.504  2052  2067 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.507  5791  5791 D BluetoothMap: Proxy object connected
06-30 10:35:55.508  5791  5791 D MapProfile: Bluetooth service connected
06-30 10:35:55.508  5791  5791 D BluetoothMap: getConnectedDevices()
06-30 10:35:55.509  2052  5901 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
,06-30 10:35:55.509  2052  2067 V BluetoothMapService: getConnectedDevices()
06-30 10:35:55.510  5791  5791 D BluetoothPbap: Proxy object connected
06-30 10:35:55.511  5791  5791 D PbapServerProfile: Bluetooth service connected
06-30 10:35:55.512  5791  5791 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
06-30 10:35:55.515  5791  5791 D BluetoothPermissionRequest: onReceive
06-30 10:35:55.518  5791  5791 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 10:35:55.519  5791  5791 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,06-30 10:35:55.525  2052  2052 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
06-30 10:35:55.527  5888  5888 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 10:35:55.527  5888  5888 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 10:35:55.534  5888  5888 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 10:35:55.534  2052  2052 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,06-30 10:35:55.539  5888  5888 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 10:35:55.541  2052  2052 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 10:35:55.542  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:35:55.543  2052  2052 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 10:35:55.549  2404  2404 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,06-30 10:35:55.550  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:55.559  5888  5924 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 10:35:55.559  2404  5923 D EasyUnlockInitService: Handling intent for initializer IntentService.
06-30 10:35:55.561  2404  2404 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
06-30 10:35:55.561  5838  5838 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,06-30 10:35:55.566  5888  5924 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,06-30 10:35:55.575  5838  5838 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 10:35:55.575  5838  5838 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,06-30 10:35:55.582  5888  5921 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 10:35:55.620   944  1895 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5927 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,06-30 10:35:55.648  2404  5923 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,06-30 10:35:55.706  5927  5927 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-30 10:35:55.785   944  1050 D BluetoothManagerService: Message: 20
06-30 10:35:55.785   944  1050 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@205286f7:true
,06-30 10:35:55.788   278  1040 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
06-30 10:35:55.789   944  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:35:55.789   944  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:35:55.792  2052  2068 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.793  2052  2067 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:35:55.834  5466  5466 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
06-30 10:35:55.834  5466  5466 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,06-30 10:35:55.844  5466  5466 V [BNRBootReceiver]: Boot Receiver Return
,06-30 10:35:55.847  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:55.853  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-30 10:35:55.863  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,06-30 10:35:55.866  5791  5791 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,06-30 10:35:55.958   944  1988 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5949 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:55.969  5927  5927 V LGMDMManager: Create singleton instance
,06-30 10:35:56.046  5927  5927 I AudioManager: getMode name:com.lge.qremote
,06-30 10:35:56.066  5949  5949 D UEI.SmartControl: Quickset Services start...
,06-30 10:35:56.071  5949  5949 I UEI.SmartControl: Manufacture = LGE
06-30 10:35:56.073  5949  5949 D UEI.SmartControl: File observer start...
06-30 10:35:56.074  5949  5949 E UEI.SmartControl: IR Port is disabled: false
06-30 10:35:56.074  5949  5949 D UEI.SmartControl: Starting file observer...
06-30 10:35:56.074  5949  5949 D UEI.SmartControl: Extracting JNI libs...
06-30 10:35:56.075  5949  5949 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
06-30 10:35:56.087  5786  5786 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,06-30 10:35:56.117   278  1040 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,06-30 10:35:56.123   944   944 D LocSvc_java: onReceive
06-30 10:35:56.126  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
06-30 10:35:56.129  5791  5791 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
06-30 10:35:56.131  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-30 10:35:56.132  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 10:35:56.132   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.132   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.132   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-30 10:35:56.132  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:35:56.132 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 10:35:56.132  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 10:35:56.134  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:35:56.136  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:35:56.136  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:35:56.136  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:35:56.136  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:35:56.137  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:35:56.137  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
06-30 10:35:56.138   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.139   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.139   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
06-30 10:35:56.139  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 10:35:56.139  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:56.140  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:35:56.14 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 10:35:56.140  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
06-30 10:35:56.142  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:35:56.142  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:35:56.142  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:35:56.142  1368  1,368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:35:56.142  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:35:56.142  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
06-30 10:35:56.143   944   944 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 10:35:56.143   944   944 D WifiServerServiceExt: setSupplicantStateASSOCIATING
06-30 10:35:56.147  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:56.166  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:56.177  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:56.196   278  1040 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-30 10:35:56.196   278  1040 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,06-30 10:35:56.197   278  1040 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-30 10:35:56.197  5786  5786 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
06-30 10:35:56.205  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 10:35:56.205   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.205   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.205   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
06-30 10:35:56.206  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:35:56.205 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 10:35:56.206  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
06-30 10:35:56.207  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:35:56.207  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-30 10:35:56.211  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:35:56.212  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:35:56.212  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:35:56.212  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:35:56.212  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:35:56.212  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
06-30 10:35:56.213  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:56.213   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.213   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.213   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
06-30 10:35:56.213   944   944 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 10:35:56.213   944   944 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
06-30 10:35:56.213  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 10:35:56.214  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:35:56.214 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 10:35:56.214  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
06-30 10:35:56.216  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:35:56.216  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:35:56.216  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:35:56.216  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:35:56.217  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:35:56.217  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
,06-30 10:35:56.232  5786  5786 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-30 10:35:56.233  5786  5786 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-30 10:35:56.233   944   944 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 10:35:56.233   944   944 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
06-30 10:35:56.233   278  1040 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-30 10:35:56.237  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-30 10:35:56.241   944  1304 I WifiServiceExtension: setVHTCapabilityType  : false
06-30 10:35:56.250  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:56.256  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:56.264   944  1304 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
06-30 10:35:56.264   944  1304 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,06-30 10:35:56.269   944  1304 I WifiServiceExtension: setSecurityType  : 2
06-30 10:35:56.280  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-30 10:35:56.283   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.283   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.283   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
06-30 10:35:56.284   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.284   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:35:56.284   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
06-30 10:35:56.284  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 10:35:56.285  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:35:56.286  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:35:56.285 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 10:35:56.286  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
06-30 10:35:56.286  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 10:35:56.287  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:35:56.287  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:35:56.287  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:35:56.287  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:35:56.287  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:35:56.287 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 10:35:56.287  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:35:56.287  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
06-30 10:35:56.287  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
06-30 10:35:56.288  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:35:56.293  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:35:56.293  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,06-30 10:35:56.293  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:35:56.294  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:35:56.294  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:35:56.294  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
06-30 10:35:56.305  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:35:56.312   944  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,06-30 10:35:56.312   944  1310 D ConnectivityService: Got NetworkAgent Messenger
06-30 10:35:56.313   944  5967 D WifiExtManager: WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@2ec18632
06-30 10:35:56.313   944  1304 D WifiExtManager: WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@1bf58f83
06-30 10:35:56.314   944  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
06-30 10:35:56.316   944  1310 D ConnectivityService: NetworkAgent connected
06-30 10:35:56.322  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 10:35:56.325  1870  1886 D WifiServiceExtension: isInternetCheckAvailable return false
06-30 10:35:56.325   944  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-30 10:35:56.329  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-30 10:35:56.337   944  1766 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:35:56.337   944  1766 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:35:56.337   944  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,06-30 10:35:56.347   278  1040 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
06-30 10:35:56.348   944  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:35:56.348   944  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:35:56.349   944  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:35:56.349   944  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:35:56.349   278  1047 D CommandListener: Setting iface cfg
06-30 10:35:56.355   944  1304 E WifiStateMachine: Start Dhcp Watchdog 1
06-30 10:35:56.359   944  5968 D DhcpStateMachine: StoppedState
06-30 10:35:56.359   944  5968 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:56.359   944  5968 D DhcpStateMachine: WaitBeforeStartState
,06-30 10:35:56.364  1907  1907 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
06-30 10:35:56.365  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-45 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:35:56.364 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 10:35:56.366  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:35:56.366  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:35:56.366  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:35:56.372   944  1310 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-30 10:35:56.373   944   944 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,06-30 10:35:56.373   944   944 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,06-30 10:35:56.376   944   944 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 10:35:56.376   944   944 D WifiServerServiceExt: setSupplicantStateCOMPLETED
06-30 10:35:56.407  5949  5949 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,06-30 10:35:56.409  5949  5949 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
06-30 10:35:56.409  5949  5949 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
06-30 10:35:56.448  5949  5949 I UEI.SmartControl: --- Selecting new region: 2
06-30 10:35:56.449  5949  5949 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,06-30 10:35:56.455  5949  5949 D UEI.SmartControl: Platform has CIR...
06-30 10:35:56.457   944  1302 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15a95f73 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 10:35:56.457   944  1304 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
06-30 10:35:56.457   944  1302 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15a95f73 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:56.457   944  1304 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-30 10:35:56.458   944  5968 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:35:56.458   944  5968 D DhcpStateMachine: DHCP Start wake lock is acquired.
06-30 10:35:56.458  5949  5949 D UEI.SmartControl: NO CIR support, need to check package...
06-30 10:35:56.460  5949  5949 I UEI.SmartControl: Model: LG-D722 uses JNI
06-30 10:35:56.460   944  1304 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-30 10:35:56.460   944  1304 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
,06-30 10:35:56.465  5949  5949 D UEI.SmartControl: QS Service created
06-30 10:35:56.489  5949  5949 E UEI.SmartControl: QS start get config
,06-30 10:35:56.561  5949  5949 D UEI.SmartControl: Loading JNI Libs...
,06-30 10:35:56.565  5949  5949 D UEI.SmartControl:  configuring local db...
06-30 10:35:56.660   944  5968 D DhcpStateMachine: DHCPV4 request on wlan0
,06-30 10:35:56.661   944  5968 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
06-30 10:35:56.661   944  5968 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
06-30 10:35:56.675  5969  5969 I dhcpcd  : version 5.5.6 starting
06-30 10:35:56.677  5969  5969 E dhcpcd  : get_duid: Read-only file system
06-30 10:35:56.748  5969  5969 I dhcpcd  : wlan0: rebinding lease of 192.168.1.103
,06-30 10:35:56.751   944  1895 I ActivityManager: Process com.google.android.talk (pid 5493) has died
06-30 10:35:56.792  5949  5949 D UEI.SmartControl:  ---- Has DB8: true
,06-30 10:35:56.800  5949  5949 D UEI.SmartControl: QS start statue = true Error code = 0
06-30 10:35:56.801  5949  5949 D UEI.SmartControl: QS version = v2.7.11.1_RC1
06-30 10:35:56.802  5949  5949 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
06-30 10:35:56.806  5949  5949 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
06-30 10:35:56.807   283  1285 V AudioFlinger: thread 0xb5651000 type 0 TID 1285 going to sleep
06-30 10:35:56.807   283  1286 V AudioFlinger: thread 0xb56eb000 type 0 TID 1286 going to sleep
,06-30 10:35:56.811   283  1288 V AudioFlinger: thread 0xb5735000 type 0 TID 1288 going to sleep
06-30 10:35:56.829  5949  5949 W irrc_jni: IRRCPlayer_nativeInit ++ 
06-30 10:35:56.829  5949  5949 D irrcClient: IrrcClient ++ 
06-30 10:35:56.829  5949  5949 D irrcClient: getIrrcService ++ 
,06-30 10:35:56.832  5949  5949 D irrcClient: getIrrcService -- 
06-30 10:35:56.832  5949  5949 D irrcClient: IrrcClient -- 
06-30 10:35:56.832  5949  5949 W irrc_jni: IRRCPlayer_nativeInit -- 
06-30 10:35:56.839  5949  5949 D UEI.SmartControl: Services init done
06-30 10:35:56.840  5949  5980 I UEI.SmartControl: Device manager: loading config....
06-30 10:35:56.843  5949  5949 D UEI.SmartControl: QS Service init finished
,06-30 10:35:56.848  5949  5949 D UEI.SmartControl: QS Service version name: 0.1.73
06-30 10:35:56.849  5949  5949 D UEI.SmartControl: QS Service version code: 1073
06-30 10:35:56.850  5949  5980 D UEI.SmartControl: Config is loaded...
06-30 10:35:56.850  5949  5949 D UEI.SmartControl: Service requested: Control
06-30 10:35:56.853  5949  5949 D UEI.SmartControl: Internal service binding...
06-30 10:35:56.854  5949  5964 D UEI.SmartControl: -----IControl: 11
06-30 10:35:56.855  5949  5964 D UEI.SmartControl: Caller: com.lge.qremote
06-30 10:35:56.856  5949  5964 D UEI.SmartControl: ------------ IControl registerCallback...
06-30 10:35:56.856  5949  5964 I UEI.SmartControl: Registering callback...
,06-30 10:35:56.858  5949  5965 D UEI.SmartControl: -----IControl: 19
06-30 10:35:56.861  5949  5965 D UEI.SmartControl: Caller: com.lge.qremote
06-30 10:35:56.863  5949  5965 I UEI.SmartControl: Registering Services Ready callback...
06-30 10:35:56.889  5949  5979 D UEI.SmartControl:  ----- QS SDK is ready!!!
,06-30 10:35:56.890  5949  5979 I UEI.SmartControl: Notify AllClients services are ready: 0
06-30 10:35:56.894  5949  5964 D UEI.SmartControl: -----IControl: 8
06-30 10:35:56.895  5949  5964 D UEI.SmartControl: Caller: com.lge.qremote
06-30 10:35:56.900  5927  5927 I AudioManager: getMode name:com.lge.qremote
06-30 10:35:56.906   944   963 I ActivityManager: Killing 5147:com.google.android.gms:car/u0a6 (adj 15): empty #11
,06-30 10:35:56.999   944  2025 W libprocessgroup: failed to open /acct/uid_10006/pid_5147/cgroup.procs: No such file or directory
,06-30 10:35:57.003  5927  5927 I AudioManager: getMode name:com.lge.qremote
,06-30 10:35:57.023  5927  5927 I AudioManager: getMode name:com.lge.qremote
,06-30 10:35:57.718   278  1040 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,06-30 10:35:57.722   944  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:35:57.722   944  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:35:57.725   944  1310 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-30 10:35:59.874   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:35:59.874   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:35:59.874   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 152935304842; DSPS: 5110020; Offset : -3013788998
,06-30 10:36:00.000   944  1282 D PowerManagerServiceEx: acquireWakeLockInternal: lock=731858183, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=944
,06-30 10:36:00.008  2825  2825 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 10:36:0
06-30 10:36:00.008  2825  2825 D WeatherService: 2 : TimeTick Intent And Screen On
06-30 10:36:00.008  2825  2825 D WeatherService: 2 : SDK version : 21
06-30 10:36:00.010   944  1355 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
06-30 10:36:00.010  2825  2825 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
06-30 10:36:00.011  2825  2825 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
06-30 10:36:00.011  2825  2825 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
06-30 10:36:00.011  2825  2825 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
06-30 10:36:00.012  2825  2825 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-30 10:36:00.012  2825  2825 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
06-30 10:36:00.012  2825  2825 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
06-30 10:36:00.012  2825  2825 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
06-30 10:36:00.012  2825  2825 D WeatherTheme: 2 : Fixed theme : optimus
,06-30 10:36:00.028  2825  2825 D WeatherReflect: 2 : Map key string is -2
06-30 10:36:00.031  2825  2825 D lim     : 2 : time = 10:36
,06-30 10:36:00.037  2825  2825 I WeatherReflect: Model Name : LG-D722
06-30 10:36:00.037  2825  2825 D WeatherTheme: 2 : Different view - status_min_formatted : 35 != 36
06-30 10:36:00.037  2825  2825 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
06-30 10:36:00.039  2825  2825 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
06-30 10:36:00.043  2825  2825 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 10:36:00.043  2825  2825 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
06-30 10:36:00.043  2825  2825 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 10:36:00.043  2825  2825 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
,06-30 10:36:00.079  2825  2825 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
06-30 10:36:00.079  2825  2825 D Weather4x2_optimus: widgetType = 1, orientation = 1
06-30 10:36:00.079  2825  2825 D Weather4x2_optimus: forecast size is 0
06-30 10:36:00.079  2825  2825 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 10:36:00.079  2825  2825 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
06-30 10:36:00.079  2825  2825 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 10:36:00.080  2825  2825 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 10:36:00.080  2825  2825 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
06-30 10:36:00.080  2825  2825 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 10:36:00.080  2825  2825 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 10:36:00.080  2825  2825 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
06-30 10:36:00.080  2825  2825 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 10:36:00.080  2825  2825 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
06-30 10:36:00.080  2825  2825 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
06-30 10:36:00.080  2825  2825 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 10:36:00.080  2825  2825 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
06-30 10:36:00.080  2825  2825 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 10:36:00.080  2825  2825 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
,06-30 10:36:00.084  2825  2825 D Theme_WeatherAncestor_optimus: url is : null
06-30 10:36:00.086  2825  2825 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 10:36:00.086  2825  2825 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
06-30 10:36:00.086  2825  2825 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 10:36:00.087  2825  2825 D WeatherAncestor: 2 : update view, appWidgetId: 2
06-30 10:36:00.093  2825  2825 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 10:36:0
06-30 10:36:00.097  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:36:00.098  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 10:36:00.101  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
06-30 10:36:00.104  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:36:00.108   944   944 D PowerManagerServiceEx: releaseWakeLockInternal: lock=731858183 [*alarm*], flags=0x0
06-30 10:36:00.109  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:36:00.110  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:36:00.111  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:36:00.115   944  1053 I PowerManagerService: ALS enabled for SRE
06-30 10:36:00.115   944  1053 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33176 ms ago)
06-30 10:36:00.115   944  1053 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,06-30 10:36:00.137   944  1053 I PowerManagerService: ALS enabled for SRE
06-30 10:36:00.139   944  1053 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33200 ms ago)
06-30 10:36:00.142   944  1053 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
06-30 10:36:00.143   944  1053 I PowerManagerService: Sleeping (uid 1000)...
06-30 10:36:00.143   944  1053 D LPWGController: [updateScreenState] screen on = false
06-30 10:36:00.148   944  1053 D LPWGController: disable proximity sensor
06-30 10:36:00.148   944  1053 D LPWGController: enable proximity sensor
,06-30 10:36:00.157   944  1053 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@33b07fcf] by com.android.server.power.ProximitySensorListener.enable():120
,06-30 10:36:00.175   944  1053 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
,06-30 10:36:00.175   944  1053 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
06-30 10:36:00.175   944  1053 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
06-30 10:36:00.175   944  1053 I sensors_hal_Ctx: activate: handle is 48, enable
06-30 10:36:00.175   944  1053 V sensors_hal_Ctx: activate sensors is 1400000000000
06-30 10:36:00.175   944  1053 D sensors_hal_Thresh: enable: handle=48
06-30 10:36:00.175   944  1053 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
06-30 10:36:00.175   944  1053 D sensors_hal_Util: waitForResponse: timeout=1000
,06-30 10:36:00.193   944   983 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
06-30 10:36:00.193   944   983 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
06-30 10:36:00.193   944  1053 D sensors_hal_Thresh: enable: Received response: 0
,06-30 10:36:00.193   944  1053 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33255 ms ago)
06-30 10:36:00.209   944  1053 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:36:00.209   944  1053 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:36:00.209   944  1053 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 10:36:00.209   944  1053 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 10:36:00.209   944  1053 I Adreno-EGL: Remote Branch: 
06-30 10:36:00.209   944  1053 I Adreno-EGL: Local Patches: 
06-30 10:36:00.209   944  1053 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:36:00.236   246  2347 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (140 us)
,06-30 10:36:00.320  1945  1945 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,06-30 10:36:00.421   419   969 I Sensors : sns_pwr.c(273):acquiring wakelock
,06-30 10:36:00.422   944   983 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
06-30 10:36:00.430  1945  1945 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
06-30 10:36:00.430   944   983 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
06-30 10:36:00.430   944   983 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
06-30 10:36:00.430   944   983 D sensors_hal_Thresh: processInd: handle 48, count=1
06-30 10:36:00.430   944   983 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
06-30 10:36:00.430   944   983 I sensors_hal_Thresh: processInd : proximity state changed - FAR
06-30 10:36:00.430   944  1023 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
06-30 10:36:00.430   944  1023 D sensors_hal_Ctx: poll: count: 256
06-30 10:36:00.430   944  1023 I sensors_hal_Ctx: poll: released wakelock sensor_ind
06-30 10:36:00.430   944  1023 D sensors_hal_Util: waitForResponse: timeout=0
06-30 10:36:00.437   944  1053 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
06-30 10:36:00.437   944  1053 I LPWGController: current mode = 1  value = 1 1
06-30 10:36:00.438   944  1053 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,06-30 10:36:00.485   294   360 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 10:36:00.527   944  1053 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,06-30 10:36:00.652   944  1924 I ActivityManager: Killing 4780:com.android.vending/u0a36 (adj 15): empty #11
,06-30 10:36:00.710   944  1895 W libprocessgroup: failed to open /acct/uid_10036/pid_4780/cgroup.procs: No such file or directory
,06-30 10:36:00.754  5969  5969 I dhcpcd  : wlan0: acknowledged 192.168.1.103 from 192.168.1.1
,06-30 10:36:00.778  5969  5969 I dhcpcd  : wlan0: leased 192.168.1.103 for 172800 seconds
,06-30 10:36:00.779   278  1040 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
06-30 10:36:00.780   944  1048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:00.781   944  1048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:00.788   944  1310 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-30 10:36:00.827   944  1345 D qdlights: set_light_backlight: 0
,06-30 10:36:00.841   944  1053 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
06-30 10:36:00.841   944  1053 I sensors_hal_Ctx: activate: handle is 46, disable
06-30 10:36:00.841   944  1053 V sensors_hal_Ctx: activate sensors is 1000000000000
06-30 10:36:00.841   944  1053 D sensors_hal_LP2: enable: handle=46
06-30 10:36:00.841   944  1053 D sensors_hal_LP2: enable: Disabling sensor handle=46
06-30 10:36:00.841   944  1053 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,06-30 10:36:00.847   246   246 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
06-30 10:36:00.847   246   246 D qdhwcomposer: hwc_blank: Blanking display: 0
06-30 10:36:00.850   944  1051 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
06-30 10:36:00.850   944   944 V ActivityManager: Display changed displayId=0
,06-30 10:36:00.884  1775  1775 D DSDPConnection: Display #0 changed.
,06-30 10:36:00.929   944  1011 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
06-30 10:36:00.929   944  1011 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,06-30 10:36:01.043   246   246 D qdhwcomposer: hwc_blank: Done blanking display: 0
06-30 10:36:01.043   944  1345 D SurfaceControl: Excessive delay in setPowerMode(): 196ms
06-30 10:36:01.044   246   682 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,06-30 10:36:01.044   944  1345 I QCOM PowerHAL: Got set_interactive hint
06-30 10:36:01.056  1368  1392 D KeyguardViewMediator: onScreenTurnedOff(3)
,06-30 10:36:01.060  5650  5650 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
06-30 10:36:01.060  5650  5650 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
06-30 10:36:01.067   944  5968 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:01.067   944  5968 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.068   944  5968 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:01.068   944  5968 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.068   944  5968 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:01.068   944  5968 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:01.071  5650  5650 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@38d117 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@41648ea, 16908290=android.view.AbsSavedState$1@41648ea}, android:focusedViewId=100}]}]
06-30 10:36:01.071  5650  5650 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
06-30 10:36:01.071  5650  5650 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
06-30 10:36:01.071  5650  5650 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
06-30 10:36:01.068   944  5968 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:01.073   944  5968 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.073   944  5968 D DhcpStateMachine: DHCPV4 succeeded on wlan0
06-30 10:36:01.076   944  5968 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
06-30 10:36:01.076   944  5968 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-30 10:36:01.076   944  5968 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:01.076   944  5968 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.077  1368  1392 D KeyguardViewMediator: notifyScreenOffLocked
06-30 10:36:01.080   944  5968 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.103
06-30 10:36:01.080  1326  1342 D SmartCoverViewMediator: onScreenTurnedOff(3)
06-30 10:36:01.082   944  5968 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.103/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
06-30 10:36:01.082   944  5968 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-30 10:36:01.082   944  5968 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
,06-30 10:36:01.087   944  1302 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:36:01.087   944  5968 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
06-30 10:36:01.087   944  1302 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:36:01.087   944  5968 D DhcpStateMachine: RunningState
06-30 10:36:01.089   944   944 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
06-30 10:36:01.090   283  1292 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 944
06-30 10:36:01.090   283  1292 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
06-30 10:36:01.090   283  1292 V voice   : voice_set_parameters: enter: screen_state=on
06-30 10:36:01.091   283  1292 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
06-30 10:36:01.091   283  1292 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-30 10:36:01.091   283  1292 V voice   : voice_set_parameters: exit with code(0)
06-30 10:36:01.091   283  1292 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
06-30 10:36:01.091   283  1292 V msm8974_platform: platform_set_parameters: enter: screen_state=on
06-30 10:36:01.091   283  1292 V msm8974_platform: platform_set_parameters: exit with code(0)
06-30 10:36:01.091   283  1292 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-30 10:36:01.091   283  1292 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
06-30 10:36:01.091   283  1292 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
06-30 10:36:01.091   283  1292 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-30 10:36:01.095  1368  1392 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
06-30 10:36:01.095  1368  1368 D KeyguardViewMediator: handleNotifyScreenOff
,06-30 10:36:01.101   944  1310 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-30 10:36:01.103  1326  1342 D SmartCoverViewMediator: notifyScreenOffLocked
06-30 10:36:01.104  1326  1326 D SmartCoverViewMediator: handleNotifyScreenOFF
06-30 10:36:01.105   944  1304 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
06-30 10:36:01.106   944  1304 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
06-30 10:36:01.108   944  1310 D ConnectivityService: ignoring duplicate network state non-change
,06-30 10:36:01.109  1368  1368 D ScreenTurnOffBySensor: unregisterProximitySensor
06-30 10:36:01.111  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,06-30 10:36:01.112  1870  1886 D WifiServiceExtension: isInternetCheckAvailable return false
06-30 10:36:01.116  1368  1368 D StatusBarWindowView: onScreenTurnedOff why = 3
06-30 10:36:01.117   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.117   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.117   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
06-30 10:36:01.119  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:36:01.119  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:36:01.121   944  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,06-30 10:36:01.123   944  1310 D ConnectivityService: Adding iface wlan0 to network 100
06-30 10:36:01.128  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:36:01.132   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.132   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.132   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,06-30 10:36:01.134  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-45 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.103 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:36:01.13 DNS addrs= 192.168.1.1, 0.0.0.0, 
06-30 10:36:01.135  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.103 ipV6Addr=
06-30 10:36:01.136  1870  1887 D WifiServiceExtension: isInternetCheckAvailable return false
06-30 10:36:01.137  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 10:36:01.139   944  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
06-30 10:36:01.140   944   944 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
06-30 10:36:01.141  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:36:01.141  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:36:01.141  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:36:01.141  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:36:01.142  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:36:01.142  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
06-30 10:36:01.143   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.143   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.143   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
06-30 10:36:01.143   944   944 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,06-30 10:36:01.146  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 10:36:01.146   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.146  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:36:01.146   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.146   944   944 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
06-30 10:36:01.147  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-45 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.103 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:36:01.147 DNS addrs= 192.168.1.1, 0.0.0.0, 
06-30 10:36:01.148  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.103 ipV6Addr=
06-30 10:36:01.149  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 10:36:01.150  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-45 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.103 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:36:01.15 DNS addrs= 192.168.1.1, 0.0.0.0, 
06-30 10:36:01.151  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.103 ipV6Addr=
06-30 10:36:01.151  1907  1907 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 10:36:01.157  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-30 10:36:01.157  5650  5748 I jxcore-log: 
,06-30 10:36:01.159  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 10:36:01.162  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:36:01.162  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 10:36:01.162  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:36:01.164  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-45 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.103 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:36:01.163 DNS addrs= 192.168.1.1, 0.0.0.0, 
06-30 10:36:01.164  1907  1907 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.103 ipV6Addr=
06-30 10:36:01.168  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:36:01.168  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
06-30 10:36:01.168  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
06-30 10:36:01.175  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
06-30 10:36:01.175   944  1018 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
06-30 10:36:01.189  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 10:36:01.189  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,06-30 10:36:01.191  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
06-30 10:36:01.194   944  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
06-30 10:36:01.194   944  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
06-30 10:36:01.195  1907  1907 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
06-30 10:36:01.196   278  1047 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-30 10:36:01.196   278  1047 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.196  1907  1907 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-45 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.103 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-06-30 10:36:01.196 DNS addrs= 192.168.1.1, 0.0.0.0, 
06-30 10:36:01.196   278  1047 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-30 10:36:01.196   278  1047 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.197   944  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
06-30 10:36:01.198   278  1047 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-30 10:36:01.198   278  1047 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.198   278  1047 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-30 10:36:01.198   278  1047 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.199   944  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
06-30 10:36:01.200   278  1047 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-30 10:36:01.200   278  1047 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.201  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:36:01.201  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:36:01.201  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
,06-30 10:36:01.202  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
06-30 10:36:01.205   944  1310 D ConnectivityService: addLocalRoutetoDefaultNetwork
06-30 10:36:01.205   944  1310 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
06-30 10:36:01.205   944  1310 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
06-30 10:36:01.206   944  1310 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:01.206   944  1310 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.207  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:36:01.207  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 10:36:01.208  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:36:01.208  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
06-30 10:36:01.208   278  1047 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
06-30 10:36:01.208   278  1047 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.208  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 10:36:01.208  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 10:36:01.208  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
06-30 10:36:01.218   944  1310 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
06-30 10:36:01.218   944  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
06-30 10:36:01.219   944  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
06-30 10:36:01.220   944  1310 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-30 10:36:01.220   944  1310 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-30 10:36:01.225   944  5967 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:36:01.225   944  5967 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
06-30 10:36:01.225   944  5967 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 10:36:01.229   944  1310 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,06-30 10:36:01.229   944  1310 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-30 10:36:01.229   944  1310 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.230   944  1310 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
06-30 10:36:01.230   944  1310 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.230   944  1310 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
06-30 10:36:01.230   944  1310 D ConnectivityService: currentScore = 0, newScore = 20
06-30 10:36:01.230   944  1310 D ConnectivityService:    accepting network in place of null
06-30 10:36:01.231   944  1310 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.232   944  1310 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
06-30 10:36:01.232   944  1304 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.232   944  1304 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:36:01.235  1775  1775 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.236  1775  1775 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
06-30 10:36:01.236  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:36:01.240   944  1310 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.103/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
06-30 10:36:01.240   944  1310 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
06-30 10:36:01.241   944  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-30 10:36:01.242  1907  1907 W QCNEJ   : |CORE| No family connected
06-30 10:36:01.243  1907  1907 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
06-30 10:36:01.243   944  1301 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:01.243   944  1301 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.244   944  1301 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:01.244   944  1301 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:01.245   278  1042 E Bandwidth,Controller: [LG DATA] No such appUid: 1000
06-30 10:36:01.245   278  1042 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
,06-30 10:36:01.247  1907  1907 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
06-30 10:36:01.247   278  6036 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
06-30 10:36:01.247   278  6036 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:01.247   278  6036 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=0
06-30 10:36:01.247   944  1310 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
06-30 10:36:01.247   278  6036 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:01.248   278  6036 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:01.250   944  1310 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
06-30 10:36:01.250   944  1048 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
06-30 10:36:01.251   944  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.103/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
06-30 10:36:01.252   944  5967 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
06-30 10:36:01.253   944  1050 D Tethering: MasterInitialState.processMessage what=3
06-30 10:36:01.253   944  1310 D ConnectivityService: validation of new default Network = false
06-30 10:36:01.253   944  1310 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
06-30 10:36:01.253   944  1310 D DSQN    : enableDataServiceNotify 
06-30 10:36:01.255   944  1310 D DSQN    : start dsqn bin
,06-30 10:36:01.257   944  6037 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
06-30 10:36:01.257  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:36:01.262  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:36:01.267  5838  5838 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
06-30 10:36:01.274   944  1301 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,06-30 10:36:01.281  5838  5838 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
06-30 10:36:01.285   944  1636 D SplitWindow: check instance of lgWin Window{38bd893a u0 SearchPanel}
06-30 10:36:01.292  1907  1907 I QCNEJ   : |CORE| sendScreenState: state:true
,06-30 10:36:01.294  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 10:36:01.294  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:36:01.294  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
06-30 10:36:01.299  5791  5791 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 10:36:01.301  1870  2037 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
06-30 10:36:01.302  1870  2037 D LEDService: stopPatternFlashing()
06-30 10:36:01.303  1870  2037 D qdlights: set_light_notifications: 0,0,0,0,3
,06-30 10:36:01.305  1870  2037 I LEDService: getCurrentHighestLGLedRecord : size = 1
06-30 10:36:01.305  1870  2037 D qdlights: set_light_notifications: 0,0,0,0,3
06-30 10:36:01.306  5791  5791 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 10:36:01.307  1870  2037 I LEDService: updateLightsLocked : turn off led
06-30 10:36:01.307  1870  2037 D qdlights: set_light_notifications: 0,0,0,0,3
06-30 10:36:01.308  1870  2037 D LEDHandler: RESTART MSG
06-30 10:36:01.318   944  1895 D InputDispatcher: Window went away: Window{32425848 u0 SearchPanel}
06-30 10:36:01.319  5838  5838 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,06-30 10:36:01.320  5838  5838 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
06-30 10:36:01.324   944  1310 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-30 10:36:01.324   944  1310 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.325   944  1310 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:36:01.334  6038  6038 I DSQN    : DSQN samuel.seo ver 141203
06-30 10:36:01.335  6038  6038 E DSQN    : DSQN sock connect success to lgdatalistenerd
06-30 10:36:01.335  6038  6038 I DSQN    : created command queue thread
06-30 10:36:01.335  6038  6038 I DSQN    : Interface wlan0 address 192.168.1.103 0xc0a80167
06-30 10:36:01.335  6038  6038 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a80167
,06-30 10:36:01.338   944  1310 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:36:01.339  1368  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 10:36:01.340   944  1310 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.340   944  1310 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.341  3969  5614 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 10:36:01.348  1368  1368 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,06-30 10:36:01.354  1368  1368 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
06-30 10:36:01.355  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 10:36:01.356  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:36:01.356  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
06-30 10:36:01.357  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 10:36:01.357  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:36:01.357  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
06-30 10:36:01.358  1368  1368 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
06-30 10:36:01.375  1368  1368 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,06-30 10:36:01.381  1870  1870 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
06-30 10:36:01.382  1870  1870 D Cliptray Service: lockStatus = 0
06-30 10:36:01.384  1853  1853 D LNfcService: action : android.intent.action.SCREEN_ON
06-30 10:36:01.389   944   944 D Ulp_jni : JNI:system_update. Event-0
,06-30 10:36:01.393  1853  6041 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
,06-30 10:36:01.393  1853  6041 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
06-30 10:36:01.393  1853  6041 D LNfcService: isRequireNfcCRouting() return true
06-30 10:36:01.393  1853  6041 D LNfcService: isHCERoutingtoHost() return : true
06-30 10:36:01.393  1853  6041 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
06-30 10:36:01.393  1853  6041 D NfcService: mEnableLPD: true
06-30 10:36:01.393  1853  6041 D NfcService: mEnableReader: false
06-30 10:36:01.393  1853  6041 D NfcService: mEnableHostRouting: true
06-30 10:36:01.393  1853  6041 D NfcService: newParams.techmask= mTechMask: default
06-30 10:36:01.393  1853  6041 D NfcService: mEnableLPD: true
06-30 10:36:01.393  1853  6041 D NfcService: mEnableReader: false
06-30 10:36:01.393  1853  6041 D NfcService: mEnableHostRouting: true
06-30 10:36:01.393  1853  6041 D NfcService: screenState= 3
06-30 10:36:01.393  1853  6041 D NfcService: Discovery configuration equal, not updating.
,06-30 10:36:01.406  1775  1775 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,06-30 10:36:01.425  2825  2825 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:36:1
,06-30 10:36:01.427  2825  2825 D WeatherService: 2 : ACTION screen on
06-30 10:36:01.429  2825  2825 D WeatherService: 2 : shouldTimeTickRegistered : false
06-30 10:36:01.435  2825  2825 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-30 10:36:01.435  2825  2825 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:36:1
06-30 10:36:01.441  3860  3860 D AppCleanupService: android.intent.action.SCREEN_ON
,06-30 10:36:01.452   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.452   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.452   944   944 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
06-30 10:36:01.457   283   283 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 944
06-30 10:36:01.457   283   283 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
06-30 10:36:01.457   283   283 V voice   : voice_set_parameters: enter: screen_state=off
06-30 10:36:01.457   283   283 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
06-30 10:36:01.457   283   283 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-30 10:36:01.457   283   283 V voice   : voice_set_parameters: exit with code(0)
06-30 10:36:01.457   283   283 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
06-30 10:36:01.457   283   283 V msm8974_platform: platform_set_parameters: enter: screen_state=off
06-30 10:36:01.457   283   283 V msm8974_platform: platform_set_parameters: exit with code(0)
06-30 10:36:01.457   283   283 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-30 10:36:01.457   283   283 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
06-30 10:36:01.457   283   283 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-30 10:36:01.459   944  1309 D WifiController: CMD_SCREEN_OFF 
06-30 10:36:01.459   944  1309 D WifiController: shouldWifiStayAwake TRUE
,06-30 10:36:01.464  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
06-30 10:36:01.464   944  1018 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
06-30 10:36:01.493  1907  1907 I QCNEJ   : |CORE| sendScreenState: state:false
,06-30 10:36:01.494  1870  2037 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,06-30 10:36:01.494  1870  2037 D LEDService: stopPatternFlashing()
06-30 10:36:01.494  1870  2037 D qdlights: set_light_notifications: 0,0,0,0,3
06-30 10:36:01.496  1870  2037 I LEDService: getCurrentHighestLGLedRecord : size = 1
06-30 10:36:01.496  1870  2037 D qdlights: set_light_notifications: 0,0,0,0,3
06-30 10:36:01.497  1870  1870 D VolumeVibrator: clear
06-30 10:36:01.498  1870  2037 I LEDService: updateLightsLocked : turn on led
06-30 10:36:01.498  1870  2037 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
06-30 10:36:01.498  1870  2037 E LEDService: Can't handle this request of patternId:0
06-30 10:36:01.498  1870  2037 D LEDHandler: RESTART MSG
06-30 10:36:01.499  1870  1870 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
06-30 10:36:01.500  1853  1853 D LNfcService: action : android.intent.action.SCREEN_OFF
06-30 10:36:01.503  1853  2196 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
06-30 10:36:01.510  1945  1945 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,06-30 10:36:01.525  1775  1775 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,06-30 10:36:01.531  2825  2825 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:36:1
06-30 10:36:01.531  2825  2825 D WeatherService: 2 : ACTION screen off
06-30 10:36:01.532  2825  2825 D WeatherService: 2 : TimeTick Receiver Unregister
06-30 10:36:01.532  2825  2825 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:36:1
06-30 10:36:01.534  3860  3860 D AppCleanupService: android.intent.action.SCREEN_OFF
06-30 10:36:01.537  3860  6044 D AppCleanupService: AppUsageStatsSaveTask
,06-30 10:36:01.542   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.542   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:01.542   944   944 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
06-30 10:36:01.584  1853  2712 E NxpNfcJni: getReconnectState = 0x0
06-30 10:36:01.586  1853  2196 D LCardEmulationManager: getHceAppCount hostAppNum : 0
06-30 10:36:01.586  1853  2196 D LCardEmulationManager: getDefaultRoute
,06-30 10:36:01.586  1853  2196 D LNfcService: isRequireNfcCRouting() return true
06-30 10:36:01.587  1853  2196 D LNfcService: isHCERoutingtoHost() return : true
06-30 10:36:01.587  1853  2196 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
06-30 10:36:01.587  1853  2196 D NfcService: mEnableLPD: true
06-30 10:36:01.587  1853  2196 D NfcService: mEnableReader: false
06-30 10:36:01.587  1853  2196 D NfcService: mEnableHostRouting: true
06-30 10:36:01.587  1853  2196 D NfcService: newParams.techmask= mTechMask: 0
06-30 10:36:01.587  1853  2196 D NfcService: mEnableLPD: true
06-30 10:36:01.587  1853  2196 D NfcService: mEnableReader: false
06-30 10:36:01.587  1853  2196 D NfcService: mEnableHostRouting: true
06-30 10:36:01.587  1853  2196 D NfcService: screenState= 1
06-30 10:36:01.643  1853  2712 E NxpNfcJni: getReconnectState = 0x0
,06-30 10:36:01.759   944  6037 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
06-30 10:36:01.759   944  6037 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:01.759   944  6037 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:01.759   944  6037 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
06-30 10:36:01.759   944  6037 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:36:01.760   278  1042 E BandwidthController: [LG DATA] No such appUid: 1000
06-30 10:36:01.760   278  1042 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-30 10:36:01.761   278  6048 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
06-30 10:36:01.761   278  6048 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:36:01.761   278  6048 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:01.762   278  6048 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:01.803   278  6048 D libc-netbsd: res_queryN name = xxxxx succeed
,06-30 10:36:01.807   944  6037 I System.out: propertyValue:false
06-30 10:36:01.807   944  6037 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
06-30 10:36:01.811   944  5967 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
06-30 10:36:01.822   944  5967 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:01.823   944  5967 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:01.852  6038  6039 I DSQN    : first global connection report this to start monitoring at DSQM.
06-30 10:36:01.852  6038  6039 I DSQN    : restart monitoring
,06-30 10:36:01.855  6038  6053 I DSQN    : dsqn report finish
06-30 10:36:01.855   278  1046 D LGDataListener: argv[0]=dsqncommand
06-30 10:36:01.856   278  1046 D LGDataListener: argv[1]=wlan0
06-30 10:36:01.856   278  1046 D LGDataListener: argv[2]=1
06-30 10:36:01.856   278  1046 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
06-30 10:36:01.856   944  1048 D DSQN    : DSQM DsqnNotification wlan0  1
06-30 10:36:01.857   944  1048 D DSQN    : start to monitor internet connection
06-30 10:36:01.878  5949  5981 D UEI.SmartControl: Internal timer expired: 1
,06-30 10:36:01.888   944  5967 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 30 Jun 2016 08:36:01 GMT], X-Android-Received-Millis=[1467275761887], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467275761857]}
06-30 10:36:01.888   944  5967 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
06-30 10:36:01.889  1870  1886 D WifiServiceExtension: isInternetCheckAvailable return false
06-30 10:36:01.889   944  5967 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
06-30 10:36:01.889   944  5967 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
06-30 10:36:01.891   944  1310 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
06-30 10:36:01.891   944  1310 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-30 10:36:01.891   944  1310 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:36:01.891   944  1310 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:36:01.892   944  1310 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-30 10:36:01.892   944  1310 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.892   944  1310 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
06-30 10:36:01.892   944  1310 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
06-30 10:36:01.892   944  1310 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-30 10:36:01.892   944  1310 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.892   944  1310 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:36:01.892   944  1310 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 10:36:01.893   944   944 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
06-30 10:36:01.894   944  1304 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
06-30 10:36:01.895  1368  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 10:36:01.895   944  1310 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.896   944  1310 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.896  3969  5614 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-30 10:36:01.897   944  1310 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.897   944  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
06-30 10:36:01.898   944  1304 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.898   944  1304 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 10:36:01.900  1775  1775 D TelephonyNetworkFactory-1: new score 60 for exisiting r,equest NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:36:01.903  1775  1775 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,06-30 10:36:01.915  1368  1368 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
06-30 10:36:01.916  1368  1368 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
06-30 10:36:01.917  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 10:36:01.917  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:36:01.917  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
06-30 10:36:01.921  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 10:36:01.921  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 10:36:01.921  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
06-30 10:36:01.921   419   432 I Sensors : sns_pwr.c(301):releasing wakelock
06-30 10:36:01.984  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-30 10:36:01.984  5650  5748 I jxcore-log: 
,06-30 10:36:02.021  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-30 10:36:02.021  5650  5748 I jxcore-log: 
,06-30 10:36:02.028  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-30 10:36:02.028  5650  5748 I jxcore-log: 
06-30 10:36:02.052  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-30 10:36:02.052  5650  5748 I jxcore-log: 
,06-30 10:36:02.059  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-30 10:36:02.059  5650  5748 I jxcore-log: 
06-30 10:36:04.138   944  1305 V WifiInternetCheck: Single check msg out of sync, ignoring.
,06-30 10:36:04.248   944  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-30 10:36:04.256   944  1018 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-30 10:36:04.257  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
06-30 10:36:04.264  2052  2068 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
,06-30 10:36:04.267   944  1018 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 10:36:04.279  5650  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 10:36:04.279  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:36:04.279  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 10:36:04.279  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 10:36:04.279  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 10:36:04.279  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 10:36:04.279  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 10:36:04.279  5650  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-30 10:36:04.289  2052  2068 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
06-30 10:36:04.290  5650  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
06-30 10:36:04.297   944  1019 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6061 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:04.308   944   944 D LocSvc_java: onReceive
06-30 10:36:04.309   944   944 D LocSvc_java: got connectivity action
06-30 10:36:04.309   944  1766 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:04.309   944  1766 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:04.309   944  1766 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:04.309   944  1766 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:04.311   278  1042 E BandwidthController: [LG DATA] No such appUid: 1000
06-30 10:36:04.311   278  1042 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-30 10:36:04.312   278  6067 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:04.312   278  6067 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:04.313   278  6067 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:04.313   278  6067 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:04.314   944  1301 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:04.314   944  1301 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:04.315   944  1301 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:04.315   944  1301 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:04.315   944   944 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
06-30 10:36:04.315   944   944 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
06-30 10:36:04.315   278  1042 E BandwidthController: [LG DATA] No such appUid: 1000
06-30 10:36:04.316   278  1042 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-30 10:36:04.318   278  6068 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:04.318   278  6068 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:04.319   278  6068 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:04.319   278  6068 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:04.322   944   944 D LocSvc_java: getAGpsConnectionInfo connType - 4
,06-30 10:36:04.327   944   944 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
06-30 10:36:04.327   944   944 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
06-30 10:36:04.327   944   944 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
06-30 10:36:04.335   944  6069 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:04.335   944  6069 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:04.336   944  6069 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:04.336   944  6069 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:04.336   278  1042 E BandwidthController: [LG DATA] No such appUid: 1000
06-30 10:36:04.336   278  1042 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
,06-30 10:36:04.338   278  6073 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:04.339   278  6073 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:04.339   278  6073 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:04.340   278  6073 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:04.357   278  6073 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:04.357   278  6067 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:04.357   278  6068 D libc-netbsd: res_queryN name = xxxxx succeed
,06-30 10:36:04.358   944  1766 I System.out: propertyValue:false
,06-30 10:36:04.362   944  6069 I System.out: propertyValue:false
06-30 10:36:04.362   944  1301 I System.out: propertyValue:false
06-30 10:36:04.392   944  6069 D LocSvc_java: NTP server returned: 1467275764351 (Thu Jun 30 10:36:04 GMT+02:00 2016) reference: 157449 certainty: 8 system time offset: -41
,06-30 10:36:04.396   944  6069 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
06-30 10:36:04.399   944  1766 D AlarmManagerService: Setting time of day to sec=1467275764
06-30 10:36:04.353   944  1766 W AlarmManagerService: Unable to set rtc to 1467275764: Invalid argument
06-30 10:36:04.371   944  1674 D LocSvc_java: reportXtraServer 
06-30 10:36:04.371   944  1674 D LocSvc_java:  server1=http://xtrapath1.izatcloud.net/xtra2.bin
06-30 10:36:04.371   944  1674 D LocSvc_java:  server2=http://xtrapath2.izatcloud.net/xtra2.bin
06-30 10:36:04.371   944  1674 D LocSvc_java:  server3=http://xtrapath3.izatcloud.net/xtra2.bin
06-30 10:36:04.371   944  1674 D LocSvc_java: xtraDownloadRequest
06-30 10:36:04.371   944  1674 D LocSvc_java: Sending msg: 6 arg1:0 arg2:1
,06-30 10:36:04.386  2404  2404 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,06-30 10:36:04.390  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:36:04.393  2825  2825 D WeatherService: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 10:36:4
06-30 10:36:04.393  1368  1368 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
06-30 10:36:04.394  2825  2825 D WeatherService: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 10:36:4
06-30 10:36:04.396  1368  1368 I LgeClockWidgetControlView: time changed, timezoneChanged : false
06-30 10:36:04.402   944  6094 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:04.402   944  6094 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:04.408   944  6094 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:04.408   944  6094 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:04.408   278  1042 E BandwidthController: [LG DATA] No such appUid: 1000
06-30 10:36:04.408   278  1042 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-30 10:36:04.409   278  6096 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:04.409   278  6096 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:04.409   278  6096 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:04.409   278  6096 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:04.449   283  1611 V AudioFlinger: 2842 died, releasing its sessions
06-30 10:36:04.450   283  1611 V AudioFlinger:  pid 1775 @ 0
06-30 10:36:04.450   283  1611 V AudioFlinger:  pid 3090 @ 1
06-30 10:36:04.450   283  1611 V AudioFlinger:  pid 3090 @ 2
,06-30 10:36:04.483   944  1019 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=6098 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
06-30 10:36:04.484   278  6096 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:04.485   944  1375 W ActivityManager: getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
06-30 10:36:04.486   944  6094 I System.out: propertyValue:false
06-30 10:36:04.486   944  6094 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:04.486   944  6094 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:04.492  1945  1945 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=30 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
,06-30 10:36:04.507  1945  1945 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 30
,06-30 10:36:04.539   944  6094 D LocSvc_java: calling native_inject_xtra_data
06-30 10:36:04.539   944  6094 D LocSvc_java: Sending msg: 11 arg1:0 arg2:1
06-30 10:36:04.540  1945  1945 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 30
,06-30 10:36:04.545  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-30 10:36:04.573   944  1935 I ActivityManager: Process com.lge.music (pid 2842) has died
,06-30 10:36:04.591   944  1018 E GpsLocationProvider: No APN found to select.
,06-30 10:36:04.618  6098  6098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:36:04.618  6098  6098 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:36:04.620  6098  6098 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,06-30 10:36:04.711   944  1018 I ActivityManager: Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6117 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,06-30 10:36:04.759   944  1355 I ActivityManager: Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6129 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:04.817  6061  6061 I MusicStore: Database version: 120
,06-30 10:36:04.840  6117  6117 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:36:04.842  6117  6117 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 10:36:04.842  6117  6117 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,06-30 10:36:04.884  6098  6098 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,06-30 10:36:04.915  6098  6098 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,06-30 10:36:05.000   944  6159 D LgeGpsConstants: Can't find 'ext_gps.conf'!!
06-30 10:36:05.001   944  6159 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:05.001   944  6159 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:05.001   944  6159 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:05.001   944  6159 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:05.002   278  1042 E BandwidthController: [LG DATA] No such appUid: 1000
,06-30 10:36:05.002   278  1042 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-30 10:36:05.003   278  6161 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:05.003   278  6161 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:36:05.003   278  6161 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:05.004   278  6161 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:05.028  3969  6165 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,06-30 10:36:05.048   944  1018 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 36623, reason: UserStart, SyncResult: databaseError: true stats []
,06-30 10:36:05.051   944  1018 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 189166, reason: UserStart
06-30 10:36:05.054   944  1018 I NotificationManager: android: cancelAsUser(716319171) by android
06-30 10:36:05.064   278  6161 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:05.065   944  6159 I System.out: propertyValue:false
,06-30 10:36:05.103  6117  6117 I AppConfig: Total System Memory = 906309632
06-30 10:36:05.108  6117  6117 I GalleryUtils: Application Heap = 96 MB
06-30 10:36:05.110  6117  6117 I AppConfig: App Tier : NOT_DEF
06-30 10:36:05.111   944  6159 D LgeGpsLocationProvider: NTP server: europe.pool.ntp.org
06-30 10:36:05.111   944  6159 D LgeGpsLocationProvider: NTP server returned: 1467275765120 (Thu Jun 30 10:36:05 GMT+02:00 2016) reference: 158214 certainty: 22 system time offset: 9
,06-30 10:36:05.123  6117  6117 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,06-30 10:36:05.162   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:05.162   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-30 10:36:05.162   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:05.163  6061  6061 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 10:36:05.165   944  1018 I NotificationManager: android: cancelAsUser(-1597574061) by android
,06-30 10:36:05.197  6129  6170 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-30 10:36:05.202  6129  6170 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-30 10:36:05.209   944  1018 I NotificationManager: android: cancelAsUser(-1816247584) by android
,06-30 10:36:05.312   944  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:05.313   944  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:05.313   944  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:05.313   944  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:05.315   278  1042 E BandwidthController: [LG DATA] No such appUid: 1000
06-30 10:36:05.315   278  1042 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-30 10:36:05.315   278  6179 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:05.315   278  6179 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:05.315   278  6179 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:05.316   278  6179 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-30 10:36:05.362   278  6179 D libc-netbsd: res_queryN name = xxxxx succeed
,06-30 10:36:05.364   944  1305 I System.out: propertyValue:false
06-30 10:36:05.369   944  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:05.369   944  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:05.369   944  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:05.369   944  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:05.370   278  1042 E BandwidthController: [LG DATA] No such appUid: 1000
06-30 10:36:05.370   278  1042 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-30 10:36:05.370   278  6182 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:05.370   278  6182 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:05.370   278  6182 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:05.371   278  6182 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:05.371   278  6182 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:05.371   944  1306 I System.out: propertyValue:false
06-30 10:36:05.382  6129  6170 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,06-30 10:36:05.431   944  1306 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,06-30 10:36:05.444   294   360 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 10:36:05.485  6129  6170 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-30 10:36:05.486  6129  6170 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-30 10:36:05.500   944  1018 I art     : Explicit concurrent mark sweep GC freed 77002(3MB) AllocSpace objects, 7(154KB) LOS objects, 33% free, 23MB/35MB, paused 2.928ms total 275.961ms
06-30 10:36:05.532   944  1988 I ActivityManager: Process com.lge.lgdmsclient (pid 5888) has died
,06-30 10:36:05.586   944  1018 I NotificationManager: android: cancelAsUser(-1597574061) by android
,06-30 10:36:05.631   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:05.631   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,06-30 10:36:05.631   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:05.633  6061  6061 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 10:36:05.638  3969  6164 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
06-30 10:36:05.650   944  1018 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6184 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:05.683   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:05.683   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-30 10:36:05.683   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:36:05.684  6061  6061 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 10:36:05.710   944  1924 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6195 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,06-30 10:36:05.752  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-30 10:36:05.752  5650  5748 I jxcore-log: 
,06-30 10:36:05.781  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-30 10:36:05.781  5650  5748 I jxcore-log: 
,06-30 10:36:05.792   944  1018 I NotificationManager: android: cancelAsUser(353845882) by android
06-30 10:36:05.798  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-30 10:36:05.798  5650  5748 I jxcore-log: 
,06-30 10:36:05.887  6061  6061 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-30 10:36:05.887  6061  6061 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 10:36:05.892  6184  6184 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:36:05.976  6129  6191 D ChimeraCfgMgr: Reading stored module config
,06-30 10:36:05.977  6129  6153 I art     : CheckpointMarkThreadRoots callback created = 0xb042d6e0
06-30 10:36:06.001  6195  6224 D ALBootInit: ====action==>android.intent.action.TIME_SET
,06-30 10:36:06.012  6195  6224 D ALBootInit: Alarm ALBootInit: TIME_SET
06-30 10:36:06.015  6195  6224 D Alarms  : [setNextAlert] start
06-30 10:36:06.023  6061  6061 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,06-30 10:36:06.026   944  1018 I NotificationManager: android: cancelAsUser(-591465577) by android
06-30 10:36:06.042   944  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{24a69452 type 2 when 159145 com.android.systemui} when 159145
06-30 10:36:06.056  6195  6224 D Alarms  : [setNextAlert] (1)
,06-30 10:36:06.062  6129  6153 I art     : CheckpointMarkThreadRoots callback created = 0xaaeaa110
06-30 10:36:06.072  6195  6224 D Alarms  :  minTime  = 0
,06-30 10:36:06.075  6195  6224 D Alarms  :  -- OK multi -- 0
06-30 10:36:06.076  6195  6224 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
06-30 10:36:06.077  6195  6224 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
06-30 10:36:06.104  6195  6224 I CommonUtil: BUILD Operator: OPEN
,06-30 10:36:06.108  6195  6224 D Alarms  : broadcastToWidgetProvider : false
06-30 10:36:06.115  6195  6224 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
06-30 10:36:06.142   944  2169 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,06-30 10:36:06.154  6195  6195 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
06-30 10:36:06.157  6195  6195 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@57be840
06-30 10:36:06.157  6129  6129 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
06-30 10:36:06.163  6195  6195 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@57be840
,06-30 10:36:06.170  6195  6195 D QuickCoverProvider: onReceiver
06-30 10:36:06.174  6129  6129 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:06.174  6129  6129 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:06.204  6061  6061 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
06-30 10:36:06.205  6061  6061 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16eeb82e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-30 10:36:06.205  6061  6061 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-30 10:36:06.206  6061  6061 D AndroidMusic: GMSCore installation verified
,06-30 10:36:06.220   944   962 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6239 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:06.244  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-30 10:36:06.244  5650  5748 I jxcore-log: 
,06-30 10:36:06.254   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:06.254   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
06-30 10:36:06.254   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:06.255  6129  6129 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
06-30 10:36:06.290  6061  6061 I ConfigStore: Config Database version: 1
,06-30 10:36:06.354  6239  6239 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:36:06.441  6239  6239 D CalendarApplication: CalendarApplication.onCreate()
,06-30 10:36:06.477   944  1018 I NotificationManager: android: cancelAsUser(-591465577) by android
06-30 10:36:06.487  6239  6239 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
,06-30 10:36:06.488  6239  6239 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@ce19027, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1b2072d4, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@13c5ac7d, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@b66b772, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3acd07c3, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@57be840, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@38059379, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@15e4d8be, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2d6e5d1f, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1d57486c, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@5c2ee35, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@a91c2ca, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1ba5ac3b, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@30a67f58, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@7c138b1, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@36714196, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@38d117, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@36b03904, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@177faeed, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@20f7e122, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@126f67b3, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3279e170, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2d354ce9, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2256ed6e, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2c6ecc0f, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@ff3a49c, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@338ccea5, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1288727a, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3b561a2b, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@27e46e88, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1b20b021, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1d1b3c46, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@151a2e07, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1695eb34, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@29b72d5d, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@5bed6d2, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1021a3a3, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@114086a0, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@13e4259, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@298f8e1e, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@38a0d6ff, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyDa,ta@26376ccc,
06-30 10:36:06.494  6239  6239 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
06-30 10:36:06.499  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-30 10:36:06.499  5650  5748 I jxcore-log: 
06-30 10:36:06.510  6239  6239 D Config  : [init]
,06-30 10:36:06.517  6239  6239 I Config  : LGCalendar ver.4.40.17
06-30 10:36:06.517  6239  6239 I Config  : start check model
06-30 10:36:06.517  6239  6239 I Config  : start check native_ca
06-30 10:36:06.519  6239  6239 I Config  : Config Operator=OPEN, Country=EU
06-30 10:36:06.519  6239  6239 D Config  : [setDefaultValuesToPref]
06-30 10:36:06.519  6239  6239 D Config  : [parseProfiles]
06-30 10:36:06.523  6239  6239 D ProfilesParser: [debug_displayParseInfos] profile.country = null
06-30 10:36:06.523  6239  6239 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
06-30 10:36:06.523  6239  6239 D Config  : [updateProfiletoCountryInfo]
06-30 10:36:06.526  6239  6239 D GeneralPreference: [checkAndMigrateOldPreference]
,06-30 10:36:06.534  6129  6191 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
06-30 10:36:06.538  6129  6191 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000003@DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk': Failed to open oat filename for reading: No such file or directory
06-30 10:36:06.545  6129  6191 D ChimeraFileApk: Classloading successful. Optimized code found.
,06-30 10:36:06.613  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-30 10:36:06.613  5650  5748 I jxcore-log: 
,06-30 10:36:06.623  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-30 10:36:06.623  5650  5748 I jxcore-log: 
06-30 10:36:06.652   944  1895 I ActivityManager: Process com.lge.bnr (pid 5466) has died
,06-30 10:36:06.665  6129  6191 D DynamitePackage: Instantiated singleton DynamitePackage.
,06-30 10:36:06.670  6239  6239 E AgendaWidgetManager: [updateWidgets] 
06-30 10:36:06.680   944  1018 I NotificationManager: android: cancelAsUser(353845882) by android
,06-30 10:36:06.685  6129  6191 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
06-30 10:36:06.691  6239  6273 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
,06-30 10:36:06.728  6239  6273 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,06-30 10:36:06.755  6129  6129 I NotificationManager: com.google.android.youtube: cancel(2) by com.google.android.youtube
,06-30 10:36:06.777  6239  6273 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,06-30 10:36:06.789   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:06.789   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
06-30 10:36:06.789   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:06.789  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
06-30 10:36:06.790  6129  6129 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
06-30 10:36:06.795   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:06.795   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
06-30 10:36:06.795   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:36:06.797  6129  6129 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
06-30 10:36:06.798   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:06.798   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
06-30 10:36:06.798   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:06.800  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
06-30 10:36:06.804  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
06-30 10:36:06.804  6129  6129 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
06-30 10:36:06.808  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,06-30 10:36:06.814  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
06-30 10:36:06.818  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
06-30 10:36:06.824  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,06-30 10:36:06.829  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
06-30 10:36:06.833  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
06-30 10:36:06.837  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,06-30 10:36:06.842  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
06-30 10:36:06.847  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
06-30 10:36:06.850  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,06-30 10:36:06.855  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
06-30 10:36:06.860   944  1924 I ActivityManager: Process com.lge.settings.easy (pid 5859) has died
06-30 10:36:06.866  6239  6273 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
06-30 10:36:06.867  6239  6273 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,06-30 10:36:06.882  6239  6273 I AlertUtils: set default noti to content://media/internal/audio/media/38
,06-30 10:36:06.885  6129  6129 W InstanceID/Rpc: Found 10006
06-30 10:36:06.893  6239  6273 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
06-30 10:36:06.938  2404  2404 I art     : Explicit concurrent mark sweep GC freed 37826(2MB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 14MB/23MB, paused 1.719ms total 151.054ms
,06-30 10:36:06.959   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:06.959   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
06-30 10:36:06.959   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:06.960  6129  6129 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,06-30 10:36:07.144   944  1344 I ActivityManager: Process com.android.settings (pid 5791) has died
,06-30 10:36:07.148  6239  6309 W HolidayIntentService: onHandleIntent
06-30 10:36:07.149  6239  6239 D MonthWidgetProvider: [onReceive]
06-30 10:36:07.149  6239  6239 D CalendarWidgetProvider: [onReceive]
06-30 10:36:07.149  6239  6239 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
06-30 10:36:07.154  6239  6239 D CalendarTypeController: [onUpdateAndInitCalendarTime]
06-30 10:36:07.160  6239  6239 D WeekWidgetProvider: [onReceive]
06-30 10:36:07.160  6239  6239 D CalendarWidgetProvider: [onReceive]
06-30 10:36:07.160  6239  6239 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,06-30 10:36:07.162  6239  6309 D HolidayDataLoader: readJsonAsset : holiday.json
06-30 10:36:07.173  6239  6239 D CalendarTypeController: [onUpdateAndInitCalendarTime]
,06-30 10:36:07.188  2825  2825 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 10:36:7
,06-30 10:36:07.191  2825  2825 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,06-30 10:36:07.194  2825  2825 D Weather_cast: 2 : set auto-update time : 6/30 13:36
06-30 10:36:07.213  2825  2825 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 10:36:7
06-30 10:36:07.213  2825  2825 D WeatherService: 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
06-30 10:36:07.214  2825  2825 D WeatherService: 2 : shouldTimeTickRegistered : false
,06-30 10:36:07.248  6061  6061 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,06-30 10:36:07.262   944  1944 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6326 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
06-30 10:36:07.265  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-30 10:36:07.265  5650  5748 I jxcore-log: 
06-30 10:36:07.277  6239  6309 E HolidayIntentService: onHandleIntent:holiday data empty
,06-30 10:36:07.280  6129  6153 W art     : Suspending all threads took: 10.459ms
06-30 10:36:07.302   944  2169 I ActivityManager: Process com.lge.sync (pid 5838) has died
,06-30 10:36:07.311  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-30 10:36:07.311  5650  5748 I jxcore-log: 
06-30 10:36:07.334  5949  5949 D UEI.SmartControl: Service.onTrimMemory: 60
,06-30 10:36:07.336  5949  5949 E UEI.SmartControl: Setup service releasing memory...
06-30 10:36:07.346  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-30 10:36:07.346  5650  5748 I jxcore-log: 
,06-30 10:36:07.357  1775  1775 I PhoneApp: onTrimMemory: 10
06-30 10:36:07.357  1775  1775 I PhoneApp: trim memory
,06-30 10:36:07.360  6061  6061 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
06-30 10:36:07.362  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-30 10:36:07.362  5650  5748 I jxcore-log: 
06-30 10:36:07.376  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:07.377  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:36:07.384  2019  2019 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,06-30 10:36:07.402  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-30 10:36:07.402  5650  5748 I jxcore-log: 
06-30 10:36:07.403  6326  6326 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1467275767403
06-30 10:36:07.404  6326  6326 D         : TimeServiceNative: User Time to be set is 1467275767403
06-30 10:36:07.404  6326  6326 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
06-30 10:36:07.404  6326  6326 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
06-30 10:36:07.404  6326  6326 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1467275767403
06-30 10:36:07.404  6326  6326 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
06-30 10:36:07.405   320  1059 D QC-time-services: Daemon: Connection accepted:time_genoff
06-30 10:36:07.406   320  6350 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1467275767403
06-30 10:36:07.406   320  6350 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1467275767403, operation = 0
06-30 10:36:07.406   320  6350 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/11/70 12:36:53
06-30 10:36:07.407   320  6350 D QC-time-services: Daemon:Value read from RTC seconds = 27175013000
06-30 10:36:07.407   320  6350 D QC-time-services: Daemon:new time 1467275767403 
06-30 10:36:07.407   320  6350 D QC-time-services: Daemon: delta 1440100754403 genoff 1440100754403 
06-30 10:36:07.407   320  6350 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100754403 to memory
06-30 10:36:07.407   320  6350 D QC-time-services: Daemon:Opening File: /data/time/ats_2
06-30 10:36:07.407   320  6350 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
06-30 10:36:07.410  6129  6343 I NotificationManager: com.google.android.youtube: cancel(10436) by com.google.android.youtube
06-30 10:36:07.416  6061  6061 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-30 10:36:07.439  5949  5949 I art     : Explicit concurrent mark sweep GC freed 153(17KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 339us total 94.232ms
,06-30 10:36:07.448  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-30 10:36:07.448  5650  5748 I jxcore-log: 
06-30 10:36:07.450   320  6350 D QC-time-services: Updating the TOD offset
06-30 10:36:07.450   320  6350 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100754403 to memory
06-30 10:36:07.450   320  6350 D QC-time-services: Daemon:Opening File: /data/time/ats_1
06-30 10:36:07.450   320  6350 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
06-30 10:36:07.452  6129  6345 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:07.452  6129  6345 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:07.453  6129  6345 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:07.453  6129  6345 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:07.457   320  6350 E QC-time-services: Daemon:Update to modem bit set
06-30 10:36:07.457   320  6350 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
06-30 10:36:07.457   320  6350 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124135954403
06-30 10:36:07.457   278  1042 E BandwidthController: [LG DATA] No such appUid: 10100
06-30 10:36:07.457   278  1042 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-30 10:36:07.457   278  6353 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:07.457   278  6353 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:07.458   278  6353 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:07.458  6326  6326 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
06-30 10:36:07.458   278  6353 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:07.460   320  1057 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
06-30 10:36:07.461   320  1059 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,06-30 10:36:07.490  6061  6079 I art     : CheckpointMarkThreadRoots callback created = 0xaaf148c0
,06-30 10:36:07.505   278  6353 D libc-netbsd: res_queryN name = xxxxx succeed
,06-30 10:36:07.506  6129  6345 I System.out: propertyValue:false
06-30 10:36:07.506  6129  6345 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:07.506  6129  6345 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:07.551  6061  6079 I art     : CheckpointMarkThreadRoots callback created = 0xaaf148a0
,06-30 10:36:07.603  6061  6061 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-30 10:36:07.607  6184  6206 I art     : CheckpointMarkThreadRoots callback created = 0xaaf5bd50
06-30 10:36:07.626  6184  6274 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:36:07.634  6184  6206 I art     : CheckpointMarkThreadRoots callback created = 0xaaf5bd40
06-30 10:36:07.666  6061  6061 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,06-30 10:36:07.687  6061  6061 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 10:36:07.721  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-30 10:36:07.721  5650  5748 I jxcore-log: 
,06-30 10:36:07.731  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-30 10:36:07.731  5650  5748 I jxcore-log: 
06-30 10:36:07.758  6098  6098 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,06-30 10:36:07.789  5650  5748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-30 10:36:07.789  5650  5748 I jxcore-log: 
,06-30 10:36:07.811  2052  5901 D BluetoothAdapterService(367319230): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@36b03904
,06-30 10:36:07.816  5650  5748 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
06-30 10:36:07.820  5650  5748 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-30 10:36:07.820  5650  5748 I jxcore-log: 
06-30 10:36:07.827   944  1895 I ActivityManager: Process com.lge.qremote (pid 5927) has died
06-30 10:36:07.829  5949  5949 D UEI.SmartControl: Service.onUnbind: IControl
06-30 10:36:07.830  5949  5949 D UEI.SmartControl: Service.onDestroy
,06-30 10:36:07.836  5949  5949 D UEI.SmartControl: Shutdown IRRCPlayer... 
06-30 10:36:07.837  2019  2019 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
06-30 10:36:07.838  1775  1775 I PhoneApp: onTrimMemory: 10
06-30 10:36:07.838  1775  1775 I PhoneApp: trim memory
06-30 10:36:07.871  5949  5949 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
06-30 10:36:07.871  5949  5949 D irrcClient: ~IrrcClient ++ 
06-30 10:36:07.871  5949  5949 D irrcClient: ~IrrcClient -- 
06-30 10:36:07.871  5949  5949 W irrc_jni: IRRCPlayer_nativeFinalize -- 
,06-30 10:36:07.871  5949  5949 D UEI.SmartControl: Blaster closed
06-30 10:36:07.871  5949  5949 D UEI.SmartControl: Blaster closed
06-30 10:36:07.871  5949  5949 D UEI.SmartControl: Shut down QS...
06-30 10:36:07.872  5949  5949 D UEI.SmartControl: Stopped file observer...
06-30 10:36:07.880  5949  5949 I UEI.SmartControl: QS lib stop result = true
06-30 10:36:07.881  5949  5949 D UEI.SmartControl: QS shutdown complete
06-30 10:36:07.883  6184  6362 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:07.884  6184  6362 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
06-30 10:36:07.884   278  1042 E BandwidthController: [LG DATA] No such appUid: 10086
06-30 10:36:07.884   278  1042 D DnsProxyListener: App 10086 tries DNS query. Accept family:2 protocol:0
06-30 10:36:07.884   278  6366 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:07.884   278  6366 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
06-30 10:36:07.885   278  6366 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:07.910  6061  6148 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,06-30 10:36:07.929   278  6366 D libc-netbsd: res_queryN name = xxxxx succeed
,06-30 10:36:07.967  5650  5748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 10:36:07.967  5650  5748 I jxcore-log: 
06-30 10:36:07.968  5650  5748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
06-30 10:36:07.968  5650  5748 I jxcore-log: 
06-30 10:36:07.969  5650  5748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 10:36:07.969  5650  5748 I jxcore-log: 
,06-30 10:36:08.004   944  1355 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6367 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,06-30 10:36:08.026   307   307 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 369us total 28.012ms
,06-30 10:36:08.050   307   307 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 350us total 23.543ms
,06-30 10:36:08.079   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 812us total 28.623ms
,06-30 10:36:08.083   944  1018 I NotificationManager: android: cancelAsUser(-1548111331) by android
06-30 10:36:08.105  6098  6098 I HubEmail: JNI_OnLoad()
06-30 10:36:08.105  6098  6098 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 10:36:08.105  6098  6098 I HubEmail: registerNatives()
06-30 10:36:08.105  6098  6098 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 10:36:08.105  6098  6098 I HubEmail: registerNativeMethods()
06-30 10:36:08.105  6098  6098 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,06-30 10:36:08.106  6098  6098 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
06-30 10:36:08.145   944  1924 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6385 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,06-30 10:36:08.177   243   243 E lowmemorykiller: Error writing /proc/6117/oom_score_adj; errno=22
,06-30 10:36:08.183   243   243 E lowmemorykiller: Error writing /proc/6117/oom_score_adj; errno=22
06-30 10:36:08.184  6061  6061 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
06-30 10:36:08.195  6098  6384 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:36:08.222   944  1879 I ActivityManager: Process com.android.gallery3d (pid 6117) has died
,06-30 10:36:08.231  1775  1775 I PhoneApp: onTrimMemory: 10
06-30 10:36:08.231  1775  1775 I PhoneApp: trim memory
06-30 10:36:08.234  6061  6061 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 10:36:08.240  2019  2019 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,06-30 10:36:08.278  6061  6402 I MusicLifecycle: Sync started
,06-30 10:36:08.401   944  1935 I art     : Explicit concurrent mark sweep GC freed 25764(1186KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.575ms total 214.800ms
,06-30 10:36:08.417  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:08.446   944  1636 I NotificationManager: android: cancelAsUser(2) by android
,06-30 10:36:08.478  6367  6367 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
06-30 10:36:08.479  6367  6367 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-30 10:36:08.483  6367  6367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 10:36:08.486  6367  6367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 10:36:08.501  6367  6407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,06-30 10:36:08.506  6061  6402 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:08.506  6061  6402 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:08.507  6061  6402 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:08.507  6061  6402 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:08.507  6367  6407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-30 10:36:08.507   278  1042 E BandwidthController: [LG DATA] No such appUid: 10081
06-30 10:36:08.507   278  1042 D DnsProxyListener: App 10081 tries DNS query. Accept family:0 protocol:0
06-30 10:36:08.507   278  6410 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:08.507   278  6410 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:08.508   278  6410 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:08.508   278  6410 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:08.523  6367  6406 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,06-30 10:36:08.528  6367  6406 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,06-30 10:36:08.553   278  6410 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:08.553  6061  6402 I System.out: propertyValue:false
,06-30 10:36:08.562   944  2169 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6415 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
06-30 10:36:08.630  6061  6402 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:08.630  6061  6402 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:08.632   944  1944 I ActivityManager: Process com.lge.clock (pid 6195) has died
06-30 10:36:08.638  1775  1775 I PhoneApp: onTrimMemory: 10
06-30 10:36:08.638  1775  1775 I PhoneApp: trim memory
06-30 10:36:08.639  2019  2019 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,06-30 10:36:08.649  6385  6385 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
06-30 10:36:08.654  6367  6406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
06-30 10:36:08.655  6385  6385 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
06-30 10:36:08.663  1326  1326 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
,06-30 10:36:08.664  1368  1368 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
06-30 10:36:08.664  1368  1368 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
06-30 10:36:08.667  6385  6385 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
06-30 10:36:08.668  6385  6385 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
06-30 10:36:08.669  6385  6385 V [BNRBootReceiver]: Boot Receiver Return
06-30 10:36:08.669  6385  6385 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 10:36:08.670  6367  6367 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
06-30 10:36:08.674  6367  6367 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
06-30 10:36:08.674  6367  6367 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
06-30 10:36:08.676  6367  6367 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
06-30 10:36:08.680  1368  1368 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
,06-30 10:36:08.688  6367  6367 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
06-30 10:36:08.705  6129  6298 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:08.705  6129  6298 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:08.705  6129  6298 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:08.705  6129  6298 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:08.708   278  1042 E BandwidthController: [LG DATA] No such appUid: 10100
06-30 10:36:08.709   278  1042 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-30 10:36:08.709   278  6433 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:08.709   278  6433 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:08.709   278  6433 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:08.709   278  6433 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:08.710   278  6433 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:08.710  6129  6298 I System.out: propertyValue:false
06-30 10:36:08.710  6129  6298 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:08.710  6129  6298 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:08.733  6415  6415 I AppUp4:AppBoxCP: onCreate
06-30 10:36:08.733  6415  6415 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,06-30 10:36:08.750  6415  6415 I AppUp4:DB:  setFingerPrint start
,06-30 10:36:08.753  6415  6415 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
06-30 10:36:08.768  6415  6415 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
,06-30 10:36:08.768  6415  6415 I AppUp4:DB:  SDK version = 21
06-30 10:36:08.769  6415  6415 I AppUp4:DB:  beforefinger == newfinger no write in DB
06-30 10:36:08.770  6415  6415 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
06-30 10:36:08.776  6415  6415 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
06-30 10:36:08.776  6415  6415 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
06-30 10:36:08.780  6415  6415 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,06-30 10:36:08.780  6415  6415 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
06-30 10:36:08.790  6415  6415 I AppUp4:CustModeStarterReceiver: onReceive
06-30 10:36:08.790  6415  6415 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
06-30 10:36:08.791  6129  6298 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:08.791  6129  6298 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:08.796  6415  6415 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3acd07c3
06-30 10:36:08.796  6415  6415 D AppUp4:CustFacade: isCustomizationCompleted : false
,06-30 10:36:08.804  6415  6415 D AppUp4:CustFacade: isSimDevice : true
06-30 10:36:08.805  6415  6415 D AppUp4:CustModeStarterReceiver: begin check event
06-30 10:36:08.805  6415  6415 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
06-30 10:36:08.805  6415  6415 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
06-30 10:36:08.809  6415  6434 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
06-30 10:36:08.809  6415  6434 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
06-30 10:36:08.809  6415  6434 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,06-30 10:36:08.872  3090  3090 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,06-30 10:36:08.873  3090  3090 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,06-30 10:36:08.877  3090  3090 I LgeMiscReceiver: networkInfo.isConnected() = true
06-30 10:36:08.904  3090  3090 D PhoneState: setPdpRejectCasuse : false
,06-30 10:36:08.951   944  2169 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6437 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,06-30 10:36:09.000  6184  6184 I NotificationManager: com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,06-30 10:36:09.097   944  1018 I NotificationManager: android: cancelAsUser(2145784878) by android
,06-30 10:36:09.173   944  1018 I NotificationManager: android: cancelAsUser(-1816247584) by android
06-30 10:36:09.175   944  1879 I ActivityManager: Killing 5949:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,06-30 10:36:09.213  6437  6437 D PhoneMonitor: Register our PhoneStateListener
,06-30 10:36:09.243   944  2169 W libprocessgroup: failed to open /acct/uid_10089/pid_5949/cgroup.procs: No such file or directory
,06-30 10:36:09.303   944  1018 I ActivityManager: Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6456 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 10:36:09.330  6437  6437 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,06-30 10:36:09.331  6437  6437 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
06-30 10:36:09.335   944  2169 I ActivityManager: Killing 6129:com.google.android.youtube/u0a100 (adj 15): empty #11
,06-30 10:36:09.358  6437  6437 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,06-30 10:36:09.362  6437  6437 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
06-30 10:36:09.367  6437  6437 D TelephonyAutoProfiling: [parse] Load xml
06-30 10:36:09.372  6437  6437 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
06-30 10:36:09.373  6437  6437 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,06-30 10:36:09.379  6437  6437 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,06-30 10:36:09.427   944  1355 W libprocessgroup: failed to open /acct/uid_10100/pid_6129/cgroup.procs: No such file or directory
,06-30 10:36:09.454  2427  2427 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,06-30 10:36:09.465  2427  2427 V DownloadManager: DownloadService onCreate
06-30 10:36:09.470  2427  6475 I DownloadManager: in removeSpuriousFiles
,06-30 10:36:09.481  2427  6475 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
06-30 10:36:09.482  2427  2427 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
,06-30 10:36:09.483  2427  6475 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@298f8e1e on behalf of 2427
06-30 10:36:09.494  2427  6475 I DownloadManager: in trimDatabase
06-30 10:36:09.495  2427  6475 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,06-30 10:36:09.497  2427  6475 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@26376ccc on behalf of 2427
06-30 10:36:09.506   944  2720 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6479 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,06-30 10:36:09.509  3969  6477 I CheckinChimeraService: Checking schedule, now: 1467275769509 next: 1467273897027
06-30 10:36:09.509  3969  6477 I CheckinChimeraService: active receiver: enabled
06-30 10:36:09.509  2427  2427 V DownloadManager: DownloadService onStartCommand
06-30 10:36:09.536  2427  6476 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,06-30 10:36:09.545  2427  6476 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@9226e2a on behalf of 2427
06-30 10:36:09.569  6061  6402 I MusicSyncAdapter: Skipping periodic sync. Last sync was 1960 seconds ago. Frequency: 86400
,06-30 10:36:09.572  3969  6477 I CheckinChimeraService: Preparing to send checkin request
06-30 10:36:09.576  3969  6477 I EventLogChimeraService: Accumulating logs since 1467275042283
,06-30 10:36:09.629  3969  4150 D NetworkUsageDbReporter: Started reporting usage
,06-30 10:36:09.643  3969  4094 I Icing   : Performing maintenance.
,06-30 10:36:09.684  2427  2427 V DownloadManager: DownloadService onDestroy
,06-30 10:36:09.703  6479  6479 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
06-30 10:36:09.705  6479  6479 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,06-30 10:36:09.717  2825  2825 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:36:9
06-30 10:36:09.729  2825  2825 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,06-30 10:36:09.731  6061  6405 W MusicApiClient: Activity events list is null or empty. Skip reporting.
06-30 10:36:09.737  6479  6479 V DrmService: Service onCreate
06-30 10:36:09.738  2825  2825 D WeatherAncestor: connectivity changed - connection : true
06-30 10:36:09.738  2825  2825 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-30 10:36:09.738  2825  2825 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:36:9
06-30 10:36:09.739  2825  2825 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
06-30 10:36:09.739  2825  2825 D WeatherService: 2 : shouldTimeTickRegistered : false
06-30 10:36:09.739  6479  6479 D DrmService: Received new request = 2
06-30 10:36:09.743  6061  6402 I MusicLifecycle: Sync ended
,06-30 10:36:09.749  6479  6504 I DrmSntpClient: Start Sync process
06-30 10:36:09.749  6479  6504 D DrmSntpClient: Server : 0
,06-30 10:36:09.765   944  1018 I NotificationManager: android: cancelAsUser(-1123058983) by android
06-30 10:36:09.774  6479  6504 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:09.774  6479  6504 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:09.774  6479  6504 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:09.774  6479  6504 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:09.775   278  1042 E BandwidthController: [LG DATA] No such appUid: 10051
06-30 10:36:09.775   278  1042 D DnsProxyListener: App 10051 tries DNS query. Accept family:0 protocol:0
06-30 10:36:09.776   278  6505 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:09.776   278  6505 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:09.776   278  6505 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:09.776   278  6505 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:09.793  2404  6507 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:09.793  2404  6507 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:09.793  2404  6507 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:09.793  2404  6507 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:09.794   278  1042 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 10:36:09.794   278  1042 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 10:36:09.794   278  6508 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:09.794   278  6508 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:09.794   278  6508 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:09.795   278  6508 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-30 10:36:09.821   278  6505 D libc-netbsd: res_queryN name = xxxxx succeed
,06-30 10:36:09.822  6479  6504 I System.out: propertyValue:false
06-30 10:36:09.831  3969  4150 D NetworkUsageDbReporter: Finished reporting usage.
06-30 10:36:09.836   278  6508 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:09.837  2404  6507 I System.out: propertyValue:false
,06-30 10:36:09.844  6479  6504 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
06-30 10:36:09.850  5381  5407 I art     : Explicit concurrent mark sweep GC freed 1829(81KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 507us total 85.326ms
,06-30 10:36:09.853   289   289 V ILGDrmService: eDRM_SetDRMTime +++
06-30 10:36:09.863   289   289 I LGDRM   : [DRM] SET TIME : YR=2016, MON=6, DAY=30
06-30 10:36:09.863   289   289 I LGDRM   : [DRM] SET TIME : HR=8, MIN=36, SEC=8
,06-30 10:36:09.877  3969  6506 W IcingInternalCorpora: getNumBytesRead when not calculated.
06-30 10:36:09.879   289   289 V ILGDrmService: eDRM_SetDRMTime ---
06-30 10:36:09.879  6479  6504 I DrmSntpClient: Synched
,06-30 10:36:09.881  6479  6479 D DrmService: Completed !! request = 2
06-30 10:36:09.881  6479  6479 D DrmService: Request count = 0
06-30 10:36:09.883  6479  6479 V DrmService: Service onDestroy
06-30 10:36:09.901   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:09.901   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-30 10:36:09.901   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:36:09.904  6456  6515 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
06-30 10:36:09.912   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:09.912   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-30 10:36:09.912   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:09.912  6456  6515 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-30 10:36:09.924  2404  6507 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:09.924  2404  6507 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:09.942  3969  6510 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,06-30 10:36:09.947  3969  6517 I iu.SyncManager: SYNC; picasa accounts
06-30 10:36:09.949  6456  6456 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
06-30 10:36:09.949  6456  6456 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
06-30 10:36:09.949  6456  6456 I GAv4    :   adb logcat -s GAv4
06-30 10:36:09.961   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:09.961   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-30 10:36:09.961   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:09.962  6456  6518 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,06-30 10:36:09.967   944  1018 I NotificationManager: android: cancelAsUser(-591465577) by android
06-30 10:36:09.976   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:09.976   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-30 10:36:09.976   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:09.979  6456  6518 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,06-30 10:36:09.982  6456  6456 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
06-30 10:36:10.007  3969  3969 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,06-30 10:36:10.020  3969  3969 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,06-30 10:36:10.029  6456  6456 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
06-30 10:36:10.041  6456  6522 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,06-30 10:36:10.056  3969  6517 I iu.UploadsManager: num queued entries: 0
,06-30 10:36:10.057  3969  6517 I iu.UploadsManager: num updated entries: 0
06-30 10:36:10.060  3969  6517 I iu.SyncManager: NEXT; no task
06-30 10:36:10.063  2404  6507 I GCM     : GCM config loaded
06-30 10:36:10.120  3969  6529 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
06-30 10:36:10.120  3969  6529 D SchedPeriodicTask: Scheduled AdAttestation task.
,06-30 10:36:10.182  3969  6477 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,06-30 10:36:10.195   944  2189 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6533 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
06-30 10:36:10.211  3969  6477 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,06-30 10:36:10.267  2404  6531 I GCM     : Ack for not saved message 25
06-30 10:36:10.292  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:10.392  6533  6533 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 10:36:10.448   294   360 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 10:36:10.494   944  1944 I art     : Explicit concurrent mark sweep GC freed 26746(1231KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.227ms total 154.575ms
,06-30 10:36:10.522   944  1636 I ActivityManager: Process com.lge.email (pid 6098) has died
,06-30 10:36:10.619  2404  2457 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:36:10.619  2404  2457 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:10.621  2404  2457 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:10.621  2404  2457 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:10.622   278  1042 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 10:36:10.622   278  1042 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 10:36:10.623   278  6566 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:10.623   278  6566 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:10.623   278  6566 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:10.623   278  6566 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:10.641  6456  6456 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,06-30 10:36:10.646   944  1018 I NotificationManager: android: cancelAsUser(-1874035846) by android
,06-30 10:36:10.670   278  6566 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:10.671  2404  2457 I System.out: propertyValue:false
,06-30 10:36:10.720  6456  6456 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3825-3827)
,06-30 10:36:10.720  6456  6456 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:36:10.745  2404  2457 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:10.745  2404  2457 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:10.748  6456  6456 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b6f1394}
,06-30 10:36:10.750  6456  6456 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:36:10.750  6456  6456 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 10:36:10.766  6456  6456 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 10:36:10.767  6456  6456 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:36:10.769  6456  6456 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 10:36:10.791  6456  6456 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,06-30 10:36:10.800  6456  6456 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-30 10:36:10.800  6456  6456 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:36:10.801  6456  6456 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:36:10.801  6456  6456 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:36:10.801  6456  6456 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 10:36:10.801  6456  6456 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 10:36:10.801  6456  6456 I Adreno-EGL: Remote Branch: 
06-30 10:36:10.801  6456  6456 I Adreno-EGL: Local Patches: 
06-30 10:36:10.801  6456  6456 I Adreno-EGL: Reconstruct Branch: 
06-30 10:36:10.804   944  1988 I ActivityManager: Process com.android.calendar (pid 6239) has died
,06-30 10:36:10.854   944  2025 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6578 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
06-30 10:36:10.887   283   283 V AudioPolicyService: registerClient() client 0xb3848b60, uid 10079
,06-30 10:36:10.891  6456  6592 W AudioManagerAndroid: Requires BLUETOOTH permission
06-30 10:36:10.914  6456  6456 I NSApplication: Starting up...
,06-30 10:36:10.918  3969  6568 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
06-30 10:36:10.957  6533  6611 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
06-30 10:36:10.957  6533  6611 I Babel_SMS: MmsConfig.loadMmsSettings
,06-30 10:36:10.972   944  2025 I ActivityManager: Process com.lge.bnr (pid 6385) has died
,06-30 10:36:10.991  6456  6614 I SyncAdapterService: Ignoring sync request for non-current account
,06-30 10:36:10.998  6533  6611 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-30 10:36:10.999  6533  6611 I Babel_SMS: MmsConfig.loadFromDatabase
06-30 10:36:11.006  6578  6578 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 10:36:11.006  6578  6578 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 10:36:11.048  6533  6611 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,06-30 10:36:11.048  6533  6611 I Babel_SMS: MmsConfig.loadFromResources
06-30 10:36:11.050  6533  6611 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
06-30 10:36:11.051  6533  6611 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-30 10:36:11.061  6578  6578 I MultiDex: VM with version 2.1.0 has multidex support
06-30 10:36:11.061  6578  6578 I MultiDex: install
06-30 10:36:11.061  6578  6578 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 10:36:11.067  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:36:11.089   944  1895 I NotificationManager: android: cancelAsUser(2) by android
,06-30 10:36:11.108  6533  6547 I art     : CheckpointMarkThreadRoots callback created = 0xb042d870
,06-30 10:36:11.114   944  2169 I NotificationManager: android: cancelAsUser(2) by android
,06-30 10:36:11.136  6578  6578 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
06-30 10:36:11.144  6533  6547 I art     : CheckpointMarkThreadRoots callback created = 0xb042d860
06-30 10:36:11.151  3969  6568 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:11.151  3969  6568 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:11.152  3969  6568 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:11.152  3969  6568 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:36:11.152   278  1042 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 10:36:11.152   278  1042 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 10:36:11.153  2404  2457 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
06-30 10:36:11.154   278  6619 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:11.154   278  6619 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:11.154   278  6619 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:11.155   278  6619 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:11.155   278  6619 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:11.156  3969  6568 I System.out: propertyValue:false
06-30 10:36:11.172  6533  6533 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
06-30 10:36:11.172  6533  6533 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
06-30 10:36:11.172  6533  6533 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
06-30 10:36:11.172  6533  6533 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
06-30 10:36:11.172  6533  6533 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
06-30 10:36:11.172  6533  6533 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
06-30 10:36:11.173  6533  6533 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
06-30 10:36:11.173  6533  6533 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
06-30 10:36:11.173  6533  6533 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
06-30 10:36:11.173  6533  6533 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
06-30 10:36:11.173  6533  6533 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
06-30 10:36:11.173  6533  6533 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
06-30 10:36:11.173  6533  6533 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
06-30 10:36:11.173  6533  6533 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
06-30 10:36:11.173  6533  6533 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
06-30 10:36:11.173  6533  6533 D SensorManager: found sensor: Motion Accel, handle=46
,06-30 10:36:11.211   944  1018 I NotificationManager: android: cancelAsUser(-701419433) by android
06-30 10:36:11.213  6578  6578 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
06-30 10:36:11.214  6578  6578 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22248964: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-30 10:36:11.214  6578  6578 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-30 10:36:11.216  6578  6578 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
06-30 10:36:11.216  6578  6578 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
06-30 10:36:11.233  3969  4094 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:11.233  3969  4094 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:11.233  3969  4094 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:11.233  3969  4094 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:11.235   278  1042 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 10:36:11.235   278  1042 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 10:36:11.235   278  6622 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:11.235   278  6622 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:11.236  6578  6578 D ChimeraCfgMgr: Reading stored module config
06-30 10:36:11.236   278  6622 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:11.236   278  6622 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-30 10:36:11.257  6533  6533 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:36:11.266  6533  6533 I Babel_Crash: startup - clean
06-30 10:36:11.267   944  1018 I NotificationManager: android: cancelAsUser(1500439826) by android
,06-30 10:36:11.272   278  6622 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:11.273  3969  4094 I System.out: propertyValue:false
06-30 10:36:11.335  6533  6624 I Babel   : deleted: false for 0
,06-30 10:36:11.347   944  1018 I ActivityManager: Start proc com.lge.qmemoplus for service com.lge.qmemoplus/.network.googledrive.DriveSyncService: pid=6626 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
06-30 10:36:11.371  3969  4094 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:36:11.371  3969  4094 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:11.431  6578  6621 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,06-30 10:36:11.472  6578  6578 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
06-30 10:36:11.473  6578  6578 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
06-30 10:36:11.511  6533  6533 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,06-30 10:36:11.523  6626  6626 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:36:11.534   944  1355 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6644 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:11.570  6533  6533 W AudioCapabilities: Unsupported mime audio/adpcm
,06-30 10:36:11.574  6533  6533 W AudioCapabilities: Unsupported mime audio/g726
,06-30 10:36:11.575  6533  6533 W AudioCapabilities: Unsupported mime audio/x-ms-wma
06-30 10:36:11.578  6533  6533 W AudioCapabilities: Unsupported mime audio/wma-voice
06-30 10:36:11.580  6533  6533 W VideoCapabilities: Unsupported mime video/mjpg
06-30 10:36:11.618  6533  6533 W VideoCapabilities: Unsupported mime video/theora
,06-30 10:36:11.697  6626  6626 E App     : [App][onCreate()] 4.40.23
,06-30 10:36:11.704  6578  6604 I art     : CheckpointMarkThreadRoots callback created = 0xb042d360
06-30 10:36:11.728   283  1317 D WVCdm   : Instantiating CDM.
,06-30 10:36:11.733  6533  6533 W AudioCapabilities: Unsupported mime audio/evrc
06-30 10:36:11.735  6533  6533 W AudioCapabilities: Unsupported mime audio/qcelp
06-30 10:36:11.736  6533  6533 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 10:36:11.741   283  1611 I WVCdm   : CdmEngine::OpenSession
,06-30 10:36:11.741   283  1611 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,06-30 10:36:11.768  6533  6533 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
06-30 10:36:11.770  6533  6533 W AudioCapabilities: Unsupported mime audio/qcelp
,06-30 10:36:11.770  6578  6604 I art     : CheckpointMarkThreadRoots callback created = 0xb042d350
06-30 10:36:11.774  6533  6533 W AudioCapabilities: Unsupported mime audio/evrc
06-30 10:36:11.791  6578  6604 I art     : Background partial concurrent mark sweep GC freed 1894(269KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 6.950ms total 87.238ms
,06-30 10:36:11.803  6533  6533 W VideoCapabilities: Unsupported mime video/mp4v-esdp
06-30 10:36:11.824  6533  6533 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-30 10:36:11.836  6533  6533 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 10:36:11.838  6533  6533 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-30 10:36:11.842  6533  6533 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-30 10:36:11.852   283  1611 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
06-30 10:36:11.852   283  1611 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
06-30 10:36:11.852   283  1611 W WVCdm   : L1 library not specified. Falling Back to L3
06-30 10:36:11.881  6533  6533 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-30 10:36:11.907  6578  6654 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:11.908  6578  6654 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:11.908  6578  6654 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:11.908  6578  6654 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:11.908   278  1042 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 10:36:11.908   278  1042 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,06-30 10:36:11.908   278  6668 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:11.909   278  6668 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:11.909   278  6668 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:11.909   278  6668 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:11.909   278  6668 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:11.910  6578  6654 I System.out: propertyValue:false
06-30 10:36:11.927  6533  6533 I vclib   : onServiceConnected
06-30 10:36:11.928  6533  6533 W Babel   : Attempted to change video mute state without an active call.
,06-30 10:36:11.944  6533  6533 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,06-30 10:36:11.956  6533  6666 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:11.956  6533  6666 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:11.957  6533  6666 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:11.957  6533  6666 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:11.957   278  1042 E BandwidthController: [LG DATA] No such appUid: 10061
06-30 10:36:11.957   278  1042 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
06-30 10:36:11.958   278  6670 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:11.959   278  6670 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:36:11.959   278  6670 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:11.959   278  6670 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:11.960   278  6670 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:11.974  6578  6654 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:11.974  6578  6654 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:11.980  6533  6666 I System.out: propertyValue:false
06-30 10:36:12.004   283  1611 I WVCdm   : CdmEngine::QueryKeyControlInfo
06-30 10:36:12.006   283  1317 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-30 10:36:12.006   283  1317 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-30 10:36:12.006   283  1317 I WVCdm   : CdmEngine::GenerateKeyRequest
,06-30 10:36:12.029   283  1317 D WVCdm   : PrepareKeyRequest: nonce=3168932300
,06-30 10:36:12.048  6533  6666 I Babel   : connection state changed from UNKNOWN to CONNECTED
,06-30 10:36:12.135  6626  6626 D AccountManager: setSyncFrequency
,06-30 10:36:12.168  3969  4094 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,06-30 10:36:12.188   944  1018 I NotificationManager: android: cancelAsUser(2126026182) by android
,06-30 10:36:12.209  6626  6626 D DriveSyncService: onCreate
06-30 10:36:12.210  6626  6626 D DriveSyncService: onBind
,06-30 10:36:12.234  6626  6674 D DriveSyncAdapter: onPerformSync() START
,06-30 10:36:12.235  6626  6674 D DriveSyncAdapter: Not added account. Stop
,06-30 10:36:12.248   944  1018 I NotificationManager: android: cancelAsUser(1312559638) by android
,06-30 10:36:12.342   944  1018 I ActivityManager: Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6677 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:12.450   283  1611 I WVCdm   : CdmEngine::OpenSession
06-30 10:36:12.451   944  1636 I ActivityManager: Killing 6326:com.qualcomm.timeservice/1000 (adj 15): empty #11
,06-30 10:36:12.534   944  2189 I ActivityManager: Killing 6367:com.lge.lgdmsclient/1000 (adj 15): empty #11
,06-30 10:36:12.615   944  1935 W libprocessgroup: failed to open /acct/uid_1000/pid_6326/cgroup.procs: No such file or directory
,06-30 10:36:12.617   944  1988 W libprocessgroup: failed to open /acct/uid_1000/pid_6367/cgroup.procs: No such file or directory
06-30 10:36:12.621  6697  6697 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=45 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
06-30 10:36:12.643  1368  1368 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,06-30 10:36:12.652  3969  6696 I RemindersSync: Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=562:priority=5:group=main]
06-30 10:36:12.653  3969  4094 I Icing   : Performing maintenance usage 1881853 budget 840921982 free 99.776% index free 99.972% purge? false target 588645387
06-30 10:36:12.671  3969  4094 I Icing   : Starting compaction min disk 99.776% min index 99.972%
,06-30 10:36:12.681  1775  1805 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
06-30 10:36:12.696  1775  1805 D PhoneUtils: getPhoneCount() sPhoneCount = 1
,06-30 10:36:12.696  1775  1805 D PhoneUtils: getPhoneCount() sPhoneCount = 1
,06-30 10:36:12.714  1775  1805 V TelecomServiceImpl: getCallState : 0
,06-30 10:36:12.716  1775  1801 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
,06-30 10:36:12.716  1775  1801 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-30 10:36:12.716  1775  1801 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-30 10:36:12.721  1368  1368 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
06-30 10:36:12.723  1368  1368 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
06-30 10:36:12.783   944  1944 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6702 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,06-30 10:36:12.806   307   307 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 22.830ms
,06-30 10:36:12.811  6697  6697 I dex2oat : dex2oat took 186.447ms (threads: 4)
06-30 10:36:12.829   944  1018 I NotificationManager: android: cancelAsUser(898701380) by android
,06-30 10:36:12.829   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 22.812ms
06-30 10:36:12.835  6578  6654 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:36:12.835  6578  6654 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:36:12.835  6578  6654 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 10:36:12.835  6578  6654 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 10:36:12.835  6578  6654 I Adreno-EGL: Remote Branch: 
06-30 10:36:12.835  6578  6654 I Adreno-EGL: Local Patches: 
06-30 10:36:12.835  6578  6654 I Adreno-EGL: Reconstruct Branch: 
06-30 10:36:12.853   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 316us total 23.793ms
,06-30 10:36:13.008  6578  6654 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:36:13.008  6578  6654 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:36:13.008  6578  6654 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 10:36:13.008  6578  6654 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 10:36:13.008  6578  6654 I Adreno-EGL: Remote Branch: 
06-30 10:36:13.008  6578  6654 I Adreno-EGL: Local Patches: 
06-30 10:36:13.008  6578  6654 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:36:13.022   944  1944 I ActivityManager: Process com.google.android.music:main (pid 6061) has died
,06-30 10:36:13.034  6702  6702 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,06-30 10:36:13.040  2825  2825 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:36:13
06-30 10:36:13.042  2825  2825 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-30 10:36:13.043  2825  2825 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
06-30 10:36:13.043  2825  2825 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:36:13
06-30 10:36:13.043  2825  2825 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
06-30 10:36:13.049  2825  2825 D WeatherService: 2 : shouldTimeTickRegistered : false
,06-30 10:36:13.093   944  1636 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,06-30 10:36:13.130  3969  4094 I Icing   : Usage reports aged/total 0/0
,06-30 10:36:13.134  1945  1945 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
06-30 10:36:13.178  1945  2581 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
06-30 10:36:13.178  1945  2581 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
06-30 10:36:13.179  1945  2581 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,06-30 10:36:13.193   944  1895 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6725 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
06-30 10:36:13.203  1945  2581 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
06-30 10:36:13.205  1945  2581 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
,06-30 10:36:13.247   944  2169 I ActivityManager: Process com.lge.appbox.client (pid 6415) has died
,06-30 10:36:13.263  6677  6739 I Gmail   : getAccountsCursor
,06-30 10:36:13.309  6677  6677 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,06-30 10:36:13.318  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:13.357  5381  5407 I art     : Explicit concurrent mark sweep GC freed 2968(119KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 814us total 72.968ms
06-30 10:36:13.535   944  2720 I art     : Explicit concurrent mark sweep GC freed 23337(984KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.094ms total 179.433ms
,06-30 10:36:13.540  3969  4094 I Icing   : Done compaction min disk 99.776% min index 99.972% num docs 84 old 285 trimmed 0 err 0
,06-30 10:36:13.565  3969  4846 I Icing   : Query from com.google.android.gms package restrict com.google.android.gms start 0 num 100
,06-30 10:36:13.572   944  1344 I ActivityManager: Process com.google.android.setupwizard (pid 6437) has died
06-30 10:36:13.574   944  1355 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
06-30 10:36:13.576   944  1375 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
06-30 10:36:13.587  6578  6654 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:36:13.587  6578  6654 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:36:13.587  6578  6654 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 10:36:13.587  6578  6654 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 10:36:13.587  6578  6654 I Adreno-EGL: Remote Branch: 
06-30 10:36:13.587  6578  6654 I Adreno-EGL: Local Patches: 
06-30 10:36:13.587  6578  6654 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:36:13.596  6725  6725 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
06-30 10:36:13.598  6677  6754 W Gmail   : Sync started for account: account:61035162
,06-30 10:36:13.615  6725  6725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
06-30 10:36:13.624  1368  1368 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
06-30 10:36:13.624  1326  1326 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
06-30 10:36:13.624  1368  1368 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
06-30 10:36:13.624  1368  1368 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
06-30 10:36:13.625  6677  6756 E Gmail   : Error finding the version of the Email provider.....
06-30 10:36:13.625  6677  6756 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
06-30 10:36:13.625  6677  6756 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
06-30 10:36:13.625  6677  6756 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
06-30 10:36:13.625  6677  6756 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
06-30 10:36:13.625  6677  6756 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:36:13.625  6677  6756 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:36:13.625  6677  6756 E Gmail   : 	at android.os.Looper.loop(Looper.java:135)
06-30 10:36:13.625  6677  6756 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:36:13.625  6677  6758 I Gmail   : getAccountsCursor
06-30 10:36:13.628  6677  6756 W EmailMigration: We do not support migrating this version of the Email provider.
,06-30 10:36:13.633  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:36:13.637   944  1636 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
06-30 10:36:13.637  6677  6753 I Gmail   : Observing account changes for notifications
06-30 10:36:13.637  6725  6725 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
,06-30 10:36:13.642  6725  6725 V [BNRBootReceiver]: Boot Receiver Return
,06-30 10:36:13.644  6725  6725 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 10:36:13.669  2404  6720 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 10:36:13.691  2404  6720 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,06-30 10:36:13.694  2404  6720 V BaseAppContext: GmsRequestQueue started.
06-30 10:36:13.744  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:13.770   944  1636 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=6766 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:13.834  3969  4094 I art     : Explicit concurrent mark sweep GC freed 51448(3MB) AllocSpace objects, 38(631KB) LOS objects, 24% free, 16MB/22MB, paused 1.313ms total 214.149ms
,06-30 10:36:13.864  2404  6564 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:13.864  2404  6564 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:13.865  2404  6564 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:13.865  2404  6564 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:13.865   278  1042 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 10:36:13.866   278  1042 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 10:36:13.866   278  6784 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:13.866   278  6784 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:13.866   278  6784 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:13.867   278  6784 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:13.867   278  6784 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:13.869  2404  6564 I System.out: propertyValue:false
06-30 10:36:13.941  2404  6564 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:13.941  2404  6564 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:13.991  6677  6765 I Gmail   : notifyAccountChanged
,06-30 10:36:13.997  6677  6765 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
06-30 10:36:14.006  6677  6786 I Gmail   : getAccountsCursor
,06-30 10:36:14.010  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:14.015  6677  6765 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
06-30 10:36:14.029  6677  6754 I Gmail   : notifyAccountChanged
,06-30 10:36:14.036  6677  6765 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
06-30 10:36:14.048  6677  6765 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,06-30 10:36:14.203  6677  6739 I Gmail   : getAccountsCursor
,06-30 10:36:14.205  2404  6763 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:14.205  2404  6763 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:14.205  2404  6763 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:14.205  2404  6763 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:14.205   278  1042 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 10:36:14.205   278  1042 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 10:36:14.205   278  6790 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:14.205   278  6790 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:14.206   278  6790 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:14.206   278  6790 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:14.206   278  6790 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:14.207  2404  6763 I System.out: propertyValue:false
06-30 10:36:14.231  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:14.289  6677  6754 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 24333, normalSync: true
,06-30 10:36:14.372   944  2189 I ActivityManager: Process com.google.android.talk (pid 6533) has died
,06-30 10:36:14.409  6766  6766 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
,06-30 10:36:14.428  6677  6754 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 10:36:14.428  6677  6754 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 10:36:14.592  6677  6754 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
06-30 10:36:14.632   944  2720 I ActivityManager: Process com.lge.drmservice (pid 6479) has died
,06-30 10:36:14.646   283   283 I WVCdm   : CdmEngine::CloseSession
06-30 10:36:14.680  6677  6754 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-30 10:36:14.681  6677  6754 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-30 10:36:14.740   283  1611 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-30 10:36:14.742   283   283 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-30 10:36:14.742   283   283 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-30 10:36:14.742   283   283 I WVCdm   : CdmEngine::GenerateKeyRequest
06-30 10:36:14.746   283  1611 I WVCdm   : CdmEngine::OpenSession
06-30 10:36:14.749   283   283 D WVCdm   : PrepareKeyRequest: nonce=4155685547
06-30 10:36:14.756  6766  6766 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(171): No need to run daily hygiene.
,06-30 10:36:14.780  6766  6766 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,06-30 10:36:14.781  6766  6766 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-30 10:36:14.786  6766  6766 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
06-30 10:36:14.807  6766  6766 I Finsky  : [1] com.google.android.finsky.utils.bk.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,06-30 10:36:14.834  2404  4152 I art     : Explicit concurrent mark sweep GC freed 93245(5MB) AllocSpace objects, 43(711KB) LOS objects, 40% free, 15MB/25MB, paused 1.769ms total 147.189ms
,06-30 10:36:14.839  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:36:14.860   944   962 I NotificationManager: android: cancelAsUser(2) by android
,06-30 10:36:14.863  6677  6693 I art     : CheckpointMarkThreadRoots callback created = 0xaaf6a220
06-30 10:36:14.888  2427  5039 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
,06-30 10:36:14.895  2427  5039 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@13d489b8 on behalf of 6766
06-30 10:36:14.899  2404  6720 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,06-30 10:36:14.911  6677  6693 I art     : CheckpointMarkThreadRoots callback created = 0x9ec37dd0
,06-30 10:36:14.934   944  2189 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.download.MusicCommunicator: pid=6818 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:15.021  6766  6766 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1226): Installer kick - no action, not running yet
,06-30 10:36:15.035  6766  6766 I Finsky  : [1] com.google.android.finsky.j.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
06-30 10:36:15.035  6766  6766 I Finsky  : [1] com.google.android.finsky.j.j.run(214): Finished loading 1 libraries.
06-30 10:36:15.039  2404  2404 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=971bd22f-ee0f-4090-9158-a0109867a777
06-30 10:36:15.046  6766  6766 I Finsky  : [1] com.google.android.finsky.c.l.a(270): result=false type=4
,06-30 10:36:15.076   944  1018 I NotificationManager: android: cancelAsUser(1222422273) by android
06-30 10:36:15.089  6766  6766 I Finsky  : [1] com.google.android.finsky.services.bc.a(1050): Restore complete with 0 success and 0 failed.
,06-30 10:36:15.159  2404  2656 I GCoreUlr: DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,06-30 10:36:15.162  6677  6754 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:15.162  6677  6754 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:15.162  6677  6754 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:15.162  6677  6754 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:15.163   278  1042 E BandwidthController: [LG DATA] No such appUid: 10053
06-30 10:36:15.163   278  1042 D DnsProxyListener: App 10053 tries DNS query. Accept family:0 protocol:0
06-30 10:36:15.163   278  6840 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:15.163   278  6840 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:15.164   278  6840 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:15.164   278  6840 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:15.170  2404  2656 I GCoreUlr: Unbound from all location providers
06-30 10:36:15.170  2404  2656 I GCoreUlr: Place inference reporting - stop
06-30 10:36:15.179  2404  2404 I GCoreUlr: DispatchingService.onDestroy()
06-30 10:36:15.179  2404  2404 I GCoreUlr: Stopping handler for UlrDispSvcFast
,06-30 10:36:15.184  2404  2404 I GCoreUlr: Unbound from all location providers
06-30 10:36:15.184  2404  2404 I GCoreUlr: Place inference reporting - stop
06-30 10:36:15.209   278  6840 D libc-netbsd: res_queryN name = xxxxx succeed
,06-30 10:36:15.210  6677  6754 I System.out: propertyValue:false
06-30 10:36:15.211  6677  6754 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:15.211  6677  6754 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:15.285  6818  6818 I MusicStore: Database version: 120
,06-30 10:36:15.453   294   360 I ThermalEngine: Sensor:pa_therm0:34000 mC
,06-30 10:36:15.492   944  1636 I ActivityManager: Process com.google.android.apps.magazines (pid 6456) has died
,06-30 10:36:15.505  2404  2690 W GCoreFlp: No location to return for getLastLocation()
,06-30 10:36:15.543   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:15.543   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-30 10:36:15.543   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:36:15.548  6818  6818 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 10:36:15.573  3969  6789 D UdcContextInitService: registered all accounts: true
,06-30 10:36:15.597  2404  2688 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 10:36:15.606  5381  5407 I art     : Explicit concurrent mark sweep GC freed 2939(112KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 877us total 26.625ms
,06-30 10:36:15.744   944  1924 I art     : Explicit concurrent mark sweep GC freed 17424(786KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.959ms total 138.805ms
,06-30 10:36:15.763  2404  2652 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 10:36:15.852  2404  6858 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,06-30 10:36:15.853  2404  6816 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,06-30 10:36:15.869   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,06-30 10:36:15.869   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-30 10:36:15.869   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:15.870  6818  6818 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,06-30 10:36:15.874   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:15.874   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-30 10:36:15.874   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:15.875  6818  6818 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 10:36:15.877  2404  6858 E CommitToConfigurationOperation: Malformed snapshot token (size): 
06-30 10:36:15.879  2404  6816 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
06-30 10:36:15.904  2404  6858 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,06-30 10:36:15.904  2404  6816 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
06-30 10:36:15.904  2404  6816 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
06-30 10:36:15.919  6818  6818 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-30 10:36:15.919  6818  6818 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-30 10:36:15.925  2404  6816 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 10:36:15.962  6818  6818 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,06-30 10:36:15.976  2404  2652 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:15.976  2404  2652 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:15.980  2404  2652 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:15.980  2404  2652 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:15.980   278  1042 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 10:36:15.980   278  1042 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 10:36:15.980   278  6859 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:15.980   278  6859 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:15.981   278  6859 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:15.981   278  6859 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:15.981   278  6859 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:15.982  2404  2652 I System.out: propertyValue:false
06-30 10:36:16.009   944   963 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:16.042  6818  6818 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
06-30 10:36:16.043  6818  6818 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16eeb82e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-30 10:36:16.044  6818  6818 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-30 10:36:16.045  6818  6818 D AndroidMusic: GMSCore installation verified
06-30 10:36:16.052  6818  6818 I ConfigStore: Config Database version: 1
06-30 10:36:16.065  2404  2652 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:16.065  2404  2652 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:16.079  2404  6816 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:16.079  2404  6816 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:16.079  2404  6816 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:16.079  2404  6816 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:16.080   278  1042 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 10:36:16.080   278  1042 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 10:36:16.080   278  6860 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:16.080   278  6860 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:16.080   278  6860 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-30 10:36:16.080   278  6860 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-30 10:36:16.119   278  6860 D libc-netbsd: res_queryN name = xxxxx succeed
,06-30 10:36:16.120  2404  6816 I System.out: propertyValue:false
06-30 10:36:16.159  6818  6818 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,06-30 10:36:16.175  6818  6818 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-30 10:36:16.209  6818  6832 I art     : CheckpointMarkThreadRoots callback created = 0xaaf1c1d0
,06-30 10:36:16.250  6818  6832 I art     : CheckpointMarkThreadRoots callback created = 0xaaf1c1a0
,06-30 10:36:16.262   944  1636 I NotificationManager: android: cancelAsUser(2) by android
,06-30 10:36:16.276  6818  6818 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-30 10:36:16.287  2404  2652 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-30 10:36:16.311   944   963 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6868 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-30 10:36:16.366  6818  6818 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,06-30 10:36:16.370  6818  6818 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
06-30 10:36:16.383  3969  6867 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,06-30 10:36:16.404   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,06-30 10:36:16.404   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,06-30 10:36:16.404   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:16.405  6818  6866 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 10:36:16.429   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:16.429   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
06-30 10:36:16.430   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:16.430  6818  6866 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
,06-30 10:36:16.521  6677  6677 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
,06-30 10:36:16.537  6868  6868 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 10:36:16.553  6818  6843 I MusicLeanback: Stop autocaching.
06-30 10:36:16.554  6818  6843 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,06-30 10:36:16.588  6818  6886 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
06-30 10:36:16.588  6818  6886 I MusicLeanback: Stop autocaching.
,06-30 10:36:16.599   944  1879 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:16.702   944  1988 I ActivityManager: Process com.lge.qmemoplus (pid 6626) has died
,06-30 10:36:16.712  6766  6766 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 80
06-30 10:36:16.719  2019  2019 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
06-30 10:36:16.720  1775  1775 I PhoneApp: onTrimMemory: 10
06-30 10:36:16.720  1775  1775 I PhoneApp: trim memory
,06-30 10:36:16.757  2404  2652 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,06-30 10:36:16.772  2404  2656 W Herrevad: Invalid mccmnc 
06-30 10:36:16.780  2404  2656 W Herrevad: Invalid mccmnc 
06-30 10:36:16.786  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:16.932   283  1292 I WVCdm   : CdmEngine::CloseSession
,06-30 10:36:16.986   283  1611 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-30 10:36:16.986   283  1317 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-30 10:36:16.986   283  1317 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-30 10:36:16.986   283  1317 I WVCdm   : CdmEngine::GenerateKeyRequest
06-30 10:36:16.992   283  1317 D WVCdm   : PrepareKeyRequest: nonce=855279743
,06-30 10:36:17.023   944  1924 I ActivityManager: Process com.android.chrome (pid 6644) has died
06-30 10:36:17.027  6578  6653 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:36:17.027  6578  6653 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:36:17.027  6578  6653 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 10:36:17.027  6578  6653 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 10:36:17.027  6578  6653 I Adreno-EGL: Remote Branch: 
06-30 10:36:17.027  6578  6653 I Adreno-EGL: Local Patches: 
06-30 10:36:17.027  6578  6653 I Adreno-EGL: Reconstruct Branch: 
06-30 10:36:17.104  6868  6900 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,06-30 10:36:17.107  6868  6900 I Babel_SMS: MmsConfig.loadMmsSettings
06-30 10:36:17.111  6868  6900 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-30 10:36:17.111  6868  6900 I Babel_SMS: MmsConfig.loadFromDatabase
06-30 10:36:17.148  6868  6882 I art     : CheckpointMarkThreadRoots callback created = 0xaaf25c70
,06-30 10:36:17.177  6868  6900 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
06-30 10:36:17.177  6868  6900 I Babel_SMS: MmsConfig.loadFromResources
06-30 10:36:17.179  6868  6900 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
06-30 10:36:17.179  6868  6900 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-30 10:36:17.278   944  2189 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:17.288  6868  6868 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
06-30 10:36:17.288  6868  6868 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
06-30 10:36:17.288  6868  6868 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
06-30 10:36:17.288  6868  6868 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
06-30 10:36:17.288  6868  6868 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
06-30 10:36:17.288  6868  6868 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
06-30 10:36:17.288  6868  6868 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
06-30 10:36:17.288  6868  6868 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
06-30 10:36:17.289  6868  6868 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
06-30 10:36:17.289  6868  6868 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
06-30 10:36:17.289  6868  6868 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
06-30 10:36:17.289  6868  6868 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
06-30 10:36:17.289  6868  6868 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
06-30 10:36:17.289  6868  6868 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
06-30 10:36:17.289  6868  6868 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
06-30 10:36:17.289  6868  6868 D SensorManager: found sensor: Motion Accel, handle=46
,06-30 10:36:17.295  6868  6882 I art     : CheckpointMarkThreadRoots callback created = 0xaae47db0
06-30 10:36:17.319  6578  6653 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:36:17.319  6578  6653 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:36:17.319  6578  6653 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 10:36:17.319  6578  6653 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 10:36:17.319  6578  6653 I Adreno-EGL: Remote Branch: 
06-30 10:36:17.319  6578  6653 I Adreno-EGL: Local Patches: 
06-30 10:36:17.319  6578  6653 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:36:17.374  6868  6868 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:17.377  6868  6868 I Babel_Crash: startup - clean
06-30 10:36:17.377  6578  6653 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 10:36:17.377  6578  6653 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:36:17.377  6578  6653 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 10:36:17.377  6578  6653 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 10:36:17.377  6578  6653 I Adreno-EGL: Remote Branch: 
06-30 10:36:17.377  6578  6653 I Adreno-EGL: Local Patches: 
06-30 10:36:17.377  6578  6653 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:36:17.408  6868  6903 I Babel   : deleted: false for 0
,06-30 10:36:17.450  2404  2656 V NQFileLogger: [174] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
06-30 10:36:17.504  3969  6477 I CheckinUtil: Classify the device as Phone.
,06-30 10:36:17.562   944  2720 I ActivityManager: Process com.google.android.apps.plus (pid 6184) has died
,06-30 10:36:17.572  1775  1775 I PhoneApp: onTrimMemory: 10
06-30 10:36:17.572  1775  1775 I PhoneApp: trim memory
06-30 10:36:17.574  2404  2404 I art     : Explicit concurrent mark sweep GC freed 40749(2MB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 15MB/26MB, paused 1.999ms total 134.051ms
,06-30 10:36:17.575  2019  2019 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
06-30 10:36:17.596   944  2169 I NotificationManager: android: cancelAsUser(2) by android
,06-30 10:36:17.602  6766  6766 I Finsky  : [1] com.google.android.finsky.utils.dm.onTrimMemory(25): Memory trim requested to level 80
06-30 10:36:17.626  2404  2656 V ProcessReports: [174] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,06-30 10:36:17.632  2404  6816 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
06-30 10:36:17.635  6868  6868 W AudioCapabilities: Unsupported mime audio/x-lg-flac
06-30 10:36:17.651  6868  6868 W AudioCapabilities: Unsupported mime audio/adpcm
,06-30 10:36:17.656  6818  6907 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
06-30 10:36:17.656  6818  6907 I MusicLeanback: Stop autocaching.
06-30 10:36:17.659  6868  6868 W AudioCapabilities: Unsupported mime audio/g726
06-30 10:36:17.660  6868  6868 W AudioCapabilities: Unsupported mime audio/x-ms-wma
06-30 10:36:17.661  6868  6868 W AudioCapabilities: Unsupported mime audio/wma-voice
06-30 10:36:17.663  6868  6868 W VideoCapabilities: Unsupported mime video/mjpg
,06-30 10:36:17.677  6868  6868 W VideoCapabilities: Unsupported mime video/theora
,06-30 10:36:17.694  5381  5399 I art     : Explicit concurrent mark sweep GC freed 2847(113KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 381us total 52.268ms
,06-30 10:36:17.724  2404  2404 D WearableService: callingUid 10006, callindPid: 2404
,06-30 10:36:17.766  6868  6868 W AudioCapabilities: Unsupported mime audio/evrc
06-30 10:36:17.767  6868  6868 W AudioCapabilities: Unsupported mime audio/qcelp
,06-30 10:36:17.769  6868  6868 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 10:36:17.796  6868  6882 W art     : Suspending all threads took: 5.120ms
,06-30 10:36:17.801  2019  2019 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
06-30 10:36:17.803  6818  6818 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
06-30 10:36:17.804  6818  6912 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
06-30 10:36:17.817  6868  6868 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,06-30 10:36:17.820  6868  6868 W AudioCapabilities: Unsupported mime audio/qcelp
,06-30 10:36:17.833  1945  1945 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
06-30 10:36:17.834  6868  6868 W AudioCapabilities: Unsupported mime audio/evrc
06-30 10:36:17.835  1945  2121 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,06-30 10:36:17.835  1945  2121 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
,06-30 10:36:17.840  2019  2019 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
06-30 10:36:17.858  1945  2121 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,06-30 10:36:17.860  1945  2121 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
06-30 10:36:17.860  1945  2121 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
06-30 10:36:17.866  6868  6868 W VideoCapabilities: Unsupported mime video/mp4v-esdp
06-30 10:36:17.909  6818  6818 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-30 10:36:17.915  6818  6920 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
06-30 10:36:17.920  6868  6868 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-30 10:36:17.951   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:36:17.951   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
06-30 10:36:17.951   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:36:17.951  6868  6868 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 10:36:17.953  6818  6918 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
06-30 10:36:17.955  6868  6868 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 10:36:17.960  6868  6868 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-30 10:36:17.971  6868  6868 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-30 10:36:17.974  3969  6477 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:17.974  3969  6477 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:36:17.974  3969  6477 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:17.974  3969  6477 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:17.983  6868  6868 I vclib   : onServiceConnected
06-30 10:36:17.983  6868  6868 W Babel   : Attempted to change video mute state without an active call.
,06-30 10:36:17.990   278  1042 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 10:36:17.990   278  1042 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 10:36:17.990   278  6923 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:17.990   278  6923 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:36:17.990   278  6923 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:36:17.991   278  6923 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:17.991   278  6923 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:17.993  3969  6477 I System.out: propertyValue:false
06-30 10:36:18.000   944  1935 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:18.005  6868  6868 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,06-30 10:36:18.033  6677  6754 I art     : Explicit concurrent mark sweep GC freed 2286(126KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 11MB/14MB, paused 620us total 58.192ms
,06-30 10:36:18.041  6677  6754 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 24510, normalSync: true
06-30 10:36:18.042  6677  6754 I Gmail   : lowestBackward conversation id 0
06-30 10:36:18.072  3969  6477 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:18.072  3969  6477 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:36:18.081  6677  6677 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
06-30 10:36:18.082  6677  6677 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
06-30 10:36:18.162  3969  6477 I CheckinTask: Sending checkin request (11178 bytes)
,06-30 10:36:18.172  6677  6754 I Gmail   : notifyAccountChanged
06-30 10:36:18.174  6677  6741 I Gmail   : getAccountsCursor
,06-30 10:36:18.180  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:36:18.186   944  2025 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-30 10:36:18.187  6677  6754 I Gmail   : notifyAccountChanged
06-30 10:36:18.189  6677  6754 W Gmail   : Sync complete for account: account:61035162
,06-30 10:36:18.191  6677  6752 I Gmail   : getAccountsCursor
06-30 10:36:18.196  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:18.239   944  1018 I NotificationManager: android: cancelAsUser(1479798955) by android
,06-30 10:36:18.314  6677  6748 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,06-30 10:36:18.351   944   944 I art     : Explicit concurrent mark sweep GC freed 29558(1332KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.203ms total 152.832ms
,06-30 10:36:18.372   944  1375 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:18.525  3969  6477 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,06-30 10:36:18.526  3969  6477 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
06-30 10:36:18.588   944  1924 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:18.666  3969  6477 I CheckinUtil: Classify the device as Phone.
,06-30 10:36:18.684  3969  6477 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,06-30 10:36:18.689  3969  6477 I CheckinChimeraService: Checking schedule, now: 1467275778689 next: 1467803027684
06-30 10:36:18.689  3969  6477 I CheckinChimeraService: active receiver: disabled
,06-30 10:36:18.734  3969  6934 I CheckinChimeraService: Checking schedule, now: 1467275778734 next: 1467803027684
06-30 10:36:18.734  3969  6934 I CheckinChimeraService: active receiver: disabled
06-30 10:36:18.744  3969  3969 D CheckinChimeraService: Recording last checkin time for package unspecified as 1467275778744
,06-30 10:36:18.786   944  1355 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:18.817   944  2720 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6935 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,06-30 10:36:18.957  2404  2656 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,06-30 10:36:19.034  3969  4094 V UdcCtxListenerSrv: handle intent
,06-30 10:36:19.043  6935  6935 D PhoneMonitor: Register our PhoneStateListener
06-30 10:36:19.065  6935  6935 V SetupWizard: Connected to Gservices successfully
,06-30 10:36:19.081  6935  6935 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,06-30 10:36:19.083  6935  6935 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
06-30 10:36:19.085  6935  6935 D TelephonyAutoProfiling: [parse] Load xml
06-30 10:36:19.093  6935  6935 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
06-30 10:36:19.093  6935  6935 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,06-30 10:36:19.100  2404  6961 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
06-30 10:36:19.103  6935  6935 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
06-30 10:36:19.138   944  1355 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:19.153  3969  4094 I Icing   : Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,06-30 10:36:19.178  3969  4094 I Icing   : Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
,06-30 10:36:19.271   283  1292 I WVCdm   : CdmEngine::CloseSession
,06-30 10:36:19.275   283  1292 I WVCdm   : L3 Terminate.
,06-30 10:36:19.324   944  1375 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:19.514   944  1895 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:19.724   944  1375 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:19.829   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:36:19.829   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,06-30 10:36:19.829   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 172936315616; DSPS: 5765413; Offset : -3013790851
06-30 10:36:19.871   944   963 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:20.020   944  1935 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:20.154   944  1344 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:20.314   944  1935 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:20.458   294   360 I ThermalEngine: Sensor:pa_therm0:34000 mC
,06-30 10:36:20.604   944  2025 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:20.728   944  1988 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:20.907   944  1344 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:21.074   944  1355 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:21.163  6818  6973 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
06-30 10:36:21.163  6818  6973 I MusicLeanback: Stop autocaching.
,06-30 10:36:21.173  6818  6818 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
06-30 10:36:21.180  6818  6976 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-30 10:36:21.282   944  2169 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:21.370  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-30 10:36:21.373  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:36:21.376  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:36:21.385  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,06-30 10:36:21.388  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:36:21.390   486   486 D charger_monitor: init target 500000
06-30 10:36:21.395   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:36:21.447  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 305
06-30 10:36:21.447  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,06-30 10:36:21.448  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:36:21.451  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:36:21.451  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:36:21.451  1870  2037 D LEDHandler: Battery Temp: 305, mChargingStatus=5, mChargingStop=false
06-30 10:36:21.462  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,06-30 10:36:21.464  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 305
06-30 10:36:21.471  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:36:21.478  6725  6725 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,06-30 10:36:21.485   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:36:21.485   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:21.486   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:21.491  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:36:21.695   944  2720 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:21.879   944  1344 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:22.098   944  1355 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:22.222   944  1344 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:22.413   944  1935 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 10:36:22.895  2404  4156 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 10:36:25.462   294   360 I ThermalEngine: Sensor:pa_therm0:34000 mC
,06-30 10:36:27.798   944  1282 V AlarmManager: RTC_WAKEUP set : Alarm{3fc7abd9 type 0 when 1467275787789 com.google.android.googlequicksearchbox} when 1467275787789
,06-30 10:36:27.978  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:27.983  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:36:28.141   944  1988 I NotificationManager: android: cancelAsUser(2) by android
,06-30 10:36:28.161  2404  2443 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-30 10:36:28.309  2019  2889 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:36:28.366  2019  7008 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:36:28.366  2019  7008 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
06-30 10:36:28.367   278  1042 E BandwidthController: [LG DATA] No such appUid: 10042
06-30 10:36:28.367   278  1042 D DnsProxyListener: App 10042 tries DNS query. Accept family:2 protocol:0
06-30 10:36:28.367   278  7012 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:28.368   278  7012 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
06-30 10:36:28.368   278  7012 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:28.368   278  7012 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:28.654  2019  7008 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:36:28.654  2019  7008 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,06-30 10:36:28.656   278  1042 E BandwidthController: [LG DATA] No such appUid: 10042
06-30 10:36:28.656   278  1042 D DnsProxyListener: App 10042 tries DNS query. Accept family:2 protocol:0
06-30 10:36:28.656   278  7015 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:36:28.656   278  7015 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
06-30 10:36:28.657   278  7015 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:36:28.657   278  7015 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:36:28.789  1368  1368 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,06-30 10:36:28.800  1907  1907 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
06-30 10:36:28.802  1368  1368 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,06-30 10:36:28.821  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
06-30 10:36:28.821  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,06-30 10:36:28.823  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,06-30 10:36:28.823  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
06-30 10:36:28.823  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
06-30 10:36:28.823  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
06-30 10:36:28.823  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
06-30 10:36:28.823  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
06-30 10:36:28.823  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
06-30 10:36:28.823  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
06-30 10:36:28.823  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
06-30 10:36:28.824  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
06-30 10:36:28.824  1368  1368 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
06-30 10:36:28.829  2019  2889 I HotwordDataManager: setSpeakerModel(thalitester@gmail.com,null)
06-30 10:36:28.863   944  1284 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-30 10:36:28.883  1945  1945 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,06-30 10:36:28.908  1945  1945 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,06-30 10:36:28.912  1945  1945 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
06-30 10:36:28.955   944  2025 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7020 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,06-30 10:36:28.983   944   944 D administrator: Handling package changes for user 0,
,06-30 10:36:28.998  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,06-30 10:36:29.017  6868  7016 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,06-30 10:36:29.033  6868  6868 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-30 10:36:29.033  6868  6868 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 10:36:29.095  7020  7020 I AppUp4:AppBoxCP: onCreate
06-30 10:36:29.096  7020  7020 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,06-30 10:36:29.108  7020  7020 I AppUp4:DB:  setFingerPrint start
06-30 10:36:29.109  7020  7020 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
06-30 10:36:29.110  6868  6868 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,06-30 10:36:29.118  7020  7020 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
06-30 10:36:29.118  7020  7020 I AppUp4:DB:  SDK version = 21
06-30 10:36:29.118  7020  7020 I AppUp4:DB:  beforefinger == newfinger no write in DB
06-30 10:36:29.152   944  1935 I ActivityManager: Process com.android.vending (pid 6766) has died
,06-30 10:36:29.154  7020  7020 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
06-30 10:36:29.170  7020  7020 I AppUp4:CustModeStarterReceiver: onReceive
06-30 10:36:29.171  7020  7020 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,06-30 10:36:29.176  7020  7020 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1b2072d4
06-30 10:36:29.176  7020  7020 D AppUp4:CustFacade: isCustomizationCompleted : false
06-30 10:36:29.187  7020  7020 D AppUp4:CustFacade: isSimDevice : true
,06-30 10:36:29.189  7020  7020 D AppUp4:CustModeStarterReceiver: begin check event
06-30 10:36:29.189  7020  7020 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
06-30 10:36:29.206  6868  6868 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,06-30 10:36:29.207  6868  6868 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-30 10:36:29.261   944  1895 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7053 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,06-30 10:36:29.292   944  2025 I ActivityManager: Process com.google.android.gm (pid 6677) has died
,06-30 10:36:29.356  7053  7053 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:36:29.356  7053  7053 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 10:36:29.357  7053  7053 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,06-30 10:36:29.424   944  1018 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:36:29.438   944   944 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,06-30 10:36:29.440   944   944 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,06-30 10:36:29.440   944   944 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
06-30 10:36:29.451   944   944 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,06-30 10:36:29.475   944   944 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
06-30 10:36:29.476   944   944 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@21379858
06-30 10:36:29.536  7053  7053 I AppConfig: Total System Memory = 906309632
06-30 10:36:29.539  7053  7053 I GalleryUtils: Application Heap = 96 MB
,06-30 10:36:29.546  7053  7053 I AppConfig: App Tier : NOT_DEF
06-30 10:36:29.552  7053  7053 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,06-30 10:36:29.563   944  1895 I ActivityManager: Process com.lge.bnr (pid 6725) has died
06-30 10:36:29.601   944  1018 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,06-30 10:36:29.633   944  1879 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7075 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,06-30 10:36:29.637  1945  1945 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,06-30 10:36:29.677  2404  2404 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
06-30 10:36:29.702  7075  7075 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 10:36:29.702  7075  7075 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:36:29.702   944  1018 D LocationProviderProxy: applying state to connected service
06-30 10:36:29.704  7075  7075 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
06-30 10:36:29.708  7075  7075 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
06-30 10:36:29.709  7075  7075 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 10:36:29.860  7075  7075 I SystemConfig: BUILD Country: EU
06-30 10:36:29.860  7075  7075 I SystemConfig: BUILD Operator: OPEN
,06-30 10:36:29.952   944  1344 I ActivityManager: Process com.google.android.setupwizard (pid 6935) has died
,06-30 10:36:30.018   944  2025 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7098 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:30.038  7075  7093 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
06-30 10:36:30.038  7075  7093 I SystemConfig: existFile = false
06-30 10:36:30.038  7075  7093 I SystemConfig: canReadFile = false
06-30 10:36:30.039  7075  7093 I SystemConfig: systemFeature RCS result false
06-30 10:36:30.039  7075  7093 D SystemConfig: refreshRcsSupport() :false
,06-30 10:36:30.098  7098  7098 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,06-30 10:36:30.122  7098  7098 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,06-30 10:36:30.122  7098  7098 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
06-30 10:36:30.122  7098  7098 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
06-30 10:36:30.122  7098  7098 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
06-30 10:36:30.122  7098  7098 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,06-30 10:36:30.168   944  1924 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7115 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:30.370  7115  7115 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
,06-30 10:36:30.467   294   360 I ThermalEngine: Sensor:pa_therm0:34000 mC
,06-30 10:36:30.565  7115  7115 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(171): No need to run daily hygiene.
,06-30 10:36:30.584  7115  7115 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-30 10:36:30.584  7115  7115 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,06-30 10:36:30.589  7115  7115 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
,06-30 10:36:30.605  7115  7115 I Finsky  : [1] com.google.android.finsky.utils.bk.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,06-30 10:36:30.646  2427  2749 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
,06-30 10:36:30.649  2427  2749 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2fc4e391 on behalf of 7115
06-30 10:36:30.651  7115  7115 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1226): Installer kick - no action, not running yet
06-30 10:36:30.655  7115  7115 I Finsky  : [1] com.google.android.finsky.j.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
06-30 10:36:30.655  7115  7115 I Finsky  : [1] com.google.android.finsky.j.j.run(214): Finished loading 1 libraries.
06-30 10:36:30.696  3969  7157 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,06-30 10:36:30.738   944   963 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7162 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,06-30 10:36:30.764   307   307 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 24.285ms
,06-30 10:36:30.790   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 23.853ms
,06-30 10:36:30.795  7115  7115 I Finsky  : [1] com.google.android.finsky.c.l.a(270): result=false type=4
06-30 10:36:30.813   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.763ms
,06-30 10:36:30.814   944  1879 I ActivityManager: Process com.google.android.gms.unstable (pid 6578) has died
06-30 10:36:30.821  3969  7157 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
06-30 10:36:30.849  3969  4094 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,06-30 10:36:30.852  7162  7162 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:36:30.870  7115  7115 I Finsky  : [1] com.google.android.finsky.services.bc.a(1050): Restore complete with 0 success and 0 failed.
,06-30 10:36:30.936  3969  7191 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-30 10:36:31.112   944  1636 I art     : Explicit concurrent mark sweep GC freed 33808(1580KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 1.875ms total 156.521ms
,06-30 10:36:31.364  2019  7201 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,06-30 10:36:31.424  2019  7201 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 60 ms] updated apps [took 60 ms] 
,06-30 10:36:31.493   944  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{b29a8e7 type 2 when 184597 com.google.android.gms} when 184597
,06-30 10:36:32.138  3969  4094 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,06-30 10:36:32.226  3969  4094 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,06-30 10:36:34.148  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:36:34.148  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:36:34.149  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:36:34.149  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 10:36:34.149   486   486 D charger_monitor: init target 500000
,06-30 10:36:34.150  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:36:34.154   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:36:34.186  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-30 10:36:34.189  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:36:34.189  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:36:34.190  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 305
06-30 10:36:34.190  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:36:34.190  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 305
06-30 10:36:34.191  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:36:34.191  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:36:34.191   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:34.191  1870  2037 D LEDHandler: Battery Temp: 305, mChargingStatus=5, mChargingStop=false
06-30 10:36:34.191   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:36:34.191   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:36:34.193  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:36:34.827   944  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3bdd7c94 type 2 when 187930 android} when 187930
,06-30 10:36:35.471   294   360 I ThermalEngine: Sensor:pa_therm0:34000 mC
,06-30 10:36:37.838   944   963 I ActivityManager: Killing 6702:com.lge.clock/u0a10 (adj 15): empty #11
,06-30 10:36:37.869   944  1935 W libprocessgroup: failed to open /acct/uid_10010/pid_6702/cgroup.procs: No such file or directory
,06-30 10:36:39.829   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:36:39.829   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:36:39.829   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 192937068681; DSPS: 6420798; Offset : -3013799944
,06-30 10:36:40.476   294   360 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 10:36:45.481   294   360 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 10:36:47.987  3969  7210 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-30 10:36:48.027  6818  6818 I NotificationManager: com.google.android.music: cancel(10436) by com.google.android.music
,06-30 10:36:48.153  6818  6818 I NotificationManager: com.google.android.music: cancel(10436) by com.google.android.music
,06-30 10:36:48.203  6818  6818 I NotificationManager: com.google.android.music: cancel(10436) by com.google.android.music
,06-30 10:36:48.230  6818  6818 I NotificationManager: com.google.android.music: cancel(10436) by com.google.android.music
,06-30 10:36:50.485   294   360 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 10:36:55.490   294   360 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 10:36:59.830   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:36:59.830   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:36:59.830   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 212937753517; DSPS: 7076180; Offset : -3013786495
,06-30 10:37:00.000  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:37:00.000  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 10:37:00.018  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:37:00.025  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:37:00.027  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:37:00.031  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:37:00.032  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:37:00.494   294   360 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 10:37:04.847   944  1282 D PowerManagerServiceEx: acquireWakeLockInternal: lock=731858183, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=944
,06-30 10:37:04.852   944  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{241899d7 type 2 when 217951 android} when 217951
06-30 10:37:04.875   944   944 D PowerManagerServiceEx: releaseWakeLockInternal: lock=731858183 [*alarm*], flags=0x0
,06-30 10:37:05.256  3969  7229 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,06-30 10:37:05.272   944  1018 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 189166, reason: UserStart, SyncResult: databaseError: true stats []
,06-30 10:37:05.278   944  1018 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 280405, reason: UserStart
06-30 10:37:05.278   944  1018 I NotificationManager: android: cancelAsUser(716319171) by android
06-30 10:37:05.499   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:37:10.503   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:37:11.608   944  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3002b730 type 2 when 205854 android} when 205854
,06-30 10:37:15.508   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:37:19.831   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:37:19.831   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:37:19.831   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 232938507937; DSPS: 7731565; Offset : -3013795250
,06-30 10:37:20.513   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:37:25.517   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:37:30.522   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:37:34.309   486   486 D charger_monitor: init target 500000
,06-30 10:37:34.314   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:37:34.315  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:37:34.316  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:37:34.316  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:37:34.316  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:37:34.316  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:37:34.358  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:37:34.358  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,06-30 10:37:34.362  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:37:34.362  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:37:34.362  1870  2037 D LEDHandler: Battery Temp: 302, mChargingStatus=5, mChargingStop=false
06-30 10:37:34.364  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:37:34.364  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
06-30 10:37:34.364  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:37:34.365  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 302
06-30 10:37:34.369  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:37:34.372   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:37:34.372   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:37:34.375   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:37:35.245   944  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2418cfa9 type 2 when 248344 android} when 248344
,06-30 10:37:35.526   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:37:35.533   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
06-30 10:37:35.533   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
06-30 10:37:35.534   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
06-30 10:37:35.534   272   820 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
06-30 10:37:35.655   272   820 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
06-30 10:37:35.655   272   820 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,06-30 10:37:35.658   272   820 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
06-30 10:37:35.658   272   820 I rmt_storage: 
06-30 10:37:35.661   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
06-30 10:37:39.831   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:37:39.832   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:37:39.832   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 252939262512; DSPS: 8386950; Offset : -3013803769
,06-30 10:37:40.531   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:37:45.535   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:37:50.546   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:37:55.551   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:37:59.832   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:37:59.832   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:37:59.832   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 272939948390; DSPS: 9042332; Offset : -3013788940
,06-30 10:38:00.064  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:38:00.064  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:38:00.064  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:38:00.068  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:38:00.068  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:38:00.069  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:38:00.070  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:38:00.555   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:38:05.560   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:38:10.565   294   360 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 10:38:15.569   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:38:19.833   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:38:19.833   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:38:19.833   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 292940909581; DSPS: 9697724; Offset : -3013804207
,06-30 10:38:20.574   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:38:25.583   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:38:30.587   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:38:34.467   486   486 D charger_monitor: init target 500000
,06-30 10:38:34.472   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:38:34.481  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,06-30 10:38:34.484  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:38:34.484  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:38:34.484  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:38:34.485  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:38:34.517  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
06-30 10:38:34.517  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:38:34.517  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
,06-30 10:38:34.521  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:38:34.522  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:38:34.522  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:38:34.522  1870  2037 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
06-30 10:38:34.523  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:38:34.525  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:38:34.526  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:38:34.529   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:38:34.529   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:38:34.529   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:38:35.592   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:38:39.834   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:38:39.834   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:38:39.834   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 312941681552; DSPS: 10353109; Offset : -3013795410
,06-30 10:38:40.596   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:38:45.601   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:38:50.605   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:38:55.610   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:38:59.835   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:38:59.835   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:38:59.835   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 332942439774; DSPS: 11008494; Offset : -3013799815
,06-30 10:39:00.038  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:39:00.038  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:39:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:39:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:39:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:39:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:39:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:39:00.615   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:05.619   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:08.399   944  3126 I LocationManagerService: remove 2a66c12e
,06-30 10:39:08.406   944  3126 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
06-30 10:39:08.407   944  3126 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 10:39:08.407   944  3126 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-30 10:39:08.407   944  3126 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
06-30 10:39:08.408   944  3126 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,06-30 10:39:10.624   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:15.628   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:19.835   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:39:19.835   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:39:19.835   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 352943104662; DSPS: 11663876; Offset : -3013806444
,06-30 10:39:20.633   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:25.637   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:30.642   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:34.627   486   486 D charger_monitor: init target 500000
,06-30 10:39:34.636  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:39:34.636  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:39:34.637  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:39:34.637  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:39:34.637  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:39:34.638   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:39:34.678  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
06-30 10:39:34.678  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:39:34.678  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
,06-30 10:39:34.683  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:39:34.683  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:39:34.684  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:39:34.684  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:39:34.685  1870  2037 D LEDHandler: Battery Temp: 299, mChargingStatus=5, mChargingStop=false
06-30 10:39:34.686  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:39:34.688  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:39:34.690   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:39:34.690   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:39:34.692   944  1309 D WifiController: battery changed pluggedType: 2
,06-30 10:39:35.649   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:39.836   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:39:39.836   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:39:39.836   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 372943915070; DSPS: 12319262; Offset : -3013789675
,06-30 10:39:40.653   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:45.658   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:50.662   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:55.667   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:39:59.837   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:39:59.837   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:39:59.837   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 392944683085; DSPS: 12974647; Offset : -3013784886
,06-30 10:40:00.040  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:40:00.040  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:40:00.040  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:40:00.044  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:40:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:40:00.045  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:40:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:40:00.672   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:05.676   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:10.681   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:15.685   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:19.838   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:40:19.838   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:40:19.838   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 412945370993; DSPS: 13630030; Offset : -3013798335
,06-30 10:40:20.690   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:25.694   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:30.699   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:34.789   486   486 D charger_monitor: init target 500000
,06-30 10:40:34.794   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:40:34.795  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:40:34.795  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:40:34.796  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:40:34.796  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:40:34.796  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:40:34.834  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
06-30 10:40:34.834  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:40:34.834  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
,06-30 10:40:34.837  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:40:34.838  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:40:34.839  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:40:34.839  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:40:34.839  1870  2037 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
06-30 10:40:34.843  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:40:34.844  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:40:34.847   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:40:34.847   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:40:34.850   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:40:35.704   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:39.838   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:40:39.838   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:40:39.839   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 432946135413; DSPS: 14285415; Offset : -3013796959
,06-30 10:40:40.708   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:45.713   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:50.717   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:55.722   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:40:59.839   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:40:59.839   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:40:59.839   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 452946911499; DSPS: 14940801; Offset : -3013814408
,06-30 10:41:00.000   944  1282 D PowerManagerServiceEx: acquireWakeLockInternal: lock=731858183, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=944
,06-30 10:41:00.024   944   944 D PowerManagerServiceEx: releaseWakeLockInternal: lock=731858183 [*alarm*], flags=0x0
,06-30 10:41:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:41:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:41:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:41:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:41:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:41:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:41:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:41:00.726   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:41:05.731   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:41:10.736   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:41:15.740   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:41:19.840   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:41:19.840   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:41:19.840   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 472947527168; DSPS: 15596181; Offset : -3013809065
,06-30 10:41:20.745   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:41:25.749   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:41:29.056  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:41:29.056  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:41:29.056  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:41:29.056  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 10:41:29.062  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:41:29.069   486   486 D charger_monitor: init target 500000
,06-30 10:41:29.074   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:41:29.109  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
06-30 10:41:29.110  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:41:29.110  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,06-30 10:41:29.114  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:41:29.115  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:41:29.115  1870  2037 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
06-30 10:41:29.115  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:41:29.115  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:41:29.117  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:41:29.119  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:41:29.122   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:41:29.123   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:41:29.126   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:41:29.164  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
06-30 10:41:29.164  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:41:29.164  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,06-30 10:41:29.167  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:41:29.167  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:41:29.169  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:41:29.169  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:41:29.169  1870  2037 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
06-30 10:41:29.173  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:41:29.176   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:41:29.176   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:41:29.178   944  1309 D WifiController: battery changed pluggedType: 2
,06-30 10:41:29.183  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:41:30.580  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:41:30.594  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:41:30.598  2404  2404 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:41:30.642   944  1988 I NotificationManager: android: cancelAsUser(2) by android
,06-30 10:41:30.660  7115  7149 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:41:30.660  7115  7149 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:41:30.660  7115  7149 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:41:30.660  7115  7149 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:41:30.670   278  1042 E BandwidthController: [LG DATA] No such appUid: 10036
,06-30 10:41:30.670   278  1042 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
06-30 10:41:30.682   278  7286 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:41:30.682   278  7286 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:41:30.682   278  7286 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:41:30.682   278  7286 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-30 10:41:30.728   278  7286 D libc-netbsd: res_queryN name = xxxxx succeed
,06-30 10:41:30.728  7115  7149 I System.out: propertyValue:false
06-30 10:41:30.754   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:41:34.964   486   486 D charger_monitor: init target 500000
,06-30 10:41:34.969   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:41:34.971  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:41:34.971  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:41:34.972  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:41:34.972  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:41:34.978  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,06-30 10:41:35.016  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
06-30 10:41:35.016  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:41:35.016  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,06-30 10:41:35.020  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:41:35.021  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:41:35.021  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:41:35.021  1870  2037 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
06-30 10:41:35.021  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:41:35.025  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:41:35.025  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:41:35.028   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:41:35.028   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:41:35.028   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:41:35.759   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:41:39.841   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:41:39.841   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:41:39.841   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 492948282369; DSPS: 16251565; Offset : -3013786312
,06-30 10:41:40.763   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:41:45.768   294   360 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 10:41:50.773   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:41:55.777   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:41:59.841   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:41:59.841   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:41:59.841   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 512948970955; DSPS: 16906948; Offset : -3013799162
,06-30 10:42:00.040  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:42:00.040  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:42:00.040  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:42:00.044  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:42:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:42:00.045  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:42:00.046  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:42:00.782   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:05.786   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:10.791   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:15.796   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:19.842   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:42:19.842   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:42:19.842   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 532949764072; DSPS: 17562334; Offset : -3013799944
,06-30 10:42:20.800   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:25.805   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:30.809   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:35.109   486   486 D charger_monitor: init target 500000
,06-30 10:42:35.114   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:42:35.116  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:42:35.116  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:42:35.116  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:42:35.116  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:42:35.116  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:42:35.157  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
06-30 10:42:35.157  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:42:35.158  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,06-30 10:42:35.162  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:42:35.163  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:42:35.163  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:42:35.163  1870  2037 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
06-30 10:42:35.163  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:42:35.165  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:42:35.167  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:42:35.169   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:42:35.169   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:42:35.171   944  1309 D WifiController: battery changed pluggedType: 2
,06-30 10:42:35.814   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:39.843   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:42:39.843   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:42:39.843   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 552950750784; DSPS: 18217726; Offset : -3013789899
,06-30 10:42:40.818   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:45.823   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:50.827   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:55.832   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:42:59.844   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:42:59.844   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:42:59.844   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 572951520203; DSPS: 18873112; Offset : -3013813520
,06-30 10:43:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:43:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:43:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:43:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:43:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:43:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:43:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:43:00.837   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:05.841   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:10.846   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:15.850   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:19.845   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:43:19.845   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:43:19.845   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 592952209831; DSPS: 19528494; Offset : -3013797310
,06-30 10:43:20.855   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:25.860   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:30.864   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:35.269   486   486 D charger_monitor: init target 500000
,06-30 10:43:35.274   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:43:35.275  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:43:35.275  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:43:35.276  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:43:35.276  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:43:35.276  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:43:35.869   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:39.845   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:43:39.845   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:43:39.845   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 612952968730; DSPS: 20183879; Offset : -3013799450
,06-30 10:43:40.873   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:45.878   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:50.882   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:55.887   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:43:59.846   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:43:59.846   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:43:59.846   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 632953732889; DSPS: 20839264; Offset : -3013798621
,06-30 10:44:00.040  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:44:00.040  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:44:00.040  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:44:00.044  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:44:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:44:00.045  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:44:00.046  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:44:00.891   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:05.896   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:10.901   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:15.905   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:19.847   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:44:19.847   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:44:19.847   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 652954420589; DSPS: 21494647; Offset : -3013812382
,06-30 10:44:20.910   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:25.914   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:30.919   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:35.429   486   486 D charger_monitor: init target 500000
,06-30 10:44:35.434   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:44:35.435  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:44:35.435  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:44:35.436  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:44:35.436  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:44:35.436  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:44:35.474  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
06-30 10:44:35.474  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,06-30 10:44:35.477  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:44:35.477  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:44:35.478  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:44:35.478  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:44:35.478  1870  2037 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
06-30 10:44:35.479  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
06-30 10:44:35.484  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:44:35.484  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:44:35.487   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:44:35.487   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:44:35.490   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:44:35.923   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:39.847   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:44:39.847   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:44:39.848   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 672955183238; DSPS: 22150032; Offset : -3013812829
,06-30 10:44:40.928   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:45.933   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:47.003   944  1282 D PowerManagerServiceEx: acquireWakeLockInternal: lock=731858183, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=944
,06-30 10:44:47.007   944  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1b1ad4f4 type 2 when 680106 android} when 680106
06-30 10:44:47.022   944   944 D PowerManagerServiceEx: releaseWakeLockInternal: lock=731858183 [*alarm*], flags=0x0
,06-30 10:44:47.493   944  1018 I NotificationManager: android: cancelAsUser(-1548111331) by android
,06-30 10:44:47.588   944  1018 I NotificationManager: android: cancelAsUser(2145784878) by android
06-30 10:44:50.937   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:55.942   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:44:59.848   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:44:59.848   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:44:59.848   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 692955942761; DSPS: 22805416; Offset : -3013785494
,06-30 10:45:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:45:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:45:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:45:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:45:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:45:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:45:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:45:00.946   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:05.951   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:10.955   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:15.960   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:17.313   944  1282 D PowerManagerServiceEx: acquireWakeLockInternal: lock=731858183, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=944
,06-30 10:45:17.317   944  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{131805ea type 2 when 710417 android} when 710417
06-30 10:45:17.387   944   963 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7337 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,06-30 10:45:17.561  7337  7337 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,06-30 10:45:17.571  7337  7337 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1b2072d4
06-30 10:45:17.572   944   944 D PowerManagerServiceEx: releaseWakeLockInternal: lock=731858183 [*alarm*], flags=0x0
06-30 10:45:17.573   944  1895 I ActivityManager: Killing 6818:com.google.android.music:main/u0a81 (adj 15): empty #11
,06-30 10:45:17.634   944  1375 W libprocessgroup: failed to open /acct/uid_10081/pid_6818/cgroup.procs: No such file or directory
,06-30 10:45:19.849   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:45:19.849   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:45:19.849   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 712956634733; DSPS: 23460799; Offset : -3013795764
,06-30 10:45:20.965   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:25.969   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:30.974   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:35.587   486   486 D charger_monitor: init target 500000
,06-30 10:45:35.592   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:45:35.601  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:45:35.601  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:45:35.601  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:45:35.601  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 10:45:35.604  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:45:35.640  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
06-30 10:45:35.640  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,06-30 10:45:35.643  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:45:35.643  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:45:35.644  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:45:35.644  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:45:35.644  1870  2037 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
06-30 10:45:35.646  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:45:35.647  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
06-30 10:45:35.649  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:45:35.651   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:45:35.651   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:45:35.653   944  1309 D WifiController: battery changed pluggedType: 2
,06-30 10:45:35.978   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:39.850   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:45:39.850   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:45:39.850   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 732957400454; DSPS: 24116184; Offset : -3013793295
,06-30 10:45:40.983   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:45.987   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:50.992   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:55.996   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:45:59.850   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:45:59.850   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:45:59.851   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 752958166801; DSPS: 24771569; Offset : -3013791320
,06-30 10:46:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:46:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:46:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:46:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:46:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:46:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:46:00.044  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:46:01.001   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:06.006   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:11.010   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:16.015   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:19.851   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:46:19.851   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:46:19.851   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 772958857939; DSPS: 25426952; Offset : -3013802059
,06-30 10:46:21.019   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:26.024   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:31.028   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:35.747   486   486 D charger_monitor: init target 500000
,06-30 10:46:35.752   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:46:35.761  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:46:35.761  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:46:35.761  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:46:35.761  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 10:46:35.764  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:46:35.799  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
06-30 10:46:35.800  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:46:35.800  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
,06-30 10:46:35.804  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:46:35.805  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:46:35.805  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:46:35.805  1870  2037 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
06-30 10:46:35.805  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:46:35.807  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:46:35.808  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:46:35.811   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:46:35.811   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:46:35.812   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:46:36.033   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:39.852   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:46:39.852   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:46:39.852   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 792959614494; DSPS: 26082337; Offset : -3013806778
,06-30 10:46:41.038   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:46.042   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:51.047   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:56.051   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:46:59.853   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:46:59.853   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:46:59.853   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 812960588289; DSPS: 26737729; Offset : -3013809415
,06-30 10:47:00.038  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:47:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:47:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:47:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:47:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:47:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:47:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:47:01.056   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:06.060   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:11.065   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:16.070   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:19.854   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:47:19.854   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:47:19.854   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 832961349271; DSPS: 27393114; Offset : -3013811243
,06-30 10:47:21.074   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:26.079   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:31.083   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:35.909   486   486 D charger_monitor: init target 500000
,06-30 10:47:35.914   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:47:35.915  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:47:35.915  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:47:35.915  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:47:35.916  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:47:35.916  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:47:35.954  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
06-30 10:47:35.954  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:47:35.954  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,06-30 10:47:35.957  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:47:35.958  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:47:35.959  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:47:35.959  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:47:35.959  1870  2037 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
06-30 10:47:35.963  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:47:35.964  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:47:35.967   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:47:35.967   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 10:47:35.970   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:47:36.088   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:39.854   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:47:39.854   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:47:39.854   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 852962090461; DSPS: 28048498; Offset : -3013802578
,06-30 10:47:41.093   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:46.097   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:51.102   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:56.106   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:47:59.855   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:47:59.855   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:47:59.855   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 872962774933; DSPS: 28703880; Offset : -3013789936
,06-30 10:48:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:48:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:48:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:48:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:48:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:48:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:48:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:48:01.111   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:06.115   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:11.120   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:16.125   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:19.856   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:48:19.856   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:48:19.856   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 892963476540; DSPS: 29359263; Offset : -3013791691
,06-30 10:48:21.129   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:26.134   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:31.138   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:36.067   486   486 D charger_monitor: init target 500000
,06-30 10:48:36.073  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:48:36.073  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:48:36.073  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:48:36.074  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:48:36.074  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:48:36.082   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 10:48:36.119  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
06-30 10:48:36.119  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:48:36.120  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
,06-30 10:48:36.124  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:48:36.124  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:48:36.124  1870  2037 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
06-30 10:48:36.124  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:48:36.125  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:48:36.127  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:48:36.128  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:48:36.131   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:48:36.131   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:48:36.132   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:48:36.143   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:39.856   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:48:39.856   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:48:39.857   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 912964165594; DSPS: 30014646; Offset : -3013802745
,06-30 10:48:41.148   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:46.152   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:51.157   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:56.161   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:48:59.857   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:48:59.857   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:48:59.857   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 932964933399; DSPS: 30670031; Offset : -3013797827
,06-30 10:49:00.038  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:49:00.038  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:49:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:49:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:49:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:49:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:49:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:49:01.166   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:06.170   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:11.175   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:16.180   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:19.858   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:49:19.858   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:49:19.858   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 952965621777; DSPS: 31325414; Offset : -3013811405
,06-30 10:49:21.184   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:21.684   944  1282 D PowerManagerServiceEx: acquireWakeLockInternal: lock=731858183, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=944
,06-30 10:49:21.702   944  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{300400db type 2 when 954788 com.google.android.gms} when 954788
,06-30 10:49:21.719   944   944 D PowerManagerServiceEx: releaseWakeLockInternal: lock=731858183 [*alarm*], flags=0x0
,06-30 10:49:21.880  2404  2404 D WearableService: callingUid 10006, callindPid: 2404
,06-30 10:49:22.017  2404  7425 I CheckinUtil: Classify the device as Phone.
,06-30 10:49:22.042  2404  7425 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:49:22.042  2404  7425 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:49:22.042  2404  7425 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:49:22.042  2404  7425 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:49:22.043   278  1042 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 10:49:22.043   278  1042 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 10:49:22.043   278  7427 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:49:22.043   278  7427 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:49:22.044   278  7427 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-30 10:49:22.044   278  7427 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:49:22.091   278  7427 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:49:22.092  2404  7425 I System.out: propertyValue:false
,06-30 10:49:22.150  2404  7425 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:49:22.150  2404  7425 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:49:22.431  3969  7415 D ChimeraConfigService: Fetched value, gms:chimera:dogfoods = null
,06-30 10:49:22.437  3969  7415 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
06-30 10:49:22.438  3969  7415 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
06-30 10:49:22.541   944  1924 I ActivityManager: Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7435 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:49:22.800  7435  7456 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 10:49:22.800  7435  7456 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 10:49:22.908  7435  7456 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,06-30 10:49:23.038  7435  7456 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-30 10:49:23.040  7435  7456 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-30 10:49:23.107  7435  7467 D ChimeraCfgMgr: Reading stored module config
,06-30 10:49:23.135  7435  7449 I art     : CheckpointMarkThreadRoots callback created = 0xaaf372d0
,06-30 10:49:23.184  7435  7449 I art     : CheckpointMarkThreadRoots callback created = 0xaaf372a0
,06-30 10:49:23.228  7435  7467 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,06-30 10:49:23.233  7435  7467 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000003@DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodlmp_xhdpi_release.apk': Failed to open oat filename for reading: No such file or directory
06-30 10:49:23.240  7435  7467 D ChimeraFileApk: Classloading successful. Optimized code found.
06-30 10:49:23.278  7435  7467 D DynamitePackage: Instantiated singleton DynamitePackage.
,06-30 10:49:23.280  7435  7467 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
06-30 10:49:23.299  7435  7435 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,06-30 10:49:23.318  7435  7435 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:49:23.318  7435  7435 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:49:23.377   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:49:23.377   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
06-30 10:49:23.377   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 10:49:23.380  7435  7435 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,06-30 10:49:23.722  7435  7435 I NotificationManager: com.google.android.youtube: cancel(2) by com.google.android.youtube
,06-30 10:49:23.753   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:49:23.753   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
06-30 10:49:23.753   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:49:23.754  7435  7435 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
06-30 10:49:23.760   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:49:23.760   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
06-30 10:49:23.760   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:49:23.760  7435  7435 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
06-30 10:49:23.762   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:49:23.762   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
06-30 10:49:23.762   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:49:23.764  7435  7435 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
,06-30 10:49:23.773  7435  7435 W InstanceID/Rpc: Found 10006
06-30 10:49:23.803   245   324 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 10:49:23.803   245   324 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,06-30 10:49:23.803   245   324 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 10:49:23.804  7435  7435 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,06-30 10:49:23.902   944  2189 I ActivityManager: Killing 6868:com.google.android.talk/u0a61 (adj 15): empty #11
,06-30 10:49:23.914  7435  7508 I NotificationManager: com.google.android.youtube: cancel(10436) by com.google.android.youtube
06-30 10:49:23.973   944  1344 W libprocessgroup: failed to open /acct/uid_10061/pid_6868/cgroup.procs: No such file or directory
,06-30 10:49:24.000  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:49:24.000  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:49:24.000  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:49:24.001  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:49:24.001   278  1042 E BandwidthController: [LG DATA] No such appUid: 10100
06-30 10:49:24.001   278  1042 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-30 10:49:24.001   278  7559 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:49:24.001   278  7559 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:49:24.001   278  7559 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:49:24.002   278  7559 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:49:24.052   278  7559 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:49:24.052  7435  7555 I System.out: propertyValue:false
,06-30 10:49:24.053  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:49:24.053  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:49:26.189   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:31.193   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:33.148  7435  7535 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:49:33.148  7435  7535 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:49:33.148  7435  7535 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:49:33.149  7435  7535 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:49:33.152   278  1042 E BandwidthController: [LG DATA] No such appUid: 10100
06-30 10:49:33.152   278  1042 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-30 10:49:33.152   278  7574 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:49:33.153   278  7574 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:49:33.153   278  7574 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:49:33.154   278  7574 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:49:33.200   278  7574 D libc-netbsd: res_queryN name = xxxxx succeed
,06-30 10:49:33.205  7435  7535 I System.out: propertyValue:false
06-30 10:49:33.206  7435  7535 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:49:33.206  7435  7535 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:49:33.258  7435  7535 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:49:33.258  7435  7535 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:49:36.199   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:36.233   486   486 D charger_monitor: init target 500000
,06-30 10:49:36.238   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:49:36.248  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:49:36.248  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,06-30 10:49:36.251  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:49:36.251  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:49:36.251  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:49:39.859   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:49:39.859   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:49:39.859   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 972966434842; DSPS: 31980800; Offset : -3013793569
,06-30 10:49:41.203   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:46.208   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:51.212   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:56.217   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:49:59.860   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:49:59.860   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:49:59.860   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 992967269262; DSPS: 32636188; Offset : -3013811557
,06-30 10:50:00.040  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:50:00.040  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:50:00.040  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:50:00.044  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:50:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:50:00.046  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:50:00.046  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:50:01.221   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:06.226   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:11.231   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:16.235   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:19.860   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:50:19.860   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:50:19.860   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1012967955504; DSPS: 33291570; Offset : -3013797040
,06-30 10:50:21.240   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:26.244   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:31.249   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:36.253   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:36.387   486   486 D charger_monitor: init target 500000
,06-30 10:50:36.392   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:50:36.401  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:50:36.401  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:50:36.401  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:50:36.401  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 10:50:36.404  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:50:36.438  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
06-30 10:50:36.438  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:50:36.438  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,06-30 10:50:36.441  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:50:36.443  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:50:36.443  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:50:36.443  1870  2037 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
06-30 10:50:36.441  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:50:36.444  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:50:36.446  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:50:36.449   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:50:36.449   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:50:36.449   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:50:39.861   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:50:39.861   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:50:39.861   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1032968707423; DSPS: 33946955; Offset : -3013807671
,06-30 10:50:41.258   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:46.263   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:51.267   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:55.006   944  1282 D PowerManagerServiceEx: acquireWakeLockInternal: lock=731858183, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=944
,06-30 10:50:55.013   944  1282 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1bf7c552 type 2 when 1048110 com.android.bluetooth} when 1048110
06-30 10:50:55.039  2052  5832 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
06-30 10:50:55.039  2052  5832 W bt-smp  : Plain text(LSB ~ MSB) = 4f e4 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 10:50:55.039  2052  5832 W bt-smp  : Encrypted text(LSB ~ MSB) = 4b 11 70 c7 6e 6e 1e b4 70 57 11 97 6d a4 c9 74 
,06-30 10:50:55.042  2052  5832 W bt-btm  : Stopping oneshot timer
06-30 10:50:55.046   944   944 D PowerManagerServiceEx: releaseWakeLockInternal: lock=731858183 [*alarm*], flags=0x0
06-30 10:50:56.272   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:50:59.862   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:50:59.862   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:50:59.862   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1052969480801; DSPS: 34602340; Offset : -3013799549
,06-30 10:51:00.040  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:51:00.040  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:51:00.040  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:51:00.045  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:51:00.045  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:51:00.046  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:51:00.047  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:51:01.276   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:06.281   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:11.286   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:16.290   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:19.863   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:51:19.863   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:51:19.863   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1072970481888; DSPS: 35257733; Offset : -3013803198
,06-30 10:51:21.295   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:26.299   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:31.304   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:36.308   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:36.547   486   486 D charger_monitor: init target 500000
,06-30 10:51:36.554   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:51:36.561  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:51:36.561  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:51:36.561  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:51:36.561  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 10:51:36.564  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:51:39.864   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:51:39.864   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:51:39.864   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1092971176932; DSPS: 35913116; Offset : -3013810242
,06-30 10:51:41.313   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:46.318   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:51.322   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:56.327   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:51:59.864   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:51:59.864   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:51:59.864   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1112971957081; DSPS: 36568501; Offset : -3013792928
,06-30 10:52:00.041  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:52:00.041  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:52:00.041  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:52:00.045  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:52:00.045  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:52:00.046  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:52:00.047  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:52:01.331   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:06.336   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:11.340   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:16.345   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:19.870   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:52:19.870   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:52:19.870   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1132977497593; DSPS: 37224043; Offset : -3013808672
,06-30 10:52:21.350   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:26.354   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:31.359   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:36.363   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:36.709   486   486 D charger_monitor: init target 500000
,06-30 10:52:36.714   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:52:36.715  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:52:36.715  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:52:36.715  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:52:36.715  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:52:36.716  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:52:39.870   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:52:39.871   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:52:39.871   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1152978234565; DSPS: 37879427; Offset : -3013802898
,06-30 10:52:41.368   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:46.372   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:51.377   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:56.382   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:52:59.871   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:52:59.871   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:52:59.871   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1172979020286; DSPS: 38534813; Offset : -3013809775
,06-30 10:53:00.038  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:53:00.038  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:53:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:53:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:53:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:53:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:53:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:53:01.386   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:06.391   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:11.395   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:16.400   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:19.872   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:53:19.872   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:53:19.872   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1192979699550; DSPS: 39190195; Offset : -3013801950
,06-30 10:53:21.404   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:26.409   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:31.414   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:36.418   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:36.869   486   486 D charger_monitor: init target 500000
,06-30 10:53:36.874   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:53:36.875  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:53:36.875  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:53:36.875  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:53:36.876  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:53:36.876  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:53:39.873   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:53:39.873   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:53:39.873   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1212980453449; DSPS: 39845580; Offset : -3013812006
,06-30 10:53:41.423   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:46.427   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:51.305   944  1018 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 10:53:51.432   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:56.436   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:53:59.873   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:53:59.873   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:53:59.874   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1232981127764; DSPS: 40500962; Offset : -3013808244
,06-30 10:54:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:54:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:54:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:54:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:54:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:54:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:54:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:54:01.441   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:06.445   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:11.450   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:16.455   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:19.874   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:54:19.874   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:54:19.874   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1252981881715; DSPS: 41156346; Offset : -3013786767
,06-30 10:54:21.459   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:24.016  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.016  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:24.016  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.016  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:54:24.019   278  1042 E BandwidthController: [LG DATA] No such appUid: 10100
06-30 10:54:24.019   278  1042 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-30 10:54:24.022   278  7614 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:54:24.022   278  7614 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:54:24.022   278  7614 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:54:24.023   278  7614 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:54:24.068   278  7614 D libc-netbsd: res_queryN name = xxxxx succeed
,06-30 10:54:24.072  7435  7555 I System.out: propertyValue:false
06-30 10:54:24.073  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.073  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:24.300  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.301  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:24.301  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.301  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:24.464  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.464  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:24.467  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.467  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:24.624  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.624  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:24.627  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.627  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:24.783  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.783  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:24.783  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.783  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:24.966  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.966  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:24.966  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:24.967  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:25.133  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:25.133  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:25.134  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:25.134  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:25.297  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:25.297  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:25.298  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:25.298  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:25.471  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:25.471  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:25.471  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:25.471  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:25.633  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:25.633  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:25.634  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:25.636  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:25.794  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:25.794  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:25.795  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:25.798  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:25.952  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:25.953  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:25.953  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:25.953  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:26.113  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:26.113  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:26.113  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:26.113  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:54:26.116   278  1042 E BandwidthController: [LG DATA] No such appUid: 10100
06-30 10:54:26.116   278  1042 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-30 10:54:26.119   278  7627 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:54:26.119   278  7627 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:54:26.119   278  7627 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:54:26.120   278  7627 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:54:26.120   278  7627 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:54:26.121  7435  7555 I System.out: propertyValue:false
06-30 10:54:26.121  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:26.121  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:26.278  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:26.282  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:26.282  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:26.283  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:26.451  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:26.455  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:26.455  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:26.455  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:26.464   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:26.620  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:26.620  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:26.620  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:26.620  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:26.784  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:26.784  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:26.784  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:26.785  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:26.940  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:26.943  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:26.943  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:26.943  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:27.096  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:27.097  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:27.100  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:27.100  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:27.254  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:27.254  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:27.258  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:27.258  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:27.428  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:27.428  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:27.429  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:27.429  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:27.586  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:27.589  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:27.589  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:27.589  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:27.748  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:27.748  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:27.749  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:27.749  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:27.914  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:27.916  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:27.917  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:27.917  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:28.083  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:28.083  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:28.084  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:28.084  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:28.242  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:28.243  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:28.243  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:28.243  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:54:28.246   278  1042 E BandwidthController: [LG DATA] No such appUid: 10100
06-30 10:54:28.246   278  1042 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-30 10:54:28.248   278  7641 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:54:28.248   278  7641 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:54:28.249   278  7641 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:54:28.249   278  7641 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:54:28.249   278  7641 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:54:28.250  7435  7555 I System.out: propertyValue:false
06-30 10:54:28.251  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:28.251  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:28.403  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:28.407  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:28.407  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:28.407  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:28.565  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:28.565  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:28.566  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:28.566  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:28.742  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:28.744  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:28.745  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:28.745  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:28.898  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:28.901  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:28.902  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:28.902  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:29.062  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:29.062  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:29.062  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:29.063  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:29.225  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:29.227  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:29.227  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:29.227  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:29.382  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:29.382  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:29.386  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:29.386  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:29.548  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:29.548  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:29.549  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:29.549  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:29.737  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:29.737  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:29.737  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:29.737  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:29.896  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:29.896  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:29.897  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:29.897  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:30.066  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.066  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:30.069  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.069  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:30.234  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.234  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:30.235  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.235  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:30.405  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.405  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:30.406  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.406  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 10:54:30.409   278  1042 E BandwidthController: [LG DATA] No such appUid: 10100
06-30 10:54:30.409   278  1042 D DnsProxyListener: App 10100 tries DNS query. Accept family:0 protocol:0
06-30 10:54:30.411   278  7656 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 10:54:30.411   278  7656 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 10:54:30.412   278  7656 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 10:54:30.412   278  7656 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 10:54:30.412   278  7656 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 10:54:30.413  7435  7555 I System.out: propertyValue:false
06-30 10:54:30.414  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.414  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:30.569  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.569  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:30.574  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.574  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:30.731  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.731  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:30.736  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.736  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:30.890  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.890  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:30.890  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:30.890  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:31.044  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:31.044  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:31.045  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:31.047  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:31.223  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:31.225  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:31.226  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:31.226  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:31.382  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:31.383  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:31.383  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:31.383  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:31.468   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:31.542  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:31.542  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:31.543  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:31.543  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 10:54:31.699  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:31.702  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:31.703  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:31.703  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:31.859  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:31.862  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:31.862  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:31.862  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:32.021  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 10:54:32.024  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:32.024  7435  7555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 10:54:32.024  7435  7555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 10:54:36.473   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:37.029   486   486 D charger_monitor: init target 500000
,06-30 10:54:37.035  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:54:37.035  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:54:37.035  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:54:37.035  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:54:37.036  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:54:37.042   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 10:54:39.875   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:54:39.875   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:54:39.875   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1272982635197; DSPS: 41811731; Offset : -3013796485
,06-30 10:54:41.477   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:46.482   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:51.487   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:56.491   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:54:59.876   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:54:59.876   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:54:59.876   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1292983319355; DSPS: 42467114; Offset : -3013815742
,06-30 10:55:00.040  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:55:00.040  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:55:00.040  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:55:00.044  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:55:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:55:00.045  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:55:00.046  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:55:01.496   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:06.500   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:11.505   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:16.509   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:19.876   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:55:19.876   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:55:19.876   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1312984051848; DSPS: 43122498; Offset : -3013813639
,06-30 10:55:21.514   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:26.519   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:31.523   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:36.528   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:37.187   486   486 D charger_monitor: init target 500000
,06-30 10:55:37.194   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:55:37.201  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:55:37.201  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:55:37.201  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:55:37.201  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 10:55:37.204  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:55:39.877   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:55:39.877   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:55:39.877   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1332984804549; DSPS: 43777882; Offset : -3013794194
,06-30 10:55:41.532   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:46.537   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:51.541   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:56.546   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:55:59.878   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:55:59.878   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:55:59.878   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1352985487302; DSPS: 44433265; Offset : -3013812615
,06-30 10:56:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:56:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:56:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:56:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:56:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:56:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:56:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:56:01.551   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:06.555   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:11.560   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:16.571   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:19.879   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:56:19.879   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:56:19.879   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1372986323179; DSPS: 45088652; Offset : -3013800895
,06-30 10:56:21.575   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:26.580   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:31.584   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:36.589   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:37.347   486   486 D charger_monitor: init target 500000
,06-30 10:56:37.352   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:56:37.361  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:56:37.361  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:56:37.361  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:56:37.361  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 10:56:37.364  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:56:37.397  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
06-30 10:56:37.397  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:56:37.398  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,06-30 10:56:37.401  1907  1907 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 10:56:37.402  1870  2037 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 10:56:37.402  1870  2037 D LEDHandler: Battery Level Remaining: 100%
06-30 10:56:37.402  1870  2037 D LEDHandler: Battery Temp: 289, mChargingStatus=5, mChargingStop=false
06-30 10:56:37.403  1907  1907 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 10:56:37.404  2052  5810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 10:56:37.406  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 10:56:37.408   944   944 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:56:37.408   944   944 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 10:56:37.409   944  1309 D WifiController: battery changed pluggedType: 2
06-30 10:56:39.879   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:56:39.879   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:56:39.879   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1392987069265; DSPS: 45744036; Offset : -3013786945
,06-30 10:56:41.594   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:46.598   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:51.603   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:56.607   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:56:59.880   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:56:59.880   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:56:59.880   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1412987756445; DSPS: 46399419; Offset : -3013801695
,06-30 10:57:00.038  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:57:00.038  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:57:00.038  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:57:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:57:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:57:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:57:00.044  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:57:01.612   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:57:06.616   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:57:11.621   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:57:16.625   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:57:19.881   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:57:19.881   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:57:19.881   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1432988590708; DSPS: 47054806; Offset : -3013791329
,06-30 10:57:21.630   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:57:26.635   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:57:31.639   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:57:36.644   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:57:37.509   486   486 D charger_monitor: init target 500000
,06-30 10:57:37.514   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:57:37.515  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:57:37.515  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:57:37.515  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:57:37.515  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:57:37.516  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:57:39.882   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:57:39.882   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,06-30 10:57:39.882   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1452989420023; DSPS: 47710193; Offset : -3013787056
06-30 10:57:41.648   294   360 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 10:57:46.653   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:57:51.657   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:57:56.662   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:57:59.883   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:57:59.883   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:57:59.883   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1472990383194; DSPS: 48365585; Offset : -3013799588
,06-30 10:58:00.040  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:58:00.040  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:58:00.040  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:58:00.044  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:58:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:58:00.045  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:58:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:58:01.667   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:06.671   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:11.676   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:16.680   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:19.883   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:58:19.883   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:58:19.883   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1492991062665; DSPS: 49020967; Offset : -3013793535
,06-30 10:58:21.685   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:26.690   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:31.694   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:36.699   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:37.669   486   486 D charger_monitor: init target 500000
,06-30 10:58:37.674   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 10:58:37.675  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 10:58:37.675  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 10:58:37.675  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 10:58:37.676  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 10:58:37.676  1870  1870 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 10:58:39.884   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:58:39.884   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:58:39.884   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1512991813335; DSPS: 49676352; Offset : -3013804582
,06-30 10:58:41.703   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:46.708   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:51.712   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:56.717   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,06-30 10:58:59.885   944   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 10:58:59.885   944   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 10:58:59.885   944   981 D sensors_hal_Time: tsOffsetIs: Apps: 1532992582285; DSPS: 50331737; Offset : -3013797477
,06-30 10:59:00.038  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 10:59:00.038  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 10:59:00.038  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,06-30 10:59:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 10:59:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:59:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
06-30 10:59:00.044  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:59:01.722   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),06-30 10:59:05.599  7703  7703 D AndroidRuntime: 
06-30 10:59:05.599  7703  7703 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 10:59:05.621  7703  7703 D AndroidRuntime: CheckJNI is OFF
06-30 10:59:05.994  7703  7703 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 10:59:06.036   944  1019 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
06-30 10:59:06.039   944  1019 I ActivityManager: Killing 5650:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
06-30 10:59:06.093   944  2169 I WindowState: WIN DEATH: Window{3ffd5b4c u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 10:59:06.141   944  2169 D InputDispatcher: Focus left window: Window{3ffd5b4c u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 10:59:06.141   944  2169 D InputDispatcher: Window went away: Window{3ffd5b4c u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 10:59:06.160   944  1019 I ActivityManager:   Force finishing activity ActivityRecord{68d79f2 u0 com.test.thalitest/.MainActivity t241}
06-30 10:59:06.171   944  1064 W PackageSettings: Skipping PackageSetting{307588b com.example.hello/10317} due to missing metadata
06-30 10:59:06.227   944   944 V ActivityManager: Display changed displayId=0
06-30 10:59:06.234  1775  1775 D DSDPConnection: Display #0 changed.
06-30 10:59:06.248   944  1935 W ActivityManager: Spurious death for ProcessRecord{160a3023 5650:com.test.thalitest/u0a30}, curProc for 5650: null
06-30 10:59:06.251   944  1064 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
06-30 10:59:06.252   944  1064 I ActivityManager:   Force finishing activity ActivityRecord{68d79f2 u0 com.test.thalitest/.MainActivity t241 f}
06-30 10:59:06.253   944  1064 W ActivityManager: Duplicate finish request for ActivityRecord{68d79f2 u0 com.test.thalitest/.MainActivity t241 f}
06-30 10:59:06.316  1368  1368 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
06-30 10:59:06.326  1907  1907 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
06-30 10:59:06.331  3363  3363 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 10:59:06.343  3363  3363 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
06-30 10:59:06.344  3363  3363 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
06-30 10:59:06.344  3363  3363 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
06-30 10:59:06.344  3363  3363 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:59:06.344  3363  3363 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:59:06.344  3363  3363 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 10:59:06.344  3363  3363 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
06-30 10:59:06.344  3363  3363 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:59:06.344  3363  3363 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:59:06.344  3363  3363 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
06-30 10:59:06.344  3363  3363 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
06-30 10:59:06.345   944  1284 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 10:59:06.349  2404  2688 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 10:59:06.369   944  1019 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7736 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
06-30 10:59:06.376  1945  1945 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
06-30 10:59:06.389  2019  2019 I art     : Explicit concurrent mark sweep GC freed 19166(1056KB) AllocSpace objects, 6(172KB) LOS objects, 40% free, 12MB/20MB, paused 1.899ms total 133.078ms
06-30 10:59:06.407  3969  3969 I art     : Explicit concurrent mark sweep GC freed 28571(1538KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 16MB/22MB, paused 1.108ms total 142.024ms
06-30 10:59:06.411  1945  1945 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
06-30 10:59:06.413  3969  3980 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
06-30 10:59:06.452  1368  1368 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
06-30 10:59:06.451  1945  1945 I [LGHome]EVENT: [LauncherModel.java:1358:startLoader()]startLoader isLaunching=true
06-30 10:59:06.457  1368  1503 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-30 10:59:06.457  1368  1503 D KeyguardModel: createShortcutInfo...
06-30 10:59:06.461  1368  1503 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-30 10:59:06.461  1368  1503 D KeyguardModel: createShortcutInfo...
06-30 10:59:06.464  1368  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:59:06.464  1945  2051 I [LGHome]Launcher.Model: [LauncherModel.java:1475:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
06-30 10:59:06.464  1368  1503 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-30 10:59:06.466  1368  1503 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-30 10:59:06.466  1368  1503 D KeyguardModel: createShortcutInfo...
06-30 10:59:06.466  1945  1945 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
06-30 10:59:06.468  1945  1945 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
06-30 10:59:06.468  1368  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:59:06.468  1368  1503 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-30 10:59:06.469  1945  1945 I Activity: Activity.onPostResume() called 
06-30 10:59:06.470  1368  1503 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-30 10:59:06.470  1368  1503 D KeyguardModel: createShortcutInfo...
06-30 10:59:06.476  1368  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:59:06.476  1368  1503 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-30 10:59:06.487  1945  1945 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
06-30 10:59:06.493  1368  1503 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-30 10:59:06.493  1368  1503 D KeyguardModel: createShortcutInfo...
06-30 10:59:06.523  1368  1368 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
06-30 10:59:06.523  1368  1368 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
06-30 10:59:06.530  1945  7758 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
06-30 10:59:06.530  1368  1368 D KeyguardModel: handleShortcutListChanged...
06-30 10:59:06.537  1368  1503 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-30 10:59:06.537  1368  1503 D KeyguardModel: createShortcutInfo...
06-30 10:59:06.540  1368  1503 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-30 10:59:06.540  1368  1503 D KeyguardModel: createShortcutInfo...
06-30 10:59:06.543  1368  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:59:06.543  1368  1503 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-30 10:59:06.546  1368  1503 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-30 10:59:06.546  1368  1503 D KeyguardModel: createShortcutInfo...
06-30 10:59:06.546   944   944 I art     : Explicit concurrent mark sweep GC freed 58144(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 24MB/36MB, paused 4.174ms total 256.511ms
06-30 10:59:06.553   944  1064 I art     : WaitForGcToComplete blocked for 146.110ms for cause Explicit
06-30 10:59:06.556  1368  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:59:06.556  1368  1503 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-30 10:59:06.573   944  1049 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
06-30 10:59:06.577   944  2189 D InputDispatcher: Focus entered window: Window{1dc2c677 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
06-30 10:59:06.578   944  1049 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
06-30 10:59:06.580  1368  1368 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
06-30 10:59:06.580  1368  1368 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
06-30 10:59:06.580  1368  1368 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
06-30 10:59:06.580  1368  1368 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
06-30 10:59:06.583  1368  1503 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-30 10:59:06.583  1368  1503 D KeyguardModel: createShortcutInfo...
06-30 10:59:06.583   944  1049 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
06-30 10:59:06.583   944  1049 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
06-30 10:59:06.583   944  1049 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 10:59:06.583   944  1049 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@77c41,  pkg=WindowManager.LayoutParams
06-30 10:59:06.583   944  1049 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
06-30 10:59:06.591  1368  1503 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 10:59:06.591  1368  1503 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-30 10:59:06.593  1368  1503 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-30 10:59:06.593  1368  1503 D KeyguardModel: createShortcutInfo...
06-30 10:59:06.605  1945  1945 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 10:59:06.605  1945  1945 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 10:59:06.606  1945  1945 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
06-30 10:59:06.614  1368  1368 D KeyguardModel: handleShortcutListChanged...
06-30 10:59:06.626  1945  1945 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
06-30 10:59:06.638  7736  7736 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:59:06.638  7736  7736 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:59:06.639  1945  1945 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
06-30 10:59:06.640  1945  1945 I PhoneWindow: [setNavigationBarColor] color=0x 0
06-30 10:59:06.641  7736  7736 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 10:59:06.665   944  1924 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
06-30 10:59:06.669   944  1924 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5650 uid 10030
06-30 10:59:06.684   944   944 D administrator: Handling package changes for user 0
06-30 10:59:06.726   294   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
06-30 10:59:06.760  1945  1945 I [LGHome]Launcher.Model: [LauncherModel.java:2270:run()] LauncherModel bind current page shortcut
06-30 10:59:06.784   944  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f29687f u0 com.lge.launcher2/.Launcher t240} time:1539892
06-30 10:59:06.794  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-30 10:59:06.819  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
06-30 10:59:06.822  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
06-30 10:59:06.824  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
06-30 10:59:06.826  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
06-30 10:59:06.858  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-30 10:59:06.897   944  1064 I art     : Explicit concurrent mark sweep GC freed 11582(1786KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.474ms total 343.523ms
06-30 10:59:06.918  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
06-30 10:59:06.918  1945  1945 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
06-30 10:59:06.919  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-30 10:59:06.926  7736  7736 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
06-30 10:59:06.944  1853  1853 D LCardEmulationManager: getHceAppCount hostAppNum : 0
06-30 10:59:06.944  1853  1853 D LCardEmulationManager: getDefaultRoute
06-30 10:59:06.951  7736  7736 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
06-30 10:59:06.952  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
06-30 10:59:06.956  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
06-30 10:59:06.956  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
06-30 10:59:06.957  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
06-30 10:59:06.961  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
06-30 10:59:06.975  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
06-30 10:59:06.976  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
06-30 10:59:06.981  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
06-30 10:59:06.983  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
06-30 10:59:06.983  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
06-30 10:59:06.989  7703  7703 D AndroidRuntime: Shutting down VM
06-30 10:59:06.996  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
06-30 10:59:07.008  1945  1945 W Resources: Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
06-30 10:59:07.018   944   944 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
06-30 10:59:07.018   944   944 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 10:59:07.024   944   944 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 10:59:07.031   944  1346 D TaskPersister: removeObsoleteFile: deleting file=241_task.xml
06-30 10:59:07.149  1945  1945 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
06-30 10:59:07.167  7736  7736 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
06-30 10:59:07.186  7020  7020 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
06-30 10:59:07.231   944  1944 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7766 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
06-30 10:59:07.231   944  1944 I ActivityManager: Killing 7053:com.android.gallery3d/u0a23 (adj 15): empty #11
06-30 10:59:07.237  1945  1945 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
06-30 10:59:07.237  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
06-30 10:59:07.238  1945  1945 I [LGHome]Launcher.Model: [LauncherModel.java:2277:run()] LauncherModel bind current page widget
06-30 10:59:07.238  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-30 10:59:07.286   944  1355 W libprocessgroup: failed to open /acct/uid_10023/pid_7053/cgroup.procs: No such file or directory
06-30 10:59:07.309  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
06-30 10:59:07.312  1945  1945 I Choreographer: Skipped 31 frames!  The application may be doing too much work on its main thread.
06-30 10:59:07.312  1945  1945 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
06-30 10:59:07.313  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-30 10:59:07.315  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
06-30 10:59:07.317  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
06-30 10:59:07.319  1945  2223 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
06-30 10:59:07.319  1945  2223 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
06-30 10:59:07.320  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
06-30 10:59:07.322  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
06-30 10:59:07.325  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
06-30 10:59:07.331  1630  1630 E b       : Unable to connect to the editor to retrieve text... will retry later
06-30 10:59:07.332  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-30 10:59:07.333  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-30 10:59:07.335   944  1064 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7785 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
06-30 10:59:07.424  1945  1945 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
06-30 10:59:07.428   944  2189 I ActivityManager: Killing 7075:com.android.contacts/u0a18 (adj 15): empty #11
06-30 10:59:07.446  1945  1945 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
06-30 10:59:07.446  1945  1945 I [LGHome]EVENT: [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
06-30 10:59:07.449  1945  1945 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
06-30 10:59:07.490   944  1879 W libprocessgroup: failed to open /acct/uid_10018/pid_7075/cgroup.procs: No such file or directory
06-30 10:59:07.531  1945  1945 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16eeb82e time:1540639
06-30 10:59:07.606  1945  1945 I art     : Explicit concurrent mark sweep GC freed 29741(1623KB) AllocSpace objects, 19(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.727ms total 72.610ms
06-30 10:59:07.608  7766  7766 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 10:59:07.609  7766  7766 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
06-30 10:59:07.609  7766  7766 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 10:59:07.611  7766  7766 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 10:59:07.613  7766  7766 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
06-30 10:59:07.620  1945  1945 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection

```
