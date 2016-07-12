#### Test 72145431744cc2c_thali01_LGE-LG-D722 Logs


```
--------- beginning of main
07-12 11:36:33.884   293   357 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-12 11:36:35.856  5632  5632 D AndroidRuntime: 
07-12 11:36:35.856  5632  5632 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-12 11:36:35.859  5632  5632 D AndroidRuntime: CheckJNI is OFF
07-12 11:36:36.043  5632  5632 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-12 11:36:36.060   841  1908 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 11:36:36.135   841  1908 D ActivityManager: setTaskToReturnTo : TaskRecord{246b5777 #253 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-12 11:36:36.136   841  1908 D ActivityManager: setTaskToReturnTo : TaskRecord{246b5777 #253 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-12 11:36:36.155   841  1908 D WindowStateEx: AppWindowTokenEx init.. 
07-12 11:36:36.179   841  1032 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-12 11:36:36.185   841  1908 D InputDispatcher: Focus left window: Window{3efbb017 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
07-12 11:36:36.186  5632  5632 D AndroidRuntime: Shutting down VM
07-12 11:36:36.195  1946  1946 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
07-12 11:36:36.212   841  1032 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-12 11:36:36.252   841  1032 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-12 11:36:36.252   841  1032 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-12 11:36:36.270   841  1032 D SplitWindow: check instance of lgWin Window{3adfbe6f u0 Starting com.test.thalitest}
07-12 11:36:36.281   841  2012 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5651 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-12 11:36:36.326  1946  1946 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
07-12 11:36:36.365  1946  1946 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
07-12 11:36:36.376   841  1032 I WindowStateAnimator: Starting window displayed
07-12 11:36:36.385   841  1029 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
07-12 11:36:36.385   841  1029 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
,07-12 11:36:36.388  1368  1368 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
07-12 11:36:36.389   841  1029 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-12 11:36:36.389  1368  1368 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
07-12 11:36:36.389  1368  1368 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
07-12 11:36:36.389  1368  1368 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-12 11:36:36.400   841  1029 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-12 11:36:36.400   841  1029 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 11:36:36.400   841  1029 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3d6cf188,  pkg=WindowManager.LayoutParams
07-12 11:36:36.400   841  1029 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-12 11:36:36.445  5651  5651 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-12 11:36:36.447  2032  2032 I HotwordDetector: Closing mic
07-12 11:36:36.461  2032  2530 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@118d5509
07-12 11:36:36.461  2032  2530 V AudioRecord: stop()
07-12 11:36:36.461  2032  2530 D AudioRecord: AudioRecord->stop()
07-12 11:36:36.461   274  1298 V AudioFlinger: RecordHandle::stop()
07-12 11:36:36.461   274  1298 V AudioFlinger: RecordThread::stop
07-12 11:36:36.473   274  1298 V AudioFlinger: Record stopped OK
07-12 11:36:36.475   274  1298 V AudioPolicyManager: stopInput() input 17
07-12 11:36:36.477   274  1298 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
07-12 11:36:36.477   274  1298 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
07-12 11:36:36.478   274  1058 V AudioPolicyService: AudioCommandThread() waking up
07-12 11:36:36.478   274  1058 V AudioPolicyService: AudioCommandThread() processing release audio patch
07-12 11:36:36.478   274  1058 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
07-12 11:36:36.478   274  1058 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
07-12 11:36:36.478   274  1058 V AudioFlinger: ThreadBase::setParameters() routing=0
07-12 11:36:36.483   274  2554 D audio_hw_primary: in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
07-12 11:36:36.526   274  2554 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
07-12 11:36:36.526   274  2554 V audio_hw_primary: disable_audio_route: enter: usecase(7)
07-12 11:36:36.526   274  2554 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
07-12 11:36:36.526   274  2554 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-12 11:36:36.528   274  2554 V audio_hw_primary: disable_audio_route: exit
07-12 11:36:36.528   274  2554 E audio_hw_primary: disable_snd_device: enter 144
07-12 11:36:36.528   274  2554 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
07-12 11:36:36.528   274  2554 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
07-12 11:36:36.532   274  2554 V audio_hw_primary: stop_input_stream: exit: status(0)
07-12 11:36:36.532   274  2554 V audio_hw_primary: in_standby: exit:  status(0)
07-12 11:36:36.532   274  2554 V AudioFlinger: RecordThread: loop stopping
07-12 11:36:36.533   274  1058 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-12 11:36:36.533   274  2554 V AudioFlinger: RecordThread: loop starting
07-12 11:36:36.533   274  2554 V AudioFlinger: processConfigEvents_l() remaining events 1
07-12 11:36:36.533   274  2554 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3858000
07-12 11:36:36.534   274  2554 V AudioFlinger: RecordThread: loop stopping
07-12 11:36:36.534   274  1058 V AudioPolicyService: AudioCommandThread() going to sleep
07-12 11:36:36.534   274  1298 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
07-12 11:36:36.534   274  1298 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
07-12 11:36:36.534   274  1298 V AudioPolicyService: AudioCommandThread() adding update audio patch list
07-12 11:36:36.534   274  1298 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
07-12 11:36:36.534   274  1059 V AudioPolicyService: AudioCommandThread() waking up
07-12 11:36:36.534   274  1059 V AudioPolicyService: AudioCommandThread() processing update audio patch list
07-12 11:36:36.534   274  1059 V AudioPolicyService: AudioCommandThread() going to sleep
07-12 11:36:36.536   274  1298 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
07-12 11:36:36.536   274  1298 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
07-12 11:36:36.536   274  1058 V AudioPolicyService: AudioCommandThread() waking up
07-12 11:36:36.536   274  1058 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
07-12 11:36:36.536   274  1058 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 274
07-12 11:36:36.536   274  1058 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
07-12 11:36:36.536   274  1058 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-12 11:36:36.537   274  2554 V AudioFlinger: RecordThread: loop starting
07-12 11:36:36.537   274  2554 V AudioFlinger: processConfigEvents_l() remaining events 1
07-12 11:36:36.537   274  2554 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
07-12 11:36:36.537   274  2554 V audio_hw_primary: in_set_parameters: exit: status(0)
07-12 11:36:36.537   274  2554 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3858000
07-12 11:36:36.537   274  2554 V AudioFlinger: RecordThread: loop stopping
07-12 11:36:36.537   274  1058 V AudioPolicyService: AudioCommandThread() going to sleep
07-12 11:36:36.544  2032  2530 V AudioRecord: stop()
07-12 11:36:36.545  2032  2530 V AudioRecord: stop()
07-12 11:36:36.545  2032  2530 V AudioRecord: stop()
07-12 11:36:36.546   274   274 V AudioFlinger: RecordHandle::stop()
07-12 11:36:36.546   274   274 V AudioFlinger: RecordThread::stop
07-12 11:36:36.546   274   274 V AudioPolicyManager: releaseInput() 17
07-12 11:36:36.546   274   274 V AudioPolicyManager: closeInput(17)
07-12 11:36:36.546   274   274 V AudioFlinger: closeInput() 17
07-12 11:36:36.546   274   274 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-12 11:36:36.546   841  1934 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-12 11:36:36.546  2032  2048 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-12 11:36:36.546   274   274 V AudioFlinger: ThreadBase::exit
07-12 11:36:36.547  2845  2862 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-12 11:36:36.547  1368  1399 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-12 11:36:36.547  3102  3119 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-12 11:36:36.547  1776  1808 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-12 11:36:36.547   274  1298 V AudioFlinger: releasing 16 from 2032 for -1
07-12 11:36:36.547   274  1298 V AudioFlinger:  decremented refcount to 0
07-12 11:36:36.547   274  1298 V AudioFlinger: purging stale effects
07-12 11:36:36.547   274  2554 V AudioFlinger: RecordThread: loop starting
07-12 11:36:36.547   274  2554 V AudioFlinger: RecordThread 0xb3858000 exiting
07-12 11:36:36.548   274   274 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dde0)
07-12 11:36:36.548   274   274 D audio_hw_primary: in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
07-12 11:36:36.548   274   274 V audio_hw_primary: in_standby: exit:  status(0)
07-12 11:36:36.548   274   274 V AudioPolicyService: AudioCommandThread() adding update audio port list
07-12 11:36:36.549   274   274 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
07-12 11:36:36.549   274   274 V AudioPolicyManager: releaseInput() exit
07-12 11:36:36.549   274  1059 V AudioPolicyService: AudioCommandThread() waking up
07-12 11:36:36.549   274   274 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
07-12 11:36:36.549   274  1059 V AudioPolicyService: AudioCommandThread() processing update audio port list
07-12 11:36:36.550   274   274 V AudioFlinger: removeClient_l() pid 2032, calling pid 274
07-12 11:36:36.550   274  1059 V AudioPolicyService: AudioCommandThread() going to sleep
07-12 11:36:36.559  2032  2538 I HotwordRecognitionRnr: Stopping hotword detection.
07-12 11:36:36.570  2032  2551 I HotwordRecognitionRnr: Hotword detection finished
07-12 11:36:36.599  5651  5651 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-12 11:36:36.672  5651  5651 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 6570-6581)
07-12 11:36:36.672  5651  5651 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:36.703  5651  5651 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e463c90}
07-12 11:36:36.704  5651  5651 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:36.710  5651  5651 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 11:36:36.730  5651  5651 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-12 11:36:36.732  5651  5651 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:36.737  5651  5651 E SysUtils: ApplicationContext is null in ApplicationStatus
07-12 11:36:36.798  5651  5685 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-12 11:36:36.818  5651  5651 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-12 11:36:36.830  5651  5651 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:36:36.830  5651  5651 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:36:36.833  5651  5651 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:36:36.833  5651  5651 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:36:36.833  5651  5651 I Adreno-EGL: Build Date: 03/02/15 Mon
07-12 11:36:36.833  5651  5651 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-12 11:36:36.833  5651  5651 I Adreno-EGL: Remote Branch: 
07-12 11:36:36.833  5651  5651 I Adreno-EGL: Local Patches: 
07-12 11:36:36.833  5651  5651 I Adreno-EGL: Reconstruct Branch: 
07-12 11:36:36.965   274  1353 V AudioPolicyService: registerClient() client 0xb551c800, uid 10030
07-12 11:36:36.990   841  1030 D BluetoothManagerService: Message: 20
07-12 11:36:36.990   841  1030 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a5d05fe:true
07-12 11:36:36.996  5651  5696 D BluetoothAdapter: 469730629: getState() :  mService = null. Returning STATE_OFF
07-12 11:36:37.133  5651  5651 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:37.148  5651  5651 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-12 11:36:37.155  5651  5651 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-12 11:36:37.160  5651  5651 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-12 11:36:37.160  5651  5651 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-12 11:36:37.173  5651  5651 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-12 11:36:37.181  5651  5651 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:37.181  5651  5651 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:37.185  1860  1860 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-12 11:36:37.186  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-12 11:36:37.186  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-12 11:36:37.186  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-12 11:36:37.186  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
07-12 11:36:37.188   486   486 D charger_monitor: init target 500000
07-12 11:36:37.193   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-12 11:36:37.231  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 304
07-12 11:36:37.231  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-12 11:36:37.231  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 304
07-12 11:36:37.233  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-12 11:36:37.234  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-12 11:36:37.234  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-12 11:36:37.234  1860  2026 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-12 11:36:37.235  1860  2026 D LEDHandler: Battery Level Remaining: 100%
07-12 11:36:37.235  1860  2026 D LEDHandler: Battery Temp: 304, mChargingStatus=5, mChargingStop=false
07-12 11:36:37.236   841  1312 D WifiController: battery changed pluggedType: 2
07-12 11:36:37.236  5483  5483 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-12 11:36:37.257  5651  5651 I Activity: Activity.onPostResume() called 
,07-12 11:36:37.266  5651  5707 D OpenGLRenderer: Render dirty regions requested: true
,07-12 11:36:37.266  5651  5707 I OpenGLRenderer: Initialized EGL, version 1.4
07-12 11:36:37.273  5651  5707 D OpenGLRenderer: Enabling debug mode 0
,07-12 11:36:37.294  5651  5651 D Atlas   : Validating map...
,07-12 11:36:37.299   841  1908 D SplitWindow: check instance of lgWin Window{cd4eaae u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-12 11:36:37.313  5651  5694 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-12 11:36:37.358   841  1908 D InputDispatcher: Focus entered window: Window{cd4eaae u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-12 11:36:37.434   841  1293 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
07-12 11:36:37.442   841  1032 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s205ms
07-12 11:36:37.442   841  1032 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1364afe4 u0 com.test.thalitest/.MainActivity t253} time:127352
07-12 11:36:37.465  5651  5651 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ec833bb time:127375
07-12 11:36:37.566  5651  5651 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5651
07-12 11:36:37.755  5651  5651 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 11:36:38.176  5651  5710 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426114304
,07-12 11:36:38.186  5651  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 11:36:38.186  5651  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 11:36:38.186  5651  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 11:36:38.186  5651  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 11:36:38.186  5651  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 11:36:38.186  5651  5710 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5199e1c added. We now have 1 listener(s)
07-12 11:36:38.190   841  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 11:36:38.194  5651  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,07-12 11:36:38.195  5651  5710 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
07-12 11:36:38.196  5651  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 11:36:38.197  5651  5710 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-12 11:36:38.207  5651  5710 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e981ab added. We now have 1 listener(s)
07-12 11:36:38.207  5651  5710 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 11:36:38.219  5651  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 11:36:38.220  5651  5710 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-12 11:36:38.230  5651  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 11:36:38.230  5651  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 11:36:38.231  5651  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 11:36:38.231  5651  5710 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-12 11:36:38.234  5651  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 11:36:38.234   841  2125 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 11:36:38.235  5651  5710 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
07-12 11:36:38.242  5651  5710 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:38.243  5651  5710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:38.243  5651  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:38.243  5651  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:38.243  5651  5710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:38.243  5651  5710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:38.243  5651  5710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:38.243  5651  5710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:38.243  5651  5710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:38.243  5651  5710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 11:36:38.243  5651  5710 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 11:36:38.243  5651  5710 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 11:36:38.408  5651  5665 I art     : CheckpointMarkThreadRoots callback created = 0xb0730200
,07-12 11:36:38.455  5651  5665 I art     : CheckpointMarkThreadRoots callback created = 0xb07301d0
,07-12 11:36:38.475  5651  5651 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 11:36:38.889   293   357 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-12 11:36:39.104  5651  5722 W jxcore-log: Initializing JXcore engine
07-12 11:36:39.104  5651  5722 W jxcore-log: JXcore engine is ready
,07-12 11:36:39.172  5722  5722 W Thread-659: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6700]" dev="sockfs" ino=6700 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-12 11:36:39.182  5722  5722 W Thread-659: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-12 11:36:39.182  5722  5722 W Thread-659: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6826]" dev="sockfs" ino=6826 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-12 11:36:39.182  5722  5722 W Thread-659: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-12 11:36:39.182  5722  5722 W Thread-659: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-12 11:36:39.182  5722  5722 W Thread-659: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25340]" dev="sockfs" ino=25340 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-12 11:36:39.218  5651  5722 W jxcore-log: Starting JXcore engine
,07-12 11:36:39.358  5651  5722 W jxcore-log: Platform android
07-12 11:36:39.358  5651  5722 W jxcore-log: 
,07-12 11:36:39.359  5651  5722 W jxcore-log: Process ARCH arm
07-12 11:36:39.359  5651  5722 W jxcore-log: 
07-12 11:36:39.648  5651  5722 I jxcore-log: JXcore Cordova bridge is ready!
07-12 11:36:39.648  5651  5722 I jxcore-log: 
07-12 11:36:39.648  5651  5722 W jxcore-log: JXcore engine is started
,07-12 11:36:39.657  5651  5710 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-12 11:36:39.658  5651  5651 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-12 11:36:42.440   841   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-12 11:36:42.440   841   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-12 11:36:42.440   841   985 D sensors_hal_Time: tsOffsetIs: Apps: 132350148079; DSPS: 4435510; Offset : -3014569087
,07-12 11:36:43.893   293   357 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-12 11:36:46.815  2322  2352 I art     : Explicit concurrent mark sweep GC freed 46524(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 14MB/23MB, paused 1.657ms total 118.572ms
,07-12 11:36:47.991  2845  2845 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,07-12 11:36:48.000  2845  2845 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,07-12 11:36:48.898   293   357 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-12 11:36:53.903   293   357 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-12 11:36:55.723   841  1039 I PowerManagerService: ALS enabled for SRE
07-12 11:36:55.723   841  1039 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (25633 ms ago)
,07-12 11:36:55.744   841  1345 D qdlights: set_light_backlight: 254
,07-12 11:36:55.757   841  1345 D qdlights: set_light_backlight: 251
,07-12 11:36:55.774   841  1345 D qdlights: set_light_backlight: 248
,07-12 11:36:55.790   841  1345 D qdlights: set_light_backlight: 244
,07-12 11:36:55.807   841  1345 D qdlights: set_light_backlight: 241
,07-12 11:36:55.824   841  1345 D qdlights: set_light_backlight: 238
,07-12 11:36:55.840   841  1345 D qdlights: set_light_backlight: 234
,07-12 11:36:55.857   841  1345 D qdlights: set_light_backlight: 231
,07-12 11:36:55.874   841  1345 D qdlights: set_light_backlight: 228
,07-12 11:36:55.890   841  1345 D qdlights: set_light_backlight: 224
,07-12 11:36:55.907   841  1345 D qdlights: set_light_backlight: 221
,07-12 11:36:55.924   841  1345 D qdlights: set_light_backlight: 218
,07-12 11:36:55.941   841  1345 D qdlights: set_light_backlight: 214
,07-12 11:36:55.957   841  1345 D qdlights: set_light_backlight: 211
,07-12 11:36:55.974   841  1345 D qdlights: set_light_backlight: 208
,07-12 11:36:55.977  5651  5722 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 11:36:55.977  5651  5722 I jxcore-log: 
07-12 11:36:55.981  5651  5722 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 11:36:55.981  5651  5722 I jxcore-log: 
07-12 11:36:55.983  5651  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:55.983  5651  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:55.983  5651  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:55.983  5651  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:55.983  5651  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:55.983  5651  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:55.983  5651  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:55.983  5651  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:55.983  5651  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:55.983  5651  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:55.984  5651  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 11:36:55.987  5651  5722 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 11:36:55.987  5651  5722 I jxcore-log: 
,07-12 11:36:55.990  5651  5722 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 11:36:55.990  5651  5722 I jxcore-log: 
07-12 11:36:55.991   841  1345 D qdlights: set_light_backlight: 204
07-12 11:36:56.007   841  1345 D qdlights: set_light_backlight: 201
,07-12 11:36:56.024   841  1345 D qdlights: set_light_backlight: 198
,07-12 11:36:56.041   841  1345 D qdlights: set_light_backlight: 194
,07-12 11:36:56.057   841  1345 D qdlights: set_light_backlight: 191
,07-12 11:36:56.074   841  1345 D qdlights: set_light_backlight: 188
,07-12 11:36:56.090   841  1345 D qdlights: set_light_backlight: 184
,07-12 11:36:56.107   841  1345 D qdlights: set_light_backlight: 181
,07-12 11:36:56.124   841  1345 D qdlights: set_light_backlight: 178
,07-12 11:36:56.141   841  1345 D qdlights: set_light_backlight: 174
,07-12 11:36:56.157   841  1345 D qdlights: set_light_backlight: 171
,07-12 11:36:56.174   841  1345 D qdlights: set_light_backlight: 168
,07-12 11:36:56.190   841  1345 D qdlights: set_light_backlight: 164
,07-12 11:36:56.207   841  1345 D qdlights: set_light_backlight: 161
,07-12 11:36:56.224   841  1345 D qdlights: set_light_backlight: 158
,07-12 11:36:56.240   841  1345 D qdlights: set_light_backlight: 154
,07-12 11:36:56.257   841  1345 D qdlights: set_light_backlight: 151
,07-12 11:36:56.274   841  1345 D qdlights: set_light_backlight: 148
,07-12 11:36:56.290   841  1345 D qdlights: set_light_backlight: 144
,07-12 11:36:56.307   841  1345 D qdlights: set_light_backlight: 141
,07-12 11:36:56.324   841  1345 D qdlights: set_light_backlight: 138
,07-12 11:36:56.340   841  1345 D qdlights: set_light_backlight: 134
,07-12 11:36:56.357   841  1345 D qdlights: set_light_backlight: 131
,07-12 11:36:56.374   841  1345 D qdlights: set_light_backlight: 128
,07-12 11:36:56.390   841  1345 D qdlights: set_light_backlight: 124
,07-12 11:36:56.407   841  1345 D qdlights: set_light_backlight: 121
,07-12 11:36:56.424   841  1345 D qdlights: set_light_backlight: 118
,07-12 11:36:56.441   841  1345 D qdlights: set_light_backlight: 114
,07-12 11:36:56.457   841  1345 D qdlights: set_light_backlight: 111
,07-12 11:36:56.474   841  1345 D qdlights: set_light_backlight: 108
,07-12 11:36:56.491   841  1345 D qdlights: set_light_backlight: 104
,07-12 11:36:56.507   841  1345 D qdlights: set_light_backlight: 101
,07-12 11:36:56.524   841  1345 D qdlights: set_light_backlight: 98
,07-12 11:36:56.541   841  1345 D qdlights: set_light_backlight: 94
,07-12 11:36:56.557   841  1345 D qdlights: set_light_backlight: 91
,07-12 11:36:56.569  5651  5722 I jxcore-log: Unit Test app is loaded
07-12 11:36:56.569  5651  5722 I jxcore-log: 
,07-12 11:36:56.576   841  1345 D qdlights: set_light_backlight: 88
07-12 11:36:56.582  5651  5722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 11:36:56.582  5651  5722 I jxcore-log: 
07-12 11:36:56.587  5651  5651 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-12 11:36:56.591   841  1345 D qdlights: set_light_backlight: 84
07-12 11:36:56.601   841  1293 D WifiServiceImplEx: setWifiEnabled: true pid=5651, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,07-12 11:36:56.607   841  1345 D qdlights: set_light_backlight: 81
07-12 11:36:56.614   841  1293 D WifiService: setWifiEnabled: true pid=5651, uid=10030
,07-12 11:36:56.624   841  1345 D qdlights: set_light_backlight: 78
,07-12 11:36:56.633   841  1991 D WifiServiceImplEx: disconnect pid=5651, uid=10030, packageName=com.test.thalitest
07-12 11:36:56.640   841   861 D WifiServiceImplEx: reconnect pid=5651, uid=10030, packageName=com.test.thalitest
07-12 11:36:56.640   841  1345 D qdlights: set_light_backlight: 74
07-12 11:36:56.645   841  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-12 11:36:56.647   841  1919 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
07-12 11:36:56.655   841  1307 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-12 11:36:56.657   841  1345 D qdlights: set_light_backlight: 71
,07-12 11:36:56.659   841  1307 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
07-12 11:36:56.664   841  1307 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
07-12 11:36:56.664   841  1307 E WifiHW  : band=b
07-12 11:36:56.664   841  1307 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
07-12 11:36:56.666   841   841 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-12 11:36:56.667   841   841 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-12 11:36:56.668   841  1030 D BluetoothManagerService: Message: 1
07-12 11:36:56.669   841  1030 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,07-12 11:36:56.673   841   841 D Ulp_jni : JNI:system_update. Event-4
07-12 11:36:56.674   841  1345 D qdlights: set_light_backlight: 68
07-12 11:36:56.675  5651  5722 I jxcore-log: My device name is: LGE-LG-D722
07-12 11:36:56.675  5651  5722 I jxcore-log: 
07-12 11:36:56.679   841   841 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-12 11:36:56.688   841   841 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,07-12 11:36:56.689   841   841 D Ulp_jni : JNI:system_update. Event-4
07-12 11:36:56.690   269  1055 D SoftapController: Softap fwReload - Ok
07-12 11:36:56.691   841  1345 D qdlights: set_light_backlight: 64
07-12 11:36:56.697  2056  2056 D BluetoothAdapterService(37326222): onBind()
07-12 11:36:56.705   841   841 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,07-12 11:36:56.707   841  1030 D BluetoothManagerService: Message: 40
07-12 11:36:56.707   841  1345 D qdlights: set_light_backlight: 61
07-12 11:36:56.708   841  1030 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-12 11:36:56.713   841  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:36:56.713   841  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:36:56.716   269  1055 D CommandListener: Setting iface cfg
07-12 11:36:56.716   269  1055 D CommandListener: Trying to bring down wlan0
07-12 11:36:56.716   269  1055 D CommandListener: Clearing all IP addresses on wlan0
,07-12 11:36:56.724   841  1345 D qdlights: set_light_backlight: 58
07-12 11:36:56.734   841  1307 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,07-12 11:36:56.741   841  1345 D qdlights: set_light_backlight: 54
07-12 11:36:56.743  2056  2071 I bluedroid: config_hci_snoop_log
07-12 11:36:56.749   841  1030 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
,07-12 11:36:56.751   841  1030 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-12 11:36:56.758   841  1345 D qdlights: set_light_backlight: 51
07-12 11:36:56.780   841  1345 D qdlights: set_light_backlight: 48
,07-12 11:36:56.796  2056  2072 V LGMDMManagerInternal: Create singleton instance
,07-12 11:36:56.799   841  1345 D qdlights: set_light_backlight: 44
07-12 11:36:56.810   841  1345 D qdlights: set_light_backlight: 41
,07-12 11:36:56.813  5767  5767 I wpa_supplicant: Successfully initialized wpa_supplicant
07-12 11:36:56.827   841  1345 D qdlights: set_light_backlight: 38
,07-12 11:36:56.839   841  1307 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-12 11:36:56.848  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 11:36:56.849   841  1345 D qdlights: set_light_backlight: 34
,07-12 11:36:56.857   841  1345 D qdlights: set_light_backlight: 31
07-12 11:36:56.863  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:36:56.873  5767  5767 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-12 11:36:56.873  5767  5767 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-12 11:36:56.876   841  1345 D qdlights: set_light_backlight: 28
07-12 11:36:56.879  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:36:56.877 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-12 11:36:56.879  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
07-12 11:36:56.891   841  1345 D qdlights: set_light_backlight: 24
,07-12 11:36:56.908   841  1345 D qdlights: set_light_backlight: 21
,07-12 11:36:56.916  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:36:56.924   841  1345 D qdlights: set_light_backlight: 18
,07-12 11:36:56.929  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:36:56.929  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-12 11:36:56.929  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
07-12 11:36:56.941   841  1345 D qdlights: set_light_backlight: 14
,07-12 11:36:56.944   841   973 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5780 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
07-12 11:36:56.948   841   841 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-12 11:36:56.955  2056  2072 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:56.955  2056  2072 D BluetoothAdapterService(37326222): enable() - Enable called with quiet mode status =  false
,07-12 11:36:56.957  2056  2150 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-12 11:36:56.957  2056  2150 D BluetoothAdapterProperties: Setting state to 11
07-12 11:36:56.958  2056  2150 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-12 11:36:56.960  2056  2150 D BluetoothAdapterService(37326222): updateAdapterState() - Broadcasting state to 1 receivers.
07-12 11:36:57.001   841  1030 D BluetoothManagerService: Message: 60
,07-12 11:36:57.003   841  1030 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-12 11:36:57.006   841  1030 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-12 11:36:57.008   841  1345 D qdlights: set_light_backlight: 10
07-12 11:36:57.009  2056  2150 D BluetoothAdapterService(37326222): processStart()
07-12 11:36:57.011  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: Unable to read settings
07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:57.026  2056  2150 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:36:57.029  2056  2150 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-12 11:36:57.029  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-12 11:36:57.030  2056  2150 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-12 11:36:57.030  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-12 11:36:57.030  2056  2150 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-12 11:36:57.031  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-12 11:36:57.031  2056  2150 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,07-12 11:36:57.032  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-12 11:36:57.032  2056  2150 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-12 11:36:57.032  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-12 11:36:57.033  2056  2150 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-12 11:36:57.033  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-12 11:36:57.033  2056  2150 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-12 11:36:57.034  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-12 11:36:57.034  2056  2150 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
07-12 11:36:57.034  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
07-12 11:36:57.034  2056  2150 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
07-12 11:36:57.035  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-12 11:36:57.035  2056  2150 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
07-12 11:36:57.035  2056  2150 D BluetoothAdapterService(37326222): processStart() - Make Bond State Machine
07-12 11:36:57.046  2056  2150 D BluetoothBondStateMachine: make
,07-12 11:36:57.049  2056  5797 I BluetoothBondStateMachine: StableState(): Entering Off State
07-12 11:36:57.049  2056  2150 D BluetoothAdapterService: setAdapterService() - set to: null
07-12 11:36:57.049  2056  2150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.049  2056  2150 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-12 11:36:57.054  2056  2150 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-12 11:36:57.055  2056  2150 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: Unable to read settings
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:57.055  2056  2150 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:36:57.055  2056  2150 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-12 11:36:57.056  2056  2150 D BluetoothAdapterService(37326222): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
07-12 11:36:57.080   841  1867 I ActivityManager: Process com.google.android.apps.docs (pid 5380) has died
,07-12 11:36:57.086  1860  1860 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:57.090  2056  2150 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-12 11:36:57.090  2056  2150 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-12 11:36:57.090  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-12 11:36:57.090  2056  2150 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-12 11:36:57.090  2056  2150 D BluetoothAdapterService(37326222): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
07-12 11:36:57.099  2056  5778 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:57.100  2056  2071 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:57.106  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
,07-12 11:36:57.108  2056  2150 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-12 11:36:57.108  2056  2150 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-12 11:36:57.108  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-12 11:36:57.108  2056  2150 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-12 11:36:57.108  2056  2150 D BluetoothAdapterService(37326222): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
07-12 11:36:57.110  2056  2056 D HeadsetService: Received start request. Starting profile...
07-12 11:36:57.113  1368  1368 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
07-12 11:36:57.115  2056  2150 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-12 11:36:57.115  2056  2150 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-12 11:36:57.115  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-12 11:36:57.116  2056  2150 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-12 11:36:57.116  2056  2150 D BluetoothAdapterService(37326222): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
07-12 11:36:57.116   841   841 D BluetoothHeadset: Proxy object connected
07-12 11:36:57.116  1776  1776 D BluetoothHeadset: Proxy object connected
07-12 11:36:57.121  2056  2150 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-12 11:36:57.121  2056  2150 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-12 11:36:57.121  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-12 11:36:57.121  2056  2150 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-12 11:36:57.121  2056  2150 D BluetoothAdapterService(37326222): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
,07-12 11:36:57.125  2056  5778 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:57.126  2056  2150 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-12 11:36:57.126  2056  2150 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-12 11:36:57.126  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-12 11:36:57.126  2056  2150 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-12 11:36:57.126  2056  2150 D BluetoothAdapterService(37326222): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
07-12 11:36:57.131  2056  2150 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-12 11:36:57.131  2056  2150 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-12 11:36:57.131  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-12 11:36:57.131  2056  2056 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-12 11:36:57.131  2056  2150 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-12 11:36:57.131  2056  2150 D BluetoothAdapterService(37326222): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
07-12 11:36:57.136  2056  2150 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-12 11:36:57.136  2056  2150 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-12 11:36:57.136  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-12 11:36:57.136  2056  2150 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-12 11:36:57.136  2056  2150 D BluetoothAdapterService(37326222): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
07-12 11:36:57.147  2056  2056 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-12 11:36:57.148  2056  2056 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 11:36:57.151  2056  2150 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-12 11:36:57.151  2056  2150 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
07-12 11:36:57.151  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
07-12 11:36:57.151  2056  2150 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
07-12 11:36:57.151  2056  2150 D BluetoothAdapterService(37326222): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
07-12 11:36:57.155  2056  2150 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-12 11:36:57.155  2056  2150 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
07-12 11:36:57.156  2056  2150 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-12 11:36:57.156  2056  2150 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
07-12 11:36:57.156  2056  2150 D BluetoothAdapterService(37326222): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
07-12 11:36:57.157  2056  2056 D HeadsetStateMachine: make
07-12 11:36:57.160  2056  2150 V LGMDMManager: Create singleton instance
07-12 11:36:57.169  2056  2150 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-12 11:36:57.185  1776  1776 D BluetoothHeadset: Proxy object connected
,07-12 11:36:57.194  1776  1776 D BluetoothHeadset: Proxy object connected
07-12 11:36:57.214  2056  2056 D HeadsetStateMachine: max_hf_connections = 1
,07-12 11:36:57.214  2056  2056 I bluedroid: get_profile_interface handsfree
07-12 11:36:57.222  2056  2056 I bt-btif : btif_hf_get_interface
07-12 11:36:57.222  2056  2056 I bt-btif : init
07-12 11:36:57.222  2056  2056 D bt-btif : max_hf_clients = 1
07-12 11:36:57.222  2056  2056 D bt-btif : btif_max_hf_clients = 1
07-12 11:36:57.222  2056  2056 D bt-btif : btif_enable_service: current services:0xa0639330
07-12 11:36:57.225  2056  2056 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-12 11:36:57.227   274   274 V AudioPolicyService: registerClient() client 0xb551c920, uid 1002
07-12 11:36:57.227   274  1353 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-12 11:36:57.229   274  1353 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-12 11:36:57.229   274  1353 V AudioPolicyManagerEx: getOutput() returns output 2
07-12 11:36:57.229   274  1603 V AudioFlinger: registerClient() client 0xb384c0a0, pid 2056
,07-12 11:36:57.229   274  1603 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
07-12 11:36:57.229   274  1603 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
07-12 11:36:57.229   274  1603 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
07-12 11:36:57.230  2056  2056 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-12 11:36:57.230   274  1291 V AudioFlinger: thread 0xb56eb000 type 0 TID 1291 waking up
07-12 11:36:57.230   274  1294 V AudioFlinger: thread 0xb5735000 type 0 TID 1294 waking up
07-12 11:36:57.230   274  1290 V AudioFlinger: thread 0xb5651000 type 0 TID 1290 waking up
07-12 11:36:57.230   274  1294 V AudioFlinger: processConfigEvents_l() remaining events 1
07-12 11:36:57.230   274  1294 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
07-12 11:36:57.231   274  1290 V AudioFlinger: processConfigEvents_l() remaining events 1
07-12 11:36:57.231   274  1290 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
07-12 11:36:57.232   274  1291 V AudioFlinger: processConfigEvents_l() remaining events 1
07-12 11:36:57.232   274  1291 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
07-12 11:36:57.234   274  1291 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:57.234   274  1291 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:57.234   841  1952 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:57.234   841  1952 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:57.235  1368  1399 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:57.235   274  1291 V AudioFlinger: processConfigEvents_l() DONE thread 0xb56eb000
07-12 11:36:57.235   274  1290 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:57.235   274  1290 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:57.235  1776  2865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:57.235  1776  2865 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:57.235   274  1294 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-12 11:36:57.235   274  1294 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-12 11:36:57.235   274  1290 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
07-12 11:36:57.235   274  1294 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5735000
07-12 11:36:57.236  1776  2865 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:57.236  1368  1399 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:57.236  1776  2865 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:57.236  1368  1399 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:57.236  1776  2865 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-12 11:36:57.236  1776  2865 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-12 11:36:57.236  1368  1399 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:57.236  2032  2047 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:57.236  2032  2047 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:57.236  1368  1399 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-12 11:36:57.236  1368  1399 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-12 11:36:57.236  2032  2047 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:57.236  2032  2047 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:57.236  2032  2047 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-12 11:36:57.236  2032  2047 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-12 11:36:57.236  2056  2071 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:57.236  2056  20,71 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-12 11:36:57.236  2056  2071 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:57.236  2056  2071 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-12 11:36:57.236  2056  2071 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-12 11:36:57.236  2056  2071 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
07-12 11:36:57.236   841  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:57.236   841  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:57.236   841  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-12 11:36:57.236   841  1867 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-12 11:36:57.237  2056  2056 V ToneGenerator: Create Track: 0xb4909480
07-12 11:36:57.237  2056  2056 V AudioTrack: set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-12 11:36:57.237  2056  2056 V AudioTrack: set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
07-12 11:36:57.237  2845  2863 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:57.237  3102  3119 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-12 11:36:57.237  2845  2863 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:57.237  3102  3119 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-12 11:36:57.237  2845  2863 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:57.237  3102  3119 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-12 11:36:57.237  2845  2863 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:57.237  3102  3119 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-12 11:36:57.237  2845  2863 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-12 11:36:57.237  2845  2863 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-12 11:36:57.237   274   274 I AudioFlinger: isAudioPlaybackHookOn() false
07-12 11:36:57.237  3102  3119 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-12 11:36:57.237  3102  3119 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-12 11:36:57.237  2056  2056 D AudioTrack: TrackOffload: AudioTrack Offload disabled by property, returning false
07-12 11:36:57.237   274  1353 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-12 11:36:57.238   274  1353 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-12 11:36:57.238   274  1353 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-12 11:36:57.238   274  1353 V AudioPolicyManagerEx: getOutput() returns output 2
07-12 11:36:57.238  2056  2056 V AudioSystem: getLatency() output 2, latency 50
07-12 11:36:57.239  2056  2056 V AudioSystem: getFrameCount() output 2, frameCount 960
07-12 11:36:57.239  2056  2056 V AudioTrack: createTrack_l() output 2 afLatency 50
07-12 11:36:57.239  2056  2056 V AudioTrack: Create normal PCM 0x1 Track
07-12 11:36:57.239   274  1298 V AudioFlinger: createTrack() lSessionId: 22
07-12 11:36:57.239   274  1298 V AudioFlinger: AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
07-12 11:36:57.239   274  1298 V AudioFlinger: sendConfigEvent_l() num events 1 event 1
07-12 11:36:57.240  2056  2056 V AudioTrack: Flags here  0x4 
07-12 11:36:57.240  2056  2056 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-12 11:36:57.242   274  1603 V AudioFlinger: acquiring 22 from 2056, for 2056
07-12 11:36:57.242   274  1603 V AudioFlinger:  added new entry for 22
07-12 11:36:57.242  2056  2056 V ToneGenerator: ToneGenerator INIT OK, time: 147152
07-12 11:36:57.242  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.244  2056  5800 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-12 11:36:57.245  2056  5800 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-12 11:36:57.245  2056  5800 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-12 11:36:57.246  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.246   274  1290 V AudioFlinger: processConfigEvents_l() remaining events 1
07-12 11:36:57.247   274  1290 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
07-12 11:36:57.248  2056  5800 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-12 11:36:57.248   841   841 D BluetoothA2dp: Proxy object connected
07-12 11:36:57.249   274  1353 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 2056
07-12 11:36:57.249  2056  2056 D A2dpService: Received start request. Starting profile...
07-12 11:36:57.250  2056  2056 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 11:36:57.251  2056  2056 V Avrcp   : make
07-12 11:36:57.251  2056  2056 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-12 11:36:57.251  2056  2056 I bluedroid: get_profile_interface avrcp
07-12 11:36:57.251   274  1353 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-12 11:36:57.251   274  1353 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-12 11:36:57.251   274  1353 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-12 11:36:57.251   274  1353 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-12 11:36:57.251   274  1353 V voice   : voice_set_parameters: exit with code(0)
07-12 11:36:57.251   274  1353 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-12 11:36:57.251   274  1353 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-12 11:36:57.252  2056  2056 I bt-btif : btif_rc_get_interface
07-12 11:36:57.252  2056  2056 I bt-btif : ## init ##
07-12 11:36:57.255  2056  2072 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:57.255  2056  2056 I LGBluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 11:36:57.256   274  1353 V msm8974_platform: platform_set_parameters: exit with code(0)
07-12 11:36:57.256   274  1353 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-12 11:36:57.257   274  1353 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-12 11:36:57.257   274  1353 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-12 11:36:57.258  2056  2056 I LGBluetoothAvrcpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-12 11:36:57.258  2056  2056 I LGBluetoothAvrcpServiceJni: initNative: succeeds
,07-12 11:36:57.261  2056  5800 V ToneGenerator: ToneGenerator destructor
07-12 11:36:57.261  2056  5800 V ToneGenerator: stopTone
07-12 11:36:57.261  2056  5800 V ToneGenerator: Delete Track: 0xb4909480
07-12 11:36:57.279  2056  2056 I BluetoothAvrcpBrcmAdapterJni: classInitBrcmNative
,07-12 11:36:57.287  2056  2056 I BluetoothAvrcpBrcmAdapterJni: initBrcmNative
07-12 11:36:57.289   274  1298 V AudioFlinger: remove track (4099) and delete from mixer
07-12 11:36:57.289   274  1298 V AudioPolicyService: AudioCommandThread() adding release output 2
07-12 11:36:57.289   274  1298 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-12 11:36:57.289   274  1298 V AudioFlinger: PlaybackThread::Track destructor
07-12 11:36:57.289   274  1059 V AudioPolicyService: AudioCommandThread() waking up
07-12 11:36:57.289   274  1298 V AudioFlinger: removeClient_l() pid 2056, calling pid 274
07-12 11:36:57.289   274  1059 V AudioPolicyService: AudioCommandThread() processing release output 2
07-12 11:36:57.289   274  1059 V AudioPolicyManager: releaseOutput() 2
07-12 11:36:57.289   274  1059 V AudioPolicyService: AudioCommandThread() going to sleep
07-12 11:36:57.289  2056  5800 V AudioTrack: ~AudioTrack, releasing session id from 2056 on behalf of 2056
07-12 11:36:57.289   274  1353 V AudioFlinger: releasing 22 from 2056 for 2056
07-12 11:36:57.289   274  1353 V AudioFlinger:  decremented refcount to 0
07-12 11:36:57.289   274  1353 V AudioFlinger: purging stale effects
07-12 11:36:57.411   841   861 V AudioService: updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,07-12 11:36:57.415   841   861 E AudioService: No RCC entry present to update
07-12 11:36:57.416  2056  2056 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-12 11:36:57.417  2056  2056 I BluetoothA2dpServiceJni: classInitNative
07-12 11:36:57.417  2056  2056 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 11:36:57.417  2056  2056 D A2dpStateMachine: make
07-12 11:36:57.419  2056  2056 I bluedroid: get_profile_interface a2dp
07-12 11:36:57.419  2056  2056 I bt-btif : btif_av_get_src_interface
07-12 11:36:57.419  2056  2056 I bt-btif : init
07-12 11:36:57.419  2056  2056 D bt-btif : btif_enable_service: current services:0xa0639330
07-12 11:36:57.420  2056  2056 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,07-12 11:36:57.421  2056  2056 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-12 11:36:57.422  2056  2056 D LGBluetoothPowerControlManager: [BTUI] getInstance
07-12 11:36:57.423  2056  2056 D LGBluetoothPowerControlManager: [BTUI] init
07-12 11:36:57.425  2056  2056 D LGBluetoothPowerControlManager: [BTUI] init : getProfileProxy
07-12 11:36:57.427   841  1030 D BluetoothManagerService: Message: 30
07-12 11:36:57.430  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.431  2056  5805 D A2dpStateMachine: Enter Disconnected: -2
07-12 11:36:57.432  2056  2056 I BluetoothHidServiceJni: classInitNative: succeeds
07-12 11:36:57.435  2056  2056 D HidService: Received start request. Starting profile...
,07-12 11:36:57.435  2056  2056 I bluedroid: get_profile_interface hidhost
07-12 11:36:57.435  2056  2056 I bt-btif : btif_hh_get_interface
07-12 11:36:57.435  2056  2056 I bt-btif : init
07-12 11:36:57.435  2056  2056 D bt-btif : btif_enable_service: current services:0xa0639330
07-12 11:36:57.435  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.436  2056  2056 I BluetoothHealthServiceJni: classInitNative: succeeds
07-12 11:36:57.449  2056  2056 D HealthService: Received start request. Starting profile...
,07-12 11:36:57.452  2056  2056 I bluedroid: get_profile_interface health
07-12 11:36:57.452  2056  2056 I bt-btif : btif_hl_get_interface
07-12 11:36:57.452  2056  2056 I bt-btif : init
07-12 11:36:57.452  2056  2056 D bt-btif : Process name (droid.bluetooth)
07-12 11:36:57.452  2056  2056 D bt-btif : btif_hl_soc_thread_init
07-12 11:36:57.455  2056  2056 D bt-btif : create_thread: entered
07-12 11:36:57.456  2056  2056 D bt-btif : create_thread: thread created successfully
07-12 11:36:57.456  2056  5807 D bt-btif : entered btif_hl_select_thread
07-12 11:36:57.456  2056  5807 D bt-btif : btif_hl_select_wakeup_init
07-12 11:36:57.456  2056  5807 D bt-btif : btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
07-12 11:36:57.456  2056  5807 D bt-btif : max_s=55 
07-12 11:36:57.456  2056  5807 D bt-btif : set curr_set = org_set 
07-12 11:36:57.456  2056  2056 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-12 11:36:57.456  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.467  2056  2056 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-12 11:36:57.472  2056  2056 D PanService: Received start request. Starting profile...
07-12 11:36:57.472  2056  2056 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 11:36:57.472  2056  2056 I bluedroid: get_profile_interface pan
07-12 11:36:57.472  2056  2056 D bt-btif : stack_initialized = 0, btpan_cb.enabled:0
07-12 11:36:57.480  2056  2056 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,07-12 11:36:57.480  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.482  2056  2056 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-12 11:36:57.488  2056  2056 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 11:36:57.488  2056  2056 D BtGatt.GattService: Received start request. Starting profile...
07-12 11:36:57.489  2056  2056 D BtGatt.GattService: start()
07-12 11:36:57.489  2056  2056 I bluedroid: get_profile_interface gatt
07-12 11:36:57.489  2056  2056 D BtGatt.AdvertiseManager: advertise manager created
07-12 11:36:57.497  2056  2056 I LGBluetoothGattAdapter: [BTUI] getInstance : create [LGBluetoothGattAdapter]
07-12 11:36:57.498  2056  2056 D LGBluetoothGattAdapter: setGattService:  set to: null
07-12 11:36:57.498  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
,07-12 11:36:57.501  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.502  2056  2056 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-12 11:36:57.503  2056  2056 V BluetoothMapService: BluetoothMapBinder()
07-12 11:36:57.504  2056  2056 D BluetoothMapService: Received start request. Starting profile...
07-12 11:36:57.504  2056  2056 D BluetoothMapService: start()
07-12 11:36:57.510  2056  2056 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-12 11:36:57.510  2056  2056 D BluetoothMapEmailAppObserver: createReceiver()
07-12 11:36:57.511  2056  2056 D BluetoothMapEmailAppObserver: initObservers()
07-12 11:36:57.511  2056  2056 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,07-12 11:36:57.519  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.524  2056  2056 I BluetoothSAPServiceJni: classInitNative(L170): succeeds
,07-12 11:36:57.527  2056  2056 D SapService: Received start request. Starting profile...
07-12 11:36:57.527  2056  2056 D BluetoothSAPServiceJni: initializeNative(L175): sap
07-12 11:36:57.527  2056  2056 I bluedroid: get_profile_interface sap
07-12 11:36:57.527  2056  2056 I bt-btif : btif_sc_get_interface
07-12 11:36:57.527  2056  2056 I bt-btif : init
07-12 11:36:57.527  2056  2056 D bt-btif : btif_enable_service: current services:0xa0639330
07-12 11:36:57.527  2056  2056 I LGBluetoothSapAdapter: [BTUI] getInstance : create [LGBluetoothSapAdapter]
07-12 11:36:57.527  2056  2056 I LGBluetoothSapAdapter: [BTUI] Create LGBluetoothSapManager Instance
07-12 11:36:57.529  2056  2056 D LGBluetoothSapManager: [BTUI] initSapManager
07-12 11:36:57.534  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.542  1776  1776 D LgeBluetoothSimManager: [BTUI] SAP_ENABLE_EVT
,07-12 11:36:57.549  2056  2056 V BluetoothFTPServiceJni: classInitNative
07-12 11:36:57.550  2056  2056 I BluetoothFTPServiceJni: classInitNative(L271): succeeds
07-12 11:36:57.550  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.551  2056  2056 D BluetoothFTPService: BluetoothFtpBinder()
07-12 11:36:57.552  2056  2056 D **BluetoothFTPService: Received start request. Starting profile...
07-12 11:36:57.552  2056  2056 V BluetoothFTPService: FTP-Server Service start
07-12 11:36:57.554  2056  2056 D BluetoothFTPServiceJni: initFtpNativeDataNative(L275): FTP
07-12 11:36:57.555  2056  2056 I bluedroid: get_profile_interface ftp
07-12 11:36:57.555  2056  2056 I bt-btif : btif_fts_get_interface
07-12 11:36:57.555  2056  2056 I bt-btif : init
07-12 11:36:57.555  2056  2056 D bt-btif : btif_enable_service: current services:0xa0639330
07-12 11:36:57.555  2056  2056 D BluetoothFTPServiceJni: initFtpNativeDataNative(L317): FTP init done
07-12 11:36:57.555  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.561  2056  2056 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-12 11:36:57.561  2056  2056 E BluetoothOPPServiceJni: classInitNative
07-12 11:36:57.561  2056  2056 I BluetoothOPPServiceJni: classInitNative(L373): succeeds
07-12 11:36:57.562  2056  2056 V OppService: Opp initBinder
07-12 11:36:57.562  2056  2056 D **OppService: Received start request. Starting profile...
07-12 11:36:57.563  2056  2056 D OppService: Starting OppService 
07-12 11:36:57.563  2056  2056 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,07-12 11:36:57.570  2056  2056 I NotificationManager: com.android.bluetooth: cancelAll by com.android.bluetooth
07-12 11:36:57.571  2056  2056 V BluetoothOppNotification: send message
07-12 11:36:57.577  2056  2056 D BluetoothOppPreference: Dumping Names:  
07-12 11:36:57.577  2056  2056 D BluetoothOppPreference: {}
07-12 11:36:57.577  2056  2056 D BluetoothOppPreference: Dumping Channels:  
07-12 11:36:57.577  2056  2056 D BluetoothOppPreference: {}
07-12 11:36:57.578  2056  2056 D OppService: Start()
07-12 11:36:57.578  2056  2056 W BluetoothOPPServiceJni: initOppNative
,07-12 11:36:57.578  2056  2056 D BluetoothOPPServiceJni: initOppNative(L383): OPP
07-12 11:36:57.578  2056  2056 I bluedroid: get_profile_interface opp
07-12 11:36:57.578  2056  2056 I bt-btif : btif_op_get_interface
07-12 11:36:57.578  2056  2056 D BluetoothOPPServiceJni: initOppNative(L411): mOppCallbacksObj 1049850
07-12 11:36:57.578  2056  2056 D BluetoothOPPServiceJni: initOppNative(L413): calling OPP init
07-12 11:36:57.579  5780  5780 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:36:57.580  2056  2056 I bt-btif : btif_opp_init
07-12 11:36:57.580  2056  2056 D bt-btif : btif_enable_service: current services:0xa0639330
07-12 11:36:57.580  2056  2056 D BluetoothOPPServiceJni: initOppNative(L429): OPC and OPS init Succesful
07-12 11:36:57.580  2056  2056 D BluetoothOPPServiceJni: initOppNative(L430): mOppCallbacksObj 1049850
07-12 11:36:57.580  2056  2056 V OppService: setOppService(): set to: com.broadcom.bt.service.opp.OppService@3cdd92e4
07-12 11:36:57.580  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
07-12 11:36:57.581  2056  2056 D HeadsetStateMachine: Proxy object connected
07-12 11:36:57.582  2056  2056 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-12 11:36:57.583  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - Message: 1
07-12 11:36:57.583  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-12 11:36:57.583  2056  2056 D BluetoothAdapterService(37326222): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-12 11:36:57.583  2056  2056 D BluetoothAdapterState: isTurningOnRadio()=false
07-12 11:36:57.583  2056  2056 D BluetoothAdapterState: isTurningOffRadio()=false
07-12 11:36:57.583  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-12 11:36:57.583  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-12 11:36:57.583  2056  2056 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-12 11:36:57.584  5780  5780 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-12 11:36:57.584  5780  5780 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-12 11:36:57.585  5780  5780 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-12 11:36:57.586  2056  5817 V OppService: pendingUpdate is :  true
07-12 11:36:57.586  5780  5780 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-12 11:36:57.588  2056  5817 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-12 11:36:57.590  2056  5817 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20e07313 on behalf of 
,07-12 11:36:57.592  2056  5817 V BluetoothOppNotification: update too frequent, put in queue
07-12 11:36:57.592  2056  5813 V OppService: Deleted complete outbound shares, number =  0
07-12 11:36:57.594  2056  2056 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-12 11:36:57.594  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - Message: 1
07-12 11:36:57.594  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-12 11:36:57.594  2056  2056 D BluetoothAdapterService(37326222): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-12 11:36:57.594  2056  2056 D BluetoothAdapterState: isTurningOnRadio()=false
07-12 11:36:57.594  2056  2056 D BluetoothAdapterState: isTurningOffRadio()=false
07-12 11:36:57.594  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-12 11:36:57.594  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-12 11:36:57.594  2056  2056 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-12 11:36:57.594  2056  5800 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-12 11:36:57.595  2056  5817 V OppService: pendingUpdate is :  false
07-12 11:36:57.595  2056  5800 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 11:36:57.595  2056  5813 V OppService: Deleted complete inbound failed shares, number = 0
07-12 11:36:57.595  2056  5800 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-12 11:36:57.595  2056  5813 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-12 11:36:57.596  2056  5817 E OppService: UpdateThread is Completed
07-12 11:36:57.596  2056  5813 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3652f950 on behalf of 
07-12 11:36:57.600  2056  2056 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-12 11:36:57.600  2056  2056 D BluetoothA2dp: Proxy object connected
07-12 11:36:57.600  2056  2056 D LGBluetoothPowerControlManager: [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@d2ab749
07-12 11:36:57.600  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - Message: 1
07-12 11:36:57.600  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-12 11:36:57.600  2056  2056 D BluetoothAdapterService(37326222): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-12 11:36:57.600  2056  2056 D BluetoothAdapterState: isTurningOnRadio()=false
07-12 11:36:57.600  2056  2056 D BluetoothAdapterState: isTurningOffRadio()=false
07-12 11:36:57.600  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-12 11:36:57.600  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-12 11:36:57.600  2056  2056 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-12 11:36:57.603  2056  2056 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-12 11:36:57.603  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - Message: 1
07-12 11:36:57.603  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-12 11:36:57.603  2056  2056 D BluetoothAdapterService(37326222): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-12 11:36:57.604  2056  2056 D BluetoothAdapterState: isTurningOnRadio()=false
07-12 11:,36:57.604  2056  2056 D BluetoothAdapterState: isTurningOffRadio()=false
07-12 11:36:57.604  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-12 11:36:57.604  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-12 11:36:57.604  2056  2056 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,07-12 11:36:57.609  2056  2056 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-12 11:36:57.609  2056  2056 V PanService: [BTUI] SIM Extra State :ABSENT
07-12 11:36:57.609  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - Message: 1
07-12 11:36:57.609  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-12 11:36:57.609  2056  2056 D BluetoothAdapterService(37326222): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
07-12 11:36:57.609  2056  2056 D BluetoothAdapterState: isTurningOnRadio()=false
07-12 11:36:57.610  2056  2056 D BluetoothAdapterState: isTurningOffRadio()=false
07-12 11:36:57.610  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-12 11:36:57.610  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-12 11:36:57.610  2056  2056 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-12 11:36:57.612  2056  2056 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-12 11:36:57.612  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - Message: 1
07-12 11:36:57.612  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-12 11:36:57.612  2056  2056 D BluetoothAdapterService(37326222): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
07-12 11:36:57.612  2056  2056 D BluetoothAdapterState: isTurningOnRadio()=false
07-12 11:36:57.612  2056  2056 D BluetoothAdapterState: isTurningOffRadio()=false
07-12 11:36:57.612  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-12 11:36:57.612  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-12 11:36:57.612  2056  2056 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-12 11:36:57.615  2056  2056 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-12 11:36:57.615  2056  2056 V BluetoothMapService: Handler(): got msg=1
07-12 11:36:57.615  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - Message: 1
07-12 11:36:57.615  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-12 11:36:57.615  2056  2056 D BluetoothAdapterService(37326222): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-12 11:36:57.615  2056  2056 D BluetoothAdapterState: isTurningOnRadio()=false
07-12 11:36:57.616  2056  2056 D BluetoothAdapterState: isTurningOffRadio()=false
07-12 11:36:57.616  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-12 11:36:57.616  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-12 11:36:57.616  2056  2056 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,07-12 11:36:57.620  2056  2056 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-12 11:36:57.621  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - Message: 1
07-12 11:36:57.621  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-12 11:36:57.621  2056  2056 D BluetoothAdapterService(37326222): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-12 11:36:57.621  2056  2056 D BluetoothAdapterState: isTurningOnRadio()=false
07-12 11:36:57.621  2056  2056 D BluetoothAdapterState: isTurningOffRadio()=false
07-12 11:36:57.621  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-12 11:36:57.621  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-12 11:36:57.621  2056  2056 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-12 11:36:57.623  2056  2056 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-12 11:36:57.623  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - Message: 1
07-12 11:36:57.623  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-12 11:36:57.623  2056  2056 D BluetoothAdapterService(37326222): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
07-12 11:36:57.623  2056  2056 D BluetoothAdapterState: isTurningOnRadio()=false
07-12 11:36:57.623  2056  2056 D BluetoothAdapterState: isTurningOffRadio()=false
07-12 11:36:57.623  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-12 11:36:57.623  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-12 11:36:57.623  2056  2056 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-12 11:36:57.625  2056  2056 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-12 11:36:57.625  2056  2056 V BluetoothOppNotification: new notify threadi!
07-12 11:36:57.626  2056  2056 V BluetoothOppNotification: send delay message
07-12 11:36:57.627  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - Message: 1
07-12 11:36:57.627  2056  2056 D BluetoothAdapterService(37326222): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-12 11:36:57.627  2056  2056 D BluetoothAdapterService(37326222): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
07-12 11:36:57.627  2056  2056 D BluetoothAdapterState: isTurningOnRadio()=false
07-12 11:36:57.627  2056  2056 D BluetoothAdapterState: isTurningOffRadio()=false
07-12 11:36:57.627  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-12 11:36:57.627  2056  2056 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-12 11:36:57.627  2056  2056 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-12 11:36:57.627  2056  2056 D BluetoothAdapterService(37326222): onProfileServiceStateChange() - All profile services started.
07-12 11:36:57.627  2056  2056 V OppService: ContentObserver received notification
07-12 11:36:57.628  2056  2150 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,07-12 11:36:57.628  2056  2150 I bluedroid: enable
07-12 11:36:57.628  2056  2150 I bt-btif : BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
07-12 11:36:57.628  2056  2150 E bt-btu  : VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
07-12 11:36:57.628  2056  2056 V OppService: ContentObserver received notification
07-12 11:36:57.629  2056  5818 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-12 11:36:57.633  2056  2150 I bt_hci_bdroid: init
07-12 11:36:57.633  2056  2150 I bt_vendor: init
07-12 11:36:57.633  2056  2150 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 11:36:57.633  2056  5819 V OppService: pendingUpdate is :  true
07-12 11:36:57.633  2056  5819 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-12 11:36:57.634  2056  2150 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-12 11:36:57.635  2056  2150 I bt-btif : libbt-hci init returns 0
07-12 11:36:57.639  2056  5820 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-12 11:36:57.639  2056  5820 I bt-btu  : btu_task pending for preload complete event
,07-12 11:36:57.714  5780  5780 I IndexDatabaseHelper: Using schema version: 115
,07-12 11:36:57.716  5780  5780 I IndexDatabaseHelper: Index is fine
07-12 11:36:57.719  2056  5822 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
07-12 11:36:57.722  2056  5822 D bt_userial_vendor: userial_vendor_open():UART is setup
07-12 11:36:57.722  2056  5822 I bt_userial_vendor: device fd = 70 open
07-12 11:36:57.734  2056  5822 D bt_hwcfg: hw_config_cback opcode:0x0c03
07-12 11:36:57.734  2056  5822 D bt_hwcfg: hw_config_cback state=1
,07-12 11:36:57.760  2056  5822 D bt_hwcfg: hw_config_cback opcode:0x0c14
07-12 11:36:57.760  2056  5822 D bt_hwcfg: hw_config_cback state=4
07-12 11:36:57.760  2056  5822 D bt_hwcfg: Chipset Name: BCM4334B0
07-12 11:36:57.760  2056  5822 D bt_hwcfg: Chipset BCM4334B0
07-12 11:36:57.760  2056  5822 D bt_hwcfg: Target name = [BCM4334B0]
,07-12 11:36:57.760  2056  5822 I bt_hwcfg: Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
07-12 11:36:57.765  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc45
07-12 11:36:57.765  2056  5822 D bt_hwcfg: hw_config_cback state=2
07-12 11:36:57.769  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc18
07-12 11:36:57.769  2056  5822 D bt_hwcfg: hw_config_cback state=3
07-12 11:36:57.769  2056  5822 I bt_hwcfg: bt vendor lib: set UART baud 4000000
07-12 11:36:57.797  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc2e
07-12 11:36:57.797  2056  5822 D bt_hwcfg: hw_config_cback state=5
,07-12 11:36:57.823   269  1048 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-12 11:36:57.823   269  1048 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,07-12 11:36:57.828   841  1906 I art     : Explicit concurrent mark sweep GC freed 40665(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/34MB, paused 2.587ms total 196.968ms
07-12 11:36:57.829  2056  5819 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a7e784e on behalf of 
07-12 11:36:57.831  2056  5818 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ad52d6f on behalf of 
07-12 11:36:57.832  2056  5818 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-12 11:36:57.833  2056  5819 V OppService: pendingUpdate is :  false
07-12 11:36:57.833  2056  5819 E OppService: UpdateThread is Completed
07-12 11:36:57.835  2056  5818 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-12 11:36:57.836  2056  5818 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13765a7c on behalf of 
07-12 11:36:57.837  2056  5818 V BluetoothOppNotification: outbound: succ-0  fail-0
07-12 11:36:57.838  2056  5818 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
07-12 11:36:57.839  2056  5818 V BluetoothOppNotification: outbound notification was removed.
07-12 11:36:57.839  2056  5818 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,07-12 11:36:57.842   841  1030 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-12 11:36:57.844  2056  5818 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10de7f05 on behalf of 
,07-12 11:36:57.844  2056  5818 V BluetoothOppNotification: inbound: succ-0  fail-0
07-12 11:36:57.846  2056  5818 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
07-12 11:36:57.846  2056  5818 V BluetoothOppNotification: inbound notification was removed.
07-12 11:36:57.847  2056  5818 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-12 11:36:57.848   841  1303 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:36:57.848   841  1303 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:36:57.848  2056  5818 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c4dcb5a on behalf of 
07-12 11:36:57.849  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.849  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.850   841  1303 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:36:57.850   841  1303 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:36:57.850   269  1050 E BandwidthController: [LG DATA] No such appUid: 1000
07-12 11:36:57.850   269  1050 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-12 11:36:57.850  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.850  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.851   269  5824 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-12 11:36:57.851   269  5824 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:36:57.851   269  5824 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-12 11:36:57.851  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.851  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.852   841  1028 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-12 11:36:57.853  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.853  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.855  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.855  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.856  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.856  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.857  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.857  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.857  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.858  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.858  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.858  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.859  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.859  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.860  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.860  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.861  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.861  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.862  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.862  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.863  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.863  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.864  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.864  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:57.867   841  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:36:57.867   841  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:36:57.868  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.868  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.868  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.868  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.869  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.869  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.870  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.870  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.871  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.871  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.872  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.872  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.873  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.873  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.874  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.874  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.875  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.875  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.876  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.876  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:57.878  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.878  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.879  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.879  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.880  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.880  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.881  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.881  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.882  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.882  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.883  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.883  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.884  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.884  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.885  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.885  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.886  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.886  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.887  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.887  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:57.889  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.889  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.890  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.890  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.891  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.891  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.892  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.892  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.892  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.893  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.893  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.893  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.894  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.894  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.896  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.896  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.896  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.896  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.897  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.898  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:57.898  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.898  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.899  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.899  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.900  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.900  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.901  2056  2056 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-12 11:36:57.901  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.901  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.901  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.901  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.902  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.902  2056  2056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:57.902  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.902  2056  2056 V BluetoothPbapReceiver: ***********state = 11
07-12 11:36:57.902  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.903  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.903  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.903  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.904  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.904  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.905  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.905  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.906  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.906  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.907  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.907  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.907  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.907  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.908  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.908  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.909  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.909  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.910  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.910  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.911  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.911  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.911  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.911  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.912  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.912  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.913  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.913  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.914  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.914  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.915  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.915  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.915  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.915  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.916  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.916  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.916  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.916  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.917  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.917  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.918  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.918  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.919  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.919  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.919  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.919  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.920  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.920  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.921  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.921  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:57.922  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.922  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.923  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.923  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.924  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.924  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.925  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.925  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.926  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.926  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.926  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.926  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.927  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.927  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.927  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.927  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.928  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-12 11:36:57.928  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.928  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.929  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.929  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.930  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.930  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.932  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.932  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.936  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.936  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.937  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.937  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.938  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.938  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.938  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.939  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.939  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.940  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.940  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.940  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.941  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.941  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.941  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.941  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.942  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.942  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.942  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.942  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.943  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.943  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.944  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.944  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.945  5767  5767 E wpa_supplicant: USIM:  scard_init function
07-12 11:36:57.945  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.945  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.946  5767  5767 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-12 11:36:57.947   269  1048 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
07-12 11:36:57.948  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.948  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.949  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.949  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.949   269  1048 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
07-12 11:36:57.950  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.950  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.951  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.951  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.951   269  1048 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
07-12 11:36:57.951  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.951  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.952  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.952  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.953  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.953  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.954  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.954  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.955  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.955  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.955   841  1028 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:36:57.955   841  1028 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:36:57.956  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.956  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.957  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.957  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.958  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.958  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.959  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.959  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.960  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.960  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.961  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.961  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:57.961  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.962  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.962  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.962  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.963  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.963  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.964  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.964  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.965  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.965  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.966  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.966  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.967  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.967  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.968  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.968  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.968  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.968  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.969  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.969  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.970  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.970  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.971  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.971  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.972  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.972  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.972  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.973  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.973  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.973  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.974  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.974  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.975  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.975  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.976  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.976  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.977  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.977  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.977  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.977  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.978  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.978  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.979  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.979  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.981  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.981  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.982  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.982  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.982  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.982  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.983  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.983  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.984  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.984  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.984  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.984  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.985  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.985  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.986  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.986  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.987  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.987  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.988  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.988  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.989  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.989  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.990  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.990  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.991  5780  5780 D WiFiOffLoadUpdatePriority: remove : truetruefalse
07-12 11:36:57.991  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.991  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.992  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.992  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.993  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.993  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.994  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.994  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.995  5780  5780 D WiFiOffLoadUpdatePriority: remove2
07-12 11:36:57.995  5780  5780 V WiFiOffLoadSharedPrefsUtils: save wifi state
07-12 11:36:57.996  5780  5780 V WiFiOffLoadSharedPrefsUtils: save remove
07-12 11:36:57.996  5780  5780 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
07-12 11:36:57.996  5780  5780 D WiFiOffLoadBroadcast: S: false, R: true
07-12 11:36:57.997  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.997  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.997  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.997  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.998  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.998  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:57.999  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:57.999  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.000  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.000  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.001  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.001  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.002  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.002  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.003  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.003  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.004  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.004  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.004  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.004  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.005  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.005  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.006  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.006  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.006  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.006  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.007  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.007  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.008  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.008  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.008  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.008  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.009  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.009  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.010  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.010  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.011  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.011  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.012  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.012  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.012  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.012  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.013  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.013  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.013  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.013  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.014  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.014  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.015  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.015  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.015  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.015  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.016  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.016  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.016  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.016  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.017  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.017  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.018  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.018  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.018  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.018  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.019  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.019  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.019  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.019  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.020  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.020  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.021  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.021  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.022  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.022  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.022  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.022  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.023  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.023  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.024  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.024  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.025  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.025  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.025  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.025  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.026  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.026  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.027  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.027  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.027  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.027  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.028  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.028  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.029  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.029  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.030  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.030  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.031  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.031  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.033  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.033  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.034  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.034  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.035  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.035  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.036  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.036  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.037  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.037  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.038  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.038  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.039  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.039  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.040  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.040  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.044  5767  5767 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-12 11:36:58.047   841  1406 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5827 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-12 11:36:58.050  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.050  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.051  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.051  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.051  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.051  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.052  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.052  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.053  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.053  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.054  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.054  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.055  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.055  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.056  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.056  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.056  5767  5767 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-12 11:36:58.057  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.057  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.058  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.058  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.059  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.059  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.060  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.060  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.061  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.061  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.062  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.062  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.063  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.063  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.064  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.064  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.065  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.065  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.066  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.066  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.067  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.067  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.068  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.068  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.069  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.069  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.069   841  1307 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
07-12 11:36:58.070  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.070  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.071  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.071  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.072  5780  5780 D BluetoothPermissionRequest: onReceive
07-12 11:36:58.072  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.072  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.073  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.073  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.074  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.074  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.075  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.075  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.076  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.076  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.077  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.077  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.078  5780  5780 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-12 11:36:58.078  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.078  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.079  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.079  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.079   841  1307 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-12 11:36:58.080  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.080  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.081  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.081  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.081   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:58.081   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:58.082  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.082  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.083  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.083  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.084  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.084  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.085  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.085  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.085  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.085  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.086  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.086  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.086  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.087  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.087  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.087  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.088  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.088  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.089  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.089  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.090  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.090  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.091  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.091  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.092  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
07-12 11:36:58.092  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:36:58.092  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:36:58.092  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:36:58.092 DNS addrs= 0.0.0.0, 0.0.0.0, 
,07-12 11:36:58.092  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:36:58.092  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
07-12 11:36:58.092  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
07-12 11:36:58.093  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.093  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.093   841   841 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-12 11:36:58.094  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.094  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.095  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.095  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.096  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:58.096  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.096  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.097  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:58.097  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:58.097  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:58.097  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:58.097  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:58.097  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:58.097  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:58.097  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:58.097  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.097  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.098  5651  5651 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:58.098  5651  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 11:36:58.100   841   841 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
07-12 11:36:58.100  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.100  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.101   841  1311 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-12 11:36:58.101  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.101  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.102  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.102  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.103  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.103  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.104  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.104  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.105  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.105  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.106  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.106  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.108  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.108  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.109  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.109  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.110  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.110  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.111  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.111  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.112  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.112  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.112  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.112  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.113  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.113  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.114  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.114  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.114  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.114  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.115  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.115  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.116  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.116  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.117  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.117  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.118  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.118  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.119  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.119  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.120  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.120  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.121  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.121  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.122  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.122  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.122  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.122  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.123  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.123  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.124  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.124  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.124  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.124  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.125  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.125  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.126  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.126  2056  5822 D bt_hwcfg: hw_config_cback state=6
,07-12 11:36:58.127   841  1030 D BluetoothManagerService: Message: 20
07-12 11:36:58.127   841  1030 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d1f62a:true
07-12 11:36:58.127  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.127  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.128  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.128  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.129  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.129  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.130  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.130  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.131  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.131  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.131  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.131  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.132  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.132  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.133  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.133  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.133   841  1307 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-12 11:36:58.133  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.133  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.134  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.134  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.135  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.135  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.136  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.136  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.137  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.137  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.138  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.138  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.138  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.138  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.139  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.139  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.139  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.139  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.140  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.140  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.141  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.141  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.142  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.142  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.143  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.143  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.143   841  1307 D WifiStateMachine: enableVerboseLogging : level 2
07-12 11:36:58.144  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.144  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.145  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.145  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.146  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.146  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.146  2056  2056 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-12 11:36:58.147  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.147  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.147  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.147  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.148  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.148  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.149  2056  2056 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,07-12 11:36:58.149  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.149  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.151  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.151  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.152  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.153  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.153  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.153  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.155  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.155  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.156  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.156  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.157  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.157  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.157  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.157  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.158  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.158  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.158  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.158  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.159  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.159  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.159  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.159  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.160  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.160  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.161  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.161  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.163  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.164  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.164  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.164  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.164  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.164  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.165  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.165  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.165  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.165  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.166  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.166  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.166  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.166  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.167  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.167  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.167  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.167  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.167  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.167  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.168  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.168  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.168  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.168  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.169  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.169  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.169  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.169  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.169  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.169  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.170  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.170  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.170  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.170  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.170  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.170  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.171  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.171  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.171  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.171  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.171  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.172  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.172  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.172  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.173  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.173  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.176  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.176  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.176  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.176  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.177  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.177  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.177  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.177  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.178  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-12 11:36:58.178  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.178  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc4e
07-12 11:36:58.178  2056  5822 D bt_hwcfg: hw_config_cback state=6
07-12 11:36:58.189   841  1406 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5848 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-12 11:36:58.206  5827  5827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-12 11:36:58.250   841  2080 I ActivityManager: Process com.google.android.gms:car (pid 5058) has died
,07-12 11:36:58.252   841  1307 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 11:36:58.253   841  1307 D WifiNative-HAL: Setting external_sim to 1
07-12 11:36:58.254   841  1307 I WifiNative-HAL: startHal
07-12 11:36:58.254   841  1307 E wifi    : getStaticLongField sWifiHalHandle 0x9b3558ec
07-12 11:36:58.254   841  1307 I WifiHAL : Initializing wifi
07-12 11:36:58.254   841  1307 I WifiHAL : Creating socket
07-12 11:36:58.255  1860  1860 D WfdsService: Supplicant Connection state is changed : true
07-12 11:36:58.256  1860  2124 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-12 11:36:58.256  5506  5506 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:58.256   841  1307 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-12 11:36:58.256  1860  2124 D WfdsService: Set the WFDS Monitor: true
07-12 11:36:58.256   841  1307 D wifi    : Did set static halHandle = 0xb06c2080
07-12 11:36:58.257   841  1307 D wifi    : halHandle = 0xb06c2080, mVM = 0xb487c280, mCls = 0x501c42
07-12 11:36:58.257   841  1307 E wifi    : getStaticLongField sWifiHalHandle 0x9b35589c
07-12 11:36:58.257   841  1307 D wifi    : array field set
07-12 11:36:58.257   841  1307 I WifiNative-HAL: interface[0] = wlan0
07-12 11:36:58.257   841  1307 I WifiNative-HAL: interface[1] = p2p0
07-12 11:36:58.258   841  1307 D wifi    : setting scan oui 0x99da1958
07-12 11:36:58.258   841  1307 D WifiHAL : Sending mac address OUI
07-12 11:36:58.258   841  1307 E WifiHAL : failed to set scanning mac OUI; result = -95
07-12 11:36:58.258   841  1307 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 11:36:58.258   841  1307 I WifiNative-HAL: startHal
07-12 11:36:58.258   841  1307 D wifi    : setting scan oui 0x99da1958
07-12 11:36:58.258   841  1307 D WifiHAL : Sending mac address OUI
07-12 11:36:58.258   841  1307 E WifiHAL : failed to set scanning mac OUI; result = -95
07-12 11:36:58.260   841  5866 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1335091072
07-12 11:36:58.261   841  5866 D wifi    : waitForHalEvents called, vm = 0xb487c280, obj = 0x501c42, env = 0x99d6c080
07-12 11:36:58.261   841  5866 E wifi    : getStaticLongField sWifiHalHandle 0x99137b2c
07-12 11:36:58.262  1860  2124 D WfdsMonitor: WfdsMonitorThread create
,07-12 11:36:58.263  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-12 11:36:58.267  1860  2124 D WfdsMonitor: WFDS Monitor is created and started
07-12 11:36:58.267  1860  2124 D WfdsService: WiFi: Supplicant connection re-established
07-12 11:36:58.270   841   841 D WifiHS20: hidePasspointNotification off =false
07-12 11:36:58.272   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:58.272   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:58.272  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:58.272   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-12 11:36:58.273  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:36:58.273 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-12 11:36:58.274  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,07-12 11:36:58.277  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:36:58.277  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:36:58.277  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:36:58.277  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-12 11:36:58.277  1860  5867 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-12 11:36:58.278  1860  5867 E CtrlSupplicant: Succeed to open control connection
07-12 11:36:58.278  1860  5867 E CtrlSupplicant: Succeed to open monitor connection
07-12 11:36:58.278  2056  5822 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-12 11:36:58.279  2056  5822 D bt_hwcfg: Settlement delay -- 100 ms
07-12 11:36:58.279  2056  5822 I bt_hwcfg: Setting fw settlement delay to 100 
07-12 11:36:58.279  1860  5867 D WfdsMonitor: Supplicant connection established
07-12 11:36:58.280  1860  2124 D WfdsService: Connected to the supplicant for wfds
07-12 11:36:58.280  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:36:58.280  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-12 11:36:58.282   841  1306 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.284   841  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:36:58.284   841  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:36:58.285   269  1055 D CommandListener: Setting iface cfg
07-12 11:36:58.285   269  1055 D CommandListener: Trying to bring up p2p0
07-12 11:36:58.285   841   841 D WifiScanningService: SCAN_AVAILABLE : 3
07-12 11:36:58.285   841   841 D RttService: SCAN_AVAILABLE : 3
07-12 11:36:58.286   841  1326 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.286   841  1326 I WifiNative-HAL: startHal
07-12 11:36:58.286   841  1327 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.287   841  1326 D wifi    : getting scan capabilities on interface[0] = 0x99da1958
07-12 11:36:58.287   841  1326 D WifiHAL : Creating message to get scan capablities; iface = 24
07-12 11:36:58.287   841  1326 D wifi    : failed to get capabilities : -95
07-12 11:36:58.287   841  1326 E WifiScanningService: could not get scan capabilities
,07-12 11:36:58.293  5780  5780 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-12 11:36:58.294  5780  5780 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-12 11:36:58.294  5780  5780 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-12 11:36:58.294  5780  5780 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-12 11:36:58.296  5780  5780 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-12 11:36:58.300   841  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-12 11:36:58.300   841  1306 D LGWifiP2pService: P2pEnablingState
07-12 11:36:58.300   841  1306 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.301   841  1306 D LGWifiP2pService: P2p socket connection successful
07-12 11:36:58.301   841  1306 D LGWifiP2pService: P2pEnabledState
07-12 11:36:58.302   841  1307 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
07-12 11:36:58.303   841  1306 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-12 11:36:58.303   841  1306 D LGWifiP2pService: before postfix = G3s-1
07-12 11:36:58.303   841  1306 D WifiServerServiceExt: postfix byte check : 5
07-12 11:36:58.304   841  1307 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,07-12 11:36:58.304   841  1306 D LGWifiP2pService: after postfix = G3s-1
07-12 11:36:58.306   841  1306 D WifiNative-HAL: p2pGetDeviceAddress
07-12 11:36:58.306   841  1306 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
07-12 11:36:58.307  5767  5767 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-12 11:36:58.308   841  1307 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-12 11:36:58.308  5767  5767 E wpa_supplicant: disconnect_rssi_lvl: -100
07-12 11:36:58.309   841  1307 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
07-12 11:36:58.309  5767  5767 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
07-12 11:36:58.311   841  1307 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
07-12 11:36:58.314   841  1306 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
07-12 11:36:58.314  1860  1860 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-12 11:36:58.321  1860  1860 D WfdsService: Update P2p Interface State: 3
,07-12 11:36:58.326  5848  5848 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-12 11:36:58.329  5780  5780 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-12 11:36:58.330  5780  5780 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-12 11:36:58.330  5780  5780 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-12 11:36:58.330  5780  5780 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-12 11:36:58.330  5780  5780 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-12 11:36:58.330  5780  5780 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-12 11:36:58.331  5780  5780 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-12 11:36:58.333  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:36:58.336  5767  5767 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-12 11:36:58.337  5767  5767 I wpa_supplicant: [LGE_PATCH]scan interval[0] = 2 sec.
07-12 11:36:58.341  1860  5867 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
07-12 11:36:58.341  1860  5867 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
07-12 11:36:58.342  5780  5780 D WiFiOffLoadUpdatePriority: remove : truetruetrue
07-12 11:36:58.359  5848  5848 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
,07-12 11:36:58.365  5767  5767 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-12 11:36:58.368  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-12 11:36:58.369  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:36:58.368 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-12 11:36:58.369  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:58.369   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:58.369   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:58.369   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-12 11:36:58.370  2322  2322 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-12 11:36:58.373  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,07-12 11:36:58.378  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,07-12 11:36:58.378  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:36:58.378  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:36:58.378  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-12 11:36:58.378  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:36:58.378  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-12 11:36:58.383  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc45
07-12 11:36:58.383  2056  5822 D bt_hwcfg: hw_config_cback state=2
07-12 11:36:58.388  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc18
07-12 11:36:58.388  2056  5822 D bt_hwcfg: hw_config_cback state=7
07-12 11:36:58.388  2056  5822 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-12 11:36:58.388  2056  5822 I bt_hwcfg: Setting local bd addr to F8:95:C7:87:85:54
07-12 11:36:58.401  2322  2322 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 11:36:58.411  2056  5822 D bt_hwcfg: hw_config_cback opcode:0xfc01
07-12 11:36:58.411  2056  5822 D bt_hwcfg: hw_config_cback state=8
07-12 11:36:58.411  2056  5822 I bt_hwcfg: vendor lib fwcfg completed
07-12 11:36:58.411  2056  5822 I bt-btif : HC preload_cb 0 [0:SUCCESS 1:FAIL]
07-12 11:36:58.411  2056  5820 I bt-btu  : btu_task received preload complete event
07-12 11:36:58.427   841  1306 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_HCI,2
,07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_L2CAP,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_RFCOMM,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_OBEX,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_AVCT,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_AVDT,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_AVRC,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_AVDT_SCB,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_A2D,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_BNEP,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_BTM,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_GAP,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_PAN,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_SAP,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_SDP,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_GATT,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_SMP,2
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_BTAPP,3
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_BTIF,3
07-12 11:36:58.432  2056  5820 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,0
07-12 11:36:58.480   841  1867 I ActivityManager: Process com.google.android.talk (pid 5506) has died
,07-12 11:36:58.483   841  1306 D LGWifiP2pService: sending p2p connection changed broadcast
07-12 11:36:58.484   841  1306 D LGWifiP2pService: InactiveState
07-12 11:36:58.485   841  1306 D LGWifiP2pService: InactiveState{ when=-146ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.485   841  1306 D LGWifiP2pService: P2pEnabledState{ when=-146ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.485   841  1306 D LGWifiP2pService: DefaultState{ when=-147ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.485   841  1306 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.485   841  1306 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.485   841  1306 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.485   841  1306 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.485   841  1306 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.485   841  1306 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.485   841   841 E WifiServerServiceExt: No p2p device connected
07-12 11:36:58.487  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
07-12 11:36:58.487  1860  1860 D WfdsService: WifiP2pState is changed : true
07-12 11:36:58.487  1860  1860 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-12 11:36:58.489  1860  2124 D WfdsService: Receive the WFDS_ENABLE Method
07-12 11:36:58.489  1860  2124 D WfdsService: Set the WFDS Monitor: true
07-12 11:36:58.489  1860  2124 D WfdsService: Connected to the supplicant for wfds
07-12 11:36:58.489  1860  2124 D WfdsJNI : doCommand: WFDS_SET TRUE
07-12 11:36:58.489  5767  5767 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-12 11:36:58.490  1860  2124 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
07-12 11:36:58.490  5767  5767 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
07-12 11:36:58.491  1860  2124 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
07-12 11:36:58.491  5767  5767 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
07-12 11:36:58.491  1860  2124 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
07-12 11:36:58.491   841   841 D LocSvc_java: onReceive
07-12 11:36:58.492   841   841 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:58.492   841   841 D WifiServerServiceExt: setSupplicantStateSCANNING
07-12 11:36:58.495  1860  2124 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
,07-12 11:36:58.495  1860  2124 D WfdsService: selectPreferredScanChannel [6]
07-12 11:36:58.495  1860  2124 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
07-12 11:36:58.502  1860  1860 D WfdsService: isConnected: false
07-12 11:36:58.502   841  1306 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.502   841  1306 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.502   841  1306 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.502   841  1306 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.502   841  1306 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.502   841  1306 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:58.503  1860  1860 D WfdsService: GroupInfoAvailable: mGroupInfo is null
07-12 11:36:58.503  1860  2124 W WfdsService: DefaultState - msg [9441285] is not handled
07-12 11:36:58.516  1776  1776 D GONS    : GONS isTestMode: false Country: 
,07-12 11:36:58.520  5780  5780 D WiFiOffLoadUpdatePriority: remove1
07-12 11:36:58.520  5780  5780 V WiFiOffLoadSharedPrefsUtils: save remove
07-12 11:36:58.529  5780  5780 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
07-12 11:36:58.529  5780  5780 D WiFiOffLoadBroadcast: S: false, R: false
,07-12 11:36:58.532  5780  5780 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
07-12 11:36:58.532  5780  5780 D WiFiOffLoadUpdatePriority: connected SSID: null
07-12 11:36:58.532  5780  5780 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
07-12 11:36:58.534   841  1908 D WifiServiceImplEx: addOrUpdateNetwork pid=5780, uid=1000, packageName=android.uid.system:1000
07-12 11:36:58.535   841  1908 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
07-12 11:36:58.536   841  1307 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
07-12 11:36:58.580  2056  5820 E bt-btif : bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,07-12 11:36:58.582  2056  5873 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-12 11:36:58.582  2056  2165 E bt-btif : warning : media task started media_task_refcnt 1 
07-12 11:36:58.583  2056  5820 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
07-12 11:36:58.583  2056  5820 W bt-smp  : Plain text(LSB ~ MSB) = 83 70 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-12 11:36:58.583  2056  5820 W bt-smp  : Encrypted text(LSB ~ MSB) = 29 e0 e6 8f 67 e6 ad 40 b4 0c ee 51 17 e6 b4 92 
,07-12 11:36:58.583  2056  5820 W bt-btm  : Stopping oneshot timer
07-12 11:36:58.584  2056  2165 E bt-btif : Calling BTA_HhEnable
07-12 11:36:58.584  2056  2165 E bt-btif : btif_storage_get_adapter_property service_mask:0x1201c8
07-12 11:36:58.584  2056  2165 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-12 11:36:58.585  2056  2165 D BluetoothAdapterProperties: Address is:F8:95:C7:87:85:54
07-12 11:36:58.585  2056  5873 D BT_PROF_AUDIO: created moving average (N=100)
07-12 11:36:58.585  2056  5873 D BT_PROF_AUDIO: reset rate average
07-12 11:36:58.585  2056  5873 W bt-btif : overflow 0, enter 0, exit 0
07-12 11:36:58.586  2056  2165 D BluetoothAdapterProperties: Name is: G3s-1
07-12 11:36:58.586   841   841 D BluetoothManagerService: Bluetooth Adapter name changed to G3s-1
07-12 11:36:58.586   841   841 D BluetoothManagerService: Stored Bluetooth name: G3s-1
07-12 11:36:58.587  2056  2165 D BluetoothAdapterProperties: Scan Mode:20
07-12 11:36:58.587  2056  2165 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:36:58.589  2056  2165 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
07-12 11:36:58.589  2056  2165 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
07-12 11:36:58.589  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 11:36:58.589  2056  2165 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-12 11:36:58.589  2056  2165 I bt-btif : BTA_JvEnable
07-12 11:36:58.589  2056  2165 E bt-btif : btsock_vendor_hci_init: !vhci_init
07-12 11:36:58.589  2056  2165 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
07-12 11:36:58.590  2056  2165 D bt-btif : init_hci_slots(L136): in
07-12 11:36:58.590  2056  2165 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
07-12 11:36:58.591  2056  2165 D IOP_DB_BT: db_open: db_open : handle 2690922460l, read 11046 bytes onto local cache
07-12 11:36:58.591  2056  2165 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
07-12 11:36:58.591  2056  2165 D IOP_DB_BT: db_query: result 1
07-12 11:36:58.591  2056  2165 I         : iop_db_open: iop_db_open status 0
07-12 11:36:58.591  2056  2165 E bt-btif : btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
07-12 11:36:58.591  2056  2165 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
,07-12 11:36:58.592  2056  2165 D bte_conf: Device ID record 1 : primary
07-12 11:36:58.592  2056  2165 D bte_conf:   vendorId            = 00c4
07-12 11:36:58.592  2056  2165 D bte_conf:   vendorIdSource      = 0001
07-12 11:36:58.592  2056  2165 D bte_conf:   product             = 13a1
07-12 11:36:58.592  2056  2165 D bte_conf:   version             = 1000
07-12 11:36:58.592  2056  2165 D bte_conf:   clientExecutableURL = 
07-12 11:36:58.592  2056  2165 D bte_conf:   serviceDescription  = 
07-12 11:36:58.592  2056  2165 D bte_conf:   documentationURL    = 
07-12 11:36:58.592  2056  2165 D bte_conf: bte_load_did_conf no section named DID2.
07-12 11:36:58.592  2056  5820 I bt-btif : bta_pan_co_init
07-12 11:36:58.593  2056  2165 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
07-12 11:36:58.594  2056  2165 E bt-btif : btif_hf_upstreams_evt: wrong handle = 12346 
07-12 11:36:58.594  2056  2165 I bt-btif : HAL bt_op_callbacks->opc_state_cb
07-12 11:36:58.594  2056  2165 D BluetoothOPPServiceJni: opc_state_cb(L140):  opc_state_cb state:0
07-12 11:36:58.594  2056  2165 D OppService: onOpcStateChange()
07-12 11:36:58.594  2056  2165 I bt-btif : HAL bt_op_callbacks->ops_state_cb
07-12 11:36:58.594  2056  2165 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:0
07-12 11:36:58.594  2056  2165 D OppService: onOpsStateChange() :0
07-12 11:36:58.594  2056  2165 I bt-btif : HAL bt_fts_callbacks->operation_cmpl_cb
07-12 11:36:58.594  2056  2165 D BluetoothFTPServiceJni: operation_cmpl_callback(L192):  oper:3 status:0
07-12 11:36:58.594  2056  2165 I BluetoothFTPService: onFtpServerEnabled: /storage
07-12 11:36:58.594  2056  2165 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-12 11:36:58.595  2056  2150 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-12 11:36:58.595  2056  2150 D BluetoothAdapterProperties: ScanMode =  20
07-12 11:36:58.595  2056  2150 D BluetoothAdapterProperties: State =  11
07-12 11:36:58.595  2056  2150 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-12 11:36:58.595  2056  2150 D BluetoothAdapterProperties: Setting state to 12
07-12 11:36:58.595  2056  2165 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-12 11:36:58.595  2056  2150 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-12 11:36:58.595  2056  2150 D BluetoothAdapterService(37326222): updateAdapterState() - Broadcasting state to 1 receivers.
07-12 11:36:58.596   841  1030 D BluetoothManagerService: Message: 60
07-12 11:36:58.596   841  1030 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-12 11:36:58.596   841  1030 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 6 receivers.
07-12 11:36:58.596  2056  2056 D OppService: Recieved MESSAGE_OPC_ENABLE
07-12 11:36:58.596   841  1030 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:58.596   841  1030 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 11:36:58.596  2056  2165 D BluetoothAdapterProperties: Scan Mode:21
07-12 11:36:58.597  2056  2165 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-12 11:36:58.597  2056  2165 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:36:58.597  2056  2056 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-12 11:36:58.597  2056  2150 I BluetoothAdapterState: Entering On State
07-12 11:36:58.597  2056  2150 I BluetoothAdapterState: Entering On State from state = 11
07-12 11:36:58.598  2056  2150 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.598  2056  2056 D OppService: Recieved MESSAGE_OPS_ENABLE
07-12 11:36:58.598  2056  2150 D BluetoothAdapterService(37326222): isQuetModeEnabled() - Enabled = false
07-12 11:36:58.598  2056  2150 D BluetoothAdapterService(37326222): autoConnect() - Initiate auto connection on BT on...
07-12 11:36:58.598  2056  2150 D, BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-12 11:36:58.599  2056  2150 D LGBluetoothServiceAdapter: [BTUI] OnState
07-12 11:36:58.599  2056  2150 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3s-1
07-12 11:36:58.599  1776  2865 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:58.599  2056  2150 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3s-1
07-12 11:36:58.599  5780  5780 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
07-12 11:36:58.599  5780  5780 D WiFiOffLoadUpdatePriority: configuration updated: 0
07-12 11:36:58.600  1776  2563 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:58.600   841  1307 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
07-12 11:36:58.600  1776  1808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:58.600  2056  5778 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 11:36:58.600  2056  2150 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.600  2056  2150 D BluetoothAdapterService(37326222): isQuetModeEnabled() - Enabled = false
07-12 11:36:58.600  2056  2150 D BluetoothAdapterService(37326222): autoConnect() - Initiate auto connection on BT on...
07-12 11:36:58.600  2056  2150 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-12 11:36:58.601  2056  2071 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.602   841   841 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-12 11:36:58.602  5651  5651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-12 11:36:58.603   841  1030 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-12 11:36:58.603   841  1030 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,07-12 11:36:58.607  2056  2056 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.608  2056  2072 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.608  2056  2071 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.609  1860  1860 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:58.609  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:58.609  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:58.609  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 11:36:58.609  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:58.609  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:58.609  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:58.609  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:58.609  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:58.610  2056  5778 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.610   841  1030 D BluetoothManagerService: Message: 40
,07-12 11:36:58.611   841  1030 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-12 11:36:58.612  2056  5822 D bt_h4   : vendor lib postload completed
07-12 11:36:58.614  2056  2071 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.615  2056  2056 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:58.615  2056  2056 D BluetoothMapService: STATE_ON
07-12 11:36:58.619  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
07-12 11:36:58.619  1368  1368 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
07-12 11:36:58.621  5651  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:36:58.626  5780  5780 D WiFiOffLoadUpdatePriority: configuration saved: true
07-12 11:36:58.629  1860  2054 D LGBluetoothAPIService: Message: 1
07-12 11:36:58.629  1860  2054 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-12 11:36:58.631  5827  5827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-12 11:36:58.638  5780  5780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-12 11:36:58.650  2056  2056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2398d8e
,07-12 11:36:58.652  2056  2056 V BluetoothPbapService: Pbap Service onCreate
07-12 11:36:58.654  2056  2056 V BluetoothPbapService: Starting PBAP service
07-12 11:36:58.658  2056  2056 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.659  2056  2056 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-12 11:36:58.659  2056  2056 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:58.659  2056  2056 V BluetoothPbapService: state: 12
07-12 11:36:58.660  2056  2056 V BluetoothMapService: Handler(): got msg=1
07-12 11:36:58.661  2056  2056 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-12 11:36:58.661  2056  2056 V BluetoothOppNotification: new notify threadi!
07-12 11:36:58.661  2056  2056 V BluetoothOppNotification: send delay message
07-12 11:36:58.661  2056  2056 V BluetoothPbapService: Handler(): got msg=1
07-12 11:36:58.663  2056  5881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,07-12 11:36:58.666  2056  2056 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-12 11:36:58.666  2056  5881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f0ca268 on behalf of 
07-12 11:36:58.668  2056  5882 V BluetoothPbapService: Pbap Service initSocket
07-12 11:36:58.670  2056  5880 D BluetoothMapMasInstance: MAS initSocket()
07-12 11:36:58.671  2056  5880 D BluetoothMapMasInstance:   masId = 00
07-12 11:36:58.671  2056  5880 D BluetoothMapMasInstance:   msgTypes = 0e
07-12 11:36:58.671  2056  5880 D BluetoothMapMasInstance:   masName = SMS/MMS
07-12 11:36:58.671  2056  5880 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-12 11:36:58.672  2056  5881 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-12 11:36:58.673  2056  5881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-12 11:36:58.675  2056  5881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@364d0681 on behalf of 
,07-12 11:36:58.676  2056  5881 V BluetoothOppNotification: outbound: succ-0  fail-0
07-12 11:36:58.677  2056  5881 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
07-12 11:36:58.678  2056  5881 V BluetoothOppNotification: outbound notification was removed.
07-12 11:36:58.678  2056  5881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-12 11:36:58.679  2056  5881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f8d4326 on behalf of 
07-12 11:36:58.679  2056  5881 V BluetoothOppNotification: inbound: succ-0  fail-0
07-12 11:36:58.681  2056  5881 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
07-12 11:36:58.681  2056  5881 V BluetoothOppNotification: inbound notification was removed.
07-12 11:36:58.682  2056  5881 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-12 11:36:58.683  2056  5881 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@eff5b67 on behalf of 
07-12 11:36:58.691   841  2012 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5883 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
07-12 11:36:58.692   841  2125 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 11:36:58.692   841  1293 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-12 11:36:58.694  2056  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:36:58.694  2056  5880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:36:58.695  1860  2054 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-12 11:36:58.701  2056  5778 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.703  2056  5880 I bt-btif : BTA_JvCreateRecordByUser
07-12 11:36:58.703  2056  5820 I bt-btif : BTA_JvRfcommStartServer
07-12 11:36:58.703  2056  5880 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=0
07-12 11:36:58.703  2056  5880 V BluetoothMapMasInstance: Succeed to create listening socket 
07-12 11:36:58.704  2056  2056 D LGBluetoothAPIServer: [BTUI] onCreate()
07-12 11:36:58.704  2056  2056 D LGBluetoothAPIServer: [BTUI] onBind()
07-12 11:36:58.705  5780  5780 D LocalBluetoothProfileManager: Adding local A2DP profile
07-12 11:36:58.706  1860  1860 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,07-12 11:36:58.707  1860  2054 D LGBluetoothAPIService: Message: 100
07-12 11:36:58.707  2056  5882 I bt-btif : BTA_JvCreateRecordByUser
07-12 11:36:58.707  1860  2054 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-12 11:36:58.707  2056  5820 I bt-btif : BTA_JvRfcommStartServer
07-12 11:36:58.707  2056  5882 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=85 mFd=83
07-12 11:36:58.707  2056  5880 D BluetoothMapMasInstance: Accepting socket connection...
07-12 11:36:58.707  2056  5882 V BluetoothPbapService: Succeed to create listening socket 
07-12 11:36:58.707  2056  5882 V BluetoothPbapService: Accepting socket connection...
07-12 11:36:58.708   841  1030 D BluetoothManagerService: Message: 30
07-12 11:36:58.711  2056  2056 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-12 11:36:58.711  5780  5780 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-12 11:36:58.711  2056  2056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:58.711  2056  2056 V BluetoothPbapReceiver: ***********state = 12
07-12 11:36:58.715   841  1030 D BluetoothManagerService: Message: 30
07-12 11:36:58.720   841  1030 D BluetoothManagerService: Message: 30
,07-12 11:36:58.726   841  1030 D BluetoothManagerService: Message: 30
07-12 11:36:58.728  5780  5780 D LocalBluetoothProfileManager: Adding local MAP profile
07-12 11:36:58.731  5780  5780 D BluetoothMap: Create BluetoothMap proxy object
07-12 11:36:58.732   841  1030 D BluetoothManagerService: Message: 30
07-12 11:36:58.738   841  1030 D BluetoothManagerService: Message: 30
,07-12 11:36:58.743  5780  5780 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-12 11:36:58.743  2056  2056 V BluetoothPbapService: Pbap Service onBind
,07-12 11:36:58.752  5780  5780 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
07-12 11:36:58.757  5780  5780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-12 11:36:58.765  5780  5780 D DockEventReceiver: finishStartingService: stopping service
07-12 11:36:58.766  5780  5780 D BluetoothA2dp: Proxy object connected
07-12 11:36:58.767  5780  5780 D A2dpProfile: Bluetooth service connected
07-12 11:36:58.769  2056  5778 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
,07-12 11:36:58.773  5780  5780 D BluetoothHeadset: Proxy object connected
,07-12 11:36:58.774  5780  5780 D HeadsetProfile: Bluetooth service connected
07-12 11:36:58.775  2056  2072 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.776  5780  5780 D BluetoothInputDevice: Proxy object connected
07-12 11:36:58.777  5780  5780 D HidProfile: Bluetooth service connected
07-12 11:36:58.777  2056  2071 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.778  5780  5780 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 11:36:58.779  5780  5780 D PanProfile: Bluetooth service connected
07-12 11:36:58.783  2056  5778 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
,07-12 11:36:58.785  5780  5780 D BluetoothMap: Proxy object connected
07-12 11:36:58.786  5780  5780 D MapProfile: Bluetooth service connected
07-12 11:36:58.786  5780  5780 D BluetoothMap: getConnectedDevices()
07-12 11:36:58.786  2056  2072 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:58.787  2056  5778 V BluetoothMapService: getConnectedDevices()
07-12 11:36:58.788  5780  5780 D BluetoothPbap: Proxy object connected
07-12 11:36:58.788  5780  5780 D PbapServerProfile: Bluetooth service connected
07-12 11:36:58.790  5780  5780 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-12 11:36:58.793  5780  5780 D BluetoothPermissionRequest: onReceive
07-12 11:36:58.795  5780  5780 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-12 11:36:58.796  5780  5780 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,07-12 11:36:58.801  2056  2056 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-12 11:36:58.807  2056  2056 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-12 11:36:58.812  2056  2056 V BluetoothSapReceiver: [BTUI] checkServiceStart
,07-12 11:36:58.814  2056  2056 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,07-12 11:36:58.820  2322  2322 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-12 11:36:58.827  2322  5908 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-12 11:36:58.830  2322  2322 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-12 11:36:58.842  5883  5883 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,07-12 11:36:58.843  5883  5883 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-12 11:36:58.849  5883  5883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-12 11:36:58.852  5883  5883 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-12 11:36:58.856  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:58.863  5883  5910 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-12 11:36:58.865  5883  5910 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-12 11:36:58.865  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:58.874  5827  5827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-12 11:36:58.874  5883  5909 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-12 11:36:58.877  5827  5827 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-12 11:36:58.877  5827  5827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-12 11:36:58.884  5331  5417 D dur     : Opening database auth.proximity.permit_store...
07-12 11:36:58.889  2322  5908 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-12 11:36:58.907   293   357 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-12 11:36:58.922   841  1934 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5914 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-12 11:36:58.954   301   301 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 31.348ms
,07-12 11:36:58.977   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 21.239ms
,07-12 11:36:59.001   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 23.689ms
,07-12 11:36:59.052  5914  5914 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-12 11:36:59.100   269  1048 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
07-12 11:36:59.101   841  1028 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-12 11:36:59.101   841  1028 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:36:59.129   841  1030 D BluetoothManagerService: Message: 20
07-12 11:36:59.129   841  1030 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15d0de1:true
,07-12 11:36:59.136  2056  5778 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:59.138  2056  2072 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:36:59.176  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:59.187  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:59.200  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-12 11:36:59.204  5780  5780 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-12 11:36:59.227  5483  5483 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-12 11:36:59.228  5483  5483 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-12 11:36:59.241  5483  5483 V [BNRBootReceiver]: Boot Receiver Return
,07-12 11:36:59.332   841  2012 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5939 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:59.347  5914  5914 V LGMDMManager: Create singleton instance
,07-12 11:36:59.464  5914  5914 I AudioManager: getMode name:com.lge.qremote
,07-12 11:36:59.470  5939  5939 D UEI.SmartControl: Quickset Services start...
07-12 11:36:59.472   269  1048 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-12 11:36:59.473  5767  5767 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
07-12 11:36:59.475  5939  5939 I UEI.SmartControl: Manufacture = LGE
07-12 11:36:59.477  5939  5939 D UEI.SmartControl: File observer start...
,07-12 11:36:59.479  5939  5939 E UEI.SmartControl: IR Port is disabled: false
07-12 11:36:59.479  5939  5939 D UEI.SmartControl: Starting file observer...
07-12 11:36:59.479  5939  5939 D UEI.SmartControl: Extracting JNI libs...
07-12 11:36:59.480  5939  5939 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-12 11:36:59.507   841   841 D LocSvc_java: onReceive
,07-12 11:36:59.508  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-12 11:36:59.511  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-12 11:36:59.511  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:36:59.511 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-12 11:36:59.511  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-12 11:36:59.512  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:59.512   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:59.512   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 11:36:59.512   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-12 11:36:59.512  5780  5780 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-12 11:36:59.514  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-12 11:36:59.515  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:36:59.515  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:36:59.515  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:36:59.515  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-12 11:36:59.516   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:59.516  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:36:59.516  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
,07-12 11:36:59.516   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:59.516   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-12 11:36:59.516   841   841 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:59.516  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:59.516   841   841 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-12 11:36:59.517  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:36:59.517 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-12 11:36:59.519  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-12 11:36:59.520  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-12 11:36:59.522  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:36:59.522  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:36:59.522  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:36:59.522  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
,07-12 11:36:59.522  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:36:59.522  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-12 11:36:59.526  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:59.540  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:59.545  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:59.557   269  1048 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-12 11:36:59.557   269  1048 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-12 11:36:59.557   269  1048 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,07-12 11:36:59.560  5767  5767 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-12 11:36:59.561   841   841 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:59.561   841   841 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-12 11:36:59.566  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:59.567  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-12 11:36:59.568   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:59.568   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:59.568   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-12 11:36:59.568  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:36:59.568 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-12 11:36:59.569  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-12 11:36:59.570  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:36:59.571  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:36:59.571  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:36:59.571  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-12 11:36:59.571  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:36:59.571  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
,07-12 11:36:59.576  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-12 11:36:59.576  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:59.576  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:36:59.576 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-12 11:36:59.577  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-12 11:36:59.579  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:36:59.579  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:36:59.579  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:36:59.579   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:59.579  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-12 11:36:59.579   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:59.579   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-12 11:36:59.579  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:36:59.579  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-12 11:36:59.579   841   841 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:59.579   841   841 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-12 11:36:59.580  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-12 11:36:59.585  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-12 11:36:59.591  5767  5767 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-12 11:36:59.591  5767  5767 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-12 11:36:59.592   269  1048 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-12 11:36:59.593   841   841 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:59.593   841   841 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-12 11:36:59.610  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:59.610   841  1307 I WifiServiceExtension: setVHTCapabilityType  : false
07-12 11:36:59.622  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-12 11:36:59.635   841  1307 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-12 11:36:59.635   841  1307 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,07-12 11:36:59.637   841  1307 I WifiServiceExtension: setSecurityType  : 2
07-12 11:36:59.648  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-12 11:36:59.648   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:59.650  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:36:59.649 DNS addrs= 0.0.0.0, 0.0.0.0, 
,07-12 11:36:59.650  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-12 11:36:59.650   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:59.650   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-12 11:36:59.652  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:59.655  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-12 11:36:59.655  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-12 11:36:59.655   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:59.655   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:36:59.655   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-12 11:36:59.656  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:36:59.656 DNS addrs= 0.0.0.0, 0.0.0.0, 
,07-12 11:36:59.656  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-12 11:36:59.658  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:36:59.658  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:36:59.658  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:36:59.658  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-12 11:36:59.659  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:36:59.659  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-12 11:36:59.659  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:36:59.662  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:36:59.662  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:36:59.662  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:36:59.662  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-12 11:36:59.662  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:36:59.662  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
,07-12 11:36:59.670  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:59.682  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:36:59.689   841  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-12 11:36:59.690   841  1313 D ConnectivityService: Got NetworkAgent Messenger
07-12 11:36:59.691   841  5963 D WifiExtManager: WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@22f8224
07-12 11:36:59.691   841  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-12 11:36:59.692   841  1313 D ConnectivityService: NetworkAgent connected
07-12 11:36:59.694  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:36:59.697  1860  1896 D WifiServiceExtension: isInternetCheckAvailable return false
07-12 11:36:59.698   841  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 11:36:59.709   841  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:36:59.719   269  1048 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
07-12 11:36:59.720   841  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:36:59.720   841  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:36:59.720   841  1028 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:36:59.720   841  1028 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:36:59.722   269  1055 D CommandListener: Setting iface cfg
,07-12 11:36:59.728  5939  5939 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-12 11:36:59.729  5939  5939 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-12 11:36:59.729  5939  5939 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-12 11:36:59.734   841  1307 E WifiStateMachine: Start Dhcp Watchdog 1
07-12 11:36:59.737   841  5964 D DhcpStateMachine: StoppedState
07-12 11:36:59.737   841  5964 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:59.737   841  5964 D DhcpStateMachine: WaitBeforeStartState
07-12 11:36:59.745  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
07-12 11:36:59.746  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-54 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:36:59.746 DNS addrs= 0.0.0.0, 0.0.0.0, 
,07-12 11:36:59.749  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:36:59.749  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:36:59.749  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:36:59.754   841  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-12 11:36:59.757   841   841 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:59.757   841   841 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-12 11:36:59.760   841   841 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-12 11:36:59.760   841   841 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-12 11:36:59.793  5939  5939 I UEI.SmartControl: --- Selecting new region: 2
07-12 11:36:59.793  5939  5939 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,07-12 11:36:59.797  5939  5939 D UEI.SmartControl: Platform has CIR...
07-12 11:36:59.798  5939  5939 D UEI.SmartControl: NO CIR support, need to check package...
07-12 11:36:59.799  5939  5939 I UEI.SmartControl: Model: LG-D722 uses JNI
07-12 11:36:59.803  5939  5939 D UEI.SmartControl: QS Service created
07-12 11:36:59.826  5939  5939 E UEI.SmartControl: QS start get config
,07-12 11:36:59.843   841  1306 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2789bc54 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:59.843   841  1307 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-12 11:36:59.844   841  1306 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2789bc54 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:59.844   841  1307 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,07-12 11:36:59.844   841  5964 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:59.844   841  5964 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-12 11:36:59.846   841  1307 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-12 11:36:59.846   841  1307 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
07-12 11:36:59.880  5939  5939 D UEI.SmartControl: Loading JNI Libs...
07-12 11:36:59.882  5939  5939 D UEI.SmartControl:  configuring local db...
,07-12 11:37:00.001   841  1283 D PowerManagerServiceEx: acquireWakeLockInternal: lock=38356974, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=841
,07-12 11:37:00.007  2827  2827 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 11:37:0
07-12 11:37:00.008  2827  2827 D WeatherService: 2 : TimeTick Intent And Screen On
07-12 11:37:00.008  2827  2827 D WeatherService: 2 : SDK version : 21
07-12 11:37:00.010   841  1867 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
07-12 11:37:00.010  2827  2827 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
07-12 11:37:00.011  2827  2827 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
07-12 11:37:00.011  2827  2827 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
07-12 11:37:00.011  2827  2827 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
07-12 11:37:00.012  2827  2827 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-12 11:37:00.012  2827  2827 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
07-12 11:37:00.012  2827  2827 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
07-12 11:37:00.013  2827  2827 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
07-12 11:37:00.013  2827  2827 D WeatherTheme: 2 : Fixed theme : optimus
07-12 11:37:00.019  2827  2827 D WeatherReflect: 2 : Map key string is -2
,07-12 11:37:00.023  2827  2827 D lim     : 2 : time = 11:37
07-12 11:37:00.024  2827  2827 I WeatherReflect: Model Name : LG-D722
07-12 11:37:00.024  2827  2827 D WeatherTheme: 2 : Different view - status_min_formatted : 36 != 37
07-12 11:37:00.024  2827  2827 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
07-12 11:37:00.026  2827  2827 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
07-12 11:37:00.026  2827  2827 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-12 11:37:00.026  2827  2827 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-12 11:37:00.026  2827  2827 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-12 11:37:00.026  2827  2827 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
07-12 11:37:00.046   841  5964 D DhcpStateMachine: DHCPV4 request on wlan0
07-12 11:37:00.047   841  5964 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-12 11:37:00.047   841  5964 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,07-12 11:37:00.056  2827  2827 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
07-12 11:37:00.056  2827  2827 D Weather4x2_optimus: widgetType = 1, orientation = 1
07-12 11:37:00.056  2827  2827 D Weather4x2_optimus: forecast size is 0
07-12 11:37:00.058  2827  2827 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-12 11:37:00.058  2827  2827 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-12 11:37:00.058  2827  2827 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-12 11:37:00.058  2827  2827 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-12 11:37:00.058  2827  2827 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-12 11:37:00.059  2827  2827 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-12 11:37:00.059  2827  2827 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-12 11:37:00.059  2827  2827 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-12 11:37:00.059  2827  2827 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,07-12 11:37:00.059  2827  2827 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
07-12 11:37:00.059  2827  2827 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
07-12 11:37:00.059  2827  2827 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-12 11:37:00.059  2827  2827 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-12 11:37:00.059  2827  2827 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-12 11:37:00.059  2827  2827 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
07-12 11:37:00.062  2827  2827 D Theme_WeatherAncestor_optimus: url is : null
07-12 11:37:00.063  5965  5965 I dhcpcd  : version 5.5.6 starting
07-12 11:37:00.064  2827  2827 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-12 11:37:00.064  2827  2827 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-12 11:37:00.064  2827  2827 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-12 11:37:00.065  5965  5965 E dhcpcd  : get_duid: Read-only file system
07-12 11:37:00.067  2827  2827 D WeatherAncestor: 2 : update view, appWidgetId: 2
07-12 11:37:00.070  2827  2827 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 11:37:0
07-12 11:37:00.081   841   841 D PowerManagerServiceEx: releaseWakeLockInternal: lock=38356974 [*alarm*], flags=0x0
,07-12 11:37:00.090  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-12 11:37:00.090  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-12 11:37:00.091  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
07-12 11:37:00.092  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-12 11:37:00.092  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:37:00.094  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-12 11:37:00.095  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:37:00.143  5965  5965 I dhcpcd  : wlan0: rebinding lease of 192.168.1.105
07-12 11:37:00.144  5939  5939 D UEI.SmartControl:  ---- Has DB8: true
,07-12 11:37:00.152  5939  5939 D UEI.SmartControl: QS start statue = true Error code = 0
07-12 11:37:00.152  5939  5939 D UEI.SmartControl: QS version = v2.7.11.1_RC1
07-12 11:37:00.153  5939  5939 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
07-12 11:37:00.158  5939  5939 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,07-12 11:37:00.174  5939  5939 W irrc_jni: IRRCPlayer_nativeInit ++ 
07-12 11:37:00.174  5939  5939 D irrcClient: IrrcClient ++ 
07-12 11:37:00.174  5939  5939 D irrcClient: getIrrcService ++ 
,07-12 11:37:00.175  5939  5939 D irrcClient: getIrrcService -- 
07-12 11:37:00.175  5939  5939 D irrcClient: IrrcClient -- 
07-12 11:37:00.175  5939  5939 W irrc_jni: IRRCPlayer_nativeInit -- 
07-12 11:37:00.181  5939  5939 D UEI.SmartControl: Services init done
07-12 11:37:00.183  5939  5973 I UEI.SmartControl: Device manager: loading config....
07-12 11:37:00.185  5939  5939 D UEI.SmartControl: QS Service init finished
,07-12 11:37:00.187  5939  5939 D UEI.SmartControl: QS Service version name: 0.1.73
07-12 11:37:00.188  5939  5939 D UEI.SmartControl: QS Service version code: 1073
07-12 11:37:00.189  5939  5939 D UEI.SmartControl: Service requested: Control
07-12 11:37:00.190  5939  5973 D UEI.SmartControl: Config is loaded...
07-12 11:37:00.222  5939  5972 D UEI.SmartControl:  ----- QS SDK is ready!!!
,07-12 11:37:00.225  5939  5972 I UEI.SmartControl: Notify AllClients services are ready: 0
07-12 11:37:00.226  5939  5939 D UEI.SmartControl: Request IControl service: devices are loaded...
07-12 11:37:00.229  5939  5939 D UEI.SmartControl: Internal service binding...
07-12 11:37:00.230  5939  5954 D UEI.SmartControl: -----IControl: 11
07-12 11:37:00.232   274  1290 V AudioFlinger: thread 0xb5651000 type 0 TID 1290 going to sleep
07-12 11:37:00.233  5939  5954 D UEI.SmartControl: Caller: com.lge.qremote
07-12 11:37:00.235  5939  5954 D UEI.SmartControl: ------------ IControl registerCallback...
07-12 11:37:00.236  5939  5954 I UEI.SmartControl: Registering callback...
07-12 11:37:00.236   274  1294 V AudioFlinger: thread 0xb5735000 type 0 TID 1294 going to sleep
07-12 11:37:00.237  1946  1946 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
07-12 11:37:00.238  5939  5955 D UEI.SmartControl: -----IControl: 19
,07-12 11:37:00.239  5939  5955 D UEI.SmartControl: Caller: com.lge.qremote
,07-12 11:37:00.239   274  1291 V AudioFlinger: thread 0xb56eb000 type 0 TID 1291 going to sleep
07-12 11:37:00.240  5939  5955 I UEI.SmartControl: Registering Services Ready callback...
07-12 11:37:00.241  5965  5965 I dhcpcd  : wlan0: acknowledged 192.168.1.105 from 192.168.1.1
07-12 11:37:00.242  5939  5955 I UEI.SmartControl: Notify client services are ready...
07-12 11:37:00.245  5939  5954 D UEI.SmartControl: -----IControl: 8
07-12 11:37:00.246  5939  5954 D UEI.SmartControl: Caller: com.lge.qremote
07-12 11:37:00.252  5914  5914 I AudioManager: getMode name:com.lge.qremote
,07-12 11:37:00.263   841  1934 I ActivityManager: Killing 5453:com.google.android.apps.plus/u0a86 (adj 15): empty #11
07-12 11:37:00.280  5965  5965 I dhcpcd  : wlan0: leased 192.168.1.105 for 172800 seconds
,07-12 11:37:00.281   269  1048 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
07-12 11:37:00.284   841  1028 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.284   841  1028 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.287   841  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-12 11:37:00.358  1946  1946 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,07-12 11:37:00.390   841  1934 I ActivityManager: Killing 5305:com.lge.eula/1000 (adj 15): empty #12
,07-12 11:37:00.480   841  2125 W libprocessgroup: failed to open /acct/uid_10086/pid_5453/cgroup.procs: No such file or directory
,07-12 11:37:00.484   841  1634 W libprocessgroup: failed to open /acct/uid_1000/pid_5305/cgroup.procs: No such file or directory
07-12 11:37:00.484  5914  5914 I AudioManager: getMode name:com.lge.qremote
07-12 11:37:00.510  5914  5914 I AudioManager: getMode name:com.lge.qremote
,07-12 11:37:00.629   841  1755 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.629   841  1755 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-12 11:37:00.629   841  1755 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.629   841  1755 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:00.629   269  1050 E BandwidthController: [LG DATA] No such appUid: 1000
07-12 11:37:00.630   269  1050 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-12 11:37:00.630   269  6000 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-12 11:37:00.631   269  6000 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:00.631   269  6000 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=0
07-12 11:37:00.633   269  6000 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:00.634   269  6000 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:00.636   841  1028 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-12 11:37:00.649   841  5964 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.649   841  5964 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.650   841  5964 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.650   841  5964 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.650   841  5964 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.650   841  5964 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.650   841  5964 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.650   841  5964 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.650   841  5964 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-12 11:37:00.651   841  5964 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
07-12 11:37:00.652   841  5964 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-12 11:37:00.652   841  5964 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.652   841  5964 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.652   841  5964 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.105
07-12 11:37:00.652   841  5964 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-12 11:37:00.652   841  5964 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-12 11:37:00.652   841  5964 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
07-12 11:37:00.654   841  1306 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:00.654   841  1306 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:00.654   841  5964 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-12 11:37:00.654   841  5964 D DhcpStateMachine: RunningState
07-12 11:37:00.659   841  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-12 11:37:00.660   841  1307 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-12 11:37:00.660   841  1313 D ConnectivityService: ignoring duplicate network state non-change
07-12 11:37:00.662  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,07-12 11:37:00.663  1860  1893 D WifiServiceExtension: isInternetCheckAvailable return false
07-12 11:37:00.666   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:00.666   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:00.667   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-12 11:37:00.670  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:37:00.673   841  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-12 11:37:00.675  1860  1896 D WifiServiceExtension: isInternetCheckAvailable return false
07-12 11:37:00.677  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-12 11:37:00.677  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:37:00.677  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:00.677  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:37:00.677  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-12 11:37:00.678  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:37:00.678  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-12 11:37:00.678   841  1313 D ConnectivityService: Adding iface wlan0 to network 100
07-12 11:37:00.679  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-12 11:37:00.679   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:00.679   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:00.680   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-12 11:37:00.683  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-12 11:37:00.684  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:00.684  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-12 11:37:00.684  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-12 11:37:00.685   841   841 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-12 11:37:00.685  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:37:00.685  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
,07-12 11:37:00.688   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:00.689   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:00.689   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-12 11:37:00.692   841   841 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-12 11:37:00.699  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,07-12 11:37:00.700  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-54 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:37:00.696 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-12 11:37:00.700  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.105 ipV6Addr=
07-12 11:37:00.700  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-12 11:37:00.703  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-54 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:37:00.703 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-12 11:37:00.703  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.105 ipV6Addr=
07-12 11:37:00.703  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-12 11:37:00.705  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:37:00.705 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-12 11:37:00.706  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.105 ipV6Addr=
07-12 11:37:00.706  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-12 11:37:00.706   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:00.706   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:00.706   841   841 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-12 11:37:00.707  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:37:00.707 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-12 11:37:00.707  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.105 ipV6Addr=
07-12 11:37:00.709  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-12 11:37:00.709  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:00.709  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
07-12 11:37:00.718  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-12 11:37:00.719  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:37:00.719  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-12 11:37:00.720  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-12 11:37:00.722  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-12 11:37:00.722  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSig,nalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:00.722  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
07-12 11:37:00.722  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-12 11:37:00.723  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-12 11:37:00.723  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
,07-12 11:37:00.742   841  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-12 11:37:00.743   841  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
07-12 11:37:00.745   269  1055 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-12 11:37:00.745   269  1055 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.745  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:37:00.745   269  1055 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-12 11:37:00.745   269  1055 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-12 11:37:00.746   841  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
07-12 11:37:00.747   269  1055 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-12 11:37:00.747   269  1055 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.747   269  1055 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-12 11:37:00.747   269  1055 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-12 11:37:00.748   841  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
07-12 11:37:00.748   269  1055 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-12 11:37:00.748   269  1055 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.749   841  1313 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-12 11:37:00.749   841  1313 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
07-12 11:37:00.751   841  1313 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
07-12 11:37:00.752   841  1313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.752   841  1313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.753   269  1055 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
07-12 11:37:00.753   269  1055 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.767   841  1313 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-12 11:37:00.768   841  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-12 11:37:00.768   841  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-12 11:37:00.768   841  1313 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-12 11:37:00.768   841  1313 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:00.769   841  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:37:00.769   841  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-12 11:37:00.769   841  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:00.769   841  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
07-12 11:37:00.769   841  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:00.769   841  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-12 11:37:00.769   841  1313 D ConnectivityService: currentScore = 0, newScore = 20
07-12 11:37:00.769   841  1313 D ConnectivityService:    accepting network in place of null
07-12 11:37:00.770   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:00.770   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
,07-12 11:37:00.772   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:00.775   841  1313 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:00.775   841  1307 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:00.775   841  1307 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:00.776   841  1313 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
07-12 11:37:00.780  1776  1776 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:00.781  1776  1776 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,07-12 11:37:00.783   841  1313 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-12 11:37:00.784   841  1313 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-12 11:37:00.784   841  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-12 11:37:00.785   841  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.785   841  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.786   841  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.786   841  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:00.786   269  1050 E BandwidthController: [LG DATA] No such appUid: 1000
07-12 11:37:00.786   269  1050 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-12 11:37:00.786  1909  1909 W QCNEJ   : |CORE| No family connected
07-12 11:37:00.786   269  6009 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-12 11:37:00.786   269  6009 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:00.787  1909  1909 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
07-12 11:37:00.787   269  6009 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=0
07-12 11:37:00.787   269  6009 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:00.788   269  6009 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:00.789   841  1028 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-12 11:37:00.790   269  1048 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
07-12 11:37:00.791   841  1028 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:00.791   841  1028 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:00.791  1909  1909 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
07-12 11:37:00.794   841  1030 D Tethering: MasterInitialState.processMessage what=3
07-12 11:37:00.794   841  1313 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-12 11:37:00.796   841  1313 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
,07-12 11:37:00.797   841  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-12 11:37:00.798  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
07-12 11:37:00.799   841  1313 D ConnectivityService: validation of new default Network = false
07-12 11:37:00.799   841  1313 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-12 11:37:00.799   841  1313 D DSQN    : enableDataServiceNotify 
07-12 11:37:00.799   841  1313 D DSQN    : start dsqn bin
07-12 11:37:00.800  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:37:00.8 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-12 11:37:00.818   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
,07-12 11:37:00.820  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-12 11:37:00.821   841  6010 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
07-12 11:37:00.825  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:37:00.828  1368  1368 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-12 11:37:00.838  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:37:00.839  1368  1368 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,07-12 11:37:00.840  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-12 11:37:00.840  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:00.841  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
07-12 11:37:00.843  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-12 11:37:00.843  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:00.843  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
07-12 11:37:00.845   841  1304 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-12 11:37:00.848  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:37:00.854  5827  5827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-12 11:37:00.858  5827  5827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-12 11:37:00.867  5780  5780 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-12 11:37:00.874   841  1313 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,07-12 11:37:00.875   841  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:00.875   841  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:37:00.875  5780  5780 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-12 11:37:00.881  5827  5827 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-12 11:37:00.881   841  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:37:00.882   841  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:00.882  5827  5827 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-12 11:37:00.883   841  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:00.884   841  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
07-12 11:37:00.884   841  1313 D ConnectivityService: identical MTU - not setting
07-12 11:37:00.884   841  1313 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-12 11:37:00.884   841  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-12 11:37:00.884   841  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:00.884   841  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:37:00.885   841  1313 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:37:00.886   841  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:00.886  5331  5608 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-12 11:37:00.887   841  1313 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:00.887  1368  1724 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-12 11:37:00.890  6011  6011 I DSQN    : DSQN samuel.seo ver 141203
07-12 11:37:00.890  6011  6011 E DSQN    : DSQN sock connect success to lgdatalistenerd
07-12 11:37:00.890  6011  6011 I DSQN    : created command queue thread
07-12 11:37:00.891   841  1313 D ConnectivityService: Wi-Fi IP changed. Lp difference / No Route difference
07-12 11:37:00.891  6011  6011 I DSQN    : Interface wlan0 address 192.168.1.105 0xc0a80169
07-12 11:37:00.891   841  1313 D DSQN    : enableDataServiceNotify 
07-12 11:37:00.891  6011  6011 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a80169
07-12 11:37:00.891   841  1313 D DSQN    : start dsqn bin
07-12 11:37:00.893  1368  1724 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-12 11:37:00.902   841  1313 D DSQN    : dsqn is running restart
,07-12 11:37:00.905  5331  5608 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-12 11:37:00.920  6014  6014 I DSQN    : DSQN samuel.seo ver 141203
07-12 11:37:00.920  6014  6014 E DSQN    : DSQN sock connect success to lgdatalistenerd
07-12 11:37:00.920  6014  6014 I DSQN    : created command queue thread
07-12 11:37:00.920  6014  6014 I DSQN    : Interface wlan0 address 192.168.1.105 0xc0a80169
07-12 11:37:00.920  6014  6014 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a80169
,07-12 11:37:01.322   841  6010 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
07-12 11:37:01.322   841  6010 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:01.322   841  6010 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:01.322   841  6010 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
07-12 11:37:01.322   841  6010 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:01.322   269  1050 E BandwidthController: [LG DATA] No such appUid: 1000
07-12 11:37:01.322   269  1050 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-12 11:37:01.323   269  6023 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
07-12 11:37:01.323   269  6023 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:01.323   269  6023 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:01.323   269  6023 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,07-12 11:37:01.480   269  6023 D libc-netbsd: res_queryN name = xxxxx succeed
,07-12 11:37:01.481   841  6010 I System.out: propertyValue:false
07-12 11:37:01.481   841  6010 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
07-12 11:37:01.488   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-12 11:37:01.517   841  5963 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:01.517   841  5963 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-12 11:37:01.543  6014  6015 I DSQN    : first global connection report this to start monitoring at DSQM.
07-12 11:37:01.543  6014  6015 I DSQN    : restart monitoring
07-12 11:37:01.544   269  1054 D LGDataListener: argv[0]=dsqncommand
07-12 11:37:01.544   269  1054 D LGDataListener: argv[1]=wlan0
07-12 11:37:01.544   269  1054 D LGDataListener: argv[2]=1
07-12 11:37:01.544   269  1054 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-12 11:37:01.545   841  1028 D DSQN    : DSQM DsqnNotification wlan0  1
07-12 11:37:01.545   841  1028 D DSQN    : start to monitor internet connection
07-12 11:37:01.545  6014  6025 I DSQN    : dsqn report finish
,07-12 11:37:01.576   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 09:37:01 GMT], X-Android-Received-Millis=[1468316221576], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1468316221550]}
07-12 11:37:01.576   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,07-12 11:37:01.580  1860  1896 D WifiServiceExtension: isInternetCheckAvailable return false
07-12 11:37:01.580   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
07-12 11:37:01.580   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,07-12 11:37:01.582   841  1313 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
07-12 11:37:01.582   841  1313 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-12 11:37:01.582   841  1313 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:01.582   841  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:37:01.582   841  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-12 11:37:01.582   841  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:01.582   841  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
07-12 11:37:01.583   841  1313 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
07-12 11:37:01.583   841  1313 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-12 11:37:01.583   841  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:01.583   841  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:37:01.583   841  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:37:01.584   841   841 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
,07-12 11:37:01.585   841  1307 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
07-12 11:37:01.586  1368  1724 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-12 11:37:01.586   841  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:01.587   841  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:01.587  5331  5608 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-12 11:37:01.588   841  1313 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:01.588   841  1307 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:01.589   841  1307 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:01.589  1776  1776 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:01.589  1776  1776 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
07-12 11:37:01.590   841  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-12 11:37:01.605  1368  1368 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-12 11:37:01.606  1368  1368 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
07-12 11:37:01.608  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,07-12 11:37:01.608  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:01.608  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
07-12 11:37:01.610  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-12 11:37:01.610  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:01.610  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
07-12 11:37:01.619   841  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{5d14c9f type 2 when 151515 com.google.android.gms} when 151515
,07-12 11:37:01.632  2322  6026 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:01.632  2322  6026 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-12 11:37:01.635  2322  6026 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:01.635  2322  6026 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:01.635   269  1050 E BandwidthController: [LG DATA] No such appUid: 10006
07-12 11:37:01.635   269  1050 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-12 11:37:01.635   269  6027 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:01.635   269  6027 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:01.636   269  6027 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:01.636   269  6027 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:01.673   269  6027 D libc-netbsd: res_queryN name = xxxxx succeed
,07-12 11:37:01.680  2322  6026 I System.out: propertyValue:false
07-12 11:37:01.696  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-12 11:37:01.696  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:01.696  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,07-12 11:37:01.779  2322  6026 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-12 11:37:01.779  2322  6026 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-12 11:37:01.894  2322  6026 I GCM     : GCM config loaded
,07-12 11:37:02.037   841   973 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6037 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-12 11:37:02.197  6037  6037 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-12 11:37:02.441   841   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-12 11:37:02.441   841   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-12 11:37:02.441   841   985 D sensors_hal_Time: tsOffsetIs: Apps: 152350942707; DSPS: 5090897; Offset : -3014596767
,07-12 11:37:02.454  6037  6061 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-12 11:37:02.454  6037  6061 I Babel_SMS: MmsConfig.loadMmsSettings
07-12 11:37:02.460  6037  6061 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-12 11:37:02.460  6037  6061 I Babel_SMS: MmsConfig.loadFromDatabase
,07-12 11:37:02.494  6037  6061 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-12 11:37:02.494  6037  6061 I Babel_SMS: MmsConfig.loadFromResources
07-12 11:37:02.497  6037  6061 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-12 11:37:02.497  6037  6061 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-12 11:37:02.517  6037  6037 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
07-12 11:37:02.517  6037  6037 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
07-12 11:37:02.517  6037  6037 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
07-12 11:37:02.517  6037  6037 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
07-12 11:37:02.517  6037  6037 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
07-12 11:37:02.517  6037  6037 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
07-12 11:37:02.517  6037  6037 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
07-12 11:37:02.518  6037  6037 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
07-12 11:37:02.518  6037  6037 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
07-12 11:37:02.518  6037  6037 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
07-12 11:37:02.518  6037  6037 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
07-12 11:37:02.518  6037  6037 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
07-12 11:37:02.518  6037  6037 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
07-12 11:37:02.518  6037  6037 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
07-12 11:37:02.518  6037  6037 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
07-12 11:37:02.518  6037  6037 D SensorManager: found sensor: Motion Accel, handle=46
,07-12 11:37:02.578  6037  6037 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 11:37:02.587  6037  6037 I Babel_Crash: startup - clean
07-12 11:37:02.604  6037  6068 I Babel   : deleted: false for 0
,07-12 11:37:02.608  6037  6051 I art     : CheckpointMarkThreadRoots callback created = 0xb042d810
,07-12 11:37:02.654  6037  6051 I art     : CheckpointMarkThreadRoots callback created = 0xb042d800
,07-12 11:37:02.689  6037  6051 W art     : Suspending all threads took: 21.491ms
,07-12 11:37:02.718   841  1039 I PowerManagerService: ALS enabled for SRE
,07-12 11:37:02.720   841  1039 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32628 ms ago)
07-12 11:37:02.720   841  1039 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-12 11:37:02.723  6037  6037 W AudioCapabilities: Unsupported mime audio/x-lg-flac
07-12 11:37:02.727  6037  6037 W AudioCapabilities: Unsupported mime audio/adpcm
07-12 11:37:02.730  6037  6037 W AudioCapabilities: Unsupported mime audio/g726
07-12 11:37:02.734   841  1039 I PowerManagerService: ALS enabled for SRE
07-12 11:37:02.734   841  1039 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (32644 ms ago)
,07-12 11:37:02.738   841  1039 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
07-12 11:37:02.740   841  1039 I PowerManagerService: Sleeping (uid 1000)...
07-12 11:37:02.740   841  1039 D LPWGController: [updateScreenState] screen on = false
07-12 11:37:02.741  6037  6037 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-12 11:37:02.742  6037  6037 W AudioCapabilities: Unsupported mime audio/wma-voice
07-12 11:37:02.743   841  1039 D LPWGController: disable proximity sensor
07-12 11:37:02.743   841  1039 D LPWGController: enable proximity sensor
07-12 11:37:02.743  6037  6037 W VideoCapabilities: Unsupported mime video/mjpg
07-12 11:37:02.754  6037  6037 W VideoCapabilities: Unsupported mime video/theora
07-12 11:37:02.754   841  1039 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@25dfb069] by com.android.server.power.ProximitySensorListener.enable():120
,07-12 11:37:02.761   841  1039 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
07-12 11:37:02.761   841  1039 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
07-12 11:37:02.761   841  1039 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
07-12 11:37:02.762   841  1039 I sensors_hal_Ctx: activate: handle is 48, enable
07-12 11:37:02.764   841  1039 V sensors_hal_Ctx: activate sensors is 1400000000000
07-12 11:37:02.764   841  1039 D sensors_hal_Thresh: enable: handle=48
07-12 11:37:02.764   841  1039 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
07-12 11:37:02.764   841  1039 D sensors_hal_Util: waitForResponse: timeout=1000
07-12 11:37:02.767  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
07-12 11:37:02.768  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-12 11:37:02.767 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-12 11:37:02.769   841   986 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
07-12 11:37:02.769   841   986 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
07-12 11:37:02.769   841  1039 D sensors_hal_Thresh: enable: Received response: 0
07-12 11:37:02.769  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-12 11:37:02.769  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:02.769  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
07-12 11:37:02.770   841  1039 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (32680 ms ago)
,07-12 11:37:02.792   841  1039 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:37:02.792   841  1039 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:37:02.792   841  1039 I Adreno-EGL: Build Date: 03/02/15 Mon
07-12 11:37:02.792   841  1039 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-12 11:37:02.792   841  1039 I Adreno-EGL: Remote Branch: 
07-12 11:37:02.792   841  1039 I Adreno-EGL: Local Patches: 
07-12 11:37:02.792   841  1039 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:37:02.807  6037  6037 W AudioCapabilities: Unsupported mime audio/evrc
,07-12 11:37:02.811  6037  6037 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 11:37:02.813  6037  6037 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 11:37:02.818   244  1286 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (160 us)
07-12 11:37:02.832  6037  6037 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-12 11:37:02.833  6037  6037 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 11:37:02.835  6037  6037 W AudioCapabilities: Unsupported mime audio/evrc
07-12 11:37:02.848  6037  6037 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-12 11:37:02.919  6037  6037 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-12 11:37:02.997   421   975 I Sensors : sns_pwr.c(273):acquiring wakelock
07-12 11:37:02.998   841   986 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,07-12 11:37:03.016   841   986 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
07-12 11:37:03.016   841   986 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
07-12 11:37:03.016   841   986 D sensors_hal_Thresh: processInd: handle 48, count=1
07-12 11:37:03.016   841   986 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
07-12 11:37:03.016   841   986 I sensors_hal_Thresh: processInd : proximity state changed - FAR
07-12 11:37:03.016   841  1026 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
07-12 11:37:03.017   841  1026 D sensors_hal_Ctx: poll: count: 256
07-12 11:37:03.017   841  1026 I sensors_hal_Ctx: poll: released wakelock sensor_ind
07-12 11:37:03.017   841  1026 D sensors_hal_Util: waitForResponse: timeout=0
,07-12 11:37:03.022  6037  6037 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 11:37:03.024  6037  6037 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 11:37:03.028  6037  6037 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 11:37:03.034  6037  6037 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-12 11:37:03.039   841  1039 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
07-12 11:37:03.039   841  1039 I LPWGController: current mode = 1  value = 1 1
07-12 11:37:03.040   841  1039 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
07-12 11:37:03.041   841  1934 I ActivityManager: Killing 4838:com.android.vending/u0a36 (adj 15): empty #11
07-12 11:37:03.104   841  1039 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,07-12 11:37:03.111   841  4781 W libprocessgroup: failed to open /acct/uid_10036/pid_4838/cgroup.procs: No such file or directory
,07-12 11:37:03.116  6037  6037 I vclib   : onServiceConnected
,07-12 11:37:03.117  6037  6037 W Babel   : Attempted to change video mute state without an active call.
,07-12 11:37:03.129  6037  6037 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,07-12 11:37:03.450   841  1345 D qdlights: set_light_backlight: 0
,07-12 11:37:03.463   841  1039 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
07-12 11:37:03.464   841  1039 I sensors_hal_Ctx: activate: handle is 46, disable
07-12 11:37:03.464   841  1039 V sensors_hal_Ctx: activate sensors is 1000000000000
07-12 11:37:03.464   841  1039 D sensors_hal_LP2: enable: handle=46
07-12 11:37:03.464   841  1039 D sensors_hal_LP2: enable: Disabling sensor handle=46
07-12 11:37:03.464   841  1039 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,07-12 11:37:03.470   244   244 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
07-12 11:37:03.470   244   244 D qdhwcomposer: hwc_blank: Blanking display: 0
07-12 11:37:03.476   841  1032 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-12 11:37:03.476   841   841 V ActivityManager: Display changed displayId=0
,07-12 11:37:03.501   841  1013 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
07-12 11:37:03.501   841  1013 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,07-12 11:37:03.532  1776  1776 D DSDPConnection: Display #0 changed.
,07-12 11:37:03.659   244   244 D qdhwcomposer: hwc_blank: Done blanking display: 0
07-12 11:37:03.659   841  1345 D SurfaceControl: Excessive delay in setPowerMode(): 188ms
,07-12 11:37:03.660   244   678 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-12 11:37:03.661   841  1345 I QCOM PowerHAL: Got set_interactive hint
07-12 11:37:03.671  1368  1990 D KeyguardViewMediator: onScreenTurnedOff(3)
,07-12 11:37:03.683  5651  5651 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-12 11:37:03.683  5651  5651 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-12 11:37:03.685   841  1308 V WifiInternetCheck: Single check msg out of sync, ignoring.
,07-12 11:37:03.697  1368  1990 D KeyguardViewMediator: notifyScreenOffLocked
,07-12 11:37:03.699  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-12 11:37:03.699  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:03.699  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
07-12 11:37:03.701   841   841 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
07-12 11:37:03.701  5651  5651 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3a3e2fa7 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3b7b1a5e, 16908290=android.view.AbsSavedState$1@3b7b1a5e}, android:focusedViewId=100}]}]
07-12 11:37:03.701  5651  5651 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-12 11:37:03.702  1328  2003 D SmartCoverViewMediator: onScreenTurnedOff(3)
07-12 11:37:03.703   274  1353 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 841
07-12 11:37:03.704   274  1353 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-12 11:37:03.704   274  1353 V voice   : voice_set_parameters: enter: screen_state=on
07-12 11:37:03.704   274  1353 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
07-12 11:37:03.705   274  1353 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-12 11:37:03.705   274  1353 V voice   : voice_set_parameters: exit with code(0)
07-12 11:37:03.705   274  1353 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
07-12 11:37:03.705   274  1353 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-12 11:37:03.705   274  1353 V msm8974_platform: platform_set_parameters: exit with code(0)
07-12 11:37:03.705   274  1353 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-12 11:37:03.705  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-12 11:37:03.705  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:03.705   274  1353 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
07-12 11:37:03.705   274  1353 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-12 11:37:03.705   274  1353 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-12 11:37:03.705  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
07-12 11:37:03.708  5651  5651 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 11:37:03.708  5651  5651 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-12 11:37:03.715  1328  2003 D SmartCoverViewMediator: notifyScreenOffLocked
,07-12 11:37:03.717  1328  1328 D SmartCoverViewMediator: handleNotifyScreenOFF
,07-12 11:37:03.719   841  1307 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
07-12 11:37:03.719  1368  1990 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
07-12 11:37:03.719  1368  1368 D KeyguardViewMediator: handleNotifyScreenOff
07-12 11:37:03.731  1368  1368 D ScreenTurnOffBySensor: unregisterProximitySensor
,07-12 11:37:03.739  1368  1368 D StatusBarWindowView: onScreenTurnedOff why = 3
07-12 11:37:03.741  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-12 11:37:03.741  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
07-12 11:37:03.743   841   972 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-12 11:37:03.775   841   861 D SplitWindow: check instance of lgWin Window{1339ea25 u0 SearchPanel}
,07-12 11:37:03.779  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:true
07-12 11:37:03.783  1860  2026 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-12 11:37:03.784  1860  2026 D LEDService: stopPatternFlashing()
07-12 11:37:03.785  1860  2026 D qdlights: set_light_notifications: 0,0,0,0,3
07-12 11:37:03.787  1860  2026 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-12 11:37:03.787  1860  2026 D qdlights: set_light_notifications: 0,0,0,0,3
07-12 11:37:03.788  1860  2026 I LEDService: updateLightsLocked : turn off led
07-12 11:37:03.788  1860  2026 D qdlights: set_light_notifications: 0,0,0,0,3
,07-12 11:37:03.797   841  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-12 11:37:03.797  1860  2026 D LEDHandler: RESTART MSG
07-12 11:37:03.801   841   972 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:03.815  2056  2072 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:37:03.817  5651  5651 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:37:03.817  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:03.817  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 11:37:03.817  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:37:03.817  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:37:03.817  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 11:37:03.817  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 11:37:03.817  5651  5651 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 11:37:03.818  2056  2072 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
,07-12 11:37:03.821  5651  5651 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 11:37:03.823   841   841 D LocSvc_java: onReceive
07-12 11:37:03.823   841  1755 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:03.823   841  1755 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:03.823   841   841 D LocSvc_java: got connectivity action
07-12 11:37:03.823   841  1755 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:03.823   841  1755 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:03.824   269  1050 E BandwidthController: [LG DATA] No such appUid: 1000
07-12 11:37:03.824   269  1050 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-12 11:37:03.826   841   841 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
07-12 11:37:03.826   841   841 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-12 11:37:03.830   269  6078 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:03.830   269  6078 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:03.830   269  6078 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:03.831   269  6078 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,07-12 11:37:03.855   841   841 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-12 11:37:03.858   841   841 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-12 11:37:03.858   841   841 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-12 11:37:03.858   841   841 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
,07-12 11:37:03.862   841   973 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6079 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-12 11:37:03.865   841  6080 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:03.866   841  6080 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:03.866   841  6080 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:03.866   841  6080 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:03.866   269  1050 E BandwidthController: [LG DATA] No such appUid: 1000
07-12 11:37:03.866   269  1050 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-12 11:37:03.867   269  6086 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:03.867   269  6086 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:03.867   269  6086 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:03.867   269  6086 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:03.894   841  1908 D InputDispatcher: Window went away: Window{e3f7a6b u0 SearchPanel}
,07-12 11:37:03.899   841  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:03.899   841  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:03.899   841  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:03.899   841  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:03.900   269  1050 E BandwidthController: [LG DATA] No such appUid: 1000
07-12 11:37:03.900   269  1050 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-12 11:37:03.902  1368  1368 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
07-12 11:37:03.906  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
,07-12 11:37:03.909   269  6094 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:03.909   269  6094 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:03.910   269  6086 D libc-netbsd: res_queryN name = xxxxx succeed
07-12 11:37:03.910   269  6078 D libc-netbsd: res_queryN name = xxxxx succeed
07-12 11:37:03.910   269  6094 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:03.910   269  6094 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:03.910   269  6094 D libc-netbsd: res_queryN name = xxxxx succeed
07-12 11:37:03.911   841  1755 I System.out: propertyValue:false
07-12 11:37:03.912   841  1304 I System.out: propertyValue:false
07-12 11:37:03.912   293   357 I ThermalEngine: Sensor:pa_therm0:33000 mC
07-12 11:37:03.912   841  6080 I System.out: propertyValue:false
,07-12 11:37:03.922  1368  1368 I LgeClockWidgetControlView: time changed, timezoneChanged : false
07-12 11:37:03.930  2322  2322 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,07-12 11:37:03.931   841  6080 D LocSvc_java: NTP server returned: 1468316223416 (Tue Jul 12 11:37:03 GMT+02:00 2016) reference: 153837 certainty: 8 system time offset: -515
07-12 11:37:03.937   841  6080 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
07-12 11:37:03.944   841  1755 D AlarmManagerService: Setting time of day to sec=1468316223
07-12 11:37:03.418   841  1755 W AlarmManagerService: Unable to set rtc to 1468316223: Invalid argument
,07-12 11:37:03.430  1835  1835 D LNfcService: action : android.intent.action.SCREEN_ON
,07-12 11:37:03.440  1835  6105 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
07-12 11:37:03.440  1835  6105 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
07-12 11:37:03.440  1835  6105 D LNfcService: isRequireNfcCRouting() return true
07-12 11:37:03.440  1835  6105 D LNfcService: isHCERoutingtoHost() return : true
07-12 11:37:03.440  1835  6105 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-12 11:37:03.440  1835  6105 D NfcService: mEnableLPD: true
07-12 11:37:03.440  1835  6105 D NfcService: mEnableReader: false
07-12 11:37:03.440  1835  6105 D NfcService: mEnableHostRouting: true
07-12 11:37:03.441  1835  6105 D NfcService: newParams.techmask= mTechMask: default
07-12 11:37:03.441  1835  6105 D NfcService: mEnableLPD: true
07-12 11:37:03.441  1835  6105 D NfcService: mEnableReader: false
07-12 11:37:03.441  1835  6105 D NfcService: mEnableHostRouting: true
07-12 11:37:03.441  1835  6105 D NfcService: screenState= 3
07-12 11:37:03.441  1835  6105 D NfcService: Discovery configuration equal, not updating.
,07-12 11:37:03.477   841   972 I ActivityManager: Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6107 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-12 11:37:03.483   841   972 I NotificationManager: android: cancelAsUser(716319171) by android
07-12 11:37:03.509  1860  1860 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,07-12 11:37:03.510  1860  1860 D Cliptray Service: lockStatus = 0
07-12 11:37:03.512  1368  1368 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
07-12 11:37:03.515  1368  1368 I LgeClockWidgetControlView: time changed, timezoneChanged : false
07-12 11:37:03.526  2827  2827 D WeatherService: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:37:3
,07-12 11:37:03.542  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:37:03.543  2827  2827 D WeatherService: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:37:3
07-12 11:37:03.544   841   841 D Ulp_jni : JNI:system_update. Event-0
07-12 11:37:03.555   841  4781 W ActivityManager: getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,07-12 11:37:03.568  1776  1776 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,07-12 11:37:03.619  6107  6107 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:37:03.619  6107  6107 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-12 11:37:03.625  6107  6107 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-12 11:37:03.629   841   972 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:37:03.639  2827  2827 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:37:3
,07-12 11:37:03.642  2827  2827 D WeatherService: 2 : ACTION screen on
07-12 11:37:03.648  2827  2827 D WeatherService: 2 : shouldTimeTickRegistered : false
07-12 11:37:03.656  1946  1946 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=12 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
,07-12 11:37:03.672   274  1603 V AudioFlinger: 2845 died, releasing its sessions
07-12 11:37:03.672   274  1603 V AudioFlinger:  pid 1776 @ 0
07-12 11:37:03.672   274  1603 V AudioFlinger:  pid 3102 @ 1
07-12 11:37:03.673   274  1603 V AudioFlinger:  pid 3102 @ 2
07-12 11:37:03.673  2827  2827 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-12 11:37:03.674  2827  2827 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:37:3
,07-12 11:37:03.703  1946  1946 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 12
,07-12 11:37:03.710  1946  1946 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 12
07-12 11:37:03.717  1946  1946 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,07-12 11:37:03.733   841  1908 I ActivityManager: Process com.lge.music (pid 2845) has died
,07-12 11:37:03.737   841   972 E GpsLocationProvider: No APN found to select.
07-12 11:37:03.745  3867  3867 D AppCleanupService: android.intent.action.SCREEN_ON
,07-12 11:37:03.756   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:03.756   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:03.756   841   841 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,07-12 11:37:03.804   841   841 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=6128 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-12 11:37:03.858   841   972 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6143 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-12 11:37:03.875   241   241 E lowmemorykiller: Error opening /proc/5883/oom_score_adj; errno=2
,07-12 11:37:03.879   841  6151 D LgeGpsConstants: Can't find 'ext_gps.conf'!!
07-12 11:37:03.880   841  6151 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:03.880   841  6151 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:03.880   841  6151 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:03.880   841  6151 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:03.880   269  1050 E BandwidthController: [LG DATA] No such appUid: 1000
07-12 11:37:03.880   269  1050 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-12 11:37:03.881   269  6157 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:03.881   269  6157 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:03.881   269  6157 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:03.881   269  6157 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:03.929   841  1991 I ActivityManager: Process com.lge.lgdmsclient (pid 5883) has died
,07-12 11:37:03.939   269  6157 D libc-netbsd: res_queryN name = xxxxx succeed
07-12 11:37:03.939   841  6151 I System.out: propertyValue:false
07-12 11:37:03.940  6107  6107 I AppConfig: Total System Memory = 906309632
07-12 11:37:03.943  6107  6107 I GalleryUtils: Application Heap = 96 MB
,07-12 11:37:03.952  6107  6107 I AppConfig: App Tier : NOT_DEF
07-12 11:37:03.960  6107  6107 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,07-12 11:37:03.970   421   430 I Sensors : sns_pwr.c(301):releasing wakelock
07-12 11:37:03.971   841  6151 D LgeGpsLocationProvider: NTP server: europe.pool.ntp.org
07-12 11:37:03.972   841  6151 D LgeGpsLocationProvider: NTP server returned: 1468316223985 (Tue Jul 12 11:37:03 GMT+02:00 2016) reference: 154404 certainty: 16 system time offset: 14
,07-12 11:37:04.016  6128  6128 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:37:04.016  6128  6128 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-12 11:37:04.018  6128  6128 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-12 11:37:04.033  6079  6079 I MusicStore: Database version: 120
,07-12 11:37:04.080  6143  6143 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:37:04.173  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,07-12 11:37:04.189  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-12 11:37:04.190  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,07-12 11:37:04.286   243   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-12 11:37:04.286   243   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-12 11:37:04.286   243   354 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 11:37:04.289  6079  6079 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,07-12 11:37:04.360  6128  6128 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-12 11:37:04.366  5331  5417 D NetworkUsageDbReporter: Started reporting usage
07-12 11:37:04.398   841  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:04.398   841  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:04.399   841  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:04.399   841  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-12 11:37:04.400   269  1050 E BandwidthController: [LG DATA] No such appUid: 1000
07-12 11:37:04.400   269  1050 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-12 11:37:04.403   269  6180 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:04.404   269  6180 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:04.404   269  6180 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:04.404   269  6180 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:04.409   841   860 I ActivityManager: Process com.lge.bnr (pid 5483) has died
07-12 11:37:04.435  6128  6128 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,07-12 11:37:04.458   841   972 I art     : Explicit concurrent mark sweep GC freed 88865(4MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 8.019ms total 461.168ms
,07-12 11:37:04.513   841  2080 I ActivityManager: Process com.lge.settings.easy (pid 5848) has died
07-12 11:37:04.521  5939  5939 D UEI.SmartControl: Service.onTrimMemory: 60
,07-12 11:37:04.527   269  6180 D libc-netbsd: res_queryN name = xxxxx succeed
07-12 11:37:04.529   841  1308 I System.out: propertyValue:false
07-12 11:37:04.532  2032  2032 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-12 11:37:04.534  1776  1776 I PhoneApp: onTrimMemory: 10
07-12 11:37:04.534  1776  1776 I PhoneApp: trim memory
,07-12 11:37:04.539  5939  5939 E UEI.SmartControl: Setup service releasing memory...
07-12 11:37:04.541  5331  6186 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
07-12 11:37:04.550   841  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:04.550   841  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:04.551   841  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:04.551   841  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-12 11:37:04.552   269  1050 E BandwidthController: [LG DATA] No such appUid: 1000
07-12 11:37:04.552   269  1050 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-12 11:37:04.552   269  6191 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:04.552   269  6191 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-12 11:37:04.552   269  6191 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:04.553   269  6191 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:04.553   269  6191 D libc-netbsd: res_queryN name = xxxxx succeed
07-12 11:37:04.553   841  1309 I System.out: propertyValue:false
07-12 11:37:04.577  2322  2322 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:37:04.581  2322  2322 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 11:37:04.595  2322  2322 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:37:04.606   841  1309 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
07-12 11:37:04.607   841   972 I NotificationManager: android: cancelAsUser(-1597574061) by android
,07-12 11:37:04.618  5939  5939 I art     : Explicit concurrent mark sweep GC freed 133(16KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 341us total 51.556ms
,07-12 11:37:04.645   841   972 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 36765, reason: UserStart, SyncResult: databaseError: true stats []
07-12 11:37:04.652   841   972 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 185496, reason: UserStart
07-12 11:37:04.657   841   972 I NotificationManager: android: cancelAsUser(716319171) by android
,07-12 11:37:04.716  5331  6156 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 267676
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: keeping row: 238
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 13594
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: keeping row: 237
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 38489
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: keeping row: 236
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 86075
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: keeping row: 235
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 41782
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: keeping row: 248
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 24135
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: keeping row: 234
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 98118
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: keeping row: 246
07-12 11:37:04.745  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 6495
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: keeping row: 240
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 45621
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: keeping row: 233
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 6831
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: keeping row: 245
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 15977
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: keeping row: 247
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2612
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: keeping row: 244
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 39728
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: keeping row: 239
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 8983
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: keeping row: 250
,07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 15366
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: keeping row: 243
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 30559
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: keeping row: 249
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 47326
07-12 11:37:04.746  5331  5417 D NetworkUsageDbReporter: keeping row: 242
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 162146
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: keeping row: 232
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 26111
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: keeping row: 241
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 46889
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: keeping row: 231
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 634964
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: keeping row: 230
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2435587
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: keeping row: 229
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 6339
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: keeping row: 221
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1138
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: keeping row: 218
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2178
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: keeping row: 213
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 28541
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: keeping row: 211
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 14027
07-12 11:37:04.747  5331  5417 D NetworkUsageDbReporter: keeping row: 212
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 32339
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: keeping row: 190
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 4199
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: keeping row: 189
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 18436
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: keeping row: 188
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 7001
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: keeping row: 187
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 321830
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: keeping row: 186
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 37474
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: keeping row: 185
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 28199
07-12 11:37:04.748  5331  5417 D NetworkUsageDbReporter: keeping row: 183
07-12 11:37:04.761   243   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-12 11:37:04.761   243   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-12 11:37:04.761   243   354 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 11:37:04.763  6079  6079 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,07-12 11:37:04.765   243   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-12 11:37:04.765   243   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-12 11:37:04.765   243   354 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 11:37:04.766  6079  6079 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-12 11:37:04.773   841  2125 I ActivityManager: Process com.android.settings (pid 5780) has died
,07-12 11:37:04.781  2032  2032 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-12 11:37:04.783  5939  5939 D UEI.SmartControl: Service.onTrimMemory: 60
07-12 11:37:04.783  5939  5939 E UEI.SmartControl: Setup service releasing memory...
07-12 11:37:04.785  1776  1776 I PhoneApp: onTrimMemory: 10
07-12 11:37:04.785  1776  1776 I PhoneApp: trim memory
,07-12 11:37:04.809   841   972 I NotificationManager: android: cancelAsUser(353845882) by android
,07-12 11:37:04.841   841   972 I NotificationManager: android: cancelAsUser(-591465577) by android
07-12 11:37:04.864  5331  5417 D NetworkUsageDbReporter: Finished reporting usage.
,07-12 11:37:04.926  6079  6079 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-12 11:37:04.929  6079  6079 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-12 11:37:04.940   841  1908 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6204 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-12 11:37:04.952  6143  6163 I art     : CheckpointMarkThreadRoots callback created = 0xb04889e0
,07-12 11:37:05.039  6143  6163 I art     : CheckpointMarkThreadRoots callback created = 0xb04889d0
,07-12 11:37:05.111  6079  6079 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 11:37:05.173  6204  6221 D ALBootInit: ====action==>android.intent.action.TIME_SET
,07-12 11:37:05.182  6204  6221 D ALBootInit: Alarm ALBootInit: TIME_SET
07-12 11:37:05.186  6204  6221 D Alarms  : [setNextAlert] start
,07-12 11:37:05.208  6204  6221 D Alarms  : [setNextAlert] (1)
,07-12 11:37:05.216  6204  6221 D Alarms  :  minTime  = 0
07-12 11:37:05.221  6204  6221 D Alarms  :  -- OK multi -- 0
07-12 11:37:05.222  6204  6221 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
07-12 11:37:05.222  6204  6221 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
07-12 11:37:05.224  6143  6198 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:37:05.227  5939  5974 D UEI.SmartControl: Internal timer expired: 1
07-12 11:37:05.239  6204  6221 I CommonUtil: BUILD Operator: OPEN
07-12 11:37:05.241  6204  6221 D Alarms  : broadcastToWidgetProvider : false
,07-12 11:37:05.246  6204  6221 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
07-12 11:37:05.275   841  1867 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,07-12 11:37:05.283  6204  6204 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
07-12 11:37:05.285  6204  6204 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2e463c90
07-12 11:37:05.289  6204  6204 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2e463c90
,07-12 11:37:05.295  6204  6204 D QuickCoverProvider: onReceiver
07-12 11:37:05.306  6079  6079 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-12 11:37:05.307  6079  6079 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d9f90fe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-12 11:37:05.308  6079  6079 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-12 11:37:05.309  6079  6079 D AndroidMusic: GMSCore installation verified
07-12 11:37:05.332   841  1634 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6225 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:37:05.371  6079  6079 I ConfigStore: Config Database version: 1
,07-12 11:37:05.400  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 11:37:05.400  5651  5722 I jxcore-log: 
,07-12 11:37:05.427  6143  6245 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:05.428  6143  6245 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
07-12 11:37:05.428   269  1050 E BandwidthController: [LG DATA] No such appUid: 10086
07-12 11:37:05.428   269  1050 D DnsProxyListener: App 10086 tries DNS query. Accept family:2 protocol:0
07-12 11:37:05.428   269  6249 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:05.428   269  6249 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
07-12 11:37:05.429   269  6249 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:05.447  6225  6225 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:37:05.470   269  6249 D libc-netbsd: res_queryN name = xxxxx succeed
,07-12 11:37:05.490   841   972 I NotificationManager: android: cancelAsUser(-591465577) by android
07-12 11:37:05.522  6225  6225 D CalendarApplication: CalendarApplication.onCreate()
,07-12 11:37:05.560  6225  6225 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
07-12 11:37:05.561  6225  6225 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@4c32ab7, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3ea72224, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2568b18d, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@33babf42, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1bd5bb53, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2e463c90, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1bbd989, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2398d8e, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@576b9af, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@c7a91bc, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1bff8545, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1ec4f49a, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@257f41cb, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2b3d0da8, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3b1830c1, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3e6dc066, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3a3e2fa7, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1295c54, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@15b617fd, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@4857cf2, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2e141f43, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@30e9e9c0, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@235136f9, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@5ea763e, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@26cf6c9f, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1b63e1ec, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@e549b5, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3513b84a, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2ec833bb, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@28a330d8, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@256dcc31, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2dd0f16, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@13bc5097, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@33868284, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2221fa6d, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1306a2, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@176b5f33, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@42b42f0, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2a70d069, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@bbeeaee, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.Preferenc,eKey$KeyData@df2bb8f, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@5199e1c, lg_pr
,07-12 11:37:05.566  6225  6225 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
07-12 11:37:05.578  6225  6225 D Config  : [init]
07-12 11:37:05.580  6225  6225 I Config  : LGCalendar ver.4.40.17
07-12 11:37:05.580  6225  6225 I Config  : start check model
07-12 11:37:05.580  6225  6225 I Config  : start check native_ca
07-12 11:37:05.581  6225  6225 I Config  : Config Operator=OPEN, Country=EU
07-12 11:37:05.581  6225  6225 D Config  : [setDefaultValuesToPref]
07-12 11:37:05.582  6225  6225 D Config  : [parseProfiles]
,07-12 11:37:05.586  6225  6225 D ProfilesParser: [debug_displayParseInfos] profile.country = null
07-12 11:37:05.586  6225  6225 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
07-12 11:37:05.586  6225  6225 D Config  : [updateProfiletoCountryInfo]
07-12 11:37:05.588  6225  6225 D GeneralPreference: [checkAndMigrateOldPreference]
07-12 11:37:05.624   841  1906 I ActivityManager: Process com.lge.qremote (pid 5914) has died
,07-12 11:37:05.626  5939  5939 D UEI.SmartControl: Service.onUnbind: IControl
07-12 11:37:05.627  5939  5939 D UEI.SmartControl: Service.onDestroy
07-12 11:37:05.628  5939  5939 D UEI.SmartControl: Shutdown IRRCPlayer... 
07-12 11:37:05.630  2032  2032 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-12 11:37:05.643  1776  1776 I PhoneApp: onTrimMemory: 10
07-12 11:37:05.643  1776  1776 I PhoneApp: trim memory
,07-12 11:37:05.647  5939  5939 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
07-12 11:37:05.647  5939  5939 D irrcClient: ~IrrcClient ++ 
07-12 11:37:05.647  5939  5939 D irrcClient: ~IrrcClient -- 
07-12 11:37:05.647  5939  5939 W irrc_jni: IRRCPlayer_nativeFinalize -- 
07-12 11:37:05.647  5939  5939 D UEI.SmartControl: Blaster closed
07-12 11:37:05.647  5939  5939 D UEI.SmartControl: Blaster closed
07-12 11:37:05.647  5939  5939 D UEI.SmartControl: Shut down QS...
07-12 11:37:05.648  5939  5939 D UEI.SmartControl: Stopped file observer...
07-12 11:37:05.657  5939  5939 I UEI.SmartControl: QS lib stop result = true
07-12 11:37:05.658  5939  5939 D UEI.SmartControl: QS shutdown complete
,07-12 11:37:05.669  6079  6079 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
07-12 11:37:05.673  6225  6225 E AgendaWidgetManager: [updateWidgets] 
,07-12 11:37:05.680  6225  6256 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
07-12 11:37:05.682  6079  6102 I art     : CheckpointMarkThreadRoots callback created = 0xb042d380
07-12 11:37:05.691  6225  6256 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,07-12 11:37:05.696  6079  6079 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
07-12 11:37:05.698   841   972 I NotificationManager: android: cancelAsUser(353845882) by android
07-12 11:37:05.729  6079  6079 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-12 11:37:05.740   841   972 I NotificationManager: android: cancelAsUser(-1597574061) by android
07-12 11:37:05.746  6225  6256 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,07-12 11:37:05.751  6079  6102 I art     : CheckpointMarkThreadRoots callback created = 0xb042d360
07-12 11:37:05.752  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
07-12 11:37:05.756  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
07-12 11:37:05.760  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,07-12 11:37:05.765  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
07-12 11:37:05.775  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,07-12 11:37:05.779  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
07-12 11:37:05.783  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
07-12 11:37:05.788  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,07-12 11:37:05.792  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
07-12 11:37:05.801  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,07-12 11:37:05.806  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
07-12 11:37:05.810  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
07-12 11:37:05.814  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,07-12 11:37:05.819  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
07-12 11:37:05.823  6225  6256 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
07-12 11:37:05.823  6225  6256 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
07-12 11:37:05.827  6225  6256 I AlertUtils: set default noti to content://media/internal/audio/media/38
,07-12 11:37:05.835  6225  6256 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
07-12 11:37:05.842  6079  6079 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-12 11:37:05.869   241   241 E lowmemorykiller: Error writing /proc/5939/oom_score_adj; errno=22
,07-12 11:37:05.906  6128  6128 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-12 11:37:06.037  6225  6225 D MonthWidgetProvider: [onReceive]
07-12 11:37:06.037  6225  6225 D CalendarWidgetProvider: [onReceive]
,07-12 11:37:06.038  6225  6225 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
07-12 11:37:06.038  6225  6262 W HolidayIntentService: onHandleIntent
07-12 11:37:06.040  6225  6262 D HolidayDataLoader: readJsonAsset : holiday.json
07-12 11:37:06.041  6225  6225 D CalendarTypeController: [onUpdateAndInitCalendarTime]
07-12 11:37:06.063   841  1293 I ActivityManager: Process com.uei.lg.quicksetsdk.lite (pid 5939) has died
,07-12 11:37:06.066  2032  2032 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-12 11:37:06.069  1776  1776 I PhoneApp: onTrimMemory: 10
,07-12 11:37:06.069  1776  1776 I PhoneApp: trim memory
07-12 11:37:06.076  6225  6225 D WeekWidgetProvider: [onReceive]
07-12 11:37:06.076  6225  6225 D CalendarWidgetProvider: [onReceive]
07-12 11:37:06.076  6225  6225 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,07-12 11:37:06.076  6225  6225 D CalendarTypeController: [onUpdateAndInitCalendarTime]
07-12 11:37:06.085  2827  2827 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:37:6
07-12 11:37:06.085  6079  6079 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
07-12 11:37:06.089  2827  2827 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-12 11:37:06.094  2827  2827 D Weather_cast: 2 : set auto-update time : 7/12 14:37
,07-12 11:37:06.105  2827  2827 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:37:6
07-12 11:37:06.105  2827  2827 D WeatherService: 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
07-12 11:37:06.106  2827  2827 D WeatherService: 2 : shouldTimeTickRegistered : false
07-12 11:37:06.134  6225  6262 E HolidayIntentService: onHandleIntent:holiday data empty
,07-12 11:37:06.152   841  1867 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6264 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-12 11:37:06.158  6079  6079 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-12 11:37:06.218  6128  6128 I HubEmail: JNI_OnLoad()
07-12 11:37:06.218  6128  6128 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,07-12 11:37:06.218  6128  6128 I HubEmail: registerNatives()
07-12 11:37:06.218  6128  6128 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-12 11:37:06.218  6128  6128 I HubEmail: registerNativeMethods()
07-12 11:37:06.218  6128  6128 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-12 11:37:06.218  6128  6128 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-12 11:37:06.246   841  1867 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6282 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-12 11:37:06.249  6128  6281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:06.285  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 11:37:06.285  5651  5722 I jxcore-log: 
,07-12 11:37:06.295  6264  6264 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1468316226295
07-12 11:37:06.295  6264  6264 D         : TimeServiceNative: User Time to be set is 1468316226295
07-12 11:37:06.295  6264  6264 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-12 11:37:06.295  6264  6264 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-12 11:37:06.295  6264  6264 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1468316226295
07-12 11:37:06.296  6264  6264 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
07-12 11:37:06.298   323  1063 D QC-time-services: Daemon: Connection accepted:time_genoff
07-12 11:37:06.300   323  6301 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1468316226295
07-12 11:37:06.300   323  6301 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1468316226295, operation = 0
07-12 11:37:06.300   323  6301 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/23/70 13:37:48
07-12 11:37:06.301   323  6301 D QC-time-services: Daemon:Value read from RTC seconds = 28215468000
07-12 11:37:06.301   323  6301 D QC-time-services: Daemon:new time 1468316226295 
07-12 11:37:06.301   323  6301 D QC-time-services: Daemon: delta 1440100758295 genoff 1440100758295 
07-12 11:37:06.301   323  6301 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100758295 to memory
07-12 11:37:06.301   323  6301 D QC-time-services: Daemon:Opening File: /data/time/ats_2
07-12 11:37:06.301   323  6301 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:37:06.322   323  6301 D QC-time-services: Updating the TOD offset
07-12 11:37:06.322   323  6301 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100758295 to memory
,07-12 11:37:06.322   323  6301 D QC-time-services: Daemon:Opening File: /data/time/ats_1
07-12 11:37:06.322   323  6301 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
07-12 11:37:06.334   323  6301 E QC-time-services: Daemon:Update to modem bit set
07-12 11:37:06.334   323  6301 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-12 11:37:06.334   323  6301 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124135958295
,07-12 11:37:06.335  6264  6264 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
07-12 11:37:06.338   323  1061 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
07-12 11:37:06.338   323  1063 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-12 11:37:06.344  6079  6168 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
07-12 11:37:06.344  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 11:37:06.344  5651  5722 I jxcore-log: 
07-12 11:37:06.352  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 11:37:06.352  5651  5722 I jxcore-log: 
,07-12 11:37:06.382  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 11:37:06.382  5651  5722 I jxcore-log: 
,07-12 11:37:06.389  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 11:37:06.389  5651  5722 I jxcore-log: 
07-12 11:37:06.413   841  1906 I ActivityManager: Process com.google.android.talk (pid 6037) has died
,07-12 11:37:06.431  6282  6282 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-12 11:37:06.431  6282  6282 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-12 11:37:06.441  6282  6282 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-12 11:37:06.444  6282  6282 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-12 11:37:06.458  6282  6306 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:06.459  6282  6306 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-12 11:37:06.475  6282  6305 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-12 11:37:06.478  6282  6305 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
07-12 11:37:06.492   841  1293 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6311 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-12 11:37:06.497  6282  6305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
07-12 11:37:06.514   301   301 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.325ms
,07-12 11:37:06.533  6282  6282 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
07-12 11:37:06.535  6282  6282 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
07-12 11:37:06.536   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 309us total 21.587ms
,07-12 11:37:06.536  6282  6282 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
07-12 11:37:06.549  6282  6282 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,07-12 11:37:06.556  6282  6282 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
07-12 11:37:06.561   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 24.116ms
,07-12 11:37:06.625  6143  6143 I NotificationManager: com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,07-12 11:37:06.654  6311  6311 I AppUp4:AppBoxCP: onCreate
,07-12 11:37:06.655  6311  6311 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-12 11:37:06.675  6311  6311 I AppUp4:DB:  setFingerPrint start
07-12 11:37:06.676  6311  6311 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,07-12 11:37:06.689  6311  6311 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
,07-12 11:37:06.690  6311  6311 I AppUp4:DB:  SDK version = 21
07-12 11:37:06.690  6311  6311 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-12 11:37:06.693  6311  6311 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-12 11:37:06.713  6311  6311 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-12 11:37:06.713  6311  6311 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:06.717  6311  6311 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-12 11:37:06.717  6311  6311 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-12 11:37:06.727  6311  6311 I AppUp4:CustModeStarterReceiver: onReceive
07-12 11:37:06.727  6311  6311 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:06.748  6311  6311 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1bd5bb53
07-12 11:37:06.748  6311  6311 D AppUp4:CustFacade: isCustomizationCompleted : false
,07-12 11:37:06.767  6311  6311 D AppUp4:CustFacade: isSimDevice : true
,07-12 11:37:06.769  6311  6311 D AppUp4:CustModeStarterReceiver: begin check event
07-12 11:37:06.769  6311  6311 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-12 11:37:06.769  6311  6311 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-12 11:37:06.774  6311  6329 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-12 11:37:06.775  6311  6329 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-12 11:37:06.776  6311  6329 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-12 11:37:06.811   841   972 I NotificationManager: android: cancelAsUser(2145784878) by android
,07-12 11:37:06.836  3102  3102 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,07-12 11:37:06.836  3102  3102 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-12 11:37:06.838  3102  3102 I LgeMiscReceiver: networkInfo.isConnected() = true
07-12 11:37:06.845  3102  3102 D PhoneState: setPdpRejectCasuse : false
07-12 11:37:06.889   841  1906 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6331 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,07-12 11:37:06.900   841   861 I art     : Explicit concurrent mark sweep GC freed 25529(1122KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.527ms total 161.426ms
07-12 11:37:07.025   841  1634 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6353 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,07-12 11:37:07.056   841  2125 I ActivityManager: Killing 5827:com.lge.sync/1000 (adj 15): empty #11
,07-12 11:37:07.146  6331  6331 D PhoneMonitor: Register our PhoneStateListener
,07-12 11:37:07.204   841   861 W libprocessgroup: failed to open /acct/uid_1000/pid_5827/cgroup.procs: No such file or directory
,07-12 11:37:07.226  6331  6331 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,07-12 11:37:07.229  6331  6331 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-12 11:37:07.231   841  2125 I ActivityManager: Killing 6204:com.lge.clock/u0a10 (adj 15): empty #11
,07-12 11:37:07.247  6331  6331 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-12 11:37:07.250  6331  6331 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-12 11:37:07.256  6331  6331 D TelephonyAutoProfiling: [parse] Load xml
,07-12 11:37:07.272  6331  6331 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,07-12 11:37:07.272  6331  6331 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
07-12 11:37:07.281  6331  6331 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-12 11:37:07.296   841  4781 W libprocessgroup: failed to open /acct/uid_10010/pid_6204/cgroup.procs: No such file or directory
,07-12 11:37:07.314  2630  2630 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:07.322  2630  2630 V DownloadManager: DownloadService onCreate
07-12 11:37:07.325  2630  6374 I DownloadManager: in removeSpuriousFiles
07-12 11:37:07.327  2630  6374 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
07-12 11:37:07.328  2630  6374 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@bbeeaee on behalf of 2630
07-12 11:37:07.333  2630  6374 I DownloadManager: in trimDatabase
07-12 11:37:07.334  2630  6374 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,07-12 11:37:07.335  2630  6374 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@df2bb8f on behalf of 2630
07-12 11:37:07.347  2630  2630 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
,07-12 11:37:07.352   841  4781 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6376 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-12 11:37:07.369  2630  2630 V DownloadManager: DownloadService onStartCommand
,07-12 11:37:07.372  2630  6375 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,07-12 11:37:07.374  2630  6375 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1a32c7fa on behalf of 2630
07-12 11:37:07.382  6353  6353 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
07-12 11:37:07.388   841  1952 I ActivityManager: Killing 6107:com.android.gallery3d/u0a23 (adj 15): empty #11
07-12 11:37:07.388  6353  6353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
,07-12 11:37:07.483   841  1634 W libprocessgroup: failed to open /acct/uid_10023/pid_6107/cgroup.procs: No such file or directory
,07-12 11:37:07.491  1328  1328 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
07-12 11:37:07.495  1368  1368 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
07-12 11:37:07.495  1368  1368 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
07-12 11:37:07.498  1368  1368 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
,07-12 11:37:07.502  6353  6353 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
07-12 11:37:07.503  6353  6353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
07-12 11:37:07.504  6353  6353 V [BNRBootReceiver]: Boot Receiver Return
07-12 11:37:07.505  6353  6353 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-12 11:37:07.506   841  1906 I ActivityManager: Killing 6079:com.google.android.music:main/u0a81 (adj 15): empty #11
07-12 11:37:07.510  2630  2630 V DownloadManager: DownloadService onDestroy
07-12 11:37:07.542  6376  6376 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,07-12 11:37:07.543  6376  6376 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
07-12 11:37:07.607   841   861 W libprocessgroup: failed to open /acct/uid_10081/pid_6079/cgroup.procs: No such file or directory
,07-12 11:37:07.613  2827  2827 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:7
07-12 11:37:07.614  6376  6376 V DrmService: Service onCreate
,07-12 11:37:07.615  6376  6376 D DrmService: Received new request = 2
,07-12 11:37:07.619   274  1298 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 841
07-12 11:37:07.621  6376  6395 I DrmSntpClient: Start Sync process
07-12 11:37:07.621  6376  6395 D DrmSntpClient: Server : 0
07-12 11:37:07.621   274  1298 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-12 11:37:07.622   274  1298 V voice   : voice_set_parameters: enter: screen_state=off
07-12 11:37:07.622   274  1298 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
07-12 11:37:07.622   274  1298 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-12 11:37:07.622   274  1298 V voice   : voice_set_parameters: exit with code(0)
07-12 11:37:07.622   274  1298 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
07-12 11:37:07.622   274  1298 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-12 11:37:07.622   274  1298 V msm8974_platform: platform_set_parameters: exit with code(0)
07-12 11:37:07.622   274  1298 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-12 11:37:07.622   274  1298 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-12 11:37:07.622   274  1298 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-12 11:37:07.624  2827  2827 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-12 11:37:07.627   841  1312 D WifiController: CMD_SCREEN_OFF 
07-12 11:37:07.629   841  1312 D WifiController: shouldWifiStayAwake TRUE
,07-12 11:37:07.633  2827  2827 D WeatherAncestor: connectivity changed - connection : true
07-12 11:37:07.633  2827  2827 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-12 11:37:07.633  2827  2827 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:7
07-12 11:37:07.634  2827  2827 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
07-12 11:37:07.634  2827  2827 D WeatherService: 2 : shouldTimeTickRegistered : false
07-12 11:37:07.636  6376  6395 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:07.636  6376  6395 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:07.636  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
07-12 11:37:07.637   841   972 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
07-12 11:37:07.639  6376  6395 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:07.639  6376  6395 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:07.639   269  1050 E BandwidthController: [LG DATA] No such appUid: 10051
07-12 11:37:07.639   269  1050 D DnsProxyListener: App 10051 tries DNS query. Accept family:0 protocol:0
07-12 11:37:07.639   269  6396 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:07.640   269  6396 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:07.640   269  6396 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:07.640   269  6396 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:07.672   269  6396 D libc-netbsd: res_queryN name = xxxxx succeed
,07-12 11:37:07.673  6376  6395 I System.out: propertyValue:false
07-12 11:37:07.694  6376  6395 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
,07-12 11:37:07.701   281   281 V ILGDrmService: eDRM_SetDRMTime +++
07-12 11:37:07.707   841  1919 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,07-12 11:37:07.718  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:false
07-12 11:37:07.726   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:07.726   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-18ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:07.727   281   281 I LGDRM   : [DRM] SET TIME : YR=2016, MON=7, DAY=12
,07-12 11:37:07.727   281   281 I LGDRM   : [DRM] SET TIME : HR=9, MIN=37, SEC=6
07-12 11:37:07.728  1860  2026 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-12 11:37:07.729   841  5963 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-12 11:37:07.731  1860  2026 D LEDService: stopPatternFlashing()
07-12 11:37:07.731  1860  2026 D qdlights: set_light_notifications: 0,0,0,0,3
07-12 11:37:07.733  1860  2026 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-12 11:37:07.733  1860  2026 D qdlights: set_light_notifications: 0,0,0,0,3
07-12 11:37:07.734  1860  1896 D WifiServiceExtension: isInternetCheckAvailable return false
07-12 11:37:07.738  1860  2026 I LEDService: updateLightsLocked : turn on led
07-12 11:37:07.742  1860  1860 D VolumeVibrator: clear
,07-12 11:37:07.743   281   281 V ILGDrmService: eDRM_SetDRMTime ---
07-12 11:37:07.744  6376  6395 I DrmSntpClient: Synched
07-12 11:37:07.745  6376  6376 D DrmService: Completed !! request = 2
07-12 11:37:07.745  6376  6376 D DrmService: Request count = 0
07-12 11:37:07.745  1835  1835 D LNfcService: action : android.intent.action.SCREEN_OFF
07-12 11:37:07.746  6376  6376 V DrmService: Service onDestroy
07-12 11:37:07.746  1860  1860 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
07-12 11:37:07.748  1860  2026 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
07-12 11:37:07.749  1860  2026 E LEDService: Can't handle this request of patternId:0
07-12 11:37:07.749  1860  2026 D LEDHandler: RESTART MSG
07-12 11:37:07.749  1835  2160 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
07-12 11:37:07.753  5331  6399 I iu.SyncManager: SYNC; picasa accounts
07-12 11:37:07.765  5331  5331 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-12 11:37:07.774  1946  1946 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
07-12 11:37:07.777  5331  5331 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-12 11:37:07.788  1776  1776 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
07-12 11:37:07.806  5331  6399 I iu.UploadsManager: num queued entries: 0
07-12 11:37:07.807  5331  6399 I iu.UploadsManager: num updated entries: 0
07-12 11:37:07.809  5331  6399 I iu.SyncManager: NEXT; no task
,07-12 11:37:07.817  5331  6401 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-12 11:37:07.817  5331  6401 D SchedPeriodicTask: Scheduled AdAttestation task.
07-12 11:37:07.840  2827  2827 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:37:7
,07-12 11:37:07.843  2827  2827 D WeatherService: 2 : ACTION screen off
07-12 11:37:07.845  2827  2827 D WeatherService: 2 : TimeTick Receiver Unregister
07-12 11:37:07.846  2827  2827 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:37:7
07-12 11:37:07.851  3867  3867 D AppCleanupService: android.intent.action.SCREEN_OFF
07-12 11:37:07.858  3867  6405 D AppCleanupService: AppUsageStatsSaveTask
,07-12 11:37:07.867  1835  2693 E NxpNfcJni: getReconnectState = 0x0
07-12 11:37:07.875  1835  2160 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-12 11:37:07.875  1835  2160 D LCardEmulationManager: getDefaultRoute
,07-12 11:37:07.878  1835  2160 D LNfcService: isRequireNfcCRouting() return true
07-12 11:37:07.885  1835  2160 D LNfcService: isHCERoutingtoHost() return : true
07-12 11:37:07.885  1835  2160 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-12 11:37:07.885  1835  2160 D NfcService: mEnableLPD: true
07-12 11:37:07.885  1835  2160 D NfcService: mEnableReader: false
07-12 11:37:07.885  1835  2160 D NfcService: mEnableHostRouting: true
07-12 11:37:07.885  1835  2160 D NfcService: newParams.techmask= mTechMask: 0
07-12 11:37:07.885  1835  2160 D NfcService: mEnableLPD: true
07-12 11:37:07.885  1835  2160 D NfcService: mEnableReader: false
07-12 11:37:07.885  1835  2160 D NfcService: mEnableHostRouting: true
07-12 11:37:07.885  1835  2160 D NfcService: screenState= 1
,07-12 11:37:07.935   841  1934 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6406 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-12 11:37:07.945  1835  2693 E NxpNfcJni: getReconnectState = 0x0
07-12 11:37:07.984   841  1906 I ActivityManager: Killing 6225:com.android.calendar/u0a13 (adj 15): empty #11
,07-12 11:37:08.065   841  2012 W libprocessgroup: failed to open /acct/uid_10013/pid_6225/cgroup.procs: No such file or directory
,07-12 11:37:08.086   841   841 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:08.086   841   841 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 11:37:08.086   841   841 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
,07-12 11:37:08.194  6406  6406 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-12 11:37:08.208   841  1634 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6424 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,07-12 11:37:08.208   841  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3a94d201 type 2 when 158618 com.android.systemui} when 158618
07-12 11:37:08.252  5331  5331 I art     : Explicit concurrent mark sweep GC freed 21154(1596KB) AllocSpace objects, 37(592KB) LOS objects, 24% free, 14MB/19MB, paused 997us total 117.266ms
,07-12 11:37:08.283  5331  6441 I CheckinService: Disabling old GoogleServicesFramework version
,07-12 11:37:08.337  6424  6424 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-12 11:37:08.339  6424  6424 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-12 11:37:08.376  5331  6444 I CheckinChimeraService: Checking schedule, now: 1468316228375 next: 1468314653045
07-12 11:37:08.376  5331  6444 I CheckinChimeraService: active receiver: enabled
,07-12 11:37:08.390   293   357 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-12 11:37:08.396  5331  6444 I CheckinChimeraService: Preparing to send checkin request
07-12 11:37:08.397  5331  6444 I EventLogChimeraService: Accumulating logs since 1468314908728
07-12 11:37:08.407  6424  6424 I MultiDex: VM with version 2.1.0 has multidex support
07-12 11:37:08.407  6424  6424 I MultiDex: install
07-12 11:37:08.408  6424  6424 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:37:08.461  6424  6424 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 11:37:08.529  6424  6424 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-12 11:37:08.530  6424  6424 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@285194b4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-12 11:37:08.531  6424  6424 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-12 11:37:08.532  6424  6424 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
07-12 11:37:08.532  6424  6424 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
07-12 11:37:08.542  6424  6424 D ChimeraCfgMgr: Reading stored module config
,07-12 11:37:08.592  5353  5502 I art     : Explicit concurrent mark sweep GC freed 2227(100KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 4.969ms total 87.603ms
,07-12 11:37:08.594  6406  6453 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-12 11:37:08.594  6406  6453 I Babel_SMS: MmsConfig.loadMmsSettings
07-12 11:37:08.621  6406  6453 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-12 11:37:08.622  6406  6453 I Babel_SMS: MmsConfig.loadFromDatabase
,07-12 11:37:08.652  6424  6440 W art     : Suspending all threads took: 8.073ms
,07-12 11:37:08.674  6424  6440 I art     : Background sticky concurrent mark sweep GC freed 18936(924KB) AllocSpace objects, 2(32KB) LOS objects, 6% free, 10MB/11MB, paused 15.940ms total 75.921ms
,07-12 11:37:08.708  6406  6453 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-12 11:37:08.708  6406  6453 I Babel_SMS: MmsConfig.loadFromResources
07-12 11:37:08.710  6406  6453 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-12 11:37:08.710  6406  6453 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,07-12 11:37:08.759  6424  6448 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-12 11:37:08.773   841  2125 I ActivityManager: Process com.lge.email (pid 6128) has died
,07-12 11:37:08.798  6424  6440 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3c0
,07-12 11:37:08.815  6406  6406 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
07-12 11:37:08.815  6406  6406 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
07-12 11:37:08.816  6406  6406 D SensorManager: found sensor: Motion Accel, handle=46
07-12 11:37:08.868  6424  6424 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
07-12 11:37:08.868  6424  6424 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,07-12 11:37:08.884  6424  6440 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3b0
07-12 11:37:08.912  6406  6406 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 11:37:08.924  6424  6440 I art     : Background partial concurrent mark sweep GC freed 1347(229KB) AllocSpace objects, 1(151KB) LOS objects, 39% free, 10MB/17MB, paused 5.979ms total 124.776ms
07-12 11:37:08.926  6406  6406 I Babel_Crash: startup - clean
07-12 11:37:08.943  6406  6420 I art     : CheckpointMarkThreadRoots callback created = 0xb042d450
,07-12 11:37:09.019  6406  6458 I Babel   : deleted: false for 0
,07-12 11:37:09.068   274   274 D WVCdm   : Instantiating CDM.
,07-12 11:37:09.071  5331  6444 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
07-12 11:37:09.074   274  1353 I WVCdm   : CdmEngine::OpenSession
07-12 11:37:09.075   274  1353 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
07-12 11:37:09.084  6424  6442 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:09.084  6424  6442 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-12 11:37:09.084  6424  6442 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:09.084  6424  6442 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:09.084   269  1050 E BandwidthController: [LG DATA] No such appUid: 10006
07-12 11:37:09.084   269  1050 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-12 11:37:09.088   269  6465 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:09.088   269  6465 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:09.088   269  6465 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:09.089   269  6465 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:09.089   269  6465 D libc-netbsd: res_queryN name = xxxxx succeed
07-12 11:37:09.089  6424  6442 I System.out: propertyValue:false
07-12 11:37:09.106  6406  6420 I art     : CheckpointMarkThreadRoots callback created = 0xb042d440
,07-12 11:37:09.134   841  1293 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6466 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:37:09.140  5331  6444 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
07-12 11:37:09.162  6424  6442 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:09.163  6424  6442 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:09.166   274  1353 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-12 11:37:09.167   274  1353 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
07-12 11:37:09.167   274  1353 W WVCdm   : L1 library not specified. Falling Back to L3
,07-12 11:37:09.210  6406  6406 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,07-12 11:37:09.212  6406  6406 W AudioCapabilities: Unsupported mime audio/adpcm
07-12 11:37:09.214  6406  6406 W AudioCapabilities: Unsupported mime audio/g726
07-12 11:37:09.216  6406  6406 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-12 11:37:09.217  6406  6406 W AudioCapabilities: Unsupported mime audio/wma-voice
07-12 11:37:09.220  6406  6406 W VideoCapabilities: Unsupported mime video/mjpg
07-12 11:37:09.251  6406  6406 W VideoCapabilities: Unsupported mime video/theora
,07-12 11:37:09.262   274  1353 I WVCdm   : CdmEngine::QueryKeyControlInfo
07-12 11:37:09.263   274  1298 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-12 11:37:09.263   274  1298 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-12 11:37:09.263   274  1298 I WVCdm   : CdmEngine::GenerateKeyRequest
07-12 11:37:09.277   274  1298 D WVCdm   : PrepareKeyRequest: nonce=3954297818
,07-12 11:37:09.306  6406  6406 W AudioCapabilities: Unsupported mime audio/evrc
,07-12 11:37:09.307  6406  6406 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 11:37:09.315  6406  6406 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 11:37:09.345  6406  6406 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-12 11:37:09.354  6406  6406 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 11:37:09.360  6406  6406 W AudioCapabilities: Unsupported mime audio/evrc
,07-12 11:37:09.435  6406  6406 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-12 11:37:09.475  6406  6406 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-12 11:37:09.492  6406  6406 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-12 11:37:09.504  6406  6406 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 11:37:09.508  6406  6406 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 11:37:09.521  6406  6406 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-12 11:37:09.544  6406  6406 I vclib   : onServiceConnected
07-12 11:37:09.545  6406  6406 W Babel   : Attempted to change video mute state without an active call.
,07-12 11:37:09.567  6406  6406 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
07-12 11:37:09.570  6406  6484 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:09.570  6406  6484 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:09.571  6406  6484 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:09.571  6406  6484 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:09.572   269  1050 E BandwidthController: [LG DATA] No such appUid: 10061
07-12 11:37:09.572   269  1050 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
07-12 11:37:09.572   269  6487 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:09.572   269  6487 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:09.572   269  6487 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:09.572   269  6487 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:09.573   269  6487 D libc-netbsd: res_queryN name = xxxxx succeed
,07-12 11:37:09.583  6406  6484 I System.out: propertyValue:false
07-12 11:37:09.641   243   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-12 11:37:09.642   243   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-12 11:37:09.642   243   354 W Vold    : Returning OperationFailed - no handler for errno 0
,07-12 11:37:09.646  6466  6489 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,07-12 11:37:09.663   243   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-12 11:37:09.663   243   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-12 11:37:09.663   243   354 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 11:37:09.664  6466  6489 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-12 11:37:09.672  6466  6466 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-12 11:37:09.672  6466  6466 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:37:09.672  6466  6466 I GAv4    :   adb logcat -s GAv4
,07-12 11:37:09.703  6466  6466 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:09.746   243   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-12 11:37:09.746   243   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-12 11:37:09.747   243   354 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 11:37:09.747  6466  6491 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-12 11:37:09.751  6466  6466 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
07-12 11:37:09.758   243   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-12 11:37:09.758   243   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-12 11:37:09.758   243   354 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 11:37:09.759  6466  6491 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,07-12 11:37:09.777  6466  6492 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:09.904  6406  6484 I Babel   : connection state changed from UNKNOWN to CONNECTED
,07-12 11:37:10.170   274  1353 I WVCdm   : CdmEngine::OpenSession
,07-12 11:37:10.180  6499  6499 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
07-12 11:37:10.302  6499  6499 I dex2oat : dex2oat took 118.504ms (threads: 4)
,07-12 11:37:10.321  6424  6442 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:37:10.321  6424  6442 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:37:10.321  6424  6442 I Adreno-EGL: Build Date: 03/02/15 Mon
07-12 11:37:10.321  6424  6442 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-12 11:37:10.321  6424  6442 I Adreno-EGL: Remote Branch: 
07-12 11:37:10.321  6424  6442 I Adreno-EGL: Local Patches: 
07-12 11:37:10.321  6424  6442 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:37:10.413  6466  6466 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,07-12 11:37:10.464  6466  6466 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 898-900)
07-12 11:37:10.464  6466  6466 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:37:10.480  6466  6466 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3cdd92e4}
07-12 11:37:10.481  6466  6466 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:37:10.481  6466  6466 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:37:10.510  6466  6466 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 11:37:10.514  6466  6466 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:37:10.515  6466  6466 E SysUtils: ApplicationContext is null in ApplicationStatus
07-12 11:37:10.535  6466  6466 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-12 11:37:10.546  6466  6466 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:37:10.546  6466  6466 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:37:10.547  6466  6466 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:37:10.547  6466  6466 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:37:10.547  6466  6466 I Adreno-EGL: Build Date: 03/02/15 Mon
07-12 11:37:10.547  6466  6466 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-12 11:37:10.547  6466  6466 I Adreno-EGL: Remote Branch: 
07-12 11:37:10.547  6466  6466 I Adreno-EGL: Local Patches: 
07-12 11:37:10.547  6466  6466 I Adreno-EGL: Reconstruct Branch: 
07-12 11:37:10.580  6424  6442 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:37:10.580  6424  6442 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:37:10.580  6424  6442 I Adreno-EGL: Build Date: 03/02/15 Mon
07-12 11:37:10.580  6424  6442 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-12 11:37:10.580  6424  6442 I Adreno-EGL: Remote Branch: 
07-12 11:37:10.580  6424  6442 I Adreno-EGL: Local Patches: 
07-12 11:37:10.580  6424  6442 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:37:10.645  6424  6442 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:37:10.645  6424  6442 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:37:10.645  6424  6442 I Adreno-EGL: Build Date: 03/02/15 Mon
07-12 11:37:10.645  6424  6442 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-12 11:37:10.645  6424  6442 I Adreno-EGL: Remote Branch: 
07-12 11:37:10.645  6424  6442 I Adreno-EGL: Local Patches: 
07-12 11:37:10.645  6424  6442 I Adreno-EGL: Reconstruct Branch: 
07-12 11:37:10.655  6466  6466 I NSApplication: Starting up...
,07-12 11:37:10.684   274   274 V AudioPolicyService: registerClient() client 0xb3826d00, uid 10079
07-12 11:37:10.685  6466  6532 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-12 11:37:10.743   841  4781 I ActivityManager: Process com.lge.lgdmsclient (pid 6282) has died
,07-12 11:37:10.790  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 11:37:10.790  5651  5722 I jxcore-log: 
,07-12 11:37:10.796   841  1991 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6537 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:37:10.810  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 11:37:10.810  5651  5722 I jxcore-log: 
,07-12 11:37:10.822  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 11:37:10.822  5651  5722 I jxcore-log: 
,07-12 11:37:10.963  2322  6403 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:10.963  2322  6403 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:10.964  2322  6403 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:10.965  2322  6403 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:10.965   269  1050 E BandwidthController: [LG DATA] No such appUid: 10006
07-12 11:37:10.965   269  1050 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-12 11:37:10.965   269  6555 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:10.965   269  6555 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-12 11:37:10.966   269  6555 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:10.966   269  6555 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:11.006   269  6555 D libc-netbsd: res_queryN name = xxxxx succeed
,07-12 11:37:11.007  2322  6403 I System.out: propertyValue:false
07-12 11:37:11.071  2322  6403 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:11.071  2322  6403 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-12 11:37:11.133  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 11:37:11.133  5651  5722 I jxcore-log: 
,07-12 11:37:11.205   841   860 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6560 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-12 11:37:11.330  6560  6560 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-12 11:37:11.525   841  1906 I art     : Explicit concurrent mark sweep GC freed 23038(1111KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.352ms total 156.228ms
,07-12 11:37:11.585   274  1603 I WVCdm   : CdmEngine::CloseSession
,07-12 11:37:11.591   841  1030 D BluetoothManagerService: Message: 20
07-12 11:37:11.591   841  1030 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fd75b9f:true
07-12 11:37:11.596   274  1603 I WVCdm   : CdmEngine::OpenSession
07-12 11:37:11.611  2056  2071 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
,07-12 11:37:11.632  2056  5778 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
,07-12 11:37:11.669   274  1353 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-12 11:37:11.671   274  1353 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-12 11:37:11.671   274  1353 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-12 11:37:11.671   274  1353 I WVCdm   : CdmEngine::GenerateKeyRequest
07-12 11:37:11.676   274  1353 D WVCdm   : PrepareKeyRequest: nonce=3004034862
07-12 11:37:11.702   841  1991 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6580 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-12 11:37:11.986  6580  6580 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
07-12 11:37:11.989   841  2012 I ActivityManager: Killing 6264:com.qualcomm.timeservice/1000 (adj 15): empty #11
,07-12 11:37:12.105   841  1991 W libprocessgroup: failed to open /acct/uid_1000/pid_6264/cgroup.procs: No such file or directory
07-12 11:37:12.106  2827  2827 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 11:37:12
,07-12 11:37:12.108  2827  2827 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-12 11:37:12.109  2827  2827 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
07-12 11:37:12.110  2827  2827 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 11:37:12
07-12 11:37:12.110  2827  2827 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
07-12 11:37:12.110  2827  2827 D WeatherService: 2 : shouldTimeTickRegistered : false
07-12 11:37:12.138  1946  1946 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,07-12 11:37:12.148  6353  6353 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
07-12 11:37:12.152  6353  6353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
,07-12 11:37:12.154  1368  1368 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
07-12 11:37:12.154  1368  1368 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
07-12 11:37:12.154  1368  1368 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
07-12 11:37:12.156  1328  1328 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
07-12 11:37:12.162  6353  6353 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
07-12 11:37:12.163  6353  6353 V [BNRBootReceiver]: Boot Receiver Return
07-12 11:37:12.180  1946  2745 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,07-12 11:37:12.180  1368  1368 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
07-12 11:37:12.180  1946  2745 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
07-12 11:37:12.181  1946  2745 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
07-12 11:37:12.216  1776  2563 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
,07-12 11:37:12.227  1776  2563 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-12 11:37:12.227  1776  2563 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-12 11:37:12.236  1776  2563 V TelecomServiceImpl: getCallState : 0
,07-12 11:37:12.238  1776  1808 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-12 11:37:12.238  1776  1808 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-12 11:37:12.239  1776  1808 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-12 11:37:12.242  1368  1368 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
07-12 11:37:12.244  1368  1368 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
07-12 11:37:12.252  1946  2745 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
07-12 11:37:12.253  1946  2745 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
,07-12 11:37:12.272  2322  2322 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=c2b6b2e2-4377-4240-8e85-30a396503757
,07-12 11:37:12.407   841  1634 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6604 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:37:12.423  6560  6560 V LGMDMManager: Create singleton instance
,07-12 11:37:12.520  6560  6560 I AudioManager: getMode name:com.lge.qremote
,07-12 11:37:12.598  6604  6604 D UEI.SmartControl: Quickset Services start...
,07-12 11:37:12.601  6604  6604 I UEI.SmartControl: Manufacture = LGE
07-12 11:37:12.604  6604  6604 D UEI.SmartControl: File observer start...
07-12 11:37:12.605  6604  6604 E UEI.SmartControl: IR Port is disabled: false
07-12 11:37:12.605  6604  6604 D UEI.SmartControl: Starting file observer...
07-12 11:37:12.605  6604  6604 D UEI.SmartControl: Extracting JNI libs...
07-12 11:37:12.606  6604  6604 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-12 11:37:12.683   841  1991 I ActivityManager: Process com.lge.appbox.client (pid 6311) has died
,07-12 11:37:12.714  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 11:37:12.714  5651  5722 I jxcore-log: 
,07-12 11:37:12.763   841  2012 I ActivityManager: Process com.google.android.setupwizard (pid 6331) has died
,07-12 11:37:12.768  1946  1946 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
07-12 11:37:12.772  1946  2091 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
07-12 11:37:12.772  1946  2091 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
07-12 11:37:12.772  1946  2091 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
07-12 11:37:12.774  1946  2091 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
07-12 11:37:12.774  1946  2091 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
,07-12 11:37:12.809  6604  6604 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-12 11:37:12.810  6604  6604 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-12 11:37:12.810  6604  6604 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-12 11:37:12.846  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 11:37:12.846  5651  5722 I jxcore-log: 
,07-12 11:37:12.856  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 11:37:12.856  5651  5722 I jxcore-log: 
07-12 11:37:12.857  6604  6604 I UEI.SmartControl: --- Selecting new region: 2
07-12 11:37:12.858  6604  6604 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
07-12 11:37:12.878  6604  6604 D UEI.SmartControl: Platform has CIR...
,07-12 11:37:12.881  6604  6604 D UEI.SmartControl: NO CIR support, need to check package...
,07-12 11:37:12.882  6604  6604 I UEI.SmartControl: Model: LG-D722 uses JNI
07-12 11:37:12.886  6604  6604 D UEI.SmartControl: QS Service created
07-12 11:37:12.902  2322  2350 I art     : Explicit concurrent mark sweep GC freed 68433(4MB) AllocSpace objects, 31(494KB) LOS objects, 40% free, 14MB/24MB, paused 1.936ms total 120.460ms
07-12 11:37:12.903  5331  6601 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-12 11:37:12.931  6604  6604 E UEI.SmartControl: QS start get config
,07-12 11:37:12.946  2322  2739 W GCoreFlp: No location to return for getLastLocation()
07-12 11:37:12.973  6604  6604 D UEI.SmartControl: Loading JNI Libs...
07-12 11:37:12.975  6604  6604 D UEI.SmartControl:  configuring local db...
,07-12 11:37:13.035  5331  6578 D UdcContextInitService: registered all accounts: true
07-12 11:37:13.037  2322  2729 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-12 11:37:13.056  2322  2724 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-12 11:37:13.190   841  1919 I ActivityManager: Process com.lge.drmservice (pid 6376) has died
,07-12 11:37:13.255  6604  6604 D UEI.SmartControl:  ---- Has DB8: true
,07-12 11:37:13.264  6604  6604 D UEI.SmartControl: QS start statue = true Error code = 0
07-12 11:37:13.265  6604  6604 D UEI.SmartControl: QS version = v2.7.11.1_RC1
07-12 11:37:13.266  6604  6604 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
07-12 11:37:13.267  5353  5502 I art     : Explicit concurrent mark sweep GC freed 2875(113KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 45.805ms total 174.927ms
07-12 11:37:13.270  6604  6604 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
07-12 11:37:13.280  6604  6604 W irrc_jni: IRRCPlayer_nativeInit ++ 
07-12 11:37:13.280  6604  6604 D irrcClient: IrrcClient ++ 
07-12 11:37:13.280  6604  6604 D irrcClient: getIrrcService ++ 
,07-12 11:37:13.280  6604  6604 D irrcClient: getIrrcService -- 
07-12 11:37:13.280  6604  6604 D irrcClient: IrrcClient -- 
07-12 11:37:13.280  6604  6604 W irrc_jni: IRRCPlayer_nativeInit -- 
07-12 11:37:13.289  6604  6604 D UEI.SmartControl: Services init done
07-12 11:37:13.290  6604  6627 I UEI.SmartControl: Device manager: loading config....
07-12 11:37:13.295  6604  6627 D UEI.SmartControl: Config is loaded...
,07-12 11:37:13.315  6604  6626 D UEI.SmartControl:  ----- QS SDK is ready!!!
07-12 11:37:13.316  6604  6626 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-12 11:37:13.325  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 11:37:13.325  5651  5722 I jxcore-log: 
07-12 11:37:13.357  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 11:37:13.357  5651  5722 I jxcore-log: 
,07-12 11:37:13.365  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 11:37:13.365  5651  5722 I jxcore-log: 
07-12 11:37:13.373  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 11:37:13.373  5651  5722 I jxcore-log: 
,07-12 11:37:13.395   293   357 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-12 11:37:13.399  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 11:37:13.399  5651  5722 I jxcore-log: 
07-12 11:37:13.429  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 11:37:13.429  5651  5722 I jxcore-log: 
,07-12 11:37:13.443   841  1908 I ActivityManager: Process com.google.android.apps.magazines (pid 6466) has died
,07-12 11:37:13.448  2032  2032 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-12 11:37:13.452  1776  1776 I PhoneApp: onTrimMemory: 10
07-12 11:37:13.453  1776  1776 I PhoneApp: trim memory
07-12 11:37:13.458  6604  6604 D UEI.SmartControl: QS Service init finished
,07-12 11:37:13.461  6604  6604 D UEI.SmartControl: QS Service version name: 0.1.73
07-12 11:37:13.462  6604  6604 D UEI.SmartControl: QS Service version code: 1073
07-12 11:37:13.463  6604  6604 D UEI.SmartControl: Service requested: Control
07-12 11:37:13.464  5331  6578 I GAv4-SVC: Google Analytics 9.2.56 is starting up.
07-12 11:37:13.470  6604  6604 D UEI.SmartControl: Service.onTrimMemory: 10
07-12 11:37:13.471  6604  6620 D UEI.SmartControl: -----IControl: 11
07-12 11:37:13.472  6604  6620 D UEI.SmartControl: Caller: com.lge.qremote
07-12 11:37:13.473  6604  6620 D UEI.SmartControl: ------------ IControl registerCallback...
07-12 11:37:13.474  6604  6620 I UEI.SmartControl: Registering callback...
07-12 11:37:13.475  6604  6604 E UEI.SmartControl: Setup service releasing memory...
07-12 11:37:13.480  6604  6619 D UEI.SmartControl: -----IControl: 19
,07-12 11:37:13.481  6604  6619 D UEI.SmartControl: Caller: com.lge.qremote
07-12 11:37:13.482  6604  6619 I UEI.SmartControl: Registering Services Ready callback...
07-12 11:37:13.483  6604  6619 I UEI.SmartControl: Notify client services are ready...
07-12 11:37:13.486  6604  6620 D UEI.SmartControl: -----IControl: 8
07-12 11:37:13.487  6604  6620 D UEI.SmartControl: Caller: com.lge.qremote
07-12 11:37:13.494  6560  6560 I AudioManager: getMode name:com.lge.qremote
,07-12 11:37:13.536  6604  6604 I art     : Explicit concurrent mark sweep GC freed 10559(755KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 364us total 58.650ms
07-12 11:37:13.536  6604  6604 D UEI.SmartControl: Internal service binding...
,07-12 11:37:13.583  6560  6560 I AudioManager: getMode name:com.lge.qremote
,07-12 11:37:13.612  6560  6560 I AudioManager: getMode name:com.lge.qremote
,07-12 11:37:13.632  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 11:37:13.632  5651  5722 I jxcore-log: 
,07-12 11:37:13.641  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 11:37:13.641  5651  5722 I jxcore-log: 
07-12 11:37:13.686  5651  5722 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 11:37:13.686  5651  5722 I jxcore-log: 
,07-12 11:37:13.700  2056  2071 D BluetoothAdapterService(37326222): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1295c54
07-12 11:37:13.702  5651  5722 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-12 11:37:13.706  5651  5722 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-12 11:37:13.706  5651  5722 I jxcore-log: 
07-12 11:37:13.809   274  1298 I WVCdm   : CdmEngine::CloseSession
,07-12 11:37:13.824  2322  2724 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-12 11:37:13.830  5651  5722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 11:37:13.830  5651  5722 I jxcore-log: 
07-12 11:37:13.832  5651  5722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 11:37:13.832  5651  5722 I jxcore-log: 
07-12 11:37:13.833  5651  5722 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 11:37:13.833  5651  5722 I jxcore-log: 
,07-12 11:37:13.848  2322  2724 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
07-12 11:37:13.849  2322  2724 V BaseAppContext: GmsRequestQueue started.
07-12 11:37:13.873   274  1603 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-12 11:37:13.874   274   274 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-12 11:37:13.874   274   274 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-12 11:37:13.874   274   274 I WVCdm   : CdmEngine::GenerateKeyRequest
07-12 11:37:13.879   274   274 D WVCdm   : PrepareKeyRequest: nonce=719803658
07-12 11:37:13.879  2322  6638 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:13.879  2322  6638 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:13.881  2322  6638 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:13.881  2322  6638 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:13.884   269  1050 E BandwidthController: [LG DATA] No such appUid: 10006
07-12 11:37:13.884   269  1050 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-12 11:37:13.884   269  6643 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:13.884   269  6643 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:13.884   269  6643 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:13.885   269  6643 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:13.885   269  6643 D libc-netbsd: res_queryN name = xxxxx succeed
,07-12 11:37:13.886  2322  6638 I System.out: propertyValue:false
07-12 11:37:13.937  2322  6642 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-12 11:37:13.937  2322  6633 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-12 11:37:13.959  2322  6642 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-12 11:37:13.960  2322  6633 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-12 11:37:13.998  2322  6642 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:37:13.999  2322  6633 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-12 11:37:13.999  2322  6633 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
07-12 11:37:14.020  2322  6633 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:37:14.067   841  1906 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:14.120  2322  6633 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-12 11:37:14.120  2322  6633 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-12 11:37:14.120  2322  6633 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:14.120  2322  6633 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:14.120   269  1050 E BandwidthController: [LG DATA] No such appUid: 10006
07-12 11:37:14.120   269  1050 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-12 11:37:14.122   269  6644 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:14.122   269  6644 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:14.122   269  6644 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:14.122   269  6644 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:14.153   269  6644 D libc-netbsd: res_queryN name = xxxxx succeed
,07-12 11:37:14.154  2322  6633 I System.out: propertyValue:false
07-12 11:37:14.212  6424  6462 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:37:14.212  6424  6462 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:37:14.212  6424  6462 I Adreno-EGL: Build Date: 03/02/15 Mon
07-12 11:37:14.212  6424  6462 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-12 11:37:14.212  6424  6462 I Adreno-EGL: Remote Branch: 
07-12 11:37:14.212  6424  6462 I Adreno-EGL: Local Patches: 
07-12 11:37:14.212  6424  6462 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:37:14.230  2322  2724 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-12 11:37:14.320  6424  6462 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:37:14.320  6424  6462 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:37:14.320  6424  6462 I Adreno-EGL: Build Date: 03/02/15 Mon
07-12 11:37:14.320  6424  6462 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-12 11:37:14.320  6424  6462 I Adreno-EGL: Remote Branch: 
07-12 11:37:14.320  6424  6462 I Adreno-EGL: Local Patches: 
07-12 11:37:14.320  6424  6462 I Adreno-EGL: Reconstruct Branch: 
07-12 11:37:14.373  6424  6462 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-12 11:37:14.373  6424  6462 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 11:37:14.373  6424  6462 I Adreno-EGL: Build Date: 03/02/15 Mon
07-12 11:37:14.373  6424  6462 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-12 11:37:14.373  6424  6462 I Adreno-EGL: Remote Branch: 
07-12 11:37:14.373  6424  6462 I Adreno-EGL: Local Patches: 
07-12 11:37:14.373  6424  6462 I Adreno-EGL: Reconstruct Branch: 
,07-12 11:37:14.455  5331  6444 I CheckinUtil: Classify the device as Phone.
,07-12 11:37:14.467   841  2125 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:14.532  5331  6444 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:14.532  5331  6444 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:14.533  5331  6444 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:14.533  5331  6444 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:14.533   269  1050 E BandwidthController: [LG DATA] No such appUid: 10006
07-12 11:37:14.533   269  1050 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-12 11:37:14.533   269  6653 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:14.533   269  6653 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:14.534   269  6653 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:14.534   269  6653 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:14.534   269  6653 D libc-netbsd: res_queryN name = xxxxx succeed
07-12 11:37:14.535  5331  6444 I System.out: propertyValue:false
,07-12 11:37:14.631  5331  6444 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:14.631  5331  6444 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-12 11:37:14.658   841  1634 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:14.699  5331  6444 I CheckinTask: Sending checkin request (11369 bytes)
,07-12 11:37:14.855   841  1906 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:15.050   841  1867 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:15.121  5331  6444 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,07-12 11:37:15.124  5331  6444 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-12 11:37:15.277   841  2080 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-12 11:37:15.278  5331  6444 I CheckinUtil: Classify the device as Phone.
,07-12 11:37:15.305  5331  6444 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-12 11:37:15.312  5331  6444 I CheckinChimeraService: Checking schedule, now: 1468316235311 next: 1468843484305
07-12 11:37:15.312  5331  6444 I CheckinChimeraService: active receiver: disabled
,07-12 11:37:15.344  5331  5331 D CheckinChimeraService: Recording last checkin time for package unspecified as 1468316235344
07-12 11:37:15.429   841  1906 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6665 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,07-12 11:37:15.452   301   301 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.875ms
,07-12 11:37:15.473   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.547ms
,07-12 11:37:15.494   301   301 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.449ms
,07-12 11:37:15.514   841  4781 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-12 11:37:15.642  6665  6665 D PhoneMonitor: Register our PhoneStateListener
,07-12 11:37:15.789   841  2012 I art     : Explicit concurrent mark sweep GC freed 18126(843KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.086ms total 140.120ms
,07-12 11:37:15.819   841  2080 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-12 11:37:15.819  6665  6665 V SetupWizard: Connected to Gservices successfully
,07-12 11:37:15.845  6665  6665 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-12 11:37:15.845  6665  6665 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,07-12 11:37:15.847  6665  6665 D TelephonyAutoProfiling: [parse] Load xml
07-12 11:37:15.849   841   860 I ActivityManager: Killing 6537:com.android.chrome/u0a48 (adj 15): empty #11
07-12 11:37:15.852  6665  6665 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-12 11:37:15.853  6665  6665 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,07-12 11:37:15.869  6665  6665 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,07-12 11:37:15.915   841  1908 W libprocessgroup: failed to open /acct/uid_10048/pid_6537/cgroup.procs: No such file or directory
,07-12 11:37:15.944  2322  6692 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-12 11:37:15.944  2322  6691 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:15.945  2322  6691 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-12 11:37:15.945  2322  6691 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-12 11:37:15.945  2322  6691 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:15.946   269  1050 E BandwidthController: [LG DATA] No such appUid: 10006
07-12 11:37:15.946   269  1050 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-12 11:37:15.947   269  6693 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-12 11:37:15.947   269  6693 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-12 11:37:15.947   269  6693 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-12 11:37:15.947   269  6693 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-12 11:37:15.948   269  6693 D libc-netbsd: res_queryN name = xxxxx succeed
07-12 11:37:15.948  2322  6691 I System.out: propertyValue:false
07-12 11:37:16.009  2322  6691 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-12 11:37:16.009  2322  6691 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-12 11:37:16.092   274  1353 I WVCdm   : CdmEngine::CloseSession
,07-12 11:37:16.096   274  1353 I WVCdm   : L3 Terminate.
,07-12 11:37:16.150  2322  2724 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,07-12 11:37:16.224  5331  5417 V UdcCtxListenerSrv: handle intent
,07-12 11:37:18.291  6604  6628 D UEI.SmartControl: Internal timer expired: 1
,07-12 11:37:18.400   293   357 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-12 11:37:18.483  1368  1368 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-12 11:37:18.494  1909  1909 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
07-12 11:37:18.516   841  1285 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-12 11:37:18.564  1368  1368 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,07-12 11:37:18.578  1946  1946 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-12 11:37:18.593  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
07-12 11:37:18.593  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
07-12 11:37:18.599  1946  1946 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-12 11:37:18.610  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
07-12 11:37:18.610  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
07-12 11:37:18.610  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
07-12 11:37:18.610  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
07-12 11:37:18.611  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
07-12 11:37:18.611  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
07-12 11:37:18.611  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
07-12 11:37:18.612  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
07-12 11:37:18.612  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
07-12 11:37:18.612  1946  1946 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,07-12 11:37:18.612  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
07-12 11:37:18.613  1368  1368 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-12 11:37:18.694  1946  1946 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,07-12 11:37:18.702   841   841 D administrator: Handling package changes for user 0
07-12 11:37:18.713   841  1952 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6723 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-12 11:37:18.792  6406  6406 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-12 11:37:18.792  6406  6406 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-12 11:37:18.800  6406  6721 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
07-12 11:37:18.897  6723  6723 I AppUp4:AppBoxCP: onCreate
,07-12 11:37:18.906  6723  6723 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-12 11:37:18.913  6406  6406 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 11:37:18.928  6723  6723 I AppUp4:DB:  setFingerPrint start
,07-12 11:37:18.928  6723  6723 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
07-12 11:37:18.944  6723  6723 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
07-12 11:37:18.944  6723  6723 I AppUp4:DB:  SDK version = 21
,07-12 11:37:18.944  6723  6723 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-12 11:37:18.946  6723  6723 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-12 11:37:18.966  6723  6723 I AppUp4:CustModeStarterReceiver: onReceive
07-12 11:37:18.966  6723  6723 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,07-12 11:37:18.974  6723  6723 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3ea72224
07-12 11:37:18.974  6723  6723 D AppUp4:CustFacade: isCustomizationCompleted : false
07-12 11:37:18.979  6723  6723 D AppUp4:CustFacade: isSimDevice : true
,07-12 11:37:18.980  6723  6723 D AppUp4:CustModeStarterReceiver: begin check event
07-12 11:37:18.981  6723  6723 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-12 11:37:19.003  6406  6406 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-12 11:37:19.004  6406  6406 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-12 11:37:19.053   841  1906 I ActivityManager: Process com.google.android.apps.plus (pid 6143) has died
,07-12 11:37:19.100   841   861 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6747 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-12 11:37:19.169  6747  6747 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:37:19.169  6747  6747 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-12 11:37:19.169  6747  6747 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-12 11:37:19.171   841   972 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:37:19.217   841   841 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,07-12 11:37:19.226   841   841 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-12 11:37:19.228   841   841 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,07-12 11:37:19.239   841   841 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
07-12 11:37:19.244   841  4781 I ActivityManager: Process com.lge.clock (pid 6580) has died
,07-12 11:37:19.273   841   841 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
07-12 11:37:19.273   841   841 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1fac62e9
,07-12 11:37:19.333   841  2012 I ActivityManager: Process com.lge.qremote (pid 6560) has died
07-12 11:37:19.335  6604  6604 D UEI.SmartControl: Service.onUnbind: IControl
07-12 11:37:19.336  6604  6604 D UEI.SmartControl: Service.onDestroy
07-12 11:37:19.336  6604  6604 D UEI.SmartControl: Shutdown IRRCPlayer... 
,07-12 11:37:19.355  6604  6604 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
07-12 11:37:19.355  6604  6604 D irrcClient: ~IrrcClient ++ 
,07-12 11:37:19.355  6604  6604 D irrcClient: ~IrrcClient -- 
07-12 11:37:19.355  6604  6604 W irrc_jni: IRRCPlayer_nativeFinalize -- 
07-12 11:37:19.355  6604  6604 D UEI.SmartControl: Blaster closed
07-12 11:37:19.355  6604  6604 D UEI.SmartControl: Blaster closed
07-12 11:37:19.355  6604  6604 D UEI.SmartControl: Shut down QS...
07-12 11:37:19.356  6604  6604 D UEI.SmartControl: Stopped file observer...
07-12 11:37:19.358  6604  6604 I UEI.SmartControl: QS lib stop result = true
07-12 11:37:19.359  6604  6604 D UEI.SmartControl: QS shutdown complete
07-12 11:37:19.375  6747  6747 I AppConfig: Total System Memory = 906309632
,07-12 11:37:19.380  6747  6747 I GalleryUtils: Application Heap = 96 MB
07-12 11:37:19.388   841   972 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,07-12 11:37:19.391  6747  6747 I AppConfig: App Tier : NOT_DEF
07-12 11:37:19.401  6747  6747 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,07-12 11:37:19.519   841  2125 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6771 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,07-12 11:37:19.527  1946  1946 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-12 11:37:19.558  2322  2322 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-12 11:37:19.597  6771  6771 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:37:19.598  6771  6771 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-12 11:37:19.599  6771  6771 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,07-12 11:37:19.601  6771  6771 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,07-12 11:37:19.601  6771  6771 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-12 11:37:19.630   841   972 D LocationProviderProxy: applying state to connected service
,07-12 11:37:19.729  6771  6771 I SystemConfig: BUILD Country: EU
07-12 11:37:19.729  6771  6771 I SystemConfig: BUILD Operator: OPEN
,07-12 11:37:19.861   841  1293 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6790 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,07-12 11:37:19.871  6771  6788 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-12 11:37:19.872  6771  6788 I SystemConfig: existFile = false
07-12 11:37:19.872  6771  6788 I SystemConfig: canReadFile = false
07-12 11:37:19.872  6771  6788 I SystemConfig: systemFeature RCS result false
07-12 11:37:19.872  6771  6788 D SystemConfig: refreshRcsSupport() :false
,07-12 11:37:19.944  6790  6790 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-12 11:37:19.969  6790  6790 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-12 11:37:19.969  6790  6790 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-12 11:37:19.969  6790  6790 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-12 11:37:19.969  6790  6790 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-12 11:37:19.969  6790  6790 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,07-12 11:37:20.014   841  1906 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6810 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:37:20.173   841  1919 I ActivityManager: Process com.google.android.gms.unstable (pid 6424) has died
,07-12 11:37:20.353  6810  6810 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
,07-12 11:37:20.546  6810  6810 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(171): No need to run daily hygiene.
,07-12 11:37:20.570  6810  6810 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:37:20.572  6810  6810 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-12 11:37:20.589  6810  6810 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
,07-12 11:37:20.614  6810  6810 I Finsky  : [1] com.google.android.finsky.utils.bk.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,07-12 11:37:20.640  2630  2645 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
07-12 11:37:20.643  2630  2645 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1f308008 on behalf of 6810
,07-12 11:37:20.656  5353  5368 I art     : Explicit concurrent mark sweep GC freed 3214(127KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 364us total 28.353ms
,07-12 11:37:20.677  6810  6810 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1226): Installer kick - no action, not running yet
,07-12 11:37:20.680  6810  6810 I Finsky  : [1] com.google.android.finsky.j.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-12 11:37:20.681  6810  6810 I Finsky  : [1] com.google.android.finsky.j.j.run(214): Finished loading 1 libraries.
07-12 11:37:20.685  6810  6810 I Finsky  : [1] com.google.android.finsky.c.l.a(270): result=false type=4
07-12 11:37:20.726  6810  6810 I Finsky  : [1] com.google.android.finsky.services.bc.a(1050): Restore complete with 0 success and 0 failed.
,07-12 11:37:20.740  5331  6853 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-12 11:37:20.748   841  2012 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6854 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-12 11:37:20.840  6854  6854 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:37:20.849  5331  6853 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-12 11:37:20.859  5331  5417 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,07-12 11:37:20.968  5331  6340 I art     : Explicit concurrent mark sweep GC freed 31802(2MB) AllocSpace objects, 21(339KB) LOS objects, 24% free, 15MB/21MB, paused 11.501ms total 160.601ms
,07-12 11:37:21.013  5331  5342 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-12 11:37:21.031  5331  6885 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-12 11:37:21.201  2032  6894 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-12 11:37:21.261  2032  6894 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 61 ms] updated apps [took 61 ms] 
,07-12 11:37:21.915   841   985 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-12 11:37:21.915   841   985 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,07-12 11:37:21.915   841   985 D sensors_hal_Time: tsOffsetIs: Apps: 172351699575; DSPS: 5746282; Offset : -3014607421
07-12 11:37:22.037  5331  5400 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,07-12 11:37:22.122  5331  5400 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,07-12 11:37:23.404   293   357 I ThermalEngine: Sensor:pa_therm0:34000 mC
,07-12 11:37:24.143   841  1406 I ActivityManager: Killing 6353:com.lge.bnr/1000 (adj 15): empty #11
,07-12 11:37:24.174   841  1634 W libprocessgroup: failed to open /acct/uid_1000/pid_6353/cgroup.procs: No such file or directory

```
